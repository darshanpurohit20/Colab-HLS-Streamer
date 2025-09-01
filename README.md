# HLS Media Streamer

**HLS Media Streamer** is a web application that allows users to download videos from the web, convert them to HLS format (`.ts` segments and `.m3u8` playlists), and stream them instantly. All backend processing is handled via a Google Colab notebook, enabling fast, scalable, and hassle-free video streaming.

---

## Features

- 🌐 Stream any video from the web within 1–2 minutes.
- ⚡ Fast processing and HLS generation on Google Colab.
- 🔀 Automatic conversion to HLS format (`.ts` segments + `.m3u8` playlist).
- 🗂️ Dynamic folder management and filename sanitization.
- 🧵 Threaded downloads for efficient processing.
- 💻 Responsive frontend to browse, stream, and manage videos.
- ⬇️ No hassle downloading – stream directly from the browser.

---

## Technologies Used

- **Backend:** Python, Flask, FFmpeg  
- **Frontend:** HTML, CSS, JavaScript  
- **Processing:** Google Colab Notebook (`.ipynb`)  

---

## How to Run

1. **Open the Colab Notebook**:

   [HLS Media Streamer Notebook](Your-Notebook-Link.ipynb)

2. **Run all cells** – it will set up the environment, download videos, convert them to HLS format, and start the Flask server.  

3. Open your browser and navigate to the local server address shown in Colab output (e.g., `http://127.0.0.1:9192`) to browse and stream videos.

---

## Project Structure
