# Smart India Hackathon Workshop
# Date:8-5-2024
## Register Number:212223220026
## Name:GOWSHIK S
## Problem Title
E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
## Problem Creater's Organization
Ministry of Environment

## Idea
Develop a platform named "GreenTech Recycle" that enables users to find the nearest e-waste collection and recycling facilities. The site offers educational pop-ups highlighting the hazards of e-waste and the environmental and health impacts of improper disposal. Users can input their device model to receive credit points based on the estimated precious metals recoverable from the device. Points can be redeemed for rewards or donations to environmental causes.

## Proposed Solution / Architecture Diagram
![Screenshot 2024-05-08 201503](https://github.com/gowshik145/SIHPS/assets/155086127/ebb2a5a2-86c0-46f1-ac50-01a27ffedeae)


## Use Cases
![Screenshot 2024-05-08 202211](https://github.com/gowshik145/SIHPS/assets/155086127/e5977c56-7dd9-4e26-96fd-f25ac0b72150)


## Technology Stack
Frontend: React for a responsive user interface, Bootstrap for styling, and D3.js for interactive data visualization (e.g., showing environmental impacts graphically).

Backend: Node.js with Express for server-side processing, MongoDB for database storage (e.g., user profiles, e-waste facility locations), and RESTful API for communication between frontend and backend.

Geolocation: Google Maps API or OpenStreetMap for location-based services, enabling users to find the nearest e-waste recycling facilities.

Authentication and Authorization: Firebase Authentication or Auth0 for secure user login/registration.

Cloud Hosting: AWS, Google Cloud Platform, or Azure for scalable hosting, serverless functions, and data storage.

Credit Point System: Stripe or PayPal integration for managing credit points, rewards, and donations.

CI/CD: Jenkins or GitHub Actions for continuous integration and deployment.

Testing: Jest and Enzyme for unit testing, and Selenium for end-to-end testing

## Dependencies
Geolocation Services: Accurate geolocation APIs for identifying user location and nearest recycling facilities.

Device Data: Access to a comprehensive database of electronic devices and their components for calculating credit points.

Security Compliance: Ensure data protection, user authentication, and privacy in compliance with regulations (e.g., GDPR).

E-Waste Partners: Partnerships with certified e-waste recycling facilities to ensure reliable data on their locations and recycling processes.

Environmental Education Content: Source accurate and engaging educational content on e-waste and its impact on health and the environment.
