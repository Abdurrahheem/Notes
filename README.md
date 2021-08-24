# Notes


- rsync -avP 'ls -tr | head -n 100' <destination>
  
- ffmpeg -skip_frame nokey -i <videfilename> -vsync 0 -f image2 <folder_name>/<any_prefix>-%06d.png
