# wallsetter
A simple live wallpaper setter for linux written in bash 
### working :
video input >> frames >> sets wallpaper

#### Dependencies :
* ffmpeg
  ```
  Arch based : sudo pacman -S ffmpeg
  Debian based : sudo apt install ffmpeg
  ```
 * nitrogen
   ```
   Arch based : sudo pacman -S nitrogen
   Debian based : sudo apt install nitrogen
   ```
#### Usage :
```
git clone $this_repo
Copy any short video to $this_repo clone
./wallsetter extractor
```

#### Note:
```
try with videos < 1 min
cuz short videos == lesser frames to extract
```

#### Preview:
<iframe width="560" height="315" src="https://www.youtube.com/embed/smD4KK-v5fA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---------------------------------------------------------------------------------------------------------------------------------------------------------
