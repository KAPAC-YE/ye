[index.html](https://github.com/user-attachments/files/23158606/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Месяц 2</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Курс по веб разработке</h1>
        <h2>Второй месяц обучения</h2>
    </header>
    <div class = "nav">
        <ul>
            <a href="index.html"> <li>wassup maboy</li></a>
            <a href="#timeosha"> <li>zdarova zemlya4ki</li></a>
            <form action="https://google.com/search" target="_blank">
            <input type="search" name="q" placeholder="Введите текст" class="poisk">
            <input type="submit" value="нажми пж" class="baton">
            </form>
        </ul>
    </div>
    <main>
        <div class = "venom_raz">
            <h2> markirovanniy spisok</h2>
            <ul type = "disk">
                <li>danil</li>
                <li>twopizza</li>
                <li>данил</li>
                <li>тупица</li>
            </ul>
        </div>
        <div class = "venom_dva">
            <h2> numerovaniy spisok</h2>
            <ol>
                <li>press ka4at</li>
                <li>anzhumanya</li>
                <li>otdih</li>
                <li>eshe podhod</li>
            </ol>
        </div>
        <div class = "venom_tri">
            <h2> morkovkoviy spisok</h2>
            <ul type = "disk">
                <li> timeosha</li>
                <li> spyat ustalie igrushki</li>
                <li> мощно</li>
                <li> и быстро</li>
            </ul>
        </div>
        <div class = "venom_4">
            <h2> Nurmagomedoviy spisok</h2>
            <ol>
                <li>danil</li>
                <li>ne ho4et</li>
                <li>ska4ivat</li>
                <li>rust</li>
            </ol>
        </div>
    </main>
    <div class = "block5">
        <form action = "https://www.b17.ru/article/shame_on_you/"> <button class = "botan1"> <img width = "200px" height = "100px" src = "images-Photoroom.png" > Ne nazimay na menya </ing></button> </form>
    </div>

    <footer id = "timeosha">
        <div>  &copy; IT школа Алтан </div>

        <div>
            <!-- Блок от социальных сетей -->
            <ul class="social">
                <li>
                    <a href="https://vk.com/altanschool"><img width="40px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/VK_Compact_Logo.svg/2048px-VK_Compact_Logo.svg.png" alt="Vk logo"></a>
                </li>
                <li>
                    <a href="https://t.me/altanschool"><img width="40px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Telegram_logo.svg/2048px-Telegram_logo.svg.png" alt="Telegram logo"></a>
                </li>
                <li>
                    <a href="https://api.whatsapp.com/send/?phone=79963168871&text&type=phone_number&app_absent=0"><img width="40px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/19/WhatsApp_logo-color-vertical.svg/768px-WhatsApp_logo-color-vertical.svg.png" alt="Whatsapp logo"></a>
                </li>

            </ul>
[style.css](https://github.com/user-attachments/files/23158618/style.css)

        </div>
    </footer>
    
</body>
</html>
[Uploading style.css…]()
body{
    margin: 0;                              /*убирает отступы от всех краев*/
    background-image: url(https://altanschool.s3.eu-central-1.amazonaws.com/learns/1697021662483_headerpic.jpg); /*изображение фона*/
    background-size: 100%;                  /*размер фона*/
    background-position-y: -50px;           /*изображение чуть поднято наверх*/
    background-attachment: fixed;           /*фиксация фона*/
}

header{
    height: 100%;               /*высота*/
    padding: 30px;          /*внутренний отступ*/
    text-align: right;      /*текст выровнени влево*/
    color: rgb(0, 0, 91); /*цвет текста*/
    font-size: 25px;        /*размер текста*/
}

h1{
    padding-top: 50px;  /*Дополнительный отступ заголовка*/
    font-size: 80px;    /*размер заголовка*/
    color:rgb(255, 255, 255);  /*цвет*/
}

form{
    width: 53%;
    float: right;
    display: flex;
}

input{
    padding: 7px 6px;
    border: 5px;
    font-size: 25px;
    margin: 5px;
}

.poisk{
    width: 100%;
}

.baton{
    width: 25%;
    background-color: brown;
    color: beige
}

.baton:hover{
    cursor: no-drop;
    background-color: black;
    color: red;
}

main{
    height: 1000px;   /*высота основной части*/
    display: flex;
}
footer{
    height: 100%;    /*высота*/
    text-align: left;  /*текст выровннен влево*/
    padding: 50px;   /*внутренний оступ*/
    color: white;  /*цвет текста*/
    font-size: 20px;  /*размер текста*/
}

.social{
    list-style: none; /*убирает маркеры*/
    display: flex; /*отображает в ряд*/
    align-items: left; /*выравнивает иконки по центру внутри каждого пункта*/
    justify-content: left; /*выравнивает все иконки по центру страницы*/
    margin: 0;
    padding: 0;
}

.social li {
    padding-left: 10px;
    padding-top: 20px;
}
.venom_raz{
    width: 25%;
    height: 40%;
    background-color: blue;
}
.venom_dva{
    width: 25%;
    height: 40%;
    background-color: red;
}
.venom_tri{
    width: 25%;
    height: 40%;
    background-color: yellow;
}
.venom_4{
    width: 25%;
    height: 40%;
    background-color: green;
}
.nav{
    position: sticky;
    top: 0;
}
.nav ul{
    list-style: none;
    margin: 0;
    padding: 0;
    background-color: purple;
    font-size: 30px;
    width: 100%;
    border: 2px solid hotpink;
    overflow: hidden;
}
.nav a{
    display: block;
    text-decoration: none;
    color: red;
    padding: 20 px 40 px;
    float: left;
    margin: 5px;
}
.nav a:hover{
    background-color: gray;
    color: black;
}

.block5{
    width: 100%;
    height: 300px;
    padding: 50px;
    background-color: aqua;
}

.botan1{
    width: 300px;
    height: 70;
    background-color: brown;
    color: black;
    padding: 42px 52px;
    font-size: 42px;
    text-align: bottom;
    text-decoration: none;
    border: 3px solid;
    display: inline;
    border-radius: none;
    box-shadow: none;
    cursor: not-allowed;
}

.botan1:hover{
    background-color: red;
}
