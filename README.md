# Supermarket Stock Bot System

## Project Overview
The Supermarket Stock Bot System is designed to streamline inventory management in supermarkets. This system uses computer vision, robotics, and automation to monitor and manage stock levels, ensuring efficient and accurate inventory control.

---

## Key Features
- **Stock Monitoring**: Real-time tracking of stock levels on shelves.
- **Automation**: Integration with robotic systems for physical inventory checks.
- **User Interface**: Web-based GUI for monitoring and controlling operations.
- **Machine Learning**: Object detection and recognition for inventory classification.

---

## Data
The project relies on:
- **Camera Feeds**: For real-time image capturing.
- **Predefined Inventory Models**: For object detection and classification.
- **Simulation Environments**: For testing robot movements and actions.

---

## Methodology
1. **Data Acquisition**: Images captured via mounted cameras.
2. **Object Detection**: Using machine learning algorithms to identify items.
3. **Inventory Analysis**: Real-time computation of stock levels.
4. **Automation**: Robotic movement for scanning and verification.

---

## Key Findings
- Improved inventory management accuracy.
- Reduced time spent on manual stock checks.
- Enhanced efficiency in detecting low-stock or misplaced items.

---

## Technologies Used
- **Languages**: Python, C++
- **Libraries**: OpenCV, ROS (Robot Operating System)
- **Simulation Tools**: Gazebo
- **Frameworks**: TensorFlow/PyTorch (for machine learning)

---

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/supermarket-stock-bot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd supermarket-stock-bot
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch the simulation:
   ```bash
   roslaunch opencv_web websocket.launch
   ```

---

## Usage
1. Open the GUI:
   - Navigate to the web interface via `gui.html`.
2. Start the robot and camera systems:
   ```bash
   rosrun orbotox drive4.py
   ```
3. Monitor real-time stock updates and robot actions.

---

## License
This project is licensed under the [MIT License](LICENSE).
