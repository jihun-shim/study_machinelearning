| NO  | Variable | Definition | Key | 분석가 의견 |
| --- | -------- | ---------- | --- | -----------|
|  1   | SalePrice      |   판매 가격 - 부동산의 판매 가격(달러)입니다. 예측하려는 대상 변수입니다. 
|  2   | MSSubClass     |   MSSubClass: 건물 클래스
|  3   | MSZoning       |   MSZoning: 일반적인 구역 분류
|  4   | LotFrontage    |   LotFrontage: 부동산에 연결된 거리의 선형 피트
|  5   | LotArea        |   LotArea: 부지면적: 평방 피트 단위의 부지 크기
|  6   | Street         |   Street: 도로: 도로 접근 유형
|  7   | Alley          |   골목: 골목: 골목 접근 유형
|  8   | LotShape       |   부지 모양: 부동산의 일반적인 모양
|  9   | LandContour    |   LandContour: 부동산의 평탄도: 부동산의 평탄도
|  10  | Utilities      |   유틸리티: 유틸리티: 사용 가능한 유틸리티 유형
|  11  | LotConfig      |   LotConfig: 로트 구성
|  12  | LandSlope      |   LandSlope: 부지 경사: 부지의 경사
|  13  | Neighborhood   |   이웃: 이웃: 에임스 시 경계 내의 물리적 위치
|  14  | Condition1     |   조건1: 주요 도로 또는 철도와의 근접성
|  15  | Condition2     |   조건2: 주요 도로 또는 철도와의 근접성(두 번째 도로가 있는 경우)
|  16  | BldgType       |   건물 유형: 주거 유형
|  17  | HouseStyle     |   HouseStyle: 주거 스타일
|  18  | OverallQual    |   OverallQual: 전반적인 재료 및 마감 품질
|  19  | OverallCond    |   OverallCond: 전반적인 상태 등급
|  20  | YearBuilt      |   YearBuilt: 최초 건설 날짜
|  21  | YearRemodAdd   |   YearRemodAdd: 리모델링 날짜
|  22  | RoofStyle      |   지붕 스타일: 지붕 유형
|  23  | RoofMatl       |   RoofMatl: 지붕 재질
|  24  | Exterior1st    |   Exterior1st: 외부: 집의 외부 덮개
|  25  | Exterior2nd    |   Exterior2nd: 외부2: 주택의 외부 덮개(두 개 이상의 재료가 있는 경우)
|  26  | MasVnrType     |   MasVnrType: 벽돌 베니어 유형
|  27  | MasVnrArea     |   MasVnrArea: 벽돌 베니어 면적(평방 피트)
|  28  | ExterQual      |   ExterQual: 외장재 품질
|  29  | ExterCond      |   ExterCond: 외부 재료의 현재 상태
|  30  | Foundation     |   기초: 기초 유형
|  31  | BsmtQual       |   BsmtQual: 지하실의 높이
|  32  | BsmtCond       |   BsmtCond: 지하실의 일반적인 상태
|  33  | BsmtExposure   |   BsmtExposure: 워크아웃 또는 정원 수준의 지하실 벽면
|  34  | BsmtFinType1   |   BsmtFinType1: 지하실 마감 면적의 품질
|  35  | BsmtFinSF1     |   BsmtFinSF1: 유형 1 마감 평방 피트
|  36  | BsmtFinType2   |   BsmtFinType2: 두 번째 품질 
|  37  | BsmtFinSF2     |   BsmtFinSF2: 유형 2 마감 평방 피트
|  38  | BsmtUnfSF      |   BsmtUnfSF: 지하 미완성 면적 평방 피트
|  39  | TotalBsmtSF    |   TotalBsmtSF: 지하실 면적의 총 평방 피트
|  40  | Heating        |   난방: 난방: 난방 유형
|  41  | HeatingQC      |   난방QC: 난방 품질 및 상태
|  42  | CentralAir     |   CentralAir: 중앙 에어컨
|  43  | Electrical     |   Electrical: 전기 시스템
|  44  | 1stFlrSF       |   1stFlrSF: 1층 평방 피트
|  45  | 2ndFlrSF       |   2ndFlrSF: 2층 평방 피트
|  46  | LowQualFinSF   |   LowQualFinSF: 저품질 마감 평방 피트(모든 층)
|  47  | GrLivArea      |   GrLivArea: 그레이드 이상(지상) 거실 면적 평방피트
|  48  | BsmtFullBath   |   BsmtFullBath: 지하 전체 욕실
|  49  | BsmtHalfBath   |   BsmtHalfBath: 지하 반 욕실
|  50  | FullBath       |   FullBath: 층 위 전체 욕실
|  51  | HalfBath       |   HalfBath: 층 위 반 욕실
|  52  | Bedroom        |   침실 지하층 이상 침실 수
|  53  | Kitchen        |   주방 주방 개수
|  54  | KitchenQual    |   주방 품질: 주방 품질
|  55  | TotRmsAbvGrd   |   TotRmsAbvGrd: 등급 이상의 총 객실 수(욕실은 포함되지 않음)
|  56  | Functional     |   Functional: 주택 기능 등급
|  57  | Fireplaces     |   벽난로: 벽난로 수: 벽난로 수
|  58  | FireplaceQu    |   FireplaceQu: 벽난로 품질
|  59  | GarageType     |   차고 유형: 차고 위치
|  60  | GarageYrBlt    |   GarageYrBlt: 차고가 지어진 연도
|  61  | GarageFinish   |   GarageFinish: 차고 내부 마감: 차고 내부 마감
|  62  | GarageCars     |   GarageCars: 차고 크기(차량 수용 가능)
|  63  | GarageArea     |   GarageArea: 차고 면적(평방 피트): 차고 크기
|  64  | GarageQual     |   GarageQual: 차고 품질
|  65  | GarageCond     |   GarageCond: 차고 상태
|  66  | PavedDrive     |   PavedDrive: 포장된 진입로
|  67  | WoodDeckSF     |   WoodDeckSF: 목재 데크 면적(평방피트)
|  68  | OpenPorchSF    |   OpenPorchSF: 개방형 현관 면적(평방피트)
|  69  | EnclosedPorch  |   EnclosedPorch: 밀폐형 현관 면적(평방피트)
|  70  | 3SsnPorch      |   3SsnPorch: 삼계절 현관 면적(평방피트)
|  71  | ScreenPorch    |   ScreenPorch: 스크린 현관 면적(평방피트)
|  72  | PoolArea       |   PoolArea: 수영장 면적(평방피트)
|  73  | PoolQC         |   PoolQC: 수영장 품질
|  74  | Fence          |   Fence: 펜스 품질
|  75  | MiscFeature    |   기타기능: 다른 카테고리에서 다루지 않는 기타 기능
|  76  | MiscVal        |   MiscVal: 기타 기능의 $가치
|  77  | MoSold         |   MoSold: 판매된 월
|  78  | YrSold         |   YrSold: 판매된 연도
|  79  | SaleType       |   판매 유형: 판매 유형
|  80  | SaleCondition  |   판매 조건: 판매 조건
