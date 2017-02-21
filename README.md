# BOJ-SRC-DOWNLOADER

## BOJ(Beakjoon Online Judge, acmicpc.net) Source Downloader

### BOJ에 제출한 자신의 코드를 다운로드 받아주는 스크래핑 프로그램입니다.
 소스코드를 하나씩 다운로드 받다가, 너무 귀찮고 힘들어서 만들었습니다.
 
 동작 방식은 아래와 같습니다.
  1. 로그인 
  2. user 페이지 이동, 해결한 문제 번호 추출
  3. 문제 명세 (내용, 입력,출력, 힌트) 추출
  4. 문제 status를 보면서 가장 최근 제출 코드 추출 (AC 받은)
  5. 끝나지 않았다면 3으로 이동 

단순히 자신이 제출한 소스코드를 다운로드 받기 위한 프로그램일 뿐, 악의, 불법적 용도로는 사용을 금합니다.
또한 acmicpc.net(Startlink)에 많은 부하를 주어 받는 불이익에 대해서는 책임지지 않습니다.

문제에 대한 모든 권리는 acmicpc.net 또는 각 문제 출제자에게 있습니다.

사용에 의해 발생되는 **모든 법적 책임은 사용자에게 있습니다.**

### 의존성 
1. JSoup 1.10.2 (프로젝트에 포함되어 있음)
2. jdk 1.8.0_40

### 실행 방법
1. BOJ 아이디와 비밀번호를 Crawl.java 23, 24번째 줄에 입력합니다.
2. 프로젝트를 빌드하고, 실행합니다.

### Output
1. 프로그램이 워크스페이스에 폴더를 생성합니다.
   result/problem
   result/source   
2. 자신이 해결한 문제의 소스코드와 문제 명세를 크롤링해서 각 폴더에 출력합니다.


제작 : jcdgods@gmail.com, [블로그](jcdgods@tistory.com)

비상업용, 무료, 출처표기, 발생하는 모든 책임은 사용자에게 있음.