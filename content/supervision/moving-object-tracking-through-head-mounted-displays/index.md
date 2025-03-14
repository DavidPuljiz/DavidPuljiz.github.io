---
title: Moving Object Tracking through Head-Mounted Displays
# event: M.Sc. Thesis Supervision
event_url: ''
location: Karlsruhe Institute of Technology
# address:
#   street: ''
#   city: Karlsruhe
#   region: ''
#   postcode: ''
#   country: Germany
# summary: Tracking and detection of moving objects using head-mounted AR displays
abstract: Head-mounted displays frequently feature a wide suite of sensors. For example, the HoloLens 2 has four environmental VLC cameras, an RGB camera, a depth sensor and an IMU. While these sensors are already used by the in-built self-localization algorithm which tracks the HoloLens 2's movement throughout its workspace, they could also be used to track other moving objects, such as humans and robots. There are already a lot of different algorithms for the task of tracking moving objects, however they often rely on LiDAR sensors, radar sensors and/or multiple cameras, which together provide a full 360° coverage of the environment. Due to the nature of wearable AR devices needing to be lightweight, compact and energy-efficient, they may come with other types of sensors, and the sensors may not cover the full 360° of the environment, meaning that there is a need of research towards finding moving object tracking approaches compatible with the sensors available on such devices. This thesis aims at finding different approaches for detecting and tracking moving objects in three dimensional space which work with the sensors embedded into a head-mounted AR device. Research on state of the art mobile object tracking methods was performed, with a focus on tracking accuracy, processing speed and sensors needed. The three most promising approaches, two depth sensor based approaches and one stereo vision based approach, were implemented and tested with the HoloLens 2 in order to find the approach achieving the best results when used with the sensors available on a head-mounted AR device. Evaluation results have shown that the stereo vision based approach had too many issues when trying to use it with the sensors available on the HoloLens 2. The two depth sensor based approaches perform similarly well with each one having its own benefits and drawbacks over the other. While the first of these two approaches performs better in cluttered spaces than the second approach and builds an additional map of the static environment, the second approach is able to also detect movable objects instead of only moving objects. Regarding their tracking accuracy, the two approaches achieve similar results when processing delays are being ignored. However, the first approach is between 2.57 and 2.67 times faster than the second approach, at least on the hardware used throughout this work, resulting in it processing more frames and therefore achieving a better tracking accuracy than the second approach when including all processing delays.

date: '2022-09-01T00:00:00Z'
date_end: ''
all_day: true
publishDate: '2022-09-01T00:00:00Z'
authors:
- admin
- Fabian Bösing
tags:
- Augmented Reality
- Computer Vision
- Object Recognition
- Tracking
- Machine Learning
- HoloLens 2
- Depth Sensor
featured: false
image:
  caption: ''
  focal_point: Center
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
slides: ''
projects:
- moving
---
