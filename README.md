# Guruguru Map
This is the project built for ECE297: Software Design and Communication at the University of Toronto. 

Note: Due to copyright restrictions at the University of Toronto for this project, we are unable to share the source code. This repository serves as a showcase of our work.
   <p align="center">
     <img src="https://github.com/user-attachments/assets/8dfcaa54-556e-4401-8669-38ff5d9d038e" alt="image", width=600/>
   </p>
   
## Discover the City with Ease and Precision

Welcome to the **Guruguru Map** project, a feature-rich geographic information system (GIS) application designed to make urban exploration seamless and intuitive. Developed in C++ with the OpenStreetMap (OSM) library, Guruguru Map offers a user-friendly and adaptive experience, allowing you to navigate and explore cities with ease.

## Table of Contents

- [Features](#features)
  - [Intuitive Interface](#1-intuitive-interface)
  - [Adaptive Display](#2-adaptive-display)
  - [Enhanced Exploration Features](#3-enhanced-exploration-features)
  - [Performance and Responsiveness](#4-performance-and-responsiveness)
  - [Advanced Algorithms](#5-advanced-algorithms)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributors](#contributors)

## Features

### 1. Intuitive Interface

The Guruguru Map interface is designed to provide users with a straightforward and enjoyable navigation experience. Here are some key aspects of our intuitive interface:

- **Minimal and Clean Design**: The interface is clutter-free and user-friendly, making it accessible for all users.

- **Dark Mode**: Offers a comfortable viewing experience, especially in low-light conditions, by reducing glare and eye strain.

- **Search Engine**: The search bar includes a smart autocomplete feature that makes it easy to find places, intersections, or points of interest.

- **Customizable Layout**: Users can personalize the interface by toggling visibility for various features, focusing on what's important to them.

- **Help Page** A detailed help page guides the functionality of the map. <br>

   <p align="center">
     <img src="https://github.com/user-attachments/assets/f2eb06bd-0fd0-4937-bbf3-d2dbca1b9266" alt="image"/>
   </p>



### 2. Adaptive Display

Guruguru Map dynamically adapts to your needs, showing the most relevant information as you explore:

- **Dynamic Zooming**: The map adjusts to display relevant information, from broad city layouts to detailed street views and points of interest, as you zoom in and out.

- **Layered Information**: Access various map layers, such as metro lines, traffic conditions, and water bodies, to get a comprehensive understanding of your surroundings.

- **Real-Time Updates**: Stay informed with live traffic updates and changes in traffic conditions.<br><br>

   <p align="center">
     <img src="https://github.com/user-attachments/assets/2a130064-0227-4e8e-b029-6406d41023c6" alt="image"/>
   </p>


### 3. Enhanced Exploration Features

Our map provides several features that make city exploration more engaging and informative:

- **Intuitive Search Functionality**: Find exactly what you need with our precise search engine and autocomplete feature.

- **Proximity Alerts**: Quickly locate nearby amenities like cafes, restaurants, and bars for convenience.

- **Distance Measurement**: Calculate distances between multiple locations easily, helping users plan their journeys effectively.

- **Ratings and Reviews**: Fetch user-generated reviews from the internet to help you make informed decisions about points of interest.<br><br>

 
### 4. Performance and Responsiveness

Our application is engineered for optimal performance, ensuring a smooth and responsive user experience:

- **Fast Rendering**: The map loads and responds to user interactions almost instantly, delivering a smooth experience without delays.

- **Adaptive Feedback**: Visual and textual feedback confirms user actions, keeping users informed and engaged with every interaction.

- **Multithreading**: Leveraging multithreading capabilities to enhance performance and reduce loading times.<br><br>


### 5. Advanced Algorithms

Guruguru Map uses cutting-edge algorithms to enhance navigation and routing:

- **Pathfinding**: Implements Dijkstra's and A* search algorithms to find optimal routes quickly and accurately. <br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/86f67747-2808-4426-ba3c-98d49a875e5d" alt="image"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/21a8ac35-cc3c-4eff-9391-d71dfb757211" alt="image"/>
</p>
<br>

- **Traveling Salesman Problem (TSP) Solution**:
    - The Traveling Salesman Problem (TSP) involves finding the shortest possible route that visits a set of locations once and returns to the starting point, optimizing for minimal travel time or distance. To solve this problem, we implemented a genetic algorithm that optimizes delivery routes.
    - The algorithm initializes a population of potential solutions using greedy heuristics, and then iteratively improves them through selection, crossover, and mutation processes. This approach effectively handles multiple deliveries and minimizes travel time, providing efficient and near-optimal routes within the given constraints.
    - Our approach consistently ranks among the top solutions in benchmark tests, showcasing the effectiveness and superiority of genetic algorithms in complex routing challenges.<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0fdd1298-141a-497d-82fe-75e134a313ec" alt="image"/>
</p>


## Usage

- **Navigation**: Use the search bar to locate places or points of interest.
- **Zooming**: Adjust zoom levels to explore different layers of information.
- **Features**: Explore nearby amenities, calculate distances, view real-time traffic data, and access reviews.

## Technologies

- **C++**: The core programming language for the application.
- **OpenStreetMap (OSM) Library**: Provides map data and functionalities.
- **Algorithms**: Includes pathfinding and genetic algorithms for optimized routing and exploration.

## Contributors

- **George Li**
- **Yucheng Tu**
- **Jinghao Zou**
