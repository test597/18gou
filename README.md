人造棋士18号のバイナリファイル

　バイナリファイルは、Windowsバイナリとして以下のバージョンを用意しました。
　将棋所やShogiGUI等のGUIのエンジン登録方法等は、やねうら王のサイトを参考にしてください。

　探索エンジン用

　　18gou-tournament.exe		AVX2用のバイナリ
　　18gou-tounament-sse42.exe	SSE4.2用のバイナリ

　　Msys2/clangでビルドした、トーナメント用のバイナリです。VSでビルドしたものより数%ぐらいは
　　高速に動作します。
　　ご自分の環境に合わせたバイナリを、18.exeにリネームしてご利用ください。


　学習、評価値分析/操作用

　　18gou-learn.exe				AVX2用バイナリ
　　18gou-learn-sse42.exe		SSE4.2用バイナリ

　　Msys2/g++でビルドした、学習、評価値分析/操作用バイナリです。
　　Msys2/clangでビルドしたものを提供したかったのですが、諸事情でOpenMPの利用にDLLが必要になって
　　しまうため、g++でビルドしてあります。ですので、学習時のパフォーマンスは若干落ちています。
　　それはイヤ！という方は、clang+OpenMPの環境を用意して、ソースからビルドしてください。

　　こちらのバイナリは、GUIに登録して使うのではなく、実行ファイルをダブルクリックして実行するなり、
　　バッチファイルから呼ぶなりしてご利用ください。

　　学習部、評価値分析/操作の説明は、「18gou.txt」を参照願います。
