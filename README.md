# Bulky Book

Bulky Book is a simple CRUD (Create, Read, Update, Delete) application developed using ASP.NET and C#. It demonstrates basic operations with a focus on managing categories. The project provides an intuitive interface for adding, viewing, updating, and deleting categories in a table.

## Features

- **Category Management**: Add, view, update, and delete categories.
- **Responsive UI**: A clean and user-friendly interface for managing categories.
- **Validation**: Includes server-side validation for form inputs.
- **ASP.NET MVC Framework**: Built using the Model-View-Controller (MVC) design pattern.
- **Entity Framework**: Utilized for database interactions.
- **Bootstrap Styling**: Responsive design using Bootstrap.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)

## Project Overview

The **Bulky Book** application focuses on category management through a CRUD interface. Users can:
1. View a list of all categories.
2. Add new categories.
3. Edit existing categories.
4. Delete unwanted categories.

### Key Components
- **Index View**: Displays a table listing all categories with their names and display orders.
- **Create View**: A form for adding new categories with validation.
- **Edit View**: A form pre-filled with existing data for editing categories.
- **Delete Action**: Removes categories from the database.

## Technologies Used

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: ASP.NET MVC Framework, C#
- **Database**: Entity Framework (Code First or Database First)
- **Tools**: Visual Studio, SQL Server

## Setup Instructions

Follow these steps to set up and run the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ThasnimaShereef/BulkyBook.git
   cd BulkyBook
2. **Open in Visual Studio**:
   
   Open the solution file (BulkyBook.sln) in Visual Studio.
3. **Database Configuration**:

   Update the connection string in the appsettings.json file to point to your SQL Server instance.
   Run the migrations to set up the database:
   ```bash
   Update-Database
4. **Run the Application**:
   
   Press F5 or click on the "Run" button in Visual Studio.

 ## Usage
1. Navigate to the Categories section.
2. Perform the desired CRUD operations:
 - **Create**: Click on "Create New Category" to add a category.
 - **Read**: View the list of categories on the main page.
 - **Update**: Click on an edit button for a category to modify its details.
 - **Delete**: Remove a category from the list.
  
## Contributing
Contributions are welcome! If you'd like to improve this project:
1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes and push the branch.
4. Submit a pull request.
