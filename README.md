# How-to-Setup-Conda-Environment-in-Ubuntu

1. Download Anaconda from it's official website in Download folder.
   ![anaconda_download](https://github.com/user-attachments/assets/bc630393-b5bb-4af0-996d-e13b5d8086ef)

2. Open Terminal from 'Downloads' and run
   
   <b>sudeep@sudeep-Precision-5820-Tower:~/Downloads$ bash Anaconda...</b> (press Tab, it will auto complete it).
   ![install_anaconda](https://github.com/user-attachments/assets/e10f782c-f747-4c1b-80c4-3d2267de3255)

   
5. A file will be created at the location where it was installed with 'anaconda3' filename.
	
   
7. To Add Anaconda to Your PATH:
	Press Ctrl+H to see hidden file.
	Look for file '.bashrc', open it with text editor and add "export PATH="$HOME/anaconda3/bin:$PATH"" in the end of 	the file.
8. Save the file and exit.
9. Open terminal check 'conda --version', it will display conda version.
10. To activate the base environment by default, type "conda activate base".
11. If it shows error like: "CondaError: Run 'conda init' before 'conda activate'", then type "conda init".
12. Then type "source ~/.bashrc"
13. Type "conda activate base"
14. Now you can create your own environment using "conda create --name my_env".
