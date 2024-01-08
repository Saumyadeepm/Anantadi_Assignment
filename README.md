# Image Insertion In Video With Occlusion Handling

## Overview
_This project aims to demonstrate the insertion of an advertisement image into a video with occlusion handling. The process involves converting the video into frames, applying a provided advertisement image onto these frames using a mask, and then compiling the modified frames back into a video._

## Project Structure
- `data/`: Directory containing input video frames.
- `output_compositions/`: Directory storing compositions of frames with the inserted advertisement image.
- `output_video.mp4`: Final compiled video with the inserted advertisement.

## Steps Involved

### Step 1: Video to Image Sequence Conversion
- The input video is converted into a sequence of frames without compromising the original resolution.

### Step 2: Applying Mask on Advertisement Image
- The advertisement image provided with a mask is used to place it within the frames of the video. The mask helps in seamless integration and occlusion handling.

### Step 3: Looping Through Frames
- Each frame of the video sequence is processed by inserting the advertisement image based on the provided mask.

### Step 4: Compiling Frames into Video
- All modified frames are compiled back into a single video, resulting in the final output video.

## Usage
1. Place the input video in the specified location.
2. Provide the advertisement image with the corresponding mask.
3. Run the Python script to execute the video processing steps.
4. Retrieve the final compiled video from the output directory.

## Requirements
- `Python`
- `OpenCV`
- `Matplotlib`
- `Jupyter Notebook` 

## How to Run
1. Ensure the required libraries are installed.
2. Modify the file paths in the provided Python script as per your system.
3. Execute the Python script in a suitable environment.
4. Access the output video in the specified output directory.

## Contributing
_Contributions are welcome. Feel free to open issues or submit pull requests if you have any suggestions or improvements._
Created By [Saumyadeep Mitra](https://in.linkedin.com/in/saumyadeep-mitra-a64030236)


## License
_This project is open-source and released under the_ [MIT License](https://opensource.org/licenses/MIT)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
