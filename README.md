# Personal Website

This is my personal website showcasing my portfolio, skills, and contact information.

## Setup Instructions

1. Clone the repository
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

2. Set up Firebase Configuration
- Copy the template configuration file:
```bash
cp js/firebase-config.example.js js/firebase-config.js
```
- Open `js/firebase-config.js` and replace the placeholder values with your Firebase project credentials

3. Firebase Database Rules
Make sure to set up your Firebase Realtime Database rules in your Firebase Console to allow writing to the contacts collection:
```json
{
  "rules": {
    "contacts": {
      ".write": true,
      ".read": false
    }
  }
}
```

## Features
- About Me section
- Skills showcase
- Project portfolio
- Contact form with Firebase integration
- Mobile-responsive design

## Technologies Used
- HTML5
- CSS3
- JavaScript
- Firebase Realtime Database
- Font Awesome icons

## Contact
For any questions or collaboration opportunities, please reach out through the contact form on the website. 