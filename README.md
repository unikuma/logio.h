# logio.h

## logio.hとは
logio.hはログを吐き出すためのライブラリです。<br>
ちなみにioをついていますがまだアウトプットしかできません。

## 使い方
test.c
```c
//logio.hをインクルード
#include "logio.h"
#pragma comment(lib,"logio.lib")

int main(void){
    LogWrite("sample.txt","HelloWorld")
    return 0;
}
```
```
cl test.c
```
* sampleフォルダ
    * test.exe
    * test.dll

VisualStudioでの使い方は調べてください。

## 作者
https://twitter.com/unikuma_sub
