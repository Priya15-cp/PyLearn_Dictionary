LexiFlow-AI: Hybrid Intelligent Dictionary:-

​A high-performance Python dictionary engine featuring Local Caching, API Integration, and Neural Text-to-Speech.

​🚀 Key Features
​Hybrid Search: Checks a local words.json first for instant results before falling back to an external API.
​Dynamic Learning: Automatically saves new words fetched from the API to the local database for future offline use.
​Natural Pronunciation: Uses Google's Neural TTS (gTTS) to generate human-like audio for every word.
​Audio Caching: Saves .mp3 files locally to save bandwidth and improve performance.

​->Technical Stack
​Language: Python 3.11
​Data: JSON (Key-Value Storage)
​Libraries: requests, gTTS, playsound

​->How it Works
​Input: User enters a word.
​Lookup: Engine checks words.json.
​Fallback: If missing, it queries dictionaryapi.dev.
​Save: New data is saved locally to avoid repeated API calls.
​Voice: A high-quality audio file is generated and played.
