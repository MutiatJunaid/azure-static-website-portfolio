# Deployment Guide

## Project Goal

The objective of this project was to deploy and host a static website using Azure Blob Storage Static Website Hosting.

---

## Azure Resources Deployed

| Resource | Purpose |
|----------|---------|
| Resource Group | Organizes Azure resources |
| Storage Account | Hosts the static website |
| Blob Storage | Stores website files |
| $web Container | Stores HTML, CSS, JavaScript, and image files |

---

## Static Website Configuration

The Static Website feature was enabled on the Azure Storage Account.

Azure automatically created the `$web` container, which stores all website files.

### Configuration

- Index document: `index.html`
- Error document: `404.html`

### Screenshot

*(Add your screenshot here.)*

---

## Website Deployment

The website files were uploaded to the `$web` container using the Azure Portal.

The following files were deployed:

- HTML
- CSS
- JavaScript
- Images


<img width="960" height="403" alt="upload" src="https://github.com/user-attachments/assets/73d2d922-493b-4f30-8f3c-621973acbb1c" />


---

## Website Verification

After deployment, the website was accessed through the Azure Static Website endpoint.

The website loaded successfully and all pages rendered correctly.


<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/37e1880d-bd9c-46c3-a3e3-c7eb0c7d1332" />

---

## Outcome

The project successfully demonstrated hosting a static website using Azure Blob Storage.

The deployment required no virtual machines or web servers because Azure managed the hosting platform.
