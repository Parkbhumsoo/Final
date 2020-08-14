# 코인세탁소 입지 분석 

###프로젝트 소개

'시간빈곤'에 시달리는 현대인은 '가사노동'에 투자되는 시간을 줄이기위해 비용을 감수하는 추세입니다.

     ....‘육아 및 가사는 노동이다’라는 데 대해 응답자의 72.9%(729명)이 ‘그렇다’고 응답했다. 이들 가운데 약 17%에 달하는 122명은               
     ‘과거(3년전)에는 가사가 노동이라고 생각하지 않았지만, 지금은 가사 역시 노동이라 생각한다’고 응답...
     출처: “내 시간 쓸 수 있다면”… ‘살림 아웃소싱’에 지갑 여는 현대인 [S 스토리] http://m.segye.com/view/20191220510314


이번 분석은 '세탁' 가사노동의 대안으로 늘어나고 있는 '코인세탁소'를 분석합니다.

서울에 위치한 코인세탁소의 위치를 수집하여, 예측가능한 잠재고객층(1인가구, 맞벌이가구) 및 그들의 거주 예상지역 등의 변수 간 유의한 상관관계를 이루는 지 파악합니다. 기존 서비스 지역의 특성 파악을 통하여, 새로운 서비스를 제공하는 것을 목표로 합니다.


1.가설설정
- 1인가구는 생활면적과 시간의 제한으로 '코인세탁소' 이용비율이 높을 것이다.
- 주거인구 집중지역의 경우, 환경적 요인(장마, 미세먼지, 온도 등)으로, 대용량 세탁 및 기계건조에 대한 수요가 많을 것이다.

2.진행 방향
- 서울에 있는 코인세탁소 주소를 크롤링
- 상업지/1인가구/직업가구(독립변수)등의 데이터 
- 코인세탁소와 독립변수에 의한 상관관계분석
- 주소를 위/경도 좌표화하여 시각화

3.구현기술
- 머신러닝

4.확장방향
- 환경적 위치를 분석하여, 코인세탁소의 신규창업입지 추천서비스
