# Manim Web Physics: A fork of Manim Physics for Manim Web

## Introduction
Manim Physics is a plugin for Manim that provides support for many physics simulations, including rigid mechanics, optics, and more. This fork, `manim-web-physics`, is specifically designed to work with Manim Web, making it easier to create physics-based animations in a web environment. It's **the same code**, but `manim` dependency is replaced with `manim-web` and some minor changes to the code to ensure compatibility with Manim Web.

**Official Documentation:** https://manim-physics.readthedocs.io/en/latest/

**Note:** If something is not working, maybe you must make some minor changes to your scene's code, as Manim Web has some differences compared to Manim. Check this at [Manim Web's repository](https://github.com/MathItYT/manim).

## Installation
Just install `manim-web-physics` with Pyodide's `micropip`:

```python
import micropip

await micropip.install("manim-web-physics")
```

**So important:** You will need to download the `pymunk` wheel file from [here](https://github.com/viblo/pymunk/releases/download/7.0.1/pymunk-7.0.1-cp312-cp312-pyodide_2024_0_wasm32.whl), as it's not available in PyPI. After downloading, you can install it with:

```python
import micropip

await micropip.install("path/to/pymunk-7.0.1-cp312-cp312-pyodide_2024_0_wasm32.whl")
```
