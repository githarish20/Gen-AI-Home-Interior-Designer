# Gen-AI Home Interior Designer

## Backend Setup & Run

1. Navigate to the backend directory:
   ```bash
   cd /Users/harishwani/Downloads/Gen-AI-Home-Interior-Designer-main/backend
   ```

2. Install dependencies (if not already installed):
   ```bash
   poetry install --no-root
   ```

3. Create a `.env` file (if not exists) and add your Gemini API key:
   ```bash
   echo "GEMINI_API_KEY=your_api_key_here" > .env
   ```
   > Replace `your_api_key_here` with your actual Gemini API key.

4. Run the backend server:
   ```bash
   poetry run uvicorn main:app --reload
   ```

5. The backend will be available at:
   - API Base: [http://localhost:8000](http://localhost:8000)  
   - API Docs: [http://localhost:8000/docs](http://localhost:8000/docs)

---

## Frontend Setup & Run

1. In a new terminal, navigate to the frontend directory:
   ```bash
   cd /Users/harishwani/Downloads/Gen-AI-Home-Interior-Designer-main/frontend
   ```

2. Install dependencies (if not already installed):
   ```bash
   npm install
   ```

3. Run the frontend development server:
   ```bash
   npm run dev
   ```

4. The frontend will be available at:
   - [http://localhost:5173](http://localhost:5173) (or the next available port)

---

## Access the Application

- Open your browser and go to: [http://localhost:5173](http://localhost:5173)  
- Ensure that the backend is running for the frontend to function properly.

---

## Notes

- Requires **Python 3.12+** and **Node.js** installed.  
- The `--reload` flag enables auto-reload when you make changes to backend code.  
- For production deployment, use a proper web server like **Nginx** to serve the frontend.  
