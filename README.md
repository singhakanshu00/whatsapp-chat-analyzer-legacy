# whatsapp-chat-analyzer-legacy

## Steps for local development

### Prerequisites:
- Git installed and configured in your system
- Python installed in your system

### Steps:
- Create a virtual environment

  ```python -m venv venv```

- Activate virtual environment

  * #### Windows:

    ```venv\Scripts\activate.bat```

  * #### Mac:

    ```source venv/bin/activate```

- Install python modules:

  ```pip install -r requirements.txt```

- Run the app in the localhost:
  
  ```streamlit run app.py```

- Deployment:

  * Create a branch from main:

    ```git checkout -b <your-branch>```

   Make the changes and create a pull request.

   After the PR is approved and merge to main it will deploy to production