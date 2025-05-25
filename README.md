📚 McGibs Sample Access Platform
McGibs is a web-based platform that offers users access to sample essays. Users can register, log in, and download up to 5 samples after upgrading.

🔧 Technologies Used
HTML5, CSS3, Bootstrap 5

JavaScript (ES6)

Firebase Authentication (Email/Password)

Firebase Hosting

Google Drive (for sample file storage)

IntaSend (for payment processing)
DEV Community
Stack Overflow
+1
YouTube
+1
Firebase
+1
YouTube
+1

🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/GibsonWaheire/McGibs_Digital_Solutions
cd mcgibs-sample-access
2. Set Up Firebase
Create a Firebase project at Firebase Console.

Enable Email/Password authentication under Authentication > Sign-in method.

Navigate to Project Settings > General and add a new web app.

Copy the Firebase configuration object provided.
React - Supercharge
CodeProject
+1
Stack Overflow
+1

3. Configure Firebase in Your Project
In your project directory, locate the firebase-init.js file.

Replace the existing firebaseConfig object with your project's configuration:

javascript
Copy
Edit
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "your-project-id.firebaseapp.com",
  projectId: "your-project-id",
  storageBucket: "your-project-id.appspot.com",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};
4. Install Firebase CLI
bash
Copy
Edit
npm install -g firebase-tools
firebase login
5. Initialize Firebase in Your Project
bash
Copy
Edit
firebase init
Select Hosting.

Choose your Firebase project.

Set public as your public directory.

Configure as a single-page app: No.

Do not overwrite index.html if prompted.
GitHub
+26
Stack Overflow
+26
Level Up Coding
+26
React - Supercharge

6. Deploy to Firebase Hosting
bash
Copy
Edit
firebase deploy
After deployment, your site will be available at https://your-project-id.web.app.

📂 Project Structure
pgsql
Copy
Edit
mcgibs-sample-access/
├── public/
│   ├── index.html
│   ├── login.html
│   ├── dashboard.html
│   ├── unlocked-samples.html
│   └── firebase-init.js
├── .firebaserc
├── firebase.json
└── README.md
💡 Features
User Authentication: Secure login and registration using Firebase Authentication.

Sample Access: Users can view and download sample essays.

Download Limit: Users can download up to 5 samples after upgrading.

Payment Integration: Upgrade functionality integrated with IntaSend for payments.

Responsive Design: Mobile-friendly interface using Bootstrap 5.

📞 Support
For any issues or inquiries, please contact [your email address].
