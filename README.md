# random-scripts
useful shell scripts

# Setup
`$ chmod +x apath`
 `$ chmod +x rpath`

you may add these in your path variable via your **~/.bash_profile** file

## Usage of apath
- print Absolute Path of current directory.

`$ ./apath  `
-  print Absolute Path of arguments.

`$ ./apath file1.txt ../dir/file2.txt  `


## Usage of rpath
- if one argument, print relative path to current working directory.  

`$ ./rpath /etc/apache2/apache2.conf `
-  if more than one argument than prints relative path to last argument.

`$ ./rpath file.txt ../file2.txt /etc/passwd /etc/apache2`


