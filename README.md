# SD Renderer (PyPI Package)

A Python package for rendering structured content (Markdown / Docs / Code) into clean output formats.

---

## 🚀 Setup Instructions

### Step 1: Create Virtual Environment

```bash
conda create -n renderer python=3.8 -y
conda activate renderer
```

---

### Step 2: Create Project Structure

Project Name: **SDRenderer**

Create the standard folder structure using your template.

Example:

```
SDRenderer/
│── src/
│── tests/
│── setup.py
│── setup.cfg
│── pyproject.toml
│── requirements_dev.txt
```

---

### Step 3: Install Development Dependencies

```bash
pip install -r requirements_dev.txt
```

---

### Step 4: Configure Packaging Files

Make sure the following files are properly implemented:

- setup.py  
- setup.cfg  
- pyproject.toml  

These files define how your package is built and distributed.

---

## 📦 Build & Install Package (Optional)

```bash
pip install .
```

---

## 🧪 Run Tests (Optional)

```bash
pytest
```

---

## 📌 Notes

- Always activate the virtual environment before working  
- Keep dependencies updated in requirements_dev.txt  
- Follow proper versioning before publishing to PyPI  

---

## 👨‍💻 Author

Shuvo Dutta