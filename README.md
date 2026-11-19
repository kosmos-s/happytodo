<div align= "center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=180&text=2025%202학기%20발표&animation=&fontColor=ffffff&fontSize=70" />
    
![git](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![kot](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white)
![an](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![ans](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
    </div>

# 행복한 할 일 앱 (Happy To-Do App)



<img width="506" height="185" alt="image" src="https://github.com/user-attachments/assets/57f86006-e2bf-4c4f-8020-2d77aba4c079" />

## 현재 저장소 상태 (2026-11-19 소스 확인)

현재 `app/src/main/java/com/example/happytodo/MainActivity.kt`는 `Greeting("Android")`를 표시하는 기본 Compose 화면입니다. 아래의 할 일 기능 설명과 화면 이미지는 프로젝트 소개 자료이며, 현재 체크아웃한 소스로 해당 기능을 재현할 수 있다는 뜻은 아닙니다. 할 일 추가·삭제·응원 메시지 구현은 이 저장소 소스에서 확인되지 않았습니다.

## 📌 프로젝트 소개 자료
안드로이드 Jetpack Compose를 사용하여 만든 **간단한 To-Do List 앱**입니다.  
- 할 일 추가 및 삭제  
- 할 일 완료 시 랜덤 응원 메시지 출력  

---

## 📌 소개 자료의 기능
1. **할 일 추가**
   - 텍스트 입력 후 `추가` 버튼 클릭 시 목록에 항목 표시
2. **할 일 삭제**
   - 완료 버튼 클릭 시 항목 삭제
3. **랜덤 응원 메시지**
   - 완료 시 화면 하단에 `Toast`로 랜덤 메시지 표시
   - 예: "잘했어요! 👍", "멋져요! 🌟", "계속해요! 💪", "대단해요! 🎉"

---

## 📌 소개 자료의 화면 예시

앱 시작 화면	
---


<img width="440" height="997" alt="image" src="https://github.com/user-attachments/assets/b3ee5a00-1c30-4a87-b16d-99cdb067b17b" />

---

할 일 추가 
---

<img width="463" height="1011" alt="image" src="https://github.com/user-attachments/assets/789720ce-dbb8-4cf9-833c-b7fa40283db5" />

---


완료 시 랜덤 메시지
---

<img width="446" height="1011" alt="image" src="https://github.com/user-attachments/assets/926cf045-d8f3-4e92-b67c-2d74e41f4b3b" />

---



📌 사용 기술

Kotlin

Jetpack Compose

Android Studio

## 빌드와 검증

Android Studio에서 저장소 루트를 열고 SDK 36을 설치한 뒤 포함된 Gradle Wrapper를 사용합니다. AGP 실행에는 JDK 17 이상이 필요합니다.

```powershell
.\gradlew.bat :app:testDebugUnitTest :app:assembleDebug
```

macOS/Linux에서는 `./gradlew`를 사용합니다. 현재 단위 테스트는 기본 산술 예제이며 할 일 기능 검증을 포함하지 않습니다. 소개 자료와 같은 앱의 원본 소스를 확인한 뒤 구현과 문서를 맞추는 작업이 남아 있습니다.
