This is the source code of [LC3CTF](lc3ctf.co) website. And it can be easily modified to a universal CTF platform.
# LC3CTF
LC3CTF is originally the lab 4 of [ICS 2018](acsa.ustc.edu.cn/ics) (a CS course in USTC). And it is based on LC-3 CPU.

# Usage
- Modify ```config.json``` and ```tasks.json``` in the example directory and then move them outside.
- Run ```python3 task_import.py``` to generate ```ctf.db```.
- Then use ```python3 server.py``` to start a temporary server, or use uwsgi with nginx/apache.
