# Smart India Hackathon Workshop
# Date: 08/05/24
## Register Number:212221220038
## Name: PRADEEPASRI S
## Problem Title
E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
## Problem Creater's Organization
Ministry of Environment

## Idea
EcoRecycleHub: Your go-to platform for eco-friendly e-waste disposal.

Locator Feature: Input your location or let us find it for you; discover nearby e-waste facilities effortlessly.

Educational Pop-ups: Learn about the environmental and health impacts of e-waste with informative pop-ups as you browse.

Model Input and Rewards: Input your device model to earn credit points based on the recovered materials' estimated value.

User Accounts: Track your recycling history, accumulate rewards, and receive personalized recommendations with your account.

Partnerships and Incentives: Benefit from exclusive incentives and rewards through our partnerships with leading electronics brands.

Mobile-Friendly: Enjoy a seamless experience across devices – desktop, tablet, or mobile.

Feedback and Improvement: Share your thoughts and help us improve with our feedback mechanism.

Join the Movement: Become part of the EcoRecycleHub community and contribute to a greener, healthier planet, one electronic device at a time.

## Proposed Solution / Architecture Diagram
1.User Interface (UI):
Frontend application accessible via web browsers and mobile devices.
Provides the user interface for searching e-waste facilities, educational pop-ups, user account management, and rewards tracking.

2.Application Server:
Backend server responsible for handling user requests, processing data, and communicating with other components.
Implements the business logic of the application, including search functionality, rewards calculation, and user authentication.

3.Database:
Stores user data, e-waste facility information, device models, rewards points, and other relevant data.
Can be a relational database management system (RDBMS) or a NoSQL database depending on scalability and data structure requirements.

4.Geolocation Service:
Utilizes geolocation APIs to determine the user's location when they allow access or manually input it.
Provides location data to the application server for finding nearby e-waste facilities.

5.Educational Content Repository:
Repository for storing educational content related to e-waste recycling.
Contains information, images, videos, and interactive elements for displaying educational pop-ups and tooltips on the UI.

6.External APIs:
Integrates with external APIs for mapping and geolocation services to fetch and display e-waste facility locations on the map.
May also integrate with electronics manufacturers' APIs for retrieving device model information and calculating rewards points.

7.Partnership Integration:
Integrates with partner systems, such as electronics manufacturers or retailers, to provide exclusive incentives and rewards for users.
Communicates with partner APIs to validate rewards and incentives earned by users.

![ewaste flowchart](https://github.com/pradeepasri26/SIHPS/assets/131433142/a7be3008-d36a-4802-8f7d-9b780efa6211)

## Use Cases

1.Find Nearest Facilities:
Users locate nearby e-waste facilities based on their location.

2.Access Educational Content:
Users learn about e-waste disposal best practices and environmental impact.

3.Earn Rewards by Inputting Device Model:
Users input their device model to earn recycling rewards.

4.Manage User Account:
Users track recycling history, rewards, and preferences.

5.Redeem Partnership Rewards:
Users redeem exclusive rewards from partnerships.

6.Provide Feedback:
Users offer suggestions and report issues for platform improvement.

7.Share Recycling Achievements:
Users share milestones and awareness on social media.

8.Filter E-Waste Facilities:
Users refine search results based on specific criteria.

## Technology Stack

1.Frontend:React.js with Bootstrap for responsive UI.

2.Backend: Node.js with Express.js, MongoDB for data storage.

3.Authentication: JWT for user authentication.

4.Map Integration: Google Maps API.

5.Cloud Services: AWS for hosting, S3 for storage.

6.DevOps: CI/CD with GitHub Actions, monitoring with AWS CloudWatch.

7.Security: SSL/TLS encryption, OWASP Top 10 compliance.

## Dependencies

1.Frontend: React.js, React Router, Axios, Bootstrap or Material-UI

2.Backend: Node.js with Express.js, Mongoose, Passport.js, jsonwebtoken, Dotenv

3.Database: MongoDB

4.Geolocation Services: Google Maps API or Mapbox API

5.Cloud Services: AWS SDK, AWS S3 SDK

6.Development and Deployment: GitHub Actions or CircleCI, AWS CloudWatch

7.Security: Helmet, bcrypt.js
