# python3
if문
if(value>=80):
	print("마스크를 쓰세요")
else:
	print("미세먼지가 좋습니다.")

	
마스크를 쓰세요


관계연산자
== 같다
 !=다르다
 >>> 1==1
True
>>> 1==2
False
>>> 1!=3
True
>>> 56565656565!=5656565656565
True
>>> 1!=5
True
>>> 1!=1
False
False
>>> "문자"=="문자"
True
>>> '문자'=='문제'
False
>>> 1=='1'
False
>>> 1==1.0
True
>>> 
>>> 'Apple'=='apple'
False
>>> val=10
>>> val>=5
True


score = int(input('숫자를 입력하세요'))
if score % 2==0:
    print('짝수입니다.')
else:
    print('홀수임.')
    
  else if ==> elif
  
  print('Hello 명아')
score = int(input('점수를 입력하세요'))
if score >= 90:
    print('에이A')
if score >= 80:
    print('비B')
if score >= 70:
    print('씨C')
if score >= 60:
    print('디D')
if score >= 50:
    print('이E')
else:
    print('재시험')
Hello 명아
점수를 입력하세요89
비B
씨C
디D
이E
    

print('Hello 명아')
score = int(input('점수를 입력하세요'))
if score >= 90:
    print('에이')
elif score >= 80:
    print('비')
elif score >= 70:
    print('씨')
elif score >= 60:
    print('디')
elif score >= 50:
    print('이')
else:
    print('재시험')

Hello 명아
점수를 입력하세요100
에이
 
 

users=['choi','lee','kim']
id = input('아이디를 입력하세요')

if id in users:
    pw = input('비밀번호를 입력하세요')
    if pw == '1111':
        print('사용자가 맞습니다')
    else:
        print('암호가 틀렸습니다.')
    
else:
    print('입력된 사용자가 아닙니다.')
    

아이디를 입력하세요lee
비밀번호를 입력하세요5151
암호가 틀렸습니다.
