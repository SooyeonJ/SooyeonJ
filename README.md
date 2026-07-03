# 👩‍💻 SOOYEON JEONG
🎓 M.Eng Hanyang University in Computer Science, Sep 2025 – now  
🎓 B.S. in Computer Software Engineering  
💼 IT System Operator specialized in **Healthcare & Financial Data** · **DevOps** · **CI/CD** · **Database Operation**

---

## 💼 Career
| Company | Duration |
|---------|----------|
| Korea Health Information Service (KHIS) | 2023.08 ~ now |
| Yonsei University Health System (Severance) | 2022.08 ~ 2023.07 |
| UBcare | 2021.06 ~ 2022.07 |
| SEESAWTALK | 2019.04 ~ 2019.12 |

---

### 🏥 KHIS — [Healthcare MyData System](https://www.myhealthway.go.kr)
- CI/CD 파이프라인 구축 ⇒ 배포 시간 50% 단축 · SQL 점검 쿼리 자동화 ⇒ 오류 분석 20% 단축
- Spring(전자정부 프레임워크) 기반 OAuth2·RSA·SEED-CTR 암호화 모듈 개발 · C# Windows 서비스 개발
- 멀티 클라우드(네이버·카카오·더존·G-Cloud) 운영 · 2025년 국가정보자원관리원 화재 복구 참여

### 🏥 Yonsei University Health System — Data Analysis & DB Construction
- UK Biobank 50만명 빅데이터 ⇒ 원내 MS-SQL DB 구축 (11개 카테고리·26개 테이블) · DICOM 추출
- RTLS 150만 row 기반 낙상위험도 평가 모델 · 감염병 전파 분석 → CDC SCI급 논문 제4저자 (IF 7.2)

### 💊 UBCare — EMR System Operation & Development
- 국내 1위 병의원 EMR(의사랑) 운영·유지보수
  - eGFR 자동계산 기능 개발·출시 (2021.11 · 한국아스트라제네카 후원 · [의학신문](https://www.bosa.co.kr/news/articleView.html?idxno=2161395) 보도) 
- Sybase 기반 이기종 DBMS 간 데이터 이관·컨버전

---

### 🚀 Featured Projects & Products
| 프로젝트 | 한 줄 소개 & 핵심 가치 | 관련 링크 |
|---|---|---|
| **MediCost AI** | "흩어진 약값 데이터를, 한눈에 재무 리포트로"<br>투약이력 PDF를 AI가 자동 분석해 약제비 흐름과 연령대 평균 대비 재무 리스크를 진단·시각화 | 🔗 [Live Demo](https://medicost-ai.lovable.app/) |

---

## 📄 Research
#### [Identifying Contact Time Required for Secondary Transmission of *Clostridioides difficile* Infections by Using Real-Time Locating System](https://wwwnc.cdc.gov/eid/article/30/5/23-1588_article)
*Emerging Infectious Diseases, CDC — Vol.30, No.5, May 2024 · IF 7.2 🏅*
- (SCI 논문 공동 저자) RTLS 기반 접촉 사례 4,196건 ⇒ 최종 3,620건 데이터셋 구축·피처 엔지니어링 

---

## 🏆 Activities
#### 📈 [DB GAPS - Mock Investment Competition](https://github.com/SooyeonJ/investment-analytics) *(2026, -ing)*
- 국내 자산배분 담당 · 188개 ETF 유니버스 대상 pykrx 기반 시세 조회·백테스팅 스크립트 개발
- argparse 기반 CLI 도구 3종 설계 (`--file`/`--month`/`--date` 파라미터화) ⇒ 매월 코드 수정 없이 재실행 가능한 분석 파이프라인 구축
- pandas로 종목별 보유구간(`series > 0`) 자동 슬라이싱 + pykrx `get_market_ohlcv_by_date` 종가 매핑 ⇒ 포지션 변화(분할매수)와 가격변동을 분리한 순수 수익률 계산 로직 설계
- 실제 매도 시나리오 vs counterfactual(미매도 가정) 시계열을 `date_to_idx`로 정렬·병합 ⇒ 리밸런싱 효과를 %p 단위로 정량화
---

## 🎯 Interests
`Data Engineering` `DevOps` `System Reliability` `Backend Operation` `Financial IT`
