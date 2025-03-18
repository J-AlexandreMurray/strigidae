Keyword Finder - Self-Publishing Keyword Research SaaS App
📌 Overview
Keyword Finder is a mobile SaaS application designed for self-published authors to discover high-ranking Amazon KDP keywords for their books. The app operates on a freemium model, offering limited daily searches for free users and unlimited searches + CSV export for premium subscribers.
This version moves away from local processing and leverages cloud-based APIs and Google Play Billing for a seamless mobile experience.
🚀 Features
✅ Amazon KDP Keyword Suggestions – Get keyword ideas for your book topic
✅ Dark Mode Support – Toggle between light and dark themes
✅ Cloud-Based Processing – No extra downloads; everything runs on a backend
✅ User Authentication – Login via Google or email using Firebase
✅ Freemium Model – Free users get 3 searches per day
✅ Premium Unlock – Pro users get unlimited searches and CSV export
✅ Google Play Billing Integration – Secure, in-app purchases
📲 Installation (For Developers & Testing)
Backend Setup (Flask API + Firebase Database)
• Clone the Backend Repository: git clone https://github.com/yourusername/keyword-finder-backend.git cd keyword-finder-backend 
• Create a Virtual Environment & Install Dependencies: python -m venv venv source venv/bin/activate # (Mac/Linux) venv\Scripts\activate # (Windows) pip install -r requirements.txt 
• Run the API Locally: python app.py 
Mobile App Setup (KivyMD + Firebase Auth)
• Clone the Frontend Repository: git clone https://github.com/yourusername/keyword-finder-app.git cd keyword-finder-app 
• Install Dependencies: pip install kivy kivymd firebase-admin requests 
• Run the App: python main.py 
💻 Technologies Used
📜 Roadmap & Development Plan
Phase 1: Core Functionality (Week 1-2)
✅ Set up Firebase Authentication (Google Sign-In & Email Login)
✅ Create a simple Flask API that processes keyword searches
✅ Implement Firestore database to store search history
Phase 2: Freemium Model & Payments (Week 3-4)
🔲 Limit free users to 3 searches per day
🔲 Integrate Google Play Billing API for in-app purchases
🔲 Develop the Pro version with unlimited searches + CSV export
Phase 3: Backend Optimization (Week 5-6)
🔲 Optimize API response times using caching
🔲 Add error handling & security features to the backend
🔲 Monitor Firebase logs & API performance
Phase 4: UI & Play Store Release (Week 7-8)
🔲 Polish UI/UX for mobile usability
🔲 Integrate dark mode settings
🔲 Prepare for Google Play Store submission & launch marketing campaign
📩 Contact & Support
For support or feature requests, reach out to:
📧 
🌐 
🚀 Get ready to dominate Amazon KDP with the best keyword research tool for self-publishers!