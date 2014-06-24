test
====

テスト用です


``` js
pres = document.getElementsByTagName('pre')
        len_pres = pres.length
        for (var i = 0; i < len_pres; i++) {
            var pre_html = pres[i].innerHTML
                pre_html = pre_html.replace(/aaa/g, '<a href="#" style="color:#ffa;">aaa(2)</a>')
            console.log(pre_html)
            pres[i].innerHTML = pre_html
        }
```
