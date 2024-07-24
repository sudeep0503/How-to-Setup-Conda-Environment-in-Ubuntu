# How-to-Setup-Conda-Environment-in-Ubuntu

1. Download Anaconda from it's official website in Download folder.
   ![anaconda_download](https://github.com/user-attachments/assets/bc630393-b5bb-4af0-996d-e13b5d8086ef)

2. Open Terminal from 'Downloads' and run
   
   <b>sudeep@sudeep-Precision-5820-Tower:~/Downloads$ bash Anaconda...</b> (press Tab, it will auto complete it).
   
5. A file will be created at the location where it was installed with 'anaconda3' filename.
6. To Add Anaconda to Your PATH:
	Press Ctrl+H to see hidden file.
	Look for file '.bashrc', open it with text editor and add "export PATH="$HOME/anaconda3/bin:$PATH"" in the end of 	the file.
7. Save the file and exit.
8. Open terminal check 'conda --version', it will display conda version.
9. To activate the base environment by default, type "conda activate base".
10. If it shows error like: "CondaError: Run 'conda init' before 'conda activate'", then type "conda init".
11. Then type "source ~/.bashrc"
12. Type "conda activate base"
13. Now you can create your own environment using "conda create --name my_env".
