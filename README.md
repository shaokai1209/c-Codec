### :wave: Hi, we’d like to invite you to listen to our demo.
<!DOCTYPE html>
<html>
<head>
    <style>
        /* 按钮容器样式 */
        .demo-button {
            display: inline-block;
            text-decoration: none;
            position: relative;
            transition: all 0.3s ease;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        /* 鼠标悬停效果 */
        .demo-button:hover {
            transform: scale(1.05); /* 轻微放大 */
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15); /* 加深阴影 */
        }
        /* 渐变遮罩（增强视觉层次） */
        .demo-button::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0) 100%);
            pointer-events: none;
        }
    </style>
</head>
<body>
    <a href='https://shaokai1209.github.io/c-Codec/index.html' target="_blank" class="demo-button">
        <img src='https://img.shields.io/badge/github.io-Audio Demo-Green?style=for-the-badge&logo=github&logoColor=white' 
             alt='github.io Audio Demo'/>
    </a>
</body>
</html>


:stuck_out_tongue_winking_eye: The codes will be organized and made publicly available upon the publication of the paper.
