# SnapSync

SnapSync is a personalized music recommendation web application designed to suggest songs for your Instagram content. By analyzing your public Instagram profile and the mood of the content you plan to post, SnapSync generates appropriate captions and song recommendations.

## Features

- **Instagram Login**: Authenticate users with their Instagram account.
- **Content Upload**: Users can upload photos for stories and posts.
- **Mood Selection**: Users can select the mood for their content (e.g., aesthetic, romantic, blues).
- **Caption and Song Recommendations**: Based on the user's profile and selected mood, SnapSync generates suitable captions and song suggestions.

## Project Structure

```
SnapSync/
├── frontend/
│   ├── node_modules/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── components/
│   │   │   └── PhotoUpload.js
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
│   ├── package.json
│   └── ...
├── backend/
│   ├── app.py
│   ├── ...
└── ...
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Python](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/SnapSync.git
    cd SnapSync
    ```

2. **Frontend Setup**:

    ```bash
    cd frontend
    npm install
    npm start
    ```

3. **Backend Setup**:

    ```bash
    cd backend
    pip install -r requirements.txt
    python app.py
    ```

### Usage

1. **Start the frontend**:

    ```bash
    cd frontend
    npm start
    ```

    The frontend will be available at `http://localhost:3000`.

2. **Start the backend**:

    ```bash
    cd backend
    python app.py
    ```

    The backend will be available at `http://localhost:5000`.

### Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Thanks to the open-source community for providing the tools and libraries used in this project.
