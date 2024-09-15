# Ola Energy CMMS Application

This is a custom-built **Computerized Maintenance Management System (CMMS)** developed using **PowerApps** for **Ola Energy**. The application streamlines the management of corrective maintenance tasks, inventory control, and staff management. It offers a user-friendly interface for both administrators and users, with role-based access control to ensure appropriate permissions for each function.

## Features

### General Features
- **User and Admin Access**: Separate login screens for users and administrators.
- **Role-based Navigation**: Based on the user's role (e.g., storekeeper), the application dynamically redirects to the appropriate screens and functionalities.

### Admin Features
- **Profile Management**: Add, modify, or delete user profiles.
- **Function Management**: Manage roles and permissions for users and staff.
- **Staff Management**: Handle staff records, including adding new staff, modifying existing records, or deleting staff members.
- **Hourly Rate**: Assign hourly rates to staff, useful for calculating labor costs in interventions.

### Storekeeper Features
- **Inventory Management**: 
  - Monthly physical inventory tracking for spare parts.
  - Add or remove spare parts and equipment.
- **Movement Orders**: Handle entry/exit of spare parts via movement order forms.
- **Intervention Validation**: Validate or modify corrective interventions submitted by other users.

### User Features
- **Corrective and Preventive Work Reports**: Submit detailed intervention reports, including start and end times, human resources used, and equipment and spare parts involved.
- **Equipment Management**: Manage the list of equipment involved in maintenance operations.

## Screens Overview

- **Welcome Screen**: Provides access to the application for both users and administrators.
- **Admin Login Screen**: Login form for administrators (username and password required).
- **User Login Screen**: Login form for users (email and password required), with dynamic redirection based on the user’s function.
- **Admin Activities Screen**: Offers multiple management options, such as profile, staff, and function management.
- **User Activities Screen**: Allows users to access corrective and preventive work report forms and manage the equipment list.
- **Storekeeper Screens**: 
  - Inventory and spare parts management.
  - Validation and modification of spare parts used in interventions.
  - Movement order management (entry/exit of spare parts).
- **Reports Screen**: For users to submit new corrective interventions with details about human resources, equipment, and spare parts used.

## Setup and Installation

1. **PowerApps Setup**: Ensure you have access to PowerApps with appropriate permissions to modify and run the application.
2. **Excel Database**: The application uses Excel as a backend database for storing staff, equipment, and intervention data. Ensure the connected Excel files are properly set up with tables and fields corresponding to the app's requirements.
