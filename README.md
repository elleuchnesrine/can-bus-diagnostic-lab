# CAN Bus Diagnostic Communication Lab

A complete simulation of automotive diagnostic communication between a diagnostic tester (client) and an ECU (server) using virtual CAN bus.

## 📋 Project Overview

This lab demonstrates real-world automotive diagnostic protocols using OBD-II standards, simulating the communication between diagnostic tools and vehicle ECUs (Engine Control Units) over CAN bus.

### 🏗️ Architecture



### 🎯 Key Features
- **Virtual CAN Bus** simulation using vcan0 interface
- **OBD-II Protocol** implementation for Engine RPM (PID 0x0C)
- **Real-time communication** between tester and ECU
- **Dynamic RPM simulation** with realistic variations
- **Error handling** and timeout management

## 🚀 Quick Start

### Prerequisites
- Windows with WSL2 (Ubuntu) or Linux environment
- Python 3.6+

### Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/can-bus-diagnostic-lab.git
cd can-bus-diagnostic-lab
