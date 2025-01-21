# Chatterlyze

# Real-Time Chat Application with Sentiment Analysis

This project is a real-time chat application built using Django and WebSockets, incorporating sentiment analysis to enhance user engagement by offering emotional insights into conversations. It enables users to exchange messages, receive real-time sentiment feedback, and share files seamlessly within the chat interface.

## Key Features
- **Instant Messaging:** Users can send and receive messages in real time using WebSockets for instant communication.
- **Emotion Analysis:** Messages are analyzed using a pre-trained NLP-based sentiment analysis model to provide insights into the emotional tone of conversations.
- **File Sharing:** Users can upload and download files directly within the chat, linking files to specific conversations.
- **Django Framework:** Built on the Django web framework, the application delivers robust scalability and performance for backend development.
- **User Sessions:** The application maintains user sessions, ensuring messages are tied to the logged-in user and specific to each chat room.

## How It Works

### Real-Time Messaging with WebSockets
- Django Channels are used on the backend to manage WebSocket connections.
- Messages sent by users are instantly broadcast to all participants in the chat room.

### Sentiment Analysis
- Every message is processed through a sentiment analysis model.
- The application uses `nltk` and a pre-trained NLP model to classify messages as positive, negative, or neutral.
- The sentiment of each message is displayed alongside the text to enrich user interaction.

### File Sharing
- Users can upload and download files directly within the chat interface.
- Uploaded files are stored on the server and linked to the corresponding chat conversations.

