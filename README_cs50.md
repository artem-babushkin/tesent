TEmperatureSENsorTracker
#### Video Demo:  <URL HERE>
#### Description:
I had a problem with low temperature in my flat. I tried to solve it different, ways but I couldn't measure their efficiency with actual degrees. 
So, my project is about to store and visualize temperature data.

TESENT is able to receive data from custom sensors via http requests, store data for one week and visualize it for a particular user.

I decided to create a final project on my own infrastructure, so it can be accessible worldwide:
- I've rent a VPC with public IP
- register free domain name
- use free dns hosting
- use free email hosting for custom domain
- get free SSL certificate
- install free opensource software
  - APACHE-WSGI-FLASK to serve webpages and http API
  - BOOTSTRAP to style my site
  - SQLite to store users and some data related attributes
  - RRDtool to store data and to create graphs

Most of TESENT written on python because of main render engine - FLASK, and because there are a lot of software with python libraries.

I've made few pages and API:
- data view page with few customization abilities
- personal area where users can regenerate their passwords or API tokens
- two text pages with about and how-to information
- simple http API to receive and store data

