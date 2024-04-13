# FastAPI-Tutorial
Repository to accompany FastAPI Tutorial (https://fastapi.tiangolo.com/tutorial/)

# Developers (Contributors): Installation

To install `fastapi-tutorial` using [Poetry](https://python-poetry.org/), follow these steps:

### 1. Prerequisites

Make sure you have Python 3.12 or later installed on your system.

### 2. Install Poetry

To install Poetry, you can use the [official installer](https://python-poetry.org/docs/#installing-with-the-official-installer)  provided by Poetry. Do not use pip.

### 3. Clone the Repository

Clone the `fastapi-tutorial` repository from GitHub:

```bash
git clone https://github.com/mohitshrestha/fastapi-tutorial
```

### 4. Install Dependencies

Use Poetry to install the package and its dependencies:

```bash
poetry install
```

or you can create a virtualenv with poetry and install the dependencies

```bash
poetry shell
poetry install
```

### 5. Running the FastAPI app

```bash
uvicorn main:app --reload
```

or If run_fastapi_app.py file exist with the following example code then we can simply run:
Please edit `src/fastapi-app/1-First_Steps/main:app` based on which chapter you are working on.
```bash
import uvicorn
if __name__ == "__main__":
    uvicorn.run("src/fasapi-app/1-First_Steps/main:app", host="127.0.0.1", port=8000, reload=True)
```

```bash
python run_fastapi_app.py
```
