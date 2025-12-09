# BiteBuddy  
AI-powered food ordering chatbot designed to streamline ordering, menu browsing, and real-time order tracking through an intuitive conversational interface.

---

## 🚀 Overview  
BiteBuddy is a smart chatbot solution that enables users to browse menus, place food orders, track delivery status, and make secure payments — all through natural language interactions.  
Built for scalability and ease of deployment, the project integrates conversational AI, mobile UI components, and backend automation.

---

## 🧠 Key Features  
- **Conversational Ordering** — Users can order food using natural phrases like *“I want a cheeseburger”*.  
- **Smart Menu Navigation** — Menu filtering, item suggestions, and contextual recommendations.  
- **Order Status Tracking** — Real-time updates on order acceptance, preparation, and delivery.  
- **Secure Payments (Future Scope)** — Stripe gateway integration planned.  
- **Admin Dashboard (Planned)** — Monitor orders, menu updates, and delivery logs.

---

## 🏗️ Architecture (High-Level)  

User (Mobile App / Web)
│
▼
BiteBuddy Chat UI (React Native)
│
▼
Dialogflow / NLP Engine → Intent detection, responses
│
▼
Backend API (Node.js / Express)
│
├── Menu Service (MongoDB)
├── Order Service (MongoDB)
└── Payment Gateway (Stripe - future)


This design ensures modularity → UI, NLP, backend, and data layers remain independently upgradeable.

---

## 📂 Folder Structure (Planned)



BiteBuddy/
│
├── mobile-app/ # React Native front-end (coming soon)
│ └── assets/ # Images, icons, chat illustrations
│
├── server/ # Node.js backend (coming soon)
│ ├── routes/
│ ├── controllers/
│ ├── models/
│ └── utils/
│
├── nlp/ # Dialogflow config files & intents (future)
│
├── docs/ # Diagrams, documentation, architecture
│
└── README.md # Project documentation


**Note:** This repository currently contains documentation only. Code upload is planned in future iterations.

---

## 🛠️ Tech Stack

### **Frontend**
- React Native / Expo  
- Reanimated & Gesture Handler  
- Styled Components or NativeWind (optional)

### **Backend**
- Node.js + Express  
- MongoDB Atlas  
- Mongoose ORM  

### **AI/NLP**
- Google Dialogflow CX / ES  
- Webhook integration for custom responses  

### **DevOps & Deployment**
- Firebase / AWS Amplify (for app builds)  
- Render / Railway (backend hosting)  
- MongoDB Atlas (database hosting)  

---

## ⚙️ Getting Started (Future Setup Instructions)

### 1. Clone the Repository
```bash
## ⚙️ Getting Started (Future Setup Instructions)

> Note: Source code will be added in future updates.  
> The steps below outline the planned setup process once development is complete.

1. Clone the Repository (future)
```bash
git clone https://github.com/Sanjanaskyy/BiteBuddy
cd BiteBuddy

2. Install Mobile App Dependencies (future)

cd mobile-app
npm install
expo start

3. Install Backend Dependencies (future)

cd server
npm install
npm run dev

4. Configure Environment Variables

Create a .env file (later):

MONGO_URI=your-mongo-url
DIALOGFLOW_PRIVATE_KEY=...
DIALOGFLOW_CLIENT_EMAIL=...
STRIPE_SECRET_KEY=...

🧪 Usage (Expected Workflow)

Open the app → Start a conversation

Say: “Show me the menu” or “I want a pizza.”

Add/remove items to cart

Confirm the order

Track preparation & delivery

(Future) Complete payment securely

🖼️ Screenshots (To be added)
/docs/screenshots/home.png  
/docs/screenshots/chat-flow.png  
/docs/screenshots/order-tracking.png  

Screenshots will be uploaded after UI implementation.

🗺️ Roadmap
Phase	Features
Phase 1	Basic chatbot flow, menu browsing
Phase 2	Order placement, cart logic, backend integration
Phase 3	Payments, admin dashboard
Phase 4	User analytics, personalization engine

🛡️ /License

MIT License

Copyright (c) 2025 Sanjana Yadav

Permission is hereby granted, free of charge, to any person obtaining a copymof this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
