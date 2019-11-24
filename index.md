<html>
  <head>
    <style type="text/css">
    #container {
    height: 100%;
    width: 100%;
    margin: auto;
    }
    </style>
  </head>
  <body>
    <div id="container"></div>
    <script src="sigma.min.js"></script>
    <script src="sigma.parsers.json.min.js"></script>
    <script src="sigma.renderers.edgeLabels.min.js"></script>
    <script>
    sigma.parsers.json('data2.json', {
    container: 'container',
    renderer: {
        container: "container",
        type: "canvas"
    },
    settings: {
    }
    });
    </script>
  </body>
</html>
