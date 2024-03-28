## IMDb TOP 2000 데이터셋을 통해 정보를 얻어보자.
![image](https://github.com/ksm1113/movie_trend_by_IMDb/assets/153878577/4fb883c0-a60e-492b-bea2-7fbfe157901f)    
IMDb(Internet Movie Database)의 약자로, 영화,배우, 드라마, 비디오 게임 등에 관한 정보를 제공하는 온라인 데이터베이스이다.    
IMDb가 제공하는 TOP 2000 데이터셋을 활용해 영화에 관한 TMI들을 알아볼 예정이다.

자료 출처 : [https://www.kaggle.com/datasets/sukhmandeepsinghbrar/netflix-all-movie-ratings-by-imdb](https://www.kaggle.com/datasets/prishasawhney/imdb-dataset-top-2000-movies)

### 데이터 구성
열 : 영화 이름, 개봉 년도, 러닝타임(분), 평점, 장르, 감독, 주연, 총 수익

### 데이터 전처리
1. 장르가 한 열에 정리 되어 있어 분할한다
2. 결측치가 있는지 검사한다    
  2.1 개봉 년도 항목에서 형식에 맞지 않는 값 발생하여 xxxx형식으로 수정하였습니다.    
  2.2 총 수익의 경우 결측치가 존재하나 얻을 방법이 없어 수익 관련 분석시 제외할 예정    
*데이터의 개수가 상대적으로 적은편이라 스프레드시트와 파이썬을 이용하였습니다.

### 전처리 결과
![image](https://github.com/ksm1113/movie_trend_by_IMDb/assets/153878577/9f3fead7-580f-4778-8cd4-c75faf03faea)

### 데이터 분석 주제
1. 최신 영화는 옛날에 비해 작품성이 떨어진다?
2. IMDb가 선정한 최고와 최악의 영화
3. 감독,배우로서 제일 많은 수익을 올린 TOP 5
4. 시대별 최애 장르와 소외 장르
5. 수익 TOP 10 영화
6. 감독과 배우 최고의 콤비를 찾아서

