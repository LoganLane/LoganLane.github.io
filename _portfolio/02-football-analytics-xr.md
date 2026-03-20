---
title: "Football Technology Research"
excerpt: "A multi-year research journey exploring the intersection of augmented reality, computer vision, and analytics in American football.<br/><img src='/images/FootballAR.png'>"
collection: portfolio
---

My interest in applying emerging technology to football began with a simple question: what if you could watch a play unfold in augmented reality on a table in front of you? That question led to years of exploration across XR, computer vision, and machine learning.

## AR Tabletop Football Experience

The first iteration was an augmented reality application that allowed users to experience football plays on a physical tabletop surface. Plays were reconstructed from tracking data and rendered as 3D animations in AR, giving viewers a novel spatial perspective on the game that traditional broadcast angles can't provide. This project established the core idea that spatial computing could reveal hidden structure in football that is invisible from conventional viewing angles.

**Stack:** Unity, C#, AR Foundation

## Computer Vision and Player Tracking

In collaboration with a team of researchers, subsequent work explored the computer vision infrastructure needed to turn raw video footage into structured spatial data. This involved developing pipelines for player detection, pose estimation, and skeletal tracking — translating what the camera sees into field coordinates that could power analytics and XR visualizations. Work included player segmentation, pose estimation from monocular video, and mapping player movements to a standardized coordinate system.

**Stack:** Python, PyTorch, Grounded SAM 2, Unreal Engine, RealityKit, SwiftUI

## Natural Language Analytics

More recently, this interest in football data led to FootballLLM — a natural language interface over NFL Big Data Bowl tracking data that lets coaches and analysts ask questions in plain English and receive data-driven answers, without requiring knowledge of SQL or data science.

[See the FootballLLM project →](/portfolio/01-footballllm/)
