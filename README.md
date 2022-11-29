# cordova_2022

#코르도바앱 환경 설정 절차
<h1>1. JDK 설치</h1>
<h>jdk를 다운해야하는데 저는 1.8버전으로 다운받았습니다</h>
<h><img width="1252" alt="image" src="https://user-images.githubusercontent.com/74278588/204412072-e7aa1c63-ff2d-49bd-8025-e0a2f3f9af77.png"></h>

<h1>2.아파치 앤트 설치하기</h1>
<h>앤트는 원래 사이트에서 다운받으면 되지만 저는 맥 OS를 사용하고 있어서</h>
<h>터미널을 실행시킨후 <strong>brew install ant</strong> 라는 명렁어를 치게 되면 자동으로 깔리게 됩니다</h>
<h>설치 후 버전 확인 화면입니다</h>
<h><img width="518" alt="image" src="https://user-images.githubusercontent.com/74278588/204416781-e0bddd84-5f00-4e8f-b811-5d3ca51806f0.png"></h>

<h1>3.Gradle 설치하기</h1>
<h>Gradle도 앤트와 마찬가지로 터미널을 실행시킨후 <strong>brew install gradle</strong> 을 입력하게되면 자동으로 깔리게 됩니다</h>
<h>설치 후 버전 확인 화면입니다</h>
<h><img width="521" alt="image" src="https://user-images.githubusercontent.com/74278588/204416732-751fc91e-1da8-4ea0-a8c2-8628416f8b12.png">
</h>

<h1>4. 안드로이드 플랫폼 패키지 추가 설치하기</h1>
<h>밑에 파일들을 다운받아야하는데 저는 뭔가 있는거도 있고 없는것도 있고 그래서 다 다운받았습니다</h>
<h><strong>Tools</strong> <br>
	Android SDK Tools<br>
	Android SDK Platfor-tools<br>
	Android SDK Build-tools<br><br>
<strong>Android R(Api 29, R preview)</strong><br>
	SDK Platform Android R Preview<br>
	Google Play Intel x86 Atom_64_System Image<br>
	Google APIs intel x86 Atom_64_System Image<br><br>
<strong>Extra</strong><br>
	Android Support Repository<br>
	Google Repository<br>
	Google USB Driver<br>
	Intel x86 Emulator Accelerator(HAXM installer)<br>
</h>
<h>안드로이드 스튜디오를 실행하고 프로젝트 목록이 뜨는 화면에서 우측 상단에 보면 점 3개가 있는데 거기를 클릭하면</h>

<h><img width="788" alt="image" src="https://user-images.githubusercontent.com/74278588/204414149-f978c699-b23e-4169-ad95-0c685ec37ea3.png">
</h>

<h>위 사진처럼 뜨게되는데 거기서 SDK Manager 를 누르고 들어가면</h>

<h><img width="968" alt="image" src="https://user-images.githubusercontent.com/74278588/204414101-271ae71f-3bbb-4e1a-bc5d-257ce050fd5a.png">
</h>
<h>위에 화면이 뜨게 되며 거기서 System Setting으로 들어가 Android SDK로 들어가서 다운받으면 된다</h>

<h1>5.환경 변수 설정하기</h1>
<h>환경변수를 설정하면 되는데 맥의 경우 터미널로 들어가서 환경변수 설정을 해야한다,,</h>
<h>참고 링크 :</h>
<h>https://seogilang.tistory.com/927</h>

<h>설치 후 버전 확인 화면입니다</h>
<h><img width="554" alt="image" src="https://user-images.githubusercontent.com/74278588/204414935-66c2dac3-2f2d-42f5-b4d2-3529e7bdb583.png">
</h>

<h1>6.Node.js 설치하기</h1>
<h>Node.js도 위와 마찬가지로 터미널을 실행시킨후 <strong>brew install npm</strong> 을 입력하게되면 자동으로 깔리게 됩니다</h>
<h>설치 후 버전 확인 화면입니다</h>
<img width="420" alt="image" src="https://user-images.githubusercontent.com/74278588/204416383-fd1400fe-fe3d-4f71-ad3a-493c556da989.png">

<h1>7. 폰갭(코르도바 설치하기)</h1>
<h>둘 다 위와 마찬가지로 터미널을 실행시킨후 이번에는 브루가 아닌 <br>
<strong>>npm install -g phonegap<br>
>npm install -g cordova을 입력하게되면 자동으로 깔리게 됩니다</h>
	<h>설치 후 버전 확인 화면입니다</h>
<img width="485" alt="image" src="https://user-images.githubusercontent.com/74278588/204417027-a6f07c4a-85b7-4faa-b9fc-4638cce42a24.png">



