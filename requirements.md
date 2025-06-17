# Q3: Functional & Non‑Functional Requirements  
**Project:** FleetFlow Manager  
**Company:** FleetFlow Logistics

## Functional Requirements
1. **FR1: Truck Location Tracking**  
   System tracks truck GPS coordinates in real‑time and displays live map views.

2. **FR2: Driver Management**  
   Register, view, update and delete driver profiles with license and contact information.

3. **FR3: Schedule Assignment**  
   Admins can assign delivery jobs to available drivers with time slots and destinations.

4. **FR4: Container Assignment**  
   Link containers to trucks, including load status (e.g., loaded, in transit, delivered).

5. **FR5: Route Planning**  
   System suggests optimal delivery routes based on distance and estimated fuel usage.

6. **FR6: Delivery Tracking**  
   Update delivery status (e.g., en route, delayed, completed) and timestamp logs.

7. **FR7: Customer Management**  
   Manage customer profiles and order history for invoicing and service tracking.

8. **FR8: Order & Billing Generation**  
   Create delivery orders, calculate costs, and generate PDF invoices for clients.

9. **FR9: Maintenance & Fuel Log**  
   Record truck maintenance schedules and fuel costs with date, cost, and notes.

10. **FR10: Notification System**  
    Send alerts to drivers and clients about upcoming schedules, updates, or delays.

## Non‑Functional Requirements
- **NFR1: Performance**  
  System should respond to user inputs within 2 seconds.

- **NFR2: Availability**  
  Ensure 99.5% uptime for 24/7 logistics operations.

- **NFR3: Reliability**  
  Maintain operation with a failure rate ≤ 0.2% during daily usage.

- **NFR4: Cross‑platform Compatibility**  
  Must work smoothly on both desktop and mobile browsers.

## Technology Justification
- **Backend:** Node.js + Express — scalable, real‑time event handling for GPS & notifications.  
- **Database:** MySQL — relational integrity for trucks, drivers, orders & billing.  
- **Frontend:** React + Tailwind CSS — componentized, responsive UI, rapid iteration.  
- **Hosting:** AWS Elastic Beanstalk + RDS — managed scaling, high‑availability SLAs.

