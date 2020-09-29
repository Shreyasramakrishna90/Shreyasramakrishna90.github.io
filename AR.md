---
layout: page
title: Assured Autonomy
#cover-img: "/assets/img/new-car.png"
full-width: true
---

[DARPA Assured Autonomy Project](https://www.darpa.mil/program/assured-autonomy) -- Tremendous advances have been made in the area of autonomous robots/vehicles in the last decades, through self driving cars, unmanned robots, unmanned aerial vehicles, etc. There has been a significant improvement in the areas of sensor technology, computing devices, baseline controllers, design methodology and simulation tools. In spite of these significant advances, there are still challenges in designing fully autonomous systems, as guaranteeing the safety of such systems is challenging. My research work is mainly focused on (1) designing Learning Enabled Components (LECs) for autonomous driving, (2) designing assurance monitors to detect out-of-distribution data, (3) design mitigation strategies like Simplex Architecture to augment safety into LEC driven systems, (4) designing safety assurance cases to the CPS with LEC.

## Research Focus

## 1. Designing Autonomous Robots
Learning enabled components (LECs) trained using data-driven algorithms are increasingly being used to achieve autonomy related perception and control tasks like end-to-end driving, object detection and tracking, and image segmentation. In this area, we have designed small scale remote controlled car called DeepNNCAR to autonomously drive around a track in our lab using the popular NVIDIA's DAVE-II neural network model.


## 2. Assurance monitors for perception based Cyber-physical systems
LECs have shown remarkable performance in several perception and control tasks like NVIDIA’s DAVE-II self driving car. However, incidents like TESLA’s self-driving accident and UBER’s autonomous car crash have shown the susceptibility of LECs to Out-of-distribution data. Besides the black box nature of the LECs makes it difficult to test and verify them. In this area, we have been designing assurance monitors that are capable of detecting if an operational test image is out-of-distribution.

## 3. Safety mitigation strategy for lec based cyber-physical systems
Cyber Physical Systems (CPS) have increasingly started using Learning Enabled Components (LECs) for performing perception-based control tasks. The simple design approach, and their capability to continuously learn has led to their widespread use in different autonomous applications. Despite their simplicity and impressive capabilities, these models are difficult to assure, which makes their use challenging. The problem of assuring CPS with untrusted controllers has been achieved using the Simplex Architecture. This architecture integrates the system to be assured with a safe controller and provides a decision logic to switch between the decisions of these controllers. However, designing Simplex Architectures for CPS with LECs is complex, because of the LECs black-box nature. In this area, we design an Simplex Architecture for LEC based CPS.

## 4. Automating Safety Assurance Cases
Assurance Cases have become an integral component for safety-certification in various Cyber Physical System domains, including automotive, aviation, military, and medical devices. Despite the strict requirements, current practices still rely on manual methods that are brittle, do not have a systematic approach or thorough consideration of sound arguments. In addition, stringent certification requirements and ever-increasing system complexity make ad-hoc, manual assurance case generation inefficient, time consuming, and expensive. In this area, we improve the current state of practice by introducing a structured Assurance Case Generation (ACG) method which uses system design artifacts, accumulated evidence, and developer expertise to construct an assurance case and evaluate it in an automated manner. Besides, we also focus on designing a tool called ALC to automate the entire design and testing of LEC based CPS.

