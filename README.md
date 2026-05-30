# QUENCH - Smart Water Dispenser

Revolutionizing public water dispensing with seamless digital payments.

QUENCH is an IoT-enabled smart water dispenser that replaces traditional coin-operated systems with dynamic QR-code based UPI payments. The system provides a contactless, secure, and convenient way for users to purchase drinking water while enabling real-time payment verification and automated dispensing.

---

## Overview

Traditional water dispensers often rely on coin-operated mechanisms that can be inconvenient, unhygienic, and difficult to maintain.

QUENCH modernizes this experience by integrating:

- Dynamic QR Code Generation
- UPI-Based Digital Payments
- Real-Time Payment Verification
- Automated Water Dispensing
- Water Flow Monitoring

The system is designed to support smart cities, public infrastructure, educational institutions, transportation hubs, and commercial spaces.

---

## Key Features

- Dynamic QR Code Generation
- UPI Payment Integration
- Contactless Transactions
- Automated Water Dispensing
- Real-Time Payment Verification
- Digital Transaction Records
- Water Flow Monitoring
- User-Friendly Display Interface

---

## Hardware Components

| Component | Purpose |
|------------|------------|
| ESP32 | Main Controller |
| TFT 2.8" LCD Display | User Interface |
| Water Flow Sensor | Flow Measurement |
| Solenoid Valve | Water Control |
| Power Supply Module | System Power |
| Wi-Fi Module (ESP32 Built-in) | Internet Connectivity |

---

## Software Technologies

- Embedded C/C++
- Arduino IDE
- ESP32 Framework
- UPI Payment Integration
- QR Code Generation
- Wi-Fi Communication

---

## Working Principle

1. User selects the desired amount of water.
2. System generates a dynamic QR code.
3. User scans the QR code and pays via any UPI application.
4. Payment verification is performed.
5. Upon successful payment, the dispenser activates.
6. Water flow is monitored using the flow sensor.
7. Dispensing automatically stops after the purchased quantity is delivered.

---

## System Architecture

```text
User
  │
  ▼
QR Code Display
  │
  ▼
UPI Payment Gateway
  │
  ▼
Payment Verification
  │
  ▼
ESP32 Controller
  │
  ▼
Water Flow Sensor
  │
  ▼
Solenoid Valve
  │
  ▼
Water Dispensing
```

---

## Technical Specifications

- Controller: ESP32
- Display: TFT 2.8" LCD
- Connectivity: Wi-Fi
- Payment Method: UPI
- Flow Sensor Accuracy: ~95%
- Transaction Type: Dynamic QR Payments

---

## Future Enhancements

- Water Quality Monitoring
- Mobile Application
- Consumption Analytics
- Cloud Dashboard
- Remote Device Monitoring
- Predictive Maintenance
- Subscription-Based Usage Models

---

## Applications

- Railway Stations
- Bus Terminals
- Airports
- Educational Institutions
- Corporate Campuses
- Smart Cities
- Public Water Kiosks

---

## Team Members

- Raadhesh Bajoria
- Kinshuk Pandala
- Manthan Sontakke

---

## Supervisor

Dr. Amit Kumar Singh

### Academic Support

Dr. Soumitra Keshari Nayak

---

## Project Vision

Making safe drinking water more accessible through smart, cashless, and connected infrastructure.
