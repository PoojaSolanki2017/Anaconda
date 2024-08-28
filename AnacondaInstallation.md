## For the Anaconda installation steps, please follow these steps


### Download Anaconda for Linux

-> Find an appropriate Anaconda installation version from https://repo.anaconda.com/archive/ . For example, 

    Anaconda3-2024.06-1-Linux-x86_64.sh

-> Install with 
    
    curl -O https://repo.anaconda.com/archive/Anaconda3-2024.06-1-Linux-x86_64.sh

-> Review the license agreement

    bash <PATH_to_Anaconda_Installer>/Anaconda3-2024.06-1-Linux-x86_64.sh

-> Press **Enter** to review the license agreement. Then press and hold **Enter to scroll**. Enter **yes** to agree to the license agreement.

-> Use **Enter** to accept the default install location, use **CTRL+C** to cancel the installation, or enter another file path to specify an alternate installation directory. 

-> If you accept the default install location, the installer displays **PREFIX=/home/<USER>/anaconda3** and continues the installation. **It may take a few minutes to complete.**

-> Once installation is completed, this instructions could be seen
    Preparing transaction: done
    Executing transaction: done
    installation finished.

-> Activate conda environment by
    
        source <PATH_TO_CONDA>/bin/activate

-> Close your current shell terminal and re-open it to see the changes. 


Reference : [Anaconda Installation](https://docs.anaconda.com/anaconda/install/linux/)

