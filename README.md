# Images Space: AI Image Generator

## Overview

Images Space is a state-of-the-art AI image generator platform designed to help users effortlessly create stunning, high-quality images. Powered by advanced AI technology, Images Space offers a straightforward, user-friendly interface that allows you to generate personalized images tailored to your specifications. Whether you are an artist, designer, marketer, or simply looking for visually striking content, Images Space provides a seamless and efficient experience, enabling you to bring your creative ideas to life.

## Features

- **Generate Images:** Create images according to your desired style and specifications.
- **Share Images:** Share your generated images on the website.
- **Download Images:** Download the images you have created directly from the website.
- **Responsive Design:** Fully responsive, ensuring functionality on all devices.
- **Enhanced User Experience:** Provides a seamless and intuitive interface, focusing on usability.

## Technology Stack

- **MERN Stack:** The application is built using the powerful MERN stack, comprising MongoDB, Express.js, React.js, and Node.js, for a comprehensive, end-to-end development experience.
- **Tailwind CSS:** The most popular CSS framework today, Tailwind offers utility-first styling for quick and efficient design implementation.
- **OpenAI's DALL-E Model:** Utilizes OpenAI's advanced deep learning model to generate images from text input, bringing your visions to life.
- **Cloudinary:** A cloud-based image storage and management service that offers robust and efficient image hosting capabilities.

# Images Space Setup and Installation Guide

To get Images Space running locally on your machine, follow these steps:

1. **Clone the repository:** Use the `git clone` command followed by the repository URL. After cloning, navigate into the project directory using the `cd` command.

    ```bash
    git clone https://github.com/chouaib-dj/images-space.git
    cd images-space
    ```

2. **Install the dependencies:** Run the `pnpm install` command to install all required dependencies.

    ```bash
    pnpm install
    ```

3. **Set up your environment variables:** Create a `.env` file in the server directory. Inside this file, include the following environment variables:

    ```plaintext
    MONGODB_URL=your-mongodb-url
    OPENAI_API_KEY=your-openai-api-key
    CLOUDINARY_API_SECRET=your-cloudinary-api-secret
    CLOUDINARY_API_KEY=your-cloudinary-api-key
    CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
    ```

4. **Set up MongoDB database:** Ensure MongoDB is installed on your machine and running. 

5. **Run the application:** Use the `pnpm dev` command to start the application. Once running, you can access the application by visiting `http://localhost:5173` in your web browser.

    ```bash
    pnpm dev
    ```

Following these steps should get Images Space up and running locally on your machine using pnpm.

## License

Images Space is open-sourced under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or need further assistance with Images Space, please don't hesitate to reach out via email: [djaidri.chouaib.24@gmail.com](mailto:djaidri.chouaib.24@gmail.com).
