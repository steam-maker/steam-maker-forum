## 從印刷術到3D打印

### 印刷術

- [Wikipedia](printing_en.pdf) (PDF)
- [維基百科](printing_cn.pdf) (PDF)

印刷術的核心不是紙墨，而是複製。我們的祖先發明了活字印刷。但是印刷術的核心：分享，卻是讓西方人掌握了。

但是實際上可以說連[古滕堡](Gutenberg_cn.pdf) ([Gutenberg](Gutenberg_en.pdf))也沒有看到印刷術的「分享」這個顛覆性思想，一百五十年後歐洲才有了文藝復興。 

大眾文化，媒體傳播，地球村，[這些思想](Gutenberg_Galaxy.pdf)六十年代西方就有了。
六十年代後的計算機革命，七十年代的圖形界面，八十年代的個人電腦，九十年代的互聯網，二十一世紀的移動互聯網，都是一脈相傳的。
3D打印，VR，AR，AI都是今後五十年的科技進步的延續。 共享，山寨，創客，黑客，極客都是表面現象。 
核心是在新技術環境下新的社會生活和工作方式，其中分享文化和社會化分工合作尤其重要。

### 3D打印

大家看看誰能用**現代桌面瀏覽器**打開[這個文件](https://github.com/skalnik/secret-bear-clip/blob/master/stl/clip.stl)?
還有[這個](https://github.com/canadaduane/house/blob/master/kitchen/faucet/faucet_fix2.stl), 誰的3D打印機可以打出來？

3D打印的核心不在於硬件，而是[文件](https://help.github.com/articles/3d-file-viewer/)。還有更重要的，文件背後的設計思想。

其實大家可以這個[文件](https://github.com/gklyne/things/blob/master/ServoBox/Servobox.stl)的[源代碼](https://raw.githubusercontent.com/gklyne/things/master/ServoBox/Servobox.stl)見看看裡面的片段，

```stl
solid OpenSCAD_Model
  facet normal -1.000000 -0.000000 -0.000000
    outer loop
      vertex -5.500000 11.000000 0.000000
      vertex -5.500000 11.000000 4.000000
      vertex -5.500000 23.000000 0.000000
    endloop
  endfacet
  ...
endsolid OpenSCAD_Model
```

這樣的文件是學習幾何的最好工具。[vertex](vertex.pdf)和[facet](facet.pdf)都是立體幾何的核心概念。
只有幾何才能保證三十年後還不會過時。

