# 💍 Wedding Memories – Full-Stack Wedding Photography Platform

A luxury, minimal, elegant full-stack web application designed for wedding photography studios, photographers, and clients. Features dynamic quotation requests, private QR code photo galleries, photographer monthly subscriptions, and a complete admin CMS control center.

---

## ✨ Features & Highlights

### 🎨 Design Theme (Beige + Brown + Ivory)
- **Primary Background**: Ivory (`#F8F3EA`) & Warm Beige (`#EDE3D5`)
- **Primary Accent Colors**: Dark Royal Brown (`#594536`) & Champagne Gold (`#C6A77B`)
- **Typography**: `Playfair Display` (Serif Headings) & `Poppins` (Sans-Serif Body)
- **Theme Switcher**: Built-in toggle between **Ivory Light Mode** and **Dark Gold Mode**.

### 📱 Key Functionalities
1. **Client Quotation Request System**:
   - Guests/clients can select photographers, desired services (Wedding, Cinematic Films, Pre-wedding, Drone, Albums, Live Stream), event date, and venue to submit direct quotation inquiries.
2. **Photographer Workspace & Subscription Management**:
   - Photographers get a dedicated dashboard to upload sample portfolio photos, configure service rates, manage business logos, and view client inquiries.
   - **30-Day Monthly Subscriptions**: Auto-evaluated membership validity with renewal warning banners and admin renewal history logs.
3. **QR Code Private Wedding Galleries**:
   - Unique QR code generated for every wedding project. Guests scan QR codes to view and download high-resolution event photos.
4. **Website Owner / Super Admin Control Center**:
   - Manage all photographers (+Add, Edit, Deactivate, Renew Subscriptions).
   - Manage clients and customer accounts.
   - Edit homepage hero banner photo and marketing content live from the dashboard.
5. **PDF Export & WhatsApp Quotation Sharing**:
   - Photographers can customize packages, apply discounts, track advance payments, print PDF invoices, or share quotations directly on WhatsApp.
6. **100% Mobile & Tablet Responsive**:
   - Custom mobile hamburger navigation drawer and fluid grid layouts across all screen resolutions.

---

## 🔑 Login Credentials

| Role | Email / ID | Password | Access Level |
| :--- | :--- | :--- | :--- |
| **Super Admin / Owner** | `bhaveshshewale76@gmail.com` | `Bhavesh@#1122` | Full Website CMS, Photographer & Client Management |
| **Photographer** | `ccddfdf@gmail.com` | `123456` | Workspace, Sample Portfolio, QR Galleries, Quotations |

---

## 🛠️ Tech Stack

- **Frontend**: React.js (v18), Vite, Lucide React Icons, Pure Responsive CSS
- **Backend**: Node.js, Express.js, JWT Authentication, bcryptjs, Multer file upload, QRCode Generator, CORS
- **Storage**: Local JSON database (`server/data.json`) and `/uploads/` file storage

---

## 🚀 Local Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/wedding-memories.git
cd wedding-memories
```

### 2. Install dependencies for root, server, and client
```bash
npm run install:all
```

### 3. Run the application in development mode
```bash
npm run dev
```
- **Frontend URL**: `http://localhost:5173` (or `http://YOUR_LOCAL_IP:5173` on mobile)
- **Backend URL**: `http://localhost:4000`

---

## 🌐 Free Hosting & Deployment Guide

### Deploy Backend on [Render.com](https://render.com)
1. Create a new **Web Service** on Render and connect your GitHub repository.
2. Set Root Directory: `server`
3. Build Command: `npm install`
4. Start Command: `npm start`
5. Render provides a live backend URL: `https://your-backend.onrender.com`.

### Deploy Frontend on [Vercel.com](https://vercel.com)
1. Create a new **Project** on Vercel and connect your GitHub repository.
2. Set Root Directory: `client`
3. Framework Preset: `Vite`
4. Output Directory: `dist`
5. Vercel provides a live website URL: `https://your-wedding-memories.vercel.app`.

---

## 📜 License & Copyright
© 2026 Wedding Memories. All rights reserved.
