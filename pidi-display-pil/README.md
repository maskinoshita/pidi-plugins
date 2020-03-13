# PiDi Display Plugin for PIL-based image output

This plugin renders album art and transport information to a PIL image for display.

## Install Insturction

```bash
wget https://github.com/adobe-fonts/source-han-sans/raw/release/OTF/SourceHanSansJ.zip
unzip SourceHanSansJ.zip
rm SourceHanSansJ.zip
mv SourceHanSansJ /usr/share/fonts/opentype/

fc-cache -f -v
fc-list | grep SourceHanSans

sudo pip3 install -e "git+https://github.com/maskinoshita/pidi-plugins.git#egg=pidi-plugins&subdirectory=pidi-display-pil"
```
