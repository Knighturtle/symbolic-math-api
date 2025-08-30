# Mini Mathway (Portfolio Version)

A minimal symbolic math API built with FastAPI + SymPy. Deployed on Render with Docker, tested with pytest, and integrated CI/CD via GitHub Actions.

---

fastapi
uvicorn[standard]
httpx
pytest
pytest-cov
coverage-badge

## 🚀 Live
- API: https://mini-mathway-portfolio.onrender.com
- Docs: https://mini-mathway-portfolio.onrender.com/docs
- Health: https://mini-mathway-portfolio.onrender.com/health


## 🚀 Tech Stack
| Category        | Tools/Libraries                  |
|-----------------|----------------------------------|
| Language        | Python 3.11                      |
| Framework       | FastAPI                          |
| Math Engine     | SymPy                            |
| Testing         | pytest, pytest-asyncio, httpx    |
| CI/CD           | GitHub Actions                   |
| Deployment      | Render (Docker)                  |


---

## ✅ Implemented Endpoints

### `GET /health`
Health check endpoint to verify the API is running.

**Response:**
~~~json
{"status": "ok"}
~~~

---

### `POST /simplify`
Simplify a mathematical expression.

**Request:**
~~~json
{"expression": "2*x + 3*x"}
~~~

**Response:**
~~~json
{"result": "5*x"}
~~~

---

## 📸 Screenshots

**Swagger UI**  
![Swagger UI](assets/swagger-ui.jpg)




**Health Check**  


![Health Check](assets/health-check.jpg)






## 🧪 Testing

Run locally:
~~~ **\`\`\`**bash  **\`\`\`**
 **\`\`\`**pytest -q **\`\`\`**
~~~

**Sample output:**
~~~text
2 passed in 0.15s
~~~

## ⚙️ How to Run Locally

Clone the repository:
```bash
git clone https://github.com/Knighturtle/mini-mathway-portfolio.git
cd mini-mathway-portfolio

Install dependencies:
pip install -r requirements.txt

Run tests (optional):
pytest -q

Start the API:
uvicorn main:app --reload

 **\`\`\`**




---


## 🚀 Roadmap
- [ ] /solve: equation solving (linear, quadratic, systems)
- [ ] /integral: calculus (integrals)
- [ ] /derivative: calculus (derivatives)
- [ ] /factor & /expand: expression manipulation
- [ ] Step-by-step solution explanations


---

## 📚 Key Takeaways
- Built and tested an API combining **FastAPI** and **SymPy**  
- Learned asynchronous testing with **pytest-asyncio**  
- Set up **CI/CD pipelines** with GitHub Actions  
- Maintained a clean and professional repository (template repo, `.gitignore`, test coverage)  

---

## 📜 License
This project is licensed under the MIT License – see the [LICENSE](./LICENSE) file for details.  

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
