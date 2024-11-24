# BoxTrack

#### Student Name: *Shane Crowley* | Student ID: *W20109015*

> [Note]
> This repo is for learning purposes

BoxTrack is an inventory management device that enables a user to track their
consumption of objects from a physical container.

A Raspberry Pi (RPI) is affixed to the lid of a container.
Events, such as open and closing, are logged.

The user **inputs** the number of items removed (or added) using a joystick.
Warnings are triggered when the container is **empty** or open for a prolonged period.

A **web interface** can be used to track the status of the container.
A **dashboard** shows some basic analytics generated over time.

## Tools, Technologies and Equipment

* Languages: Python
* IoT platform: ThingSpeak
* Framework (stretch): Flask
* Devices: RPI, Sense HAT
* Sensor: inertial measurement
* Networking: HTTP
* Server automation: systemd
* Programming environment: SSH to NeoVim on Ansible-provisioned RPI

## Objective

### Requirements

- [ ] Container tracked with orientation sensor
- [ ] User data entry through joystick
- [ ] Capacity indicated with LED array
- [ ] Web interface for monitoring data
- [ ] Reaction sent from IoT platform
- [ ] Reaction or actuation based on sensor data

### Stretch goals

- [ ] Custom interface (e.g., flask backend, digital twin with three.js, HTTP API, dashboard with streamlit)
- [ ] Publish website with live data feed

## Project Repository

[https://github.com/edibotopic/boxtrack](https://github.com/edibotopic/boxtrack)
