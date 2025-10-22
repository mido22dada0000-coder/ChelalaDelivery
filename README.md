Chelala Delivery — PRO v2 Online (Render)

This package is prepared to deploy the Back-end and Admin to Render and contains:
- Backend (Node.js) with payments mock and Render deploy files
- Admin (Next.js) with Arabic i18n and map stub
- Android app skeleton configured to use BACKEND_URL = https://chelala-delivery.onrender.com
- Play Store publishing guide and privacy policy

Admin credentials (local testing / initial admin):
- Email: www.mido22dada0000@gmail.com
- Password: Rifka12022005

Important:
- To publish live, create a Render account (we will use your email) and create a Web Service using the backend folder.
- Create a managed Postgres on Render and set DATABASE_URL in Render dashboard.
- After deployment, update the BACKEND_URL in Android app if the URL differs.
