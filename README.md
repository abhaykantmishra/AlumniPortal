# 🎓 Alumni Portal – College Alumni Registration & Admin Management System

Welcome to the **Alumni Portal**, a web platform designed to connect alumni with their college, fostering a vibrant and engaged alumni network. This portal allows alumni to register their profiles, stay updated on events, and engage with their alma mater. The admin dashboard enables administrators to easily manage alumni profiles and promote upcoming events.

## 🚀 Key Features

- **📝 Alumni Registration**: Alumni can register their profiles, including personal and professional details, to stay connected with their college.
- **🛠️ Admin Dashboard**: Admins have full control to approve, update, and manage alumni profiles, ensuring accurate and up-to-date information.
- **📅 Event Management**: Admins can create and manage upcoming alumni events, ensuring greater participation from the community.
- **🌟 Featured Alumni**: Highlight distinguished alumni by displaying their image, name, and current role, providing inspiration and connection to others.

## 🛠️ Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/) for SSR & SSG and fast development, [Tailwind CSS](https://tailwindcss.com/) better code readablity and management
- **Backend**: [Node.js](https://nodejs.org/), [Express.js](https://expressjs.com/) - microservice architecture for scalability of backend.
- **Database**: [MongoDB](https://www.mongodb.com/)- Fast read and write and easiar to use than SQL databases.
- **Payment Integration**: [RazorPay]
- **Real-Time Communication**: [Socket.io](https://socket.io/) for real time messaging feature.
- **Image Hosting**: [Cloudinary](https://cloudinary.com/)- for better image optimization and formatting.
- **Containerization**: [Docker](https://www.docker.com/) 
- **Animations**: [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/) - for smooth animation providing better user experience.
- **Cloud Hosting**: Used combination of AWS EC2 & AWS Lambda for backend servers, And Vercel for hosting frontend.


# LinkLum - User Flow Schema

## Overview

This project outlines the user flow schema for a **College Alumni and Student Registration Portal(LinkLum)**. It is designed to provide a clear understanding of the registration process and the interactions between users (alumni, students, and administrators) within the platform.

### Features:

- **Alumni Registration**: Allows alumni to create profiles, manage events, feature prominent alumni, and access job and donation portals.
- **Student Registration**: Students can create profiles with restrictions, apply for jobs, and access a job portal.
- **Admin Access**: Admins manage accounts, events, and alumni features.
- **User Sessions**: Both alumni and student users can browse job opportunities, apply for jobs, and access messaging functionalities.
- **Real Time Messaging**: Verified students can message their alumni and peers in real time.
- **Student Hub**: Students can raise their problems to the college.
- **Memories**: Students & Alumni can share post to create memories.
- **Alumni Direcotory**: Students can search alumni by their year of passing, name, branch & location, And browse through their profile to know more about them.
- **Event Management**: College can create a event on platform and student & alumni can participate in them.

## Project Preview

[View on Eraser ![](https://app.eraser.io/workspace/nUk7TGsdzzudksvIKjeZ/preview?elements=iqTZG7Ls-pERnVCsI1O5mA&type=embed)](https://app.eraser.io/workspace/nUk7TGsdzzudksvIKjeZ?elements=iqTZG7Ls-pERnVCsI1O5mA)

## Flowchart Description

1. **Start**: Users begin by visiting the app.
2. **Choose Registration Type**: Users select whether they are registering as an Alumni or a Student.
   - If the college is not registered, it must register first.
3. **Alumni and Student Flows**: 
   - Alumni can access additional features such as managing events, posting job opportunities, and accessing the donation portal.
   - Students have profile restrictions but can access job listings and messaging functionalities.
4. **Admin Section**: Admins manage alumni profiles, accounts, and events.
5. **End Sessions**: Users and admins can end their sessions after completing tasks.

## Technology

The schema is created using **Eraser.io**, a visual collaboration and diagramming tool that helps map out processes and workflows efficiently.


