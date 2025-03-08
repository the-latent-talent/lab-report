**Lab Report: DevHive Web Application**

**1. Introduction**

DevHive is a web application designed to facilitate the listing of development projects and services, drawing inspiration from platforms like Fiverr and Upwork. Built on the Laravel PHP framework, it provides a robust platform for developers to showcase their skills and services to potential clients. citeturn0search0

**2. Objectives**

- Implement user authentication and authorization mechanisms.
- Enable users to create and manage service listings.
- Utilize MySQL for database management.
- Incorporate file storage and access functionalities.
- Develop an admin panel using PHP Filament.

**3. Methodology**

**3.1. User Authentication and Authorization**

Laravel's built-in authentication system was employed to manage user registration and login processes. Role-based access control was implemented to distinguish between administrators and regular users, ensuring appropriate access levels.

**3.2. Listing Management**

Authenticated users can create and manage listings for their development services. The application supports file uploads, allowing users to attach relevant project files and documents to their listings.

**3.3. Database Management**

MySQL was chosen as the database management system. Laravel's migration and seeder features were utilized to set up and manage the database schema efficiently.

**3.4. File Storage and Access**

Laravel's storage system was used to handle file uploads. A symbolic link was created to make uploaded files publicly accessible, facilitating seamless access to resources.

**3.5. Admin Panel Development**

An admin panel was developed using PHP Filament, providing administrators with a user-friendly interface to manage users, listings, and other critical aspects of the application.

**4. Results**

The implementation of DevHive resulted in a functional web application with the following features:

- **User Authentication and Authorization:** Secure login and registration processes with role-based access control.
- **Listing Management:** Users can create, edit, and delete service listings, with support for file attachments.
- **Database Management:** Efficient data storage and retrieval using MySQL, facilitated by Laravel's migration and seeder tools.
- **File Storage and Access:** Reliable file upload and access system, ensuring users can attach and retrieve necessary documents.
- **Admin Panel:** A comprehensive admin interface for managing application content and users.

**5. Conclusion**

DevHive successfully provides a platform for developers to list and manage their services, inspired by established platforms like Fiverr and Upwork. The use of Laravel and PHP Filament contributed to a robust and scalable application architecture. Future enhancements could include integrating payment gateways, implementing advanced search functionalities, and incorporating user feedback mechanisms to further enrich the platform's capabilities.

**6. References**

- citeturn0search0

*Note: This lab report is based on the DevHive project as described in the provided GitHub repository.* 
