﻿# Learning OpenCV 3 책자 소스 사이트


원래 책자의 소스는 [oreillymedia GitHub]( https://github.com/oreillymedia/Learning-OpenCV-3_examples )에서 받을 수 있습니다. 
해당 GitHub는 책을 번역하는 과정에서 소스의 버그와 MSVC2015 버전에 맞게 프로젝트 파일과 데이터의 경로를 일부 변경했습니다.
자세한 소스 컴파일 및 프로젝트를 만드는 과정은 동영상으로 녹화 예정입니다.

# 컴파일 환경 구축
동일한 msvc 버전으로 컴파일한 의존 라이브러리를 다운받은 github 폴더의 상위 폴더에 다음과 같은 폴더를 구성해준다.

* __bin 폴더(250MB(openCV만)~600MB(QT추가))__

의존한 라이브러리에서 만들어진 dll 파일이 한 곳에 모인 폴더, 

* __install 폴더(300MB 이하 용량)__

>1. OpenCV의 install 프로젝트로 컴파일된 결과 폴더(include 폴더와 lib 폴더)
>2. WITH_QT 항목을 체크하면 QT 폴더가 필요하다.(9장 예제에서 사용)
>3. OPENCV_ENABLE_NONFREE 옵션을 체크한다.(16장 예제에서 사용)
>4. WITH_OPENGL 옵션 체크한다.(9장 예제에서 사용)


* __QT\msvc2015 폴더__

QT를 설치한 폴더에 mscv2015 폴더를 그래도 복사해준다. (x86버전) (9장 예제에서 사용), 10GB 용량.


* __WTL 폴더(5MB 이하)__

설치된 WTL 폴더를 그대로 복사해준다. (9장 예제에서 사용), 


* __wxWidgets 폴더(컴파일후 4GB 용량.)__

wxWidgets를 컴파일해서 폴더 전체를 복사해준다. (9장 예제에서 사용) .
## 관련링크
- [유튜브 강의 동영상](https://www.youtube.com/playlist?list=PLUDq35yka-fuPQGJi1m1cuCFZ914sDT1S)
- [스터디 그룹](https://www.facebook.com/groups/OpenCPP/)


## 참여자
#### 윤훈남, 나명진, [신재익](https://jishin86.github.io/about), [유원상](https://github.com/yws6909)
<div float="left">
  <img src="./imgs/2.jpg" width="20%" height="20%" />
  <img src="./imgs/3.jpg" width="20%" height="20%" />
   <img src="./imgs/4.jpg" width="20%" height="20%" />
  <img src="./imgs/1.jpg" width="20%" height="20%" />
</div>
