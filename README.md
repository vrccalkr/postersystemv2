# postersystemv2

## How to use
For normal users, just get the link `https://github.com/vrccalkr/postersystemv2/blob/main/poster.mp4?raw=true`

For update the poster, make a single script file like this to update easily
```
git pull
git add poster.mp4 # Add the poster image
git commit -m "Poster Update $(date +"%Y%m%d_%H%M")"
git push https://<USERNAME>:<PASSWORD>@github.com/vrccalkr/postersystemv2
```
