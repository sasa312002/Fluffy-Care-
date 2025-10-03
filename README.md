# 🐾 Fluffy Care  
**Where big hearts meet small paws.**  

Fluffy Care is a **community-driven pet care platform** that brings together adopters, pet owners, and veterinary professionals—turning the chaos of pet care into something calm, kind, and wonderfully organized.  

---

## ✨ Features  

### 🏡 For Pet Owners & Adopters  
- **Find a forever home**: Guided forms + home-visit flows for adoption.  
- **Reunite families**: Report lost & found pets to mobilize the community.  
- **See the doctor (without the drama)**: Book & manage appointments with reminders.  
- **Shop smart**: Browse products, add to cart, place orders & leave reviews.  
- **Stay connected**: Announcements, events & community updates.  
- **Picture-perfect**: Seamless pet image uploads powered by [Cloudinary](https://cloudinary.com/).  

### 👩‍⚕️ For Veterinary Professionals  
- **Doctor portal**: Availability, appointments, medical records & pet profiles.  
- **Streamlined workflow**: React-based SPA for smooth, professional UX.  

---

## 🛠️ Under the Hood  

- **Backend**: `Node.js + Express + MongoDB (Mongoose)`  
- **Doctor Interface**: `React (Vite)` SPA  
- **Notifications**: Email + in-app alerts to keep everyone in the loop  
- **Media**: Local uploads (dev) → Cloudinary (prod)  

### 📂 Monorepo Structure  
```
fluffy-care/
│
├── backend/           # Auth, pets, forms, appointments, orders, reviews, events
├── doctorInterface/   # React (Vite) dashboard for veterinary professionals
├── uploads/           # Local dev media (Cloudinary in prod)
└── README.md          # You are here 💜
```

---

## 🚀 Getting Started  

### 1. Clone the repo  
```bash
git clone https://github.com/your-username/fluffy-care.git
cd fluffy-care
```

### 2. Install dependencies  
Backend:  
```bash
cd backend
npm install
```

Doctor Interface:  
```bash
cd ../doctorInterface
npm install
```

### 3. Environment setup  
Create `.env` files in both **backend** and **doctorInterface** with:  
```env
# Backend
MONGO_URI=your_mongo_db_url
JWT_SECRET=your_secret_key
CLOUDINARY_URL=your_cloudinary_url
EMAIL_HOST=smtp.yourprovider.com
EMAIL_USER=your_email
EMAIL_PASS=your_password
```

```env
# Doctor Interface
VITE_API_URL=http://localhost:5000
```

### 4. Run the apps  
Backend:  
```bash
npm run dev
```
Doctor Interface:  
```bash
npm run dev
```

---

## 🐶 Why Fluffy Care?  
Because every pet deserves:  
- A story with a happy ending 🐕  
- A family that loves them 🐈  
- And a **great UX along the way** 💜  

---

## 🤝 Contributing  
We welcome contributions! Please:  
1. Fork the repo  
2. Create a feature branch (`git checkout -b feature/awesome-feature`)  
3. Commit changes (`git commit -m 'Add awesome feature'`)  
4. Push to branch (`git push origin feature/awesome-feature`)  
5. Open a Pull Request  

---

## 📸 Sneak Peek  
> (You can later add screenshots/GIFs of the app UI here.)  

---

## 📜 License  
MIT License © 2025 [Your Name/Org]  
