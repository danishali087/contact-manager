# 📱 Danish Contact App

> A responsive and feature-rich Contact Manager built with Angular 18 — create, view, edit, search, and delete contacts with real-time photo previews and JSON-based data storage.

![Angular](https://img.shields.io/badge/Angular-18-red?style=for-the-badge&logo=angular)
![TypeScript](https://img.shields.io/badge/TypeScript-blue?style=for-the-badge&logo=typescript)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?style=for-the-badge&logo=bootstrap)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 🖼️ App Preview

> A clean, yellow-themed contact dashboard with card-based layout showing contact photo, name, email, and mobile — with quick action buttons for View, Edit, and Delete.

---

## ✨ Features

- ➕ **Add New Contact** — Create contacts with name, email, mobile number, and profile photo
- 🖼️ **Auto Photo Preview** — Profile photo updates automatically as soon as the user fills in details
- 🔍 **Search Contacts** — Instantly search through all contacts by name
- 👁️ **View Contact** — View full contact details in a dedicated view
- ✏️ **Edit Contact** — Update any contact's information at any time
- 🗑️ **Delete Contact** — Remove contacts with a single click
- 💾 **JSON Data Storage** — All contact data is stored and managed via JSON
- 📱 **Responsive UI** — Card-based layout that works across all screen sizes
- 🎨 **Custom Branded Theme** — Green header with yellow background and color-coded action buttons

---

## 🚀 Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Angular 18 |
| Language | TypeScript |
| Styling | CSS / Bootstrap |
| Data Storage | JSON |
| CLI | Angular CLI v18.2.10 |

---

## 📁 Project Structure

```
contact-manager/
├── src/
│   ├── app/
│   │   ├── components/        # Contact card, add, edit, view components
│   │   ├── services/          # Contact data service (JSON handling)
│   │   ├── models/            # Contact interface/model
│   │   └── app.component.ts   # Root component
│   ├── assets/                # Static assets & images
│   └── index.html             # Main HTML entry point
├── public/                    # Public assets
├── angular.json               # Angular CLI config
├── package.json               # Dependencies
└── tsconfig.json              # TypeScript config
```

---

## ⚙️ Installation & Setup

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (v18 or higher)
- [Angular CLI](https://angular.io/cli) v18

Install Angular CLI globally:
```bash
npm install -g @angular/cli
```

### 1. Clone the Repository

```bash
git clone https://github.com/danishali087/contact-manager.git
cd contact-manager
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the Development Server

```bash
ng serve
```

Visit `http://localhost:4200/` in your browser. The app will automatically reload on file changes.

---

## 📋 How to Use

1. **View Contacts** — All saved contacts appear as cards on the home screen
2. **Add a Contact** — Click the **"Add New ➕"** button → fill in Name, Email, Mobile & Photo
3. **Auto Photo** — The contact photo updates live as you fill in the form
4. **Search** — Type a name in the search bar and click **Search** to filter contacts
5. **View Details** — Click the 🟡 **eye button** to view full contact info
6. **Edit** — Click the 🟢 **pencil button** to update contact details
7. **Delete** — Click the 🔴 **trash button** to remove a contact

---

## 🎨 UI Overview

| Element | Detail |
|---------|--------|
| Header | Green branded bar — *"Danish Contact App"* |
| Background | Vibrant yellow theme |
| Contact Cards | White cards with photo, name, email & mobile |
| View Button | 🟡 Yellow — eye icon |
| Edit Button | 🟢 Green — pencil icon |
| Delete Button | 🔴 Red — trash icon |
| Search Bar | Top of page with search button |

---

## 🔧 Build for Production

```bash
ng build
```

Build artifacts will be stored in the `dist/` directory.

---

## 🧪 Running Tests

```bash
# Unit tests
ng test

# End-to-end tests
ng e2e
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add my feature'`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Danish Ali**
- GitHub: [@danishali087](https://github.com/danishali087)

---

⭐ If you found this project useful, please give it a **star** on GitHub — it means a lot!