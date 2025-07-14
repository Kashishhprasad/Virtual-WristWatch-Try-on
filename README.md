# Virtual Watch Try-On | Browser-Based AR Experience

A browser-based Augmented Reality (AR) application that enables users to virtually try on wristwatches in real time using their webcam. Powered by TensorFlow.js, Canvas API, and hand detection, this app provides a seamless, interactive, and responsive try-on experience—right from your browser.

 ## Overview
 
This project utilizes machine learning-based hand detection and dynamic image overlay techniques to simulate a virtual wristwatch try-on feature. The app is completely client-side, ensuring privacy and performance, and is built using HTML, JavaScript, Tailwind CSS, and TensorFlow.js Handpose model.

 ## Features
 
 Real-Time Hand/Wrist Detection
 
Leverages TensorFlow.js Handpose to detect wrist keypoints directly from your webcam stream.

 Dynamic Watch Overlay
 
Uploaded watch images are positioned and scaled in real-time to align perfectly with your wrist.

 Rotation & Scaling Support
 
Watches auto-rotate and resize based on hand orientation and depth, offering a realistic AR effect.

 Background Removal (Watch Images)
 
Automatically removes backgrounds from uploaded PNG/JPG watch images for a clean overlay.

 Zoom & Export Options
 
Users can zoom in/out and export snapshots of their virtual try-on session.

 Fully Responsive UI
 
Built with Tailwind CSS for responsiveness across devices (mobile/tablet/desktop).

 No App Download Needed
 
Runs completely in-browser—no installations, plugins, or external apps required.

## Tech Stack
 
Technology	Description

HTML5 / Canvas	Used for rendering and drawing AR overlays

Tailwind CSS	Modern and responsive utility-first CSS design

JavaScript (Vanilla)	Core application logic and event handling

TensorFlow.js	Handpose model for real-time hand detection

Canvas API	For drawing the watch overlay on video frames

 Getting Started
 
 Installation
 
Clone the repository:

git clone https://github.com/your-username/virtual-watch-tryon.git

cd virtual-watch-tryon

Open the project in a live server or your browser:

Open index.html in a web browser (preferably Chrome).

 No backend or additional setup required.

 ## Screenshots:

Real-time wrist detection with watch overlay

Watch gallery with background-removed previews

Responsive layout on desktop and mobile
