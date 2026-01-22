#100-Days-DevOps #Linux
**What did I learn from this task?**

**Basic Linux User Administration**
- User and group concepts in Linux
- The `useradd` command
- The difference between **interactive shells** and **non-interactive shells**
- Use of shells such as `/sbin/nologin` or `/bin/false`
- User verification in files such as `/etc/passwd`
- Basic SSH access concepts on Linux servers

### Referênces:
https://www.geeksforgeeks.org/linux-unix/shell-scripting-interactive-and-non-interactive-shell/
### Courses Help Me:
https://learn.kodekloud.com/user/courses/learning-linux-basics-course-labs
### Studys:
[[Shell Scripting - Interactive and Non-Interactive Shell]]
### Important commands:

**SSH into Host:**
`ssh user@host`

**Create user um home and no-intective shell:**
`sudo useradd -m -s /sbin/nologin mariyam

**Set Password:**
`sudo passwd mariyam

**Verify the user and shell:**
`getent passwd mariyam
output: 
`mariyam:x:100X:100X::/home/mariyam:/sbin/nologin

username:x:UID:GID:GECOS:login_shell

