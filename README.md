# AI-Based Pupil Detection and Eye Tracking System

This project implements a computer vision–based pupil detection system using facial landmark analysis.
The system detects eye regions from human face images and accurately localizes pupil centers.

---

## 📌 Overview

The system uses Dlib’s 68-point facial landmark detector to extract eye coordinates.
Dark pixel analysis and Hough Circle Transform are applied to identify pupil locations.
If circle detection fails, fallback logic is used to estimate pupil position.

---

## 🛠 Tech Stack
- Python
- OpenCV
- Dlib
- NumPy
- Image Processing
- Computer Vision

---

## 🚀 Features
- Face detection using frontal face detector
- 68-point facial landmark extraction
- Eye region localization using landmark indices
- Pupil detection using pixel-intensity analysis
- Circle detection using Hough Circle Transform
- Fallback logic for robust pupil localization
- Batch image processing with annotated outputs

---

## 🔄 Project Workflow
1. Detect face from input image
2. Extract 68 facial landmarks using Dlib
3. Crop left and right eye regions
4. Identify dark pixels corresponding to pupil
5. Apply Hough Circle Transform for pupil detection
6. Annotate and save output images

---


### Results

<img src="output/1.jpg" width = "300" height = "280"/> <img src="output/2.jpg" width = "300" height = "280"/>
<img src="output/3.jpg" width = "300" height = "280"/> <img src="output/4.jpg" width = "300" height = "280"/>

## Want to Contribute?

- Created something awesome, made this code better, added some functionality, or whatever (this is the hardest part).
- [Fork it](http://help.github.com/forking/).
- Create new branch to contribute your changes.
- Commit all your changes to your branch.
- Submit a [pull request](http://help.github.com/pull-requests/).

-----

## Need Help? 

We also provide a free, basic support for all users who want to use this AI ML based pupil detection techniques for their projects. In case you want to customize this Pupil detection technique for your development needs, then feel free to contact our [AI ML developers](https://www.weblineindia.com/ai-ml-dl-development.html).

-----

## Collection of Components

We have built many other components and free resources for software development in various programming languages. Kindly click here to view our [Free Resources for Software Development](https://www.weblineindia.com/communities.html).

------

## Changelog

Detailed changes for each release are documented in [CHANGELOG.md](./CHANGELOG.md).

## Credits

Refered dlib face detection lib [Dlib](http://dlib.net/python/index.html).

## License

[MIT](LICENSE)

[mit]: https://github.com/miguelmota/is-valid-domain/blob/e48e90f3ecd55431bbdba950eea013c2072d2fac/LICENSE

## Keywords

Pupil-detection, face-detection, eye-detection, opencv-image-processing, dlib, HoughCircles, artificial-intelligence, machine-learning, ai-ml
