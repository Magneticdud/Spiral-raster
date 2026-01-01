# 🎨 Spiral Raster - SVG Converter

Convert raster images (JPG, PNG, GIF) into beautiful vector spiral patterns using Paper.js.

## 📋 Overview

This tool transforms bitmap images into unique SVG spiral patterns using three different tracing methods. The application analyzes the brightness values of your image and creates vector spirals that represent the original image in an artistic, abstract way.

## ✨ Features

- **Three Tracing Methods:**
  - 🔵 **Round Spiral** - Creates smooth, circular spiral patterns
  - 🟦 **Square Spiral** - Generates angular, rectangular spiral patterns  
  - ➖ **Parallel Lines** - Produces parallel line patterns

- **Interactive Controls:**
  - Drag-and-drop image loading
  - Real-time parameter adjustment with visual handles
  - Adjustable spiral center position
  - Customizable grid spacing and segment count
  - Angle rotation control

- **Vector Output:**
  - Export as SVG for infinite scalability
  - Compatible with Adobe Illustrator and other vector editors
  - Clean, editable paths

## 🚀 Getting Started

### Prerequisites

No installation required! This is a standalone HTML file that runs entirely in your browser.

### Usage

1. **Open the Application**
   - Simply open `spiral-raster-converter.html` in any modern web browser

2. **Load an Image**
   - Drag and drop a JPG, PNG, or GIF file onto the canvas area
   - Or click the canvas to select a file

3. **Choose a Tracing Method**
   - Select one of the three available methods:
     - Round Spiral
     - Square Spiral (default)
     - Parallel Lines

4. **Adjust Parameters**
   - Use the orange control handles to modify:
     - **Center position** - Where the spiral starts
     - **End position** - How far the spiral extends
     - **Step size** - Spacing between spiral segments
     - **Angle** - Rotation and density of the pattern
     - **Sub-steps** - Fine-tuning of segment divisions

5. **Generate the Spiral**
   - Click the **"Trace Image"** button to create the vector pattern

6. **Export**
   - Click **"Download SVG"** to save your creation
   - Open the SVG in vector editing software for further refinement

## 🎯 How It Works

The application uses Paper.js to:
1. Sample pixel brightness values from your raster image
2. Generate spiral or line paths based on the selected method
3. Vary the path width according to the darkness of the sampled pixels
4. Create smooth vector curves that represent the original image

Darker areas in your image result in thicker spiral segments, while lighter areas produce thinner segments, creating a recognizable representation of the original image.

## 🛠️ Technical Details

- **Built with:** HTML5, CSS3, JavaScript
- **Library:** [Paper.js](http://paperjs.org/) v0.12.17
- **Canvas-based:** Uses HTML5 Canvas for rendering
- **No server required:** Runs entirely client-side

## 📸 Best Practices

For optimal results:
- Use high-contrast images
- Images with clear subjects work best
- Experiment with different tracing methods
- Adjust the grid parameters to match your image complexity
- Try different angles for unique effects

## 🙏 Credits

**This project is based 100% on the original tutorial:**

[Spiral Raster Script Tutorial](https://web.archive.org/web/20200212232401/http://vectorboom.com/load/tutorials/effects/spiral_raster_script/3-1-0-501) by VectorBoom (some squatter stole their domain, now it's not accessible anymore)

All credit for the original concept, algorithm, and implementation goes to the creators at VectorBoom. This version has been adapted with an improved user interface and Italian localization.

## 📄 License

MIT License - Feel free to use and modify this tool for your own projects.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 💡 Tips & Tricks

- **Portrait photos** work particularly well with round spirals
- **Geometric patterns** are great for square spirals
- **Landscapes** can create interesting effects with parallel lines
- Adjust the step size to control the level of detail
- Smaller angles create denser, more detailed spirals
- Larger spacing creates more abstract representations

## 🔗 Resources

- [Paper.js Documentation](http://paperjs.org/reference/)
- [Original VectorBoom Tutorial (Archive)](https://web.archive.org/web/20200212232401/http://vectorboom.com/load/tutorials/effects/spiral_raster_script/3-1-0-501)