## rename file X_en.srt to X.srt 
```shell
#first go to dir and lunch git bash
for file in *.srt; do
    new_name=$(echo "$file" | sed 's/_en//')
    mv "$file" "$new_name"
done
```

 
# ASP  `A`ctive `S`erver `P`ages
### IDE [`I`ntelligent `D`evelopment `E`nviroment] useful shortcut keyBoard
|vscode|description| 
|------------|-----------| 
|<kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>Arrow</kbd> key|copy line| 
|<kbd>Ctrl</kbd>+<kbd>]</kbd> and <kbd>Ctrl</kbd>+<kbd>[</kbd>|adjust indent| 
|<kbd>Alt</kbd>+<kbd>z</kbd>|break long line| 



 
#  Pascal Case
 
 