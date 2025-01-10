<h1>
🏎️Car Lane Detection🛣️ </h1>
<Br>
<h2>Overview</h2>
<br>
This project is a Car Lane Detection system that identifies and tracks lane markings on the road using computer vision techniques. The system processes video input to detect lane lines in real-time, providing valuable information for autonomous driving and driver assistance systems.
<br>
<h2>Features</h2>

. Real-time lane detection <br>
. Supports various road conditions and lighting<br>
. Can be integrated with other driving assistance systems<br>
. Visualizes lane boundaries on video output<br>
 <h2>Demo</h2>

. Installation<br>
. Prerequisites<br>
. Python 3x<br>
. OpenCV<br>
. NumPy<br>
. Matplotlib<br>
<h2>Steps to Install</h2>

Clone the repository to your local machine.<br>
Install the required dependencies listed in the requirements.txt file.<br>
<h2>Usage</h2>
Running the Lane Detection<br>
Ensure you have a video file or a camera feed to use as input.<br>
Run the script with the video file as an argument, specifying the input and optionally the output path and debug mode.<br>
<h2>Parameters</h2>
--input: Path to the input video file or camera feed.<br>
--output: (Optional) Path to save the output video with detected lanes.<br>
--debug: (Optional) Enable debug mode to visualize intermediate steps.<br>
<h2>Project Structure</h2>
README.md: Project overview and instructions<br>
requirements.txt: Python dependencies<br>
lane_detection.py: Main script for lane detection<br>
utils.py: Helper functions<br>
test_video.mp4: Sample video for testing<br>
output/: Directory for saving output videos<br>
<h2>How It Works</h2>
Preprocessing: The video frames are converted to grayscale and blurred to reduce noise.<br>
Edge Detection: The Canny edge detector is applied to identify edges in the frame.<br>
Region of Interest: A mask is applied to focus on the region of the road where lanes are likely to be.<br>
Hough Transform: The Hough Transform is used to detect lane lines from the edges.<br>
Lane Overlay: The detected lanes are overlaid on the original video frame.<br>
<h2>Contributing</h2>
Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.<br>
<h2>
Steps to contribute:</h2>

Fork the repository.<br>
Create a new branch for your feature.<br>
Commit your changes.<br>
Push to the branch.<br>
Create a new Pull Request.<br>
<h2>License</h2>
This project is licensed under the MIT License. See the LICENSE file for details.

<h2>Acknowledgements</h2>
OpenCV<br>
NumPy<br>
Matplotlib<br>
