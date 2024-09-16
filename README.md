<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>微信举报系统</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #181818;
            font-family: 'Arial', sans-serif;
            overflow: hidden;
        }

        /* 外部渐变边框容器 */
        .border-container {
            position: relative;
            width: 420px;
            height: 420px;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #ff3d7f, #06d7ff, #ff3d7f);
            border-radius: 10px;
            padding: 2px;
        }

        /* 内部容器，内容保持不动 */
        .container {
            width: 100%;
            height: 100%;
            background-color: #1e1e1e;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
            text-align: center;
            position: relative;
        }

        /* 标题样式 */
        .container h1 {
            color: #fff;
            font-size: 24px;
            margin-bottom: 10px;
        }

        /* 描述文本 */
        .container p {
            color: #aaa;
            font-size: 16px;
            margin-bottom: 30px;
        }

        /* 登录按钮 */
        .login-btn {
            padding: 10px 30px;
            background-color: #fff;
            color: #000;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
        }

        /* 按钮悬停效果 */
        .login-btn:hover {
            background-color: #eaeaea;
        }
    </style>
</head>
<body>
    <div class="border-container">
        <div class="container">
            <h1>微信举报系统</h1>
            <p>网页端举报平台</p>
            <button class="login-btn">登录</button>
        </div>
    </div>
</body>
</html>
