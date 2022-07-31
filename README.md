# Medias

## Vidéos

Pour vos vidéos encodez-les de préférence en AV1 ou en VP9

si vous possédez ffmpeg les commandes les plus adaptées sont :

```
# AV1
ffmpeg -i input.mp4 -c:v libsvtav1 output.webm

#VP9
ffmpeg -i input.mp4 -c:v libvpx-vp9 output.webm
```

## Images

Pour vos vidéos encodez-les de préférence en AVIF ou en WEBP
