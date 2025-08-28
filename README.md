# Mini Mathway (Portfolio Version)

A minimal **FastAPI + SymPy** project that demonstrates symbolic math operations through an API.  
This project is designed as a **portfolio piece** to showcase skills in API design, testing, and CI/CD integration.

---

## 🚀 Tech Stack
- **Language**: Python 3.11  
- **Framework**: FastAPI  
- **Math Engine**: SymPy  
- **Testing**: pytest + pytest-asyncio + httpx  
- **CI/CD**: GitHub Actions (automated testing)  
- **Dependency Management**: pip + requirements.txt  

---

## ✅ Implemented Endpoints

### `GET /health`
Health check endpoint to verify the API is running.  

**Response:**
```json
{"status": "ok"}

{"expression": "2*x + 3*x"}

{"result": "5*x"}


Run locally:
```bash
pytest -q　


Sample output:
2 passed in 0.15s

How to Run

Clone the repository:
git clone https://github.com/YOUR_USERNAME/mini-mathway-portfolio.git
cd mini-mathway-portfolio

Start the API:
uvicorn main:app --reload

Visit:

Swagger UI: http://127.0.0.1:8000/docs

Health check: http://127.0.0.1:8000/health


## License
This project is licensed under the MIT License – see the [LICENSE](./LICENSE) file for details.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

