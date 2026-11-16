# Weapon Detection Project

The application runs a trained YOLO model on the default webcam. It displays detections in an OpenCV window and saves detection screenshots and video to `screenshots/` and `recordings/` in the working directory.

From the repository root, install dependencies and start the app.

```sh
python -m pip install -r requirements.txt
python weapon_detection.py
```

The model weights are at `models/weapon_detection_best.pt`. The app requires a desktop session and a connected webcam. Press **Q** to exit.
