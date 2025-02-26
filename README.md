# calculator
계산기만들기

index.html부분(body)

<div class="calculator">
        <form name="forms">
            <input type="text" name="output">
            <input type="button" class = "clear" value="C">
            <input type="button" class = "operator" value="/">
            <input type="button" value="1">
            <input type="button" value="2">
            <input type="button" value="3">
            <input type="button" class = "operator" value="*">
            <input type="button" value="4">
            <input type="button" value="5">
            <input type="button" value="6">
            <input type="button" value="+">
            <input type="button" value="7">
            <input type="button" value="8">
            <input type="button" value="9">
            <input type="button" class = "operator" value="-">
            <input type="button" class = "dot" value=".">
            <input type="button" value="0">
            <input type="button" class = "operator result" value="=">
        </form>
    </div>

    <img width="574" alt="image" src="https://github.com/user-attachments/assets/222335e5-c6bd-4b04-b511-e58ffbb60d5e" />

    이런 화면이 생긴다
    <input type="button" value="1" onclick="document.forms.output.value+='1'"> 요 옆에 onclick부분은 버튼을 눌렀을 때 1이 나타나도록 한다. value = '1'이라면 계속 1을 찍었을때 1 하나만 나타나지만, +=를 추가하면 연속적으로 1111이 찍히게 된다.

    하지만 등호 버튼 부분은 실제 계산이 되어야하기에 eval함수를 사용한다. onclick="document.forms.output.value=eval(document.forms.output.value)"> 이러면 텍스트에 있는값이 실제로 계산이 된다.


    style.css부분

    
