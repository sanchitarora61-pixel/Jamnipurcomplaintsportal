# Online Complaints Website

## Features

### For Public (Normal People):
- Home page with welcome message
- Complaint submission form (Name, Mobile, Address, Complaint Description, Upload Photo)
- Option to check complaint status

### For Admin (Gram Panchayat Staff):
- Login page (User ID & Password)
- View all complaints
- Update complaint status
- Download complaints in Excel

## Project Structure
- `client/` - React frontend
- `server/` - Node.js/Express backend

## Getting Started

### Backend
1. Install MongoDB and ensure it is running on `mongodb://localhost:27017/complaints`.
2. In the `server` directory, run:
   ```sh
   node index.js
   ```

### Frontend
1. In the `client` directory, run:
   ```sh
   npm start
   ```

---

Replace any placeholder credentials and update as needed for production use.
