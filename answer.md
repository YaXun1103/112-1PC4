# 第4次練習-練習-PC4
>
>學號：111111109
><br />
>姓名：張雅薰
><br />
>作業撰寫時間：15 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2023/12/11
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x] 說明內容
- [x] 個人認為完成作業須具備觀念

## 說明程式與內容

先fork老師的倉庫並clone 
```
git clone
```
依照投影片範例，利用@keyframes做出閃爍效果
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .firstDiv{

            width: 220px;
            height: 220px;
            border: 1px solid #FF0000;
            position: relative;
        }
        .flashing {
            width: 20px;
            height: 20px;
            background-color: rgb(19, 154, 232);
            position: absolute;
            animation: flashing 2s infinite;
        }
        @keyframes flashing{
            0%{
                opacity: 1;
            }
            50%{
                opacity: 0;
            }
            100%{
                opacity: 1;
            }
        }
        </style>
</head>
<body>
    <div class="firstDiv">
            <div class="flashing"></div>
    </div>
</body>
</html>
```
推上github
```
git add 
git commit 
git push
```
## 個人認為完成作業須具備觀念

