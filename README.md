# **Rasterizing Lines and Triangles**

## **Overview**
This assignment involves implementing rasterization algorithms to draw lines and solid triangles using a simple framebuffer. The goal is to create a JavaScript application that allows users to specify vertices, points, lines, and triangles through text input and visualize the rasterized output in a web browser.

## **Getting Started**
To run and develop this assignment, follow these steps:
- Start a local HTTP server in the directory containing a3.html.
  - On MacOS and Linux, you can use `python3 -m http.server` in a terminal.
  - For Windows or troubleshooting, refer to these instructions.
- Once the HTTP server is running, navigate your browser to `http://localhost:8000/a3.html`.
- If changes in the code are not reflected after refreshing, try clearing the browser cache.

## **Implementation Instructions**
The implementation involves the following steps:
- **Line Rasterization**: Implement algorithms for rasterizing lines with constant color values and handle cases of different slopes.
- **Color Interpolation**: Implement linear interpolation of RGB color values along lines.
- **Triangle Inside-Outside Test**: Implement a function to determine if a pixel is inside a triangle.
- **Triangle Rasterization**: Implement triangle rasterization using the inside-outside test.
- **Barycentric Color Interpolation**: Implement color interpolation within triangles using barycentric coordinates.

## **File Structure**
- `a3.html`: HTML file containing the interface and canvas for visualization.
- `a3.js`: JavaScript file containing the implementation of rasterization algorithms.
- `README.md`: Documentation file (this file) providing an overview of the assignment.

## **Usage**
- Edit the text box in the interface to specify vertices, points, lines, and triangles.
- Click the "Update" button to refresh the image output.
