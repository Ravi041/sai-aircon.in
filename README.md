# ❄️ SAI Aircon Website

Official website for **SAI Aircon** — Delhi's trusted second-hand AC dealer and service provider.
Live at: [sai-aircon.in](https://sai-aircon.in)

---

## 📁 Project Structure

```
/
└── index.html      # Single-page website (HTML + CSS + JS)
└── README.md       # This file
```

---

## 🚀 Deployment (GitHub Pages)

This site is hosted on **GitHub Pages** with a custom domain.

### Steps to deploy:
1. Push `index.html` to the `main` branch
2. Go to **Settings → Pages**
3. Set source to: `Deploy from branch → main / root`
4. Set custom domain to: `sai-aircon.in`
5. Enable **Enforce HTTPS**

---

## 🌐 DNS Configuration (Porkbun)

In your Porkbun dashboard, set these DNS records:

| Type  | Host | Value                  | TTL |
|-------|------|------------------------|-----|
| A     | @    | 185.199.108.153        | 600 |
| A     | @    | 185.199.109.153        | 600 |
| A     | @    | 185.199.110.153        | 600 |
| A     | @    | 185.199.111.153        | 600 |
| CNAME | www  | yourusername.github.io | 600 |

> DNS changes can take up to 24 hours to propagate.

---

## ✏️ How to Update Content

All content is in `index.html`. Common things you'll want to change:

| What to update | Search for in the file |
|---|---|
| Phone number | `+91 99999 99999` |
| WhatsApp number | `wa.me/919999999999` |
| Email address | `info@sai-aircon.in` |
| AC stock / prices | Inside `#inventory` section |
| Your location/area | `Delhi NCR, India` |
| Customer reviews | Inside `.review-card` blocks |

---

## 🔧 Features

- Fully responsive (mobile + desktop)
- Services section (Buy, Sell, Repair, Install, Clean, AMC)
- AC inventory listings with enquiry buttons
- Contact form (submits via WhatsApp)
- Floating WhatsApp chat button
- Smooth scroll navigation
- Animated hero section

---

## 📞 Contact

**SAI Aircon**
- 🌐 [sai-aircon.in](https://sai-aircon.in)
- 📧 info@sai-aircon.in
- 📍 Delhi NCR, India
