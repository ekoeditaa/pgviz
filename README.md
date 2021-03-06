# Postgres Query Execution Plan Visualizer

## Getting Started
After cloning the project, execute the following commands once you're in the project root.
1. Create virtual environment
    ```
    python3 -m venv venv
    ```
2. Activate virtual environment
   ```
   source venv/bin/activate
   ```
   Once you see (venv) beside the terminal, you have succesfully activated the virtual environment.
   
3. Install requirements for the project
    ```
    pip install -r requirements.txt
    ```

4. Enter your local database credentials on the file `db_credentials.py`. This only works for PostgresQL(version 10.5) database!

5. Run `python server.py`