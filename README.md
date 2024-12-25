# Blog System Project

## Overview

The **Blog System Project** is a modern web application designed to facilitate blogging with features like user authentication, CRUD operations, and search functionality. The project focuses on learning and implementing modern IT technologies and practices.

## Objectives

1. Gain hands-on experience with modern web technologies:
    - **Front-End**: React (TypeScript), Next.js, and TanStack (React Query).
    - **Back-End**: Next.js API routes with possible extensions.
    - **Database**: MySQL for structured data management.
    - **DevOps**: Docker for containerization and GitHub Actions for CI/CD.
2. Develop a responsive, scalable, and secure blog application.

## Features

### Functional Features

- **User Authentication**:
    - Sign-up, login, and logout functionality.
    - JWT-based token authentication.
    - Secure password storage (bcrypt).
- **Blog Management**:
    - Create, read, update, and delete (CRUD) blog posts.
    - Optional: User profile management.
- **Search Functionality**:
    - Basic filtering by author, tags, or date.
    - Full-text search (MySQL or Elasticsearch).

### Non-Functional Features

- Secure HTTPS in production.
- Scalability for handling moderate traffic.
- Efficient query handling with database indexing.

## Technology Stack

### Front-End

- **React**: For building the user interface.
- **Next.js**: For SSR, SSG, and routing.
- **TypeScript**: For type-safe development.

### Back-End

- **Next.js API Routes**: To handle server-side logic.
- Optional: Node.js with Express for more complex setups.

### Database

- **MySQL**: Primary data store with schema optimization for performance.

### DevOps

- **Docker**: To containerize the front end, back end, and database.
- **GitHub Actions**: For automated CI/CD pipelines.

## Development Setup

1. Clone the repository:
    
    ```
    git clone <repository-url>
    cd blog-system
    ```
    
2. Install dependencies for the front end:
    
    ```
    cd blog-frontend
    npm install
    ```
    
3. Start the application using Docker Compose:
    
    ```
    docker-compose up
    ```
    

## Project Structure

```
blog-system/
├── blog-frontend/
│   ├── components/    # React components
│   ├── pages/         # Next.js pages
│   ├── styles/        # CSS/SCSS files
│   ├── lib/           # Utility functions
│   ├── api/           # API functions
│   └── hooks/         # Custom React hooks
├── docker-compose.yml # Docker configuration
└── README.md          # Project documentation
```

## Roadmap

| Milestone | Description | Target Date |
| --- | --- | --- |
| M1 | Initial setup with Next.js and Docker | TBD |
| M2 | User authentication implementation | TBD |
| M3 | CRUD operations for blog posts | TBD |
| M4 | Search functionality implementation | TBD |
| M5 | CI/CD pipeline setup | TBD |
| M6 | Final deployment and testing | TBD |

## Contributing

1. Fork the repository.
2. Create a feature branch:
    
    ```
    git checkout -b feature/your-feature
    ```
    
3. Commit your changes:
    
    ```
    git commit -m "Add your message here"
    ```
    
4. Push to the branch:
    
    ```
    git push origin feature/your-feature
    ```
    
5. Open a pull request.

## License

This project is licensed under the MIT License.

---

Feel free to explore and contribute to this exciting project!