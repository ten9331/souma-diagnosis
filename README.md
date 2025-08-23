# souma-diagnosis
souma-diagnosis
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>そうまくんとすること診断</title>
  <style>
    body { font-family: sans-serif; text-align: center; margin-top: 50px; }
    input, button { padding: 10px; font-size: 16px; }
    #result { margin-top: 20px; font-weight: bold; font-size: 20px; }
  </style>
</head>
<body>
  <h1>そうまくんとすること診断</h1>
  <input type="text" id="nameInput" placeholder="あなたの名前を入力">
  <button onclick="showResult()">診断する</button>
  <div id="result"></div>

  <script>
    function showResult() {
      const name = document.getElementById("nameInput").value;
      if (!name) {
        document.getElementById("result").textContent = "名前を入力してください！";
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

      // 今日の日付を「YYYYMMDD」形式にする
      const today = new Date();
      const dateString = today.getFullYear() + "-" + (today.getMonth()+1) + "-" + today.getDate();

      // 名前と日付を組み合わせて数値化
      let hash = 0;
      const combined = name + dateString;
      for (let i = 0; i < combined.length; i++) {
        hash += combined.charCodeAt(i);
      }

      // 数値から結果を決める
      const index = hash % activities.length;
      const activity = activities[index];

      document.getElementById("result").textContent =
        `${name}さんの今日の診断結果は…「そうまくんと${activity}」です！`;
    }
  </script>
</body>
</html>
