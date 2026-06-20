# hand-gesture-music-control
what the project does
# Gestonix — Gesture & Voice Controlled Music Player

Gestonix is a web-based music player that lets you control playback using hand gestures or voice commands, instead of clicking buttons. It uses real-time hand-tracking through your webcam to recognize gestures, alongside a full authentication and personalization system.

## Features
- **Hand gesture control** — play, pause, skip tracks, and adjust volume using hand gestures, detected in real time via webcam
- **Voice command control** — control playback by speaking commands like "play," "pause," "next," or "volume up"
- **User authentication** — sign up or log in with email/password or Google sign-in
- **Favorites & recently played** — saved per user and synced across sessions
- **Light/dark theme toggle**
- **Responsive dashboard UI** with sidebar navigation, artist view, and settings panel
- **Guided onboarding** — a gesture tutorial screen shown to new users before they reach the dashboard

## Tech Stack
- HTML5, CSS3, JavaScript
- [MediaPipe Hands](https://developers.google.com/mediapipe) — real-time hand landmark detection for gesture recognition
- Web Speech API — voice command recognition
- Firebase Authentication — email/password and Google sign-in
- Firebase Firestore — storing user favorites and recently played songs

## How It Works
1. **Loading screen** checks if the user is already logged in
2. **Landing page** introduces the app and its features
3. **Login/Signup** authenticates the user via Firebase
4. **Gesture tutorial** walks new users through the supported gestures and voice commands
5. **Dashboard** is the main music player, where gesture and voice control are active

## Gesture Guide
| Gesture | Action |
|---|---|
| Open palm | Play |
| Closed fist | Pause |
| Index + middle finger up | Volume up |
| Index finger only | Volume down |
| Pinky out, thumb folded | Previous track |
| Index + pinky out, thumb folded | Next track |

## How to Run
1. Clone or download this repository
2. Open `index.html` in a browser (camera and microphone access required for full functionality)
3. Sign up or log in to reach the dashboard
4. Use hand gestures or voice commands to control music playback

## Author
Deekshith — Final Year BCA Student
