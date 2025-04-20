# Wilderness Works - Custom Survival Gear

Welcome to **Wilderness Works**, a handcrafted survival gear storefront website. This site is built with HTML and Tailwind CSS, and includes an order form powered by [Formspree](https://formspree.io/) to handle submissions.

## 🌲 Features
- Responsive design using Tailwind CSS
- Product showcase for custom survival gear
- Order form for purchasing items
- Contact form for inquiries
- Confirmation page with auto-redirect

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/wilderness-works.git
cd wilderness-works
```

### 2. Customize Form Submission
Update both forms in `index.html` with your [Formspree](https://formspree.io/) form endpoint:

```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```
Replace `your-form-id` with your actual Formspree form ID.

Also make sure the redirect in the order form points to your hosted `thank-you.html` page:
```html
<input type="hidden" name="_redirect" value="https://yourdomain.com/thank-you.html">
```

### 3. Deploy to GitHub Pages
- Push your code to a GitHub repository
- Go to **Settings > Pages**
- Set the source to the root of your main branch
- Your site will be live at `https://yourusername.github.io/wilderness-works`

---

## 🧰 Folder Structure
```
/
├── index.html
├── thank-you.html
└── README.md
```

---

## 📬 Contact
Have questions or feedback? Use the contact form on the website or email us at: `your-email@example.com`

---

## 🪓 License
This project is open source and available under the [MIT License](LICENSE).
