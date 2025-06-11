# Emotional-Campanion-AI
Emotional Companion AI is an intelligent, empathetic virtual assistant designed to support your emotional well-being. Whether you're feeling stressed, lonely, anxious, or just need someone to talk to, this AI listens, understands, and responds with kindness and care.
An emotion-aware AI chatbot that responds with empathy, understanding, and support based on the user’s detected emotional state. Powered by OpenChat 3.5 and GoEmotions, this AI companion uses advanced natural language processing to recognize human emotions and generate emotionally intelligent replies in real time.

🌟 Features:
🎭 Emotion Detection: Uses BERT-based goemotions model to analyze the user's message and identify the most probable emotion from 28 nuanced emotions (like sadness, joy, anger, etc.).

🤖 Emotionally Conditioned Chatbot: Generates responses using OpenChat 3.5, tailoring replies to the user's emotional context for more human-like and supportive interactions.

⚡ Real-Time Inference: Built with Hugging Face Transformers, accelerated with torch.cuda, and optimized for quick emotional analysis and chat generation.

💬 Interactive Chat Interface: Simple, clean UI using Gradio to enable seamless chatting in the browser—just type how you feel!

🧠 Empathetic Prompt Engineering: Prompts the model with the user's detected emotion to shape a compassionate and relevant assistant response.

🛠️ Tech Stack:
Language Models: openchat/openchat-3.5-0106, monologg/bert-base-cased-goemotions-original
Libraries: transformers, torch, gradio, sentencepiece, accelerate
UI: Gradio Blocks for interactive and modular UI design
Platform: CUDA-accelerated PyTorch for high-performance inference

💖 Use Cases:
Mental health support
Emotion-aware virtual companions
Empathy-driven chat interfaces
Social robotics and AI therapy experiments

📌 Future Enhancements:
Multilingual emotion detection and response
Emotion trends and visualization dashboard
Custom personas or voice synthesis support
Optional memory of past emotional states

