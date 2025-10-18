# Pelican on a Bicycle - Generative Art Project

## Overview

This project contains an algorithmic art piece exploring the whimsical concept of "a pelican on a bicycle." It combines computational aesthetics, generative algorithms, and interactive visualization to create a unique artistic expression.

## Files

1. **pelican-bicycle-philosophy.md** (8KB)
   - Comprehensive philosophical framework for the art piece
   - Explores the contrast between organic and mechanical forms
   - Discusses balance, momentum, circles, and the joy of absurdity
   - Contains aesthetic principles and generative algorithm theory

2. **pelican-bicycle-viewer.html** (20KB)
   - Complete interactive p5.js visualization
   - Fully self-contained HTML file with embedded JavaScript
   - Features a generative pelican character with realistic behaviors
   - Includes a functional bicycle with spinning wheels and physics
   - Interactive elements: mouse movement creates wind, clicking makes the pelican flap

## How to View

Simply open `pelican-bicycle-viewer.html` in any modern web browser. No build process or dependencies required beyond an internet connection (for loading the p5.js library from CDN).

## Features

### Visual Elements
- **Pelican**: Organic curves, wing flapping, breathing pouch, bobbing motion
- **Bicycle**: Geometric precision, spinning wheels with spokes, pedals, frame
- **Background**: Dynamic gradient sky, floating clouds, ambient birds
- **Particles**: Environmental effects that enhance the scene

### Interactions
- **Mouse Movement**: Creates wind force that affects both pelican and bicycle
- **Mouse Click**: Triggers wing flapping animation
- **Responsive**: Adapts to window resizing

### Technical Highlights
- Pure p5.js implementation with no external dependencies
- Object-oriented design with Pelican, Bicycle, and Particle classes
- Time-based animations using sine waves and noise functions
- Dynamic color palettes that shift with time
- Smooth motion through lerp and easing functions

## Philosophy

The piece embodies several key concepts:
- The harmony between natural grace and mechanical precision
- Balance through perpetual motion
- The joy found in absurd juxtapositions
- Computational aesthetics as a medium for whimsy

## Technical Details

- **Canvas**: Full window responsive canvas
- **Frame Rate**: 60 FPS default (p5.js)
- **Color Scheme**: Sky blues, pelican whites/oranges, bicycle reds and metallics
- **Animation**: Continuous generative animation, never repeats exactly
- **Performance**: Optimized for smooth rendering on modern browsers

---

*"In the space between the probable and the impossible, there rides a pelican on a bicycle, forever balanced on the edge of wonder."*
