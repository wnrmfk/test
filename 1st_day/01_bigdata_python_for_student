
# coding: utf-8

# # 1일차 오후: Data Science and Python

# In[13]:


from IPython.display import Image


# ---

# # 수업의 목적

# - 우리에겐 2.5일 밖에 없습니다.
# - Python을 완벽하게 마스터 하겠다!는 아닙니다.
# - **Python이라는 도구를 어디서 어떻게 활용할 것인가**
# - **업무 중 생산된 데이터를 Python 이라는 도구로 어떻게 분석할 것인가**
# - **Python 이라는 도구로 이런 것도 가능해? 이런 거하려면 이런 저런 패키지를 사용하면 되겠네?**
# - 라는 아이디어를 얻어갔으면 좋겠습니다.
# - 직접 실습을 하겠지만 2.5일 안에 마스터는 불가능하고 자가 학습이 가능할 정도의 아이디어를 가져갔으면 좋겠습니다.

# ---

# # 오늘 수업의 목표

# - 나는 오늘 데이터 사이언스의 필요성과 중요성 인식했다.
# - 나는 오늘 데이터 사이언스에서 Python을 활용하는 큰 그림을 알 것만 같다.
# - 나는 오늘 Python을 어떻게 설치하는지 알았고 패키지를 설치하는 방법을 배웠다.
# - 나는 오늘 Python의 기본적인 문법을 살펴봤고 실습을 통해 프로그래밍한다는 게 뭔지 좀 알게 됐다.
# - 나는 오늘 실습을 통해 Jupyter Notebook의 기본적인 사용방법을 익혔다.
# - 나는 오늘 드디어 Python을 맛 보았다. 유익한 하루였다.

# In[2]:


Image(url='http://20timeline.s3.amazonaws.com/wp-content/uploads/2014/10/52822-c6b1c20ac311b797aa331062c5eb4f3d-400x315.jpg')


# In[5]:


Image(url='http://mblogthumb1.phinf.naver.net/20160407_84/beundeom1998_1460018282528MqAks_PNG/1460017862902.png?type=w800',
     width=300, height=300)


# ---

# # 수업 시 필요한 것1

# - 컴퓨터(노트북)
# - 운영체제(Windows, macOS, or Linux) -> Windows 기준으로 설명할 예정
# - Python -> Python 배포판인 Anaconda를 사용할 예정
#     - Windows 7 Enterprise K Edition인 경우엔 Anaconda가 최소한으로 설치될 가능성이 있음
#     - 최소한으로 설치가 된다는 건 필요한 여러 패키지가 설치되지 않고 Python만 설치가 된다는 뜻입니다.
#     - 이런 경우 pip을 통해서 추가적으로 설치를 하면 됩니다.
# - pip (Python Package Manager)
# - Jupyter Notebook(ipynb 파일)

# ---

# # 수업 시 필요한 것2

# ## 눈 보다는 손!!

# ---

# # 수업 시 필요한 것3: How to open ipynb file

# - 이메일을 통해 받은 ipynb(IPYthon NoteBook) 파일은 본인이 원하는 곳에 복사해둡니다.
# - 다만 Jupyter Notebook이 익숙해지기 전까지는 Desktop에 복사해두길 권장합니다.
# 
# 
# - 예를들어
# 1. 바탕화면에 `python`이라는 폴더를 만든다.
# 2. `C:\Users\사용자계정\Desktop\python`에 `material.zip` 압축을 푼다.
# 3. 시작 > Jupyter Notebook을 실행한다.
# 4. 압축을 풀면 나오는 `ipynb`파일을 클릭하여 오픈한다.

# ---

# # 0. Jupyter Notebook 소개 및 실습

# 해당 노트북에 직접 필기 하면서 공부해보세요.

# ## 0.1 기본

# ### 1) 셀(Cell)

# - 하나의 실행 단위 블럭을 뜻한다.
# - 크게 2가지가 있다.
#     1. Code: 코드가 실행되는 블럭
#     2. Markdown: Markdown 문법이 적용되는 노트

# In[3]:


# Code Cell
print("hello")


# Markdown Cell

# ## 0.2 2가지 모드

# 1. Edit Mode: 셀 안의 내용을 편집할 수 있는 상태
#     - 셀 위에서 Enter 키를 눌러 셀 내용을 편집할 수 있다.
# 2. Command Mode: 셀 밖에서 해당 노트북을 명령어로 컨트롤할 수 있는 상태
#     - 셀 위에서 ESC 키를 눌러 명령을 내릴 수 있다.
#     - `h`를 눌러 도움말을 볼 수 있다.

# ## 0.3 유용한 커맨드 모드 명령어

# - CTRL + Enter: 셀 실행
# - y: 셀을 Code 블록으로 변환
# - m: 셀을 Markdown 블록으로 변환
# - a: 위에 셀 추가
# - b: 아래에 셀 추가
# - dd: 셀 삭제

# 각자 위 명령어를 연습해보자~

# ## 0.4 명령어에 대한 도움이 필요할 때

# - Jupyter Notebook에서
#     - 특정 함수/클래스에 커서를 옮긴 후
#     - Shift + Tab
#     - Docstring을 보여주는 명령어임
#     - Docstring을 만들지 않으면 보여지지 않음

# ## 0.5 유용한 Markdown 문법

# # Header 1
# 
# ## Header 2
# 
# ### Header 3
# 
# - Bulleted List
#     - Bulleted List
# 
# 
# 1. Numbered List
#     - Bulleted List
#     - Bulleted List
# 2. Numbered List
#     1. Numbered List
#     2. Numbered List
# 
# **Emphasis**
# 
# *Italic*
# 
# `block`
# 
# ```
# Script
# ```

# ## 0.6 이 외 Jupyter Notebook의 다양한 기능

# 1. Magic Command (http://ipython.readthedocs.io/en/stable/interactive/magics.html)
#     - Line Magic
#         - `%load`
#     - Cell Magic
#         - `%%writefile`
# 2. 다양한 모듈이 존재
#     - ex) `from IPython.display import Image`
#     - https://ipython.org/ipython-doc/3/py-modindex.html

# In[4]:


from IPython.display import Image


# In[5]:


Image(url='http://blogfiles9.naver.net/MjAxNzA1MjRfMTk5/MDAxNDk1NjAzNTE0MjQw.HziNRQMJyDIPUuIy_Qp7GCuFZ6zJm6H_jOV40jKNlvwg.6AYchX7DPnZZQii3RagjQWXBS8tfHg3LHhzaob035NQg.PNG.midashan/LG%C0%FC%C0%DA_%B7%CE%B0%ED.png')


# In[6]:


from IPython.lib.display import YouTubeVideo


# In[7]:


YouTubeVideo('ZZuD6iUe3Pc', width='800', height='550')


# ---

# # 1. Big Data and Data Science

# ## 1.1 Big Data

# - 빅데이터란 **기존 데이터베이스 관리도구의 능력을 넘어서**는 대량(수십 테라바이트)의 정형 또는 심지어 데이터베이스 형태가 아닌 비정형의 데이터 집합조차 포함한 데이터로부터 **가치를 추출**하고 **결과를 분석**하는 기술이다. (Wikipedia)
#     - 기존 데이터베이스 관리도구의 능력을 넘어서
#         - 기존 데이터베이스 관리도구(DBMS): Oracle, MSSQL, MySQL, PostgreSQL etc.
#         - MS Excel이나 위에서 언급한 DBMS는 몇 백만 데이터 간 수정, 추가, 질의 등의 작업 시 Performance가 떨어지는 경향이 있다.
#         - 때문에 빅데이터를 다룰 때 서버를 여러 대 나누어 대용량 데이터를 처리하는 개념인 **분산 처리 기술**이 중요해 진다.
#         - 이 떄 사용하는 기술들이 Apache Hadoop, Apache Spark 등이 있다.
#     - 가치를 추출
#         - 수 많은 데이터에서 가치를 추출하는 것, 즉 **Data Mining**을 하는 것은 정보의 홍수 시대에 살고 있는 지금 필요한 기술로 여겨진다.
#     - 결과를 분석
#         - 가치를 추출한 후 해당 가치에 따라 **기업의 의사 결정이 이루어지는 행동으로 이끌어 낼 수 있어야** 한다.
# - **큰 데이터를 처리하는 기술력에 치중되어 있음(ex. 분산처리)**
#     - Apache Hadoop
#     - Apache Spark
#     - etc.

# ## 1.2 Data Science

# ### 1) 정의

# 데이터를 단순히 분류하거나 분석하는 것 말고 **데이터 속에 담긴 패턴이나 미래 예측에 도움이 되는 신호를 찾는 것**을 말합니다.

# ### 2) Skillset

# In[8]:


Image('images/Data_Science_VD.png')


# [American Data Scientist, Drew Conway, 2013](http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram)

# ### 3) Data Science Process

# 데이터 파이프라인이라고도 합니다.
# 1. 데이터 수집
# 2. 데이터 전처리
#     - Transforming
#     - Munging
#     - Wrangling
#     - Preprocessing
# 3. 데이터 분석
#     - EDA(Exploratory Data Analysis)
# 4. 데이터 예측
#     - Machine Learning
# 5. 데이터 시각화
#     - Reporting

# In[9]:


Image('images/ds_process.png')


# ### 4) Data Science에서의 다양한 Tool과 Python의 위치

# In[11]:


Image('images/ds_tool.png')


# ### 5) Data Science와 Big Data, Machine Learning과의 관련성

# In[5]:


Image('images/ai_data-science-diagram.jpg')


# ---

# ---

# # 2. Python의 다양한 활용

# ## 2.1 Data Science에서 Python은 어떻게 활용되는가

# In[6]:


Image('images/bigdata_with_python.png')


# ### 1) 단계별 Python 패키지

# 1. Collecting: BeautifulSoup, Selenium, Scrapy etc.
# 2. Processing(Munging, Wrangling, etc.): NumPy, pandas etc.
# 3. Storing: 각 Database와 연결된 라이브러리 제공 ex) pymysql, mymongo etc.
# 4. Explorary Data Analysis: NumPy, pandas etc.
# 5. Machine Learning: Scikit Learn, SparkML, Tensorflow, etc.
#     - scikit-learn: 머신러닝 프레임워크입니다. 분류, 회귀, 클러스터링, 차원 축소처럼 머신러닝에서 자주 사용되는 다양한 알고리즘을 지원합니다.
# 6. Communication/Reporting/Building Data Product: Django, Flask etc.

# ## 2.2 Python 과 R은 누가 많이 사용할까

# ### 1) Kaggle

# - 호주 맬버른 기반 스타트업
# - 데이터 과학자들이 머신러닝을 이용해 주어진 과제를 푸는 콘테스트 사이트 (http://www.kaggle.com/)
# - 캐글을 이용하는 데이터 전문가는 60만명 (2017년 3월)
# - [구글의 캐글(Kaggle) 인수, AI 분야에 미칠 영향은?](http://www.ciokorea.com/news/33510) (2017년 3월)

# 출처: https://www.kaggle.com/surveys/2017?utm_medium=blog&utm_source=nofreehunch&utm_campaign=EOY+mailer+2017

# #### 2017년 Data Science 분야에서 가장 많이 사용하는 Tool

# In[10]:


Image('images/kaggle_most_tool.png')


# #### 2017년 Data Science 분야에서 가장 많이 사용하는 Tool for Statistician

# In[11]:


Image('images/kaggle_tool_for_statistician.png')


# > #### Python과 R은 주로 누가 쓸까?
# > - Python: Engineer/Machine Learning Engineer/Software Developer/Data Scientist/Comuputer Scientist
# > - R: Statistician/Data Analyst/Business Analyst

# #### 데이터 과학자로써 처음으로 배우기에 추천하는 Language by Kaggle

# In[14]:


Image('images/kaggle_recommend.png')


# ### 2) Python 개발자 설문조사 (by JetBrains)

# - 2000년에 설립된 체코 회사
# - 통합 개발 환경 프로그램을 만드는 소프트웨어 회사, Python 세계에서는 PyCharm 이라는 인기있는 IDE를 만들었다.

# 출처: https://www.jetbrains.com/research/python-developers-survey-2017/

# #### Python으로 개발하는 분야

# In[15]:


Image('images/python_survey_usage.png')


# #### Data Scientist들이 주로 사용하는 Library

# In[17]:


Image('images/survey_most_lib.png')


# #### Data Scientist들이 추가적으로 사용하는 기술들

# In[18]:


Image('images/survey_addi_tech.png')


# ---

# # 3. Python 역사 및 Trend

# ## 3.1 역사

# - 1991년 네덜랜드 국립 연구소의 Guido Van Rossum에 의해 발표 (현 2018년, 27년의 역사)
# - “Python“이라는 이름은 코메디 프로그램 “Monty Python’s Flying Circus”에서 유래
# - Python의 원래 의미는 그리스 신화에 나오는 거대한 뱀
# - 2000년 Python 2 발표
# - 2008년 Python 3 발표
#     - Python 2의 경우 2020년까지만 Maintenance가 이루어질 예정

# ## 3.2 Trend

# ### Google Trend: 2008년 ~ 2018년 Python 검색 추이 - 지역별

# In[7]:


Image('images/1_2_interest_by_region.png')


# ### Google Trend: 2008년 ~ 2018년 Python 검색 추이, 6위 Seattle 7위 Seoul - 도시별

# In[8]:


Image('images/1_2_interest_by_city.png')


# ### Google Trend: 2008년 ~ 2018년 Related Topics and Related Queries

# Rank|Related Topics|Related Queries
# --|--|--
# 1|pandas - Sofwware|python flask
# 2|Raspberry Pi - Computer|flask
# 3|GitHub - Downloadable software|raspberry pi
# 4|PyCharm - Computer program|pycharm
# 5|pip - Package manager|pandas
# 6|scikit-learn - Software|python pip
# 7|Sublime Text - Software|python argparse
# 8|Codecademy - Company|python the hard way
# 9|MongoDB - Topic|codecademy python
# 10|Flask - Web framework|codecademy

# ---

# > # CASE STUDY - 기업신용평가모델: 부도율 예측하기

# ---

# # 6. Python 101

# ## 6.1 설치

# - http://www.python.org
# - Anaconda (Python 배포판)
# - brew for mac
# - apt for ubuntu
# - yum for CentOS

# - 설치가 잘 되었는지 확인해보겠습니다.
# - Anaconda를 정상적으로 설치한 경우
#     - `시작 > 모든 앱 > Anaconda > Jupyter Notebook`이 있는지 확인
#     - `실행 > cmd`를 통해 `Terminal`을 실행한 후 `python`을 입력하고 엔터 (빠져나오려면 `exit()`)
# - Anaconda가 정상적으로 설치되지 않았거나 Python만 설치한 경우
#     - `실행 > cmd`를 통해 `Terminal`을 실행한 후 `python`을 입력하고 엔터 (빠져나오려면 `exit()`)

# ## 6.2 Python을 이용한 프로그래밍 기초

# ### 1) 프로그래밍

# In[2]:


YouTubeVideo("GrsqZSDMKO4", start=150, width=700, height=450)


# 나를 대신해 마트에 가서 새우깡 한 봉지을 사오도록 지시하는 상황
# 
# 1. 일단 마을버스 777번을 타세요.
# 2. 3개의 정거장을 지난 후 4번째 정거장에서 하차하세요.
# 3. 정거장 우측으로 100m를 직진한 후 A 마트로 가세요.
# 4. 마트의 2층 식품 판매대에서 과자 한 봉지를 사세요.
# 5. 1층 결제 코너에서 C 카드를 통해 결제하시고 포인트는 제 핸드폰 뒷 자리 4자리로 적립하세요.
# 6. A마트 맞은편 버스 정류장에서 777 버스를 타세요.
# 7. 세 개의 정거장을 지나 4번째 정거장에서 하차하세요.
# 8. 집으로 돌아와서 새우깡을 뜯어 새우깡 하나를 집어 저에게 먹여주세요.

# - 컴퓨터에게 어떤 일을 시킬 때도 위와 같은 형태로 **지시 내용을 나열**해야 합니다.
# - 이처럼 명령어가 나열된 것을 **프로그램**이라고 하며, 프로그램을 작성하는 행위를 **프로그래밍**이라고 합니다.

# ### 2) 프로그래밍을 나에게 적용한다면?

# - 간 밤 라인별/모델별 생산량을 파악해 Delivery를 만족할 수 있는지 분석/예측 차트/테이블을 만든다.
# - 최근 유가증권시장/코스닥시장에서 거래량이 60일 평균치에 비해 2배 이상 급등한 종목을 나에게 알려준다.
# - 고객 만족도 조사 파일을 받아 해당 제품의 만족도가 낮은 이유에는 어떤 걸들이 있는지 보여준다.

# ### 3) 연산(Operator)

# In[1]:


1 + 2


# In[2]:


16 / 2


# In[3]:


3 * 9


# ### 4) 변수에 문자열 또는 숫자 넣기(할당연산자(=))

# In[32]:


naver = 601000  # naver라는 변수에 601000 라는 숫자를 할당(데이터가 있는 위치를 매핑)


# In[11]:


a = 1  # 숫자
b = 2


# In[12]:


a + b


# In[15]:


lgelectronics = "LG전자"  # 문자


# In[ ]:


lgelectronics


# In[17]:


lge


# In[16]:


lge + " 가산 R&D Campus"


# > **Q. 위에 선언한 lge와 숫자 1을 더하면 어떻게 될까? 직접 계산해보자.**

# In[ ]:


# 여기에 코드를 작성해보세요.


# ### 5) 데이터가 어떤 Type인지 확인하기

# - 프로그래밍을 할 때 데이터를 숫자 유형인지 문자 유형인지 등에 따라 구분합니다.
# - 이것을 데이터 타입이라고 합니다.
# - Python 에서는 아래와 같은 것들이 있습니다.

# Variable Name|Value|Data Type
# --|--|--
# dog_name|'Freddie'|str (short for string)
# age|9|int (short for integer)
# is_vaccinated|True|bool (short for Boolean)
# height|1.1|float (short for floating)
# birth_year|2001|int (short for integer)

# In[20]:


data = "1"


# In[21]:


type(data)


# In[22]:


type(a)


# In[23]:


isinstance(data, str)


# In[23]:


try:
    data + 1
except TypeError:
    if isinstance(data, str):
        print("문자열이 포함되어 있어 계산이 안됩니다!")


# ### 6) 변수에 특정값 넣기(리스트에서 가져와서 할당하기, 함수 반환값을 통해 할당하기)

# In[25]:


lge_employee = ['홍길동', '정약용', '배성심', '김아무개']  # list 값 할당하기
lge_employee


# In[26]:


best_employee = lge_employee[0]  # indexing 해서 할당하기
best_employee


# In[47]:


from random import randint

number = randint(1, 5)  # 함수 반환 값 할당하기
number


# > **Q. 위에서 배운 것을 이용해서 lge_employee 리스트 중 랜덤하게 한 명을 선택해 출력해보자.**

# ### 7) 좌항과 우항의 값이 같은지 큰지 작은지 확인해보자 - 비교연산자

# In[78]:


'A' == 'A'


# In[79]:


1 == '1'


# In[80]:


1 != '1'


# In[81]:


1 >= 3


# In[82]:


100 <= 300


# ## 6.3 특징

# ### 1) Interactive Shell

# - 서로 대화하듯 명령어를 입력하는 순간 바로 명령어에 대한 대답을 볼 수 있는 Shell을 제공한다.
# - Shell: Input을 받아서 OS에 넘겨주는 Terminal

# In[10]:


Image('images/interactive_shell.png')


# - 꼭 빠져나오자! (`exit()`)

# ### 2) 들여쓰기(Indentation)

# - 들여쓰기는 함수 몸체, 조건문 루프, 클래스 등 다양한 코드 블록을 나타낸다.
# - 들여쓰기로 탭(tab)을 사용할 수 있지만 권장하지 않는다.
# - 스페이스(space) 4칸을 사용하는 것이 파이썬 커뮤니티에서 보편적으로 선호되고 권장하는 방식이다.
# - Python을 처음으로 접하는 사용자들은 익숙하지 않아서 들여쓰기에서 많은 에러가 발생한다.

# In[84]:


my_age = 15
if my_age >= 19:
    print("19살 이상이네요!")
    print("당신은 성인입니다!")
else:
    print("That's nono!")
    print("미성년자입니다!")


# In[85]:


# 들여쓰기가 제멋대로인 경우 에러 발생
are_u_sure = True
if are_u_sure:  # if 변수가 True(참)이면
  print("Starting with 2 spaces")  # 2칸
   print("That's nono!")  # 3칸
else:
    print("It's false.")  # 4칸


# > **Q. 아래 조건을 이용해서 내 신용등급을 출력해보자. (위에 나온 if 조건문을 이용)**
# >
# > 100 ~ 90: 1
# >
# > 89 ~ 80: 2
# >
# > 79 ~ 70: 3
# >
# > 69 ~ 0: 4

# In[11]:


my_age = 80
if 100 >= my_age >= 90:
    print("1")
elif 90 > my_age >= 80:
    print("2")
else:
    print("3")


# ### 3) Code Block starts with 콜론(:)

# - 코드 블록의 시작은 콜론(:)으로 한다.
# - 문맥 상 들여쓰기를 기준으로 들여쓰기가 없는 곳이 코드 블록의 끝이 된다.

# > **Package Manager**
# > - Python은 매우 다양한 오픈 소스가 있습니다.
# - 특정 프로그램의 패키지 또는 라이브러리라고하며 간편하게 패키지를 다운받고 설치하게 도와주는 프로그램을 Package Manager라고 합니다.
# - 특히 Python에서는 이 Package Manager를 `pip`라고 합니다.
# - pip: Pip Installs Package or Python
#     - Python 설치와 함께 설치됨.
# - 사용법
#     - Package 검색: pip search 패키지명
#     - 설치한 Package 목록보기: pip freeze
#     - 최신 버전으로 패키지 설치: pip install 패키지명
#     - 특정 버전으로 패키지 설치: pip install 패키지명==특정 버전
#     - 패키지 삭제: pip uninstall 패키지명

# In[12]:


import requests  # 실행해보기, 안되시는 분?


# > **실습**
# >
# > 1. 내 컴퓨터에 설치된 Python 패키지 목록 확인하기
# >
# > 2. `requests`라는 패키지 설치하기

# In[90]:


import requests

l = requests.get('http://www.lge.com/')
status_code = str(l.status_code)
if status_code.startswith('2'):
    print("Successful response: {0}".format(status_code))
else:
    print("It's false.")


# In[14]:


a="바나나"
b="우유"
print("나는 오늘 아침에 {0}과 {1}을 먹었다".format(a,b))


# ### 4) 세미콜론(;)

# - Java, JavaScript 같은 언어의 경우 한 문장의 마지막에는 세미콜론(`;`)을 붙인다.
# - 하지만 Python은 없어도 된다.
# - 그러나 붙여도 에러는 나지 않는다.

# In[21]:


print('Hello World')


# In[22]:


print('Hello World');


# ### 5) 주석(Comment)

# - Single line: #
# - Multiple lines
#     - ''' ... '''
#     - """ ... """

# In[8]:


"""
www.naver.com 페이지를 요청하여
응답받은 결과값(HTTP Status Code)을 판별
Python에서는 쌍따옴표(")는 3개로 된 주석은
보통 모듈/함수의 Docstring에 사용한다.
"""

import requests

naver = requests.get('http://www.lge.com/')

'''
naver라는 requests 객체는 status_code 라는 속성을 가지고 있다.
status_code는 예를 들어 200, 404, 500 등과 같으며 숫자이다.
숫자를 문자열로 바꿔주는 함수인 str를 사용하여 문자열로 바꿔준다.
'''
status_code = str(naver.status_code)

if status_code.startswith('2'):  # 만약 코드가 2로 시작한다면
    print("Successful response: {0}".format(status_code))
else:
    print("It's false.")


# ### 6) 0부터 시작

# In[15]:


lst = ['냉장고', '세탁기', '에어콘']  # 리스트(list)


# In[16]:


lst


# In[17]:


lst[0]


# In[18]:


lst[1]


# In[23]:


lst[0:]  # 0번째 부터 2번째 전까지 가져와라 (Slicing)


# In[20]:


lst[:2]  # 0번째 부터 2번째 전까지 가져와라 (Slicing)


# In[21]:


from random import randint


# In[29]:


random_number = randint(0, 2)

print(random_number)
print(lst[random_number])  # lst[2]


# > **Q. 아래 주식 데이터 중 티엘아이 종목의 2018년 5월 4일 데이터만 출력하라**
# 
# > - 아래는 numpy와 pandas를 사용하고 있습니다. 따라서 numpy와 pandas 패키지가 기본적으로 설치되어있어야 합니다.
# - 아래 소스는 아직 배우지 않은 pandas의 DataFrame이지만 위와 똑같은 방법으로 Indexing할 수 있습니다.
#  
# > 설치방법
# - `pip install numpy pandas`

# In[50]:


# pandas라는 패키지로 dummy data를 만드는 부분
import numpy as np
import pandas as pd

dates = pd.date_range('20180501', periods=10)
stocks = ['A', 'B', 'C', 'D']
values = np.random.randint(0, 2000, size=(10, 4))

df = pd.DataFrame(values, index=dates, columns=stocks)
df


# > #### 살펴본 김에 시각화도 해볼까요?!
# >
# > **prerequisite: pandas는 matplotlib 라는 시각화 패키지를 사용하고 있으므로 기본적으로 matplotlib가 설치되어있어야 합니다.**

# In[52]:


get_ipython().run_line_magic('matplotlib', 'inline')


# In[51]:


df.plot()


# In[53]:


df.plot();


# > **! 한글이 깨지네요!! 한글 폰트를 설정 해야합니다~ 내일 본격적으로 다뤄보겠습니다.**

# > **Q 차트 사이즈가 너무 작아요! 어떻게 해볼까요?**

# In[46]:


# 괄호 안에 파라미터값을 넣어주면 간단하게 해결됩니다. 어떤 값을 넣어야할까요? 찾아봅시다.


# ### 7) 패키지 > 모듈 > 클래스|함수|변수

# In[46]:


# from 패키지.모듈 import 함수
from numpy.random import randint


# In[47]:


randint(1000, 2000, size=(7, 4))


# - 패키지: 디렉토리
# - 모듈: 파일(확장자: py)
# - 클래스|함수|변수: 모듈 안의 객체
# - 점(.)으로 접근

# ### 8) 동적 타입(자료형)

# In[58]:


number = 0  # 할당 연산자


# - 보통은 변수를 선언할 때 앞에 붙여 사용한다.
# - ex) `int num = 10;`
# - ex) C, C#, C++, Java
# - 이렇게 미리 선언하는 방식을 정적 타입이라 한다.
# 
# 
# - 그러나 Python은 타입을 지정하지 않아도 된다.
# - ex) `num = 10`
# - ex) JavaScript, Ruby, Python

# ### 9) 파이썬의 모든 것은 객체 ⭐️

# - 파이썬 프로그램에서 모든 데이터는 객체(object)라는 개념을 사용하여 저장된다.
# - 가장 기본이 되는 데이터 타입인 숫자, 문자열, 리스트, 사전은 다 객체이다.
# - 이를 더 잘 이해하기 위해선 객체지향프로그래밍을 알아야 한다.
# - 객체를 만드는 것은 클래스이다.
# - **클래스 = 속성 + 행동**
# - Object-Oriented Programming(객체지향프로그래밍, OOP)에서 객체가 바로 클래스를 통해 만들 수 있는 것이다.

# **사람 클래스**
#     - 인스턴스(객체): 홍길동
#         - 속성: 국적=대한민국, 체력=93
#         - 메소드(행동): 벌주기
#     - 인스턴스(객체): 셜록홈즈
#         - 속성: 국적=영국, 자격증=[탐정], 통찰력=99
#         - 메소드: 추리하기, 파이프피우기

# **점(.)으로 접근 가능!**
# ```python
# 홍길동 = 사람()
# print(홍길동.국적)
# 홍길동.벌주기(target='탐관오리')
# print(홍길동.체력)  # -1
# 
# 셜록홈즈 = 사람()
# print(셜록홈즈.국적)
# print(셜록홈즈.자격증)
# 셜록홈즈.파이프피우기(n=10)  # n=-1
# 셜록홈즈.추리하기(algorithm='')
# ```

# In[25]:


type(1)


# In[28]:


type('this is string!')


# In[31]:


dir('this is string!')


# In[119]:


'this is string!'.title()


# ---

# # 7. 실습: Naver 쇼핑 크롤러(Crawler)

# > **Naver 쇼핑(http://pc.shopping2.naver.com/) 에서 인기있는 세탁기 모델을 찾아보자**

# ## 7.0 개발 알고리즘

# 1. 먼저 네이버 쇼핑에 접속한다.
# 2. 세탁기 카테고리에 접근한다.
# 3. 원하는 필터를 선택한다. (LG 트롬, LG 통돌이, LG전자)
# 4. 해당 URL을 복사하여 `url` 이란 변수에 저장한다.
# 5. `requests` 패키지를 이용해 `url`에 해당하는 페이지를 요청하여(request) 가져온다(get).
# 6. HTML 태그를 파싱(Parsing) 해주는 `BeautifulSoup`이란 패키지로 파싱한다.
# 7. 파싱된 이후에는 컴퓨터가 해당 HTML 태그를 이해할 수 있게 된다.
# 8. 따라서 세탁기 모델에 해당하는 HTML 태그를 찾는다(select).
# 9. 출력한다.
# 10. 끝

# ## 7.1 필요 패키지

# 1. requests
# 2. beautifulsoup4

# > **Q. 위 패키지를 pip를 이용해 설치해보자. 이미 설치가 되어있다면 아래 from .. import ..을 실행해보자.**

# In[4]:


get_ipython().system('pip install bs4')


# In[5]:


import requests
from bs4 import BeautifulSoup


# In[46]:


url = 'https://search.shopping.naver.com/search/all.nhn?origQuery=%EC%97%90%EC%96%B4%EC%BB%A8&pagingIndex=1&pagingSize=40&viewType=list&sort=rel&cat_id=50002522&minPrice=20000&maxPrice=999000000&frm=NVSHPRC&query=%EC%97%90%EC%96%B4%EC%BB%A8'


# In[47]:


r = requests.get(url)


# In[48]:


r.text


# In[49]:


r = requests.get(url)
soup = BeautifulSoup(r.text, 'html.parser')


# In[50]:


soup


# In[51]:


goods = soup.select('ul.goods_list li div.info a.tit')
goods


# In[45]:


lst = [1,2,3,4,5]
for a in range(0,10):
    print("지금 List에서 꺼낸 값은", a,"입니다.")


# In[52]:


print("네이버 쇼핑 에어컨 순위")
for prod in goods:
    print(prod['title'])


# > **Q. 가장 인기있는 순서대로 세탁기를 살펴봤는데... 어떤 걸 더 해볼까요?**
# >
# > **모델 T15DS인 제품이 몇 위인지 살펴보고 싶은데 눈에 잘 안보이네요. 각 모델이 몇 위인지도 출력해볼까요?**

# In[58]:


print("=네이버 쇼핑 에어컨 순위=")
num=0
for prod in goods:
    num=num+1
    #num +=1
    print(num, prod['title'])


# > **죄송합니다!!! 사실 좀 더 간편하게 할 수 있는 방법이 있습니다! `enumerate`**

# In[53]:


for seq, prod in enumerate(goods, start=1):
    print(seq, prod['title'])


# ---

# # Wrap up

# 1. Jupyter Notebook
# 2. Big Data
# 3. Data Science
# 4. Data Pipeline
#     1. Collecting: BeautifulSoup, Selenium, Scrapy etc.
#     2. Processing(Munging, Wrangling, etc.): NumPy, pandas etc.
#     3. Storing: 각 Database와 연결된 라이브러리 제공 ex) pymysql, mymongo etc.
#     4. Explorary Data Analysis: NumPy, pandas etc.
#     5. Machine Learning: Scikit Learn, SparkML, Tensorflow, etc.
#     6. Communication/Reporting/Building Data Product: Django, Flask etc.
# 5. Programming을 한다는 것
# 6. Python 기초 문법: 할당연산자, 비교연산자, 수치연산자, 데이터 타입, 클래스
# 7. Python 특징: 들여쓰기, 콜론, 주석처리방법(#)
# 8. 주식 Dummy Data를 통해 pandas DataFrame 만드는 것과 특정 날짜만 가져와 보았습니다.
# 9. 네이버 쇼핑 크롤러를 간단하게 만들어보았습니다.
