<!DOCTYPE html>
<html lang="HE">
<head>
  <title>בית בקהילה</title>
<link rel="stylesheet" type="text/css" href="style.css" />
</head>

<body>
  <!-- -----------------  menu  ----------------->
    <div id="menu">
    <a href="#about">קצת עלינו</a>
    <a href="#photos">התמונות שלנו</a>
    <a href="#playlist">השירים שלנו</a>
    <a href="#like">לייק</a>
    <a href="#qrcoder">קוד סריקה</a>
    <a href="#contact">צור קשר</a>
    </div>
		  
    <!-- -----------------  about  ----------------->
<section id="about" class="section">

<h1>    בית בקהילה    </h1>


<p>
 <span style="font-weight: bolder;">יוצרים משפחה שהיא חלק מקהילה פעילה</span> <br><br>
  כולנו רוצים את הטוב ביותר לילדינו
   וכשהם גדלים אנו רוצים לראותם פורשים כנפיים ועפים.
   כהורים לילדים עם מוגבלות השאיפה הזו נראית 
  לרוב כחלום רחוק. כשהילד שלנו מגיע לגיל 21 רבים מאיתנו
   מוצאים שהפתרון הטוב ביותר עבורו, הוא להשאירו בבית.
   החלטה זו מציבה בפנינו אתגרים לא פשוטים.
  אנו מאמינים
   שלכל אדם עומדת הזכות להזדמנות שווה לחיות חיים מלאים ומשמעותיים.
   על כן כחלק מרכזי בתכנית לשילוב אנשים עם מוגבלות הקמנו
   את 'בית בקהילה': בתים לאנשים עם מוגבלות בקהילותינו. 
  הבתים של בית בקהילה מקנים לחברי הדירה 
  מרחב נוח, בטוח ומשפחתי בעודם חלק מקהילה פעילה חמה ומחבקת.
  
  הבתים ממוקמים בשכונת מגורים, קרוב 
  ככל האפשר למרכז הקהילה. משפחות חברי הבתים מוזמנים לקחת
   חלק בקהילה ולחוות מעגל קהילתי תומך, בתוך קהילת האם.
</p>
<br/>
<br/>
<br/>
</section>

<!-- -----------------  photos  ----------------->

<section id="photos" class="section">

<h1> התמונות שלנו</h1>

  <img src="pic1.jpeg" width="600" height="450">
  <img src="pic2.jpeg" width="600" height="450">
  <!--  <img src="pic3.jpeg" width="530" height="450"> -->
  <img src="pic6.jpeg" width="960" height="600">

</section>

<!-- -----------------  songs  ----------------->

<section id="playlist" class="section">

  <h1>  השירים שלנו </h1>
<br/>

<iframe width="560" height="315" src="https://www.youtube.com/embed/28WbOW1WUn8?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/wSQCw8IEjOA?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/tgbNymZ7vqY"> </iframe>

<br/>
</section>

<!-- -----------------  like  ----------------->


<section id="like" class="section">

<h1> נשמח מכם ללייק </h1>


<!-- LikeBtn.com BEGIN -->
<span class="likebtn-wrapper" data-theme="large" data-lang="he"></span>
<script>(function(d,e,s){if(d.getElementById("likebtn_wjs"))return;a=d.createElement(e);m=d.getElementsByTagName(e)[0];a.async=1;a.id="likebtn_wjs";a.src=s;m.parentNode.insertBefore(a, m)})(document,"script","//w.likebtn.com/js/w/widget.js");</script>
<!-- LikeBtn.com END -->
 

</section>

<!-- -----------------  qrcoder  ----------------->


<section id="qrcoder" class="section">

   <h1>קוד סריקה</h1>         
  <img src="frame.png" width="500px" height="500px">


</section>

<!-- -----------------  contact  ----------------->

<section id="contact" class="section">

    <h1> <u> צרו קשר </u> </h1>
<br/>

    <form id="fo">
    <input type="text" size="20px">
    <label> : הקלד את שמך  </label>  <br> 
    
    <input type="text" size="28px">
    <label> : Email  </label>  <br>

    <input type="text" size="29px">
    <label> : נושא  </label>  <br> 
    
    <textarea name="message" rows="10" cols="29"> </textarea>
    <label> : הודעה  </label>  <br><br>

    <input type="submit">
    </form>
    


<br/>
</section>




<script type="text/javascript">
$(function(){
  $("#nav a").click(function(e){
    e.preventDefault();
    $('html,body').scrollTo(this.hash,this.hash); 
  });
});
</script>
<script type="text/javascript">
 $(document).scroll(function() {
    $('#menu').toggle($(this).scrollTop()>1000)
 });​
 </script>
</body>
</html>
