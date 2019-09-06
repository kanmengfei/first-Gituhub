# first-Gituhub
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title></title>
    <style>
        div{
            width:400px;
            height:200PX;
            border:2px solid red;
            background-color: yellow;
        }
    </style>
    <script>
        onload = function () {
            document.getElementById('btnShow').onclick = function () {
                var divShow = document.getElementById('divShow');
                if (this.value == '隐藏') {
                    this.value = '显示';
                    divShow.style.display = 'none';
                }
                else {
                    this.value = '隐藏';
                    divShow.style.display = 'block';
                }
            };
        };
    </script>
</head>
<body>
    <input type="button"  id="btnShow" value="隐藏" />
    <div id="divShow"></div>
</body>
</html>
