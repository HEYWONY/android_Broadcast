# 브로드캐스트
`브로드캐스트 수신` 시스템 혹은 앱에서 발생 시키는 이벤트를 수신처리 하는 것 <br>
안드로이드는 브로드캐스트 수신을 할 때 `onReceive()`는 대략 10초 정도 화면에 보여줌 <br>
응답하지 않으면 사용자가 이 이벤트를 처리하지 않겠다고 생각함 <br>

### 브로드캐스트 수신의 종류 <br>
1. 시스템에서 발생 (헨드폰에서 발생) <br>
2. 앱에서 발생 시키는 것 (소스에서 코딩) <br>


### mainactivity 화면 <br>
![br](https://user-images.githubusercontent.com/65533618/152719188-8bce71c7-47b5-450f-a283-7f1e7c5f581f.JPG)

### breadcast
![image](https://user-images.githubusercontent.com/65533618/152720191-c6fb69df-b3da-4b81-955e-360c958bd473.png) <br>
이제 이 화면을 만들 차례이다 <br> <br>

app 우클릭 => other -> BroadcastReceiver 클릭 <br>
![image](https://user-images.githubusercontent.com/65533618/152719586-2c7cefda-8d07-46fd-8c2c-3f0f2d439393.png) <br>
이 과정을 총 두 번 실행해서 2개의 BroadcastReceiver를 생성한다.

### 실행 결과
![image](https://user-images.githubusercontent.com/65533618/152722690-392de72a-f4d9-4642-9c3b-3bc832dd085c.png) <br>
![image](https://user-images.githubusercontent.com/65533618/152722714-deb5f7c7-1731-4ade-ad0f-e9eb081ae081.png)
