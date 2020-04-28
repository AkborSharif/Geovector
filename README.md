# Geovector

Geovector allows a user to find the location of an object, or point of interest after taking two or more images. 
The company Topcon sponsored the app (Geovector) and we are in an agreement not to publish it in public. 



## Motivation
This is my Capstone project for software engineering course where I with 3 other peers implementing a system that detects the geolocation of a point of interest. Out of all the project sponsonred by many companies, I decided to implement this application because it made me interested to learn more about the geography and mapping. Using our app, people can immidietly detect any locations of an onject within few second. I loved the idea that it will be useful for the company (Topcon) we are building it for without any cost or hard work.

## Description

Develop a Capture to Measure system for difficult-to-reach targets on or above ground based on 2 or more images captured from a known position. All the points of interest for GIS or surveying applications are not always safely reachable, and we will need some kind of offset measurement devices to locate those objects, with the advancement in imaging technology and photogrammetric techniques, we believe that commercially available camera (inside our smartphones, tablets) can be used to precise position targets without expensive EDM or camera system.



## Objectives
End-user starts with a known precise position of the camera with IMU -Aim the point of interest (POI), and capture image covering that POI -The user selects POI on 1st image -The user moved to another location with a known precise position of the camera -Aim the same point of interest (POI) -The software should guide the user with confidence-level if 2nd image can be used to derive positioning. Or ask to re-aim the camera. Ideally, after taking the 1st image, software should guide user the best 2nd camera position -Capture 2nd image covering POI. -If two images are not enough to derive the position of POI, software should ask a user to take other images containing POI for the best results. -Compute position of the POI based on images and compare it with the known precise position of POI obtained from an independent system (Total Station, GNSS) to show the accuracy of the “Captureto Measure” system. Notes –-The idea emphasizes to use smartphones/tablet available in the market to build a non-bulky, inexpensive image-based location system. -The software could run on iOS/Android or Windows Mobile operating systems. -The system should clearly outline factors contributing to meet/or improve desired accuracy requirements (hints -IMU specifications, camera resolution, the accuracy of camera positions, etc.) -Key points in this implementation are the final accuracy of the solution, Insanely great User experience, and easy user interface. Create an app that solves a real-world challenge with a simple yet smart work

## Tech/framework used

Android Studio plateform with Java 

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/3/34/Android_Studio_icon.svg)
<a href="https://www.clipart.email/download/11386057.html" title="Image from clipart.email"><img src="https://cdn.clipart.email/80b77b23b7b5532d36d68266016a7fd5_the-java-feature-you-never-knew-about-the-java-report-medium_500-334.png" width="180" height = "120" alt="Java 8 Logo Png" /></a>



## License
