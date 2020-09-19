[ja](./README.ja.md)

# Shell.SeatingChart.20200919163455

Randomly generate a seating chart.

# DEMO

![demo](https://github.com/ytyaru/Shell.SeatingChart.20200919163455/blob/master/demo/demo.png?raw=true)

# Features

* Display in HTML using `zenity`
* 40 people (8 columns, 5 rows)
* Male-female ratio 1: 1
* Full name of Japanese name
* Arranged from top left to bottom right in order of name (attendance number)
* Color-coded with blue for men and red for women

# Requirement

* <time datetime="2020-09-19T16:34:52+0900">2020-09-19</time>
* [Raspbierry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 4 Model B Rev 1.2
* [Raspbian](https://ja.wikipedia.org/wiki/Raspbian) buster 10.0 2019-09-26 <small>[setup](http://ytyaru.hatenablog.com/entry/2019/12/25/222222)</small>
* bash 5.0.3(1)-release

```sh
$ uname -a
Linux raspberrypi 4.19.97-v7l+ #1294 SMP Thu Jan 30 13:21:14 GMT 2020 armv7l GNU/Linux
```

# Installation

```sh
cd /tmp
git clone https://github.com/ytyaru/Shell.StudentNameListGenerator.20200919160912
git clone https://github.com/ytyaru/Shell.SeatingChart.20200919163455
```

# Usage

```sh
cd Shell.SeatingChart.20200919163455/src
/tmp/Shell.StudentNameListGenerator.20200919160912/src/sn.sh | ./tsv2html.sh
```

# Author

ytyaru

* [![github](http://www.google.com/s2/favicons?domain=github.com)](https://github.com/ytyaru "github")
* [![hatena](http://www.google.com/s2/favicons?domain=www.hatena.ne.jp)](http://ytyaru.hatenablog.com/ytyaru "hatena")
* [![mastodon](http://www.google.com/s2/favicons?domain=mstdn.jp)](https://mstdn.jp/web/accounts/233143 "mastdon")

# License

This software is CC0 licensed.

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.en)

