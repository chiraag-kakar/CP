# My Competitive Programming Guide
---
## Sublime Text 3 Package Control Installation:
* Open Sublime Text editor
* Click on the file option 
* Click on Save as option 
* Make sure you change the storage location to the required directory 
* Then save the file as first.php 
* Then write this code 
```php
 <?php
echo "Hello Sublime";
?>
```
* After that go to this link packagecontrol.io

* Then click on the installation bar which appears in the right corner of your window.

* After that you will find another  page open where some code will be written in a editor unde Sublime Text 3.

* Select it and copy it.

* Then again go to sublime.

* Press ctrl + '~' 

* You will find a small shell console below there in the empty text field.

* Paste the code you have copied and press enter.
```text
Package Control will be enabled.
You can find it in the Preferences bar of Sublime Text Editor.
```
---
## Sublime Text 3 C++ Setup :

* Click on Tools then select layout->3 columns
* Then again Click on Tools->groups->Max Columns 2

Save the files name.cpp , input.txt & output.txt files in the same directory not necessarily it has to be in the desktop.

```C++
#include <bits/stdc++.h>
using namespace std;

int main() {
	#ifndef ONLINE_JUDGE
	//for getting input from input.txt
	freopen("input.txt","r",stdin);
	//for getting output to output.txt
	freopen("output.txt","w",stdout);
	#endif

	int n;
	cin>>n;
	cout<<n;
}
```


```bash
{
 "shell_cmd": "g++ -std=c++14 \"${file}\" -o \"${file_path}/${file_base_name}\" && \"${file_path}/${file_base_name}\"",
     "file_regex": "^(..[^:]):([0-9]+):?([0-9]+)?:? (.)$",
     "working_dir": "${file_path}",
     "selector": "source.c, source.c++",
     "variants":
     [
     	
       {
         "name": "Run",
        "shell_cmd": "g++ -std=c++14 \"${file}\" -o \"${file_path}/${file_base_name}\" && \"${file_path}/${file_base_name}\""
       }
     ]
    }
```

* After these steps save the build file named as C++14.sublime-build and close it.
* After that select the C++14 build system .

* To run the code enter the input case in input.txt file and press ctrl+b .

* But when we run the C++ file in sublime text , there appears an error message : "g++ is not recognized as internal or external command".

* To solve this issue you simply need to copy the path of the bin folder under MinGw to the "Path" variable in User Environment variable.
* Give a "/" if you are adding there are already some paths added.
---
## Restart the Sublime Text and run the Program , it will now execute without producing any errors. 


