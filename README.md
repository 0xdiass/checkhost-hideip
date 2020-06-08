# Hide your IP - check-host.net


## Intro
This is a simple script in js to hide your ip in check host.

## Requirements
Tampermonkey --> https://www.tampermonkey.net/

Browser --> Chrome, Firefox, Safari, Opera, or Microsoft Edge.

## Script
###### Hide IP by DiasS.js                         

    // ==UserScript==
    // @name         Hide IP by DiasS
    // @namespace    http://tampermonkey.net/
    // @version      1.0
    // @description  Script hide your ip in check-host!
    // @author       DiasS
    // @match        https://check-host.net/*
    // @grant        none
    // ==/UserScript==

    (function() {
        'use strict';
        
    document.getElementById("yourip").innerHTML = "<div id=\"yourip\">\r\n<div style=\"padding-top: 5px; padding-left: 5px\"><strong>IP<\/strong>: <a title=\"your ip address info\" href=\"\/ip-info?host=DiasS\">DiasS<\/a>\r\n<strong>Country<\/strong>:\r\n<img class=\"flag\" src=\"\/images\/flags\/pt.png\" alt=\"PT\">\r\nPortugal\r\n(Alto, Mar)\r\n<\/div>\r\n<\/div>"
    })();


# How to Use
1. You will need **Tampermonkey** installed on your browser.

2. Open your **Tampermonkey** and "create a new script".

3. Put the code in new script.

4. Enjoy

## Proof

### Before:
![download](https://user-images.githubusercontent.com/36014967/84076706-28bc2f00-a9ce-11ea-9fe0-50c0e662c436.png)

### After: 
![Screenshot_1](https://user-images.githubusercontent.com/36014967/84076945-8badc600-a9ce-11ea-8271-fb57fc17dd1b.png)
