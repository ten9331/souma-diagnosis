# souma-diagnosis
souma-diagnosis
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>そうまくんとすること診断</title>
  <style>
    body {
      font-family: 'Hiragino Maru Gothic Pro', 'Arial Rounded MT Bold', sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #fff9c4 0%, #ffe082 100%);
      color: #444;
      overflow: hidden; /* 背景アニメ用 */
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 30px;
      color: #6d4c41;
      text-shadow: 2px 2px 6px rgba(255, 245, 157, 0.9);
      position: relative;
      z-index: 2;
    }
    input {
      padding: 12px;
      font-size: 16px;
      border: 2px solid #fdd835;
      border-radius: 20px;
      margin-right: 10px;
      outline: none;
      box-shadow: inset 2px 2px 5px rgba(0,0,0,0.1);
      position: relative;
      z-index: 2;
    }
    button {
      padding: 12px 20px;
      font-size: 16px;
      border: none;
      border-radius: 20px;
      background: #ffca28;
      color: white;
      font-weight: bold;
      cursor: pointer;
      transition: transform 0.2s, box-shadow 0.3s;
      box-shadow: 2px 4px 10px rgba(255, 202, 40, 0.6);
      position: relative;
      z-index: 2;
    }
    button:hover {
      transform: scale(1.05);
      box-shadow: 4px 6px 15px rgba(255, 202, 40, 0.8);
    }
    #result {
      margin-top: 30px;
      font-weight: bold;
      font-size: 22px;
      opacity: 0;
      transition: opacity 1s ease-in-out, transform 0.5s;
      color: #5d4037;
      position: relative;
      z-index: 2;
    }
    #result.show {
      opacity: 1;
      transform: scale(1.05);
    }

    /* 星やハート用 */
    .floating {
      position: absolute;
      font-size: 20px;
      animation: floatUp 6s linear forwards;
      opacity: 0.8;
      z-index: 1;
    }
    @keyframes floatUp {
      0% {
        transform: translateY(100vh) scale(0.5);
        opacity: 1;
      }
      100% {
        transform: translateY(-10vh) scale(1.2);
        opacity: 0;
      }
    }
  </style>
</head>
<body>
  <h1>そうまくんとすること診断</h1>
  <div>
    <input type="text" id="nameInput" placeholder="あなたの名前を入力">
    <button onclick="showResult()">診断する</button>
  </div>
  <div id="result"></div>

  <script>
    function showResult() {
      const name = document.getElementById("nameInput").value;
      const resultBox = document.getElementById("result");

      if (!name) {
        resultBox.textContent = "名前を入力してください！";
        resultBox.classList.add("show");
        return;
      }

      const activities = [
        "一緒にカフェでゆったりする",
        "公園を散歩する",
        "カラオケで盛り上がる",
        "ゲームで対戦する",
        "ボードゲームを楽しむ",
        "映画を見る",
        "ショッピングに行く",
        "ラーメンを食べに行く",
        "スポーツ観戦する",
        "花火を見る",
        "夏祭りに行く",
        "勉強会をする",
        "ケーキを食べる",
        "絵を描きあう",
        "デュエットする",
        "旅行を計画する",
        "一緒に写真を撮る",
        "お家でゴロゴロする",
        "推し活を語る",
        "サプライズをもらう"
      ];

      const today = new Date();
      const dateString = today.getFullYear() + "-" + (today.getMonth()+1) + "-" + today.getDate();
      let hash = 0;
      const combined = name + dateString;
      for (let i = 0; i < combined.length; i++) {
        hash += combined.charCodeAt(i);
      }
      const index = hash % activities.length;
      const activity = activities[index];

      resultBox.textContent = `${name}さんの今日の診断結果は…「そうまくんと${activity}」です！`;
      
      // 結果をふわっと表示
      resultBox.classList.remove("show");
      setTimeout(() => resultBox.classList.add("show"), 50);

      // 星やハートを生成
      for (let i = 0; i < 10; i++) {
        createFloatingSymbol();
      }
    }

    function createFloatingSymbol() {
      const symbols = ["⭐", "✨", "🌼", "💛", "💫"];
      const symbol = symbols[Math.floor(Math.random() * symbols.length)];
      
      const span = document.createElement("span");
      span.classList.add("floating");
      span.textContent = symbol;
      span.style.left = Math.random() * 100 + "vw";
      span.style.fontSize = (20 + Math.random() * 20) + "px";
      document.body.appendChild(span);

      // アニメーション終了後に削除
      setTimeout(() => {
        span.remove();
      }, 6000);
    }
  </script>
</body>
</html>
