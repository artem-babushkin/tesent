TEmperatureSENsorTracker
#### Video Demo:  <URL HERE>
#### Description:
My flat always seems to be cold, therefore I tried to solve it different ways but I couldn't measure their efficiency with actual degrees. 
So, my project is about storing and visualize temperature data.

TESENT is able to receive data from custom sensors via http requests, store data for one week and visualize it for a particular user.

I've decided to create my final project on my own infrastructure, so it can be accessible worldwide. To do so I have ...
- Rent a VPC with public IP
- Register free domain name
- Use free DNS hosting
- Use free email hosting for custom domain
- Get free SSL certificate
- Install free opensource software
  - APACHE-WSGI-FLASK to serve webpages and http API
  - BOOTSTRAP to style my site
  - SQLite to store users and some data related attributes
  - RRDtool to store data and to create graphs

Most of TESENT written on python because of main render engine - FLASK, and because there are a lot of software with python libraries available.

I've made few pages and API ...
- data view page with few customization abilities
- personal area where users can regenerate their passwords or API tokens
- two text pages with about and how-to information
- simple http API to receive and store data

You are welcome to join https://www.tesent.ml
