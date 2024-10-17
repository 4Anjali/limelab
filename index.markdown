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
    <div class="timeline-event">
        <div class="textbox">Lorem ipsum</div>
        <div class="circle">
            <a href="https://youtu.be/nLxlBb88Mvs?feature=shared" target="_blank" class="tooltip">
                YouTube Video
                <div class="tooltip-box">
                    <iframe src="https://www.youtube.com/embed/nLxlBb88Mvs" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                </div>
            </a>
            <div class="horizontal-line"></div>
        </div>
    </div>
    <!-- Event 2 -->
    <div class="timeline-event">
        <div class="textbox">Lorem ipsum</div>
        <div class="circle">
            <a href="https://youtu.be/nLxlBb88Mvs?feature=shared" target="_blank" class="tooltip">
                Vid2
                <div class="tooltip-box">
                    <iframe src="https://www.youtube.com/embed/nLxlBb88Mvs" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                </div>
            </a>
            <div class="horizontal-line"></div>
        </div>
    </div>
    <!-- Event 3 -->
    <div class="timeline-event">
        <div class="textbox">Lorem ipsum</div>
        <div class="circle">
            <a href="https://youtu.be/nLxlBb88Mvs?feature=shared" target="_blank" class="tooltip">
                Vid3
                <div class="tooltip-box">
                    <iframe src="https://www.youtube.com/embed/nLxlBb88Mvs" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                </div>
            </a>
            <div class="horizontal-line"></div>
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

    .timeline-event {
        display: flex;
        align-items: center;
        margin: 60px 0;
        position: relative;
    }

    .textbox {
        width: 100px;
        height: 50px; /* Update height to 50px */
        background-color: #f0f0f0;
        border: 1px solid #ccc;
        font-size: 11px;
        display: flex;
        align-items: center;
        justify-content: center;
        position: absolute;
        right: calc(50% + 20px); /* Position to the left of the circle with a 20px gap */
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
        left: 100%;
        transform: translate(3px, -50%);
        width: 300px;
        height: 200px;
        background-color: #007bff;
        color: white;
        border-radius: 3px;
        display: none;
        z-index: 2;
    }

    .tooltip-box iframe {
        width: 100%;
        height: 100%;
        border: none;
    }

    .circle:hover .tooltip-box {
        display: block;
    }

    /* Horizontal line connecting the bubble to the tooltip */
    .horizontal-line {
        position: absolute;
        top: 50%;
        left: 100%;
        width: 100px;
        height: 2px;
        background-color: #007bff;
        transform: translateY(-50%);
    }
</style>
