# Intro-to-ML
Introduction to Machine Learning Mid-term Project, 2023 spring.

Data: http://www.kobis.co.kr
![image](https://github.com/NamYoonJi/Intro-to-ML/assets/136441326/1fef7177-104b-44aa-abb3-5dd4b04c30d4)
## Data preprocessing
- 레이블링
```
clean_movie['전국'] = clean_movie['전국'].astype('int64')
clean_movie.loc[clean_movie['전국'] >= 5000000 ,'전국'] = 1
clean_movie.loc[clean_movie['전국'] < 5000000 ,'전국'] = 0
```
```
gamdok_bisection = pd.merge(clean_movie, main_gamdok, how='inner', left_on='감독', right_on='주요 감독')
```

- 원핫인코딩
- 성수기 개봉 데이터 분리
  
## Data Analyzing & Prediction
### Random Forest
### Gradient Boosting
### XGBoost
### LightGBM


### Compare scores


