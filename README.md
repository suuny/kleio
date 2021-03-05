# KPT

### week1

**작업내용**
1. github에 새로운 repository 생성
2. snowpack, svelte 개발환경 설정
3. plan'it 인트라넷 프로젝트 Sketch 파일을 Figma로 이식

+repository 생성은 문제없었다.<br>
+snowpack, svlete를 함께 설치할 수 있도록 안내되어 있는 페이지를 찾아서 진행했다.<br>
+Sketch 파일은 Figma에서 열기만 해도 대부분 잘 보였다.

-Sourcetree를 이용해 github에 소스를 올리려고 했는데, 여기서 실패했다.<br>
-아마 새로 프로젝트를 시작하면서 개인계정으로 접속하여 회사계정 간 간섭이 있는 것으로 추측한다.<br>
-몇 가지 방법 시도했으나 실패, 좀 더 찾아보기로 했다.<br>
-기존 Sketch 프로젝트에서 요소들을 복사해서 사용하고 싶었으나(속도가 빠르니까),<br>
Inspect 탭에서 제공되는 소스코드가 예상과 달리 사용하기 힘들고, Auto layout을 익히기에 좋지 않다고 판단된다. 

### week2
**3월 2일 - 3일**
Figma 작업
- kit를 atoms와 molecules, organisms로 세분화시키는 작업
- 네이밍 법칙으로 계층화 시키는 부분이 편했다.
- Frame / Auto layout / Group / Instance 등이 꼬여서 자가복제가 되는 광경 자주 목격함
- constraints 컨트롤이 잘 안됨
- 컨테이너를 기본으로 하여 레이아웃을 짜 나가는 습관이 있어, 각 엘리먼트를 가지고 구성하는 방식에서 많이 헤맸다.

- Frame이 artboard와 개념이 헷갈려서 메모한다.<br>
>Frames. A foundational element that can act as a top-level contatiner. It represent areas ro components.

**3월 4일**
- Sourcetree 접속계정 정상화를 하기 위해 시도한 것
    - 키체인 삭제 후 다시 등록
    - SSH keygen (어떤 건지 모름)
    - Account 계정 수정 (이 등록된 계정의 역할을 모르겠음)
    - Setting / Global user information 해제 후 수정 ==> 성공
- component -> instance -> component -> error! 이유가 뭘까
- Swap instance 편하다

**3월 5일**
- 구체적으로 organisms을 만들어나감.
- molecules에서는 없던 간격 문제가 많이 발생한다.
- 본격적으로 component의 variants와 property 사용.
- 도대체 layer의 네이밍은 어느 정도까지 해야할까
- figma 디자인을 코드로 가져오는데 생각보다 구조 및 스타일이 복잡하고 정확하지 못하다.
- 다른 플러그인을 사용해봤지만 아직 미흡

