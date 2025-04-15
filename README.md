# luminous-meow-star
My personal MeowMeow web
打開終端機（Terminal）或命令提示字元（Command Prompt），並切換到你本地的專案資料夾。
初始化 Git 倉庫（如果尚未初始化):
git init
將遠端 repository 設定為 origin:
git remote add origin https://github.com/pada20/luminous-meow-star.git
新增所有檔案並提交：
git add .
git commit -m "Initial commit"
推送到 GitHub:git push -u origin main
建立一個 index.html 文件：
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>喵喵的網站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            background-color: #f0f0f0;
        }
        h1 {
            color: #ff6b6b;
        }
    </style>
</head>
<body>
    <h1>歡迎來到喵喵的網站！</h1>
    <p>這是一個簡單的示範網站。</p>
</body>
</html>
