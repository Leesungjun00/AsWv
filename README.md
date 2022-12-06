# WebView
<url src ="https://leesungjun1.netlify.app/"></url>

<img src="https://user-images.githubusercontent.com/65274604/204462712-d4509789-2531-4e23-9fa5-3ba12fa01d4e.png" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="pf1"></img>
<h3>안드로이드 스튜디오로 만들었으며 나의 정보 웹 사이트를 웹뷰로 간단히 불러온다</h3>
<img src="https://user-images.githubusercontent.com/65274604/204462725-f865dfbc-5c65-4204-bd54-b87afdcaa1f6.png" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="pf2"></img>
<h3>안드로이드 스튜디오 웹뷰를 통해 만들었습니다. 간단한 행사장에서 뽑기를 뽑을때 쓰는 APK 입니다.</h3>
<img src="https://user-images.githubusercontent.com/65274604/204462726-696b018a-c4e8-427c-9c53-7cb205fc00fc.png" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="pf3"></img>
<h3>안드로이드 스튜디오 웹뷰로 만들었으며 간단하게 만든  회사 소개 홈페이지 입니다. 다른 사용자들도 편리하게 접속해서 최신 정보를 받을 수 있습니다.</h3>
<h7>서버와 클라이언트에 대해 기술하시오
 서버 : 다수의 클라이언트에게 서비스를 제공하기 때문에 고사양의 하드웨어를 갖춘 컴퓨터이지만, 하드웨어의 사양으로 서버와 클라이언트를 구분하는 것은 절대 아니며, 사양의 관계없이 서비스를 제공하는 소프트웨어가 실행되는 컴퓨터를 서버라고 한다.
 클라이언트 : 서버와 이어진 모든 기기(컴퓨터의 경우 WIFI / 모바일은 모바일 네트워크)와 단말기에서 이용하는 웹에 접근하는 SW이며, 주로 서버에 요청을 보내고 응답을 받는 역할을 한다.
﻿﻿﻿2. IP와 port에 대해 기술하시오
IP :  컴퓨터를 찾을 때 필요한 주소
Port :  컴퓨터가 각종 신호, 정보 등을 주고 받을 수 있도록 해주는 통신 통로
3. SPA와 MPA에 대해 기술하시오
Spa : 한 개(Single)의 Page로 구성된 Application이다.
Mpa : 여러 개(Single)의 Page로 구성된 Application이다.
﻿﻿﻿4. API와 open API에 대해 기술하시오.
API :  Application Programming Interface 의 줄임말으로 어떠한 응용 프로그램에서 데이터를 주고 받기 위한 방법을 의미한다. 오픈 API 와 비공개 API로 나누어지며 특정 사이트에서 특정 데이터를 공유 할 경우 어떠한 방식으로 정보를 요청하고 받을수 있는지에 대한
Open API : 여러 개(Single)의 Page로 구성된 Application이다.
﻿5. ﻿﻿세션과 토큰 로그인 방식에 대해 기술하시오.
세션 : 세션은 브라우저와 웹 서버가 연결되어 연결이 끊어질 때 까지를 뜻한다
토큰 : 토큰은 인증할 수 있는 일종의 확인서라고 생각하면된다
﻿﻿﻿6. 코르도바 하이브리드 앱을 만들기 위한 환경설정에 대해 기술하시오
1. JDK 설치
jdk-8u162-windows-x64.exe   

2. 아파치 앤트 설치하기
c:\HybridApp\폴더에 "apache-ant-1.9.16-bin.zip  download" 
알아서 풀기

3. Gradle 설치하기
c:\HybridApp\폴더에 "gradle-3.5.zip download"
알아서 풀기

8. 안드로이드 스튜디오 설치
8.1 가상 기계(AVD)는 "Nexus 5"나 "Nexus 5X" api 29 로 만드세요
8.2 안드로이드 플랫폼 패키지 추가 설치하기
SDK platforms
	Android 12L	32
	Android 12	31
	Android 11	30
	Android R	29
SDK Tools
	Android SDK Tools
	Android SDK Platfor-tools
	Android SDK Build-tools

Extra
	Android Support Repository
	Android Auto Desktop head unit emulator
	Android auto API simulator
	Google Repository
	Google USB Driver
	Google Play Services
	Android SDK Command-line Tools
	Intel x86 Emulator Accelerator(HAXM installer)

5. 환경 변수 설정하기(윈도우+x => 시스템=> 고급시스템설정)
JAVA_HOME 		c:\progrqm files\java\jdk1.8--
ANDROID_SDK_ROOT	C:\Users\608\AppData\Local\Android\android-sdk
GRADLE_HOME		C:\gradle-3.5

Path 
	%JAVA_HOME%\bin;
	%ANDROID_HOME%\tools
	%ANDROID_HOME%\platform-tools
	%ANDROID_HOME%\build-tools
	%ANDROID_HOME%\cmdline-tools\latest\bin
	%ANDROID_HOME\emulator
	%GRADLE_HOME%\bin
	c:\HybridApp\apace-ant-1.9.16\bin
6. Node.js 설치하기
"node js 설치" 검색 후 다운로드
>node -v
>npm -v
>npm update -g

7. 폰갭(코르도바 설치하기)
>npm install -g phonegap
>npm install -g cordova
>cordova -v
>npm update -g phonegap
>npm update -g cordova


9. 안드로이드 코르도바 앱 만들기
>mkdir \HybridProject
>cd \HybridProject
>cordova create test com.example.test testApp -d
>cd test
>dir
>dir platform
>cordova platform add android
>dir platform
0. build.gradle(:app) ->안드로이드 스튜디오

-android 밑에 namespace 위에
packagingOptions {

        exclude 'META-INF/DEPENDENCIES.txt'

        exclude 'META-INF/LICENSE.txt'

        exclude 'META-INF/NOTICE.txt'

        exclude 'META-INF/NOTICE'

        exclude 'META-INF/LICENSE'

        exclude 'META-INF/DEPENDENCIES'

        exclude 'META-INF/notice.txt'

        exclude 'META-INF/license.txt'

        exclude 'META-INF/dependencies.txt'

        exclude 'META-INF/LGPL2.1'

    }

11. AndroidManifest.xml
-application 안에 
android:largeHeap="true" 넣기

7. 웹앱, 하이브리드앱, 네이티브앱에 대해 기술하시오 
웹앱
모바일 웹의 장점과 네이티브의 장점을 결합. 웹 기술로 구현하는 앱을 통칭한다. 기본적으로 HTML, CSS, JS를 사용해 만들어진 애플리케이션이다
하이브리드앱
네이티브 + 웹앱의 기술을 함께 사용하는 앱. 콘텐츠 영역은 HTML 기반의 웹 앱으로 개발을 하되 패키징 처리만 각 아이폰, 안드로이드 플랫폼 안에서 함으로써 앱 배포를 가능하게 한다.
네이티브앱
SDK기반으로 개발된 애플리케이션. 모바일 플랫폼 API를 이용해 개발한다. 모바일 기기에 직접 다운로드하여 로컬에 저장되는 실행파일로 사용된다.
8. 인의예지신과 중도에 대해 기술하시오
인의예지신의 오성이 감정으로 드러나 측은, 수오, 사양, 시비지심으로 나 타나는 것 역시 '심통성정'한 상태임을 말하고 있다. 중도를 보면, 사단과 칠정이라는 감정으로 나타나지만 오직 선함을 말하고 있음을 알 수 있다</h7>
