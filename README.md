
```markdown
# 🏠 ROOM SHARE APP

**ROOM SHARE APP** is a modern web application designed to help roommates or flatmates **track, manage, and share expenses seamlessly**.  
With intuitive navigation and smart automation, managing group expenses has never been this simple.

---

## ✨ Key Features

### **1️⃣ Smooth Navigation**
- Start from a beautiful **Home Page** with a single **Get Started** button.  
- Quickly access **Signup** or **Login** pages with a clean, user-friendly interface.

---

### **2️⃣ Authentication**
- **Signup**: Create your account with your **Name, Email, Phone Number, and Password**.  
- **Login**: Access your personalized dashboard securely.

---

### **3️⃣ Smart Dashboard**
After logging in, you land on a simple, elegant dashboard with:
- **➕ Create Group**
- **📂 Open Group**
- **📜 View History**
- **🚪 Logout**

---

### **4️⃣ Group Management**
- Create groups by entering:
  - Number of members
  - Emails or phone numbers for invitations
- Automatically generates a **secure invite link** for members.
- Clicking the invite link instantly adds the member to the group.

---

### **5️⃣ Group Tools**
- **💬 Real-Time Chat**: Interact with your group for better coordination.  
- **💰 Expense Tracking**:
  - Add and manage expense details.
  - Check dues for each member.
  - Get a **clear breakdown** of contributions, savings, and shared expenses.
  - Visualize expense stats with **interactive pie charts**.

---

### **6️⃣ Payment & Dues**
- View pending **dues and balances**.
- Record payments with:
  - **Cash**
  - **Online Transfer** (enter **UTR number** and **upload proof of payment**)
- Mark dues as **completed** only after payment proof is validated.
- **No deletion** of cleared dues for complete history accuracy.

---

### **7️⃣ Reminders & Notifications**
- Set **due dates** for each expense.  
- Receive **reminders 1 day before** due dates via SMS.  
- Notify recipients automatically when payments are completed.

---

## 🛠 Tech Stack
- **Frontend**: React (Vite)
- **Routing**: React Router DOM
- **Styling**: CSS3 (modern and responsive)
- **State Management**: React Hooks (future: Redux)
- **Charts**: Recharts
- **Planned Backend**: Node.js + Express + MongoDB
- **Planned Notifications**: Twilio / Firebase

---

## 📂 Project Structure
```

room-share/
├── public/
│   └── background.jpg
├── src/
│   ├── components/
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   ├── Signup.jsx
│   │   ├── Dashboard.jsx
│   │   ├── GroupCreation.jsx
│   │   ├── GroupChat.jsx
│   │   └── ExpenseTracker.jsx
│   ├── styles/
│   │   ├── global.css
│   │   ├── Home.css
│   │   ├── loginsignup.css
│   │   ├── dashboard.css
│   │   ├── group.css
│   │   └── expenses.css
│   ├── App.jsx
│   └── main.jsx
├── package.json
└── vite.config.js

````

---

## ⚙️ Installation & Setup

### **1️⃣ Clone the repository**
```bash
git clone https://github.com/your-username/room-share.git
cd room-share
````

### **2️⃣ Install dependencies**

```bash
npm install
```

### **3️⃣ Start the development server**

```bash
npm run dev
```

Then open:

```
http://localhost:5173
```

---

## 📌 Upcoming Features

* Real-time chat using WebSockets.
* Cloud storage for payment proof uploads.
* Advanced analytics for expense summaries.
* Push notifications for all group members.
* Exportable reports in **PDF** and **Excel**.

---

## 🤝 Contributing

Contributions are always welcome!

1. **Fork** the repository
2. **Create a branch**:

   ```bash
   git checkout -b feature-branch
   ```
3. **Commit changes**:

   ```bash
   git commit -m "Added new feature"
   ```
4. **Push and open a Pull Request**.

---

## 📜 License

This project is licensed under the **MIT License**.
Feel free to use and customize it for your needs.

---

## 👨‍💻 Author

* **Batch 1** – Developer & Designer
* Email: *[renukadevikota23@gmail.com](tejadeepikayarrakula@gmail.com)*
* Year: **2025**

```

---

