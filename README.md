# 🍃 fMi Kitchen | Homemade Malabar Delicacies & Pickles

> **"നല്ല രുചി, നല്ല മനസ്സ്!"** — Authentic Kerala snacks, delicacies, and homestyle pickles delivered fresh with love.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fshammaskattil24-byte%2Ffathima)

---

## 🌟 Highlights & Features

- **📱 Responsive & Modern UI:** Designed specifically for mobile & desktop with warm Kerala forest tones, crisp typography (`Outfit`, `Plus Jakarta Sans`, and `Manjari`), and mouthwatering food presentation.
- **🥟 Malabar Delicacy Catalog:**
  - **സമൂസ (Malabar Samosas):** Crispy triangular snacks with Chicken, Beef, and Veg variants (₹450).
  - **ചട്ടിപ്പത്തിരി (Traditional Chattipathiri):** Layered crepe delicacy available in Chicken, Beef, Veg, and Sweet (₹470).
  - **കോഴി അട / ഇറച്ചി അട (Kozhi Ada):** Traditional folded pastry stuffed with spiced meat (₹450).
  - **പ്രീമിയം അച്ചാറുകൾ (Homemade Pickles):** Authentic homestyle Chicken (₹250), Beef (₹250), Fish (₹250), Prawn (₹250), and Mussel / Kallummakkaya (₹300) 200g jars.
  - **പപ്പായ അച്ചാർ (Papaya Pickle):** Vegetarian delicacy in 250g (₹50) & 200g (₹30).
- **⚡️ Live Search & Category Filtering:** Instant search in Malayalam and English, with category pills for All, Snacks, and Pickles.
- **🛒 Dynamic Cart System:**
  - In-card variant selection and quantity stepper (`− [count] +`).
  - Persistent shopping cart saved via `localStorage`.
  - Floating bottom cart bar on mobile and desktop showing live totals.
  - Interactive slide-down cart summary with free packaging notice.
- **📲 1-Click WhatsApp Direct Ordering:**
  - Captures Customer Name, Phone, Delivery Address, Delivery Type (Home Delivery vs Pickup), and Special Cooking Notes.
  - Formats an emoji-rich, structured order text and opens WhatsApp directly to **+91 96336 48272**.
  - Backup **"Copy Order Details"** button for clipboard copying.
- **🔍 Full Menu Lightbox:** Click on the hero showcase card to view the original high-resolution menu flyer in full screen.
- **💬 Customer Reviews & FAQ Accordion:** Transparent answers to customer queries on shelf life, payment modes (GPay, PhonePe, COD), and party orders.

---

## 📁 Project Directory Structure

```text
fmi-kitchen/
├── assets/
│   ├── logo.jpg               # fMi Kitchen wooden chef sign logo
│   ├── poster-clean.jpg       # Clean high-res menu poster flyer
│   ├── poster.jpg             # Original flyer graphic
│   ├── dish-samosa.jpg        # Crisp golden samosas platter
│   ├── dish-chattipathiri.jpg # Authentic chattipathiri with curry bowls
│   ├── dish-kozhiada.jpg      # Spiced meat folded kozhi ada
│   ├── dish-papaya.jpg        # Papaya pickle in terracotta clay pot
│   ├── pickle-chicken.jpg     # Chicken pickle jar
│   ├── pickle-beef.jpg        # Beef pickle jar
│   ├── pickle-fish.jpg        # Fish pickle jar
│   ├── pickle-prawn.jpg       # Prawn pickle jar
│   └── pickle-mussel.jpg      # Mussel / Kallummakkaya pickle jar
├── index.html                 # Complete standalone web application
├── README.md                  # Project documentation
└── .gitignore                 # Standard clean ignore rules
```

---

## 🚀 How to Deploy on Vercel

This website is **100% static** and has zero build dependencies.

1. **Option 1: Git Integration (Recommended):**
   - Connect your GitHub repository `shammaskattil24-byte/fathima` on [vercel.com/new](https://vercel.com/new).
   - Framework preset: **Other**.
   - Build command: *Leave blank*.
   - Output directory: `.` *(root)*.
   - Click **Deploy**. Vercel will instantly generate a live public URL (e.g. `https://fathima.vercel.app`).

2. **Option 2: Vercel CLI:**
   ```bash
   npm i -g vercel
   vercel
   ```

---

## 🛠️ How to Edit Menu Items & Prices

All product definitions are stored cleanly in the `products` array inside [index.html](index.html):

```javascript
const products = [
  {
    id: 'samosa',
    category: 'snacks',
    name: 'സമൂസ',
    engName: 'Malabar Samosa',
    price: 450,
    img: 'assets/dish-samosa.jpg',
    ...
  }
];
```

To update the phone/WhatsApp number:
```javascript
const WA_NUMBER = '919633648272';
```

---

## 📞 Contact & Orders

- **Phone:** [+91 96336 48272](tel:9633648272)
- **WhatsApp:** [Message on WhatsApp](https://wa.me/919633648272)
- **Location:** Kerala, India
- **Operating Hours:** Every day, 8:00 AM – 9:00 PM

---

© 2026 **fMi Kitchen** · *Made with ❤️ in Kerala*
