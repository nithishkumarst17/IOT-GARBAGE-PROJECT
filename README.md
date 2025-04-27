# Smart Trash Bin with Shortest Path Finder  
## **An IoT-enabled solution to revolutionize waste collection**

Imagine a bustling city where waste collection is always a challenge. Bins overflow, trucks waste fuel checking half-empty bins, and cities struggle to stay clean.  
Now imagine a smarter world — where garbage bins can *talk*, trucks know *exactly* where to go, and waste collection is *fast and efficient*.

That’s where our project comes in:  
**Smart Trash Bin with Shortest Path Finder** — an intelligent IoT solution that **monitors**, **updates**, and **optimizes** garbage collection using real-time data and smart routing.

---

### How It Works:
1. **Monitoring Bin Levels**:  
   Each smart bin is equipped with an **Ultrasonic Sensor** to constantly measure the garbage level inside. When the bin gets full, the system detects it automatically.

2. **Location Tracking**:  
   A **GPS Module** is attached to each bin, recording the exact location. This information is crucial when sending updates to the cloud.

3. **Real-Time Alerts**:
   Using an **ESP32 microcontroller**, the bin sends data (garbage level + location) to an IoT cloud platform (like Blynk or Firebase).

4. **Optimized Route Finding**:  
   On the server side, a **Python-based shortest path algorithm** (like Dijkstra’s or A*) calculates the best route for the garbage truck to collect *only* the full bins, saving time and fuel.

5. **Driver Notification**:  
   Once the route is generated, the system can send location data or even a message directly to the driver’s mobile device, guiding them efficiently.

6. **User Interface**:  
   In the Blynk mobile app (or a dashboard), admins can:
   - View bin fill status
   - See locations of full bins on a map
   - Get the optimized collection route in real-time

---

###  Technologies Used:
| Technology | Purpose |
|:-----------|:--------|
| **ESP32-WROOM** | Main controller for connecting sensors and sending data to cloud |
| **Ultrasonic Sensor (HC-SR04)** | To measure the garbage level inside the bin |
| **GPS6MU2 Module** | To get the real-time location of each bin |
| **16×2 LCD Display with I2C** | To display bin status locally |
| **Blynk IoT App / Firebase** | Cloud platform for real-time monitoring and notifications |
| **Python (Dijkstra)** | To compute the shortest and most efficient collection route |
| **Internet (Wi-Fi)** | To send/receive bin data to/from the cloud |
| **Switch/Sensor** | To detect bin type or additional events (optional) |

---

### How to Use the System:
- **For Admins**:  
  - Open the Blynk app or Dashboard.  
  - Check bin statuses (full/empty).  
  - View suggested collection routes for trucks.  
  - Send route data to drivers if needed.

- **For Drivers**:  
  - Receive optimized collection instructions on mobile.  
  - Follow the shortest route to pick up only full bins.  
  - Save time, fuel, and keep the city cleaner faster!

- **For the City**:  
  - Cleaner environment   
  - Less fuel consumption   
  - Smarter waste management 

---

# The Goal:
> **Transform waste collection into a smart, efficient, and sustainable process for a cleaner future.**
![output 3](https://github.com/user-attachments/assets/3ac88191-c4a8-4b3f-bd68-136f6198bdc8)
![output 2](https://github.com/user-attachments/assets/970f68ce-d930-41c3-986c-b543fa853fb0)
![output 1](https://github.com/user-attachments/assets/b5d4f2d9-90bb-42fa-9188-a11d41779f88)
![output 1](https://github.com/user-attachments/assets/f4f2f434-0d97-4a70-91a7-354cf5df21dd)
