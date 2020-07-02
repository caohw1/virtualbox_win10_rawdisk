# virtualbox_win10_rawdisk

1. create vmdk of raw drive

   run cmd as administrator, run "C:\Program Files\Oracle\VirtualBox\VBoxManage.exe"   internalcommands createrawvmdk -filename your_file_name.vmdk -rawdisk \\.\PhysicalDrive0
   
2. run virtualbox as administrator, create virtual machine with your_file_name.vmdk

3. run virtualbox as administrator, run virtual machine
