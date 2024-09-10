<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>跳转到微信</title>
</head>
<body>
    <h2>点击下方按钮跳转到微信</h2>
    <button onclick="openWeChat()">跳转到微信</button>

    <script>
        function openWeChat() {
            // 跳转到微信的提示页面
            window.location.href = "weixin://";
        }
    </script>

    <p>如果按钮无法使用，请扫描下方二维码添加微信。</p>
    <img src="你的二维码链接.jpg" alt="扫码添加微信" width="200px">
</body>
</html>
