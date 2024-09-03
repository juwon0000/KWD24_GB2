# 📧 이메일 보안 침해 사례 Research 

## 👤 경상 2조 - 팀 구성 
|번호|구분|이름|담당업무|
|:-:|---|---|-------------|
|1|팀원|임경용|     미정     |
|2|팀원|조성원|     미정     |
|3|팀원|신서영|     미정     |
|4|팀원|정주원|     미정     |
|5|팀원|김민지|     미정     |

# 이메일 보안 침해 사례 및 대응 방법 조사 

## 1. 개요

### **사례 1 : Google과 Facebook의 피싱 사건**

- **기간**: 2013년 ~ 2015년
- **피해자**: Google, Facebook 및 기타 글로벌 기업
- **공격자**: 회계 정보를 탈취한 피싱 공격 범죄 조직
- **피해 금액**: 약 1억 달러
- **공격 방법**: 실제 청구서와 유사한 피싱 이메일 발송 후, 피해자의 회계 부서가 송금 요청을 승인하여 자금 유출
[Google Facebook $100 million phishing scam 조사](https://www.notion.so/Google-Facebook-100-million-phishing-scam-9b3ce00e34e54d72a622751c2f9d2e95?pvs=21)

### **사례 2 : 북한 라자루스 해킹 조직** 

- **수법**: '꿈의 직장 작전' - 채용 담당자로 가장해 방산업체 직원에게 접근, 악성 코드가 포함된 문서를 전송하여 감염 유도
- **최근 공격**: 프로그래머를 대상으로 코딩 테스트를 빙자한 악성 ISO 파일 전송
- **목적**: 저비용으로 방산 첨단 기술 확보 및 무기 개발
[북한 라자루스 해킹 조직의 방산업체 해킹 수법 및 대응 방안 요약](https://www.notion.so/6431868a9fbc4180805553b92d2de564?pvs=21)

## 2. **기술적 방어 방법**
### **2.1. 이메일 보안 강화**

1) **스팸 필터링**:
    - **기능**: 스팸 및 피싱 이메일을 자동으로 차단하고 필터링
    - **기술**: 머신러닝 기반 필터링, 정규 표현식 검출
2) **이메일 보안 관련 주요 기술(DMARC, DKIM, SPF)**:
    - **기능**: 이메일의 진위를 확인하고 이메일 스푸핑 및 피싱 공격(위조된 발송자)을 차단
    - **기술**: 도메인 기반 메시지 인증(DMARC), 도메인 키 식별 이메일(DKIM), 발신자 정책 프레임워크(SPF)
    - 위 기술들을 적절하게 활용 시 피싱 공격 및 이메일 스푸핑 공격 효과적 방지 가능
3) **피싱 URL 차단**:
    - **기능**: 악성 URL을 자동으로 탐지하고 차단
    - **기술**: URL 필터링 및 악성 웹사이트 탐지 시스템

### **2.2. 사회공학적 공격 방어**

1) **다단계 인증(MFA)**:
    - **기능**: 로그인을 위한 추가 인증 단계 도입, 피싱 공격으로부터 보호
    - **기술**: OTP(일회용 비밀번호), 푸시 알림 기반 인증
2) **보안 교육 및 훈련**:
    - **기능**: 직원들에게 피싱 및 소셜 엔지니어링 공격에 대한 교육 제공
    - **기술**: 시뮬레이션 공격, 보안 인식 훈련 프로그램
3) **정기적인 보안 감사 및 테스트**:
    - **기능**: 시스템의 취약점을 정기적으로 점검하고 개선
    - **기술**: 취약점 스캔, 펜 테스트(침투 테스트)

## 3. 기술적 현황과 향후 과제

### 3.1. **현재 기술 발전**

* **스팸 필터링 및 이메일 보안 기술**: DMARC, SPF, AI 기반 탐지 시스템
* **다단계 인증**: 비밀번호 유출 방지에 효과적

### 3.2. **한계 및 개선 필요**

* **지속적인 공격 기법의 진화**: 보안 기술의 지속적 발전 필요
* **사용자 인식 부족**: 기술적 방어와 함께 사용자 교육 강화 필요
* **종합적 보안 접근**: 이메일 보안, 사용자 교육, 시스템 감사 통합적 적용 필요

## 4. References
_**추가사항:(아래에 참고 기사/논문/블로그 주소 등 인용자료 정보 추가할 것)_  

[1] https://www.bbc.com/news/technology-39744007  
[2] https://www.cnbc.com/2019/03/27/phishing-email-scam-stole-100-million-from-facebook-and-google.html  
[3] https://www.cpomagazine.com/cyber-security/the-phishing-scam-that-took-google-and-facebook-for-100-million/  
[4] https://www.trendmicro.com/vinfo/us/security/news/cybercrime-and-digital-threats/google-and-facebook-fraudster-pleads-guilty-to-100-million-scam  
[5] https://www.bitdefender.com/blog/hotforsecurity/the-phishing-swindle-that-conned-100-million-out-of-google-and-facebook/?srsltid=AfmBOoqMIzKl8LKXw2782QcBdaIKzqMT-cFf9tr4379DfRl7dw1iy9yt%2F%2F  
