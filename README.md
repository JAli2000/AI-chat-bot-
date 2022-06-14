# AI-chat-bot-
__django and telegram bot__



...:| USE BASH |:..

# Run posgress 
sudo docker-compose -f docker-compose.dev.yml up -d 

# Create and activate virtual environment :
virtualenv -p python3 venv 
source venv/bin/activate 

# Install requirements :
pip install -r requirements.txt 

# migrate :
./manage.py migrate 

# Initiate db : 
./manage.py initial_db 

# Start chat with bot 
./manage.py startchat 

# for clear db : 
./manage.py clear_db
