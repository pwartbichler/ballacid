
# ballacid - Internet Radio Site

**ballacid** is an Internet radio website inspired by my favorite techno channel. This project utilizes **Python3** for the backend and **Next.js** for the frontend, with deployment on [Vercel](https://vercel.com). The live version of the site can be found at [ballacid.vercel.app](https://ballacid.vercel.app).

## Technologies

- **Backend:** Python 3
- **Frontend:** Next.js
- **Deployment:** Vercel

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following installed on your system:
- Python 3
- Node.js (including npm)

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   python3 -m venv venv
   source venv/bin/activate   
3. Install the required Python packages
   ```bash
   pip install -r requirements.txt   
4. Start the development server
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    python3 backend/app.py    
5. Run the app
   ```bash
   python app.py
   
### Frontend setup

    cd frontend
    npm install
    npm run dev


Your frontend app should now be running on http://localhost:3000, and the backend is accessible through the specified port (default is port 5000 for Flask).

### Deployment

The project is automatically deployed on Vercel when changes are pushed to the main branch. For details on configuration and the deployment process, refer to the Vercel documentation.
