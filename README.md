# TodoList
TodoList는 할 일 관리 앱으로, 생산성을 높여주는 앱입니다. 다른 앱들과 달리, 직관적이고 깔끔한 인터페이스가 특징이고, 코드에는 여러가지 설명을 붙여 다른 사람들도 이 코드를 보면서 학습을 할 수 있습니다.


## Motivation
평소 할 일 관리를 소홀히 하는 편이라, 해야할 일들을 잊어버리는 경우가 종종 있습니다.
이를 해결하기 위하여 여러 가지 노력을 해보았으나, 실패하였습니다.
노트는 잊어버리거나 안 가지고 다녀 문제가 있었으며,
휴대폰 같은 경우는 돈을 주고 앱을 구매한 경우에도 불구하고 사용법과 용량이 아쉬워 결국 환불하였습니다.
이러한 경우를 해결하기 위해 용량에서 벗어나고, 사용법도 정말 간단한 앱을 개발하기로 하였습니다.


## Project
### TableViewController
이 함수는 메인 화면을 컨트롤합니다. 메인 화면에서는 우측 상단에 추가 버튼과, 좌측 상단에 수정 버튼, 그리고 중간에는 표가 그려저있습니다. 이 함수는 수정, 그리고 할 일 표시를 담당합니다. 함수의 구성은 기본적인 TableView에 관한 셋팅입니다.

<img src="https://github.com/ycostdalp/TodoList/blob/main/%E1%84%86%E1%85%A6%E1%84%8B%E1%85%B5%E1%86%AB.png" width="300px" height="600px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>

<img src="https://github.com/ycostdalp/TodoList/blob/main/%E1%84%89%E1%85%A1%E1%86%A8%E1%84%8C%E1%85%A6.png" width="300px" height="600px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>


### AddViewController
이 함수는 추가 화면, 그리고 수정 화면을 컨트롤합니다. 추가 화면과 수정 화면의 구분은 Segue를 통한 값의 변화에 따라 결정이 되며, 이러한 값을 이용해 버튼을 보여주거나 숨길 수 있습니다. 처음에는 추가 화면과 수정 화면의 뷰컨트롤러를 다르게 설정하려고 기획했으나, 개발하고 보니 비슷한 부분이 많아 코드를 통일화하여 간편화를 많이 하였습니다.

<img src="https://github.com/ycostdalp/TodoList/blob/main/%E1%84%8E%E1%85%AE%E1%84%80%E1%85%A1.png" width="300px" height="600px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>

## Closing
기본에 충실한 앱입니다. 그러다 보니 매우 깔끔한 인터페이스를 자랑하며, 다른 앱과는 다른 빠름을 자랑합니다. 
다른 개발자 분들도 이러한 앱을 개발하며 좋은 계기가 될 수 있기를 바랍니다.
