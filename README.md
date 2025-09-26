🌐 Creative Solutions Web Dashboard


Project Overview
This is a multi-page static website template featuring a modern, responsive landing page (Home/Dashboard) and a stylish, two-column user authentication flow (Sign Up and Login). The design incorporates modern CSS techniques like Flexbox, Sticky Navigation, and gradient backgrounds for a contemporary user experience.

🚀 Features
Home / Dashboard (home.html / dashboard.html)
Sticky Navigation: The navigation bar is fixed to the top of the viewport, ensuring access to links (Home, Product, Services, etc.).

Centered Search Bar: A clean search input is integrated and centered within the main navigation bar.

Hero Section: A visually appealing section featuring a central image overlaid on a "wet-glass" background, followed by descriptive Mission and Vision cards.

User Authentication (index.html / signup.html)
Two-Column Split Design: A modern layout separating the inspiring welcome panel (left, gradient background) from the functional form panel (right, white background).

Sign Up Flow: Uses client-side JavaScript (localStorage) to register new users (Email and Password) and redirects them to the Login page.

Login Flow: Checks credentials against the data stored during Sign Up.

Editable Image: A circular placeholder for a profile picture is included in the sign-up form.

🛠️ Technology Stack
HTML5: Semantic structure for all pages.

CSS3: Styling, including Flexbox for layout, sticky positioning, gradients, and subtle shadow/transparency effects.

JavaScript: Simple, client-side logic for the Sign Up and Login process (saving and retrieving credentials via localStorage).

⚙️ Installation and Setup
This is a static project, requiring no backend server to run.

Clone the Repository:

Bash

git clone [YOUR_REPO_URL]
cd creative-solutions-web
(If you are not using Git, simply download and unzip the project folder.)

Verify File Structure: Ensure your project directory looks like this:

.
├── index.html       (Login Page)
├── signup.html      (Sign Up Page)
├── dashboard.html   (Home Page)
├── css/
│   └── style.css
└── images/
    ├── logo-home.png
    ├── default-avatar.png
    ├── twitter-icon.png
    ├── facebook-icon.png
    ├── wet-glass-background.jpg  (Or other hero backgrounds)
    └── ...
Run Locally:

Open your file explorer and double-click index.html or signup.html to view the site in your default web browser.

(Alternatively, use a local server extension like VS Code's "Live Server" for best results.)

📝 Usage
Sign Up and Login
Open signup.html.

Fill in the Email Address and Password fields and click REGISTER.

The credentials will be saved locally in your browser's localStorage.

You will be redirected to index.html (Login).

Enter the same Email and Password to log in. Upon successful verification, you will be redirected to dashboard.html.

Customization
Branding: Update all instances of Your Logo, Creative Solutions Co., and www.yoursite.com in both the HTML and CSS.

Colors: Modify the purple gradient (#8E2DE2, #4A00E0) in the welcome-panel CSS to match your brand colors.

Images: Replace the placeholder images in the images/ folder with your own high-resolution assets.

