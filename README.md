# ITandDDP
## About project
Platform for graphic designers portfolios and chatting between client and designer.
## Mockup Link
https://www.figma.com/file/pSOpfnLSQDN3Iysm5G9Bp5/Untitled?node-id=132%3A168&t=2w4Ydm2go4bGNHLW-1
## Functions
For all users:
- login and register
- open designer profile and project page
For clients:
- chat with designer
For designers:
- crud for project page
- crud for personal page
- chat with client or another designer
## Data models
Roles:
- id
- name

Users:
- id 
- role id
- first name
- last name
- phone number 

Projects:
- id
- name 
- designer_id

Images:
- id
- image
- project_id

Message:
- id
- text
- timestamp
- user_id
- room_id

Room:
- id
- user1_id
- user2_id
