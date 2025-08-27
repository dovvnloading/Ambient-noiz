<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>


# Ambient Noiz

An advanced noise generator for focus, relaxation, and sleep. No ads, no interruptions—just pure, customizable sound.

![1000013845](https://github.com/user-attachments/assets/3afac907-a8b7-4d31-aa8d-db1ad94ee633)


---

### The Story Behind This Project

This project started on a vacation with a simple problem: I needed a white noise generator to help me sleep, but I didn't want to use YouTube. The last thing you want when you're drifting off is a loud ad waking you up. I figured, "How hard can it be to generate some noise in a browser?"

So, I built a quick and simple white noise machine in a single HTML file. It worked perfectly for its intended purpose.

But then I got curious. The Web Audio API is incredibly powerful, and I started wondering if I could create something more flexible than just a basic hiss. This led to experimenting with different "colors" of noise and adding more controls.

What began as a practical tool to block out noise evolved into this—an advanced noise generator with multiple sound types and a tone control to shape the sound exactly how you like it. It’s a testament to how a simple need can blossom into a fun and useful project.

### Features

*   **Three Noise Colors:** Choose from three distinct types of noise to find the sound that works best for you.
    *   **White Noise:** A sharp, hissing sound that contains all frequencies at equal intensity. Great for masking high-pitched noises.
    *   **Pink Noise:** A more balanced, waterfall-like sound with reduced high frequencies. Many find it less harsh than white noise.
    *   **Brown Noise:** A deep, rumbling sound that emphasizes low frequencies. Excellent for a calming, deep hum.
*   **Adjustable Tone Control:** A low-pass filter lets you make the noise "softer" by rolling off the sharp high frequencies, giving you full control over the sound's character.
*   **Simple Volume Control:** Easily set the perfect volume for your environment.
*   **Ad-Free & Uninterrupted:** Designed for sleep and focus, so there will never be ads or interruptions.
*   **Single File, Zero Installation:** It's all contained in one HTML file. No servers, no setup, no dependencies.

### How to Use

Since this is a simple, self-contained HTML file, you don't need to clone a repository or install anything.

1.  Go to the repository files section at [https://github.com/dovvnloading/Ambient-noiz](https://github.com/dovvnloading/Ambient-noiz).
2.  Download the `index.html` file.
3.  Open that file in any modern web browser (like Chrome, Firefox, or Safari).

That's it! Press the "Start" button to begin generating sound.

### Controls

*   **Noise Type Buttons:** Select **White**, **Pink**, or **Brown** to instantly switch between the different noise colors.
*   **Volume Slider:** Adjusts the overall loudness of the sound.
*   **Tone Slider:** Controls the character of the noise. Move it to the left to filter out high frequencies for a softer, deeper sound. Move it to the right for a brighter, crisper sound.

### Tech Stack

*   **HTML & CSS:** For the structure and styling of the interface.
*   **JavaScript (ES6):** For the application logic.
*   **Web Audio API:** The core technology used for all sound generation and processing.
