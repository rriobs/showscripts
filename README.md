# extracting-chinese-subs
This repository contains code to extract Chinese hard subs from the TV series 他来了请闭眼 (*Love Me If You Dare*). 

To get started, install OpenCV, Tesseract, the `chi_sim` data pack for Tesseract, and PyOCR. 
```

Then try running `./main.py --test-all` to test the extraction algorithm on all test cases. To run it on a video file, you'll need to track down a 1280x720 video of one of the 他来了请闭眼 episodes with white hard subs at the bottom, similar to the test frames.
