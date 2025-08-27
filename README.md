# Ambient Noiz

A generative ambient synthesizer for focus, relaxation, and sleep. Born out of a need for an ad-free white noise machine and evolved into something much more musical.

![1000013845](https://github.com/user-attachments/assets/64caedde-2d77-4e6e-872e-955f2cd108a3)


---

### The Story Behind This Project

This project started on a vacation with a simple problem: I needed a white noise generator to help me sleep, but I didn't want to use YouTube. The last thing you want when you're drifting off is a loud ad waking you up. I figured, "How hard can it be to generate some noise in a browser?"

So, I built a quick and simple white noise machine in a single HTML file. It worked perfectly.

But then I got curious. The Web Audio API is incredibly powerful, and I started wondering if I could make something more interesting than just static. This led to experimenting with different noise colors (pink, brown), filters, and eventually, oscillators.

What began as a practical tool to block out noise evolved into this—a generative ambient synthesizer that creates beautiful, non-repeating soundscapes. It's a testament to creative coding and a fun reminder of how a simple need can blossom into a much larger passion project.

### How It Works

`Ambient Noiz` is a self-contained synthesizer that runs entirely in your web browser. It procedurally generates musical notes from a harmonious scale and plays them with a rich, evolving pad sound. The addition of a custom-built reverb creates a deep, atmospheric soundscape that never repeats itself. It’s perfect for background music while working, meditating, or falling asleep.

### Features

*   **Generative Soundscapes:** Creates an endless, non-repeating stream of calming ambient music.
*   **Harmonious by Design:** Uses a C Minor Pentatonic scale to ensure the notes always sound pleasant together.
*   **Rich, Evolving Pad Sound:** Each note is generated with multiple oscillators and a slow-attack envelope for a classic, lush ambient feel.
*   **Built-in Reverb:** A custom convolver reverb adds a sense of space and depth.
*   **No Ads, No Interruptions:** Just pure, uninterrupted sound.
*   **Single File, No Installation:** It's all contained in one HTML file. No servers, no setup.

### How to Use

Since this is a simple, self-contained HTML file, you don't need to clone a repository or install anything.

1.  Go to the [repository files](https://github.com/dovvnloading/Ambient-noiz).
2.  Download the `index.html` file.
3.  Open it in any modern web browser (like Chrome, Firefox, or Safari).

That's it! Press the "Begin" button to start the soundscape.

### Controls

*   **Density:** Controls how frequently new notes are played. Move the slider to the right for a more sparse, minimalist texture, and to the left for a denser, more active soundscape.
*   **Tone:** Adjusts a low-pass filter. A lower value creates a softer, more muted sound, while a higher value makes it brighter and clearer.
*   **Reverb:** Controls the amount of the reverb effect. Increase it for a vast, cavernous sound, or decrease it for a more intimate, dry feel.

### Tech Stack

*   **HTML & CSS:** For the structure and styling of the interface.
*   **JavaScript (ES6):** For the application logic.
*   **Web Audio API:** The core technology used for all audio synthesis, scheduling, and effects.
