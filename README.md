# Nystagmus Detection Using OpenCV

This project provides a workflow for detecting nystagmus by analyzing video frames to identify eye movements. The process involves extracting frames from a video, detecting eyes using Haar cascades, and visualizing the detected regions. The project is implemented in Python using OpenCV and Matplotlib.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Data Source](#data-source)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- Matplotlib
- Google Colab or a local environment with support for Jupyter Notebooks

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/nystagmus-detection.git
   cd nystagmus-detection
   ```

2. Install the required libraries:
   ```bash
   pip install opencv-python matplotlib
   ```

## Usage

1. **Upload a Video**: The first step is to upload a video file containing eye movements. This can be done using the `files.upload()` function provided in the notebook (if using Google Colab).

2. **Extract Frames**: The code extracts all frames from the uploaded video and displays a random selection of 5-10 frames for quick visualization.

3. **Detect Eyes**: Using a Haar cascade classifier for eye detection, the code identifies the regions of the eyes in the extracted frames. The Haar cascade file is downloaded from a specified URL if not already available.

4. **Display Results**: The identified eye regions are highlighted on the frames, and the images are displayed using Matplotlib.

## Data Source

Nystagmus Data: The primary source of data for this analysis was gotten from Youtube

## Project Structure

- `Nystagmus_detection_dis.ipynb`: Jupyter Notebook containing the code for video frame extraction, eye detection, and visualization.
- `haarcascade_eye.xml`: Haar cascade file used for detecting the eye region (downloaded automatically if not present).
- `README.md`: Documentation file (you are reading this).

## Contributing

Feel free to contribute to this project by creating pull requests or reporting issues. Make sure to follow the repository's coding style and guidelines.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
