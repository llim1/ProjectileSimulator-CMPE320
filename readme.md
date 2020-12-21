# About this Repository
This is the codebase for a group project in my software development course to learn about C++ development and working in an Agile environment. During development, the repository was hosted on an internal BitBucket server, so some things may not have transferred over so well.

# Projectile Simulator 
The proposed application is a physics simulation that models the behaviour of non-Newtonian projectiles in a range of different environments (planets). The project will focus both on the algorithms/physics behind non-Newtonian motion, in addition to demonstrating the concepts through a user-friendly interface. Users can select the activity and environment, and travel through “space” on their rocket, exploring the various activities as a cartoon astronaut.

## How it works
The project was developed using standard C++14 in Visual Studio 2019.

The program is split into a frontend and backend. The backend contains all the required data structures, and manages all projectiles and their associated data. A manager class provides a single interface which the frontend can interact with. The backend is compiled to a DLL.

The frontend is a GUI that makes use of the [dear ImGui](https://github.com/ocornut/imgui) library and DirectX 11. 

## Tools Used
* Visual Studio 2019 for development 
* Confluence for design and documentation
* Jira for issue and progress tracking, sprints, and other analytics
* BitBucket for Git version control 
* Microsoft Teams for communication 

## Screenshots 
<img alt="home screen" src="https://i.imgur.com/8Y90zVj.png" width="50%" />
<img alt="select screen" src="https://imgur.com/uGJRMg8.png" width="50%" />
<img alt="launch screen" src="https://imgur.com/1p6KE77.png" width="50%" />
