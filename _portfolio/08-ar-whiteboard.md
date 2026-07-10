---
title: "Collaborative AR Whiteboarding System"
excerpt: "A collaborative AR system exploring how varying levels of user control during session initialization affect remote collaboration experience.<br/><img src='/images/whiteboard.png'>"
collection: portfolio
---

![Manual](/images/manual.gif)

This project investigated how the level of user control during the initialization of a shared AR whiteboarding session affects the overall collaboration experience. We designed and evaluated three initialization techniques (MANUAL, DISCRETE CHOICE, and AUTOMATIC) using a simulated AR environment built in VR for the Meta Quest 2.

Using Photon PUN 2, the system allowed two remote collaborators to establish a shared virtual whiteboard within their individual,  respective physical environments, synchronizing avatar positions, gaze direction, and pointer interactions across both spaces. We developed C-SAW (Collaborative Surface Algorithm for Whiteboarding), a set of heuristics for intelligently suggesting whiteboard placements that respect the constraints of each collaborator’s environment.

A user study with 36 participants found that collaborators preferred having direct control over whiteboard placement, size, and shape, even when automated suggestions were available.

**Stack:** Unity, C#, Photon PUN 2, Meta Quest 2

**Publication:** [Exploring the Effects of Level of Control in the Initialization of Shared Whiteboarding Sessions in Collaborative Augmented Reality](https://arxiv.org/abs/2502.00908) — IEEE VR 2025
