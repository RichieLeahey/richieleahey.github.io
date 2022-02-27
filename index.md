<h2>About</h2>

<script type="text/javascript">

let pageView = 0;
let siteTitle = "RichieLeahey.com";
let pageTitle = 'All About Me';
let pageAuthor = 'Richie Leahey';


 function pageTitles() {

   document.write(pageTitle);
 }

 function pageAuthors() {
   document.write(pageAuthor);
 }

 function pageViews() {
   pageView++;
   document.write(pageView);
 }

 pageTitles();
 pageAuthors();
 pageViews();

 </script>


<h1 class="page-title"><script>pageTitles();</script></h1>
<p>by: <script>pageAuthors();</script></p>
<small><script>pageViews();</script></small>

<h2>Portfolio</h2>

<h2>Contact</h2>
