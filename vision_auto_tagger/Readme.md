# vision_auto_tagger
# In this document, you will understand how this codes work.

# 1.topic: vision_auto_tagger. GPT 
# 2.project goals:
# - input camera images
# - OpenAI get the images and show the explanation
# - search the log and data in DB
# 얼굴 표정 자동태깅

# 3.skills
# - Python, PyQt5
# - OpenAI API
# - SQLite3
# - dotenv

# 4.flowchart
# - upload images
# - input prompt
# - ask GPT that sort and explain the images
# - show the info of images and save the DB
# - explore the lable with searching tools

# 5.architecture
<img width="1064" height="754" alt="archtetr" src="https://github.com/user-attachments/assets/41ff7a76-9347-4d37-b7e7-150bf4833b84" />

# 6.structure of directory
project/
├── gui/
│   └── main_app.py
├── api/
│   └── openai_api.py
├── db/
│   └── image_log.db
│   └── moving.db
├── utils/
│   └── file_handler.py
├── main.py
├── .env
└── requirements.txt

# 7.sinario
# - in that images, sys will found main big 5 items
# - describe the images, save the discription
# - categories it with tags
# - Kaggle face expression recognition dataset

# 8.more
# - export the result with CSV/Excel
# - GPT tag checking
# - put cropto.
# 개인정보 보안 시스템 도입
