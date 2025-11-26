# 🌍 TravelEase – Travel Management System

TravelEase is a modern map-based travel assistant that helps users explore destinations, discover top attractions, and navigate using real-time location intelligence.  
The system provides a clean UI, curated travel information, and deep Google Maps integration for a seamless and enjoyable travel experience.

---

##  Project Overview

TravelEase aims to simplify travel planning and exploration by offering:

- 🗺️ Interactive map features  
- ✈️ Destination-based exploration  
- ⭐ Curated attraction lists  
- 🏨 Nearby hotels  
- 🏥 Nearby hospitals  
- ⛽ Nearby fuel stations  
- 🔗 Direct Google Maps deep-linking  

Built using **Next.js**, **Tailwind CSS**, and **Google Maps APIs**, the platform provides a modern, responsive, and scalable solution suitable for real-world travel applications.

---

## 💡 Key Highlights

###  1. Destination Search  
Users can enter any location (e.g., *Bangalore, Mysore, Hampi*) and instantly explore curated information about that city.

###  2. Curated Top Attractions  
Every destination includes well-structured sightseeing cards containing:  
- High-quality images  
- Short descriptions  
- Google Maps redirect buttons  

###  3. Google Maps Integration  
Users can open locations directly inside Google Maps to access:  
- Satellite view  
- Ratings  
- Reviews  
- Directions  
- Nearby services (hotels, petrol pumps, restaurants)

###  4. Real-Time Nearby Services  
Automatically shows:  
- 🏥 Hospitals  
- 🏨 Hotels  
- ⛽ Petrol Stations  

Using **Google Places API**, the system fetches real-time nearby services around the user’s selected destination.

###  5. Clean, Responsive, Modern UI  
- Full-screen hero section with travel imagery  
- Glass-effect search box  
- Smooth animations  
- Dark blue / gradient theme  
- Mobile-friendly layout  

---

## 🧭 Core Features

| Feature | Description |
|--------|-------------|
| **Interactive Map** | Satellite view, zoom, drag, markers |
| **Destination Search** | Search travel locations instantly |
| **Nearby Services** | Shows hospitals, hotels & fuel pumps |
| **Attractions Page** | City-wise curated sightseeing list |
| **Google Maps Deep-Linking** | Opens live map with all features |
| **Responsive UI** | Works on PC, Tablet, and Mobile |

---

## 🖼️ Screenshots

### ⭐ Home Page  
A clean hero section with a stunning mountain background and a glass search box.


![WhatsApp Image 2025-11-26 at 19 35 20_0e5cc2a9](https://github.com/user-attachments/assets/d1e477ef-b7a9-4bc5-a00b-d15640e35d22)



---

### ⭐ Top Attractions Page  
Displays curated attractions with images, descriptions, and maps link.

![WhatsApp Image 2025-11-26 at 19 35 19_307c4620](https://github.com/user-attachments/assets/f12377aa-87b2-4874-a9a4-579b259ba2b0)



---

### ⭐ Google Maps Deep-Link  
Direct deep-link to Google Maps showing hotels, hospitals, ratings, and prices.

![WhatsApp Image 2025-11-26 at 19 35 19_d27af542](https://github.com/user-attachments/assets/783b1c84-0d64-44f3-b76e-60c568acdba2)



---

### ⭐ Hotel Booking View (Booking.com Style)

TravelEase integrates hotel discovery using Google Places and Booking-style UI.  
Users can view hotel details such as:

- 💰 Price per night  
- ⭐ Ratings  
- 🛏️ Room details  
- 🔗 Booking links  
- 📍 Map location  

This gives travelers a similar experience to apps like **Booking.com, Agoda, and Airbnb**, but embedded into the TravelEase ecosystem.

![WhatsApp Image 2025-11-26 at 19 35 19_a3895dd0](https://github.com/user-attachments/assets/115a04bb-c9c9-4668-bfa0-cbc16bb7a7b7)


---

## 🏗️ Technology Stack

### **Frontend**
- Next.js / React.js  
- Tailwind CSS  
- TypeScript (optional)

### **Backend (Optional)**
- Node.js + Express.js  
- API routes for directions & places

### **Database (Optional Enhancement)**
- Firebase Firestore  
- MongoDB

### **APIs Used**
- Google Maps JavaScript API  
- Google Places API  
- Google Directions API  
- HTML5 Geolocation API  

### **Deployment**
- Vercel  
- Firebase Hosting  

---

## 📁 Project Structure

```
src/
 ├── app/
 ├── components/
 ├── pages/
 ├── utils/
 ├── styles/
public/
server/ (optional backend)
package.json
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-github-username/TravelEase.git
cd TravelEase
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Add Environment Variables  
Create `.env.local`:

```
NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=your_api_key
```

### 4️⃣ Run Development Server
```bash
npm run dev
```

Open the app in your browser:  
👉 `http://localhost:3000`

---

## 🚀 Future Enhancements

- 🔑 User login & personalized dashboard  
- 🔔 Smart alerts for fuel, hospitals, and weather  
- ☁️ Weather API integration  
- 🆘 SOS emergency location button  
- 📍 AI-powered recommended routes  
- 🚘 Real-time movement simulation on map  

---

## 👩‍💻 Developer

**Nisha Naik** 
**Nithin R**
B.E. Computer Science & Engineering  
Alva’s Institute of Engineering & Technology (AIET), VTU  

*Focused on building clean UI experiences, map-based applications, and real-time location-aware systems.*



