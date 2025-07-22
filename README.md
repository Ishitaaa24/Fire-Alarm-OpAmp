
# 🔥 Operational Amplifier-Based Fire Alarm

This project demonstrates a simple yet effective fire alarm system using an IC 741 operational amplifier. The circuit leverages analog electronics principles to detect elevated temperatures and trigger both visual and audio alerts.

---

## 💡 Objective

To design a temperature-sensitive alarm system that activates when a preset temperature threshold is exceeded using basic analog components.

---

## 🔧 Working Principle

- A **thermistor (NTC)** is used as the temperature-sensing component. As temperature increases, its resistance decreases.
- The thermistor forms a **voltage divider** with a fixed resistor.
- This analog voltage is fed to one input of the **IC 741 Op-Amp**, configured as a **comparator**.
- When the thermistor voltage crosses a reference voltage (set at the other input of the Op-Amp), the output switches states.
- The high output drives an **NPN transistor**, which powers:
  - An **LED** (for visual indication)
  - A **buzzer** (for sound alert)

---

## 🧪 Components Used

- IC 741 Operational Amplifier
- NTC Thermistor
- Fixed Resistors (for divider and base resistor)
- NPN Transistor (e.g., BC547)
- LED
- Buzzer
- 9V Power Supply

---

## 🖥️ Simulation

The design was simulated using **LTspice**, verifying:
- Output voltage transitions
- Trigger response to simulated temperature change

---

## 📌 Applications

- Fire or heat detection systems in small enclosures
- Safety automation in analog systems
- Educational analog electronics demonstration

---

## 🎓 Learning Outcomes

- Op-Amp comparator configuration
- Thermistor-based sensing circuits
- Practical use of transistors as switches
- Analog system integration for real-world sensing
