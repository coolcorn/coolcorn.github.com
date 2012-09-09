---
layout: default
title: COOLidge CORNer
---
* [links](links)
* [devo](devo)

<script charset="utf-8" src="http://widgets.twimg.com/j/2/widget.js" type="text/javascript"></script>
<script type="text/javascript">
new TWTR.Widget({
  version: 2,
  type: 'profile',
  rpp: 30,
  interval: 30000,
  width: 250,
  height: 300,
  theme: {
    shell: {
      background: '#544e46',
      color: '#ffffff'
    },
    tweets: {
      //background: '#000000',
      //color: '#ffffff',
      //links: '#4aed05'
      background: '#ccbd9f',
      color: 'black',
      links: '#587aff'
    }
  },
  features: {
    scrollbar: false,
    loop: false,
    live: false,
    behavior: 'all'
  }
}).render().setUser('coolcorn').start();
</script>
