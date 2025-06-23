
NER 모델 테스트 기록
---
model_1_name = "Leo97/KoELECTRA-small-v3-modu-ner"
model_2_name  = "FacebookAI/xlm-roberta-large-finetuned-conll03-english"
model_3_name  = "jinwoowef/final_crf"

-----------------------------------
롯데는 AI 기반의 고객 맞춤형 여행 서비스를 제공하기 위해 대한항공과 함께 새로운 플랫폼을 개발하고 있으며, 이를 통해 여행객들에게 보다 편리한 예약과 서비스를 제공할 계획입니다.
model 1: 롯데: B-OG  AI: B-TR  대한항공: B-OG  
model 2: ▁롯데: I-ORG  ▁대한: I-ORG  항공: I-ORG  
model 3: 
-----------------------------------
친환경 기술에 대한 관심이 높아지는 가운데 GM Korea와 대우조선해양은 차세대 전기차와 친환경 선박 기술을 함께 개발하고 있으며, 이를 통해 전 세계 시장에서의 입지를 강화할 것으로 보입니다.
model 1: GM: B-OG  Korea: I-OG  대우: B-OG  ##조선: I-OG  ##해: I-OG  ##양: I-OG  전기차: B-AF  
model 2: ▁GM: I-ORG  ▁Korea: I-ORG  ▁대: I-ORG  우: I-ORG  조선: I-ORG  해양: I-ORG  
model 3: 
-----------------------------------
네이버는 최근 카카오와 협력하여 AI 챗봇 기능을 개선하고, 사용자 경험을 극대화할 계획을 발표했습니다.
model 1: 네이버: B-OG  카카오: B-OG  AI: B-TR  ##봇: I-TM  
model 2: ▁네이버: I-ORG  ▁카: I-ORG  카: I-ORG  오: I-ORG  
model 3: 
-----------------------------------
쿠팡은 하림과의 협약을 통해 신선 식품 배송 서비스를 강화하고 있으며, 고객 만족도를 높이는 데 주력하고 있습니다.
model 1: 쿠팡: B-OG  하림: B-OG  
model 2: ▁: I-ORG  쿠: I-ORG  팡: I-ORG  ▁하: I-ORG  림: I-ORG  
model 3: 
-----------------------------------
아모레퍼시픽은 신세계와 함께 뷰티와 라이프스타일을 결합한 새로운 복합 매장을 오픈할 예정입니다.
model 1: 아모레: B-OG  ##퍼: I-OG  ##시: I-OG  ##픽: I-OG  신세계: B-OG  
model 2: ▁아: I-ORG  모: I-ORG  레: I-ORG  퍼: I-ORG  시: I-ORG  픽: I-ORG  ▁신: I-ORG  세계: I-ORG  
model 3: 
-----------------------------------
현대자동차는 효성과의 협력을 통해 전기차 충전 인프라를 확충하고, 친환경 자동차 보급에 힘을 쏟고 있습니다.
model 1: 현대: B-OG  ##자동: B-OG  ##차: I-OG  효성: B-OG  
model 2: ▁현대: I-ORG  자동차: I-ORG  ▁: I-ORG  효: I-ORG  성과: I-ORG  ▁: I-ORG  
model 3: 
-----------------------------------
농협은 동국제약과 손잡고, 건강기능식품 개발에 착수했으며, 이를 통해 농산물의 부가가치를 높이고 있습니다.
model 1: 농협: B-OG  동국: B-OG  ##제: I-OG  ##약: I-OG  
model 2: ▁: I-ORG  농협: I-ORG  ▁동: I-ORG  국: I-ORG  제약: I-ORG  ▁: I-ORG  
model 3: 
-----------------------------------
한국전력공사는 두산중공업과 협력하여 신재생 에너지를 활용한 발전소를 건설하고 있으며, 에너지 전환에 박차를 가하고 있습니다.
model 1: 한국전력: B-OG  ##공사: I-OG  두산: B-OG  ##중: I-OG  ##공업: I-OG  
model 2: ▁한국: I-ORG  전: I-ORG  력: I-ORG  공사: I-ORG  ▁두: I-ORG  산: I-ORG  중: I-ORG  공: I-ORG  업: I-ORG  
model 3: 
-----------------------------------
롯데는 한국수력원자력과 함께 친환경 에너지 솔루션을 도입해 향후 탄소 중립 달성에 기여하고자 합니다.
model 1: 롯데: B-OG  한국: B-OG  ##수: I-OG  ##력: I-OG  ##원: I-OG  탄소: B-MT  
model 2: ▁롯데: I-ORG  ▁한국: I-ORG  수: I-ORG  력: I-ORG  원: I-ORG  자: I-ORG  력: I-ORG  
model 3: 
-----------------------------------
삼양은 CJ제일제당과 협력해 새로운 식품 기술을 개발하고 있으며, 이를 통해 글로벌 식품 시장 진출을 모색하고 있습니다.
model 1: 삼양: B-OG  CJ: B-OG  ##제: I-OG  ##일: I-OG  ##제당: I-OG  
model 2: ▁삼: I-ORG  양: I-ORG  ▁C: I-ORG  J: I-ORG  제: I-ORG  일: I-ORG  제: I-ORG  당: I-ORG  
model 3: 
-----------------------------------
한온시스템은 기아와의 협력을 통해 차세대 전기차에 적용할 냉난방 시스템을 개발하고 있습니다.
model 1: 한: B-OG  ##온: I-OG  ##시스: I-TM  ##템: I-TM  기아: B-OG  전기차: B-AF  
model 2: ▁한: I-ORG  온: I-ORG  시스템: I-ORG  ▁기: I-ORG  아: I-ORG  
model 3: 
-----------------------------------
대한항공은 한화와 손잡고 차세대 무인 항공기 개발에 착수했으며, 글로벌 시장에서의 경쟁력을 높이기 위해 협력을 강화하고 있습니다.
model 1: 대한항공: B-OG  한화: B-OG  무인: B-AF  항공기: I-AF  
model 2: ▁대한: I-ORG  항공: I-ORG  ▁한: I-ORG  화: I-ORG  
model 3: 
-----------------------------------

