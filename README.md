# PDF_RENAME_TOOL

Here’s a basic README template for your PDF renaming tool project. You can adapt this to include any additional details or instructions as necessary:

---

# PDF Rename Tool

This PDF Rename Tool is a web application that allows users to rename a batch of PDF files based on names provided in an Excel sheet. This is useful for bulk renaming tasks, such as renaming certificates, invoices, or any other set of PDF documents according to a pre-defined list of names.

## Features

- Upload an Excel file containing the list of desired names
- Upload a folder of PDF files to be renamed
- Automatic renaming of PDFs based on the list in the Excel file
- Download the renamed PDF files

## Installation

### Prerequisites

- Python 3.9+
- [Flask](https://flask.palletsprojects.com/)
- [Pandas](https://pandas.pydata.org/)
- [openpyxl](https://openpyxl.readthedocs.io/)

### Setup

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/pdf-rename-tool.git
    cd pdf-rename-tool
    ```

2. Set up a virtual environment:

    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Flask Application**:
   
    ```bash
    python app.py
    ```

   The application should now be running on `http://127.0.0.1:5000`.

2. **Using the Web Interface**:
   - Open your browser and navigate to `http://127.0.0.1:5000`.
   - Upload your Excel file containing the list of new file names.
   - Upload a folder containing the PDF files to be renamed.
   - Download the renamed files.

## File Structure

- `app.py`: Main Flask application.
- `requirements.txt`: Contains all dependencies.
- `README.md`: Documentation for the project.

## Dependencies

- **Flask**: For building the web interface.
- **pandas**: To handle data from the Excel file.
- **openpyxl**: For reading Excel files (.xlsx).

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This should give users clear instructions on setting up and using your project! Let me know if you need help with any additional sections.
