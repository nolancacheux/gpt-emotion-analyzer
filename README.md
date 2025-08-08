# GPT-Emotion Analyzer

<p align="center">
  <img src="/client/photos/explication1.JPG" alt="App Screenshot 1" width="400"/>
  <br/>
  <em>Analyze emotions from photos and get personalized AI-driven recommendations.</em>
</p>

## About The Project

GPT-Emotion Analyzer is a web application that detects emotions from faces in photos and generates personalized recommendations based on the detected feelings. Users can upload images or capture photos directly from their webcam. The application uses an AI model for face and emotion detection and then communicates with OpenAI's ChatGPT API (gpt-3.5-turbo) to provide tailored suggestions, such as opinion pieces, music recommendations, or activities suited to the user's emotional state.

### Key Features

*   **Face & Emotion Detection:** Analyzes emotions from uploaded images or live webcam feed.
*   **AI-Powered Recommendations:** Integrates with the ChatGPT API to generate personalized content.
*   **Emotion Statistics:** Displays a breakdown of detected emotions with progress bars.
*   **Daily Analysis:** Provides a personalized daily summary based on the user's emotions.
*   **Custom Suggestions:** Offers music, activities, and other ideas tailored to your mood.

### Built With

*   **Frontend:**
    *   [Vite](https://vitejs.dev/)
    *   HTML, CSS, JavaScript
*   **Backend:**
    *   [Node.js](https://nodejs.org/)
    *   [Express](https://expressjs.com/)
*   **APIs:**
    *   [OpenAI API](https://openai.com/docs/api-reference/)

---

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

*   [Node.js](https://nodejs.org/en/download/) (v14 or later)
*   [npm](https://www.npmjs.com/get-npm)
*   An OpenAI API key

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/nolancacheux/gpt-emotion-analyzer.git
    cd gpt-emotion-analyzer
    ```

2.  **Install client dependencies:**
    ```sh
    cd client
    npm install
    ```

3.  **Install server dependencies:**
    ```sh
    cd ../server
    npm install
    ```

4.  **Set up your environment variables:**
    Create a `.env` file in the `server` directory and add your OpenAI API key:
    ```env
    OPENAI_API_KEY="your_openai_api_key_here"
    ```

### Running the Application

1.  **Start the backend server:**
    From the `server` directory, run:
    ```sh
    npm run server
    ```

2.  **Start the frontend client:**
    In a separate terminal, from the `client` directory, run:
    ```sh
    npm run dev
    ```

3.  **Open the application:**
    Open your browser and navigate to `http://localhost:5173`. You can now upload an image or use your webcam to start analyzing emotions!

---

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

Don't forget to give the project a star! Thanks again!

## License

Distributed under the ISC License. See `LICENSE` for more information.

## Contact

Nolan Cacheux - [@nolancacheux](https://github.com/nolancacheux)

Project Link: [https://github.com/nolancacheux/gpt-emotion-analyzer](https://github.com/nolancacheux/gpt-emotion-analyzer)

## Screenshots

<p align="center">
  <img src="/client/photos/explication2.JPG" alt="Explication 2" width="48%">
  <img src="/client/photos/explication3.JPG" alt="Explication 3" width="48%">
  <img src="/client/photos/explication4.JPG" alt="Explication 4" width="48%">
  <img src="/client/photos/explication5.JPG" alt="Explication 5" width="48%">
</p>
