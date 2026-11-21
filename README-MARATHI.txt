WEDDING MEMORIES - FULL STACK MVP

कसे सुरू करायचे:
1. ZIP extract करा.
2. Node.js LTS install असणे आवश्यक.
3. Android Studio मध्ये extracted Wedding-Memories-Full folder Open करा.
4. View > Tool Windows > Terminal उघडा.
5. Project root मध्ये:
   npm install
   npm run install:all
   npm run dev
6. Browser मध्ये http://localhost:5173 उघडा.

Demo Owner Login:
Email: owner@weddingmemories.local
Password: ChangeMe123!

महत्त्वाचे:
- हा local-development MVP आहे; production-ready hosting नाही.
- Demo owner password लगेच बदला आणि deploy करण्यापूर्वी JWT_SECRET व PUBLIC_BASE_URL बदला.
- Data server/data.json मध्ये राहतो; uploaded images server/uploads मध्ये राहतात.
- Public gallery QR/link असलेल्या कोणालाही उघडता येते. Private/password-protected gallery अजून जोडलेली नाही.
- Photo download analytics, payment, email notifications, forgot-password आणि advanced permissions हे पुढील upgrade मध्ये जोडायचे आहेत.
- फक्त image formats jpeg/png/webp/gif, प्रति image 12MB पर्यंत; local storage.
