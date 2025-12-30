# Pupil Detection using Dlib face landmark detector

The code is used to get the co-ordinates of eyes and detect the pupil region accurately.

It works with human face images. Dlib's facial landmark detector is used for extracting the coordinates from the eye region.
The eye corner points are collected and it check for dark colored region between the detected eye corner points of each eye.
It uses OpenCV's houghcircles for detecting circle in a gray scaled image. Thus the pupil is calculated as the midpoint of the circle.


## Table of contents

- [Getting started](#getting-started)
- [Installation](#installation)
- [Features](#features)
- [Usage](#usage)
- [Results](#results)
- [Want to Contribute?](#want-to-contribute)
- [Need Help / Support?](#need-help)
- [Collection of Other Components](#collection-of-components)
- [Changelog](#changelog)
- [Credits](#credits)
- [License](#license)
- [Keywords](#Keywords)


## Features

- Accurately detects the eye pupil on human face.
- HoughCircles is used to detect circles.

## Usage

Inside the project directory run:

```
python pupil_detection.py -i path-to-directory-of-input-images -o path-to-output-directory
```
You can find sample images in image folder and result images in output folder.

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
