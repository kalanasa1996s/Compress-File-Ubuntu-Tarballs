# Compress-File-Ubuntu-Tarballs
Compressed and Extract File and Directory Using tar.gz and tar.bz2

Two types of Compress Formats

    1.tar.gz
    2.tar.bz2
    
example :

Create 2 directorys and 2 files

    mkdir dir1      touch file1
  
    mkdir dir2      touch file2


1). Compress File 1

    tar czvf file1.tar.gz file1
    
    (file1.tar.gz => compressed file name)
    
    (file1 => original file name)
    
    
# czvf

* c -> Create
* z -> g.zip
* v -> verbose
* f -> file


2).Compressed one and two files 
  
    tar czvf files.tar.gz file1 file2
    
3).Extract the files

    tar xzvf files.tar.gz -C /home/test/Desktop (File extract path)
    
4).Show Compressed Files (list)

  tar tzvf files.tar.gz
  
5).compressed file1, file2, dir1,dir2 ,(all)

    tar czvf all.tar.gz file1 file2 dir1 dir2 
    

-----------------------------------------------------------------------------------
# bz2

tar cjvf - > create
tar tjvf - > show list
tar zjvf - > unzip
  




