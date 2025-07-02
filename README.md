# Midlayer for separating application logic and user interface in web solutions

A repository containing code developed as part of the Bachelor thesis at the University of Ljubljana, Faculty of Computer and Information Science by Peter Šterman.

## Abstract
As part of this thesis, we developed a middleware layer that enables the connection of the RenderCore and VPT applications with a selected user interface library. Based on this solution, we redeveloped the user interfaces of both applications. The middleware allows for easy replacement of the user interface library without modifying the core application logic. During the development process, we evaluated the impact of the middleware on system performance by measuring responsiveness. We found that the introduction of the middleware had no significant impact on performance, while improving code clarity and simplifying the development of the user interface.

The thesis is accessible at:  
#TODO  
Bibtex:  
#TODO  

# Code files

This repository references two submodules, both being implementations of web applications using a midlayer to separate application logic from the user interface. This alleviates several issues that arise from tight coupling, 

# RenderCoreEditor
RenderCore is a versatile rendering framework. As part of the thesis, a simple scene editor was developed for it, using the midlayer approach.
# VPT-WebGPU
VPT is a volumetric path tracing framework targeted towards interactive real-time data exploration, intended for web use. An updated UI, using the Tweakpane library, was developed for it.
