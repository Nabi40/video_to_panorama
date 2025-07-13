#﻿# video_to_panorama  

# 🎥 Video to Panorama Generator  
**OpenCV · Computer Vision · SIFT · Homography · Stitching**

This project extracts frames from a video and stitches them into a single wide **panoramic image**.  
It uses **SIFT feature matching** and **homography transformations** to align and merge frames captured at different moments into a cohesive panorama.


------


## 📌 Features
 - ✅ End-to-end video-to-panorama pipeline  

 - 🔍 Robust feature matching using SIFT  

 - 🔁 Homography-based alignment  

 - 💾 Output saved as panorama.jpg  

 - 📏 Frame resizing for memory optimization  

 - 📊 Print logs for each step and progress info  


-----


## ❌ Limitations
- Requires a GPU/High-RAM environment (best on Google Colab Pro or local machine)    

-  Fails gracefully if not enough features or matches are found   

-  Hardcoded frame count limit and resolution (can be tuned)


----


## 📌 How It Works

### 1. Download Video  
- Downloads a sample video from a remote URL into the `video/` directory:
```python
!wget -P video/ "https://ml-hiring.fringecore.sh/capture_the_scene/video.mp4"







