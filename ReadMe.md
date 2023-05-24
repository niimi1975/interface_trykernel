﻿# Interface 2023年7月号 特集「ゼロから作るOS」配布プログラム
## 概要
本リポジトリは、CQ出版(株) Interface 2023年7月号の特集「ゼロから作るOS」の配布プログラムです。  
特集記事にて記載した自作OS「Try Kernel」のプログラムです。ラズパイPicoにて動作します。プログラムの内容、開発環境や手順については記事をご覧ください。  
特集の各部、各章で作成した完成プログラムのソースコードを以下のディレクトリに格納しています。ディレクトリ毎に実行プログラムをビルドすることができます。part_5が完成したTry Kernelのプログラムとアプロケーションとなります。  

part_2         第2部  
    ├ sect_3    第3章  
    └ sect_4    第4章  

part_3         第3部  
    ├ sect_1    第1章  
    ├ sect_2    第2章  
    └ sect_3    第3章  

part_4         第4部  
    ├ sect_1    第1章  
    ├ sect_2    第2章  
    └ sect_3    第3章  

part_5         第5部  

## ライセンスについて
本プログラムはMITライセンスの下でオープンソースとして公開します。著作権および許諾表示を記載すれば、非営利、商用を問わず、使用、改変、複製、再頒布が可能な制限の緩いライセンスですので、本プログラムをOSの自作に活用いただけたらと思います。ライセンスの詳細については、同梱のLICENSE.TXTをご参照ください。  
ただし、ブートコードの一部でPico C/C++ SDKのオブジェクトコードを利用してますので、それについてはPico C/C++ SDKのライセンスが適用されます。ソースファイルの冒頭に記載したライセンスに従ってください。このライセンスも厳しい制約はありません。該当するファイルは以下です。  

part_2\sect_3\boot\boot2.c  
part_2\sect_4\boot\boot2.c  
part_3\sect_1\boot\boot2.c  
part_3\sect_2\boot\boot2.c  
part_3\sect_3\boot\boot2.c  
part_4\sect_1\boot\boot2.c  
part_4\sect_2\boot\boot2.c  
part_4\sect_3\boot\boot2.c  
part_5\boot\boot2.c  
