Below is the documentation based on your recent full-stack project as per the task requirements:

---

### Full-Stack Project: **Building Management System (Single Building)**

#### Objective:
The project involves developing a robust Building Management System (BMS) that caters to both user and admin functionalities. The goal is to create a responsive platform where users can view apartments, make agreements, and manage rentals, while admins can handle building operations such as announcements, managing members, and handling agreement requests.

---

#### 1. **Backend: Structure, Database Design, and Server-Side Logic**

- **Backend Technologies**: 
  - **Node.js**: The primary runtime environment for the server.
  - **Express.js**: Used as the web framework for building the API.
  - **MongoDB**: A NoSQL database to store user and apartment data.
  - **Mongoose**: An Object Data Modeling (ODM) library for MongoDB to simplify schema design.
  - **JWT**: JSON Web Token for user authentication and session management.
  - **Firebase Admin SDK**: For server-side Firebase operations.

- **Database Design**:
  - **User Collection**: Stores user profiles, roles, and authentication information.
  - **Apartment Collection**: Contains details about apartments, including floor, block, rent, and availability.
  - **Agreement Collection**: Manages agreement data, with fields like username, apartment details, rent, and agreement status.

- **Server-Side Logic**:
  - **Authentication and Authorization**: Implemented using JWT for securing private routes.
  - **CRUD Operations**: Server handles creating, reading, updating, and deleting apartments, agreements, and announcements.
  - **Payment Handling**: Stores payment history and integrates coupon logic to reduce rent based on valid codes.

---

#### 2. **Frontend: Technologies, UI Design, and User Experience**

- **Frontend Technologies**:
  - **React.js**: For building a dynamic and responsive user interface.
  - **Tailwind CSS**: To style components and maintain a mobile-first responsive design.
  - **TanStack Query**: Used for fetching data (GET requests) from the API.
  - **Firebase Authentication**: Handles user sign-up and login.

- **UI Design**:
  - **Home Page**: Includes a navbar with a dynamic login/profile section, a banner with images of the building, and sections for building information, coupons, and apartment locations.
  - **Apartment Page**: Displays apartments in a paginated view, with buttons for users to apply for agreements.
  - **Dashboard**:
    - **User Dashboard**: Contains profile information, announcements, and agreement details.
    - **Admin Dashboard**: Features routes for managing members, announcements, and agreement requests.

- **User Experience**:
  - **Responsive Design**: The platform is fully responsive for mobile, tablet, and desktop views.
  - **Notifications**: Toast notifications are used for CRUD operations and successful login/sign-ups.
  - **Pagination**: Applied to the apartment listing with six apartments per page.
  - **Payment Integration**: Users can apply coupons during payments and view payment history with search functionality.

---

#### 3. **Hosting: Environment and Deployment**

- **Hosting Platform**: 
  - The application is hosted on **Firebase Hosting** for fast and reliable delivery.
  - Firebase also handles static asset delivery and user authentication.

- **Deployment Process**:
  - **Frontend**: The React app is deployed using Firebase's CLI tool. The live site can be accessed via the link below.
  - **Backend**: Hosted on a cloud platform (e.g., Heroku or AWS), connected to the MongoDB Atlas for database management.
  - **Continuous Deployment**: Integrated with GitHub for automatic deployment of new changes.

---

#### 4. **Project Link**

Live Project Link: [Cozynest](https://cozynest-cbb8e.web.app)

---

This documentation outlines the backend structure, frontend technologies, hosting, and deployment process, ensuring the project meets the functional and non-functional requirements stated.
