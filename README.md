# ScholarshipWorld

ScholarshipWorld is a user-friendly platform that enables students to manage and track applications for various scholarships using their Aadhaar numbers or Student IDs. The platform provides a seamless experience for students to apply for scholarships, track the status of their applications, and manage their profiles. Admin officials can efficiently view, process, and manage pending applications.

## Features

- **Application Management:**

  - Students can easily apply for scholarships by providing their details once. Subsequent applications can be filled within seconds.
  - Students can view all their applied applications, including detailed information and current application status.
  - Application status tracking is available, including reasons for rejection provided by administrators.
  - Application status filter allows students to find specific applications based on their status (e.g., Pending, Approved, Rejected). The status filter is tracked for easier navigation between the current and previous pages with the applied filters.
  - Prevention of duplicate applications ensures students can only submit one application per scholarship.

- **Scholarship Search:**

  - Students can search for available scholarships based on filters to quickly find the most relevant options.

- **Profile Management:**

  - Students can change their profile photo and view the number of applications they have submitted.
  - The profile page displays the number of applications based on their status (e.g., Pending, Approved, Rejected).
  - Students can view and edit their details from their profile page, enabling easy application to scholarships.

- **Authentication & Authorization:**

  - **_Passport.js_** is used for authentication, ensuring secure login and user management.
  - Role-based authorization security has been set up to restrict access based on user roles (Student, Admin). Only authorized users can access specific functionalities and data.

- **Cloud Storage:**

  - Integration with Cloudinary for storing profile photos and supporting documents, providing easier access and management.

- **Admin Features:**
  - Administrators can view and process pending applications efficiently, with the ability to provide rejection reasons directly to students.

## Technologies Used

- **Frontend:** React.js, TypeScript, Material UI, React-Redux Toolkit,
<p align="center">
  <img style="margin:1rem;" src="https://img.icons8.com/color/48/000000/react-native.png" alt="React.js" />
  <img style="margin:1rem;" src="https://img.icons8.com/color/48/000000/typescript.png" alt="TypeScript" />
  <img style="margin:1rem;" src="https://img.icons8.com/color/48/000000/material-ui.png" alt="Material UI" />
  <img style="margin:1rem;" src="https://img.icons8.com/color/48/000000/redux.png" alt="Redux" />
</p>

- **Backend:** Node.js, Express.js
<p align="center">
  <img src="https://img.icons8.com/color/48/000000/nodejs.png" alt="Node.js" />
  <img src="https://img.icons8.com/color/48/000000/express.png" alt="Express.js" />
</p>

- **Database:** MongoDB
<p align="center">
  <img src="https://img.icons8.com/color/48/000000/mongodb.png" alt="MongoDB" />
</p>

- **Cloud Storage:** Cloudinary

- **Architecture:** MVC (Model-View-Controller)


## Installation

1. ### Clone the repository:

   `git clone https://github.com/Adhish1612Acharya/ScholarshipWorld.git`

2. ### Open Two Terminals :

   - **First Terminal :**
     `cd frontend`

     `npm install`

     `npm run dev`

   - **Second Terminal :**
     `cd backend`

     `npm install`

     `npm start`

3. ### .env file :

   - Create a Cloudinary account and add the required credentials for storing files in Cloudinary.
   - Add the MongoDB database URL.

