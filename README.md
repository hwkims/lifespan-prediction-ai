### GitHub 레포지토리 이름

**lifespan-prediction-ai**  
(이 프로젝트는 남은 수명을 예측하는 AI 기반 웹 애플리케이션이므로, 직관적이고 명확한 이름이 적합합니다.)

---

### README.md

```markdown
# Lifespan Prediction AI

**Lifespan Prediction AI**는 사용자의 얼굴 사진과 음성을 기반으로 남은 수명을 예측하는 웹 애플리케이션입니다. 사용자는 웹캠과 마이크를 사용하여 얼굴과 음성을 제공하고, 이 데이터를 바탕으로 OpenAI GPT API를 통해 예측을 받습니다. API 키를 입력하여 예측을 수행할 수 있습니다.

## 주요 기능

- **웹캠 얼굴 인식**: `face-api.js`를 사용하여 사용자의 얼굴을 인식하고 나이와 성별을 예측합니다.
- **음성 인식**: `SpeechRecognition API`를 사용하여 사용자의 음성을 텍스트로 변환하고, 이를 남은 수명 예측에 활용합니다.
- **OpenAI GPT API 통합**: OpenAI GPT API를 통해 사용자의 얼굴, 성별, 음성 내용을 바탕으로 남은 수명을 예측합니다.
- **사용자 친화적인 인터페이스**: 직관적이고 깨끗한 UI로 사용자가 쉽게 인터랙션할 수 있습니다. API 키를 입력하고 예측 결과를 확인할 수 있습니다.

## 작동 방식

1. **웹캠 얼굴 인식**: 사용자가 웹캠에 대한 접근 권한을 허용하면 얼굴을 인식하여 나이와 성별을 추정합니다.
2. **음성 인식**: 사용자가 음성을 녹음하면 해당 음성이 텍스트로 변환됩니다.
3. **남은 수명 예측**: 수집된 데이터를 바탕으로 OpenAI GPT API에 요청을 보내 남은 수명을 예측합니다.
4. **API 키**: 사용자는 자신의 OpenAI API 키를 입력하여 예측을 요청합니다.

## 설치 및 실행

### 1. 레포지토리 클론

프로젝트를 로컬 머신에 클론하려면 아래 명령어를 사용하세요:

```bash
git clone https://github.com/hwkims/lifespan-prediction-ai.git
cd lifespan-prediction-ai
```

### 2. OpenAI API 키

이 앱을 실행하려면 **OpenAI API 키**가 필요합니다. [OpenAI](https://platform.openai.com/)에서 API 키를 발급받을 수 있습니다. 발급받은 API 키를 웹 페이지의 입력란에 입력해야 합니다.

### 3. 의존성 설치

이 프로젝트는 다음 라이브러리에 의존합니다:

- `face-api.js`: 얼굴 인식 라이브러리.
- `SpeechRecognition API`: 음성 인식 라이브러리.

### 4. 로컬 서버에서 실행

이 앱은 로컬 서버에서 실행해야 합니다. `Live Server`(VS Code 플러그인)나 `http-server`(Node.js 패키지)를 사용해 로컬 서버를 실행할 수 있습니다.

```bash
# http-server를 설치하려면
npm install -g http-server

# 서버 실행
http-server
```

웹 브라우저에서 `http://localhost:8080`에 접속하여 앱을 실행할 수 있습니다.

## 스크린샷

![Webcam Capture](screenshot1.png)  
*웹캠을 통한 얼굴 인식 예시.*

![Voice Transcription](screenshot2.png)  
*음성 텍스트 변환 예시.*

## 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

## 크레딧

- [face-api.js](https://github.com/justadudewhohacks/face-api.js): 얼굴 인식 라이브러리.
- [OpenAI GPT API](https://platform.openai.com/docs): 텍스트 생성 API.
- [SpeechRecognition API](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition): 음성-텍스트 변환 API.

## 기여

이 프로젝트에 기여하고 싶다면 이슈를 제기하거나 풀 리퀘스트를 제출하세요. 앱 개선을 위한 모든 기여를 환영합니다!
```

---

### **README 설명**

1. **프로젝트 개요**: 프로젝트가 무엇인지, 어떤 기술을 사용하는지 간단하게 설명합니다.
2. **주요 기능**: 웹캠을 통한 얼굴 인식, 음성 인식, GPT API 통합 등 주요 기능을 나열합니다.
3. **작동 방식**: 앱이 어떻게 작동하는지 간단하게 설명합니다.
4. **설치 및 실행**: 프로젝트를 로컬에서 실행하는 방법을 단계별로 설명합니다.
5. **스크린샷**: 웹캠 인식 및 음성 텍스트 변환 예시를 제공하는 스크린샷을 추가할 수 있습니다.
6. **라이선스**: MIT 라이선스 사용을 명시합니다.
7. **크레딧**: 사용된 주요 라이브러리와 API를 명시합니다.
8. **기여**: 다른 개발자들이 프로젝트에 기여할 수 있는 방법을 안내합니다.

---

### **다음 단계 (GitHub)**

1. **레포지토리 생성**:
   - [GitHub](https://github.com/)에서 `lifespan-prediction-ai`라는 이름의 레포지토리를 새로 만듭니다.
   - 해당 레포지토리에 프로젝트 파일들을 업로드합니다.

2. **라이선스 추가**:
   - 이 프로젝트는 **MIT 라이선스**로 배포되므로 `LICENSE` 파일을 추가하여 이를 명시합니다.

3. **스크린샷 추가**:
   - 사용 예시를 보여주는 스크린샷을 추가하여 `README.md`에 삽입합니다. 예를 들어, 웹캠에서 얼굴 인식 화면과 음성 녹음 화면을 캡처하여 추가할 수 있습니다.

4. **프로젝트 배포**:
   - 웹 서버 환경에서 프로젝트를 실행하거나, GitHub Pages 등을 활용해 데모 버전을 배포할 수 있습니다.

위와 같은 절차를 따르면, GitHub에서 **Lifespan Prediction AI** 프로젝트를 관리하고 다른 개발자와 협업할 수 있게 됩니다.
