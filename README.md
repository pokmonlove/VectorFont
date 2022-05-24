<h1 align="center"> 
🌦 날씨에 따른 한글 폰트 윤곽선 벡터 변형 알고리즘
<br> 
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white">
<img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=NumPy&logoColor=white">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=Jupyter&logoColor=white">
<img src="https://img.shields.io/badge/SVG-FFB13B?style=flat&logo=SVG&logoColor=white">
</h1>





## 📕 프로젝트 요약

|1️⃣|2️⃣|3️⃣|
|:---:|:---:|:---:|
|<img width="100%" src="https://user-images.githubusercontent.com/70003514/170021880-fcd08188-e089-43a6-a66b-bb0e76143595.png"/>|<img width="70%" src="https://user-images.githubusercontent.com/70003514/169716987-2706811a-0a88-4203-97f2-cd66576a757f.png"/>|<img width="100%" src="https://user-images.githubusercontent.com/70003514/170022980-af498ae2-2ee6-4060-b6bf-83e1b7ac237c.png"/>|

<h4 align="center"> 폰트 벡터화와 윤곽선 벡터 변형으로 날씨 폰트를 자동 생성하는 프로젝트입니다 </h4>

## 📗 프로젝트 배경 및 목적
* 상황 정보에 따라 바뀔 수 있는 벡터 폰트 기반의 한글 폰트 변형 기술의 개발 필요성
* 기존의 래스터 이미지가 아닌 벡터 데이터로 폰트를 변형하는 기술의 필요
* 폰트 벡터화를 통한 디자인 변형 기술을 적용하여 **텍스트를 보다 자유롭게 꾸미고 감성을 풍부하게 전달하고자 함**

## 📘 프로젝트 목표 
* **벡터 데이터 기반의 디자인 기술 활용**
  * 디자인을 자유롭게 조작할 수 있도록 폰트를 벡터화 후 변형 필요
  * 아웃라인(글리프)을 추출하여 다양한 디자인을 적용할 수 있는 방법을 시도하고자 함 
* **수치 정보에 따라 달라지는 직관적인 폰트 스타일 제공**
  * 미세먼지 농도, 자외선 농도와 같은 구체적인 기상 수치 정보를 활용
  * 각 데이터가 대표하는 날씨의 감성이 잘 반영되도록 스타일 설계

## 🌞 대표 디자인
|구름|습도|눈|
|:---:|:---:|:---:|
|&nbsp;&nbsp;<img width="90%" src="https://user-images.githubusercontent.com/70003514/169096899-3d86c146-57d1-45d4-936e-856c9b9d29be.png"/>&nbsp;&nbsp;|<img width="50%" src="https://user-images.githubusercontent.com/70003514/169098790-8e14e8f4-03e0-4e89-a741-eae4045ef652.png"/>|<img width="60%" src="https://user-images.githubusercontent.com/70003514/169718364-fb2dd368-80ad-48c2-8cfe-40f5a057af89.png"/>|
| 뭉게뭉게 부풀어오른 구름을 표현|습도가 높을 때의 끈적거림을 표현|눈과 눈사람이 동그랗게 쌓인 모습을 표현|

## 🌤 디자인 적용 전후 비교
|기상정보|디자인 적용 전|디자인 적용 후|
|:------:|:---:|:---:|
|[구름](Vectorfont/vectorfont_cloud.ipynb)|<img width="35%" src="https://user-images.githubusercontent.com/70003514/169712056-f959a84a-74f0-4081-8e8d-e2a985e3e0bf.png"/>|<img width="35%" src="https://user-images.githubusercontent.com/70003514/169713653-53a63223-46fd-43ce-9a98-44af8ee2a836.png"/>|
|[자외선](Vectorfont/vectorfont_ray.ipynb)|<img width="50%" src="https://user-images.githubusercontent.com/70003514/169712314-e802c7a3-3fc0-46bf-b0f8-bfdfb6e07672.png"/>|<img width="47%" src="https://user-images.githubusercontent.com/70003514/169713751-62f526ff-df30-4330-ad94-b6dcec87ea71.png"/>|
|[비](Vectorfont/vectorfont_waterdrop.ipynb)|<img width="50%" src="https://user-images.githubusercontent.com/70003514/169712605-0ef2fc4d-acfe-4ac4-8ed7-efab169dcc8e.png"/>|<img width="50%" src="https://user-images.githubusercontent.com/70003514/169712761-f0dca491-169b-4cf4-aa75-83112a4df3dd.png"/>|
|[눈](Vectorfont/vectorfont_snow.ipynb)|<img width="50%" src="https://user-images.githubusercontent.com/70003514/169713013-81e95de9-da2d-44af-8600-2a9d9c827223.png"/>|<img width="50%" src="https://user-images.githubusercontent.com/70003514/169712954-e99008a3-acb8-48ec-bfec-a42114f943e9.png"/>|
|[습도](Vectorfont/vectorfont_humidity.ipynb)|<img width="40%" src="https://user-images.githubusercontent.com/70003514/169713076-7f21a07c-6e92-42f3-991c-9497ccc8cff7.png"/>|<img width="40%" src="https://user-images.githubusercontent.com/70003514/169098790-8e14e8f4-03e0-4e89-a741-eae4045ef652.png"/>|
|[아지랑이](Vectorfont/vectorfont_haze.ipynb)|<img width="60%" src="https://user-images.githubusercontent.com/70003514/169713257-d549df59-4162-4a5b-b81e-388468387ee4.png"/>|<img width="60%" src="https://user-images.githubusercontent.com/70003514/169713237-9ad7e00e-e9cd-4949-bf54-024213d7484c.png"/>|
|[바람](Vectorfont/vectorfont_wind.ipynb)|<img width="40%" src="https://user-images.githubusercontent.com/70003514/169713411-e4293f62-4f62-4b97-8de8-66c3b5b40342.png"/>|<img width="35%" src="https://user-images.githubusercontent.com/70003514/169713362-b0d6729a-9508-430e-b331-99d8595f5416.png"/>|
|[먼지](Vectorfont/vectorfont_dust.ipynb)|<img width="40%" src="https://user-images.githubusercontent.com/70003514/169713479-e6865c2b-b4be-440c-b4ba-219d1a474dbe.png"/>|<img width="37%" src="https://user-images.githubusercontent.com/70003514/169713446-f131e927-289f-447b-9b9c-c4f90f5ac780.png"/>|

## 🎨 폰트 벡터화 및 디자인 과정
<img width="100%" src="https://user-images.githubusercontent.com/70003514/169715064-22a1c8e1-536b-4f28-b26d-c7adc3cefe2f.png"/>

 ① 디자인할 글자와 폰트를 불러옵니다.
<details>
<summary> 🔍 click! </summary>
<div markdown="1">
 
```python
f = font.open("fonts/font_file_name.ttf")
```
 </div>
</details>

② 불러온 글자를 벡터화시켜 글리프 묶음으로 변환합니다.
<details>
<summary> 🔍 click! </summary>
<div markdown="1">
 
```python
def glyphcommands(f, ch):
    return Path([copy(cmd) for cmd in f.glyph(f.charmap[ord(ch)])])

def advancefor(f, ch):
    return f.advances[f.charmap[ord(ch)]]
```
</div>
</details>

③ 글자를 이루는 각 글리프들의 방향을 알아냅니다. <br>
<details>
<summary>🔍 click</summary>https://github.com/pokmonlove/VectorFont/blob/5eaf1c8b9a342402268939638ea1012ddd1328de/Vectorfont/vectorfont_cloud.ipynb?short_path=01f60ac#L180-L214 </summary>
<div markdown="1">
</div>
</details>
④ 디테일한 디자인을 위해 글리프를 잘라 재구성합니다. <br>
⑤ 자른 글리프들을 2차 혹은 3차 베지어 곡선으로 변경합니다. <br>
⑥ 각 글리프의 방향과 디자인에 따라 글리프의 제어점을 이동시킵니다. <br>
⑦ 디자인을 적용시킵니다.


## ✅ 사용한 폰트
* [NanumSquareEB.ttf](https://hangeul.naver.com/2021/fonts/nanum)
* [TmoneyRoundWindExtraBold.ttf](https://www.tmoney.co.kr/aeb/cmnctn/ci/ci.dev)

## ✅ Install
이 프로젝트는 [`Bezmerizing`](https://github.com/aparrish/bezmerizing/) 라이브러리를 사용합니다.
```python
import sys
!{sys.executable} -m pip install --upgrade https://github.com/aparrish/bezmerizing/archive/master.zip
```

## ✅ Module & Packages

<details>
<summary> 🔍 click! </summary>
<div markdown="1">
 
```py
import math
import random
import numpy as np
from flat import document, rgb, rgba, font, strike, shape
from flat.command import moveto, quadto, curveto, lineto, closepath
from bezmerizing import Polyline, Path
from numpy.random import uniform, normal, choice
from copy import copy
from random import randrange
from IPython.display import SVG, displa
```
 </div>
</details>

## 💘 Inspired by 
 [Allison Parrish](https://www.decontextualize.com/)'s Notebook on [Manipulating Font Data](https://github.com/aparrish/material-of-language/blob/master/manipulating-font-data.ipynb)

[`Flat`](https://xxyxyz.org/flat) + [`Bezmerizing`](https://github.com/aparrish/bezmerizing/) 라이브러리를 이용한 폰트 벡터화 & 디자인

## 💬 References

## 👩‍💻 Authors
숙명여자대학교 대학원  | MINTLAB | 팀 오토폰트
* [김남희](https://github.com/pokmonlove) | 📧 kelly9455@sookmyung.ac.kr
* [박동연](https://github.com/DyeonPark) | 📧 yeon0729@sookmyung.ac.kr
* [조세란](https://github.com/shooshoo0329) | 📧 shooshoo329@sookmyung.ac.kr
----
