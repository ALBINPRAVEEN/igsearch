<p align="center">
  <img src="https://instagram.fcok1-1.fna.fbcdn.net/v/t51.2885-15/fr/e15/s1080x1080/168612449_282110913384556_3661831203179550868_n.jpg?tp=1&_nc_ht=instagram.fcok1-1.fna.fbcdn.net&_nc_cat=104&_nc_ohc=xYi2UgERwPIAX9zKbfX&edm=ABJHkxYAAAAA&ccb=7-4&oh=e6fce17397b399b7efe80491c2b4ff68&oe=608FD9A8&_nc_sid=fa978c&ig_cache_key=MjU0NDMwMTM0NjY3MzQwMTI3NA%3D%3D.2-ccb7-4" width="757" height="427">
</p>

 
<p align="center">
  Open Source Information Instagram
</p>

---

* The Instagram OSINT Tool gets a range of information from an Instagram account that you normally wouldn't be able to get
from just looking at their profile

* The information includes:

* [ profile ] : Username, Profile Name, URL, Followers, Following, Number of Posts, Bio, Profile Picture URL, Is Business Account ?, Connected to a FB account ?, External URL, Joined Recently ?, Business Category Name, Is private ?, Is Verified ?,

* [ tags ] : most used , and by -t all used tags

* [ posts ] : accessability caption, location, timestamp, comments disabled, Caption, picture url

---

## • How To Install

`$ pkg install -y git`

`$ git clone https://github.com/ALBINPRAVEEN/igsearch`

`$ chmod +x install.sh && ./install.sh`

## • Usage

`$ python3 main.py -u username`

`$ python3 main.py -h`

`usage: main.py [-h] -u USERNAME [-p] [-s] [-t]`

`optional arguments:`

`  -h, --help            show this help message and exit`

`  -u USERNAME, --username USERNAME`
`                        username of account to scan`

`  -p, --post            get all uploaded images info`

`  -s, --savedata        save data to file `
`                        ( save profile pic, info , post info )`

`  -t, --tags            list often used tags`

## • Update

`$ git pull`

---
