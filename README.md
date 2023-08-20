# asapp-2b

## Git Setup
1. Open VSCode (or another text editor)
2. Open the terminal
3. Change the directory to where you want to download the Git Repo: 
> cd "Desktop" --> if you want the folder to be downloaded onto your "Desktop"
4. Clone the Git Repo:
> git clone https://github.com/graceli458/asapp-2b
5. Change directory into cloned repo: 
> cd asapp-2b
6. Checkout your branch
> git checkout "yourname"
7. Add gitignore file
> touch .gitignore
8. Create a "data" folder to hold the json file: https://github.com/asappresearch/abcd/blob/master/data/abcd_v1.1.json.gz
9. Add "data" to .gitignore file
> add this line to .gitignore "data"

### To add code
1. Make sure you are in the "asapp-2b" folder on your local computer
2. git checkout "yourname"
> git checkout grace
3. make changes/edits
4. git add .
5. git commit -m "message with details on that changes/edits you made"
6. git push 
