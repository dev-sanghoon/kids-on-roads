# 어린이 보호구역 무단횡단 관측 시스템
CCTV에서 무단횡단자를 감지하고, 운전자에게 위험상황을 TTS와 네비게이션에 표시로 전달하는 시스템입니다.  
4명의 팀원이 참여했으며, 제로베이스 데이터 스쿨 파이널 프로젝트 결과물입니다.  
[발표 PPT](https://docs.google.com/presentation/d/1uwYJ2r_uVWttqV8qrVTlghyhynitfAQOw1BSz16xqko/edit?usp=drive_link) /
[요약](https://docs.google.com/presentation/d/1HQ0d0n-Y7lD1ToSu4zesNNe1vbFjfIUntuF1bou-c6Q/edit?usp=drive_link)

### 주피터 노트북
- `inference.ipynb`: 모델로 객체 탐지 및 분할하고, 이를 활용하여 데모 영상을 생성합니다. 클래스를 활용해보았습니다.
- `yolo_100_epochs`: 100 epoch로 훈련시킨 파인튜닝 코드입니다.
- `yolo_300_epochs`: 100 epoch로 훈련시킨 파인튜닝 코드입니다.

### 업로드되지 않았지만 사용한 디렉토리
- `data/`: 훈련 시 활용한 데이터입니다.
- `demo-prepare/`: 시연 영상 제작을 위한 데이터입니다.