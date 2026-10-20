# Ganesh Towers - Official Website

Modern, responsive landing page for **Ganesh Towers**, located in **Anaparthi, Andhra Pradesh**. Showcases luxury 2 & 3 BHK flats available for rent and sale with interactive specifications, EMI calculator, image gallery, and direct WhatsApp enquiry booking.

---

## 🌟 Key Features

- **Modern Luxury Real Estate Design**: Sleek architectural design with glassmorphism header, responsive layout, and gold/navy theme.
- **Flats Showcase (Rent & Sale)**: Interactive filterable tabs for Rent and Sale units (2 BHK & 3 BHK) with dimensions, floor plan specs modal, and WhatsApp integration.
- **Interactive Home Loan EMI Calculator**: Sliders for property cost, interest rate, and tenure with real-time monthly EMI, principal, and total interest calculations.
- **Direct WhatsApp Enquiry Flow**: One-click enquiry generation pre-filled with the customer's name, preferred flat type, and visit date.
- **Amenities Grid**: 24/7 DG generator backup, automatic passenger lift, CCTV security, covered stilt car parking, 100% Vastu compliance, and rooftop sit-out.
- **Lightbox Photo Gallery**: High-resolution gallery preview with fullscreen modal view.
- **Strategic Location & Distance Matrix**: Highlights nearby connectivity in Anaparthi (Railway Station, Main Road, Schools, Hospitals) with embedded Google Map.
- **FAQ Accordion**: Smooth collapsible accordion answering common tenant and buyer questions.
- **Mobile Responsive & Floating Actions**: Floating WhatsApp action button and mobile sticky bottom action bar (Call / WhatsApp).

---

## ⚙️ How to Customize Your Contact Details

Open [`index.html`](index.html) and locate the `SITE_CONFIG` object inside the `<script>` tag near the bottom (around line 950):

```javascript
const SITE_CONFIG = {
  // Set your active WhatsApp number with Country Code (no +, spaces, or dashes)
  // e.g. "919876543210" for India
  whatsappNumber: "91XXXXXXXXXX",

  // Phone number displayed to visitors
  phoneDisplay: "+91 9XXXXXXXXX",
  phoneDial: "+919876543210",

  // Email address
  email: "ganeshtowers.anaparthi@gmail.com",

  // Address
  address: "Ganesh Towers, Anaparthi, East Godavari, Andhra Pradesh - 533342"
};
```

---

## 🚀 How to Enable GitHub Pages (Free Hosting)

1. Push the changes to your GitHub repository:
   ```bash
   git add .
   git commit -m "Enhance Ganesh Towers website with modern real estate design"
   git push origin main
   ```
2. In your GitHub repository:
   - Go to **Settings** > **Pages** (under Code and automation).
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select branch: `main` and folder: `/ (root)`.
   - Click **Save**.
3. Within 1-2 minutes, your website will be live at:
   `https://dileepkumarreddysathi.github.io/Ganesh-Towers/`

---

## 💻 Local Testing

Simply double-click `index.html` to open it in any web browser, or run a local server:

```powershell
# Using Python
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.
