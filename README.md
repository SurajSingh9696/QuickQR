# QuickQR

## Description
QuickQR is a full-stack application that allows users to upload images and manage them for QR code generation. The frontend provides a user-friendly interface for uploading images and accessing download links. The backend is built with Node.js and Express, handling image storage and retrieval.

## Features
- Upload images for storage and QR code link generation
- Generate download links for uploaded images
- Download images directly
- CORS support for cross-origin requests

## Tech Stack
- Frontend: (Web interface hosted at https://quickqr-image2qr.onrender.com)
- Backend: Node.js, Express, Multer, Mongoose, CORS

## Installation and Setup

### Backend
1. Navigate to the backend directory:
   ```
   cd React-NodeJS/00-Deployed/QuickQR
   ```
2. Install dependencies:
   ```
   npm install
   ```
3. Start the backend server:
   ```
   npm start
   ```
4. The backend server runs on `http://localhost:5555` (or the port specified in .env).

### Frontend
The frontend is deployed at `https://quickqr-image2qr.onrender.com`.

## Usage
- Use the frontend interface to upload images.
- The backend generates a download link for the uploaded image.
- Download the image via the provided link or GET to `/downloadQrImage/:id`.

## License
This project is open source and available under the MIT License.
