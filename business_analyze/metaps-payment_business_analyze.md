## 사업 분석에 관한 원칙
- 홈 페이지 및 언론에 소개된 내용을 바탕으로 하여 분석한다.
- ホームページまたはメディアに紹介された内容を基づいて分析します。

### 신용카드 결제
- 결제 웹 페이지를 제공하여 고객사와 연동을 한 후 고객사의 유저에게 메텝스 페이먼트의 결제 페이지를 전달한다.
- 고객은 메텝스 페이먼트가 제공하는 결제 페이지를 통해서 고객의 결제 정보를 등록한다.
- 결제 페이지는 세계 최고 수준의 보안 기준을 충족한다.


#### 신용카드 결제 대행을 이용하는 장점
-  5대 카드사 Visa, MasterCard, JCB, American Express, Diners Club 국제 카드사와 결제 연동
-  결제 기능을 제공하여 고객들에게 상품을 직접 팔 수 있는 비즈니스 기회를 제공
-  신용카드를 통한 결제를 제공하여 고객의 상품 결제를 유도할 수 있는 기회를 제공
-  실시간 결제를 통해 결제 피드벡을 통한 고객 대응이 빨라지며 고객 만족도를 높일 수 있다.
-  시용카드 결제를 비즈니스에 도입하는 시대적인 흐름에 맞춰 비즈니스의 기회를 넓힐 수 있다.


#### 유저 측 시스템의 흐름
- 상품 서비스를 도입
- 카드 정보를 입력
- 결제 완료


#### 가맹점 측의 시스템 흐름
- 사이트 연동
- 메텝스 페이먼트에서 제공하는 결제 시스템 (결제 처리, 데이터 집계, 카드 회사로 부터 결제 금액 회수 -> 대금 처리, 처리 데이터 전달)
- 메텝스 페이먼트에서 제공하는 결제 피드백을 통해 가맹점의 업무 시스템에 반영한다.

#### 사업 형태에 관계 없이 다양한 비즈니스와 연동가능
- 쇼핑몰 컨텐츠 판매
- 보안 코드 서비스 (?)
- 매월 자동 결제 시스템
- 전화, 펙스 판매 등
- 3D 보안 인증 서비스 (해외 신용카드 사용 시의 문제일듯?)

#### 토큰 결제
- 카드정보를 암호화 하는 자바스크립트를 고객사에게 제공
- 고객사는 메텝스에서 제공한 암호화 자바스크립트를 통해 결제 정보 암호화
- 고객사가 프론트앤드에서 암호화를 잘 적용한다면 결제 대행사에서 제공하는 결제 페이지로의 도메인 변경 없이 고객사의 페이지에서 카드 정보를 입력하지만 고객사 서버에 카드 정보를 전송하지 않고 토큰만 전송하고 고객사의 서버에 전송하고 고객사는 결제 대행사에 토큰을 전달하여 결제를 진행해야 하기 때문에 고객사에 카드 정보가 누출되는 위험성을 줄일 수 있다.
- 하지만 고객사가 몰래 고객의 카드 정보를 수집 할 수 있기 때문에 서버로 전달되는 데이터에 문제가 없는지 심사가 필요하다. 이 부분에서 완벽한 차단을 할 수 없기 때문에 위험성을 100% 방지한다기 보다는 위험성을 줄일 수 있다고 하는 것으로 보임




---

## Reference
- https://www.metaps-payment.com/
