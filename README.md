# Inter-Window Communication Experiment with Interconnected Balls

## Introduction
Inspired by a fascinating experiment in inter-window communication ([source](https://twitter.com/_nonfigurativ_/status/1727322594570027343)), this project is a foray into the realm of browser-based communication technologies. While acknowledging the simplicity of our approach compared to the original, this project aims to provide an easy-to-understand demonstration of inter-window communication through the use of interconnected balls.

## Project Concept
The core idea of this experiment is to utilize a straightforward and visually engaging method to demonstrate inter-window communication. By creating a dynamic and interactive system of balls moving across multiple browser windows, we can observe how data can be shared and synchronized in real-time between different instances of a web application.

### Experiment Features
- **Dynamic Ball Movement:** Balls move autonomously within each browser window, showcasing individual behavior.
- **Interconnection Across Windows:** Utilizing Local Storage, the position and movement of each ball are synchronized across all open windows, demonstrating a fundamental aspect of inter-window communication.
- **Visual Interaction:** The HTML5 Canvas API is used to draw lines between balls, visually representing the interconnectedness and real-time communication between different windows.

## Technology Stack
- **HTML/CSS:** Provides the structure and style for the canvas and ball elements.
- **JavaScript:** Manages the dynamic behavior of the balls and handles the synchronization of their states across multiple windows.
- **HTML5 Canvas API:** Used for drawing the lines between balls, offering a visual representation of their interconnected paths.
- **Local Storage:** Employs browser Local Storage for tracking and sharing the positions of the balls across different windows.

## Implementation Details
The code creates an interactive environment where each ball, represented as a colored circle, moves within the browser window. Their positions are stored in Local Storage, allowing for real-time synchronization across multiple browser instances. The Canvas API is used to draw lines between the balls, visually depicting the connection between them as they move.

## Getting Started
1. **Clone the Repository:** https://github.com/vladimirkhoetsyan/cross-wndow-data-sync
2. **Open in Multiple Windows:** To fully experience the inter-window communication, open the project in multiple browser windows.
3. **Interact and Observe:** Watch how the movement of balls is synchronized across windows and how they interact with each other.

## Conclusion and Acknowledgements
While this experiment is a simplification of the advanced concepts presented in the referenced experiment, it serves as an accessible introduction to the principles of inter-window communication. Special thanks to the original experiment shared by [@_nonfigurativ_](https://twitter.com/_nonfigurativ_/status/1727322594570027343) for inspiring this project.
