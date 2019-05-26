<style> html { height: 100%; }
    body {
        background-image: url("https://storage.googleapis.com/smiletaiwan-cms-cwg-tw/article/201805/article-5afd3c77edcdf.jpg");
        background-repeat: no-repeat;
        background-attachment: fixed;
        background-position: center;
        background-size: cover;
    }
    
    p {
        font-size: 18px;
        font-family: Microsoft JhengHei;
    }
    
    h2 {
        font-family: "微軟正黑體";
        font-weight: bold;
    }
    
    td {
        font-family: "微軟正黑體";
        font-size: 18px;
    }
    /* button*/
    .button {
        background-color: #a0fdff;
        border: 2px solid black;
        color:  #0645ad;
        padding: 8px 24px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        display: block;
    }
    
    .button:hover {
        background-color: #A1D0FF;
    }
    
    #flip {
        background-color: #a0fdff;
        border: 2px solid black;
        color: black;
        padding: 8px 42px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        display: block;
    }
    
    .button-bar {
        position: fixed;
        top: 5%;
        right: 5%;
    }
    
    
    
    
    /*light box*/
    
     * {
        box-sizing: border-box
    }
    
    body {
        font-family: Verdana, sans-serif;
        margin: 0
    }
    
    .mySlides {
        display: none
    }
    
    img {
        vertical-align: middle;
    }
    /* Slideshow container */
    
    .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
    }
    /* Next & previous buttons */
    
    .prev,
    .next {
        cursor: pointer;
        position: absolute;
        top: 50%;
        width: auto;
        padding: 16px;
        margin-top: -22px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
    }
    /* Position the "next button" to the right */
    
    .next {
        right: 0;
        border-radius: 3px 0 0 3px;
    }
    /* On hover, add a black background color with a little bit see-through */
    
    .prev:hover,
    .next:hover {
        background-color: rgba(0, 0, 0, 0.8);
    }
    /* Caption text */
    
    .text {
        color: #f2f2f2;
        font-size: 15px;
        padding: 8px 12px;
        position: absolute;
        bottom: 8px;
        width: 100%;
        text-align: center;
    }
    /* Number text (1/3 etc) */
    
    .numbertext {
        color: #f2f2f2;
        font-size: 12px;
        padding: 8px 12px;
        position: absolute;
        top: 0;
    }
    /* The dots/bullets/indicators */
    
    .dot {
        cursor: pointer;
        height: 15px;
        width: 15px;
        margin: 0 2px;
        background-color: #bbb;
        border-radius: 50%;
        display: inline-block;
        transition: background-color 0.6s ease;
    }
    
    .active,
    .dot:hover {
        background-color: #717171;
    }
    /* Fading animation */
    
    .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
    }
    
    @-webkit-keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    
    @keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    /* On smaller screens, decrease text size */
    @media only screen and (max-width: 300px) {
        .prev,
        .next,
        .text {
            font-size: 11px
        }
    }
    
    
    
    
    /*tabs*/
     body {
        font-family: Arial;
    }
    /* Style the tab */
    
    .tab {
        overflow: hidden;
        border: 1px solid #ccc;
        background-color: #f1f1f1;
    }
    /* Style the buttons inside the tab */
    
    .tab button {
        background-color: inherit;
        float: left;
        border: none;
        outline: none;
        cursor: pointer;
        padding: 10px 12px;
        transition: 0.3s;
        font-size: 17px;
    }
    /* Change background color of buttons on hover */
    
    .tab button:hover {
        background-color: #ddd;
    }
    /* Create an active/current tablink class */
    
    .tab button.active {
        background-color: #ccc;
    }
    /* Style the tab content */
    
    .tabcontent {
        display: none;
        padding: 6px 12px;
        border: 1px solid #ccc;
        border-top: none;
    }
    
    
    /*video*/
    .video-container {
    position: relative;
    padding-bottom: 56.25%;
    padding-top: 30px;
    height: 0;
    overflow: hidden;
    }

    .video-container iframe,
    .video-container object,
    .video-container embed {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    }

   
</style>

<head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
    <script>
        $(document).ready(function() {
            $('#top').click(function() {
                $('html, body').animate({
                    scrollTop: 0
                }, 1000);
            });
            $('#bottom').click(function() {
                $('html, body').animate({
                    scrollTop: $(document).height() - $(window).height()
                }, 1000);
            });
            $('#a').click(function() {
                $('html, body').animate({
                    scrollTop: $("#A").offset().top
                }, 1000);
            });
            $('#b').click(function() {
                $('html, body').animate({
                    scrollTop: $("#B").offset().top
                }, 1000);
            });
            $('#c').click(function() {
                $('html, body').animate({
                    scrollTop: $("#C").offset().top
                }, 1000);
            });
            $('#d').click(function() {
                $('html, body').animate({
                    scrollTop: $("#D").offset().top
                }, 1000);
            });
            $('#e').click(function() {
                $('html, body').animate({
                    scrollTop: $("#E").offset().top
                }, 1000);
            });
            $('#f').click(function() {
                $('html, body').animate({
                    scrollTop: $("#F").offset().top
                }, 1000);
            });
            $("#flip").click(function() {
                $(".button").slideToggle("slow");
            });
        });
    </script>
</head>
<div id="google_translate_element"></div>

<script type="text/javascript">
function googleTranslateElementInit() {
  new google.translate.TranslateElement({pageLanguage: 'zh-tw', layout: google.translate.TranslateElement.InlineLayout.SIMPLE}, 'google_translate_element');
}
</script>

<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
<center><h1 style="font-size:40px;font-weight:bold;">陽明山國家公園</h1></center>

<h2 class="header-level-2" id="A">基本資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <ol>
        <li>
            <p>陽明山國家公園是台灣設置的第三個國家公園，建立於1985年9月1日，前身為臺灣日治時期成立之大屯國立公園。位於臺北都會區近郊，行政區域 包括臺北市北投區、士林區，新北市的萬里區、金山區、石門區、三芝區、淡水區一帶；地理上則屬於大屯火山彙區域，占地113平方公里，陽明山原名草山，泛指大屯山、七星山、紗帽山、小觀音山這一帶的山區，而非單指某座山峰。清治時期，官府憂慮賊寇可匿於林中竊取硫磺，故定期放火燒山，因此整個山區只能長出五節芒這類的芒草。日治時期，1927年，臺灣日日新報舉辦民眾投票，選出「臺灣八景十二勝」，草山獲選為臺灣十二勝之一。日本人稱草山為「臺灣的箱根」。1932年成立大屯國立公園協會，將大屯山地區列入國立公園的範圍。1937年12月27日，大屯國立公園與次高太魯閣、新高阿里山兩處國立公園同時成立，直到1945年二次大戰日本投降。唯當時的大屯國立公園尚包括淡水河對岸的觀音山。1945年國民政府接管臺灣，1950年，總統蔣中正為紀念明代學者王陽明，將大屯山、七星山、紗帽山、小觀音山一帶，原名草山的山區改名為陽明山。1962年，當時的臺灣省公共工程局開始規劃，初步規劃面積為28,400公頃，包括北海岸、觀音山與大屯火山群。1985年9月16日，經過多年規劃並解決土地資源糾紛後，陽明山國家公園正式成立，其範圍以大屯火山彙的中心地帶為主，並未包含日治時期及初期規劃中的觀音山，北海岸亦不包括在內。2002年10月17日，上述兩地區另行由交通部觀光局規劃成立北海岸及觀音山國家風景區。 </p>
        </li>
        
    </ol>
</div>

<h2 class="header-level-2" id="B">國家公園標示意涵:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <img align="left" style="width: 100px; height: 100px;" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQRuYnTlRmWatGzSkAocAeExuYxtG57lndSONluSTT9-g_BX2mj" data-type="image">
    <center>
        <p>1. 處徽整體主軸為展現陽明山的火山地質地形。
2. 三角形設計即代表陽明山國家公園以火山地形為主體。
3. 圓形代表整個地球與物質循環、生生不息，永續利用之保育觀念。
4. 三角凹凸形狀，代表區內之最高峰七星山。
5. 樹型代表自然界之動植物。
6. 圍繞三角形外之波紋代表陽明山國家公園特殊之硫磺噴氣及雨霧。
7. 綠底藍紋即意喻綠地與藍天是人類生存的空間所在。。
        </p>
    </center>
</div>

<h2 class="header-level-2" id="C">特色介紹:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">

<p></p>
    <body>

<div class="tab">
    <button class="tablinks" onclick="openCity(event, '氣候')" id="defaultOpen">氣候</button>
    <button class="tablinks" onclick="openCity(event, '地形景觀')">地形景觀</button>
    <button class="tablinks" onclick="openCity(event, '動物')">動物</button>
    <button class="tablinks" onclick="openCity(event, '植物')">植物</button>
    
   
    <button class="tablinks" onclick="openCity(event, '相關影音')">相關影音</button>
</div>

<div id="氣候" class="tabcontent">
    <h2>氣候</h2>
    <p>本區約位於北緯25度，有明顯的亞熱帶地區季風型氣候的特徵，夏季受到西南季風影響，多為晴朗，午後有雷陣雨的天氣，冬季則因東北季風南下而變得潮濕多雨，年雨量多達4000毫米，降雨日數也在190天以上。</p>
   
</div>

<div id="地形景觀" class="tabcontent">
    
    <h2>地形</h2>
    <p> 一、水系 : 高聳山嶺為發源地，向四方奔流而下，形成火山區特有之輻射狀山系。</p>
    <p> 二、山峰 : 山巒起伏，而以層狀火山居多，此類火山以錐狀為其特徵，火山口小，但噴出之熔岩流與碎屑物卻披覆相當廣闊之地區。</p>
    <p> 三、火山口 : 大屯山西鄰馬鞍形之面天山，西邊的一個直徑230公尺，深45公尺，近似梨形，舊時積水成湖，稱為「面天池」，今日登山界所稱之「向天池」乃指此而言。目前此地只有在雨天時才會積點水，天晴時便整個乾涸掉。七星山東南山腰上的小窪地，一個長約200公尺，積水成湖，乃遊客所嚮往的「夢幻湖」。</p>
    <p> 四、閉塞湖 : 大屯火山群之各火山體所噴發的熔岩流或碎屑物，經常在坡下錯綜交疊，有時兩個火山之熔岩流將其間之谷地圍堵而造成湖泊。</p>
    <p>五、噴氣孔 : 引人入勝的景觀，莫過於火山活動後期地底殘餘岩漿活動所造成的各種現象。</p>
    <p>六、溫泉 : 金山斷層沿線許多地殼裂隙發達的地方，地表水順著裂縫下滲到深處，受溫度仍高的火山岩體加熱，再度冒出地表。</p>
</div>

<div id="動物" class="tabcontent">
   
    <p>因地形陡峭及人為活動頻繁，較不利於大型哺乳動物活動，但複雜的林相仍然提供了許多中、小型野生動物理想的活動、覓食和棲息場所；在生態保護區內臺灣獼猴、臺灣野豬、臺灣野兔、赤腹松鼠、白鼻心、臺灣鼴鼠、刺鼠、鬼鼠等哺乳動物活動頻繁，活動範圍以鹿角坑溪、磺嘴山一帶的天然闊葉林與草原為主，其中又以赤腹松鼠最為常見，足跡幾乎遍及全區。</p>
  
</div>

 <div id="植物資源" class="tabcontent">
    
    <p>目前園區內的植物種類含部份馴化栽培種共約有1359種，生育環境包括水生與陸生兩種，陸生大致可分為芒草原、矢竹林、闊葉林與人工造林等。</p>
</div>





<div id="相關影音" class="tabcontent">
<div class="video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/I6tPmzxxJ4g" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    </div>





<script>
    function openCity(evt, cityName) {
        var i, tabcontent, tablinks;
        tabcontent = document.getElementsByClassName("tabcontent");
        for (i = 0; i < tabcontent.length; i++) {
            tabcontent[i].style.display = "none";
        }
        tablinks = document.getElementsByClassName("tablinks");
        for (i = 0; i < tablinks.length; i++) {
            tablinks[i].className = tablinks[i].className.replace(" active", "");
        }
        document.getElementById(cityName).style.display = "block";
        evt.currentTarget.className += " active";
    }

    // Get the element with id="defaultOpen" and click on it
    document.getElementById("defaultOpen").click();
</script>
    <p></p>
        <div class="slideshow-container">

    <div class="mySlides fade">
        <div class="numbertext">1 / 5</div>
        <img style="width:100%;height:400px" src="https://www.funtime.com.tw/blog/wp-content/uploads/2017/08/28.png">
        <div class="text"> 夢幻湖</div>
    </div>

    <div class="mySlides fade">
        <div class="numbertext">2 / 5</div>
        <img style="width:100%;height:400px" src="https://www.funtime.com.tw/blog/wp-content/uploads/2017/08/130.jpg" >
        <div class="text"> 擎天崗</div>
    </div>

    <div class="mySlides fade">
        <div class="numbertext">3 / 5</div>
        <img style="width:100%;height:400px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTCQbpF2Ed1cBs92fJpY4bIFw8aLfNKPjMt8hR7sl3AnYO_cDSyoQ">
        <div class="text"> 山羌</div>
    </div>
    
    <div class="mySlides fade">
        <div class="numbertext">4 / 5</div>
        <img style="width:100%;height:400px" src="https://www.ymsnp.gov.tw/filesys/images/ch/csv/rsc/resource04-01.jpg">
        <div class="text"> 赤腹松鼠  </div>
    </div>
    
    <div class="mySlides fade">
        <div class="numbertext">5 / 5</div>
        <img style="width:100%;height:400px" src="https://www.ymsnp.gov.tw/filesys/images/ch/csv/rsc/resource03-01.jpg">
        <div class="text"> 臺灣龍膽</div>
    </div>
    
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>


<br>

<div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
    <span class="dot" onclick="currentSlide(4)"></span>
    <span class="dot" onclick="currentSlide(5)"></span>
</div>

<script>
    var slideIndex = 1;
    showSlides(slideIndex);

    function plusSlides(n) {
        showSlides(slideIndex += n);
    }

    function currentSlide(n) {
        showSlides(slideIndex = n);
    }

    function showSlides(n) {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        var dots = document.getElementsByClassName("dot");
        if (n > slides.length) {
            slideIndex = 1
        }
        if (n < 1) {
            slideIndex = slides.length
        }
        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
        }
        for (i = 0; i < dots.length; i++) {
            dots[i].className = dots[i].className.replace(" active", "");
        }
        slides[slideIndex - 1].style.display = "block";
        dots[slideIndex - 1].className += " active";
    }
</script>
    
    
    
    <p></p>
</div>


<h2 class="header-level-2" id="D">交通資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
      <body>
<div class="tab">
    <button class="tablinks" onclick="openCity(event, '遊園公車')">遊園公車</button>
    <button class="tablinks" onclick="openCity(event, '聯營公車')">聯營公車</button>
    <button class="tablinks" onclick="openCity(event, '休閒公車')">休閒公車</button>
    <button class="tablinks" onclick="openCity(event, '公路客運')">公路客運</button>
    <button class="tablinks" onclick="openCity(event, '租車')">租車</button>
    

</div>
<p>1．台北火車站到陽明山國家公園管理處<br>
（1）北二門搭乘260公車到陽明山站（終點站)到轉搭108遊園公車到陽明山國家公園管理處<br>
（2）搭乘捷運淡水線、北投線到捷運劍潭站到轉搭紅5到陽明山站（終點站）轉搭108遊園公車到陽明山國家公園管理處<br>
2．台灣高鐵台北站到陽明山國家公園管理處<br>
（1）北二門搭乘260公車到陽明山站（終點站)轉搭108遊園公車<br>
（2）搭乘捷運淡水線、北投線到捷運劍潭站到轉搭紅5到陽明山站（終點站）轉搭108遊園公車到陽明山國家公園管理處<br>
3．公園路（台北車站)到陽明山國家公園管理處<br>
搭乘1717皇家客運到陽明山國家公園管理處<br>
4．捷運劍潭站到陽明山國家公園管理處<br>
搭乘紅5到陽明山站（終點站轉搭108遊園公車到陽明山國家公園管理處<br>
5．捷運石牌站到陽明山國家公園管理處<br>
搭乘小8到陽明山國家公園管理處<br>
6．捷運北投站到陽明山國家公園管理處<br>
（1）搭乘小9到陽明山國家公園管理處<br>
（2）搭乘230公車陽明山站轉搭108遊園公車到陽明山國家公園管理處<br>
7．東湖到陽明山國家公園管理處<br>
搭乘681到陽明山國家公園管理處<br> </p>
<div id="遊園公車" class="tabcontent">
    <h2 style="color:#FF8800;font-weight:bold;">遊園公車:</h2>
   
<p>
        <table border="1" cellpadding="5" cellspacing="0" width="90%">
            <thead>
                <tr>
                    <th width="31%">名稱 </th>
                    <th width="47%">路線 </th>
                  
                </tr>
            </thead>
            <tbody>


                <tr>
                    <td>108</td>
                    <td>陽明山遊園公車</td>
                    
                </tr>

                <tr>
                    <td>108區</td>
                    <td>陽明山－二子坪</td>
                    
                </tr>

               
                </tbody>
        </table>
    </p>
</div>

<div id="聯營公車" class="tabcontent">
    <h2 style="color:#FF8800;font-weight:bold;">聯營公車:</h2>
    <p>
        <table border="1" cellpadding="5" cellspacing="0" width="90%">
            <thead>
                <tr>
                    <th width="31%">名稱 </th>
                    <th width="47%">路線 </th>
                  
                </tr>
            </thead>
            <tbody>


                <tr>
                    <td>230</td>
                    <td>捷運北投站─陽明山</td>
                    
                </tr>

                <tr>
                    <td>260</td>
                    <td>東園─陽明山</td>
                    
                </tr>

                <tr>
                    <td>260區</td>
                    <td>臺北車站─陽明山</td>
                   
                </tr>

                <tr>
                    <td>303 </td>
                    <td>捷運劍潭站─大坪尾</td>
                    
                </tr>

                <tr>
                    <td>303區	</td>
                    <td>捷運劍潭站─平等里</td>
                    
                </tr>

                <tr>
                    <td>681	</td>
                    <td>東湖站─陽明山國家公園管理處</td>
                </tr>

                <tr>
                    <td>紅5	</td>
                    <td>捷運劍潭站─陽明山</td>
                    
                </tr>

                <tr>
                    <td>小6	</td>
                    <td>北投站─清天宮</td>
                   
                </tr>

                <tr>
                    <td>小7</td>
                    <td>北投站─嶺頭</td>
                    
                </tr>
                 <tr>
                    <td>小8</td>
                    <td>捷運石牌站─竹子湖</td>
                    
                </tr>
                 <tr>
                    <td>小9</td>
                    <td>(台灣好行-北投竹子湖)	捷運北投站─竹子湖</td>
                    
                </tr>
                 <tr>
                    <td>小15</td>
                    <td>捷運劍潭站─擎天崗</td>
                    
                </tr>
                 <tr>
                    <td>小15區</td>
                    <td>捷運劍潭站─菁山遊憩區</td>
                    
                </tr>
                
                 <tr>
                    <td>小18</td>
                    <td>捷運劍潭站─聖人瀑布</td>
                    
                </tr>
                 <tr>
                    <td>小19</td>
                    <td>捷運劍潭站─平等里</td>
                    
                </tr>
                 <tr>
                    <td>小25</td>
                    <td>捷運北投站─六窟</td>
                    
                </tr>
                <tr>
                    <td>小26</td>
                    <td>北投站─頂湖</td>
                    
                </tr>
                <tr>
                    <td>小36</td>
                    <td>捷捷運石牌站─六窟</td>
                    
                </tr>
                <tr>
                    <td>市民小巴1</td>
                    <td>捷運劍潭站─風櫃嘴</td>
                    
                </tr>
                </tbody>
        </table>
    </p>
</div>

<div id="休閒公車" class="tabcontent">
    <h2 style="color:#FF8800;font-weight:bold;">休閒公車(僅假日行駛):</h2>

    <table border="1" cellpadding="5" cellspacing="0" width="90%">
        <thead>
            <tr>
                <th width="31%">名稱 </th>
                <th width="18%">路線 </th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <td>109</td>
                <td>萬芳社區─陽明山國家公園管理處</td>
            </tr>

            <tr>
                <td>111</td>
                <td>	捷運迴龍站─陽明山國家公園管理處</td>
            </tr>

            <tr>
                <td>128</td>
                <td>捷運石牌站─陽明山國家公園管理處</td>
            </tr>

            <tr>
                <td>129</td>
                <td>	捷運北投站─竹子湖</td>
            </tr>

        </tbody>
    </table>
    
</div>
<div id="公路客運" class="tabcontent">
    <h2 style="color:#FF8800;font-weight:bold;">公路客運:</h2>
   
<p>
        <table border="1" cellpadding="5" cellspacing="0" width="90%">
            <thead>
                <tr>
                    <th width="31%">名稱 </th>
                    <th width="47%">路線 </th>
                  
                </tr>
            </thead>
            <tbody>


               

                <tr>
                    <td>1717</td>
                    <td>臺北車站─陽明山─金山</td>
                    
                </tr>

               
                </tbody>
        </table>
    </p>
</div>




<script>
    function openCity(evt, cityName) {
        var i, tabcontent, tablinks;
        tabcontent = document.getElementsByClassName("tabcontent");
        for (i = 0; i < tabcontent.length; i++) {
            tabcontent[i].style.display = "none";
        }
        tablinks = document.getElementsByClassName("tablinks");
        for (i = 0; i < tablinks.length; i++) {
            tablinks[i].className = tablinks[i].className.replace(" active", "");
        }
        document.getElementById(cityName).style.display = "block";
        evt.currentTarget.className += " active";
    }

    // Get the element with id="defaultOpen1" and click on it
    document.getElementById("defaultOpen1").click();
</script>
</body>
</div>



<h2 class="header-level-2" id="E">住宿資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <p>
        <table border="1" cellpadding="5" cellspacing="0" width="90%">
            <thead>
                <tr>
                    <th width="25%">民宿/飯店 </th>
                    <th width="48%">地址 </th>
                    <th width="24%">聯絡電話 </th>
                </tr>
            </thead>
            <tbody>

                <tr>
                    <td>麗之湯溫泉會館</td>
                    <td>台北市北投區溫泉路銀光巷4-2號</td>
                    <td>07-9682715</td>
                </tr>

                <tr>
                    <td>陽明山天籟渡假酒店</td>
                    <td>新北市金山區名流路1之7號</td>
                    <td>02-2408-0000</td>
                </tr>

                <tr>
                    <td>陽明山出霧溫泉飯店</td>
                    <td>新北市金山區山城路82之3號</td>
                    <td>02-24080666#1</td>
                </tr>

                <tr>
                    <td>陽明山中國麗緻大飯店</td>
                    <td>台北市士林區格致路237號</td>
                    <td>02 2861 6661</td>
                </tr>

                <tr>
                    <td>金山劉住春天 原宿溫泉民宿</td>
                    <td>208新北市金山區名流路10巷11號</td>
                    <td>0955 937 226</td>
                </tr>
            </tbody>
        </table>
    </p>
</div>

<h2 class="header-level-2" id="F">美食資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <p>
        <table border="1" cellpadding="5" cellspacing="0" width="90%">
            <thead>
                <tr>
                    <th width="31%">店名</th>
                    <th width="43%">地址 </th>
                    <th width="23%">聯絡電話 </th>
                    <th width="23%">營業時間 </th>
                </tr>
            </thead>
            <tbody>

                <tr>
                    <td>The cafe’ by 想 陽明山</td>
                    <td>台北市士林區陽明里光華路30號</td>
                    <td>02 2862 6628</td>
                    <td>上午9:30 – 下午8:00</td>
                </tr>

                <tr>
                    <td>草山夜未眠景觀餐廳</td>
                    <td>台北市士林區東山路25巷81弄99號</td>
                    <td>02 2862 3751</td>
                    <td>周一至周四16:00 – 3:00周五16:00 – 5:00周六12:00 – 5:00周日12:00 – 3:00</td>
                </tr>

                <tr>
                    <td>皇池溫泉御膳館</td>
                    <td>台北市北投區行義路402巷42之1號</td>
                    <td>02 2862 3688</td>
                    <td>皇池一館泡湯24小時，用餐中午12：00～凌晨03：00</td>
                </tr>

                <tr>
                    <td>白房子Yang Ming Caf’e</td>
                    <td>台北市士林區愛富二街厚生巷2號</td>
                    <td>(02)2861-1777</td>
                    <td>10:00–21:00</td>
                </tr>

                <tr>
                    <td>蒙馬特影像咖啡 </td>
                    <td>台北市士林區菁山路131巷13號</td>
                    <td>02 2862 4347</td>
                    <td>早上10:00–19:00</td>
                </tr>
            </tbody>
        </table>
    </p>
</div>

<h2 class="header-level-2">資料來源:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <ul>
        <li><a href="http://np.cpami.gov.tw/">台灣國家公園</a></li>
        <br>
        <li><a href="https://www.ymsnp.gov.tw/">陽明山國家公園</a></li>
        <br>
        
        <li><a href="https://www.mecocute.com/ymsnp/">台北美食：陽明山美食溫泉餐廳小吃景點推薦，陽明山必吃美食必去景點</a></li>
        <br>
        <li><a href="https://www.trivago.com.tw/?themeId=457&iGeoDistanceItem=2512484&sem_keyword=%E9%99%BD%E6%98%8E%E5%B1%B1%20%E4%BD%8F%E5%AE%BF%20%E6%8E%A8%E8%96%A6&sem_creativeid=333376697745&sem_matchtype=e&sem_network=g&sem_device=c&sem_placement=&sem_target=&sem_adposition=1t1&sem_param1=&sem_param2=&sem_campaignid=1682128211&sem_adgroupid=71121431928&sem_targetid=kwd-635820411482&sem_location=1012825&cip=8861901253&gclid=EAIaIQobChMI3dPGgaKi4gIVGq6WCh2bkwmiEAAYASAAEgK6oPD_BwE">trivago</a></li>
        <br>
        <li><a href="https://zh.wikipedia.org/wiki/%E9%99%BD%E6%98%8E%E5%B1%B1%E5%9C%8B%E5%AE%B6%E5%85%AC%E5%9C%92">維基百科</a></li>
    </ul>
</div>

<div class="button-bar">
    <a id="flip">選單</a>
    <a class="button" id="a" href="#">基本資訊</a>
    <a class="button" id="b" href="#">標示意涵</a>
    <a class="button" id="c" href="#">特色介紹</a>
    <a class="button" id="d" href="#">交通資訊</a>
    <a class="button" id="e" href="#">住宿資訊</a>
    <a class="button" id="f" href="#">美食資訊</a>
    <a class="button" id="top" href="#">網頁頂端</a>
    <a class="button" id="bottom" href="#">網頁底部</a>
    <a class="button" id="home" href="https://jim99224.github.io/HomePage/">返回主頁</a>
</div>

