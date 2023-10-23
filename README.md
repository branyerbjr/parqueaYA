# parqueaYA
# IoT Vision Project

Welcome to the IoT Vision Project, a comprehensive system that integrates IoT, computer vision, and mobile development. This project aims to provide a complete solution for capturing, processing, and presenting visual data. Here's an overview of its components:

## Components

- **ESP32-CAM**: We use ESP32-CAM as our IoT device. This small yet powerful board combines the ESP32 microcontroller with a camera, enabling it to capture images and stream video.

- **Django REST API**: The project backend is built using Django, a high-level Python web framework. It provides a RESTful API for communication between the ESP32-CAM, the web frontend, and the mobile app.

- **React.js Web Frontend**: The web interface is developed using React.js, a popular JavaScript library for building user interfaces. It allows users to access the visual data captured by the IoT device.

- **Kotlin Mobile App**: The Android mobile app is built with Kotlin using Android Studio. This app provides a mobile interface for users to interact with the system on the go.

## Project Structure

The project is structured as follows:

- **`/esp32-cam`**: This directory contains the code and configuration for the ESP32-CAM device. It handles image capture, processing, and communication with the API. 

- **`/django-api`**: This directory houses the Django project, which serves as the REST API. It manages the data, user authentication, and communication between clients. [parqueaya-api](https://github.com/branyerbjr/parqueaya-a).

- **`/react-frontend`**: This directory contains the React.js web frontend, which users can access through their web browsers to view and interact with the visual data. [parqueaya-web](https://github.com/branyerbjr/parqueaya-web).

- **`/android-app`**: Here, you'll find the Kotlin mobile app built with Android Studio. It allows users to access the system from their Android devices. [parqueaya-android]().

## Getting Started

To get started with the IoT Vision Project, follow the setup instructions in each component's respective directory. You'll need to set up and configure the ESP32-CAM, deploy the Django API, launch the React.js frontend, and install the Android app on your mobile device.

Please refer to the individual README files within each directory for detailed instructions.

## Support and Contribution

If you have any questions, encounter issues, or want to contribute to the project, please feel free to reach out to us. We welcome contributions and collaborations from the community to make this project even better.

## License

This project is licensed under the [Apache License, Version 2.0](LICENSE).

You can find the full text of the license [here](https://www.apache.org/licenses/LICENSE-2.0).

### Copyright and Permissions Notice

Copyright [2023] [parqueaYA]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Contributors

We appreciate the valuable contributions of developers and team members in various roles. Here are the primary areas of contribution and the roles associated with them:

### Backend Developers

- **[carlosDaniel0293](https://github.com/CarlosDaniel0293)**: Role - Backend Developer, Contribution - Django API development.
- API data processing and management.

### Frontend Developers

- **[Bel1en](https://github.com/Be1en)**: Role - Frontend Developer, Contribution - React.js web interface development.
- User interface design and optimization.

### Mobile App Developer

- **[MICHELLCGs](https://github.com/MICHELLCGs)**: Role - Mobile App Developer, Contribution - Android mobile app development with Kotlin.

### IoT Architect

- **Name 6**: Role - IoT Architect, Contribution - ESP32-CAM setup, image capture, and communication with API.

### DevOps Engineer

- **Name 7**: Role - DevOps Engineer, Contribution - System deployment, server management, and CI/CD pipeline setup.

...

We want to express our gratitude to all the contributors who have dedicated their time and expertise to make this project a reality. If you are interested in joining the team or have ideas for improvements, please don't hesitate to reach out. We value your input and collaboration.
