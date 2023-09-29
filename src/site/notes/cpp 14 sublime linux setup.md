---
{"dg-publish":true,"permalink":"/cpp-14-sublime-linux-setup/"}
---

```json
{
"cmd" : ["g++ -std=c++14 $file_name -o $file_base_name && timeout 4s ./$file_base_name<inputf.in>outputf.in"], 
"selector" : "source.c",
"shell": true,
"working_dir" : "$file_path"
}
```

- save the file as 
```C++14_linux.sublime-build```