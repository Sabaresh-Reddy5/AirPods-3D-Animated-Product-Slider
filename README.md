# AirPods-3D-Animated-Product-Slider

AirPods 3D Animated Product Slider

This project is a modern, interactive product carousel built using HTML, CSS, and JavaScript. It features smooth animations, dynamic transitions, and a detailed product preview section. The UI is inspired by premium e-commerce websites and showcases product design in a visually appealing way.

The project is fully responsive and adapts nicely to desktop, tablet, and mobile screens.

🚀 Features
🎞️ Animated Product Carousel

Smooth sliding animation between product cards

Foreground and background blur effects

3D depth effect using CSS transforms

Auto-managed z-index, opacity, and transitions

🛒 Product Information Section

Each item includes:

Product title

Short description

Detailed specifications (Battery, Charging Port, Compatibility, Bluetooth version, Control type)

“Add to Cart” and “Checkout” buttons

🔍 “See More” Detail Mode

Clicking SEE MORE opens a full-width detailed product view:

Right-aligned text panel with animations

Responsive image repositioning

Smooth fade-in content reveal

Back button (See All ↗) to return to slider

📱 Fully Responsive

Optimized for:

Desktop

Tablet

Mobile

Responsive font sizes, layout resizing, scrollable sections

🎨 Glassmorphism + Gradient Background

Dynamic animated gradient behind the carousel

Blurred Glass effect on mobile detail view

🖼️ Tech Stack
Technology	Purpose
HTML5	Structure and carousel layout
CSS3	Animations, transitions, responsive design, gradients
JavaScript (Vanilla)	Slider logic, transitions, event handling
📂 Project Structure
/project-folder
│
├── index.html        # Main webpage structure
├── style.css         # Styling, animations, media queries
├── script.js         # Slider logic & interactivity
└── /images           # AirPod product images

🧠 How It Works
1. Sliding Logic (script.js)

Moves items using:

listHTML.appendChild(items[0]); // next slide
listHTML.prepend(items[last]);  // previous slide


Adds classes .next or .prev to trigger CSS animations

Temporarily disables button clicks during animation

2. Detail View

Activated when user clicks SEE MORE:

Adds .showDetail class

Expands selected item

Reveals hidden .detail section

Hides other slider elements

3. CSS Animation Engine

Uses custom --itemX-transform, blur, opacity variables

Keyframe animations:

showContent

transformFromPosition2

transformFromPosition3

transformFromPosition4

transformFromPosition5

📱 Responsive Design Highlights

On mobile:

Text becomes scrollable

Detail panel uses blur (backdrop-filter)

Buttons align differently for usability

Image size auto-scales

🛠️ How to Run

Download or clone the repo:

git clone [<your-repo-url>](https://github.com/Sabaresh-Reddy5)


Make sure the images folder is placed correctly.

Open index.html in any browser.

No dependencies. Works offline.

💡 Possible Future Improvements

Add auto-slide mode

Add fetch-powered product data

Add dark mode

Add GSAP animations

Convert to React / Vue component

📝 License

This project is free to use for learning and personal use.
