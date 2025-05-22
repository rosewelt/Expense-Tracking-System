# Expense Management System

This project is an expense management system featuring a Streamlit-based frontend and a FastAPI-powered backend server.


## Project Structure

- **frontend/**: Source code for the Streamlit-based user interface.
- **backend/**: CCode for the FastAPI backend server handling API requests.
- **tests/**: Contains the test cases for both the frontend and backend components.
- **requirements.txt**: Specifies all Python dependencies needed to run the project.
- **README.md**: Contains project overview, setup instructions, and usage guidelines.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/rosewelt/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
