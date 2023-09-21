# Video to MP3 Converter

## Overview

The Video to MP3 Converter is a software application that allows users to convert video files into MP3 audio files. This README provides an overview of the project, its components, and instructions on how to use it.

## Features

- Convert various video formats (e.g., MP4, AVI, MKV) to MP3 audio.
- Simple and intuitive user interface.
- Support for batch processing multiple video files.
- Configurable output settings (e.g., bit rate, audio quality).

## Components

The project consists of several key components:

1. **Auth Service**: Manages user authentication and authorization.
2. **Gateway Service**: Acts as a central entry point for requests.
3. **Converter Service**: Responsible for converting video files to MP3 format.
4. **Notification Service**: Handles notifications and alerts.
5. **MongoDB & GridFs**: Stores metadata and files.
6. **Kubernetes & RabbitMQ**: Orchestrates and manages containerized services.
7. **Frontend**: Provides a user-friendly interface for users to interact with the application.

## Installation and Usage

To use the Video to MP3 Converter, follow these steps:

1. Clone the project repository:
~~~
https://github.com/Satyam298/converter-app.git 
~~~
2. Install the required dependencies for each service.

3. Configure the services according to your environment (e.g., database connection, RabbitMQ settings).

4. Build and deploy the services using Kubernetes.

5. Access the frontend application in your web browser.

6. Upload the video files you want to convert, configure conversion settings if needed, and start the conversion process.

7. Monitor the progress and receive notifications once the conversions are complete.

![Screenshot 2023-09-21 22:21:38](https://github.com/Satyam298/converter-app/assets/79797786/57ba284b-d7f2-4c45-8d30-8a48c9d857cc)
![Screenshot 2023-09-21 22:20:42](https://github.com/Satyam298/converter-app/assets/79797786/0ff537b5-01c7-4701-a023-5c084b386222)
![Screenshot 2023-09-21 22:21:16](https://github.com/Satyam298/converter-app/assets/79797786/8ead2106-3de1-4ca7-8f7d-0ec37cb0e19b)


## Contributing

Contributions to this project are welcome. If you encounter issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
