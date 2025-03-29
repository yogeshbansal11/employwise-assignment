# User Management System

A React-based user management system that allows you to view, edit, and delete users. The application uses the ReqRes API for demonstration purposes.

## Features

- User authentication (login)
- View list of users with pagination
- Search users by name or email
- Edit user details
- Delete users
- Responsive design
- Toast notifications for feedback

## Tech Stack

- React
- React Router for navigation
- Axios for API requests
- Tailwind CSS for styling
- Lucide React for icons
- React Hot Toast for notifications

## Prerequisites

- npm or yarn

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yogeshbansal11/employwise-assignment.git
cd employwise-assignment
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Usage

### Login
- Use the following credentials to log in:
  - Email: eve.holt@reqres.in
  - Password: cityslicka

### Features
- **User List**: View all users with their details
- **Search**: Use the search bar to filter users by name or email
- **Pagination**: Navigate through multiple pages of users
- **Edit User**: Click the pencil icon to edit user details
- **Delete User**: Click the trash icon to remove a user
- **Logout**: Click the logout button to end your session

## API Integration

This project uses the [ReqRes API](https://reqres.in/) for demonstration purposes. The following endpoints are utilized:

- `POST /api/login` - User authentication
- `GET /api/users` - Fetch users list
- `PUT /api/users/:id` - Update user details
- `DELETE /api/users/:id` - Delete user

## Live Demo

The application is deployed and can be accessed at: [https://employwise-assignment-phi.vercel.app/login](https://employwise-assignment-phi.vercel.app/login)

## Project Structure

```
src/
├── components/
│   ├── Login.jsx       # Login page component
│   ├── UserList.jsx    # User list and management component
│   └── EditUser.jsx    # User edit form component
├── App.jsx             # Main application component
└── main.jsx           # Application entry point
```

## License

This project is open source and available under the [MIT License](LICENSE).
