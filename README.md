# Firebase 설정
### 1. 프로젝트 버킷 분리

![led1 time](https://github.com/user-attachments/assets/36260c9d-990c-4ea2-9f9c-827add0bdf79)

# APP-Inventor 설정
### 2. 디자이너

#### - 조명 초기 화면

<img src="https://github.com/user-attachments/assets/aa89cc80-50fd-45ed-88b2-ae0a0d896609" alt="400" width="200">

노란색의 버튼은 아직 눌리지 않은 상태를 의미함 (노란색 버튼을 눌러야 동작함!)

회색 버튼은 비활성화 상태를 의미 (눌러도 동작 X)

1) 조명 on/off 변경 시 조명 이미지 변경 및 스위치 색상 변경

 <img src="https://github.com/user-attachments/assets/275e5af9-6d8a-4225-9b60-722463532476" alt="400" width="200">

2) 시간 설정하기 버튼 클릭 시 숨겨진 창 팝업 및 스위치 동작 시간 설정

 <img src="https://github.com/user-attachments/assets/590ae69c-f100-4a00-8a52-806cc0c29590" alt="400" width="200">

3) 시간 설정 후 적용하기 버튼 클릭 시 시간 설정 창 숨기기 후 적용 완료 버튼 표시

 <img src="https://github.com/user-attachments/assets/369348dd-32c9-40f4-aeba-cc1a142ac605" alt="400" width="200">

4) 에어컨 설정하기 버튼 클릭 시 에어컨 배치화면으로 이동

#### - 에어컨 초기 화면

<img src="https://github.com/user-attachments/assets/0d19b1b0-33fb-4b25-8ae1-d57d4e9457da" alt="400" width="200">

1) 에어컨 on/off 변경 시 이미지 변경 및 스위치 이미지 변경

 <img src="https://github.com/user-attachments/assets/4b919c9f-2cf1-4e8e-b221-95d023e717d5" alt="400" width="200">

2) 시간 설정하기 버튼 클릭 시 숨겨진 창 팝업 및 스위치 동작 시간 설정

 <img src="https://github.com/user-attachments/assets/6288559c-4411-4f54-98d6-b2d60b74d185" alt="400" width="200">

3) 시간 설정 후 적용하기 버튼 클릭 시 시간 설정 창 숨기기 후 적용 완료 버튼 표시

 <img src="https://github.com/user-attachments/assets/5ce1ce0a-a712-40d8-b56f-f827e0e7ce05" alt="400" width="200">
 
### 3. 블록

#### - 스크린 초기화 시 설정

![스크린 초기화](https://github.com/user-attachments/assets/85c0b94a-a067-4b1e-aaf3-d3ffe56cdd7f)

1) 텍스트 초기화 설정

![함수1](https://github.com/user-attachments/assets/3e43409a-6bc5-4a99-a1ef-736618d3c793)

2) 조명 및 에어컨 이미지 초기화 설정

![함수2](https://github.com/user-attachments/assets/88e67f45-34ea-41b5-bb51-41660c66a77b)

3) 조명 화면 표시 및 에어컨 화면 숨기기 설정

![함수3](https://github.com/user-attachments/assets/675d3a8b-b786-46d8-a55e-e603a527417d)

4) 파이어베이스 값 초기화 설정

<img src="https://github.com/user-attachments/assets/2e86cc14-b5e3-4300-b564-0c020ffa9760" alt="400" width="200">

#### - on/off 설정

1) 조명 on/off 설정

![조명 온오프 블럭](https://github.com/user-attachments/assets/b7d48b61-edb3-41d3-bdf9-f2af7644c57d)

on/off 시 파이어베이스의 저장된 값에 1, 0 지정 및 이미지 변경

스위치 색상을 변경시켜 스위치가 눌렸음을 표시함

2) 에어컨 on/off 설정

![에어컨 온오프 블록](https://github.com/user-attachments/assets/72a22007-aa72-4e95-9c6f-edc35b0f5ef6)

on/off 시 파이어베이스의 저장된 값에 1, 0 지정 및 스위치와 이미지 변경

조명과 에어컨의 on/off 방식이 다른 이유는 2가지 방법을 모두 표현하기 위함이었음.

#### - 시간 설정

1) 조명 시간 설정

![조명 시간입력](https://github.com/user-attachments/assets/77e2d87d-cda3-4182-86a7-5f31bff3db8c)
![조명 시간설정](https://github.com/user-attachments/assets/09d7df47-eb36-49ee-ab1f-23f42d343646)
![조명 초기화](https://github.com/user-attachments/assets/cd3ccd46-14ac-45ed-bc55-049237c42ffe)

00:00 형식으로 작성 그 후 Firebase에 실시간 업데이트

안방 시간 설정 시 거실 시간 설정 숨기기 및 그 역도 성립되게 함



2) 에어컨 시간 설정

![에어컨 시간입력](https://github.com/user-attachments/assets/a6fff976-ac5d-45e6-b21f-f7d519c8ca30)
![에어컨 시간 설정](https://github.com/user-attachments/assets/ee62209a-2305-4820-ac80-440924ed3e4c)
![에어컨 초기화](https://github.com/user-attachments/assets/c4ddcc1b-6d84-4e6f-af95-0f4b00e5af7c)

00:00 형식으로 작성 그 후 Firebase에 실시간 업데이트

안방 시간 설정 시 거실 시간 설정 숨기기 및 그 역도 성립되게 함

4) 공통 설정

![시간 적용완료 설정](https://github.com/user-attachments/assets/9d7b0a79-3e34-4e7d-93a4-5f03ff3df534)

#### - 화면 전환 설정

![화면전환블럭](https://github.com/user-attachments/assets/53a93031-2474-4b83-8ada-8f814cdb9306)

# ESP32 보드 설정
### 4. 사용 보드

#### - i2r-03
WiFi Bluetooth PLC (4채널 릴레이, 온습도센서, ESP32) KC인증
![i2r-03-포트설명](https://github.com/kdi6033/i2r-03/assets/37902752/a6df72d2-0707-48f0-93b9-484a90149bba)

### 5. 프로그램 코드

#### - 아두이노 프로그램 코드

```
#include <WiFi.h>
#include <FirebaseESP32.h>
#include <NTPClient.h>
#include <WiFiUdp.h>

// WiFi 설정
#define WIFI_SSID "your_WiFi"
#define WIFI_PASSWORD "your_PASSWORD"

// Firebase 설정
#define FIREBASE_HOST "Firebase address"
#define FIREBASE_AUTH "API Key"

// Firebase 객체 생성
FirebaseData firebaseData;
FirebaseAuth auth;
FirebaseConfig config;

// 핀 설정
const int led1Pin = 26; // Bedroom LED
const int led2Pin = 27; // Living Room LED
const int ac1Pin = 32;  // Bedroom AC
const int ac2Pin = 33;  // Living Room AC

// NTP 클라이언트 설정
WiFiUDP ntpUDP;
NTPClient timeClient(ntpUDP, "pool.ntp.org", 3600 * 9); // KST(UTC+9)

// 상태 저장 변수
String led1StartTime, led1EndTime, ac1StartTime, ac1EndTime;
String led2StartTime, led2EndTime, ac2StartTime, ac2EndTime;
bool led1State = false, led2State = false, ac1State = false, ac2State = false;

bool firebaseStreamConnected = false; // Firebase 스트림 상태

// WiFi 연결 함수
void connectToWiFi() {
  Serial.print("Connecting to Wi-Fi");
  WiFi.begin(WIFI_SSID, WIFI_PASSWORD);
  while (WiFi.status() != WL_CONNECTED) {
    delay(1000);
    Serial.print(".");
  }
  Serial.println("\nConnected to Wi-Fi");
}

// Firebase 데이터 변경 감지 (StreamData를 사용)
void streamCallback(StreamData data) {
  String path = data.dataPath();
  String value = data.stringData();

  Serial.println("Path: " + path);
  Serial.println("Value: " + value);

  if (path == "/BedRoom/led1_start") led1StartTime = value;
  if (path == "/BedRoom/led1_end") led1EndTime = value;
  if (path == "/BedRoom/ac1_start") ac1StartTime = value;
  if (path == "/BedRoom/ac1_end") ac1EndTime = value;
  if (path == "/LivingRoom/led2_start") led2StartTime = value;
  if (path == "/LivingRoom/led2_end") led2EndTime = value;
  if (path == "/LivingRoom/ac2_start") ac2StartTime = value;
  if (path == "/LivingRoom/ac2_end") ac2EndTime = value;
}

void streamTimeoutCallback(bool timeout) {
  if (timeout) {
    Serial.println("Stream timeout, attempting to reconnect...");
    firebaseStreamConnected = false;
  }
}

// 현재 시간을 "HH:MM" 형식으로 가져오기
String getCurrentTime() {
  timeClient.update();
  return timeClient.getFormattedTime().substring(0, 5); // HH:MM 형식
}

// 장치 제어 함수
void controlDevices() {
  String currentTime = getCurrentTime();

  // Bedroom LED 제어
  if (currentTime == led1StartTime && !led1State) {
    digitalWrite(led1Pin, HIGH);
    led1State = true;
    Firebase.setString(firebaseData, "/BedRoom/led1", "1");
    Serial.println("Bedroom LED ON");
  } else if (currentTime == led1EndTime && led1State) {
    digitalWrite(led1Pin, LOW);
    led1State = false;
    Firebase.setString(firebaseData, "/BedRoom/led1", "0");
    Serial.println("Bedroom LED OFF");
  }

  // Living Room LED 제어
  if (currentTime == led2StartTime && !led2State) {
    digitalWrite(led2Pin, HIGH);
    led2State = true;
    Firebase.setString(firebaseData, "/LivingRoom/led2", "1");
    Serial.println("Living Room LED ON");
  } else if (currentTime == led2EndTime && led2State) {
    digitalWrite(led2Pin, LOW);
    led2State = false;
    Firebase.setString(firebaseData, "/LivingRoom/led2", "0");
    Serial.println("Living Room LED OFF");
  }

  // Bedroom AC 제어
  if (currentTime == ac1StartTime && !ac1State) {
    digitalWrite(ac1Pin, HIGH);
    ac1State = true;
    Firebase.setString(firebaseData, "/BedRoom/ac1", "1");
    Serial.println("Bedroom AC ON");
  } else if (currentTime == ac1EndTime && ac1State) {
    digitalWrite(ac1Pin, LOW);
    ac1State = false;
    Firebase.setString(firebaseData, "/BedRoom/ac1", "0");
    Serial.println("Bedroom AC OFF");
  }

  // Living Room AC 제어
  if (currentTime == ac2StartTime && !ac2State) {
    digitalWrite(ac2Pin, HIGH);
    ac2State = true;
    Firebase.setString(firebaseData, "/LivingRoom/ac2", "1");
    Serial.println("Living Room AC ON");
  } else if (currentTime == ac2EndTime && ac2State) {
    digitalWrite(ac2Pin, LOW);
    ac2State = false;
    Firebase.setString(firebaseData, "/LivingRoom/ac2", "0");
    Serial.println("Living Room AC OFF");
  }
}

// Firebase 스트림 연결 함수
void connectToFirebaseStream() {
  if (!Firebase.beginStream(firebaseData, "/")) {
    Serial.println("Stream connection failed: " + firebaseData.errorReason());
    firebaseStreamConnected = false;
  } else {
    firebaseStreamConnected = true;
    Serial.println("Firebase stream connected.");
    Firebase.setStreamCallback(firebaseData, streamCallback, streamTimeoutCallback);
  }
}

void setup() {
  Serial.begin(115200);

  // 핀 모드 설정
  pinMode(led1Pin, OUTPUT);
  pinMode(led2Pin, OUTPUT);
  pinMode(ac1Pin, OUTPUT);
  pinMode(ac2Pin, OUTPUT);

  // 초기 상태
  digitalWrite(led1Pin, LOW);
  digitalWrite(led2Pin, LOW);
  digitalWrite(ac1Pin, LOW);
  digitalWrite(ac2Pin, LOW);

  // WiFi 연결
  connectToWiFi();

  // Firebase 설정
  config.host = FIREBASE_HOST;
  config.signer.tokens.legacy_token = FIREBASE_AUTH;

  // Firebase 초기화
  Firebase.begin(&config, &auth);

  // Firebase 스트림 연결
  connectToFirebaseStream();

  // NTP 클라이언트 초기화
  timeClient.begin();
}

void loop() {
  // 스트림 연결 확인 및 재연결
  if (!firebaseStreamConnected) {
    delay(2000); // 2초 대기
    connectToFirebaseStream();
    Serial.println("reconnecting..");
  }

  // 시간 기반 장치 제어
  controlDevices();
  delay(30000); // 30초 간격으로 제어
}
```
수정중...
