# Real Time Speech Translation

This project is a Gradio application that allows users to add captions to their short videos in multiple languages. It utilizes the Whisper model by OpenAI for speech recognition and translation.

The application takes a video as input, converts it to audio, transcribes the audio using Whisper, translates the transcript, and generates a VTT subtitle file. Finally, it combines the original video with the subtitles using ffmpeg to create a subtitled video.
