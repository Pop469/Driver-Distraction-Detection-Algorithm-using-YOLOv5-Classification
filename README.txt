**Project Name: Driver Distraction Detection Algorithm using YOLOv5 with Attention Mechanism**

**GitHub Link:** [Driver Distraction Detection Algorithm](https://github.com/Pop469/Driver-Distraction-Detection-Algorithm-using-YOLOv5-Classification)

**Description:**
The Driver Distraction Detection Algorithm is a computer vision project that utilizes YOLOv5 with Attention Mechanism to detect driver distractions in real-time. The algorithm can identify various distractions such as texting, talking on the phone, eating, etc., and aims to enhance road safety by alerting drivers when distractions are detected.

**Installation and Use:**
1. Clone the repository using the following command:
   ```
   git clone https://github.com/Pop469/Driver-Distraction-Detection-Algorithm-using-YOLOv5-Classification.git
   ```

2. Install the latest version of PyTorch by following the official PyTorch installation instructions.

3. Navigate to the yolov5 folder in the cloned repository.

4. For inference:
   - Insert the images you want to test into `yolov5/data/images`.
   - Call `yolov5/classify/predict.py` from any Python CLI to perform inference using the pretrained models. The models used for prediction can be found in the "Run Index" tab of the `Results.xlsx` file.

5. For more information on YOLOv5, you can refer to the official GitHub repository: [YOLOv5 by Ultralytics](https://github.com/ultralytics/yolov5). Please note that while the prediction process remains unchanged, the training and validation of YOLOv5 have been modified for this specific project.

**Contact:**
If you have any questions, suggestions, or issues related to the project, feel free to contact the project owner at chunhau.lian@gmail.com.

Thank you for your interest in the Driver Distraction Detection Algorithm project! Stay safe on the roads!