### Hi there 👋

<style>
  h1 {
    color: red;
    animation: myanimation 2s infinite;
  }
  
  @keyframes myanimation {
    from {
      color: red;
    }
    to {
      color: yellow;
    }
  }

  #test {
    border: 1px solid gray;
  }
</style>

<p>
  
  Test:
</p>

<h1>
  
  header
</h1>

<div id="test">
  <canvas id="myCanvas" width="200" height="100"></canvas>
</div>

<script>

var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.moveTo(0, 0);
ctx.lineTo(200, 100);
ctx.stroke();

</script>