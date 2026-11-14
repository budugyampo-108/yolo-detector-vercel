# Image Detector (Web and Mobile, YOLO11)

A Progressive Web App that runs three YOLO11 detection models (exported to ONNX)
directly in the browser with ONNX Runtime Web. It works on a laptop and on a phone,
where it can be installed to the home screen and can use the camera.

## Features
- Upload an image or take a photo with the phone camera
- Three models run on the image; each reports its confidence percentage
- "No match (0%)" when nothing trained is detected
- Installable (PWA), no image leaves the device

## Structure
- `index.html` - the app (interface and detection code)
- `manifest.json`, `sw.js`, `icons/` - PWA files
- `models/` - `exp5.onnx`, `exp6.onnx`, `exp8.onnx`
- `vercel.json` - hosting settings

## Run locally
```
python -m http.server 8000
```
Open http://localhost:8000

## Live app
ADD YOUR VERCEL LINK HERE

Author: Francis, Pentecost University College
