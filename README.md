# 📌 IU Geek Out :: Best Video (2021)

![](https://images.velog.io/images/hyerimiya/post/e64abfdf-0c85-472d-a8a3-d6ac0b6174fd/1.png)

![](https://images.velog.io/images/hyerimiya/post/aec9a9f9-0f3e-4134-97ca-b17c445e61ee/2.png)


## ✏ 프로젝트 소개
기존에 있던 'Best Horror Scenes' 사이트를 조금 바꿔서 만든  
평소 좋아하는 연예인 아이유를 덕질할 때 많이 보는 영상들을 모아둔 사이트입니다.  
나만의 취향을 그대로 노출한다는게 마음에 걸려 로그인 페이지를 별도로 만들었습니다.  
드라마, 예능, 연예인들에 관심이 많아 덕질을 많이 하는 편이라 연예인 팬페이지나 방송 관련 된 사이트나 앱을 꼭 만들어보고 싶었는데  
React를 사용할 줄 알게 되면서 간단한 웹페이지를 만들어보았습니다.

## 🖱 실행 방법
* 로그인 페이지
  - **email : 기존 이메일 방식으로 아무렇게나 입력하면 된다 ex) email@sample.com**
  - **password : 영문/숫자 포함, 8~15자를 입력하면 된다**
  - 올바르게 입력하지 않으면 로그인페이지 그대로, 알맞게 입력했다면 메인페이지로 넘어간다
* 메인 페이지
  - 로그인페이지에서 입력했던 이메일이 저장되어 메인페이지에서 표시된다

## 🖱 작업 툴
**React** (mobX, Formik, Yup), CSS

## 📎 [참고사이트_BEST HORROR SCENES](https://besthorrorscenes.com/)

## ✏ 프로젝트를 통해 배운 점
React로 프로젝트를 하나 완성했다는 것만으로도 뿌듯했는데  
두 페이지를 연결시키면서 더 알게되는 것이 많았고 좋았습니다.  
다만, 새로고침을 하면 다시 로그인페이지로 가게되는데 그 부분을 아직 해결하지 못해서 아쉽지만  
이 사이트의 사용은 개인적인 것이기 때문에 더 공부해서 퀄리티 높은 프로젝트를 만들 수 있도록 계속해서 공부하려고합니다.

---

### mobX
state를 전역적으로 쉽게 관리할 수 있게 해주는 라이브러리 (Redux와 유사)  
@observable : '관찰받고 있는' 상태로 이해하면 됨(상태 관찰 대상)  
@action : 상태에 어떻게 변화를 일으킬 것인지 정의하는 부분(Redux의 action과 같은 개념)  
@inject : @inject('스토어명')을 이용해서, 해당 스토어의 observable 값과 action 함수를 가져올 수 있음 (가져온 스토어들은 해당 컴포넌트의 props로 내려받아서 사용)  

### Formik
React에서 폼의 복잡성과 장황함을 제거하고,  
Yup 라이브러리를 함께 사용해서 form 양식을 핸들링 하는 방법이 있음

### Yup 
Yup은 Form validation 을 위한 라이브러리 
