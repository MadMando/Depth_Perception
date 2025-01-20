# Depth Perception with ML-Depth Pro 🚀

## Overview
This repository expands upon [Apple's ML-Depth Pro](https://github.com/apple/ml-depth-pro/tree/main) to showcase depth perception in images and real-time video feeds. My goal was to explore the model's capabilities and extend its use to live video streams.

## Features
- **Image-based depth perception:** Apply the model to static images.
- **Video demonstration:** Generate depth maps for pre-recorded videos.
- **Live video integration:** Real-time depth perception with a live feed.

## Getting Started

### Prerequisites
- Python 3.x
- PyTorch
- OpenCV
- Additional libraries (see `requirements.txt`)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/username/ml-depth-perception.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
1. Run the static image demo:
   ```bash
   python src/depth_model.py --input data/sample_images/image1.jpg
   ```
2. Run the video demo:
   ```bash
   python src/depth_model.py --video examples/video.mp4
   ```
3. Start the live feed:
   ```bash
   python src/live_video_feed.py
   ```

## Results

### Image Demo
![Example](examples/image_demo.jpg)

### Live Video
[Live Video Demo](examples/live_feed_demo.mp4)

## Acknowledgements
This project builds upon the [ML-Depth Pro repository](https://github.com/apple/ml-depth-pro/tree/main) developed by Apple Inc. I would like to acknowledge the fantastic work of Apple's Machine Learning team in creating the original model.

### License
This project incorporates software provided by Apple Inc., which is licensed under the following terms:

```
Copyright (C) 2024 Apple Inc. All Rights Reserved.

Disclaimer: IMPORTANT:  This Apple software is supplied to you by Apple
Inc. ("Apple") in consideration of your agreement to the following
terms, and your use, installation, modification or redistribution of
this Apple software constitutes acceptance of these terms.  If you do
not agree with these terms, please do not use, install, modify or
redistribute this Apple software.

In consideration of your agreement to abide by the following terms, and
subject to these terms, Apple grants you a personal, non-exclusive
license, under Apple's copyrights in this original Apple software (the
"Apple Software"), to use, reproduce, modify and redistribute the Apple
Software, with or without modifications, in source and/or binary forms;
provided that if you redistribute the Apple Software in its entirety and
without modifications, you must retain this notice and the following
text and disclaimers in all such redistributions of the Apple Software.
Neither the name, trademarks, service marks or logos of Apple Inc. may
be used to endorse or promote products derived from the Apple Software
without specific prior written permission from Apple.  Except as
expressly stated in this notice, no other rights or licenses, express or
implied, are granted by Apple herein, including but not limited to any
patent rights that may be infringed by your derivative works or by other
works in which the Apple Software may be incorporated.

The Apple Software is provided by Apple on an "AS IS" basis.  APPLE
MAKES NO WARRANTIES, EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION
THE IMPLIED WARRANTIES OF NON-INFRINGEMENT, MERCHANTABILITY AND FITNESS
FOR A PARTICULAR PURPOSE, REGARDING THE APPLE SOFTWARE OR ITS USE AND
OPERATION ALONE OR IN COMBINATION WITH YOUR PRODUCTS.

IN NO EVENT SHALL APPLE BE LIABLE FOR ANY SPECIAL, INDIRECT, INCIDENTAL
OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) ARISING IN ANY WAY OUT OF THE USE, REPRODUCTION,
MODIFICATION AND/OR DISTRIBUTION OF THE APPLE SOFTWARE, HOWEVER CAUSED
AND WHETHER UNDER THEORY OF CONTRACT, TORT (INCLUDING NEGLIGENCE),
STRICT LIABILITY OR OTHERWISE, EVEN IF APPLE HAS BEEN ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
```

For more details, refer to the original [ML-Depth Pro repository](https://github.com/apple/ml-depth-pro/tree/main).

## Notes
This repository is for educational and research purposes only. Please ensure compliance with Apple's license terms and conditions if you plan to redistribute or modify this work.

---

#License Information
