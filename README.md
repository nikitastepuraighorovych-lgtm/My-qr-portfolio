# About

My small creative twist on portfolio in a qr code 
based on CodeNerve project: https://github.com/CodeNerve/CodeNerve.github.io/tree/master
Minifier for html used: https://kangax.github.io/html-minifier/
Qr generator used: https://goqr.me

## Mac
```zsh
qrtool decode qrcode.png > NikitaStepura.html | open NikitaStepura.html
```

## Linux(change to your preferable browser)
```bash
qrtool decode qrcode.png > NikitaStepura.html && firefox NikitaStepura.html
```

## Windows cmd
```cmd
qrtool decode qrcode.png > NikitaStepura.html && start NikitaStepura.html
```

## Windows ps
```ps
qrtool decode qrcode.png > NikitaStepura.html; Start-Process NikitaStepura.html
```
