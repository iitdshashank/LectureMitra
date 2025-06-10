# **LectureMitra: The AI-Powered YouTube Tutor**

This repository contains the Google Colab notebook for LectureMitra, a conversational AI designed to help you study and understand any YouTube video.

**For any doubt while running the code, take reference from the demo video. ( https://youtu.be/EXim3NoRhRI )**

## **Section 1: Project Overview**

### What is LectureMitra?

LectureMitra is an interactive, AI-powered conversational tutor that transforms any YouTube video into a personalized learning session. It uses a Retrieval-Augmented Generation (RAG) model, which grounds its responses strictly in the video's transcript content. This means it won't make things up or use external knowledge, acting as a true expert on that *specific* video. The bot supports both text and voice interaction for asking questions and receiving answers.

### Who It's For

This tool is designed for anyone who learns from video content and wants a more efficient and engaging way to do so:

*   **Students** tackling long university lectures or complex tutorials.
*   **Professionals** trying to quickly extract key information from conference talks or technical demos.
*   **Lifelong Learners** exploring new topics through documentaries and educational videos.

### Why It Matters

LectureMitra addresses the core limitations of passive video watching. It allows you to:

*   **Save Time:** Instantly find specific information or get a summary of a key concept without manually scrubbing through the video timeline.
*   **Improve Comprehension:** Ask clarifying questions as they arise, reinforcing your understanding of the material.
*   **Learn Actively:** Convert passive screen time into an active, two-way conversation with the content.
*   **Get Reliable Answers:** Trust that the information provided is based solely on the source material you've provided.

## **Section 2: How to Use This Notebook**

Follow these simple steps to run your own LectureMitra session.

### Prerequisites

1.  A **Google Account** (to use Google Colab).
2.  A **Sarvam AI API Key**. You can get one from the [Sarvam AI Platform](https://platform.sarvam.ai/).

### Step-by-Step Instructions

1.  **Open in Google Colab:**
    *   Download the `LectureMitra.ipynb` file.
    *   Go to [Google Colab](https://colab.research.google.com/) and click `File -> Upload notebook...` to upload and open the file.

2.  **Run the Application:**
    *   The easiest way to start is to run all the cells at once. Go to the menu bar and click **`Runtime -> Run all`**.

3.  **Enter Your API Key:**
    *   The notebook will start running from top to bottom. Partway through, an input box will appear asking for your **Sarvam AI API Key**.
    *   Paste your key into this box and press `Enter`.

4.  **Provide a YouTube URL:**
    *   Scroll to the bottom of the notebook. After all the cells have finished running, a final input box will appear.
    *   **Paste the URL of the YouTube video** you want to study and press `Enter`. The video must have English captions available.

5.  **Start Chatting!**
    *   The Q&A session has now begun! You can now interact with your tutor:
        *   **Ask questions via text:** Simply type your question and press `Enter`.
        *   **Ask questions via voice:** Type `voice` and press `Enter`. Your browser may ask for microphone permission. After giving permission, speak your question.
        *   **End the session:** Type `exit` and press `Enter`.

Enjoy your personalized learning session
