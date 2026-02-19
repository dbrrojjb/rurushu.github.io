<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<title>루루슈의 무역선 선적 돕기!</title>

<style>
body{
  margin:0;
  font-family:sans-serif;
  overflow:hidden;
  background:#f2f2f2;
}

/* ===== 로그인 화면 ===== */
#loginScreen{
  position:fixed;
  top:0; left:0;
  width:100vw; height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  background:linear-gradient(135deg,#f5e6d3,#d8f5c6);
  flex-direction:column;
}

#loginScreen input{
  padding:10px 15px;
  font-size:18px;
  margin-bottom:20px;
  border-radius:5px;
  border:2px solid #888;
}

#loginScreen button{
  padding:14px 36px;
  font-size:20px;
  font-weight:bold;
  border:none;
  border-radius:40px;
  cursor:pointer;

  background:linear-gradient(135deg,#ffcc70,#ff9f43);
  color:white;
  box-shadow:0 6px 0 #cc7a00,
              0 8px 15px rgba(0,0,0,0.2);

  transition:all 0.15s ease;
}

#loginScreen button:hover{
  transform:translateY(-3px);
  box-shadow:0 9px 0 #cc7a00,
              0 12px 18px rgba(0,0,0,0.25);
}

#loginScreen button:active{
  transform:translateY(4px);
  box-shadow:0 2px 0 #cc7a00;
}

/* ===== 관리자 화면 ===== */
#adminPanel{
  position:fixed;
  top:0; right:0;
  width:350px; height:100vh;
  background:#fff;
  border-left:3px solid #888;
  padding:10px;
  overflow:auto;
  display:none;
  box-shadow:-5px 0 15px rgba(0,0,0,0.2);
}

#adminPanel h2{
  text-align:center;
}

#records{
  margin-top:10px;
  font-size:14px;
}

#clearRecordsBtn{
  margin-top:10px;
  width:100%;
  padding:5px;
}

/* ===== 게임 화면 ===== */
#gameArea{
  position:relative;
  width:100vw;
  height:100vh;
  display:none;
}

/* ===== 색상 구역 ===== */
.dropZone{
  width:180px;
  height:180px;
  position:absolute;
  border-radius:15px;
  opacity:0.85;
}

#redZone{background:#FF4B4B;top:20px;left:20px;}
#blueZone{background:#4B8DFE;top:20px;right:20px;}
#greenZone{background:#83B748;bottom:20px;left:20px;}
#blackZone{background:#484848;bottom:20px;right:20px;}

/* ===== 택배 상자 ===== */
.box{
  width:110px;
  height:110px;
  background:linear-gradient(#d9a66b,#c48a4e);
  border:3px solid #8b5a2b;
  position:absolute;
  border-radius:8px;
  cursor:grab;
  box-shadow:5px 5px 10px rgba(0,0,0,0.2);
}

.box::before{
  content:"";
  position:absolute;
  width:20px;
  height:100%;
  left:45px;
  background:#f3e2b3;
}

.box::after{
  content:"";
  position:absolute;
  top:-10px;
  left:0;
  width:100%;
  height:15px;
  background:#e0b27c;
  border-radius:5px 5px 0 0;
}

/* 세로 리본 */
.ribbon{
  position:absolute;
  height:0%;
  width:20px;
  left:45px;
  top:0;
  border-radius:5px;
  animation:tieVertical 0.5s forwards ease-out;
}

@keyframes tieVertical{
  from{height:0%;}
  to{height:100%;}
}

/* 확인 버튼 */
#confirmBtn{
  position:absolute;
  bottom:25px;
  left:50%;
  transform:translateX(-50%);

  padding:16px 42px;
  font-size:20px;
  font-weight:bold;

  border:none;
  border-radius:50px;
  cursor:pointer;

  background:linear-gradient(135deg,#6ee7b7,#10b981);
  color:white;

  box-shadow:0 6px 0 #0f9f6e,
              0 10px 20px rgba(0,0,0,0.25);

  transition:all 0.15s ease;
}

#confirmBtn:hover{
  transform:translateX(-50%) translateY(-3px);
  box-shadow:0 9px 0 #0f9f6e,
              0 14px 22px rgba(0,0,0,0.3);
}

#confirmBtn:active{
  transform:translateX(-50%) translateY(4px);
  box-shadow:0 2px 0 #0f9f6e;
}

/* ===== 코인 ===== */
#coin{
  position:absolute;
  top:50%;
  left:50%;
  transform:translate(-50%,-50%);
  width:220px;
  height:220px;
  border-radius:50%;
  background:radial-gradient(circle at 30% 30%, #fff7b0, #ffd700 60%, #c89b00);
  border:8px solid #a67c00;
  box-shadow:0 0 30px rgba(255,215,0,0.7);
  display:none;
  cursor:pointer;
  animation:coinAppear 0.5s ease-out;
}

#acorn{
  position:absolute;
  width:80px;
  height:100px;
  top:60px;
  left:70px;
}

#acorn .nut{
  width:80px;
  height:70px;
  background:linear-gradient(#ffcc33,#d89b00);
  border-radius:40px 40px 50px 50px;
  border:4px solid #a06d00;
  position:absolute;
  bottom:0;
}

#acorn .cap{
  width:80px;
  height:40px;
  background:#b57f00;
  border-radius:40px 40px 20px 20px;
  border:4px solid #8a5e00;
  position:absolute;
  top:0;
}

@keyframes coinAppear{
  from{transform:translate(-50%,-50%) scale(0);}
  to{transform:translate(-50%,-50%) scale(1);}
}

@keyframes coinCollect{
  to{
    transform:translate(-50%,-200%) scale(0.2);
    opacity:0;
  }
}

/* ===== 엔딩 화면 ===== */
#endingScreen{
  position:fixed;
  top:0;
  left:0;
  width:100vw;
  height:100vh;
  display:none;
  justify-content:center;
  align-items:center;
  text-align:center;
  padding:40px;
  box-sizing:border-box;
  background:linear-gradient(135deg, #f5e6d3, #d8f5c6);
  font-size:22px;
  line-height:1.8;
}
</style>
</head>

<body>

<!-- 로그인 화면 -->
<div id="loginScreen">
  <input type="text" id="userName" placeholder="이름을 입력하세요">
  <button id="loginBtn">게임 시작</button>
</div>

<!-- 관리자 화면 -->
<div id="adminPanel">
  <h2>관리자 패널</h2>
  <div id="records"></div>
  <button id="clearRecordsBtn">전체 삭제</button>
</div>

<!-- 게임 화면 -->
<div id="gameArea">
  <div id="redZone" class="dropZone"></div>
  <div id="blueZone" class="dropZone"></div>
  <div id="greenZone" class="dropZone"></div>
  <div id="blackZone" class="dropZone"></div>

  <button id="confirmBtn">확인</button>

  <div id="coin">
    <div id="acorn">
      <div class="cap"></div>
      <div class="nut"></div>
    </div>
  </div>
</div>

<div id="endingScreen">
  선적 성공! 루루슈의 무역선이 출발합니다!<br><br>
  획득한 기념주화는 추후 루루슈의 특별 선물과 교환할 수 있습니다.
</div>

<script>
/* ===== 로그인 기능 ===== */
const loginScreen = document.getElementById("loginScreen");
const loginBtn = document.getElementById("loginBtn");
const userNameInput = document.getElementById("userName");
const adminPanel = document.getElementById("adminPanel");
const recordsDiv = document.getElementById("records");
const clearBtn = document.getElementById("clearRecordsBtn");
const gameArea = document.getElementById("gameArea");

let currentUser = "";
let isAdmin = false;
let gameEnded=false;
let coinCollected=false;

/* 로그인 이벤트 */
loginBtn.addEventListener("click", () => {
    const name = userNameInput.value.trim();
    if (!name) {
        alert("이름을 입력해주세요!");
        return;
    }
    currentUser = name;

    if (name.toLowerCase() === "루루슈".toLowerCase()) {
        isAdmin = true;
        loginScreen.style.display="none";
        adminPanel.style.display="block"; // 루루슈 로그인 시 관리자 패널만
        showRecords();
    } else {
        isAdmin = false;
        loginScreen.style.display="none";
        gameArea.style.display="block";  // 일반 유저는 게임 화면만
    }
});

/* ===== 관리자 기록 함수 ===== */
function saveRecord(user, result, coin=false){
    let records = JSON.parse(localStorage.getItem("records") || "[]");

    // 이미 기록이 있으면 업데이트 (코인 획득 포함)
    const existingIndex = records.findIndex(r => r.user===user && r.time===currentTime);
    if(existingIndex>=0){
        records[existingIndex].coin = coin;
    } else {
        records.push({user, result, coin, time: currentTime});
    }

    localStorage.setItem("records", JSON.stringify(records));
    if(isAdmin) showRecords();
}

function showRecords(){
    let records = JSON.parse(localStorage.getItem("records") || "[]");
    let html = "";
    records.forEach((r, index) => {
        html += `${index+1}. ${r.user} → ${r.result} | 코인:${r.coin?"획득":"없음"} (${r.time})<br>`;
    });
    recordsDiv.innerHTML = html;
}

clearBtn.addEventListener("click", () => {
    if(confirm("정말 삭제할까요?")){
        localStorage.removeItem("records");
        showRecords();
    }
});

/* ===== 게임 코드 ===== */
const zones={
  "#FF4B4B": redZone,
  "#4B8DFE": blueZone,
  "#83B748": greenZone,
  "#484848": blackZone
};
const coin=document.getElementById("coin");
const endingScreen=document.getElementById("endingScreen");
const confirmBtn=document.getElementById("confirmBtn");

let boxes=[];
let shakeCount={};
let currentTime="";

function createBox(id){
  const box=document.createElement("div");
  box.className="box";
  box.dataset.id=id;
  box.dataset.ribbon="";
  shakeCount[id]=0;

  randomPosition(box);
  makeDraggable(box);
  addEvents(box);

  gameArea.appendChild(box);
  boxes.push(box);
}

function randomPosition(box){
  const x=Math.random()*(window.innerWidth-300)+150;
  const y=Math.random()*(window.innerHeight-300)+150;
  box.style.left=x+"px";
  box.style.top=y+"px";
}

function makeDraggable(el){
  let offsetX,offsetY,dragging=false;

  el.addEventListener("mousedown",e=>{
    if(gameEnded) return;
    dragging=true;
    offsetX=e.offsetX;
    offsetY=e.offsetY;
  });

  document.addEventListener("mousemove",e=>{
    if(dragging){
      el.style.left=(e.pageX-offsetX)+"px";
      el.style.top=(e.pageY-offsetY)+"px";

      if(el.dataset.id=="3"){
        if(Math.abs(e.movementX)>20){
          shakeCount[3]++;
          if(shakeCount[3]>8){
            addRibbon(el,"#83B748");
          }
        }
      }
    }
  });

  document.addEventListener("mouseup",()=>{
    dragging=false;
    shakeCount[3]=0;
  });
}

function addRibbon(box,color){
  if(box.dataset.ribbon || gameEnded) return;
  const ribbon=document.createElement("div");
  ribbon.className="ribbon";
  ribbon.style.background=color;
  box.appendChild(ribbon);
  box.dataset.ribbon=color;
}

function addEvents(box){
  const id=box.dataset.id;
  if(id=="1"){ box.addEventListener("contextmenu",e=>{ e.preventDefault(); addRibbon(box,"#FF4B4B"); }); }
  if(id=="2"){ box.addEventListener("dblclick",()=>{ addRibbon(box,"#4B8DFE"); }); }
  if(id=="4"){
    let seq=[];
    box.addEventListener("mousedown",e=>{
      if(e.button===0) seq=["left"];
      else if(e.button===2 && seq[0]=="left"){
        addRibbon(box,"#484848");
      }
    });
  }
  box.addEventListener("contextmenu",e=>e.preventDefault());
}

confirmBtn.addEventListener("click",()=>{
  if(gameEnded) return;

  currentTime = new Date().toLocaleString(); // 기록용 타임스탬프
  let allHave=true;
  let correct=true;

  boxes.forEach(box=>{
    if(!box.dataset.ribbon){
      allHave=false;
      correct=false;
      return;
    }

    const rect=box.getBoundingClientRect();
    const zone=zones[box.dataset.ribbon];
    const z=zone.getBoundingClientRect();

    const inside=
      rect.left>z.left &&
      rect.right<z.right &&
      rect.top>z.top &&
      rect.bottom<z.bottom;

    if(!inside) correct=false;
  });

  if(allHave && correct){
    alert("🎉 성공!");
    coin.style.display="block";
    gameEnded=true;
    saveRecord(currentUser,"성공",false); // 코인 획득 전
  } else{
    alert("❌ 실패! 다시 도전!");
    gameEnded=true;
    saveRecord(currentUser,"실패",false);
  }
});

/* 코인 클릭 */
coin.addEventListener("click",()=>{
  if(coinCollected) return; // 중복 저장 방지
  coinCollected=true;
 setTimeout(()=>{
    alert("🎉 루루슈의 기념주화를 획득했습니다!");
  },0);

  saveRecord(currentUser,"성공",true);

  coin.style.animation="coinCollect 0.8s forwards ease-in";
  setTimeout(()=>{
    coin.style.display="none";
    endingScreen.style.display="flex";
  },800);
});

/* 랜덤 상자 생성 */
let ids=[1,2,3,4];
ids.sort(()=>Math.random()-0.5);
ids.forEach(id=>createBox(id));

</script>
</body>
</html>
