# earth-orbit-hohmann-transfer-gmat
# GMAT Hohmann Transfer Simulation

This project demonstrates a Hohmann transfer in NASA GMAT (General Mission Analysis Tool) to move a spacecraft from a 7000 km circular Earth orbit to a 12000 km circular Earth orbit using two impulsive burns.

## Project Objective
The objective of this project is to simulate and visualize a basic orbital transfer maneuver between two circular Earth orbits. This helps in understanding how spacecraft can move efficiently from a lower orbit to a higher orbit.

## Mission Overview
The spacecraft starts in a near-circular low Earth orbit with:

- Semi-major axis: 7000 km
- Eccentricity: 0.0001
- Inclination: 28.5 degrees

Two impulsive burns are applied:

1. **Burn 1** raises the spacecraft into an elliptical transfer orbit.
2. **Burn 2** circularizes the spacecraft into the final 12000 km orbit.

## Why These Parameters Were Chosen
- **7000 km initial orbit** was chosen to represent a simple low Earth orbit.
- **12000 km final orbit** was selected so the transfer is clearly visible.
- **Very small eccentricity** was used to approximate a circular orbit.
- **28.5 degree inclination** gives the orbit a realistic orientation.
- **Two impulsive burns** were used because this is the standard Hohmann transfer method.

## Software Used
- NASA GMAT

## Files Included
- `HohmannTransfer.script` - GMAT script for the mission
- `screenshots/` - orbit visualization images

## Output
The simulation shows:
- the initial circular Earth orbit
- the elliptical transfer orbit after the first burn
- the final larger circular orbit after the second burn

## Screenshots

### Transfer Orbit
<img width="658" height="791" alt="Screenshot 2026-03-31 204741" src="https://github.com/user-attachments/assets/3f6576a5-578a-4b05-a7c8-cdd05986f67a" />


### Final Orbit
<img width="679" height="792" alt="image" src="https://github.com/user-attachments/assets/4a0b8c60-f5fc-42bd-9f86-914adaf88bd6" />

## Conclusion
This project successfully demonstrates a Hohmann transfer using GMAT. It shows how orbital maneuvers can be modeled using impulsive burns and propagation conditions in mission analysis software.
