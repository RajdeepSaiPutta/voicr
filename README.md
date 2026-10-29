# voicr

a voice assistant that runs in the browser. press the mic button, speak, and it answers out loud :) it can also search the web, keep a calendar and read or write files.

new in this version: hold space to talk (push-to-talk toggle under the mic controls), download the session transcript as a text file, and the dashboard now gets its websocket token from /api/auth-token instead of being rejected in secured mode.

it uses groq for speech to text and the language model, edge tts for the voice, and a websocket between the browser and the python server ;)

copy .env.example to .env and put your keys in it, then run python app.py and open localhost:8000. with no keys it runs in mock mode so you can still try the ui :D
