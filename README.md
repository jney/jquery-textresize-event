A jquery event handler based on Christian Heilmann and Lawrence Carvalho article @ http://www.alistapart.com/articles/fontresizing

Example :

<code>
  $('body').bind('textresize', function () {
    console.log('text resized !');
  });
</code>