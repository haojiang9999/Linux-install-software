# Linux-install-software
### Get the software from web
wget ftp// http// *****.tar.gz

wget ****.zip
### Unzip files
tar xvfz file.tar.gz

unzip file.zip
### Add $PATH to the linux
vim ~/.bashrc

export PATH=$PATH:/path/to/dir

:wq

source ~/.bashrc

### Get software from conda
conda install software
### Download SRA files using sratoolskit from NCBI
#### Configuring the Toolkit
Go to the "bin" subdirectory for the Toolkit and run the following command:
```
./vdb-config -i
```
re-set download folder
#### Download sra files
```
prefetch --option-file SRR_Acc_List.txt
```
Reference

https://www.cnblogs.com/ywliao/p/7356528.html

https://trace.ncbi.nlm.nih.gov/Traces/sra/sra.cgi?view=toolkit_doc&f=std
