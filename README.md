<p align="center">
  <img src="https://instagram.fcok10-1.fna.fbcdn.net/v/t51.2885-15/fr/e15/s1080x1080/155235768_273833734139974_2417452675757866425_n.jpg?tp=1&_nc_ht=instagram.fcok10-1.fna.fbcdn.net&_nc_cat=110&_nc_ohc=c-DgyanP83MAX-w_VkG&oh=d3fae8b869e4092b94e6d7d880e9d560&oe=606863FB&ig_cache_key=MjUyMDM3MTU4NTIzNjY0NDg0MA%3D%3D.2" width="300" height="120">
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

`$ git clone https://github.com/ALBINPRAVEEN/osi.ig`

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
