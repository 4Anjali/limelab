---
layout: page
title: Status
permalink: /
---

### Completed:
- Camera integrated with robotic arm
- Machine Vision model correctly detecting good, bad, imperfect carrots
- Robotic arm moving to correct bins based on classification

### Work In Process Tasks:
- Make end of gripper work for carrots
- Figure out way for 360 degree view of carrots (use multiple cameras?)

### Future Work:
- Make end of gripper work for carrots
- Figure out way for 360 degree view of carrots (use multiple cameras?)

If you are interested in contributing to this initiative, please write to anjali.sharma@limelab.org with your vita and a less than 500 word statement describing why you are interested and how you wish to contribute.

<!-- Timeline section starts here -->
<div class="timeline">
    <!-- Event 1 -->
    <div class="circle">
        <a href="https://youtu.be/nLxlBb88Mvs?feature=shared" target="_blank" class="tooltip">YouTube Video</a>
        <div class="horizontal-line"></div>
        <div class="tooltip-box">YouTube Video</div>
    </div>
    <!-- Event 2 -->
    <div class="circle">
        <a href="https://youtu.be/nLxlBb88Mvs?feature=shared" target="_blank" class="tooltip">Vid2</a>
        <div class="horizontal-line"></div>
        <div class="tooltip-box">Vid2</div>
    </div>
    <!-- Event 3 -->
    <div class="circle">
        <a href="https://youtu.be/nLxlBb88Mvs?feature=shared" target="_blank" class="tooltip">Vid3</a>
        <div class="horizontal-line"></div>
        <div class="tooltip-box">Vid3</div>
    </div>
</div>

<!-- CSS styles for the timeline -->
<style>
    * {
        box-sizing: border-box;
    }

    body {
        font-family: Arial, sans-serif;
    }

    .timeline {
        position: relative;
        max-width: 800px;
        margin: 0 auto;
        padding-top: 40px;
    }

    /* Create the vertical line */
    .timeline::after {
        content: '';
        position: absolute;
        width: 6px;
        background-color: #007bff;
        top: 0;
        bottom: 0;
        left: 50%;
        margin-left: -3px;
    }

    /* Add circles for the timeline events */
    .circle {
        position: relative;
        top: 15px;
        left: 50%;
        transform: translateX(-50%);
        width: 20px;
        height: 20px;
        background-color: white;
        border: 3px solid #007bff;
        border-radius: 50%;
        z-index: 1;
        margin: 60px 0; /* Increased margin to separate the bubbles vertically */
    }

    .circle a {
        display: block;
        width: 100%;
        height: 100%;
        text-decoration: none;
        color: transparent; /* Hide the link text */
    }

    .circle a:hover {
        background-color: #007bff;
    }

    /* Tooltip box for the circle links */
    .tooltip-box {
        position: absolute;
        top: 50%;
        left: 150%; /* Shift to the right by another inch */
        transform: translateY(-50%);
        padding: 20px 40px; /* Increase size */
        background-color: #007bff;
        color: white;
        border-radius: 3px;
        text-align: center;
        font-size: 16px; /* Increase font size */
        display: none;
        z-index: 2;
    }

    .circle:hover .tooltip-box {
        display: block;
    }

    /* Horizontal line connecting the bubble to the tooltip */
    .horizontal-line {
        position: absolute;
        top: 50%;
        left: 100%;
        width: 100px; /* Adjust the width as needed */
        height: 2px;
        background-color: #007bff;
        transform: translateY(-50%);
    }
</style>
