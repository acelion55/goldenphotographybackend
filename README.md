# Golden Photography Backend

## Setup Instructions

1. Install dependencies:
```bash
cd backend
npm install
```

2. Start the server:
```bash
npm start
```

The server will run on http://localhost:3001

## API Endpoints

- `POST /api/upload` - Upload a file
- `GET /api/files` - Get all uploaded files
- `DELETE /api/files/:filename` - Delete a file
- `GET /uploads/:filename` - Access uploaded files

## Features

- File upload with validation (images and videos only)
- 50MB file size limit
- Automatic file storage in `uploads/` directory
- CORS enabled for frontend integration
