 Internship =>

A responsive multi-section website created as part of my **Growfinix internship task** using **HTML, Tailwind CSS, and JavaScript**.

The project focuses on building a modern frontend interface with responsive design and interactive UI components.

## 🚀 Features

* 📱 Responsive navigation bar
* 🍔 Mobile menu toggle
* 🌙 Dark mode toggle
* 🏠 Hero section with call-to-action
* 💼 Services section with responsive cards
* 👨‍💻 About/Team section
* 📩 Contact form with client-side validation
* ❓ Interactive FAQ accordion
* ⌨️ Keyboard interaction support for FAQ
* ✨ Smooth scrolling and UI transitions
* 📱 Responsive layout for different screen sizes

## 🛠️ Technologies Used

* **HTML5** – Structure and semantic markup
* **Tailwind CSS** – Responsive styling and utility classes
* **JavaScript** – DOM manipulation and interactive functionality
* **Git & GitHub** – Version control and project management

## 📂 Project Structure

```text
growfinix-internship-task-1/
│
├── task1.html
├── javascrript.js
└── README.md
```

## ⚙️ How to Run

Since this is a frontend project, no backend or database setup is required.

### 1. Clone the repository

```bash
git clone https://github.com/Anurag017pratap/growfinix-internship-task-1.git
```

### 2. Navigate to the project

```bash
cd growfinix-internship-task-1
```

### 3. Run the project

Open `task1.html` directly in your browser.

You can also use **VS Code Live Server** for a better development experience.

## 🎨 Main Sections

### 1. Navigation

The website contains a responsive navigation bar with links to:

* Home
* Services
* About
* Contact

On smaller screens, a hamburger menu is used to show or hide the navigation links.

### 2. Hero Section

The hero section introduces the website with a heading, description, and call-to-action button.

### 3. Services

The services section contains responsive cards for:

* Web Development
* Mobile Apps
* Cloud Solutions

Tailwind CSS grid utilities are used to make the cards responsive.

### 4. About

The About section contains information about the team along with profile cards.

### 5. Contact Form

The contact section includes:

* Name
* Email
* Message

JavaScript is used for basic client-side form validation before submission.

The validation checks:

* Required fields
* Basic email format
* Empty input values

### 6. Dark Mode

Dark mode is implemented using Tailwind CSS's class-based dark mode.

JavaScript toggles the `dark` class on the root `<html>` element:

```javascript
document.documentElement.classList.toggle('dark');
```

Tailwind's `dark:` utility classes then apply the appropriate dark theme styles.

### 7. FAQ Accordion

The FAQ section provides expandable and collapsible questions.

JavaScript handles:

* Opening and closing FAQ answers
* Icon rotation
* Keyboard interaction using `Enter` and `Space`

## 📱 Responsive Design

The project uses Tailwind CSS responsive utilities to adapt the interface to different screen sizes.

For example:

```html
md:grid-cols-3
```

allows the service cards to change from a single-column layout on smaller screens to a three-column layout on medium and larger screens.

## 🧠 What I Learned

Through this internship task, I gained practical experience with:

* Building responsive web layouts
* Using Tailwind CSS utility classes
* DOM manipulation with JavaScript
* Event listeners
* Mobile navigation
* Dark mode implementation
* Form validation
* Accordion components
* Basic accessibility and keyboard interactions
* Organizing and managing a frontend project with Git and GitHub

## 🔮 Future Improvements

Some possible improvements for the project include:

* Separate JavaScript into dedicated files
* Add backend integration for the contact form
* Store submitted contact messages in a database
* Add form submission feedback without browser alerts
* Improve accessibility with additional ARIA attributes
* Add animations and micro-interactions


## 👨‍💻 Author

**Anurag Pratap**

B.Tech Graduate | Software Engineering Enthusiast

* GitHub: [Anurag017pratap](https://github.com/Anurag017pratap)




