# ibus-victory-bn
Ibus layout for [Bijoy](https://en.wikipedia.org/wiki/Bengali_input_methods#Bijoy), in ANSI and Unicode.

## Overview
Typing in Bangla in ANSI is always a problem. Typing it in Linux adds another level of complexity. This repository holds mim file to write Bangla just like writing in properitory OSes.
Here is layout corresponding the Bijoy classic and unicode. It uses the same backend as linux version of [Avro](https://en.wikipedia.org.wiki/Avro_Keyboard) [ibus-avro](https://linux.omicronlab.com), [Ibus](https://github.com/ibus/ibus)

## Disclaimer
I didn't write the mim files. They were collected from [here](https://web.archive.org/web/20201229055025/https://www.facebook.com/groups/linux.loverz/permalink/675008252586806)
I just modified a little bit
## note:
1. in e kar there was a problem that soace ekar was joining 2 word and so i changed space c for matra less ekar to c space matra less ekar same goes to oikar and ' to ' 

## Requirements
1. Ibus
2. Ibus-m17n
## note
i would recommend you to buy the real version from Ananda Computers and take the font from there them use this software to install instead of their software as that has so many mistakes.
## Usage
1. Download the repo (optional: if you want bijoy fonts to install coppy your bijoy fonts to fonts folder)
2. Run the script (install.sh) and give password
3. Add the layouts
  > ibus-setup => Input Method => Add => More => Bangla => bijoyClassic
4. Enjoy

## Known Issue
 LibreOffice cannot detect font when used with ANSI. Manually change the font. [Here](https://www.omicronlab.com/bangla-fonts.html) you can get some ANSI fonts.

## License
The layout is supposed to be licensed under [Copyright Act,2000](http://bdlaws.minlaw.gov.bd/act-details-846.html)([English](https://www.clcbd.org/document/577.html)). But according to upstream, the linux version is free to use for personal use (see the [comments](https://www.facebook.com/groups/linux.loverz/permalink/675008252586806)).

The use of this properitory layout is controversial since its inception. The involved company seem to have a very complicted policy. For instances, they suppose to provide a [linux version of their product](https://bijoyekushe.net.bd/index.php?action=software) for [free](https://www.facebook.com/mustafajabbar49/posts/2099386236859530) but tries to charge 100 BDT but that is not even available in [download page](https://bijoyekushe.net.bd/index.php?action=software_activation). They also has a page dedicated for [it](http://www.bijoyekushe.net/index.php?action=ekushe_linux) but provide no idea how to get that.

(For the starters, the developer is the minister of ICT and there exists a lot other options if one use Unicode, [see](https://openbangla.github.io/)).

I have no intention to infringing copyright. If any official notice is provided, I may take down this repository.
and ibus m17n is totally a opensource software.

P.S.: Multiligualization database [m17n-db](https://savannah.nongnu.org/projects/m17n/) include a slightly modified unicode layout under the name unijoy (Originally developed by Avro but later removed due to copyright claim).
