# File Sharing Platform

File Sharing Platform is a simple file-sharing application built using Node.js. It allows users to upload files and generate shareable links for easy file distribution. The link expires after 24 hours for security purposes. Users can also share the download link via email.

## Features

- **Drag-n-drop or upload**: Upload your file directly by dragging it into the browser window or by selecting it through a file upload interface.
- **Shareable links**: Get a link that can be shared with anyone for easy download.
- **Email sharing**: Send the file's download link directly to an email address.
- **File expiration**: Files and their corresponding links expire after 24 hours.
  
[Try it here](https://fileshare.onrender.com)

## Limitations

- **Maximum file size**: 100 MB
- **Single file upload**: Only one file can be uploaded at a time.

## Tech Stack

- **Node.js** with **Express** as the backend framework.
- **MongoDB** for storing file metadata and managing expiration.
- **Nodemailer** for email functionality.
- **Multer** for file uploads.
- **EJS** for rendering views.

## Getting Started

Follow the instructions below to set up the project on your local machine.

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or cloud instance)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/vaishnavi-mapari/CodeClauseInternship_File-Sharing-Platform.git
    cd CodeClauseInternship_File-Sharing-Platform
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and provide the following environment variables:

    ```
    PORT=3000
    MONGO_URI=<your_mongo_connection_string>
    EMAIL_HOST=<your_email_host>
    EMAIL_PORT=<your_email_port>
    EMAIL_USER=<your_email_username>
    EMAIL_PASS=<your_email_password>
    ```

4. Start the development server:

    ```bash
    npm start
    ```

5. Visit `http://localhost:3000` in your browser to use the application.

### Usage

1. Drag-and-drop or upload a file using the web interface.
2. A shareable download link will be generated, which expires after 24 hours.
3. Optionally, share the link via email directly from the application.

## Contributing

Feel free to open issues or submit pull requests if you want to contribute to the project. Any contributions, bug reports, or feature requests are welcome!

