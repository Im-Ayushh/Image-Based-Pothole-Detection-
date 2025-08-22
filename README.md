# Image-Based-Pothole-Detection-
An interactive web-based pothole detection simulation app built with HTML, CSS, and JavaScript.

A modern, interactive web app that simulates pothole detection on road images. Users can sign up/login, upload an image, “scan” for potholes, and view a visual report of the findings. The UI is lightweight, responsive, supports dark/light mode, and stores user/auth data locally—no backend required.

Features:
- **User Authentication:** Signup/login with credentials, managed locally in the browser.
- **Image Upload:** Upload a photo (JPG, PNG, etc.) of a road scene to the dashboard.
- **Simulated Detection:** Click ‘Scan’ to simulate pothole detection. The app marks potholes with visible, glowing red dots—always on the road, never in the sky.
- **Result Reports:** Get an overview: pothole count, severity breakdown, and estimated distances from the “car.”
- **Image Download:** Download the result image, including pothole highlights.
- **Dark/Light Mode:** Easily switch modes with a single toggle.
- **No Backend Required:** All logic runs in the browser, user data is stored in `localStorage`.

---

## Project Structure

index.html # Main HTML UI
style.css # Modern, responsive styling (dark/light mode)
script.js # All interactivity, dashboard logic, and simulation

---

## How It Works

- The "Scan" feature simulates pothole detection using randomly placed markers.
- Dots are never placed in the sky, only along the road section to enhance realism.
- User credentials are securely (but simply) stored in localStorage for demo purposes.

---

## Limitations

- This is a **frontend-only simulation**. No AI, server-side, or genuine image analysis is performed.
- For a real detection pipeline, you would replace the simulated logic with a backend model (e.g., YOLO, TensorFlow).

---

## Possible Improvements

- Integrate a real pothole detection model via API.
- Store and display user history or previous detection results.
- Enhance mobile responsiveness further.
- Add more advanced user roles and permissions.
- Provide image cropping/adjustment pre-scan.

---

## Credits

Developed for demo and educational purposes.
