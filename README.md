
## Purpose of the Project

The purpose of **Writtenby** is to create a space where users can read and explore fictional stories, whether it's fantasy, romance, sci-fi, mystery, or any genre that excites the imagination. The website also provides a platform for writers to upload their stories, engage with readers, and build their presence within the literary community.

Whether you're an avid reader or an aspiring author, **Writtenby** offers an easy-to-use and visually appealing platform to immerse yourself in the world of fiction.

## Features

- **Story Library**: A comprehensive collection of fictional stories in various genres, with a user-friendly interface to search, filter, and read.
- **User Profiles**: Both readers and writers can create personalized profiles to manage their library, track reading progress, and follow their favorite authors.
- **Story Submission**: Writers can submit their stories, upload e-books, and edit their content directly through their profiles.
- **Rating & Reviews**: Readers can rate stories and leave reviews to share their opinions with others.
- **Interactive Reading Experience**: Features like bookmarks, night mode, font customization, and auto-scroll for an enhanced reading experience.
- **Community Engagement**: Comment sections on each story where readers can interact with writers and other readers.
- **Genres & Categories**: Filter stories based on popular genres and categories such as fiction, mystery, romance, fantasy, and more.
- **Search & Recommendations**: Intelligent search options and story recommendations based on user preferences and past activity.

## Installation and Setup

Follow the steps below to set up the **Writtenby** project locally on your machine.

### Prerequisites

Before you begin, ensure that you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en/) (with npm)
- [MongoDB](https://www.mongodb.com/try/download/community) (for database)
- A code editor (e.g., [VS Code](https://code.visualstudio.com/))

### 1. Clone the Repository

Begin by cloning the **Writtenby** repository from GitHub:

```bash
git clone https://github.com/your-username/writtenby.git
```

### 2. Install Dependencies

Navigate into the project directory:

```bash
cd writtenby
```

Then, install the required dependencies using npm:

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the root directory of the project and configure the following variables:

```
MONGODB_URI=mongodb://localhost:27017/writtenby
PORT=5000
SECRET_KEY=your-secret-key
```

### 4. Run the Development Server

To start the development server, use the following command:

```bash
npm start
```

This will start the application on `http://localhost:5000`.

### 5. Access the Website

Open a web browser and go to `http://localhost:5000` to start using **Writtenby** locally.

### 6. Database Setup

To set up MongoDB for the application:

1. Install MongoDB on your machine or use a MongoDB cloud service (e.g., MongoDB Atlas).
2. Ensure that your MongoDB server is running.
3. The application will automatically connect to the database specified in the `.env` file.

### 7. Additional Configuration (Optional)

You can configure additional features like email notifications, third-party integrations, or cloud storage for user-uploaded content by editing the relevant files in the `config/` directory.

## Contributing

We welcome contributions to **Writtenby**! If you want to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.
