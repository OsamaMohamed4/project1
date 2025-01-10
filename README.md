# Project1

## Requirements

- Python 3.8 or above

### Install Python using Miniconda

- Download and install Miniconda from this link: [Miniconda Installation Guide](https://docs.anaconda.com/miniconda/install/)

- Create a new environment using the following command:
  ```
  conda create -n mini-RAG-app python=3.10
  ```

- Activate the environment:
  ```
  conda activate mini-RAG-app
  ```

## Installation

### Install the required package

```bash
pip install -r requirements.txt
```

### Setup the environment variables

- Copy `.env.example` to `.env`:
  ```bash
  cp .env.example .env
  ```

- Set your environment variables in the `.env` file, e.g., `OPENAI_API_KEY`.

---

### Modify the README file

Ensure the README file is updated with correct and clear instructions for the setup process.

## run the fastAPI server 

  ```bash
  uvicorn main:app --reload --host 0.0.0.0 --port 500
  ```