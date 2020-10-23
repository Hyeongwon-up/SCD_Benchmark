# SCD_Benchmark


## SourceCode Differencing techniques (GumTree, ChangeDistiller)이 생성한 출력 내용.

Apache Commons Lang(LANG), Math(MATH), Collections(COLLECTIONS), Apache Ivy(IVY) 에 식별기법을 적용하여 얻은  출력 파일. (CTET 모델)
Header : fileId, tool, change_type, entity_type, edit

+ 전체.csv

위 데이터에서 GumTree 만을 검출.

+ GUMTREE.csv

위 데이터에서 ChangeDistiller 만을 검출.

+ Changedistiller.csv


## 오로지 변경사항의 수만을 GT와 CD 비교결과 내용. ( 2.3 세번째 결과 및 3 의 샘플링을 하기 위한 파일)

Main_work sheet : 각 파일의 변경사항의 수를 Count 하고 이를 정리한 시트.
1.GT>CD sheet :  GumTree 변경사항의 수가 ChangeDistiller 보다 큰 파일 정리.
2.GT<CD sheet :  GumTree 변경사항의 수가 ChangeDistiller 보다 작은 파일 정리.
3.GT=CD sheet :  GumTree 변경사항의 수가 ChangeDistiller 와 같은 파일  정리.

+ CompCount_GT_CD.xlsx

## 변경사항의 수가 5 개 이하인 파일을 필터링(filtering)을 하여 3,808 개의 파일.
Header: fileId
+ TESTLIST.csv

## 3,808 파일 중 랜덤으로 100개의 파일.

+ LIST.CSV

## 100개의 파일을 사람이 예측한 변경내용과 기법이 출력한 변경내용을 비교 한 파일.

사람 sheet : 사람이 예측한 변경내역
도구 sheet : 100개의 파일에 대한 기법이 출력한 변경내역
비교 sheet : 사람과 도구의 비교 ( tool 1 : GumTree, tool 2 : ChangeDistiller, Tool 3 : 사람)





