This project is a full-stack multi-tenant web application designed to support multiple organizations (tenants) within a single system while ensuring secure data isolation between them.

Each user belongs to a specific organization, and all data—such as users, resources, and activities—is strictly scoped to that organization using a unique tenant ID. This ensures that users can only access and interact with data from their own tenant, maintaining privacy and security.

The application includes a secure authentication system using JWT-based login and signup, along with role-based access control. Admin users can manage other users within their organization, while regular users have limited permissions.

The backend is built using Node.js and Express, with MongoDB as the database to efficiently manage tenant-based data. Middleware is implemented to enforce tenant isolation and protect routes.

The frontend provides a responsive dashboard interface where users can view and manage data relevant only to their organization, creating a seamless and personalized experience.

Overall, this project demonstrates key SaaS concepts such as:

Multi-tenancy architecture
Secure authentication and authorization
Scalable backend design
Data isolation and access control

It is designed to be scalable, modular, and deployment-ready, making it suitable for real-world SaaS applications.
