# j-photos

Cloud storage to store photos and videos. <a href="https://photos.jmuszka.com">photos.jmuszka.com</a>

<b>View the repository for the web client and backend code <a href="https://github.com/jmuszka-cloud/j-photos-web">here</a>.</b>


### Overview

A multi-user cloud-based solution, j-photos allows for seamless storage of photos and videos. As a free and self-hosted application, users can upload, view, and delete photos and videos from mutliple devices, both from a web browser and from their smartphone. Admin dashboard allows for the creation of new user accounts, modification of account data, such as name and maximum storage capacity, and changing of various application defaults and preferences. User-interface features such as background, font size, and accent color can be adjusted at the discretion of each user.


### Mission

j-photos is the first installment of a wider set of projects called <a href="https://github.com/jmuszka-cloud">j-cloud</a>. The goal of j-cloud is for me to create a suite of free and open source, self-hosted apps for me (and others) to use, that will also serve as a learning opportunity to expand my skills as a developer. With j-photos complete, I no longer need to rely on Google Photos for my centralized photo-storage needs. This project is my first forray into fullstack development, and I will continue exploring other technologies as I develop each subsequent app.


### How it was made

This app has both a web client and an Android app client, with the backend intended to run on an Apache Linux server. Click <a href="https://github.com/jmuszka-cloud/j-photos-web">here</a> to view the repository and installation for the backend and web client, as well as an installation guide for those interested in hosting it themselves. When I begin developing the Android app, I will update this page with a link to that repository as well.


### Roadmap

All the essential functionality is complete: users can log in, upload, delete, and view their photos. The web client has a complete user-interface, and keeps track of how much storage each user has consumed. There are some other features that need to be added, namely file upload security, a working admin dashboard, and some minor GUI tweaks. But once that is finished, the server backend and web client will be ready for use, and I will begin developing the Android app. As of now, only photos are supported, but I intend to add support for video files as soon as possible after release. There are some minor features that I will likely add later, such as categorizing photos/videos by month (ie. December 2023, January 2024, etc.), and GUI animations. I will also continuously patch any bugs that arise.
