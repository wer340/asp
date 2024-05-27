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
|visual studio  |description| 
|------------|-----------| 
|<kbd>ctrl</kbd>+<kbd>d</kbd> |copy line| 
 
 



 
#  Pascal Case
 
 ## snippet code  in visual studio 

###  `prop`  make property
```
 public int MyProperty { get; set; }
```

###  `ctor`   make constructor
```
public ApplicationDbContext()
{
    
}
```