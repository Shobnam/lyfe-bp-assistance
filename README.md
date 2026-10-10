# ❤️ Lyfe BP Assistance

A mobile-optimized web application for monitoring post-discharge Heart Failure patients using photoplethysmography (PPG). It features camera-based real-time heart rate detection, blood pressure estimation, and clinical risk-stratification logic.

## 🚀 Features
- **Camera & Flash Integration**: Uses WebRTC and Torch API to leverage the device's camera and flashlight for optical pulse detection.
- **Signal Processing**: Includes digital bandpass filtering and peak-detection algorithms to derive heart rate and blood pressure from raw red-channel camera data.
- **Clinical Triage Logic**: Incorporates heart failure metrics (baseline BP, 2-day weight gain, and shortness of breath) to generate Green/Yellow/Red risk statuses.
- **Local Persistence**: Saves patient history logs securely via `localStorage`.
- **Responsive UI**: Built with HTML5, Tailwind CSS, Vanilla JavaScript, and Chart.js for smooth data visualization.
