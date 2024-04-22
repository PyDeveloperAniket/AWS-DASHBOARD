# aws-dashboard
# DNS Manager

Welcome to the DNS Manager! This application is designed to provide a seamless experience for managing DNS records with the following features:

- **Standardized Stack**: Built on the MERN (MongoDB, Express.js, React.js, Node.js) stack for frontend, backend, and infrastructure layers, ensuring robustness and scalability.

- **AWS Route 53 Integration**: Seamlessly integrates with AWS Route 53 for efficient management of DNS records.

- **User-Friendly Dashboard**: Offers an intuitive dashboard for easy uploading and viewing of domains and DNS records.

- **Support for Various Record Types**: Supports a wide range of DNS record types including A, AAAA, CNAME, MX, NS, PTR, SOA, SRV, TXT, and DNSSEC, ensuring compatibility with diverse use cases.

- **Forms and Modals**: Provides forms and modals for effortless addition, editing, and deletion of DNS record entries, enhancing user convenience.

- **Filters and Search Options**: Incorporates filters and search options for effortless navigation through bulk data, saving time and effort.

- **Graphical Charts and Metrics**: Presents graphical charts and metrics to visualize domain and record type distribution, enabling users to gain insights at a glance.

- **Bulk Uploads**: Integrates CSV or JSON bulk uploads for domain and records data, facilitating efficient data management.

- **Backend API Endpoints**: Offers backend API endpoints for CRUD operations on DNS records, ensuring flexibility and customization.

- **Secure Authentication and Authorization**: Implements secure user authentication and authorization mechanisms, safeguarding sensitive data and ensuring data integrity.

## Getting Started


1. **Clone the Repository**: Clone this repository to your local machine.

    `git clone <repository_url>`


2. **Install Dependencies**: Navigate to the project directory and install dependencies for both frontend and backend.

    - cd dns-manager
    - cd client && npm install
    - cd ..
    - cd server && npm install


3. **Set Up Environment Variables**: Create a `.env` file in the `server` directory and configure environment variables including MongoDB connection URI, AWS credentials, and JWT secret.


- PORT=3001
- MONGODB_URI=<your_mongodb_uri>
- AWS_ACCESS_KEY_ID=<your_aws_access_key_id>
- AWS_SECRET_ACCESS_KEY=<your_aws_secret_access_key>
- JWT_SECRET=<your_jwt_secret>


4. **Start the Application**: Run the frontend and backend servers.

- cd client && npm start
- cd ..
- cd server && npm start



5. **Access the Application**: Open your browser and navigate to `http://localhost:3000` to access the DNS Manager application.

## Usage

Once the application is running, you can:

- Log in using your credentials or sign up if you are a new user.
- Navigate through the user-friendly dashboard to manage domains and DNS records.
- Add, edit, or delete DNS record entries using forms and modals.
- Utilize filters and search options for easy navigation through bulk data.
- Visualize domain and record type distribution through graphical charts and metrics.
- Upload domain and records data in bulk using CSV or JSON files.
- Perform CRUD operations on DNS records using backend API endpoints.

## Support

For any issues or inquiries, please contact [support@example.com](mailto:pydeveloperaniket2001@gmail.com).

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.


---

Thank you for choosing the DNS Manager! We hope it simplifies your DNS management tasks and enhances your experience. If you have any feedback or suggestions, feel free to reach out. Happy managing! 🚀
#
