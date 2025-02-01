<h1 align="center">
🚀 Learning FastAPI
</h1>

<h3 align="center">
📖 Documenting my journey into FastAPI for better understanding and future reference
</h3>

---

## 📌 What I Have Learned

### ✅ Basic Backend Fundamentals
- Setting up a **FastAPI server** from scratch  
- Understanding **GET requests** with **path parameters** & **query parameters**  
- Using **async functions** and enforcing type hints (`int`, `str`, `bool`, `Optional[str]`, etc.)  
- Handling **POST requests** with **Pydantic's BaseModel** for data validation  

---

🔹 **Why This Repository?**  
This repository serves as my personal **FastAPI learning log**, helping me revisit concepts and share knowledge with others. Stay tuned for more updates! 🚀  


### **Key Improvements:**
✅ **Clear Sections** → Learning, Setup, Running, Stopping  
✅ **Consistent Formatting** → Code blocks, comments, icons  
✅ **Platform-Specific Commands** → Windows & Linux/Mac  
✅ **Better Readability** → Emphasized key points  

Would you like me to add **Advanced Topics** like middleware, authentication, or database integration later? 🚀




## 🔥 Want to Try This Out?

### Pull the code

``` mkdir FastAPI  ```

``` cd FastAPI ```

``` git init ```

``` git pull https://github.com/mallickboy/FastAPI.git ```


### 🐍 Create & Activate Python Virtual Environment

``` py -3.11 -m venv .venv ```

``` .venv\Scripts\activate ```  # Windows

``` source .venv/bin/activate ```  # Mac/Linux


### 🚀 Install Dependencies & Start the Server

``` pip install -r requirements.txt ```

``` uvicorn app.main:app --host "0.0.0.0" --port 8080 ```


### 🔄 Enable Auto-Reload for Development (Optional)

``` puvicorn app.main:app --host "0.0.0.0" --port 8080 --reload ``` ( Optional for auto relaod )


### 🛑 Stop Virtual Environment

``` deactivate ```

### ⚠️ Remove Python Virtual Environment (Use with Caution!)

``` Remove-Item -Recurse -Force .\venv ```
