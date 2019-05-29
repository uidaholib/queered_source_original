# Images

for f in *.jpg; do magick "$f" -resize 800x800 -flatten "small/${f%.jpg}_sm.jpg"; done

for f in *.jpg; do magick "$f" -resize 300x300 -flatten "thumbs/${f%.jpg}_th.jpg"; done

# YouTube

main image:
https://img.youtube.com/vi/{{ page.youtube }}/0.jpg
thumbs:
https://img.youtube.com/vi/{{ page.youtube }}/1.jpg
https://img.youtube.com/vi/{{ page.youtube }}/2.jpg
https://img.youtube.com/vi/{{ page.youtube }}/3.jpg

highquality, http://img.youtube.com/vi/<insert-youtube-video-id-here>/hqdefault.jpg 

md quality no black, https://img.youtube.com/vi/KXObIJnV1_w/mqdefault.jpg 

max, https://img.youtube.com/vi/KXObIJnV1_w/maxresdefault.jpg
