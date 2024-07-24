# How-to-Setup-Conda-Environment-in-Ubuntu

1. Download Anaconda from it's official website in Download folder.
   ![anaconda_download](https://github.com/user-attachments/assets/bc630393-b5bb-4af0-996d-e13b5d8086ef)

2. Open Terminal from 'Downloads' and run
   
   <b>sudeep@sudeep-Precision-5820-Tower:~/Downloads$ bash Anaconda...</b> (press Tab, it will auto complete the file name).
   ![install_anaconda](https://github.com/user-attachments/assets/e10f782c-f747-4c1b-80c4-3d2267de3255)

   
3. A file will be created at the location where it was installed with 'anaconda3' filename.
   	![bashfile](https://github.com/user-attachments/assets/f60a3607-193b-4099-a8a9-303329fb796d)

7. To Add Anaconda to Your PATH:
	Press Ctrl+H to see hidden file.
	![bashfile](https://github.com/user-attachments/assets/9b8b9866-9fa2-49d5-b445-ecbebc97a2d2)

	Look for file '.bashrc', open it with text editor and add "export PATH="$HOME/anaconda3/bin:$PATH"" in the end of the file.
	![bashfile_edit](https://github.com/user-attachments/assets/b9d960cf-9fb1-4a58-8a76-a31e330af1ec)

5. Save the file and exit.
6. Open terminal check 'conda --version', it will display conda version.
    ![conda_version](https://github.com/user-attachments/assets/9908de63-a21f-4da6-8fda-ce0d9a02b051)

7. To activate the base environment by default, type "conda config --set auto_activate_base true".
   ![image](https://github.com/user-attachments/assets/762d9544-8936-44cb-acca-8520c074479f)
   and exit terminal.
9. THen type, "conda activate base"
10. If it shows error like: "CondaError: Run 'conda init' before 'conda activate'", then type "conda init".
11. Then type "source ~/.bashrc"
12. Type "conda activate base"
    
13. Now you can create your own environment using "conda create --name my_env".
14. Say "Yes" to every permissions.
15. To activate your envinroment: "conda activate my_env"
