# CS231n_study / Notion Link
* BOAZ 19/20th Winter study, CS231n repository  
* Session Date: Wed, 22:30 (PM 10:30)
* Notion Link: [Notion](https://url.kr/4bin67)
* Zoom Link: [Zoom](https://korea-ac-kr.zoom.us/j/96772869170?pwd=U1ZiSHJFeWJ6QXVNdHg3Z2JWMHM1Zz09)

# Introduction of Assignment #1
* Assignment는 간단한 Machine Learning 및 Backpropagation에 주력을 두는 단원입니다.
* 첫번쨰주에 소개했던 Trace Trick을 잘 활용하면 SVM, Softmax, Two Layer 모두 쉽게 구현하실 수 있을 겁니다!

# Cover of Assignment #1
* 모든 스터디 진행인원은 **Lecture 1 - Lecture 4**까지 수강하여야 합니다.
    * Lecture 1 | Introduction to Convolutional Neural Networks for Visual Recognition
    * Lecture 2 | Image Classification
    * Lecture 3 | Loss Functions and Optimization
    * Lecture 4 | Introduction to Neural Networks
* 시청 이후 흥미로운 사실이나 질문 사항을 아래 설문을 통해 작성합니다.
    * [설문 조사 링크](https://forms.gle/xGHBMjkTgrAZg3Hs8)

# Assignment #1 study materials
* [Assignment 1 Info](https://cs231n.github.io/assignments2022/assignment1/)
* [~ Lecutre 4](http://cs231n.stanford.edu/schedule.html)
* [Youtube Link](https://www.youtube.com/watch?v=vT1JzLTH4G4&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)

# 질문 설문 링크
* 설문 링크는 01/20(금) 공개됩니다.
    * [(Remind)설문 조사 링크](https://forms.gle/xGHBMjkTgrAZg3Hs8)
* 모든 분들은 답을 **01/22(일)** 까지 해주세요. 이후, 발표 주제를 사다리타기로 뽑을 예정입니다.

# (Advanced) New Learning Method(Not backpropagation!!)
* 2022년 후반기에 딥러닝의 대가 힐튼 교수가 아주 흥미로운 연구 결과를 내 놓았습니다.
* (위의 수업에서 배우는) Backpropagation이 가지고 있는 문제점을 고치기 위한 학습 방법입니다.
    * Backpropagation을 위해서는 모델의 전체 구조 및 cache를 들고 있어야 한다는 단점이 있습니다.
    * 모델이 커지면 커질수록 학습 시간이 기하급수적으로 늘어나서 이걸 최적화하기 위한 연구가 활발히 이루어지고 있죠 (e.g. Deepspeed, 8-bit precision, ..)
* Forward Forward Method인데, 관심 있으신분들은 Backprop 이해 이후 한번 읽어보셔도 좋을 것 같습니다.
    * [The Forward-Forward Algorithm: Some Preliminary Investigations, Hinton](https://www.cs.toronto.edu/~hinton/FFA13.pdf)

---
# Role of Branch
* Branch에는 Assignment #1와 Assignment #2, 그리고 1주차에 대한 내용이 들어가게 됩니다.
* 이론 및 코딩으로 따로 나누진 않을 생각이고, 도움이 되는 자료들(공부할 때 사용하면 좋은 자료들)을 업로드 해놓을 예정입니다.
* 또한, 주차 때 공부해야 하는 **범위**를 이쪽에만 표기해놓을 생각입니다.
* 이외에 이론 주에 받을 설문 페이지를 공지할 생각입니다. (이건 카톡방에도 할 것 같긴한데,, 여기에도 합니다)
* 발표자료는 저한테 따로 보내주셔도 되고, 이쪽으로 Pull request 날려주셔도 됩니다.
    * 바로 커밋하진 말아주세욥 ㅠ

# Fork & Pull Request
* 만일 해당 주차에 본인이 도움이 되었던 자료를 공유하고 싶다면, 바로 main branch에 올리지 마시고 Pull request를 날려주세요.
    * Pull request를 날릴 땐 임의로 Branch를 만들어도 됩니다. 어짜피 닫고 나면 없어져요
    * 이게 좀 꼬이면 골치 아픈데, Fork => Pull request를 날리시면 안 되고, 이 Repository의 Branch에서 바로 Pull request를 날리셔야 합니다. 그래야, 정보가 보존됩니다.
    * "그냥 지금 이 사람이 무슨 소리하는지 모르겠다~" 싶으시면 저한테 따로 자료를 보내주세요. 제가 올려 놓겠습니다.
