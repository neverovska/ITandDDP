# ITandDDP
## About project
Platform for graphic designers portfolios and chatting between client and designer.
## Mockup Link
https://www.figma.com/file/pSOpfnLSQDN3Iysm5G9Bp5/Untitled?node-id=132%3A168&t=2w4Ydm2go4bGNHLW-1
## Functions
For all users:
- login and register
- open designer profile and project page

For designers:
- crud for project page
- crud for personal page
- invite another designer to project
## Data models
Designers:
- id *number* **PK**
- first name *varchar2(50)*
- last name *varchar2(50)*
- phone number *varchar2(50)*
- bio *varchar2(500)*

Projects:
- id *number* **PK**
- name *varchar2(50)*
- description *varchar2(1000)*
- instruments *varchar2(100)*
- designers_projects_id **FK**

Designer_projects_id:
- id *number* **PK**
- designer_id *number*
- project_id *number*
