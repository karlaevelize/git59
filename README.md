## WHAT IS GIT FOR?

- Version control
- Collaborating

## GIT COMMANDS

- git init (only once)
- git status (gst)
- git add .
- git commit -m "message"
- git remote add origin git@github.com:karlaevelize/git59.git (only once)
- git push origin master (ggpush)
- git remote -v (see to which repo it's connected)

## GIT FLOW

**First upload**

1. git init (once)
2. git add .
3. git commit -m "your message here"
4. git remote add origin YOUR-ORIGIN (once)
5. ggpush 

**And then**

1. git add .
2. git commit -m "your message"
3. git push

## IGNORING

- Ignore secre files
- Node-modules

1. Create a file called git ignore `touch .gitignore`
2. Write the files/folder you want to ignore in it