# Offline Voice Assistant – **Luma** (IoT + Arduino + AI Thinker VC-02)

This project is an **offline smart voice assistant prototype**, inspired by Amazon Alexa, built using **Arduino Uno**, **AI Thinker VC-02**, **Relay Module**, and common IoT components.  
The system works **100% offline**, without internet, and can control home appliances such as lights, fans, bulbs, etc.  

It supports **50+ custom offline voice commands**, including controlling appliances, answering basic questions, reciting poems, and performing custom programmed actions.

---

## 🟣 Assistant Name & Wake Word

Your offline assistant is officially named **Luma**.

To wake the assistant, simply say:

### 🔊 **“Hey Luma”**

After this wake command, Luma actively listens and executes your next instruction.

Example wake commands:
- “Hey Luma, turn on the light”  
- “Hey Luma, turn on the fan”  
- “Hey Luma, tell me a poem”  
- “Hey Luma, who is the Prime Minister?”  

---

## 🚀 Project Overview
Luma listens to commands, processes them locally using the **AI Thinker VC-02** module, and triggers actions using **Arduino Uno**.  
It behaves like a complete **offline home automation assistant**.

Key Highlights:
- Fully offline, no Wi-Fi required  
- 50+ voice commands stored in VC-02’s 2MB flash  
- Works instantly with very low response delay  
- Controls home devices via relay  

---

## 🧠 Components & Tech Used

### 🔹 Hardware
- **Arduino Uno**  
- **AI Thinker VC-02 (Offline Voice Recognition)**  
- **Relay Module** (fan/light/TV control)  
- **KED/LED Bulb**  
- **Jumper Wires**  
- **Breadboard**  
- **5V Battery / Power Bank (optional)**  

### 🔹 Features
- Offline speech recognition  
- 2MB flash for storing command dataset  
- Fast local processing  
- Expandable command set  

---

## 🔌 Power Options

Luma can be powered in two different ways:

### 1️⃣ **USB (Laptop / PC)**
- Arduino connected directly to laptop  
- Provides stable **5V power**  
- Best for development & debugging  

### 2️⃣ **5V Battery / Power Bank**
- Makes the system completely portable  
- Works standalone without any computer  
- VC-02 and Relay work smoothly on 5V  

---

## 🎤 Example Voice Commands

### 🏠 Home Automation Commands
- “Hey Luma, turn on the light”  
- “Hey Luma, turn off the fan”  
- “Hey Luma, switch on the bulb”  
- “Hey Luma, turn off the TV”  

### 🧠 General Knowledge / Fun Commands
- “Hey Luma, tell me a poem”  
- “Hey Luma, who is the Prime Minister?”  
- “Hey Luma, who built you?”  
- “Hey Luma, say something funny”  

### 🎯 Custom Commands
You can train up to **50 custom commands** in the VC-02 module.

---

## 🔧 How Luma Works

### 1. Wake Word Detection  
Luma stays in listening mode for **“Hey Luma”**.

### 2. Offline Speech Recognition  
VC-02 matches the spoken phrase with stored commands.

### 3. Signal → Arduino  
Arduino receives command ID from VC-02.

### 4. Action Execution  
Arduino controls:
- Relay  
- Fan  
- Bulb  
- Any connected appliance  

### 5. Response  
Optional audio playback (poem, intro, etc.).

---

## 🔌 Circuit Connections

- **Arduino TX → VC-02 RX**  
- **Arduino RX → VC-02 TX**  
- **5V & GND** → Both modules  
- **Relay IN → Arduino Digital Pin**  
- **Relay Output → Appliance (Fan/Light/Bulb)**  

---

## 📚 What I Learned

- Integration of IoT modules  
- Offline speech recognition systems  
- Arduino coding & serial communication  
- Relay-based AC load control  
- Embedded system design  
- Power management for microcontrollers  
- Hands-on home automation engineering  

---

## 🧭 Future Improvements

- Add LCD display for voice feedback  
- Add Bluetooth / Wi-Fi (Hybrid Luma)  
- Wake-word LED indicator  
- Add alarms, reminders, routines  
- Create a 3D-printed outer case  
- Add background noise filtering  

---

## 👤 Author  
**Rahul Mishra**

GitHub: https://github.com/MishraRahul02  
LinkedIn: [*(add your link)*  ](https://www.linkedin.com/in/rahul-mishra-319794309/)

