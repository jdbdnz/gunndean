---
layout: default
container: rsvp
---
<iframe
id="google-rsvp-form"
src="https://docs.google.com/forms/d/e/1FAIpQLSemwC_aTclEuFZZa9y4LaM9YvdwOe24-Une51ma6Z5ig_XsXQ/viewform?embedded=true"
frameborder="0" marginheight="0" marginwidth="0"
onload="resizeIframe(this)">
Loading...</iframe>

<script>
  function resizeIframe() {
    var obj = document.getElementById('google-rsvp-form');
    var container = document.getElementById('max-size-container');
    obj.style.height = container.scrollHeight + 'px';
    obj.style.width = container.scrollWidth + 'px';
  }

  document.onload = resizeIframe();
  document.onresize = resizeIframe();
</script>
