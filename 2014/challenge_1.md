# Challenge 1 : Bob Doge

Öncelikli olarak indirdiğimiz zip dosyasının içerisinden çıkan C1.exe isimli dosyamızın adını C1.zip yapalım ve içerisinde bulunan `Challenge 1` isimli exe dosyamızı çıkartalım.

Daha sonra dosyamızı `DIE` (Detect It Easy) aracımıza atıp inceleyelim

![DIE](img/1/1.png)

Henüz bu işlerde çok yeniyim ancak .NET gördüğümüz zaman `dnspy` aracını kullanmakta fayda olduğunu düşünüyorum (Belki başka püf noktalarda vardır, öğreneceğiz)

![dnspy](img/1/2.png)

Programımızın içerisinde bir adet form var. Bu formu incelediğimiz zaman `btnDecode_Click` isimli fonksiyon dikkatimizi çekecektir. Bunun içerisine bir adet breakpoint koyarak programımızı çalıştırırsak bakalım ne olacak.

Açılan ekranda `decode` et butonuna basalım ve...

![flare-on](img/1/3.png)

Bingo ! ilk text değişkenimizin içerisinde aramış olduğumuz adresi bulduk :)
