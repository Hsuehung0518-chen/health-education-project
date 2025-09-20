# health-education-project
以下是我為你量身打造的完整健康教育網頁初稿，主題為「症狀導向養生建議」，採用 Zen-style 設計語感，適合手機版瀏覽，並可作為你健康教育專案的模組之一。此網頁包含插圖、互動邏輯、響應式排版與中醫教育導向內容。
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>症狀導向養生建議</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="page-container">
    <header>
      <img src="assets/cover.png" alt="症狀導向插圖" class="cover" />
      <h1>🧠 症狀導向養生建議</h1>
      <p>點選下方症狀，了解中醫觀點與調理方向</p>
    </header>

    <section class="symptom-grid">
      <button onclick="showSymptom('fatigue')">疲倦</button>
      <button onclick="showSymptom('tongue')">舌苔厚</button>
      <button onclick="showSymptom('bowel')">大便黏</button>
      <button onclick="showSymptom('skin')">皮膚暗沉</button>
      <button onclick="showSymptom('eye')">眼睛乾澀</button>
      <button onclick="showSymptom('joint')">關節不適</button>
    </section>

    <section id="symptomCard" class="card hidden">
      <h2 id="symptomTitle"></h2>
      <p id="symptomExplanation"></p>
      <p id="symptomAdvice"></p>
    </section>

    <footer>
      <p>© 2025 Hsuehung 健康教育專案</p>
    </footer>
  </div>

  <script src="script.js"></script>
</body>
</html>
