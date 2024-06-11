# sw개론 과제

- - -

### 리눅스 명령어: top
##### 아무 옵션도 주지 않은 top 입력 시 상단과 하단의 두 개의 영역으로 구분되어 내용이 표시된다. 상단에는 시스템에 대한 전반적인 요약 정보가, 하단에는 프로세스별 구체적인 정보가 표기된다. 정보는 3초마다 업데이트된다.
> top 정렬을 위한 명령어에는
> * P(%cpu순으로 정렬)
> * M(%mem순으로 정렬)
> * N(pid순으로 정렬)
> * T(time+순으로 정렬)
> 이 있다.

![top예시](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FRZup6%2FbtrI8QMZboA%2FPFgF1f7UT6aoXk95dZgnLK%2Fimg.png)

### 리눅스 명령어: ps
##### ps명령어는 현재 실행 중인 프로세스의 정보를 제공한다.
> * 옵션에는 -e, -f, -u <username>, -p <proces ID>, -l, -a, -x가 존재한다.
> ps 명령어를 통해 시스템 리소스를 소비하는 프로세스를 식별하고, 필요한 경우 관련 프로세스를 종료하거나 조정 가능하다.
> ps 명령어와 grep을 조합하면 특정 프로세스의 정보를 쉽게 검색할 수 있다. 이 방법은 시싀템에서 특정 프로세스의 상태를 모니터링하는 데 유용하다.

![ps예시](https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAxNzA2MTFfMTY2%2FMDAxNDk3MTQ5MDE4OTkx.v4YrwjBf651vBVNzKwM9xjBY0SEpu3bmyv-BoBqpmksg.hUafgHpseGkZSljeI5mYp44x6H5toGSFpFXy1l-9Kk0g.JPEG.sera3579%2F2.JPG&type=sc960_832)

### 리눅스 명령어: jobs
##### jobs 명령어는 현제 세션의 작업 상태를 출력한다.
> * 옵션으로는 -l, -n, -p, command 등이 존재한다.
> jobs 명령어는 작업이 중지된 상태, 백그라운드로 진행 중인 작업 상태, 변경되었지만 보고되지 않은 상태 등을 표시한다.
> running은 진행중임을 뜻하고, done은 종료되고 0을 반환했음을, done(code)는 완료되었으나 0이 아닌 코드를 반환했음음 의미한다. 
> 이 외에도 다른 상태들이 존재한다.

![jobs예시](https://dbscthumb-phinf.pstatic.net/4938_000_1/20170710154910976_RX87MMBQ3.jpg/ka38_149_i2.jpg?type=w575_fst_n&wm=Y)

### 리눅스 명령어: kill
##### kill 명령어는 프로세스를 종료시킨다.
> pid 로 종료시킬 프로세스 ID나 이름을 지정한다.
>  > * -s로 전달할 시그널의 종류를 지정한다. 여기에는 시그널 이름이나 번호를 써준다.
>  > * -l로 시그널로 사용할 수 있는 이름들을 보여준다. 이것은 /usr/include/linux/signal.h 파일에서도 알 수 있다.
>  > * -1,: -HUP 프로세스를 재활성화한다.
>  > * -9: 프로세스를 강제로 종료시킨다.

![kill예시](https://dbscthumb-phinf.pstatic.net/4938_000_1/20170705204102763_BIV3YDDFB.jpg/ka38_154_i2.jpg?type=w575_fst_n&wm=Y)

아아아


아아아
