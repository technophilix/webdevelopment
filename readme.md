You have to add a ssh or gpg key to authenticate git from your computer. Search in google “how to generate a ssh key for github” or go to link in the descriptions.

**Step 1: Create .ssh folder in “C:\User\Username” (in my case it is C:\User\Agniswar”) or anywhere you want. The create a conifg file in it for future. Just create a file named config. No extension, no ‘dot’.**

**Step 3: Copy the path of .ssh folder and paste it to git bash. then add your file name with a slash, ie “C:\Users\Agniswar\.ssh\technogit”. Then hit enter, It will ask for paraphrase (like password) give it or leave blank. Two file will generate. technogit and technogit.pub.**

**Step 4: Open config file and add this two line**
Host github.com
IdentityFile ~/.ssh/technogit

**Step 5: Copy the content of .pub file and paste it to github.com. You are almost done. They are secret keys, So all text are blured in this video.**

Now, to interact with github

1. Open git in your project and initialize git in your project root folder with <pre>git init</pre> command
2. Create a public repository at github. No need to add readme, gitignore or lisence file.
3.
