# DOC2VEC


# 1st
- 블로그 글뭉치로 학습한 결과를 확인하기 위하여 가까운 단어를 정렬해 보았다.
- 문제점: 가까운 단어의 결과가 대부분 조사, 어미임 -> 글뭉치의 클리닝 작업이 필요함(명사 추출의 필요성)

- 봄날은 간다
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/1st%20%EA%B2%B0%EA%B3%BC.JPG">

# 2nd
- 블로그 글뭉치의 명사를 학습한 결과를 확인하기 위하여 '자연'과 가까운 단어를 정렬
- 문제점 : 조사와 어미는 없어졌지만, 여전히 연관된 단어라고 보기 힘든 단어들이 학습됨 -> (새로운 글뭉치의 필요성)

- 봄날은 간다(BAD)
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/2nd%20%EB%B4%84%EB%82%A0%EC%9D%80%20%EA%B0%84%EB%8B%A4.JPG">
- 주토피아(BAD)
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/2nd%20%EC%A3%BC%ED%86%A0%ED%94%BC%EC%95%84.JPG">

- 마션(BAD)
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/2nd%20%EB%A7%88%EC%85%98.JPG">
# 3rd
- 위키피디아
- 문제점 : 봄날은 간다,주토피아는 양호한 결과를 보여주었지만 마션의 경우 아쉬운 결과를 보여 주고 있다.

- 봄날은 간다(GOOD)
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/3rd%20%EB%B4%84%EB%82%A0%EC%9D%80%20%EA%B0%84%EB%8B%A4.JPG">

- 주토피아
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/2nd%20%EC%A3%BC%ED%86%A0%ED%94%BC%EC%95%84.JPG">

- 마션
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/3rd%20%EB%A7%88%EC%85%98.JPG">

# 4th
- 평소 블로그 글을 읽을때 관심있는 부분만을 읽기 때문에 이점에 착안하여 문단 단위로 끊는 방법을 생각함.
- 위의 단계에서 설명글 전체를 벡터로 변환하였다면 이번 단계에서는 문단별로 벡터로 변환 뒤 일정거리를 초과하는 벡터는 제거하고 나머지벡터의 평균으로 거리를 계산

- 봄날은 간다
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/4th%20%EB%B4%84%EB%82%A0%EC%9D%80%20%EA%B0%84%EB%8B%A4.JPG">

- 주토피아
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/4th%20%EC%A3%BC%ED%86%A0%ED%94%BC%EC%95%84.JPG">

- 마션
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/3rd%20%EB%A7%88%EC%85%98.JPG">


# 5th
- 학습방법을 변경
- 기존 PV-DM 방식에서 PV-DBOW방식으로 변경 하였다.


- 봄날은 간다
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/5th%20%EB%B4%84%EB%82%A0%EC%9D%80%20%EA%B0%84%EB%8B%A4.JPG">

- 주토피아
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/5th%20%EC%A3%BC%ED%86%A0%ED%94%BC%EC%95%84.JPG">

- 마션
<img src="https://github.com/BAEintelli/Where2go-/blob/master/DOC2Vec/img/5th%20%EB%A7%88%EC%85%98.JPG">








