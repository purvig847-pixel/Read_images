# Read Images

A beginner Python project that reads all images from a folder, prints their size, and displays one image using matplotlib.

## Project Structure

```
Read_image/
├── main.py
├── README.md
└── Images/      # input images (jpg/png)
```

## Requirements

- Python 3.8 or higher
- opencv-python
- matplotlib

Install them with:

```
pip install opencv-python matplotlib
```

## How It Works

1. The program loops through every file in the `Images` folder using `glob`.
2. Each image is read with `cv2.imread()`.
3. If the image is read successfully, its file path and shape (height, width, channels) are printed.
4. One image is loaded with matplotlib and displayed using `plt.imshow()`, with the axes hidden.

## How to Run

1. Put your images in the `Images` folder.
2. Open the project folder in VS Code.
3. Open the terminal and run:

```
python main.py
```

## Author

Purvi

