# Inventory Tracker Project

This project is an inventory management system designed to manage inventory for multiple stores using a reusable class structure. It efficiently handles inventory operations such as adding, editing, removing, and viewing products while ensuring smooth error handling and data persistence.

## Features

- **Reusable Class for Multiple Stores**  
  Designed with a class structure that makes it easy to manage multiple stores using the same framework.

- **Separation of Concerns**  
  - **Backend**: Handles business logic, such as inventory operations and error handling.
  - **User Interface**: The main menu handles input/output and presents data to the user.

- **Persistent Data Storage**  
  - Automatically saves all inventory data to a JSON file stored on Google Drive.
  - Pulls inventory data from the JSON file whenever the program is reopened, ensuring no data is lost.

- **Error Handling for Smooth Operation**  
  - Utilizes `try-except` blocks to handle value errors (e.g., invalid input types) gracefully, ensuring the program doesn’t crash during execution.

- **Proper Data Types for Manipulation**  
  - Prices are stored as `float` and quantities as `int` instead of strings, making it easier to perform numerical operations like sorting or analytics in the future.

## Skills and Concepts Demonstrated

- **Python Programming** with **Object-Oriented Programming (OOP)**
- **File Handling** using **JSON** for data persistence
- **Error Handling** with **`try-except` blocks**
- **Separation of Concerns** in program design
- **Integration with Google Drive** for seamless file storage

## How to Run the Project

You can run this project either **locally** on your machine or using **Google Colab**.

### Run Locally

If you prefer to run the project on your local machine:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/mjassiri/inventory-tracker.git
Navigate to the project directory:

cd inventory-tracker
Install Python 3.x if you don’t have it installed. You can download it from python.org.

Run the script:

python inventory_manager.py

### Run on Google Colab

You can also run this project in Google Colab without setting up a local environment.

[**Click here to open the project in Google Colab**](https://colab.research.google.com/drive/1Z2fxMuCsCrOeLajguv2kO_Ujo34-y4dn)


## Example Output

Here’s a sample of how the program operates:

### Adding a Product:

Enter Product ID: 101

Enter Product Name: Laptop

Enter Price: 1200.99

Enter Quantity: 5

Product successfully added!

JSON File Example:

{
    "101": {
        "item": "Laptop",
        "price": 1200.99,
        "quantity": 5
    }
}

### About Me

I’m an aspiring data scientist with a strong foundation in Python programming and a passion for building impactful solutions. This project demonstrates my ability to create data-driven applications and manage structured data.

### License

This project is open-source under the MIT License.
