<div align="center">

<img src="https://www.google.com/search?q=https://img.shields.io/badge/Status-Active-success%3Fstyle%3Dfor-the-badge" alt="Status" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Version-1.0.0-blue%3Fstyle%3Dfor-the-badge" alt="Version" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/License-MIT-yellow%3Fstyle%3Dfor-the-badge" alt="License" />

<br />
<br />

<h1 style="font-size: 3rem; color: #00F3FF; text-shadow: 0 0 20px #00F3FF;">
⚡ NeonGlass Calculator
</h1>

<p style="font-size: 1.2rem; color: #cccccc;">
A futuristic, glassmorphic calculator suite with a procedural melodic audio engine.
</p>

<p>
<a href="https://[YOUR_USERNAME].github.io/[YOUR_REPO_NAME]/"><strong>View Live Demo »</strong></a>
<br />
<br />
<a href="#-features">Features</a>
·
<a href="#-installation">Installation</a>
·
<a href="#-customization">Theming</a>
</p>
</div>

<hr />

🔮 About The Project

NeonGlass Calculator is not just a math tool; it's an interactive UI experiment. Built with a focus on aesthetics and auditory feedback, it combines advanced CSS3 Glassmorphism with a custom JavaScript audio synthesizer.

Instead of playing static .mp3 files, the application generates audio in real-time using the Web Audio API, playing notes from a C Major Pentatonic scale to create a harmonious, melodic experience with every keystroke.

⚡ Built With

✨ Features

🎨 Visuals & UI

Glassmorphism Architecture: Real-time backdrop filters, translucent layers, and neon glow effects.

Neon Color Palette: Utilizing Krypton Green, Cyber Pink, and Cyan.

Responsive Layout: Flexbox and Grid-based design that adapts from desktop split-views to mobile single-columns.

Smooth Animations: fadeIn and slideIn transitions for all interface elements.

🎹 Melodic Audio Engine

Procedural Audio: No external audio assets. All sounds are synthesized sine waves generated via the AudioContext API.

Harmonic Scaling: Input keys map to specific frequencies in the pentatonic scale.

ADSR Envelope: Custom Attack-Decay envelopes for soft, pleasant keypress sounds.

🧮 Functionality

Standard Computation: Arithmetic, Powers, and standard operations.

History Sidebar: A slide-out panel that tracks previous calculations (stores up to 20 entries).

Equation Solvers: Built-in UI for Linear and Quadratic equation solving.

Settings Persistence: Remembers your Sound/Vibration preferences via localStorage.

🚀 Installation

This is a vanilla web project. It requires no build steps, no npm, and no bundlers.

Clone the repo

git clone [https://github.com/](https://github.com/)[YOUR_USERNAME]/[YOUR_REPO_NAME].git


Open the project
Simply navigate to the folder and open index.html in your browser.

🎨 Customization

The design relies heavily on CSS Variables. You can instantly change the entire theme by modifying the :root variables in style.css.

:root {
    /* Backgrounds */
    --bg-color: #050505;
    --glass-bg: rgba(20, 20, 20, 0.5);

    /* Neon Accents - Change these to re-theme! */
    --neon-pink: #FF0099;
    --neon-cyan: #00F3FF;
    --neon-purple: #9D00FF;
    --neon-krypton: #00FF41; 
}


🕹️ Controls

Key/Action

Result

Note/Frequency

Numbers (0-9)

Input Number

Pentatonic Scale (C4-A5)

Operators (+ - * /)

Set Operator

F4 (Distinct tone)

Equals (=)

Calculate

C5 Chord (Resolution)

C / DEL

Clear / Delete

G3 (Low Reset)

History Click

Load Result

G4

🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📝 License

Distributed under the MIT License. See LICENSE for more information.

<div align="center">
<p>Made with ❤️ and Neon by <a href="https://github.com/[YOUR_USERNAME]">[YOUR_NAME]</a></p>
</div>
