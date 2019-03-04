# 1주차 vue.js

현대 웹 애플리케이션 개발 개론

6번의 용어에서 5가지 중요하다
DOM 과 버추얼 돔의 차이를 알고 있는게 주용하다

- 웹개발 관련용어는 알고 계시면 좋다.

확장의 유연함이 jquery 와 차이가 있다.
(vue.js)

자동 Refresh

Webpack 1 & 2 : 모듈 번들러

Jest



sli.do (L551)


--theme 

night owl

material syntax

winter is comming


----
liver server
vetur
div#app


git clone https://github.com/JongyoonOh/vue-camp.git

할당과 접근

obj.num console에서 친다


doc 탭
html:5


     Object.defineProperty(viewModel,'str', {
        //  'viewModel.str' 했을 때의 동작 정의
         get : function(){
            console.log('접근되었습니다');
            
         },
         //  'viewModel.str = 값' 했을 때의 동작 정의
         set : function(newValue){
            console.log('할당되었습니다');  
            render(newValue);
            // div.innerHTML = newValue;
         }
     });

     function render(value){
         div.innerHTML = value;
     }
	 
	 
reactivitiy 에 한것


<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>


Vue는 무엇인가? MVVM 패턴의 ....


Data Bindings 와 Dom Listeners


눈으로 봤을때 마크업만 봤을때도 어떤 동작을 하는지 이해할수 있다. 그게 vue의 모토다
코드를 빠르게 파악할수 있는게 vue 코드다 


vue.js reactivitiy 의 동작 원리가 오늘 한것이다.


javascript 에서 할수 있는것들은  줄여서 할수 있다.


https://vuejs.org/v2/guide/reactivity.html#ad



앵귤러에 비해 많이 러닝 커브 해야 한다.


this 맨 아래에 생성자 함수


function Vue(){
    this.log = function(){
		console.log('hi');
    }
}

쓰는 이유는? 가져다가 쓰면 된다.

넣가

컴포넌트 통신 방식 (데이터 흐름을 예측할수 있다.
component 에서 통신에서는 vue.js에 있다.
이렇게 받을것은 react 



바뀔때마다 다 그리자
reactivity

컴포넌트에 목적은 코드의 재사용이다.
컴포넌트설계 와 통신을 이해하는게 핵심이다.


수요일날 오시면 props를 이해해서 통신방식으로 상위 컴포넌트를 배우게 된다.
