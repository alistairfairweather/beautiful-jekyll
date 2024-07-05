---
layout: post
title: CSS Selector test
subtitle: Testing page
---

    <style>
        .menu-button {
            display: block;
            margin: 10px;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            text-align: center;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>

    <div>
        <a id="button1" href="https://example.com" class="menu-button">Click Me</a>
    </div>
    <div>
        <a class="button2" href="https://example.com" class="menu-button">Click Me</a>
    </div>
    <div>
        <a href="https://example.com" class="menu-button" data-button="3">Click Me</a>
    </div>
    <div>
        <div class="parent">
            <a href="https://example.com" class="menu-button">Click Me</a>
        </div>
    </div> 
 
 