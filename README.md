# 2026-kamakura
鎌倉三日遊
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kamakura Trip 2024</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;700&display=swap');
        body { font-family: 'Noto Sans TC', sans-serif; background-color: #F9F7F2; color: #333; }
        .card { background: white; border-radius: 16px; box-shadow: 0 4px 6px rgba(0,0,0,0.02); margin-bottom: 16px; border-left: 4px solid #D4C3A3; }
        .tag-food { background: #FFE4E1; color: #CD5C5C; padding: 2px 8px; border-radius: 4px; font-size: 12px; font-weight: bold; }
        .tag-spot { background: #E0EEE0; color: #2E8B57; padding: 2px 8px; border-radius: 4px; font-size: 12px; font-weight: bold; }
        .nav-btn { background: #2C2C2C; color: white; padding: 8px 16px; border-radius: 20px; font-size: 14px; display: inline-flex; align-items: center; gap: 8px; }
        .tab-bar { position: fixed; bottom: 0; left: 0; right: 0; background: white; display: flex; justify-content: space-around; padding: 12px; border-top: 1px solid #EEE; }
    </style>
</head>
<body class="pb-24">

    <header class="p-6 bg-white shadow-sm">
        <h1 class="text-2xl font-bold">鎌倉 · 10/26 - 10/28</h1>
        <div class="mt-2 text-sm text-gray-500 flex items-center gap-2">
            <i class="fas fa-sun text-yellow-500"></i> 18°C / 24°C · 鎌倉市即時預報
        </div>
    </header>

    <main class="p-4">
        <section>
            <h2 class="text-lg font-bold mb-4 flex items-center gap-2">
                <span class="bg-black text-white px-2 py-1 rounded">Day 2</span> 10/27 (日)
            </h2>

            <div class="card p-4">
                <div class="flex justify-between items-start">
                    <div>
                        <span class="tag-food">早餐 / 必吃美食</span>
                        <h3 class="text-xl font-bold mt-1">bills 七里濱</h3>
                        <p class="text-gray-500 text-sm mt-1"><b>必點：</b>香蕉蜂蜜奶油鬆餅</p>
                    </div>
                    <a href="https://www.google.com/maps/search/?api=1&query=bills+Shichirigahama" class="nav-btn">
                        <i class="fas fa-location-arrow"></i> 導航
                    </a>
                </div>
                <div class="mt-3 text-sm text-gray-600 border-t pt-2">
                    💡 攻略：建議提早預約或日出後直接前往，窗外即是海岸線。
                </div>
            </div>

            <div class="card p-4" style="border-left-color: #778899;">
                <div class="flex justify-between items-start">
                    <div>
                        <span class="tag-spot">景點 / 攻略</span>
                        <h3 class="text-xl font-bold mt-1">長谷寺 & 高德院大佛</h3>
                        <p class="text-gray-500 text-sm mt-1"><b>必看：</b>日本三大佛像之一，青銅結構。</p>
                    </div>
                    <a href="https://www.google.com/maps/search/?api=1&query=鎌倉大佛" class="nav-btn">
                        <i class="fas fa-location-arrow"></i> 導航
                    </a>
                </div>
                <div class="mt-3 text-sm text-gray-600 border-t pt-2">
                    📌 攻略：大佛內部可以進入（需另付 20 日圓），體驗獨特空間感。
                </div>
            </div>
        </section>
    </main>

    <nav class="tab-bar">
        <div class="text-center text-xs text-gray-400 font-bold"><i class="fas fa-calendar-day text-lg block"></i>行程</div>
        <div class="text-center text-xs text-gray-400"><i class="fas fa-plane text-lg block"></i>資訊</div>
        <div class="text-center text-xs text-gray-400"><i class="fas fa-calculator text-lg block"></i>記帳</div>
    </nav>

</body>
</html>
