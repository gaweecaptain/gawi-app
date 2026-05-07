<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>가위캡틴 CRM</title>

<style>

body{
  margin:0;
  font-family:-apple-system,BlinkMacSystemFont,sans-serif;
  background:#f3f4f6;
  color:#111827;
}

header{
  background:white;
  padding:20px;
  position:sticky;
  top:0;
  z-index:10;
  border-bottom:1px solid #e5e7eb;
}

.topMenu{
  display:flex;
  justify-content:space-between;
  align-items:center;
}

.tabs{
  display:flex;
  gap:10px;
}

.tab{
  background:#e5e7eb;
  border:none;
  padding:10px 15px;
  border-radius:12px;
  font-weight:600;
}

.addBtn{
  background:#2563eb;
  color:white;
  border:none;
  padding:12px 18px;
  border-radius:15px;
  font-weight:bold;
}

.container{
  padding:20px;
}

.calendar{
  background:white;
  border-radius:30px;
  padding:20px;
  box-shadow:0 2px 10px rgba(0,0,0,0.05);
}

.monthTitle{
  font-size:30px;
  font-weight:700;
  margin-bottom:20px;
}

.week{
  display:grid;
  grid-template-columns:repeat(7,1fr);
  margin-bottom:10px;
  text-align:center;
  color:#6b7280;
}

.days{
  display:grid;
  grid-template-columns:repeat(7,1fr);
  gap:10px;
}

.day{
  background:#eff6ff;
  border-radius:20px;
  min-height:90px;
  padding:10px;
  font-weight:600;
}

.today{
  background:#2563eb;
  color:white;
}

.section{
  background:white;
  border-radius:25px;
  padding:20px;
  margin-top:20px;
  box-shadow:0 2px 10px rgba(0,0,0,0.05);
}

.task{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:12px 0;
  border-bottom:1px solid #f3f4f6;
}

.check{
  width:22px;
  height:22px;
}

.bottomMenu{
  position:fixed;
  bottom:0;
  left:0;
  right:0;
  background:white;
  border-top:1px solid #ddd;
  display:flex;
  justify-content:space-around;
  padding:12px;
}

.bottomMenu button{
  background:none;
  border:none;
  font-size:15px;
  font-weight:600;
}

</style>
</head>

<body>

<header>

<div class="topMenu">

<div class="tabs">

<button class="tab">월별</button>
<button class="tab">주별</button>
<button class="tab">일별</button>

</div>

<button
class="addBtn"
onclick="location.href='customer.html'">

+ 신규고객

</button>

</div>

</header>

<div class="container">

<div class="calendar">

<div class="monthTitle">
2026년 1월
</div>

<div class="week">

<div>일</div>
<div>월</div>
<div>화</div>
<div>수</div>
<div>목</div>
<div>금</div>
<div>토</div>

</div>

<div class="days">

<div class="day"></div>
<div class="day"></div>
<div class="day"></div>

<div class="day">1</div>
<div class="day">2</div>

<div class="day">3</div>

<div class="day">4</div>

<div class="day">5</div>

<div class="day">6</div>

<div class="day">7</div>

<div class="day">8</div>

<div class="day">9</div>

<div class="day">10</div>

<div class="day">11</div>

<div class="day">12</div>

<div class="day">13</div>

<div class="day">14</div>

<div class="day">15</div>

<div class="day">16</div>

<div class="day today">
22
</div>

</div>

</div>

<div class="section">

<h2>📌 오늘 일정</h2>

<div class="task">
<div>김원장 방문</div>
</div>

<div class="task">
<div>AS 수리 전달</div>
</div>

<div class="task">
<div>결제 확인</div>
</div>

</div>

<div class="section">

<h2>🎯 오늘 방문 고객 5명</h2>

<div class="task">

<div>청담헤어</div>

<input type="checkbox" class="check">

</div>

<div class="task">

<div>에이블샵</div>

<input type="checkbox" class="check">

</div>

<div class="task">

<div>제이살롱</div>

<input type="checkbox" class="check">

</div>

<div class="task">

<div>김민수 원장</div>

<input type="checkbox" class="check">

</div>

<div class="task">

<div>박원장</div>

<input type="checkbox" class="check">

</div>

</div>

</div>

<div class="bottomMenu">

<button onclick="location.href='index.html'">
홈
</button>

<button onclick="location.href='list.html'">
고객목록
</button>

<button onclick="location.href='customer.html'">
등록
</button>

</div>

</body>
</html>
