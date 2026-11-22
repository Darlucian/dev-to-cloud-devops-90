# Week 2/13 recap

**Dates:** Mon, Nov 16 - Sun, Nov 22 (this recap covers Days 8 to 13)

## Learned (3 things, plain English)
1. **How the Linux shell works.** The shell is a program that lets me talk to the operating system by typing commands. I practised `bash`, `pwd`, `mkdir`, `touch` and `file`, and created and edited my first file entirely in the terminal with `touch` and `nano`.
2. **Users, groups and `sudo`.** Linux identifies users and groups with numbers (UID and GID). I learned how groups are managed, how `sudo` works with configured permissions and policies, and how to read system files like `/etc/group` (local groups) and `/etc/shadow` (password-related account information).
3. **File permissions, in depth.** Read, write and execute permissions, ownership, `umask` (default permissions for new files), and the special bits: SetUID (run with the file owner's privileges), SetGID (keep group ownership in shared folders) and the sticky bit (control who can delete files in shared directories).

## Built
- My first file created and edited entirely from the terminal
- Daily notes for Days 8 to 13 in my public learning log: github.com/Darlucian/dev-to-cloud-devops-90
- Portfolio redesign in progress: design, structure and presentation, to showcase new projects and support my freelancing

## Broke (and how I fixed it)
- **Day 9: the labs overwhelmed me.** Fix: I slowed down and completed one lab properly instead of rushing through all of them.
- **Day 10: I struggled with a few practical exercises in class.** Fix: I kept practising them and worked on the concepts that made sense afterward.
- **Day 12: octal permission values like `4755`, `2755` and `1777` confused me.** Fix: I broke them down as special digit + owner + group + others, using read = 4, write = 2, execute = 1 (written up in my Day 12 note). Still practising.
- **Days 11 and 13: I skipped hands-on labs** to work on my portfolio. Fix: I'll make up those labs next week.

## Numbers
- Daily posts published: 6 (Days 8 to 13)
- Daily notes written: 6
- Labs: 1 completed properly (Day 9), plus hands-on practice on Days 8 and 10
- Classes attended: 1 (Day 10); classes were cancelled later in the week

## Next week
- Week 3 plan: networking fundamentals and more Bash
- Classes on Wed, Nov 25 and Sat, Nov 28
- Make up the Linux labs I skipped, with a fixed time on the calendar
- Keep practising octal permissions until I can read `644`, `755`, `4755` and `1777` without notes

## Where I need help
- How do you explain octal permissions to someone learning Linux?