# Dacon_algorithm

## **잡케어 추천 알고리즘** 경진대회

### **배경** :

잡케어는 일자리를 탐색하는 구직자에게 구직자의 이력서를 인공지능 기술로 직무역량을 자동 분석하여 훈련, 자격, 일자리 상담에 활용할 수 있도록 지원하는 시스템이다.

한국고용정보원은 구인구직 빅데이터 기반으로 커리어 관리 서비스인 잡케어 서비스를 구축하고 있다.

본 대회를 통해 데이터를 기반으로 개인별 맞춤형 컨텐츠 추천 모델을 만들고자 한다.
<br></br>

### **목적**:

잡케어 서비스에 적용가능한 추천 알고리즘 개발
<br></br>

### **주최/주관**:

주최 : 한국고용정보원
</br>주관 : 데이콘

---

### **데이터 설명** :

- **train.csv**

  - d_l_match_yn : 속성 D 대분류 매칭 여부

  d_m_match_yn : 속성 D 세분류 매칭 여부

  d_s_match_yn : 속성 D 코드 매칭 여부

  h_l_match_yn : 속성 H 대분류 매칭 여부

  h_m_match_yn : 속성 H 중분류 매칭 여부

  h_s_match_yn : 속성 H 코드 매칭 여부

  person_attribute_a : 회원 속성 A

  person_attribute_a_1 : 회원 속성 A 하위 속성 1

  person_attribute_b : 회원 속성 B

  person_prefer_c : 회원 선호 속성 C

  person_prefer_d_1 : 회원 선호 속성 D 1번

  person_prefer_d_2 : 회원 선호 속성 D 2번

  person_prefer_d_3 : 회원 선호 속성 D 3번

  person_prefer_e : 회원 선호 속성 E

  person_prefer_f : 회원 선호 속성 F

  person_prefer_g : 회원 선호 속성 G

  person_prefer_h_1 : 회원 선호 속성 H 1번

  person_prefer_h_2 : 회원 선호 속성 H 2번

  person_prefer_h_3 : 회원 선호 속성 H 3번

  contents_attribute_i : 컨텐츠 속성 I

  contents_attribute_a : 컨텐츠 속성 A

  contents_attribute_j_1 : 컨텐츠 속성 J 하위 속성 1

  contents_attribute_j : 컨텐츠 속성 J

  contents_attribute_c : 컨텐츠 속성 C

  contents_attribute_k : 컨텐츠 속성 K

  contents_attribute_l : 컨텐츠 속성 L

  contents_attribute_d : 컨텐츠 속성 D

  contents_attribute_m : 컨텐츠 속성 M

  contents_attribute_e : 컨텐츠 속성 E

  contents_attribute_h : 컨텐츠 속성 H

  person_rn : 사용자번호

  contents_rn : 컨텐츠번호

  contents_open_dt : 컨텐츠 열람 일시

  target : 컨텐츠 사용 여부 (라벨)

- **test.csv**
- **속성D코드.csv, 속성L코드.csv, 속성H코드.csv**

<br></br>

### **결과**:

- **score** : 0.70213
