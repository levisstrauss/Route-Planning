# Route Planner Project

This project is a route planner that plots a path between two points on a map using real map data from the OpenStreetMap project. The project uses the A* search algorithm to find the optimal path and renders the path on a map using the IO2D graphics library.

## Repository Structure
```bash

Route-Planner-OpenStreetMap/
├── cmake/
│   ├── FindIO2D.cmake
│   └── Findcairo.cmake
├── src/
│   ├── main.cpp
│   ├── model.cpp
│   ├── model.h
│   ├── render.cpp
│   ├── render.h
│   ├── route_model.cpp
│   ├── route_model.h
│   ├── route_planner.cpp
│   └── route_planner.h
├── test/
│   ├── test.cpp
│   └── ...
├── thirdparty/
│   ├── io2d/
│   └── ...
├── CMakeLists.txt
├── README.md
└── LICENSE
```
## Table of Contents

- [Introduction](#introduction)
- [Features](#features)

## Introduction

This Route Planner project is part of the Udacity C++ Nanodegree Program. It implements a simple route planning application using the A* search algorithm, a popular pathfinding and graph traversal algorithm. The application reads OpenStreetMap data and visualizes the shortest path between two points on the map.

## Features

- Reads and processes map data from OpenStreetMap.
- Implements the A* search algorithm to find the shortest path.
- Visualizes the map and the route using the IO2D graphics library.

This repo contains the final code for the Route Planning project.

<img src="map.png" width="600" height="450" />


