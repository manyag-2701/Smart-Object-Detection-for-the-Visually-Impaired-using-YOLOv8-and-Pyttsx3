# Smart-Object-Detection-for-the-Visually-Impaired-using-YOLOv8-and-Pyttsx3
This system helps visually impaired individuals by detecting objects in real time and providing audio feedback. Using YOLOv3 and the COCO dataset, it identifies multiple objects through live video processing with OpenCV. Using advanced AI and computer vision technologies, it helps users understand their surroundings through sound. Once detected, objects are converted into speech using gTTS, allowing users to "hear" their surroundings. 

At the core of this system is the **YOLOv3 (You Only Look Once)** algorithm, a powerful deep-learning model trained on the **COCO dataset**. This allows it to detect and identify multiple objects in real time with high accuracy. The system processes live video feeds using **OpenCV**, an open-source computer vision library. It captures frames from the camera, analyzes them, and identifies various objects present in the environment.  

Once objects are detected, their names are converted into speech using **Google Text-to-Speech (gTTS)**. This enables users to "hear" what is around them. For example, if the system detects a "chair" or "dog," it will announce it through audio output, helping visually impaired individuals navigate safely and independently.  

### **Key Features:**  
✅ **Real-Time Object Detection** – Instantly recognizes objects in the environment.  
✅ **AI-Powered Recognition** – Uses YOLOv3 for accurate and fast identification.  
✅ **Live Video Processing** – Captures and analyzes frames using OpenCV.  
✅ **Voice Feedback System** – Converts detected objects into speech with gTTS.  
✅ **User-Friendly** – Requires minimal setup and works efficiently on basic hardware.  

### **How It Works:**  
1. The system captures live video using a camera.  
2. YOLOv3 processes the frames and detects objects in real time.  
3. OpenCV highlights detected objects by drawing boxes around them.  
4. The system uses gTTS to convert object names into speech.  
5. The audio is played, informing the user about nearby objects.  

This innovative solution enhances accessibility and independence for visually impaired individuals, making recognizing objects safer and more convenient.
