# Smart-Elevator-Control

This project contains an ER diagram for a multi-building elevator control system.
  
## ER Diagram
<img width="2319" height="1355" alt="Smart Elevator Control_dark" src="https://github.com/user-attachments/assets/e5f984f5-c3af-4622-8f44-b2a7f82f9981" />

eraser link: https://app.eraser.io/workspace/1WoZ2zNgU0rsKD42UVvf?origin=share

It supports:
	•	Managing multiple buildings, floors and elevators
	•	Mapping elevators to the floors they serve
	•	Handling floor requests (source → destination)
	•	Assigning requests to elevators
	•	Tracking ride logs for completed trips
	•	Recording maintenance history for each elevator

Key points:
	•	Elevators and floors have a many-to-many relationship
	•	Floor requests store both source and destination floors
	•	Ride assignments and logs are separated for better tracking
	•	Maintenance history is stored without overwriting past data

The ER diagram image is included in this repository.
