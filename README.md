## Git-Study

#### 제목 크기 작성하기

#### h4 특수문자 샵4개

```text
// git 로컬 레파지토리 생성 이후 원격 레파지토리 push 방법
git init
git status
git add .
git status
git commit -m "test commit"
git remote add origin "your github remote repository url"
git push origin master
```

```text
// git 원격 레파지토리 clone 이후 수정사항 push 방법
git clone "your github remote repository url"
git status
git add .
git status
git commit -m "test commit"
git push
```

```text
---------------------- S : 위에꺼 보고 내가 이해한것--------------------------------

1. 깃설치 먼저하고 cmd에서 git --version 으로 설치확인


	// 최초 깃에 올릴때
	git init                                              	// workspace에 .git 파일이 생김 (파일>옵션>보기> 숨김파일,폴더표시)
	git status                                            	//상태확인
	git add . 	                                        // 빨간상태를 초록상태로 변경
	git status 	                                        // 초록색상태로 변경된것을 확인
	git commit -m "메세지"                                   // 커밋
	git remote add origin "깃 원격(리모트) 레파지토리 주소"    // 해당 주소로 add
	git push origin master		                         // 해당 레파지토리로 푸시

```text
	// 최초 올리고 수정시 
	git add .
	git stuats
	git commit -m "커밋메세지"
	git push origin master 
	
---------------------- E : 위에꺼 보고 내가 이해한것--------------------------------
```


```text
---------------------- S : 2019.12.16 최신버전 --------------------------------

1. 깃 설치 후 cmd에서 git --version 으로 설치 확인
2. 깃허브에서 레파지토리 생성 후 주소 복사
3. 작업하고자 하는 폴더에서 마우스 우클릭으로  "Git Bash Here" 로 터미널 열기
4. git clone 복사한 저장소 주소
	git clone https://github.com/noCountJun/GitTest.git

5. README.md 파일 생성 후 저장
6. git status                                    // 상태 확인 (빨간색으로 되어 있음)
7. git add *                                    // 파일을 스테이지 영역으로 이동 (녹색으로 변경됨)
8. git status                                    // 녹색 변경 확인
9. git commit -m "git test Commit"    			// git commit -m "커밋 메세지 입력"
10. git push origin master                	// 해당 레파지토리 push
	
----------------------  :2019.12.16 최신버전--------------------------------
```

_이탤릭체는 언더바 사용_

`#`는 숫자키 1 옆에 single quote로 특수문자 표시가 가능함


#### 소스코드 작성하기

```java

public class MyClass{
  public static void main(String args[]){
    System.out.println("소스코드 블럭지정 방법 ");
    System.out.println("```java");
    System.out.println("소스코드내용 ");
    System.out.println("```");
  }
}

```

#### 링크 작성하기

[블로그 링크는 [블로그 제목]와 (블로그 url) 을 붙여서 만들수 있습니다.](https://shlee0882.tistory.com)

#### 인용구문 작성하기

> 인용구문은 ">" 기호를 사용합니다.

#### 테이블 작성하기

이름 | 나이 | 직업
--- | --- | --- |
이상현 | 30 | 코더 |
김길동 | 28 | 디자이너 |
조현영 | 29 | 기획자 |
김지숙 | 26 | 테스터 |

#### 순서있는 리스트 작성하기

- 동물
  1. 포유류
  2. 양서류

#### 순서없는 리스트 작성하기

* 과일
  * 딸기
    * 빨간색
    * 상큼하다.
  * 바나나
    * 노란색
    * 달다.
  * 블루베리
    * 파란색
    * 시원하다.
    * 리스트는 *을 사용하여 만듭니다.
    
#### 체크 박스 작성하기

- [x] 체크박스1
- [ ] 체크박스2
- [ ] 체크박스3
    
#### 강조 표현하기

**강조표현은 별2개를 사용하여 표현합니다. 조지아 맥스** ~~최애커피 물결표시 2개로 표현합니다.~~ 맛있어요!!!
    
[Git 관련 명령어 모음](https://shlee0882.tistory.com/190)


#### 이미지 넣기
    
![강아지](https://i.pinimg.com/originals/79/a9/41/79a941de1bfe8d9fbea2369fef8c2e35.jpg)

#### 이모티콘 사용하기

:smile:
