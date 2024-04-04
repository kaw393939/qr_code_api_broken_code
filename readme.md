# RestAPI for Creating QR Codes

# Instructor Videos
* [Rest API Project Overview](https://youtu.be/xEcBKSSXxhQ)

# Install
1. Clone
2. Make virtual environment:  python3 -m venv venv
3. Activate virtual environment: source venv/bin/activate
4. Install requirements: pip install -r requirements.txt
5. Note: make sure docker is started
6. run pytest locally to check that it works locally
7. Start the app with docker compose up --build
8. Goto http://localhost/docs to view openapi spec documentation
9. Click "authorize" input username: admin password: secret
10. Test making,  retrieving, and deleting QR codes on the spec page.