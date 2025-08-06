# Object Tracking Using OpenCV 🎥

This project demonstrates **object tracking** in video files using **OpenCV**, focusing on detecting and tracking objects based on their color.

## 📹 Overview

The program processes a pre-recorded video and performs color-based object tracking using the HSV color space. It identifies and highlights objects that fall within predefined HSV color ranges.

### 🖍️ Tracked Colors
- **Red**
- **Pink** (e.g., a butterfly)
- **White**

For each detected color, bounding boxes are drawn around the object in the video frames.

## 🛠 Technologies Used

- Python 3.x
- OpenCV
- NumPy
- FFmpeg (for video format compatibility, if needed)
- Jupyter/Google Colab (for execution)

## ⚙️ How It Works

1. A video file is loaded and processed frame by frame.
2. Each frame is converted to the HSV color space.
3. Binary masks are generated using color thresholding.
4. Contours are detected for each target color.
5. Bounding boxes are drawn and labeled on the original frame.
6. The final annotated video is saved in standard MP4 format.

## 📂 Project Structure

```
📁 object-tracking/
│
├── final_tracking.mp4 # Output video with annotations
├── input_video.mp4 # Input video used for processing
├── Object_Tracking_Code.ipynb # Colab Notebook
└── README.md # Project documentation
```


## ▶️ Running the Project

To run the project:

1. Upload a video file (e.g., MP4 format).
2. Execute the code using your preferred Python environment (Colab or local).
3. The output will be saved as an annotated video with tracked objects highlighted.

> 💡 The output video is encoded using standard codecs (e.g., H.264) for compatibility with most media players.

## 📝 Notes

- This project uses basic color segmentation and is best suited for videos with a clear background and distinct color separation.
- You can easily extend it to track more colors or different object types using advanced techniques such as feature detection or deep learning-based models.

## 📄 License

This project is released under the MIT License.
