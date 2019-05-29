# Images

for f in *.jpg; do magick "$f" -resize 800x800 -flatten "small/${f%.jpg}_sm.jpg"; done

for f in *.jpg; do magick "$f" -resize 300x300 -flatten "thumbs/${f%.jpg}_th.jpg"; done
