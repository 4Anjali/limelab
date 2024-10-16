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
    <div class="container left">
        <div class="circle"></div>
        <div class="tooltip">YouTube Video</div>
        <div class="content">
            <a href="https://youtu.be/nLxlBb88Mvs?feature=shared" target="_blank">YouTube Video</a>
        </div>
    </div>
    <!-- Event 2 -->
    <div class="container right">
        <div class="circle"></div>
        <div class="tooltip">PDF Document</div>
        <div class="content">
            <a href="https://youtu.be/nLxlBb88Mvs?feature=shared" target="_blank">Vid2</a>
        </div>
    </div>
    <!-- Event 3 -->
    <div class="container left">
        <div class="circle"></div>
        <div class="tooltip">External Website</div>
        <div class="content">
            <a href="https://youtu.be/nLxlBb88Mvs?feature=shared" target="_blank">Vid3</a>
        </div>
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

    /* Timeline event container */
    .container {
        padding: 10px 40px;
        position: relative;
        background-color: inherit;
        width: 50%;
    }

    /* Place the containers to the left and right */
    .left {
        left: 0;
    }

    .right {
        left: 50%;
    }

    /* Add circles for the timeline events */
    .circle {
        position: absolute;
        top: 15px;
        left: 50%;
        transform: translateX(-50%);
        width: 20px;
        height: 20px;
        background-color: white;
        border: 3px solid #007bff;
        border-radius: 50%;
        z-index: 1;
    }

    /* Timeline event content */
    .content {
        padding: 20px;
        background-color: white;
        position: relative;
        border-radius: 6px;
        border: 1px solid #007bff;
    }

    .left .content {
        left: calc(-100% - 40px);
    }

    .right .content {
        left: calc(50% + 20px);
    }

    /* Hover effect */
    .tooltip {
        position: absolute;
        display: none;
        top: -50px;
        left: 50%;
        transform: translateX(-50%);
        padding: 10px;
        background-color: #333;
        color: #fff;
        font-size: 12px;
        border-radius: 5px;
    }

    .circle:hover + .tooltip {
        display: block;
    }

    /* Hyperlink style */
    .circle:hover {
        background-color: #007bff;
    }

    .content a {
        text-decoration: none;
        color: #007bff;
    }
</style>
