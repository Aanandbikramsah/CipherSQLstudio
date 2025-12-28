# CipherSQLStudio

**CipherSQLStudio** is a browser-based SQL learning platform that allows students to practice SQL queries interactively. Users can attempt pre-configured assignments, view real-time query results, and receive intelligent hints to guide learning without revealing full solutions.  

---

## Features

### Core Features
- **Assignment Listing**: Browse available SQL assignments with difficulty, title, and description.  
- **Assignment Attempt Interface**:
  - **Question Panel**: View assignment requirements.
  - **Sample Data Viewer**: Inspect pre-loaded table schemas and sample data.  
  - **SQL Editor**: Write SQL queries in-browser using **Monaco Editor**.  
  - **Results Panel**: Display executed query results in a formatted table.  
  - **Hint System**: Get guidance from integrated LLM API without revealing solutions.  
- **Query Execution Engine**: Execute user queries against PostgreSQL, validate, sanitize, and return results or errors.  

### Optional Features
- User authentication (login/signup)  
- Save SQL query attempts per assignment  

---

## Technology Stack

- **Frontend**: React.js, Vanilla SCSS (mobile-first responsive design, BEM methodology)  
- **Backend**: Node.js, Express.js  
- **Databases**: PostgreSQL (sandbox), MongoDB Atlas (persistence)  
- **Code Editor**: Monaco Editor  
- **LLM Integration**: OpenAI/Gemini API for intelligent hints  

---

## Project Structure

