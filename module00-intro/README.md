# Introduction

Welcome to the class! This first module is about getting acclimated to the class. What coding language / environment would you like to use? Suggested is p5.js but you are welcome to create your assignments with any language or framework you like.

- [Introduction Slides](https://docs.google.com/presentation/d/1iL0bbOMbS_S8ssUGRecb7rtTZW9W9HaZrV0YKVRn36g/edit?usp=sharing)

## Emoji Key

The following emoji key will hopefully help you navigate the material for each module.

- 🚂 Video tutorial from Coding Train
- 🎥 Other video tutorial
- 📕 Reading
- 💻 Code examples
- 🎨 Creative project references

## Core Material

For each module, I will provide written and video tutorials on the topics. You can review whichever format suits you best. If the amount feels overwhelming, please reach out and we can help you narrow things down, and select a subset of the material to focus an exercise around.

### Text

- 📕 [Nature of Code Chapter 0](https://natureofcode.com/random)

### Videos

- 🚂 [Introduction to Perlin Noise](https://thecodingtrain.com/tracks/the-nature-of-code-2/noc/perlin/intro-to-perlin-noise) - 11 min
- 🚂 [Perlin noise() vs. random()](https://thecodingtrain.com/tracks/the-nature-of-code-2/noc/perlin/noise-vs-random) - 10 min
- 🚂 [Graphing 1D noise](https://thecodingtrain.com/tracks/the-nature-of-code-2/noc/perlin/graphing-1d-perlin-noise) - 13 min
- 🚂 [2D Random Walk](https://thecodingtrain.com/challenges/52-random-walker) - 15 min

### Reference Research and Artistic Work:

- [Pulse Room](https://www.lozano-hemmer.com/pulse_room.php) by Rafael Lozano-Hemmer
- [The Book of Shaders on Noise](https://thebookofshaders.com/11/) by Patricio Gonzalez Vivo & Jen Lowe
- [Quantum Cloud Sculpture](https://en.wikipedia.org/wiki/Quantum_Cloud)

## p5.js Review

If you feel you need a p5.js refresher, specifically around Object Oriented Programming in JavaScript (classes and objects), here are links to the ICM videos:

- [Full p5.js track](https://thecodingtrain.com/tracks/code-programming-with-p5-js/)
- [Starting with OOP in JavaScript](https://thecodingtrain.com/tracks/code-programming-with-p5-js/code/6-objects/2-classes)

## Supplemental Material

For each module, I will provide a list of additional video tutorials and readings that you may draw on for further exploration. It's unlikely you would be able to consume everything in one week and if you are looking for guidance about what might fit with your learning style the most, please reach out.

### More about noise

- 📕 [Characteristics of Modified Noise](https://palmdrop.site/nodes/modified-noise)
- 📕 [Perlin Noise with p5.js](http://genekogan.com/code/p5js-perlin-noise/) by Gene Kogan
- 🚂 [2D Perlin Noise](https://youtu.be/ikwNrFvnL3g?list=PLRqwX-V7Uu6ZV4yEcW3uDwOgGXKUUsPOM) - 11 min
- 🚂 [noiseDetail()](https://youtu.be/D1BBj2VaBl4?list=PLRqwX-V7Uu6ZV4yEcW3uDwOgGXKUUsPOM) - 4 min
- 🚂 [Open Simplex Noise](https://thecodingtrain.com/tracks/noise/noise/open-simplex-noise)

### More about Random Walks

- 🚂 [Diffusion-Limited Aggregation](https://thecodingtrain.com/challenges/34-diffusion-limited-aggregation) - 47 min
- 🚂 [Random Walker with Vectors and Lévy Flight](https://thecodingtrain.com/challenges/53-random-walker-with-vectors-and-levy-flight) - 16 min (Note: vectors will be explored in detail next week!)
- 🚂 [Self Avoiding Walk](https://thecodingtrain.com/challenges/162-self-avoiding-walk)

### Code Examples

- 💻 [All Nature of Code Examples](https://editor.p5js.org/codingtrain/collections/qTyT_RX11)
- 💻 [Nature of Code Chapter 0 Example Collection](https://editor.p5js.org/natureofcode/collections/q6TdDnTAp)
- 💻 [Additional Perlin Noise Example Collection](https://editor.p5js.org/codingtrain/collections/qTyT_RX11)
- 💻 [Diffusion Limited Aggregation](https://editor.p5js.org/codingtrain/sketches/XpS9wGkbB)
- 💻 [Random Walk Lévy Flight](https://editor.p5js.org/codingtrain/sketches/L24X90MBH)

## Assignment

Using the random walker as a model, develop a sketch that experiments with motion. Here are some ideas but you should feel free to develop your own.

- Use a random walker to "paint" colors.
- Try a walk in 3D, see [Quantum Cloud](http://en.wikipedia.org/wiki/Quantum_Cloud) for an example.
- Create a random walker with dynamic probabilities. For example, can you give it a 50% chance of moving in the direction of the mouse?
- Use the random walker as a template to simulate some real-world "natural" motion. Can you develop a set of rules for simulating that behavior? Ideas: nervous fly, hopping bunny, slithering snake, etc. Consider the challenge of using minimal visual design, i.e. black and white primitive shapes. Can you give your "being" a personality? Can it express emotions -- happiness, sadness, fear?

Another way of thinking about the assignment is to apply the rules of motion to another medium of expression: sound, color, number, scale...

- Walk through RGB or HSB space (as opposed to XYZ)
- Walk through Pan, Amplitude, Pitch (as opposed to XYZ)
- Plot an "orchestra" of instruments on an XY plane and move a melody through it like.
- Create a constantly morphing creature shape using `createShape()` and `vertex()`. Play with how you change the number of vertices, anchor points.

### Instructions

- Document your work on the web with a short blog post. Here are some guiding questions if you are not sure what to write about:
  - What did you originally intend to create?
  - Narrate the process of creating your sketch.
  - What resources and examples did you draw on to create your sketch? What was most helpful / least helpful from this week’s materials.
  - What problems/discoveries did you encounter along the way?
- Submit a link to your blog post to the course wiki - [ITP Section](https://github.com/nature-of-code/noc-syllabus-S25/wiki)
