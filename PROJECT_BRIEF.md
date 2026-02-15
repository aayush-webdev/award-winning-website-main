# Project Brief: Zentry Project Clone

## 🎙️ Elevator Pitch
"I built a high-performance, visually immersive gaming landing page that replicates the award-winning Zentry website. The project focuses on bridging Web2 and Web3 gaming concepts into a unified 'Play Economy'. It features complex scroll-triggered animations, video backgrounds, and a responsive Bento grid layout, all built with React, Tailwind CSS, and GSAP."

## 🔑 Key Technical Highlights
- **Advanced Animations**: utilized **GSAP (GreenSock)** for high-performance animations, including scroll-triggered image reveals, video scaling effects, and text animations.
- **Modern UI/UX**: Implemented a **Bento Grid** layout with 3D tilt effects for a premium, interactive feel.
- **Performance Optimization**: Managed multiple video backgrounds and heavy assets efficiently using React's `useEffect` and `useRef` hooks to ensure smooth playback and loading.
- **Responsive Design**: Ensured a seamless experience across all devices using **Tailwind CSS**'s utility-first approach.
- **Component Architecture**: Structured the application into reusable components like `Hero`, `Features`, `About`, and `Story` to maintain a clean and scalable codebase.

## 💡 Challenges & Solutions
- **Challenge**: Synchronizing complex animations with user scroll without causing performance bottlenecks.
  - **Solution**: detailed use of `ScrollTrigger` from GSAP to pin elements and scrub animations smoothly based on scroll position.
- **Challenge**: Handling multiple video elements without impacting load times.
  - **Solution**: Implemented a loading state that waits for a specific number of videos to load before displaying the content, ensuring a glitch-free initial experience.

## ⚠️ Disclaimer
This project uses assets and design concepts from the original Zentry website for educational purposes to demonstrate proficiency in modern frontend development techniques.
