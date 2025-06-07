# Computer_vision_openCV_repo
everything you need to know in one place
# OpenCV Bootcamp Examples

This repository contains a collection of Python scripts and Jupyter-converted notebooks demonstrating fundamental OpenCV operations and workflows. These examples serve as a hands‑on companion to the OpenCV Bootcamp course and provide ready-to-run code for:

* **Getting Started with Images**
* **Basic Image Manipulation**
* **Image Annotation**
* **Basic Image Enhancement**
* **Video Writing with OpenCV**

More examples and deeper topics will be added over time, so stay tuned!

---

## 📂 Repository Structure

```
├── 01_getting_started_with_images.py            # Read/display images, inspect properties
├── 02_basic_image_manipulations_crop_resize_flip_and_modify_pixels.py
│   # Pixel access, cropping, resizing, flipping
├── 03_annotating_images.py                     # Draw lines, circles, rectangles, add text
├── 04_basic_image_enhancement_mathematical_operations.py
│   # Brightness/contrast, thresholding, bitwise operations
├── 06_writing_video_using_opencv.py            # Capture and write video in AVI/MP4
├── Manual_Template.docx                        # Base template for manual/report
└── README.md                                   # This file
```

## 🛠️ Requirements

* Python 3.6+
* OpenCV (`opencv-python`)
* NumPy
* Matplotlib

Install dependencies with:

```bash
pip install opencv-python numpy matplotlib
```

## 🚀 Usage

Each script is standalone. To run an example, invoke it from the command line. For instance:

```bash
python 01_getting_started_with_images.py
```

To switch between video files and webcam in the video-writing example:

```bash
python 06_writing_video_using_opencv.py     # uses hardcoded path or change source variable
python 06_writing_video_using_opencv.py --video my_clip.mp4
```

*(Refer to each script’s header comments for more details and optional flags.)*

## 📝 Contributing

This is a personal collection—feel free to fork and adapt. I’m planning to add more tutorials on:

* Advanced filtering (Gaussian, bilateral, morphological)
* Object detection and tracking
* GPU acceleration with OpenCV CUDA modules
* Real-time camera pipelines

If you have suggestions or improvements, open an issue or submit a pull request.

## 🔮 Future Work

I will be expanding this repo with additional examples and deeper dives into computer vision topics, so watch this space for new scripts, notebooks, and documentation!
