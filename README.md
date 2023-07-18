# Virtual Painter

Virtual Painter is a computer vision project that utilizes the OpenCV library to create a virtual painting experience. The program detects colors and movements of objects captured by a camera and allows users to paint on a virtual canvas in real-time.

## Features

- Detects and tracks specific colors in the video stream using the HSV color space.
- Identifies the contours of colored objects and extracts their center points.
- Allows users to paint on a virtual canvas by mapping the detected points to corresponding positions.
- Supports multiple colors for painting simultaneously.
- Provides an interactive and immersive painting experience.

## Requirements

- C++ compiler
- OpenCV library

## Usage

1. Clone the repository: `git clone https://github.com/jakubpiwowarski/virtual-painter.git`
2. Navigate to the project directory: `cd virtual-painter`
3. Compile the source code: `g++ virtual_painter.cpp -o virtual_painter `pkg-config --libs opencv``
4. Run the program: `./virtual_painter`

## How It Works

1. The program captures frames from the camera and converts them to the HSV color space.
2. It applies color thresholding to identify the desired colors using predefined color ranges.
3. Contours of the colored objects are extracted, and their center points are determined.
4. The detected points are mapped to corresponding positions on the virtual canvas.
5. Users can interact with the program by moving objects or changing their colors to paint on the canvas.

## Contributing

Contributions are welcome! If you find any issues or have ideas for improvements, please open an issue or submit a pull request.
