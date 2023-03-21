# AI_CP1_DS PROJECT 
---
프로젝트 구조는 다음과 같습니다.
```
AI_16_youngkwan_CP1_DS
├── data
│   └── video
├── models
│   ├── best.pt
├── results
└── test.ipynb
```

```
New_Sample
├── 원천데이터
│   ├──  TS1.대형차
│       ├── 불법차량
│           └── *.JPG
│       └── 정상차량
│           └── *.JPG
├── 라벨링데이터
│   ├──  TS1.대형차
│       ├── 불법차량
│           └── *.JSON
│       └── 정상차량
└──          └── *.JSON



- **data**: 모델 추론의 입력값으로 사용할 영상 파일들이 저장되어 있는 폴더입니다.
- **models**: 추론에 사용될 사전 학습된 모델의 가중치 파일(best.pt)이 저장되어 있습니다.
- **results**: yolov5에 의해 생성된 결과 영상이 해당 폴더에 저장되게 됩니다.
- **test**: 해당 패키지가 정상적으로 작동하는지 확인하는 test.ipynb 파일을 포함하고 있습니다.

---
##사용법
1. 해당 레포지토리를 클론해주세요
    - https://github.com/0Kwan/AI_16_youngkwan_CP1_DS.git
2.  AI_16_youngkwan_CP1_DS 폴더내에서 레포지토리 한개를 추가로 클론해주세요
    - https://github.com/ultralytics/yolov5.git
3. !pip install -r requirements.txt 완료해주세요  
4. test.ipynb 파일을 열고 주석을 달아둔 부분만(총 2번) 변경해주세요(파일명 및 경로)
5. test.ipynb 파일내 코드를 실행시키면 results에 파일이 생깁니다.
