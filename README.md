# libogg-vobisとかの静的ライブラリビルドプロジェクト

## 手順

### liboggとlibborvisをダウンロード

http://www.xiph.org/downloads/

### リネームと配置

解凍したlibogg-x.x.xをliboggにする。
解凍にフォルダが作られ、libogg-x.x.x\libogg-x.x.xとなっている場合は、中にあるものを使う。

libvovisも解凍し、ファイル名からバージョンを取り除き、その中にliboggを入れる。

端的な話、次のような状態になれば良い。

libvorbis\include が存在
libvorvis\libogg\include が存在

libvorbis\libogg\win32\VS2015\とlibvorbis\win32\VS2015\内にプロジェクトがあるのでビルド。
