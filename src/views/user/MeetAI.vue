<template>
    <main>
        <section class="head-section">
            <div class="head-area">
                <p class="head-title">AI BestFriend와 대화하기:D</p>
                <img id="head_img" class="head_img" src="@/assets/ai-image.jpg">
            </div>
        </section>
        <section class="main-section">
            <button class="back-button">
                <svg height="16" width="16" xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 1024 1024"><path d="M874.690416 495.52477c0 11.2973-9.168824 20.466124-20.466124 20.466124l-604.773963 0 188.083679 188.083679c7.992021 7.992021 7.992021 20.947078 0 28.939099-4.001127 3.990894-9.240455 5.996574-14.46955 5.996574-5.239328 0-10.478655-1.995447-14.479783-5.996574l-223.00912-223.00912c-3.837398-3.837398-5.996574-9.046027-5.996574-14.46955 0-5.433756 2.159176-10.632151 5.996574-14.46955l223.019353-223.029586c7.992021-7.992021 20.957311-7.992021 28.949332 0 7.992021 8.002254 7.992021 20.957311 0 28.949332l-188.073446 188.073446 604.753497 0C865.521592 475.058646 874.690416 484.217237 874.690416 495.52477z"></path></svg>
                <span>뒤로</span>
            </button>
            <div class="main-area">
                <div class="main-container">
                    <div class="main-title">
                        <img src="@/assets/heart_ballon.png">
                        <h2>AI 친구와 대화해보세요!</h2>
                    </div>
                <div class="ai-content">
                    <!-- 대화창 -->
                    <div class="card-container">
                        <div class="card-body">
                            <!-- ai 대화 -->
                            <div class="messages-container left">
                                <div class="message-box left">
                                    <div class="loader">
                                    <div class="loader-text">잠시만! 생각 중이야:)</div>
                                    <div class="loader-bar"></div>
                                    </div>  
                                    <p class="left-text">안녕! 반가워:D</p>
                                </div>
                            </div>
                            <!-- user 대화 -->
                            <div class="messages-container right">
                                <div class="message-box right">
                                <p class="right-text">나도 반가워!!</p>
                                </div>
                            </div>


                            <!-- 이 아래는 지우고 추가하시면 됩니다. 샘플용 데이터 -->
                            <!-- ai 대화 -->
                            <div class="messages-container left">
                                <div class="message-box left">
                                    <p class="left-text">무슨 얘기할까? 잘 지내?</p>
                                </div>
                            </div>
                            <!-- user 대화 -->
                            <div class="messages-container right">
                                <div class="message-box right">
                                    <p class="right-text"> 응 그럼 너무 잘 지내지~ 너는 어때?</p>
                                </div>
                            </div>

                            <!-- ai 대화 -->
                            <div class="messages-container left">
                                <div class="message-box left">
                                    <p class="left-text">나는 요새 수영에 관심이 있어. 수영장에서 수영하고 재밌게 노는게 너무 좋아.</p>
                                </div>
                            </div>
                            <!-- user 대화 -->
                            <div class="messages-container right">
                                <div class="message-box right">
                                    <p class="right-text">오 그렇구나. 보다 긴 텍스트도 실험해볼까</p>
                                </div>
                            </div>

                            <!-- ai 대화 -->
                            <div class="messages-container left">
                                <div class="message-box left">
                                    <p class="left-text">죽는 날까지 하늘을 우러러 한 점 부끄럼이 없기를, 잎새에 이는 바람에도 나는 괴로워했다. 별을 노래하는 마음으로 모든 죽어가는 것을 사랑해야지. 그리고 나한테 주어진 길을 걸어가야겠다. 오늘 밤에도 별이 바람에 스치운다.</p>
                                </div>
                            </div>
                            <!-- user 대화 -->
                            <div class="messages-container right">
                                <div class="message-box right">
                                    <p class="right-text">윤동주 서시!</p>
                                </div>
                            </div>

                            <!-- ai 대화 -->
                            <div class="messages-container left">
                                <div class="message-box left">
                                    <p class="left-text">이번엔 네 차례야</p>
                                </div>
                            </div>
                            <!-- user 대화 -->
                            <div class="messages-container right">
                                <div class="message-box right">
                                    <p class="right-text">산모퉁이를 돌아 논가 외딴 우물을 홀로 찾아가선 가만히 들여다봅니다. 우물 속에는 달이 밝고 구름이 흐르고 하늘이 펼치고 파아란 바람이 불고 가을이 있습니다. 그리고 한 사나이가 있습니다. ...  우물 속에는 달이 밝고 구름이 흐르고 하늘이 펼치고 파아란 바람이 불고 가을이 있고 추억처럼 사나이가 있습니다.</p>
                                </div>
                            </div>

                            <!-- ai 대화 -->
                            <div class="messages-container left">
                                <div class="message-box left">
                                    <p class="left-text">윤동주 자화상</p>
                                </div>
                            </div>
                            <!-- user 대화 -->
                            <div class="messages-container right">
                                <div class="message-box right">
                                    <p class="right-text">텍스트가 길어지면 양옆으로 꽉 차는데 그래도 간격이 있는게 좋겠지?</p>
                                </div>
                            </div>

                            <!-- ai 대화 -->
                            <div class="messages-container left">
                                <div class="message-box left">
                                    <p class="left-text">얼마나 간격을 넣을까?</p>
                                </div>
                            </div>

                            </div>
                        </div>
                    
                    </div>
                    <div class="input-wrapper">
                        <div class="input-text-info">
                            <p> 개인 정보 등 민감 정보를 입력하지 않도록 주의하세요!</p>
                        </div>
                        <textarea autocomplete="off" class="input-text" placeholder="말을 걸어보세요:)"></textarea>
                        <button class="submit-button">입 력</button>
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<script>
export default {

}
</script>

<style scoped>
body {
    margin: 0;
    padding: 0;
}

.head-area {
    width: 100%;
    height: 250px;
    margin: auto;
    position: relative;
    background: #000000;
        
    overflow: hidden;
    justify-content: center;
    align-items: center;
}

.head-title {
    margin-top: 200px;
    margin-left: 5%;
    font-size: 30px;    
    color: rgb(255, 255, 255);
    position: absolute;
    z-index: 1;
}

.head_img {
    opacity: 1;
    position: absolute;
    min-height: 250px;
    width: 100%;
}

.head-title {
    word-spacing:5px;
    letter-spacing:1px;
}

.main-area {
    width: 1200;
    height: auto;
}

.main-container {
    margin: 20px 0px 70px 0px;
    padding: 50px;
}

/* ai 이미지 area */

.main-title {
    display: grid;
    grid-template-rows: auto 30px;
    justify-content: center;
}

.main-title img {
    width: 150px;

    grid-row: 1/2;
    margin:  auto;
    padding-bottom: 10px;
}

.main-title h2 {
    color: #454545;
    margin-left: 15px;

    grid-row: 2/3;
    margin: 0 auto;
}

/* 뒤로 버튼 */

.back-button {
    margin: 30px 50px;
    display: flex;
    height: 3em;
    width: 100px;
    align-items: center;
    justify-content: center;
    background-color: #dddddd;
    border-radius: 3px;
    letter-spacing: 1px;
    transition: all 0.2s linear;
    cursor: pointer;
    border: none;
    background: #909090;
}

.back-button span {
    font-size: 14px;
    font-weight: 600;
    color: white;
}

.back-button svg {
    margin-right: 5px;
    margin-left: 5px;
    font-size: 20px;
    transition: all 0.4s ease-in;
    fill: white;
}

.back-button:hover svg {
    font-size: 1.2em;
    transform: translateX(-5px);
    fill: white;
}

.back-button:hover {
    background-color: #707070;
}

.back-button:active {
    transform: translate(0, 3px);
    transition-duration: .3s;
}


/* 대화창 area */

.ai-content {
    width: 70%;
    height: 500px;
    justify-content: center;
    margin: 30px auto;
}


.card-container {
  width: auto;
  height: 490px;
  background-color: #fff8ef;
  border-radius: 10px ;
  padding: 30px;
  display: flex;
  flex-direction: column;
  box-shadow: inset 0px 10px 20px 4px rgba(255, 166, 0, 0.1);

  overflow: auto;
}

.card-body {
  margin-top: auto;
}

.messages-container.left {
  display: flex;
  padding: 10px 5px;
  margin-right: 5%;
}

.messages-container.right {
  display: flex;
  padding: 10px 5px;
  margin-left: 5%;
}

.message-box {
  padding: 1px 15px;
  border-radius: 10px;
}

.message-box.right {
  background-color: #454545;
  margin-left: auto;
}

.right-text {
    color: #fff;
    font-size: 16px;
}

.message-box.left {
    background-color: #f372a3;
    width: auto;
    margin-right: auto;
}

.left-text {
    color: rgb(255, 255, 255);
    font-size: 16px;
}
  
  
  
/* loader 로딩  */

/* js쪽에서 이걸로 Hide 옵션을 줄 수 있습니다! */
/* <script>
    $(window).load(function() {
     $('.loader').addClass('hide');
    });
</script>  */
.hide {
  display: none;
}

.loader {
/* background-color: blue; */
  padding : 10px 5px;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: auto;
}

.loader-text {
  font-size: 16px;
  color: rgb(255, 255, 255);
  margin-bottom: 3px;
  align-self: center;
}

.loader-bar {
  margin-left: 45px;
  width: 32%;
  height: 5px;
  border-radius: 5px;
  background-color: #fff8ef;
  animation: loader-bar-animation 2s ease-in-out infinite;
}

@keyframes loader-bar-animation {
0% {
    /* transform: translateX(-100%) rotate(270deg); */
    transform: translateX(-100%);
}

50% {
    /* transform: translateX(100%) rotate(-90deg); */
    transform: translateX(100%);
}

100% {
    /* transform: translateX(-100%) rotate(270deg); */
    transform: translateX(-100%);
}
}
  



/* 대댓글 입력 area */

.input-wrapper {
    margin: 50px 18%;
    display: grid;

    grid-template-columns: auto 80px;
    grid-template-rows: 55px 100px;
    grid-gap: 12px;
}

.input-text-info {
    display: flex;
    grid-column: 1 / 3;
    grid-row: 1 / 2 ;
}

.input-text-info p {
    margin-right: auto;
    margin-left: 20px;
    font-size: 0.9rem;
    color: #909090;
}

.input-text {
    padding: 0.5rem 0.8rem;
    grid-column: 1 / 2;
    grid-row: 2 / 3 ;
    width: auto;
    resize: none; 

    background-color: #05060f0a;
    border-radius: .5rem;
    padding: 0.5rem 0.8rem;
    border: 2px solid transparent;
    font-size: 1rem;
    transition: border-color .3s cubic-bezier(.25,.01,.25,1) 0s, color .3s cubic-bezier(.25,.01,.25,1) 0s;
}

.input-text:hover, .input-text:focus, .input {
    outline: none;
    border-color: #909090;
}

.input-group:hover, .input:focus {
    color: rgb(255, 233, 205);
}


/* 대댓글 입력 / 취소 button area */

.submit-button {
    grid-column: 2 / 3;
    grid-row: 2 / 3;
    height: 100px;
    outline: none;
    border: none;
    cursor: pointer;
    font-size: 1rem;
    font-weight: 500;
    color: hsl(0, 0%, 100%);
    border-radius: 5px;
    text-transform: uppercase;
    transition: all 0.2s ease-in-out;
    position: relative;
    background-color: #454545;
    box-shadow: 0 2px 5px rgba(70, 70, 70, 0.5);
}

.submit-button:active {
    transform: translate(0, 3px);
    transition-duration: .3s;
}
</style>