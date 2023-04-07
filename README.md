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
- id *number* **PK**
- name *varchar2(50)*

Users:
- id *number* **PK**
- role id **FK**
- first name *varchar2(50)*
- last name *varchar2(50)*
- phone number *varchar2(50)*

Projects:
- id *number* **PK**
- name *varchar2(50)*
- designer_id **FK**

Message:
- id *number* **PK**
- text *varchar2(200)*
- timestamp *timestamp*
- user_id **FK**
- room_id **FK**

Room:
- id *number* **PK**
- user1_id **FK**
- user2_id **FK**
