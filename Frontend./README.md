## Features (Front-End Only)

### Pages
1. **Landing / Home (`index.html`)**
   - Hero section with tagline and CTA buttons
   - App introduction and brief overview
   - Header and Footer

2. **About Us (`about.html`)**
   - Team member cards with photo, name, and role
   - Project mission and vision
   - Header and Footer

3. **How It Works (`how-it-works.html`)**
   - Step-by-step guide: Add → Track → Analyze
   - Visual cards with icons/images
   - Header and Footer

4. **Login (`login.html`) & Register (`register.html`)**
   - User authentication forms (email, password, name)
   - Login/Register buttons and validation placeholders
   - Header and Footer

5. **Dashboard (`dashboard.html`)**
   - Summary cards (Total Balance, Income, Expenses)
   - Expense charts (canvas placeholders)
   - Recent transaction list
   - Budget progress bars
   - Alerts placeholder

6. **Add Transaction (`add-transaction.html`)**
   - Form to input income/expense transactions
   - Fields: Type, Amount, Category, Date, Description
   - Submit button

7. **Goals (`goals.html`)**
   - Savings goals cards with progress bars
   - Add/Edit goal section

---

### Components
- **Header (`components/ui/header.html`)** – appears on all pages
- **Footer (`components/ui/footer.html`)** – appears on all pages
- **Alert Banner (`components/ui/alert-banner.html`)** – dashboard or goals alerts
- **Dashboard Components (`components/dashboard/`)**
  - Summary Cards
  - Expense Chart
  - Transaction List
  - Budget Progress

---

## Folder Structure (Front-End Only)
spendwise/
│ index.html
│ about.html
│ how-it-works.html
│ dashboard.html
│ login.html
│ register.html
│ add-transaction.html
│ goals.html
├── css/
│ ├── style.css
│ ├── dashboard.css
│ ├── forms.css
│ └── responsive.css
├── js/
│ ├── app.js
│ ├── budgetCalculator.js
│ ├── chartRenderer.js
│ ├── uiController.js
│ └── alertSystem.js
├── assets/
│ ├── icons/
│ └── images/
├── components/
│ ├── dashboard/
│ │ ├── summary-cards.html
│ │ ├── expense-chart.html
│ │ ├── transaction-list.html
│ │ └── budget-progress.html
│ └── ui/
│ ├── header.html
│ ├── footer.html
│ └── alert-banner.html
├── lib/
│ └── utils.js
└── README.md



---

## Technologies Used
- **HTML5** – Semantic structure and content
- **CSS3** – Layout, styling, Flexbox/Grid, responsive design
- **JavaScript (ES6)** – Modular scripts for budgeting, charts, UI updates, and alerts
- **Chart.js placeholders** – Ready for future integration
- **Local Storage** – Temporary persistence of data in browser

---

## Team Members & Responsibilities (Front-End HTML)

| Member | Pages / Components |
|--------|------------------|
| Lalisa Tamene | Home page (`index.html`), Header & Footer |
| Leoul Zerihun | About Us (`about.html`), How It Works (`how-it-works.html`) |
| Meklit Yemane | Login (`login.html`), Register (`register.html`) |
| Nebiyu Yalemgeta | Dashboard (`dashboard.html`) |
| Negasi Berihu | Add Transaction (`add-transaction.html`) |
| Robel Wondwossen | Goals (`goals.html`), Alert Banner (`components/ui/alert-banner.html`) |

---

## Usage
1. Open any page in a modern browser.
2. All pages include **modular components** for header, footer, and dashboard elements.
3. JavaScript modules (`app.js`, `budgetCalculator.js`, etc.) handle UI interactions and placeholders for charts/alerts.
4. No backend required yet; all data is stored temporarily using **localStorage**.

---

## Future Enhancements (Phase II)
- PHP backend with MySQL for persistent storage
- User authentication
- Dynamic charts and real-time updates
- Email notifications for budget alerts
- AI-driven spending insights

---

## Conclusion
This front-end implementation of Savr is a **fully modular, multi-page web application** designed for **university students**. It provides a **professional, collaborative foundation** for future full-stack development, showcasing clean HTML structure, responsive design, and scalable JavaScript modules.

