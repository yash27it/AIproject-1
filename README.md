Project Overview
In modern cities, the bane of daily commute is often unpredictable traffic congestion. With the current infrastructure, traffic light timings are mostly static and don't adapt to real-time traffic conditions. This leads to unnecessary traffic congestion and wastage of time for the daily commuter. Our solution? An intelligent traffic light control system that alters its timings dynamically based on real-time traffic congestion.

Theme: AI Traffic Management
Problem Statement: Altering traffic light timings based on the congestion of traffic per lane using OpenCV and Neural Networks.
Features
Real-time Traffic Analysis: Using OpenCV, we analyze live camera feeds to assess the volume of traffic in each lane at an intersection.
Dynamic Traffic Light Timings: Neural network models predict the optimal traffic light durations to minimize congestion.
Adaptive Learning: Our model becomes more accurate over time as it learns from more data.
Scalable: Can be easily deployed across multiple intersections and traffic conditions.
Eco-Friendly: Reducing traffic congestion also means reducing the amount of time cars spend idling, leading to reduced carbon emissions.
Technical Stack
Computer Vision: OpenCV
Machine Learning: Custom Neural Network using Tensorflow
Backend: Python Flask
Frontend: React.js (For traffic data visualization)
Installation & Setup
Clone the Repository

git clone https://github.com/Tromso-AI-Traffic-Solution/repo.git
Set Up the Environment

pip install -r requirements.txt
Run the Application

python main.py
Access the frontend dashboard at http://localhost:3000 to visualize real-time data.

Future Enhancements
Integration with Smart Cities: Collaborate with municipalities to integrate our solution into existing smart city initiatives.
Prediction of Traffic Patterns: With enough data, predict future traffic patterns to better prepare for congestion.
Emergency Vehicle Priority: Detect emergency vehicles and alter traffic lights to give them a clear path.
