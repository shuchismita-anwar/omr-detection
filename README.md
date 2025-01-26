# OMR Answer Sheet Grader  
Automatically grades scanned OMR sheets using OpenCV. Detects bubbles, corrects perspective, and compares answers against a key.  

### Features  
- Image preprocessing (grayscale, blur, edge detection).  
- Four-point transform for perspective correction.  
- Bubble detection and answer validation.  

### Installation  
```bash  
pip install opencv-python numpy imutils  
