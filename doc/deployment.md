# Deployment Guide

## Project Goal

The objective of this project is to deploy a static website using Azure Blob Storage Static Website Hosting.

---

## Step 1 – Create the Storage Account

A Storage Account was created to host the static website.
<img width="958" height="394" alt="storageacct1" src="https://github.com/user-attachments/assets/6fc135b4-8c01-4625-8055-7af9110a2796" />
<img width="960" height="404" alt="storageacct2" src="https://github.com/user-attachments/assets/9cc82025-acbd-4dc5-a4a9-1d5357ebf3bd" />


---

## Step 2 – Enable Static Website

The Static Website feature was enabled within the Storage Account.

Azure automatically created the `$web` container.

<img width="960" height="404" alt="configstaticweb2" src="https://github.com/user-attachments/assets/78c7fd64-240d-4144-968f-748b400db436" />



## Step 3 – Upload Website Files

The website files were uploaded into the `$web` container.

Files included:

- index.html
- CSS
- JavaScript
- Images

<img width="960" height="401" alt="container1" src="https://github.com/user-attachments/assets/c2fe537b-83cd-40cb-a737-8a6f2bd04bd1" />

---

## Step 4 – Verify Website

The Azure Static Website endpoint was opened in a web browser to verify successful deployment.

### Screenshot

(To be added)
<img width="960" height="540" alt="website" src="https://github.com/user-attachments/assets/69f4e3f1-251e-4d2c-90cd-0023dd6875c8" />

---

## Lessons Learned

- Learned how Azure Static Website Hosting works.
- Understood the purpose of the `$web` container.
- Successfully deployed a static website using Azure Blob Storage.
- Improved GitHub documentation skills.

---

## Future Improvements

- Configure a custom domain.
- Enable Azure CDN.
- Automate deployment using GitHub Actions.
- Deploy using Azure CLI.
