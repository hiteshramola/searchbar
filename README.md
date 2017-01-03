# searchbar

A simple jquery search bar. Just add single div css and js and you are good to go
credits goes to Mary Lou for creating such a beautiful element here's the link - https://tympanus.net/codrops/2014/11/04/simple-morphing-search/.

I've just tweaked it a bit for a simpler use as I was facing problems with using it on both mobile and desktop menu.
So, I made a simple plugin out of it.
ENJOY!!

Here's how to use:

--> add script
<script src="https://cdnjs.cloudflare.com/ajax/libs/foundation/6.3.0/js/foundation.min.js"></script> <!-- For Foundation js -->
<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.0.0/jquery.min.js"></script>  <!-- Jquery js -->
<script src="search.min.js"></script>

--> add CSS
<link rel="stylesheet" href="search.css" />
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/foundation/6.3.0/css/foundation.css"/> <!-- For Foundation css -->

--> add this div in body or any section/element
<div class="searchbox"></div>

--> initialise the search
 <script>
         //SEARCH BAR INITIALISE
        jQuery(document).ready(function($){init_search();});
</script>
