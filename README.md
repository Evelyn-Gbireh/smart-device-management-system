# Smart Device Management System

An Object-Oriented Programming (OOP) implementation designed to simulate control mechanics over modern Smart Home devices. Built as a Python-based ecosystem demonstrating principles of abstraction, proper inheritance hierarchies, and strict data validation via getters and setters.

## Core OOP Concepts Applied
* **Inheritance:** Extends a base abstract concept (`SmartDevice`) seamlessly down to distinct hardware types (`SmartLight`, `TemperatureSensor`, `SecurityCamera`) sharing standard power properties.
* **Encapsulation:** Protects crucial states (`__device_id`, `__power_status`) from direct outside mutation, cleanly enforcing explicit rules using Pythonic `@property` decoratored getters and setters.
* **Data Validation:** Prevents data leaks/corrupt system states; throws custom errors if `device_id` values are built blank, and maintains hard ceilings/floors for dimming features (`0-100%`).

## Project Structure
* `smart_device_management_system.py`: The single primary executable runtime module housing all components and the interactive CLI engine.

## Installation & Setup Guide

### Prerequisites
Make sure you have Python 3.8 or higher installed on your platform. 

### Running the Program
1. Clone the project locally or pull the repository directly:
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/smart-device-management-system.git](https://github.com/YOUR_GITHUB_USERNAME/smart-device-management-system.git)
