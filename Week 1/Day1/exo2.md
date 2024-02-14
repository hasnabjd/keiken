### all files under the /etc directory whose names begin with rc
`find /etc -name "rc*"`

(images/af5c7047-6331-4a9d-98c0-7aedb3fde353.png)
### all regular files belonging to you; put the result in the file /tmp/findme and errors in/dev/null,
`find / -type f -user hasna -exec ls -l {} + > /tmp/findme 2> /dev/null`

(d14a83ac-4c8f-4df9-9721-38e7354d8f51.png)
### all subdirectories of /etc
`find /etc -type d`

(<fa0c8f9e-f8f5-4d7d-9242-e53d67b2ff95 (1).png>)
### all regular files under your home directory that haven't been modified in the last 10 days
`find ~ -type f -mtime +10`

(<919c40cb-1246-4a30-9da1-09d8f246e1ec (1).png>)
### The 10 largest file in your computer
`find / -type f -exec du -Sh {} + | sort -rh | head -n 10`

(<eb4ecce7-f20c-454f-aaef-3c429e5867da (1).png>)

(<75daff16-e44e-45d6-adab-f7333ea85727 (1).png>)
