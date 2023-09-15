# A-IoT-KNU

This repository contains the source code and project description for the "IoT Platform" - a multi-user platform designed to capture sensor data.

## Project Description

This project aims to create an infrastructure for collecting, storing, and displaying sensor data, such as temperature, humidity, pressure, air quality, and illumination. Data from various sensors is sent to a message queue in the form of individual messages.

Key functionalities of the project include:

- **Multi-User Interface:** Each client can create an account and monitor sensor readings.

- **Locations:** Users can have multiple locations where sensors are installed.

- **Message Information:** Each message contains details about the client who owns the sensor, the location identifier, and the sensor type.

- **Historical Data:** Users can view historical data of sensor readings.

- **Automatic Interface Updates:** When new data arrives, the interface updates automatically without the need for page refresh.

## Architectural Considerations

The project has several important architectural attributes:

- **Security:** The system is developed with security in mind to protect against "man-in-the-middle" attacks.

- **Portability:** The system can be easily deployed in both cloud solutions and private data centers.

## Contribution to the Project

We welcome contributions from other developers. If you'd like to get involved in development, please follow our contribution standards and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE.md).

## Contact

If you have any questions or suggestions, please feel free to reach out to us via [email](mailto:youremail@example.com).

---

Start contributing to the project and building your IoT Platform! Thank you for your participation.