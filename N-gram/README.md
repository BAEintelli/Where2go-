# N-gram
- 고전언어 모델중 하나인 N-gram방식을 사용하여 어느정도의 결과를 활용가치가 있는가를 확인하기 위해 사용해 보았다.
- 단어가 보통 3자리 미만 이기 때문에 윈도우 사이즈를 3으로 하였다.
- 현재 결과상 대체적으로 결과가 나쁘지는 않으나 long term dependency와 희소성있는 단어에서 문제가 발생하기 때문에 다른 임베딩 방식이 필요

- 봄날은 간다
<img src="https://github.com/BAEintelli/Where2go-/blob/master/N-gram/img/n-gram%20%EA%B2%B0%EA%B3%BC%20%EB%B4%84%EB%82%A0%EC%9D%80%20%EA%B0%84%EB%8B%A4.JPG">

- 주토피아
<img src="https://github.com/BAEintelli/Where2go-/blob/master/N-gram/img/ngram%20%EA%B2%B0%EA%B3%BC%20%EC%A3%BC%ED%86%A0%ED%94%BC%EC%95%84.JPG">

- 마션
<img src="https://github.com/BAEintelli/Where2go-/blob/master/N-gram/img/ngram%20%EB%A7%88%EC%85%98.JPG">
