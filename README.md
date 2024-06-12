# StudentContactManager

A Google Apps Script project to manage students and their contacts in Google Sheets. This project includes functionality for logical deletion to ensure data integrity and prevent accidental loss of data. The script allows users to add, update, delete, and search for students and their associated contacts.

## Features

- **Manage Students**: Add, update, logically delete, and search for students.
- **Manage Contacts**: Add, update, logically delete, and search for contacts.
- **Logical Deletion**: Prevents accidental loss of data by marking records as deleted instead of physically removing them.
- **Google Sheets Integration**: Leverages Google Sheets as a backend database.

## Project Structure

- `Core.gs`: Contains core functions for managing students and contacts.
- `UI.gs`: Handles user interface interactions and dialog boxes.
- `Estudiantes.gs`: Manages student-specific functions.
- `Contactos.gs`: Manages contact-specific functions.
- `Estudiantes_Contactos.gs`: Manages relationships between students and contacts.
- `Sidebar.html`: The HTML file for the sidebar user interface.
- `FormularioAgregarEstudiante.html`: The HTML form for adding students.
- `FormularioActualizarEstudiante.html`: The HTML form for updating students.
- `FormularioAgregarContacto.html`: The HTML form for adding contacts.
- `FormularioBuscarContacto.html`: The HTML form for searching contacts.

## Getting Started

### Prerequisites

- A Google account
- Access to Google Sheets and Google Apps Script

### Installation

1. Open a new or existing Google Sheets document.
2. Go to `Extensions` > `Apps Script`.
3. Copy the contents of the `.gs` and `.html` files into your Google Apps Script project.
4. Save the project.

### Usage

1. **Initialize Sheets**: Ensure that the sheets for `Estudiantes`, `Contactos`, and `Estudiantes_Contactos` are present in your Google Sheets document.
2. **Add Students and Contacts**: Use the sidebar to add, update, and manage students and their contacts.
3. **Logical Deletion**: Mark records as deleted instead of removing them to maintain data integrity.

### Example

Here is an example of how to add a student and associate a contact:

1. Open the sidebar and select `Agregar Estudiante`.
2. Fill in the student details and submit.
3. Open the sidebar and select `Agregar Contacto`.
4. Fill in the contact details and provide the student's DNI.
5. Submit the contact form to associate it with the student.

### Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

### License

This project is licensed under the MIT License.

---

Feel free to customize this README to better fit your needs and include any additional information that might be useful for users of your project.
