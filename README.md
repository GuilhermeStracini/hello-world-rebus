# Hello World Rebus

📚 A repository to explore and learn **[Rebus](https://github.com/rebus-org/Rebus)** with .NET.

[![wakatime](https://wakatime.com/badge/github/GuilhermeStracini/hello-world-rebus.svg)](https://wakatime.com/badge/github/GuilhermeStracini/hello-world-rebus)
[![Maintainability](https://api.codeclimate.com/v1/badges/b3f0aedd63fff2c00f19/maintainability)](https://codeclimate.com/github/GuilhermeStracini/hello-world-rebus/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/b3f0aedd63fff2c00f19/test_coverage)](https://codeclimate.com/github/GuilhermeStracini/hello-world-rebus/test_coverage)
[![CodeFactor](https://www.codefactor.io/repository/github/GuilhermeStracini/hello-world-rebus/badge)](https://www.codefactor.io/repository/github/GuilhermeStracini/hello-world-rebus)
[![GitHub license](https://img.shields.io/github/license/GuilhermeStracini/hello-world-rebus)](https://github.com/GuilhermeStracini/hello-world-rebus)
[![GitHub last commit](https://img.shields.io/github/last-commit/GuilhermeStracini/hello-world-rebus)](https://github.com/GuilhermeStracini/hello-world-rebus)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/b491fdc0fa5a4f46badb451bfb07569e)](https://app.codacy.com/gh/GuilhermeStracini/hello-world-rebus/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)

---

## About

This repository demonstrates the basics of **Rebus**, a simple and flexible service bus library for .NET. It is designed to help developers implement reliable messaging patterns like publish/subscribe and sagas.

---

## Features

- **Reliable Messaging**: Easily send and receive messages across services.
- **Integration with RabbitMQ**: Demonstrates usage with RabbitMQ as a transport layer.
- **Saga Pattern**: Learn to implement the saga pattern for managing long-running workflows.

---

## Prerequisites

To get started with this repository, you need:
- **.NET SDK**: Available [here](https://dotnet.microsoft.com/download).
- **RabbitMQ**: Installed and running locally or accessible in your environment.

---

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/GuilhermeStracini/hello-world-rebus.git
   ```
2. Navigate to the project directory:
   ```bash
   cd hello-world-rebus
   ```
3. Restore dependencies:
   ```bash
   dotnet restore
   ```
4. Update configuration for RabbitMQ (if needed) in the app settings.
5. Run the application:
   ```bash
   dotnet run
   ```

---

## Useful Links

- [Rebus Official Documentation](https://github.com/rebus-org/Rebus)
- [Rebus Samples](https://github.com/rebus-org/RebusSamples)
- [Saga with Rebus + RabbitMQ](https://medium.com/@MilanJovanovicTech/mnw-031-implementing-the-saga-pattern-with-rebus-and-rabbitmq-5a42d28dc7e4)

---

## Contribution

Contributions are welcome! If you'd like to enhance this repository, feel free to:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Submit a pull request with a detailed description.

---

## License

This project is licensed under the [MIT License](LICENSE).
