<h1 align="center">Draco Panel</h1>

## Overview

Draco Panel is a powerful and intuitive server management solution designed to streamline your workflow. With a focus on ease of use and robust functionality, Draco Panel empowers you to efficiently manage your servers and applications.

## Features

*   **Intuitive Interface:** A clean and user-friendly interface for effortless server management.
*   **Easy Installation:** Get up and running quickly with our straightforward installation process.
*   **Robust Functionality:** Manage your servers and applications with ease.
*   **Community Driven:** We welcome contributions from the community to enhance Draco Panel.

## Installation

Get Draco Panel up and running in just a few simple steps:

1.  **Clone or Download:**
    ```bash
    git clone https://github.com/dragonlabsdev/v3panel
    ```

2.  **Install Node.js:** Ensure Node.js is installed on your system. Use the following commands:
    ```bash
    curl -sL https://deb.nodesource.com/setup_23.x | sudo bash -
    apt-get install nodejs git
    ```

3.  **Navigate to Panel Directory:**
    ```bash
    cd v3panel
    ```

4.  **Prepare Panel:**
    ```bash
    apt install zip -y && unzip panel.zip && cd panel
    ```

5.  **Install Dependencies & Configure:**
    ```bash
    npm install && npm run seed && npm run createUser
    ```

6.  **Launch Draco Panel:**
    ```bash
    node .  # or use pm2 for persistent operation
    ```

    *Tip: Use PM2 (`npm install -g pm2`) to keep Draco Panel running smoothly in the background!*

## Contributing

We welcome contributions from the community! If you have ideas for improving Draco Panel, please submit a pull request. Your contributions help make Draco Panel even better.

## License

(c) 2025 Hopingboyz. This software is licensed under the MIT License.

Made with ❤️ by Hopingboyz
