# Ai-Chat-Box

This is a AI chat app enable user to text other users, moreover ask text-davinci-003 ai model provided by OpenAi. But it no longer works because my trial has expired :)

# Technique:
1. React
2. React-router-dom
3. React-redux
4. Vite
5. Sass
6. OpenAi
7. ExpressJs

# Installation: 
To run the application locally, follow these steps:

1. Clone the repository to your local machine using: ``` git clone https://github.com/Ganzzi/Ai-Chat-Box.git ```
2. Move into server folder: ``` cd Ai-Chat-Box\server ```
3. Install: ``` npm install ``` or ``` yarn install ```
4. Change .env.example to .env, add some information:
  - Go to https://chatengine.io/projects --> new project --> copy Project Id & Private Key --> paste to CHATENGINE_PRIVATE_KEY & PROJECT_ID --> click user --> create new user -> copy and paste to BOT_USER_NAME & BOT_USER_SECRET
  - Go to https://platform.openai.com/account/api-keys --> Create and copy your API key --> paste to OPEN_API_KEY
5. Start server: ``` npm run dev ```
6. Create new terminal at client folder
7. Install: ``` npm install ``` or ``` yarn install ```
8. Change .env.example to .env, paste your Project Id copied in chategine site to VITE_PROJECT_ID 
9. Start client: ``` npm run dev ```
10. Open the application in your web browser at ``` http://127.0.0.1:5173 ```
11. Remember to add bot to your chat: member --> add member

# Resource: https://www.youtube.com/watch?v=ffEDkqfIzxM&list=LL&index=12
