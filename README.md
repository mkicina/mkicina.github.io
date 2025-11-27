<!doctype html>
<html>
<head><meta charset="utf-8"><title>Enterprise token</title></head>
<body>
<h1>Enterprise token</h1>
<pre id="t">waiting...</pre>
<script>
  const p = new URLSearchParams(window.location.search);
  const token = p.get('enterpriseToken');
  document.getElementById('t').textContent = token || 'no token found';
  console.log('enterpriseToken=', token);
</script>
</body>
</html>
