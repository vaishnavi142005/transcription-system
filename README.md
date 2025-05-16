The system converts spoken audio into written text using deep learning-based speech recognition.

It includes a noise reduction step to improve transcription accuracy in environments with background noise.

The audio input is resampled to 16 kHz, as required by the Wav2Vec2 model used for transcription.

The model used is a pre-trained Wav2Vec2 from Hugging Face, specifically designed for English speech recognition.

Audio files uploaded by users are automatically processed, with support for common formats like WAV, MP3, and MPEG.

The system reduces memory usage by allowing audio to be split into chunks before transcription.

All major processing steps are automated: loading, denoising, resampling, and transcribing.

The output is clean, accurate text that can be printed, saved, or further analyzed.

The system uses widely adopted Python libraries including torchaudio, librosa, transformers, and noisereduce.

This project serves as a foundation for more advanced applications like real-time transcription, multilingual support, and integration into web apps or mobile platforms.
