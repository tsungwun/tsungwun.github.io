---
layout: archive
title: "Control Projects"
permalink: /controls/
collection: controls
---


======

| Semester  | Project  | Keywords | Attachment |
|:----:|:--------:|:----:|:----:|
| Spring 2022 | Vibration Suppression of An Optical Table | Input-Output Disturbance Response Decoupling (IODRD) | [report](http://tsungwun.github.io/files/report_optical.pdf) |
| Spring 2022 | MIMO System Identification of A Quadcopter | ARX Model, H $\infty$ Synthesis | [slide](http://tsungwun.github.io/files/report_sysID_David.pdf), [video](https://youtube.com/shorts/HsXJFUH4R2Q) |
| Spring 2021 | $\mu$-Synthesis Design of A Half-Car Active Suspension System | $\mu$-Synthesis, Robust Performance | [slide](http://tsungwun.github.io/files/presentation_synthesize_half_car.pdf), [report](http://tsungwun.github.io/files/report_synthesize_half_car.pdf) |
| Spring 2020 | Adaptive Control Design and Stability Analysis of RR Robotic Manipulators | Lyapunov Stability, Model Reference Adaptive Control (MRAC) | [report](http://tsungwun.github.io/files/report_adaptive_rr_arm.pdf) |
| Fall 2018 | Wheeled Inverted Pendulum  | System Identification, PID Control | [slide](http://tsungwun.github.io/files/presentation_inverted.pdf), [video](https://youtu.be/Kn8Ok2zyNI4) |

{% for post in site.controls %}
    {% include archive-single.html %}
{% endfor %}