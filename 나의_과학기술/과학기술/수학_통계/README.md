# 수학

# 통계

statistics
    population
        data
            raw data
                spreadsheet
            error
                true value
                estimate
            sample
                representative
                sampling
                    probability sampling
                        simple random sampling
                            random number table
                        stratified sampling
                            stratification
                        cluster sampling
                        systematic sampling
                    non-probability sampling
                        judgement sampling
                        quota sampling
                            category
                    sampling error
                    non-sampling error
                        non-response error
                        response error
                            measurement error
                            processing error
            information
                inference
                    generalization
                    valid inference
            qualitative data=categorical data
                nominal data
                ordinal data
            quantitative data=numerical data
                discrete data
                continuous data
        variable
            variable value
            qualitative variable
                nominal variable
                ordinal variable
            quantitative variable
                discrete variable
                continuous variable

    descriptive statistics
        table,graph
        mean,variance

        frequency table
            frequency
            relative frequency
            qualitative frequency table
                bar graph
            quantitative frequency table
                class
                    class interval
                    class value
                histogram
        stem and leaf plot
        boxplot
            summary statistics
                quartile
                interquartile range
                range
                outlier
                
        measure of central tendency
            mean
                population mean
                sample mean
            median
        measure of dispersion
            variance
                population variance
                sample variance
            standard deviation
                population standard deviation
                sample standard deviation
            degree of freedom

    inferential statistics

    statistical survey
        who
        what
        when
        where
        how

        complete survey
            population and sompiinkl
        sampling survey
            pilot survey
            post survey

    sample space
    random variable
        discrete random variable
        continuous random variable
    probability distribution
        discrete probability distribution
        continuous probability distribution

## terminology differences : (용어 차이) 통계학이랑 다른 분야랑 용어 차이가 있다.

### data analysis

    inference : (추론) 적은 표본을 가지고 더 큰 모집단에 대한 결론을 도출하기 위한 일련의 복잡한 과정

    exploratory data analysis : (EDA) 탐색적 데이터 분석

    summary statistics : (요약통계량) 평균, 중앙값, 분위수

    chart : (도표) 상자그림, 산점도
    
    raw : 가공되지 않은

    data type : 데이터 종류에 따라 처리방법이 다르다

    numeric : (수치형) 숫자를 이용해 표현할 수 있는 데이터

    continuous : (연속형, 구간형, 실수형, 수치형) 일정 범위 안에서 어떤 값이든 취할 수 있는 데이터

    discrete : (이산, 정수형, 횟수) 횟구와 같은 정수 값만 취할 수 있는 데이터

    categorical : (범주형, 목록, 열거, factor, 요인, 명목, polychotomous,다항형) 가능한 범주 안의 값만을 취하는 데이터

    binary : (이진, 이항적, 논리형, indicator, 지표, 불리언) 두 개의 값만을 갖는 범주형 데이터

    ordinal : (순서형, 정렬된 요인) 값들 사이에 분명한 순위가 있는 범주형 데이터

    object : (객체) 값을 가진 것, 데이터를 담을 거

    rectangular data : (테이블 데이터) 이차원 행렬로 이루어진 데이터

    data frame : (데이터 프레임) 이차원 행렬로 이루어진 데이터

    feature : (열, 특징, 속성, 입력, predictor, 예측변수, 변수)

    outcome : (결과, 종속변수, 응답, 목표, 출력)

    record : (행, 기록값, case, 사건, 사례, 예제, 관측값, 패턴, 샘플)

    indicator variable : (지표변수, dummy variable, 더미) 이진 변수

    response variable : (응답변수)

    dependent variable : (종속변수)

    predictor variable : (예측변수)

    target : (목표)

    time-series data : (시계열 데이터)

    spatial data : (공간 데이터) 지리정보분야에서 object (객체)는 하나의 실체로 인식될 수 있는 것들(건물,도로,필지)와 위치 정보를 뜻하고, field (필드)는 일정 공간 상에 연속적으로 분포된 특정 계량값들(기온, 수온, 압력)을 뜻한다.

    graph data : (그래프 데이터) 추상적인 관계 데이터, 소셜 네트워크 데이터, 물류 중심지 데이터, 그래프 구조는 네트워크 최적화나 추천 시스템에 유용하다.

#### 데이터의 특징을 요약하는 다양한 요소들이 (위치, 변이) 있다.

    typical value : (대푯값) "typical" or "middle" 은 "central tendancy (중심경향성)", 대부분의 값이 어디 있는지를 location (위치) 나타내는 추정값, 산술평균과는 조금 다른 "일반적인" 평균 같은 것들 #중요개념 

    mean : (평균, average) 모든 값의 총합을 개수로 나눈 값

    weighted mean : (가중평균, weighted average) 가중치를 곱합 값의 총합을 가중치의 총합으로 나눈 값

#### 어떤 값들이 본래 다른 값들에 비해 큰 변화량을 가질 때, 예로 한 센서의 정확도가 떨어진다면 그 센서에서 나온 데이터에는 낮은 가중치를 주는 것이 합리적이고, 데이터가 부족한 관심있는 그룹에 더 높은 가중치를 적용할 필요가 있을 수도 있다.

    median : (중간값, percentile, 50번째 백분위수) 데이터에서 가장 가운데 위치한 값 

    percentile : (백분위수, quantile, 분위수) 전체 데이터의 P %를 아래에 두는 값

    weighted median : (가중 중간값) 데이터를 정렬한 후, 각 가중치값을 위에서부터 더할 때, 총합의 중간이 위치하는 데이터 값

    trimmed mean : (절사평균, truncated mean, 절단평균) 정해진 개수의 extreme value, 극단값을 제외한 나머지 값들의 평균

    robust : (로버스트하다, resistant, 저항성있다) 극단값들에 민감하지 않다는 것을 의미한다

    outlier : (특잇값, 극단값) 대부분의 값과 매우 다른 데이터 값

    anomaly detection : (이상 검출) 일반적으로 분석에서 특잇값들은 제거되지만, 이상 검출에서는 아니다.

    estimate : (추정값) 데이터로부터 계산된 값

    metric : (측정지표)

## 링크 

    [수학 공부 목록](https://github.com/rossant/awesome-math)