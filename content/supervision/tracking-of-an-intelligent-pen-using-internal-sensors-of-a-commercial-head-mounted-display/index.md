---
title: Tracking of an Intelligent Pen Using Internal Sensors of a Commercial Head
  Mounted Display
# event: B.Sc. Thesis Supervision
event_url: ''
location: Karlsruhe Institute of Technology
# address:
#   street: ''
#   city: Karlsruhe
#   region: ''
#   postcode: ''
#   country: Germany
# summary: Utilized internal sensors of head-mounted displays for intelligent pen tracking
abstract: Although optical tracking systems are improving more and more each year, the most advanced solutions still rely on clunky, fixed cameras that are difficult to set up. In large spaces, where numerous objects are present, such as factories, these systems either do not perform well, or become really expensive. For this reason, a shift towards more mobile optical tracking methods is needed. Such systems could be implemented on head mounted displays and would therefore perform well even in cluttered environments, as they would be able to see everything from the point of view of the user. More mobile systems could also encourage the development of more intuitive robot programming methods, that use head mounted displays with augmented reality and optical tracking abilities. For this reason, we developed a method that uses a commercial head mounted display (Microsoft Hololens) to track passive reflective infrared markers attached to a smart pen, although any marker configuration can be used. Our algorithm uses the depth sensor of the Hololens to determine the 3D position of the markers. Model fitting and a least-squares pose estimation method are then used to reconstruct the position and orientation of the entire marker configuration. Since mobility is one of our key goals, all computations are performed on the device, and we only rely on an external workstation for visualizing the calculated pose of the pen. We then designed experiments to asses the performance of our system in the following areas- latency, frame rate, angular and positional precision. Our findings have concluded that in static conditions, the method performs with a precision of 1.9 millimeters and 0.37 degrees, at a framerate of 46 Hz. In more dynamic situations, the precision values reach 2.2 centimeters and 3.87 degrees, while the framerates drop to 40 Hz. The latency of the system was found to be 90 milliseconds, regardless of the amount of movement present. Compared with the state of the art, the performance of our system definitely leaves room for improvement, as it still has a long way to go until it reaches sub-millimeter accuracies, latencies lower than 5 milliseconds and frame rates of 2000 Hz. However, we believe that our method illustrates a valuable proof of concept for head mounted displays as mobile optical tracking systems. Furthermore, there are still numerous optical tracking applications that do not require a high degree of accuracy and where higher latencies do not pose a big problem, that could make use of our mobile optical tracking system even with its current performance.
date: '2020-11-01T00:00:00Z'
date_end: ''
all_day: true
publishDate: '2020-11-01T00:00:00Z'
authors:
- admin
- Alexandru-George Vasilache
tags:
tags:
- Augmented Reality
- Robot Programming
- Computer Vision
- Object Recognition
- Tracking
- Marker Tracking
- HoloLens 1
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
- tracking
---

