We started with files that where available to the public via:
```
wget -r 198.82.18.138 &&\
mv 198.82.18.138 htdocs &&\
cd htdocs ;\
# because wget does not run the JavaScript that loads these files:\
wget 198.82.18.138/floor1.jpg ;\
wget 198.82.18.138/floor2.gif ;\
convert floor2.gif floor2.png ;\
wget 198.82.18.138/floor3.jpg ;\
wget 198.82.18.138/floor4.jpg ;\
```

and so on.   We made lots more edits, but that's where we started.

