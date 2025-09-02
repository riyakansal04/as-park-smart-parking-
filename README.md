# 🚗 Automatic Smart Car Parking System (AS Park)

## 📌 Introduction
In the ever-changing world of technology, automation has become part of our daily lives.  
An important application is **parking systems**, which not only improve convenience but also manage limited parking space efficiently.  

This project — **Automatic Smart Car Parking System (AS Park)** — is built using **Arduino UNO, IR sensors, servo motor, and an LCD display**.  
It automates vehicle entry/exit, displays available slots in real-time, and ensures efficient use of parking space.  

---

## 🛠️ Components Required
- Arduino UNO  
- 20×4 LCD Display + I2C Module  
- 2× IR Sensors (entrance & exit)  
- 6× IR Sensors (for parking slots)  
- Mini Servo Motor SG-90 (barrier control)  
- Power source (220V → 5V, 2A adapter)  
- Proteus simulation software  

---

## 🖥️ Simulation (Proteus)
The **Proteus simulation** demonstrates how Arduino, sensors, LCD, and servo interact before real-world deployment.  

<!-- Replace the link below with your uploaded simulation image -->
![Simulation Screenshot](https://via.placeholder.com/600x300.png?text=Simulation+Screenshot)  

---

## 🔌 Circuit Diagram
The circuit integrates **IR sensors, LCD, and servo motor** with Arduino to automate parking.  

<!-- Replace the link below with your uploaded circuit diagram -->
![Circuit Diagram](https://via.placeholder.com/600x300.png?text=Circuit+Diagram)  

---

## 📟 Working
1. **Vehicle Entry** → IR sensor detects car → Barrier opens (servo rotates).  
2. **Slot Monitoring** → IR sensors in each slot detect occupancy (`Fill` / `Empty`).  
3. **LCD Display** → Shows available slots and updates in real-time.  
4. **Vehicle Exit** → Exit IR sensor detects → Barrier opens, slot count increases.  
5. **Parking Full** → LCD shows “Sorry, Parking Full”.  

---


## 🛠 Tech Stack
- **Hardware:** Sensors (IR/Ultrasonic), Microcontroller (Arduino/Raspberry Pi)  
- **Software:** Python, Machine Learning  
- **Other Tools:** Data Visualization, IoT frameworks  

---

## 📂 Project Structure
/src → Source code
/images → Photos & diagrams
/docs → Documentation & reports

---

## 🖼 Project Photos
![Prototype](images/prototype.jpg)  
![System Flow](images/system_flow.jpg)  

---

## 🚀 Future Improvements
- Mobile app for real-time parking updates  
- Cloud integration for large-scale deployments  
- AI optimization for traffic flow  

---

## 👩‍💻 Author
**Riya Kansal**  
[LinkedIn](https://www.linkedin.com/in/riya-kansal-963042268/) | [GitHub](https://github.com/riyakansal04)
