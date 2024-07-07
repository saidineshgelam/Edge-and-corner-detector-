This code reads a video frame by frame and performs several image processing tasks. It first splits the video into frames and checks for the
variance of Laplacian to determine if the frame is blurry. If the frame is sufficiently sharp, it converts it to grayscale, applies edge detection
using the Canny algorithm, and then detects lines using the Hough transform. The detected lines are used to find intersections, which are then
marked on the original frame. Additionally, the code applies the Harris corner detection algorithm to verify the detected corners. Detected
corners are marked on the original frame using the Harris corner detector. Finally, the code writes the processed frames to an output video file.
The process is repeated until all frames in the video are processed. The output includes the number of frames processed, the count of non-
blurry frames, and the count of removed frames due to blurriness.

https://github.com/saidineshgelam/Edge-and-corner-detector-/assets/144295692/4ce4f8d8-f700-4410-b164-eca970b51280

