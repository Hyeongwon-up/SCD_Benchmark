# SCD_Benchmark

전체 데이터 개수 : 10726

Error.csv
: GumTree 와 ChangeDistiller 의 툴을 사요하여 검출할 때 오류가 생기는 파일을 DB에 저장.

에러가 발생했던 데이터 개수 : 18


비교에 사용한 데이터 개수: 10709

전체 파일 개수 


1. fileId ,change_type ,entity type
    GumTree != CHD 10636

2. fileId, Change type 별 edit 수 비교

    GumTree != CHD : 10517

3. fileId 별 edit 수 비교.

    GumTree != CHD  : 9830
    
    

DISTINCTTABLE.csv

: fileId별로 GT와 CHD 의 개수가 다른 fileId 항목.

RANDOM_EXPORT.ipynb
:DISTINCTTABLE 로 부터 읽어와서 RANDOM으로 fileId100개 뽑아 LIST.csv 로 저장한다.

LIST.csv 
: 위에서 추출한 추출 한 목록.


예측_분석_비교.excel
: 랜덤으로 뽑은 100개를 직접 파일을 old와 new로 비교하여서 프로그래머 관점으로 변화를 파악하고
 GT 와 CHD 파일 과 출력을 비교할 수있다.
 
 
 
    
    
    

 
    


