
# OverTheWire Bandit

## Challenge Overview

**Platform:** OverTheWire  
**Category:** Linux / Command Line  
**Difficulty:** Beginner  
**Status:** Completed

### Objective

The objective of this challenge was to connect to the Bandit server using SSH and locate the password required to access the next level.

### Tools Used

- Kali Linux
- SSH
- Linux terminal

### Practical Walkthrough

**Step 1: Establishing an SSH connection**

I connected to the Bandit server using SSH.

``` bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

**Step 2: Exploring the environment**

After successfully connecting, I explored the available files and directories.

```bash
ls
```

**Step 3: Reading the target file**

I used the `cat` command to display the contents of the relevant file.

```bash
cat readme
```

### Concepts Learned

- Secure Shell (SSH)
- Linux command-line navigation
- Reading files using `cat`
- Understanding remote Linux environments

### Challenges Encountered

Document any errors, difficulties or unexpected behaviour experienced during the exercise.

### Key Takeaways

This exercise introduced me to remote Linux environments and demonstrated how SSH can be used to securely access a remote machine.

### References

- [OverTheWire Bandit](https://overthewire.org/wargames/bandit/)
