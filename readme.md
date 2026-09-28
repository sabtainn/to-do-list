# Sleek To-Do List & Task Manager

A responsive, dark-themed To-Do List web application featuring a modern frosted-glass (glassmorphic) interface, integrated client-side authentication, real-time filtering, and a team contact portal.

## 📸 Key Features

* **Glassmorphic UI / UX**: Deep dark-mode aesthetic with radial gradient highlights, backdrop-filter blurs, and animated borders.

* **Client-Side Authentication**: Interactive login form with custom animated validation tooltips, password visibility toggles, and simulated credential checks.

* **Dynamic Task Management**:

  * Add tasks via the input button or the `Enter` key.

  * Interactive task completion with strikethrough styling and state transitions.

  * Smooth task deletion with exit animations.

  * Dynamic empty-state indicator when no tasks remain.

* **Status Filtering**: Instantly toggle between **All**, **Active**, and **Completed** tasks.

* **Support & Team Portal**: Dedicated contact page presenting developer credentials and an animated message submission form with toast notifications.

* **Fully Responsive**: Adapts across mobile, tablet, and desktop screens.

## 🛠️ Tech Stack

* **HTML5**: Semantic document structure.

* **CSS3**: Custom variables, CSS Grid, Flexbox, glassmorphic styling, and keyframe animations.

* **JavaScript (ES6+)**: DOM manipulation, event listeners, and client-side state logic.

* **FontAwesome (v6.0.0)**: Vector iconography.

## 📂 Project Structure

```
├── index.html       # Entry authentication page (user login)
├── home.html        # Main to-do list dashboard & task manager
├── contact.html     # Team showcase & support inquiry form
├── style.css        # Stylesheet for the dashboard interface
└── README.md        # Project documentation

```

## 🚀 Getting Started

### 1. Clone the Repository

```
git clone https://github.com/sabtainn/to-do-list.git
cd to-do-list

```

### 2. Launch the Application

No external build tools or web servers are required. Open `login.html` directly in any modern browser:

* **macOS**: `open login.html`

* **Linux**: `xdg-open login.html`

* **Windows**: `start login.html`

## 🔑 Demo Credentials

To access the task dashboard via `login.html`:

| Field | Value | 
 | ----- | ----- | 
| **Username** | `admin` | 
| **Password** | `123` | 

## 👥 Contributors

* **Muhammad Sabtain** - `k250696@nu.edu.pk`

* **Arqam Bin Amir** - `k250830@nu.edu.pk`

* **Amaan Mairaj** - `k250768@nu.edu.pk`

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).