# Agrigram
Overview
AgroAdmin is a comprehensive agricultural management system designed for farmers and administrators. It includes:

Login/Signup for secure access

Admin Dashboard to manage crops, schemes, and applications

Farmer Dashboard to view crops, apply for schemes, and track status

Features
1. Authentication
🔐 Login & Signup Pages

Secure access for farmers and admins

Role-based redirection (Admin → Dashboard, Farmer → User Dashboard)

2. Admin Features
🌾 Crop Management – Add/update crop details
📋 Scheme Management – Create and publish government schemes
✅ Request Approval – Review and approve farmer applications

3. Farmer Features
🌱 View Crops – Browse crop details and submit cultivation data
🎯 Apply for Schemes – Submit applications for government support
📊 Track Status – Check approval progress of applications

/Agrigram 
│──portals/ # Login/Signup page
│──login.html
│──login.css
│──signup.html
│──signup.css
│──css/
│──style.css #global styling
│  
├── admin/  
│   ├── dash.html            # Admin Dashboard  
│   ├── crop.html            # Post Crop Details  
│   ├── scheme.html          # Manage Schemes  
│   └── request.html         # Approve Applications  
│  
└── user/  
    ├── dash.html            # Farmer Dashboard  
    ├── vcrop.html           # View/Submit Crops  
    ├── vscheme.html         # Browse Schemes  
    ├── ascheme.html         # Apply for Schemes  
    └── vstatus.html         # Check Application Status  

    How to Use
Login/Signup (index.html)

Admins: admin@agro.com (default)

Farmers: Sign up or use farmer@agro.com

Admin Dashboard

Manage crops, schemes, and approve requests

Farmer Dashboard

Apply for schemes and track submissions

Future Improvements
Password recovery

OTP verification

Database integration (MySQL/Firebase)

Mobile app (React Native/Flutter)

Setup
Clone the repository

Open index.html in a browser

Use default credentials or sign up

