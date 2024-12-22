# Python Development Environment

This project provides a simple setup for a Python development environment, with or without using Dev Containers. It allows developers to work in a consistent environment and includes basic tools for coding, formatting, and testing.

## How to Run the Project?

### Option 1: Using Dev Containers
1. Ensure you have `Docker` and `Visual Studio Code` installed.
2. Clone the repository and open it in Visual Studio Code.
3. When prompted, select `Reopen in Container`. This will automatically set up the environment based on the devcontainer.json file.
4. Run the application:
   ```python
   python3 main.py
   ```
5. Run tests:
   ```python
   python3 -m pytest
   ```

### Option 2: Without Dev Containers
1. Clone the repository to your local machine.
2. Create a virtual environment and activate it.
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. Install the dependencies:
   ```python
   pip install -r requirements-dev.txt
   ```
4. Run the application:
   ```python
   python3 main.py
   ```
5. Run tests:
   ```python
   python3 -m pytest
   ```

## How to Customize?

- **Dependencies**: Add or modify dependencies in `requirements-dev.txt`.
- **Dev Container Configuration**: Update the `devcontainer.json` file to include additional tools, settings, or extensions.
- **Main File**: Customize the `main.py` file to include additional functionality or modify the existing add_numbers function as per your project requirements.
- Testing: Add more test cases in the `tests` directory to cover new functionality.

  
