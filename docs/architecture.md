# Azure Static Website Architecture

## Overview

This solution hosts a static website using Azure Blob Storage Static Website Hosting.

The website files are stored in the `$web` container within an Azure Storage Account. Azure serves the files through a public static website endpoint, allowing users to access the site over HTTPS.

## Architecture Diagram

                     User / Browser
                          |
                          |
                     HTTPS Request
                          |
                          ▼
              Azure Static Website Hosting
                          |
                          |
                Azure Storage Account
                          |
                          |
                     $web Container
                          |
      ---------------------------------------
      |                  |                  |
      ▼                  ▼                  ▼
  index.html        style.css          script.js
      |
      |
   images/
   assets/
## Components

### Resource Group

Contains all Azure resources for the project.

### Storage Account

Provides the storage service and hosts the static website.

### $web Container

Stores the website content including HTML, CSS, JavaScript, and image files.

### Static Website Endpoint

Provides public access to the hosted website.
