# Video Conferencing App

## Overview

Welcome to the Video Conferencing App! This project showcases the development of a robust and feature-rich video conferencing application using cutting-edge web technologies. The app offers seamless user authentication, dynamic meeting management, real-time screen sharing, and much more.

## Features

- **User Authentication**: Secure account creation and sign-in with Clerk.
- **Video Meetings**: Easily initiate, join, and manage video meetings.
- **Screen Sharing**: Share your screen with participants during meetings.
- **Reactions**: Enhance interactions with emoji reactions.
- **Recording**: Record meetings for future reference.
- **Scheduling**: Schedule future meetings with ease.
- **History**: Access past meetings and recordings.
- **Join via Link**: Effortlessly join meetings using a shared link.

## Technologies Used

- **Next.js 14**: Powerful framework for building the application.
- **TypeScript**: Ensures code maintainability and scalability.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **Clerk**: Simplifies user authentication and management.
- **Stream**: Provides reliable video and audio functionalities.

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- Clerk API keys
- Stream API keys

### Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/niladri-1/Zoom-clone.git
    cd Zoom-clone
    ```

2. **Install dependencies**
    ```bash
    npm install
    # or
    yarn install
    ```

3. **Set up environment variables**

    Create a `.env.local` file in the root directory and add your Clerk and Stream API keys:
    ```env
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<YOUR_CLERK_PUBLIC_KEY>

    CLERK_SECRET_KEY=<YOUR_CLERK_SECRET_KEY>
    
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
    ```

### Running the App

1. **Start the development server**
    ```bash
    npm run dev
    # or
    yarn dev
    ```

2. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## Deployment

Deploy the app to Vercel by connecting your GitHub repository and following the Vercel deployment steps.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request with your changes. Make sure to follow the project's coding standards and guidelines.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [Clerk](https://clerk.dev/)
- [Stream](https://getstream.io/)
- [Tailwind CSS](https://tailwindcss.com/)

## Contact

For any questions or inquiries, feel free to reach out to the project maintainer:

- **Niladri Chatterjee**
  - [GitHub](https://github.com/niladri-1)
  - [LinkedIn](https://linkedin.com/in/niladri1)
  - [Email](mailto:code.niladri@gmail.com)

---

Enjoy building and enhancing your own video conferencing application with this project!