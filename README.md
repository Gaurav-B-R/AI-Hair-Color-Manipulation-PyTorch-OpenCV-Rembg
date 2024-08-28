# Advanced AI-Based Hair Color Manipulation Using PyTorch, OpenCV, and Background Removal Techniques

## About the Project
This project is an advanced AI-based solution for hair color manipulation in images, even with complex backgrounds. I have built upon existing hair color models and further tuned them to enhance the detection of hair regions, especially when the background includes multiple objects or complex elements. This improved model provides more accurate and realistic results in various environments.

## Features
- Automatically detects and removes backgrounds for better hair region detection.
- Applies accurate hair color changes even in images with complex backgrounds.
- Ability to stitch the modified image back into the original image without backgrounds.
- Well-organized code with clear comments for easy understanding and extensibility.

## Project Demo
### Original Image vs Hair Color Changed Image

![Hair Color Changing Demo](https://github.com/Gaurav-B-R/Hair-Color-Changin/blob/main/Hair%20Color%20Changed%20Image.png?raw=true)

## How It Works
The solution involves the following steps:

1. **Remove Background**: Remove the background from the image to isolate the human region.
2. **Detect and Crop Hair Region**: Crop and detect the relevant hair area using BiSeNet models.
3. **Apply Hair Color**: Apply custom colors to the detected hair region using color masks and enhancements.
4. **Stitch Image Back**: Stitch the modified image back into the original image without backgrounds.

## Installation and Usage

To get started with this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/hair-color-changing-ai.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the main script to change the hair color of an image:
    ```bash
    python main.py --img-path your_image.jpg
    ```

## Credits
This project builds upon the excellent work from the following repositories:

- [Face Makeup PyTorch](https://github.com/zllrunning/face-makeup.PyTorch)
- [Additional Gist for Models](https://gist.github.com/757e63802b0b28fbdab9d98b2e646ac2)

## Author
Project developed by **Gaurav Bharatavalli Rangaswamy**

GitHub: [github.com/Gaurav-B-R](https://github.com/Gaurav-B-R)

