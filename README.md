# sakeL-archive
#### 주진표


# 진행전
## 목적 및 기대 효과
많은 유튜버들이나, 시청자가 sake L의 유튜브 댓글을 모두 보려고 했으나, 실패를 하였고, 유튜브에 댓글을 검색하는 기능이 없어 중복댓글을 쓰고 비난을 받는 사람들이 있어, 좀더 직관적으로 댓글들을 보고, 검색할 수 있을것을 기대하여 공개하기로 했다.<br>
수집된 자료가 부족하지만, 머신러닝이나 기계학습에 도움이 되었으면 좋겠다는 바람이 있음.
## 수집 방법
주로 파이썬의 "Selenium" 모듈과 댓글 제공 사이트를 파싱하여 [노동요](https://www.youtube.com/watch?v=TpPwI_Lo0YY), [이마트](https://www.youtube.com/watch?v=QUXKib-jfEM)의 댓글 데이터를 수동 / 자동적으로 수집함.
## 제공 방법
json파일로 제공할 계획임. 댓글 작성자는 추후 업데이트를 통해 함께 제공할 계획이나, 아직은 수집하지 않음.<br>
24시간 모든 정보를 자동적으로 수집하면, 트래픽 문제와 하드웨어상으로 문제가 발생할 수 있으므로, 자주 데이터가 업데이트 되지는 않을것임.
# 진행중
## 시행착오
수집시 이용할 컴퓨터가 i3 3세대인 컴퓨터라서, 순수한 Selenium 모듈을 이용하여 자동스크롤을 통해 댓글을 수집하는데 하드웨어적 한계가 있음.
#### -> 유튜브 댓글을 제공해주는 사이트가 있어, Selenium 모듈 및 BeautifulSoup을 통해 HTML태그를 제거후, 리스트로 저장하고 JSON으로 파일을 만듬.
생각보다 무의미하거나, 홍보성 댓글이 많아서 sake L과 관련된 댓글만 제공하기 힘듬
#### -> Json 추출시 if문을 통해 링크가 포함된 모든 댓글을 포함하지 않음, ㅋㅋ나 ㅎㅎ와 같은 문자가 3개 이상 붙어있는경우 모두 2개로 치환.

# 진행후
.
.


## 업데이트 노트
v1.0(2020.10.18) : 리포지토리를 생성하고 README 파일을 작성함.
