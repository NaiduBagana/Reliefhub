
# 🌍 Relief Hub – Real-Time Emergency Coordination Platform

**Relief Hub** is a full-stack web application designed to streamline coordination among rescue agencies during natural calamities and man-made emergencies. It enables real-time calamity tracking, resource sharing, agency collaboration, and emergency alerts — all from a responsive and intuitive interface.

---

## 🚀 Live Demo

🌐 **Frontend:** [https://reliefhub-frontend.vercel.app/](https://reliefhub-frontend.vercel.app/)  
🔧 **Backend API:** [https://reliefhub-backend.onrender.com](https://reliefhub-backend.onrender.com)

---

## 🔍 Key Features

### 🌀 Calamities
- Real-time updates on ongoing disasters
- View disaster type, severity, and exact location on map

### 🧰 Resources
- Catalog of essential resources (medical kits, transport vehicles, etc.)
- Used to support and manage rescue efforts efficiently

### 🏢 Agencies
- Directory of registered rescue agencies
- View agency details and collaborate on operations

### 📢 Alerts
- Broadcast alerts to all or selected agencies
- Improve response time during high-risk situations

### 🙋 My Profile
- Each agency can manage its profile and contact information
- View assigned alerts and calamity history

---

## 🛠️ Tech Stack

| Category       | Tech Used                         |
|----------------|-----------------------------------|
| Frontend       | React.js, Tailwind CSS, Bootstrap |
| Backend        | Node.js, Express.js               |
| Database       | MongoDB                           |
| Maps & Geo     | Google Maps API                   |
| Deployment     | Vercel (Frontend),Render(Backend) |
| Version Control| Git + GitHub                      |

---

## 📸 Screenshots

> --

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/NaiduBagana/reliefhub.git
cd reliefhub
```

---

### 2. Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd frontend
npm install
```

---

### 3. Environment Variables

Create a `.env` file in both the `backend` and `frontend` directories.

#### Example `.env` for Backend:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

*(Add any other required keys based on your implementation)*

---

### 4. Run the App

#### Run Backend:

```bash
cd backend
npm start
```

#### Run Frontend:

```bash
cd frontend
npm start
```

Visit `http://localhost:3000` to view the app.

---

## 🧠 Inspiration

Relief Hub was created to offer a real-time emergency response coordination system that empowers agencies and responders with centralized disaster information, alerts, and resource management. It bridges the gap between agencies and communities during crises.

---

## 🙌 Feedback & Contributions

Have ideas or suggestions?  
Feel free to [open an issue](https://github.com/NaiduBagana/reliefhub/issues) or submit a pull request.  
Let’s collaborate to improve disaster response together. 💪

---

## 📜 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more details.
