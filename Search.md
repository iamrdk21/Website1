---
layout: page
title: "Search"
subtitle: 
css: /css/Search.css
---
<div id="google-custom-search">
<script>
  (function() {
    var cx = '006356838477834478456:wlqkkiamvtm';
    var gcse = document.createElement('script');
    gcse.type = 'text/javascript';
    gcse.async = true;
    gcse.src = 'https://cse.google.com/cse.js?cx=' + cx;
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(gcse, s);
  })();
</script>
<gcse:searchbox></gcse:searchbox>
<gcse:searchresults></gcse:searchresults>
</div>

<!--
<div id="google-custom-search">
<script>
  (function() {
    var cx = '006356838477834478456:wlqkkiamvtm';
    var gcse = document.createElement('script');
    gcse.type = 'text/javascript';
    gcse.async = true;
    gcse.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') +
        '//www.google.com/cse/cse.js?cx=' + cx;
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(gcse, s);
  })();
</script>
<gcse:searchbox></gcse:searchbox>
<gcse:searchresults></gcse:searchresults>
</div>
-->
<!-- 
<gcse:searchresults></gcse:searchresults>
(document.location.protocol == 'https:' ? 'https:' : 'http:') +
        '//www.google.com/cse/cse.js?cx=' + cx;
'https://cse.google.com/cse.js?cx=' + cx;
-->
