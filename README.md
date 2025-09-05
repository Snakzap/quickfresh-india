# 🍽️ QuickFresh

**भारत में ताज़ा भोजन की सबसे तेज़ डिलीवरी सेवा**

QuickFresh एक पूर्णतः भारत-केंद्रित फूड डिलीवरी प्लेटफ़ॉर्म है, जो OTP लॉगिन, UPI भुगतान, हिंदी UI और role-based access के साथ तैयार किया गया है। इसका उद्देश्य है:

- 🇮🇳 भारत के उपयोगकर्ताओं के लिए स्थानीयकृत अनुभव देना  
- 🔐 सुरक्षित और तेज़ लॉगिन (OTP + RBAC)  
- 💳 Razorpay और Cashfree के माध्यम से UPI-ready भुगतान  
- 🧑‍💼 Admin, 🍽️ Restaurant, 🚚 Deliveryman और 🛒 Customer के लिए अलग-अलग panels  
- 📦 Modular architecture और आसान deployment

---

## 🔧 Technologies Used

- **Frontend**: React + Zustand + Tailwind  
- **Backend**: Node.js + Express + Prisma  
- **Database**: PostgreSQL  
- **Cache**: Redis (OTP TTL)  
- **Deployment**: Vercel (frontend), Railway (backend)  
- **Security**: JWT, HTTPS, OWASP compliance

---

## 🚀 Getting Started

```bash
git clone https://github.com/Snakzap/quickfresh-india.git
cd quickfresh-india
docker-compose up --build
