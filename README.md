<h1 id="gandom-font">Gandom Font</h1>
<p>A Persian (Farsi) Font</p>
<p dir="rtl">فونت (قلم) فارسی گندم</p>
<p dir="rtl"><a href="http://rastikerdar.github.io/gandom-font/">نمایش فونت</a></p>
<p dir="rtl">با تشکر از برنامه <a href="https://fontforge.github.io">FontForge</a></p>
<p dir="rtl">بر مبنای فونت <a href="http://rastikerdar.github.io/samim-font/" dir="rtl">صمیم</a></p>
<h2 id="-" dir="rtl">طریقه استفاده در صفحات وب:</h2>
<div lang="fa" dir="rtl">
کد زیر را در قسمت style یا فایل css وارد نمایید:
</div>


```css
@font-face {
  font-family: Gandom;
  src: url('Gandom.eot');
  src: url('Gandom.eot?#iefix') format('embedded-opentype'),
       url('Gandom.woff') format('woff'),
       url('Gandom.ttf') format('truetype');
  font-weight: normal;
}

@font-face {
  font-family: Gandom;
  src: url('Gandom-Bold.eot');
  src: url('Gandom-Bold.eot?#iefix') format('embedded-opentype'),
       url('Gandom-Bold.woff') format('woff'),
       url('Gandom-Bold.ttf') format('truetype');
  font-weight: bold;
}
```

## Install
#### Arch Linux

Arch user's could use [gandom-fonts](https://aur.archlinux.org/packages/gandom-fonts/) package from [AUR](https://aur.archlinux.org/) repository to install gandom font. Use your favourite [AUR helper](https://wiki.archlinux.org/index.php/AUR_helpers) like pacaur or yaourt for installing package:

```shell
pacaur -S gandom-fonts
```
