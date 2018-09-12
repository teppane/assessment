<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>英単語</title>
</head>

<center>

    <style>
    
h4 { 
color : hsl(0, 100%, 50%);
} 

h4 { 
font-size : 400%;
} 

    </style>
<body>

        <h4>英作文</h4>
    
    <script>




//乱数を出す
        var rnd = Math.floor(Math.random()*10 + 1);
         

         //問題の出題
            if(rnd==1){
                document.write("<h1>[問]This is a good book.<h1>");
            }else if(rnd==2){
                document.write("<h1>[問]This dictionary is good.<h1>");
            }else if(rnd==3){
                document.write("<h1>[問]Is That an interesting book?--Yes, it is.<h1>");
            }else if(rnd==4){
                document.write("<h1>[問]Is that book interesting?--No,it isn't.<h1>");
            }else if(rnd==5){
                document.write("<h1>[問]This is not right.<h1>");
            }else if(rnd==6){
                document.write("<h1>[問]That is not a real flower.<h1>");
            }else if(rnd==7){
                document.write("<h1>[問]This soup is not very tasty.<h1>");
            }else if(rnd==8){
                document.write("<h1>[問]Is this salt or sugar?--It is sugar.<h1>");
            }else if(rnd==9){
                document.write("<h1>[問]Is that woman French or Itakian?<h1>");
            }else{
                document.write("<h1>[問]Is that man Japaneseor Chinese?--He is Japanese.<h1>");
            }

  //答えボタンが押された後          
   function OnButtonClick() {
    if(rnd==1){
            target = document.getElementById("output");
            target.innerHTML = "これはいい本です";
            }else if(rnd==2 ){
                target = document.getElementById("output");
            target.innerHTML = "この辞書はいい";
            }else if(rnd==3 ){
                target = document.getElementById("output");
            target.innerHTML = "あれは面白い本ですか？--はい、そうです。";
            }else if(rnd==4 ){
                target = document.getElementById("output");
            target.innerHTML = "あの本はおもしろいですか？--いえ、面白くありません。";
            }else if(rnd==5 ){
                target = document.getElementById("output");
            target.innerHTML = "これは正しくない。";
            }else if(rnd==6 ){
                target = document.getElementById("output");
            target.innerHTML = "あれは本物の花ではない";
            }else if(rnd==7 ){
                target = document.getElementById("output");
            target.innerHTML = "このスープはあまり美味しくない。";
            }else if(rnd==8 ){
                target = document.getElementById("output");
            target.innerHTML = "これは塩ですか、それとも砂糖ですか？--砂糖です。";
            }else if(rnd==9 ){
                target = document.getElementById("output");
            target.innerHTML = "あの女性はフランス人ですか、それともイタリア人ですか？--フランス人です。";
            }else{
                target = document.getElementById("output");
            target.innerHTML = "あの男性は日本人ですか、それとも中国人ですか？--日本人です。";
            }
   }
        </script>



<input type="button" value="答え" onclick="OnButtonClick();"/><br />
<br />
<div id="output"></div>
<br><br>


<input type="button" value="次の問題へ" onclick="window.location.reload();" />
<br />
<div id="output"></div>
</body>
</html>
