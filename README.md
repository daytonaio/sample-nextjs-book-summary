# 📚 Book Summary Platform ( Nextjs / FastAPI )

This repository contains a **Book Summary Platform** built with **Next.js**, **FastAPI**, **MeiliSearch**, and the **Gemini API**. The platform enables users to upload books, generate AI-powered summaries, and search for them quickly, making knowledge more accessible and convenient.

---

### Open Using Daytona

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).
2. **Create the Workspace**:
   ```bash
   daytona create https://github.com/daytonaio/sample-nextjs-book-summary
   ```
3. **Updating the API Keys**:

To update the **GEMINI_API_KEY** with your own API key:

1. Navigate to the following file in the backend directory:
   ```
   backend/app/utils.py
   ```
2. Open the file and locate the `GEMINI_API_KEY` variable.
3. Replace the placeholder or existing key with your own API key:
   ```python
   GEMINI_API_KEY = "your_api_key_here"
   ```
4. Save the file.

Make sure to keep your API key secure and avoid sharing it publicly.

### 🚀 Running the Application

Once the application is set up, you can access the different components at the following addresses:

- **Frontend**: [http://localhost:3000](http://localhost:3000)
- **MeiliSearch Panel**: [http://localhost:7700](http://localhost:7700)
- **Backend**: [http://localhost:8000](http://localhost:8000)

---

## ✨ Features

- **Upload Books**: Easily upload your favorite books in various formats (PDF, ePub, etc.) to the platform.
- **AI-Powered Summaries**: Generate concise and accurate summaries of books instantly using the Gemini API.
- **Efficient Search**: Quickly find specific books or summaries using MeiliSearch's powerful search capabilities.
- **User-Friendly Interface**: Enjoy a modern and intuitive frontend built with Next.js for seamless navigation.
- **Reliable Backend**: Experience a robust and scalable backend powered by FastAPI.
- **Personal Library**: Access all your uploaded books and their summaries anytime, anywhere.
- **Knowledge On-the-Go**: Retrieve summaries through a responsive design suitable for both desktop and mobile users.
- **Secure Data Handling**: Ensure your data is securely stored and managed.
