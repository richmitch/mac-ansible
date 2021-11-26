# mac-ansible
Default installation for my mac

To Do
- Write a proper README.md for how to use this role
- Add a proper changelog
- Add validation of the Mac default settings before attempting to set them
- Add checks for applications that are already installed (or force install)

Done
- Change vars/main.yml so that there is a single dictionary for all the vars (use absent to remove)