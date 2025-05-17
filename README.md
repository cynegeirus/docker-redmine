# Redmine with Custom "Circle" Theme

This project provides a Dockerized Redmine instance with a custom theme named **Circle**. It uses PostgreSQL as the database backend and mounts persistent volumes for data storage.

## Features

- Redmine running in a Docker container
- PostgreSQL as the database
- Custom "Circle" theme included
- Persistent storage using Docker volumes

## Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/cynegeirus/docker-redmine.git
   cd docker-redmine
   ````

2. Make sure the custom theme is located in the `./circle` folder.

3. Build and start the containers:

   ```bash
   docker-compose up --build
   ```

4. Access Redmine:

   Open your browser and navigate to: [http://localhost](http://localhost)

## Default Credentials

Redmine automatically creates an administrator account during the installation process after the first run. The default username is "admin:admin".

---

## License

This project is licensed under the [MIT License](LICENSE). See the license file for details.

---

## Issues, Feature Requests or Support

Please use the Issue > New Issue button to submit issues, feature requests or support issues directly to me. You can also send an e-mail to akin.bicer@outlook.com.tr.
