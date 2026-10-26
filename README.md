# 🔍 EasyFind — Lost & Found Management Platform

EasyFind is a web-based Lost & Found platform designed to help students report lost or found belongings, identify potential matches, and recover their items through an organized claim and barcode-based handover process.

## 🚀 Features

- **Lost Item Reporting:** Report lost belongings with descriptions and images.
- **Found Item Reporting:** Register found items to help reunite them with their owners.
- **Intelligent Item Matching:** Uses text embeddings to identify potentially matching lost and found reports.
- **Image Uploads:** Upload item images for easier identification.
- **Claim Management:** Submit claims for lost items.
- **Admin Verification:** Administrators review reports and approve legitimate claims.
- **Barcode-Based Item Handover:** Uses barcodes to support item identification and the handover process.
- **Authentication and Authorization:** Protects application features through authenticated access.
- **Email Notifications:** Sends updates about relevant actions when email integration is configured.

## 🛠️ Tech Stack

**Frontend**
- React.js
- Vite
- Tailwind CSS

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB
- Mongoose

**Additional Technologies**
- Google OAuth and JWT authentication
- Cloudinary for image storage
- Text embedding models for intelligent matching
- SMTP for email notifications

## 🔄 How It Works

1. A student reports a lost or found item.
2. The platform stores the item details and associated images.
3. The matching engine identifies potentially related reports.
4. The student submits a claim for the item.
5. An administrator reviews and approves the claim.
6. The barcode-based handover process helps identify the item and facilitate its return to the rightful owner.

## 🔐 Security

- Authentication and protected API endpoints.
- Authorization checks for restricted operations.
- Claim verification before item handover.
- Appropriate barcode validation, if implemented.
