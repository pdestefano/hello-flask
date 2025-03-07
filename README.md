# Flask Hello World App

A simple Flask app to deploy on Heroku.

## Setup & Run Locally
1. Install dependencies:pip install -r requirements.txt
2. Run the app:python app.py

## Deploy to Heroku
1. Login to Heroku:
heroku login
2. Create a GitHub repo and push your code:
git init git add . git commit -m "Initial commit" git branch -M main git remote add origin https://github.com/YOUR_USERNAME/hello-flask.git git push -u origin main
3. Create and deploy on Heroku:
heroku create your-app-name git push heroku main

Visit the deployed app at:
https://your-app-name.herokuapp.com/

---

Once you've set this up in Visual Studio Code, you can push it to GitHub and deploy to Heroku. Let me know if you need help with any step! 🚀
