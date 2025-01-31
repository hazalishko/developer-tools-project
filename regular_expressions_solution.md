**Exercise 1**
'''bash
ls -d ~/[A-Z]*
'''

**Exercise 2**
'''bash
ls -d ~/.* 
'''

**Exercise 3**
'''bash
ls -d ~/.* | wc -l
'''

**Exercise 4**
'''bash
ls -d ~/[A-Za-z]*
'''

**Exercise 5**
'''bash
ls -d ~/[^A-Z]*
'''

**Exercise 6**
'''bash
ls -d ~/ | grep -vE '\.[a-zA-Z]{3}$'
'''

**Exercise 7**
'''bash
ls -d /etc/c*y
'''

**Exercise 8**
'''bash
ls /etc | grep 'ss'
'''

**Exercise 9**
'''bash
ls ~ | grep -E '^.(.[A-Z].){2}e$'
'''

**Exercise 10**
'''bash
ls ~ | grep -E '^[A-Za-z0-9]{4}$'
'''

**Exercise 11**
'''bash
ls /var/log | grep '\.log$'
'''
