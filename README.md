# Generative Deep Learning _with Pytorch_
## 1. 소개

**O'Reilly - Generative Deep Learning _with Pytorch_**

이 레포지토리는 O'Reilly 에서 출판한 _David Foster_ 의 책 <Generative Deep Learning>을 pytorch로 구현한 내용을 담고있습니다. 딥러닝을 공부하는 것을 넘어 연구에 활용하고자 하는 분들은 pytorch에 기반하여 코드를 빌드 할 일이 많을테지만 책이 tensorflow 기반으로 쓰여있어서 구현을 따라하는 데 어려움을 느끼실 것입니다. 그래서 책의 내용을 그대로 따라하되 저의 torch 스타일을 가미하여 코드를 작성했습니다. 원본 tensorflow 코드에 비하여 모듈화 되지 않은 코드가 있지만 이것은 뒤집어 말하면 .ipynb 파일 속에 과정을 차근차근 담았다는 뜻이기도 합니다. 저는 이왕 .ipynb(a.k.a. 쥬피터) 형식으로 코드를 작성할 것이라면 가급적 그 파일 하나에 코드가 다 있어야 교육용으로는 더 좋다고 생각합니다.

+ 코드 구현이 없는 챕터 1은 빠졌고 아주 기초적인 딥러닝 CNN을 구현하는 챕터 2도 생략하겠습니다. 이 부분은 제가 흉내낼 수도 없을 정도로 양질인 강의나 자료가 구글에 매우 많습니다!
+ 한국어로만 쓰여졌습니다.
+ 일부 학습에 실패한 사례도 있습니다:grimacing::grimacing:. 구현이 잘못 되었을 수도 있고 파라미터 세팅이 만족스럽지 못한 경우도 있을테니 수정하는대로 바로 업데이트 하겠습니다.

## 2. 활용법
- 다음의 prerequisites가 요구됩니다.
    - 기초적인 통계적 지식
    - pytorch, numpy 문법 이해
    - GPU를 사용할 수 있는 컴퓨팅
    - O'Reilly - Generative Deep Learning 을 구비해주세요.
- 이 레포지토리를 원하는 로컬 위치에 clone합니다.
    - ```git clone https://github.com/HongSungRae/Generative-Deep-Learning-for-Pytorch.git```
- 가상환경을 열어서 ```requirements.txt```의 라이브러리 환경을 맞추어주세요.
    - 그렇게 특별한 library가 사용되지 않으니 그냥 로컬 환경에서 돌려도 문제 없을겁니다.
    - 단, 가용할 수 있는 GPU가 1개 이상은 있어야합니다.
- 챕터 1,2 는 스스로 읽으면서 코딩하거나 넘어가세요
- 책의 내용을 이해하면서 코드에 달린 설명을 함께 읽습니다. 코드를 한 칸 한 칸 돌려보면서 알고있는 지식과 비교합니다.

## 3. For who don't use Korean
- Examples of the O'Reilly book 'Generative Deep Learning'
- The book contatins only tensorflow codes. For pytorch users, I wrote source code using pytorch.
- Unfortunately, this repository is not written in English. However, there is high-quality material available in English at [[2]](https://github.com/pyoungkangkim/Generative-Deep-Learning-Code-in-Pytorch), so please refer to it.

## Contact
- sun.hong@kaist.ac.kr

## Reference
[1] https://github.com/davidADSP/GDL_code
[2] https://github.com/pyoungkangkim/Generative-Deep-Learning-Code-in-Pytorch
[3] Generative Deep Learning by _David Foster_, 2019