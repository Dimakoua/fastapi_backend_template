## 🛠️ Installation  

1️⃣ **Clone the repository**  
```sh
git clone git@github.com:Dimakoua/fastapi_backend_template.git
cd fastapi_backend_template
```

2️⃣ **Create a virtual environment**  
```sh
python -m venv .venv
```

3️⃣ **Activate the virtual environment**  
- **Linux/macOS:**  
  ```sh
  source .venv/bin/activate
  ```
- **Windows (PowerShell):**  
  ```sh
  .venv\Scripts\Activate
  ```

4️⃣ **Install dependencies**  
```sh
pip install -r requirements.txt
```

---

## ▶️ Running the Server  

Once dependencies are installed, start the backend server:  

```sh
source .venv/bin/activate
uvicorn main:app --reload
deactivate
```

> **Note:** The \`--reload\` flag enables auto-reloading for development.

---

## 🧪 Running Tests  

Run the test suite in a **test environment**:  

```sh
ENV=test pytest
```

---

## 📜 License  

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.  

