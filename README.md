# Book Review Application

## Overview
The **Book Review Application** is a platform that allows users to review and rate books. Users can browse books, read reviews, and contribute their own opinions.

## Features
- User authentication and profile management
- Add, edit, and delete book reviews
- View ratings and reviews from other users
- Search and filter books based on title, author, or genre
- Responsive UI for seamless experience across devices

## Technologies Used
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Token)

## Installation & Setup
### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Clone the Repository
```bash
git clone https://github.com/Ayussh-Raj/Book-review-application.git
cd Book-review-application
```

### Backend Setup
1. Navigate to the backend folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file and add the following:
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=5000
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend server:
   ```bash
   npm run dev
   ```

## Usage
1. Register or log in to the application.
2. Browse books and read existing reviews.
3. Add your own book reviews and ratings.
4. Manage your profile and reviews.

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is open-source and available under the [MIT License](LICENSE).

