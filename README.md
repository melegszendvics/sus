# sus
### made by best programozó ever uwu
```py
import os

folder = input("Raw path: ")
files = os.listdir(folder)
count = 0
for file in files:
    if (file.startswith("sus")):
        os.rename(str(folder+"\\"+file), str(folder+"\\sus "+str(count)+".png"))
        count=count+1
```
