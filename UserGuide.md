Access Ubuntu from command line (PowerShell)
- wsl -l -v   #check ubuntu version on PC/Laptop
- wsl -d Ubuntu-20.04
- If type "exit" while using Ubuntu, it would be logout

![Screenshot 2022-12-18 161448](https://user-images.githubusercontent.com/69444682/208290249-1cadb46c-6ddb-4768-af5a-00d115de2a7b.jpg)


Terminate virtual machine
- wsl -l -v #check current the state of this virtual machine
- wsl --terminate Ubuntu-20.04
- wsl -l -v #check again the current state of this virtual machine


Using PowerShell/CommandPrompt
- cd ./{PathToDirectory}
- dir

