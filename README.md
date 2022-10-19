# Testwebsite
<!-- CDP Web Insight script -->
<script type = "text/javascript" >
   var _portalId = "33167"; // Portal ANTSOMI Shopping 2 
   var _propId = "556301676"; // https://lequocdat0910.github.io/Testwebsite/home.html 
(function() {
    var w = window;
    if (w.web_event) return;
    var a = window.web_event = function() {
        a.queue.push(arguments);
    }
    a.propId = _propId;
    a.track = a;
    a.queue = [];
    var e = document.createElement("script");
    e.type = "text/javascript", e.async = !0, e.src = "//sandbox-st-a.cdp.asia/insight.js";
    var t = document.getElementsByTagName("script")[0];
    t.parentNode.insertBefore(e, t)
})(); </script>
<!-- End of CDP Web Insight script -->
