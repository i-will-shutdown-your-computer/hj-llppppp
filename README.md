<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Close All Tabs</title>
<script>
function closeAllTabs() {
    window.open('', '_self', '');
    window.close();
}
</script>
</head>
<body>
<h1>Klik på knappen for at lukke alle faner</h1>
<button onclick="closeAllTabs()">Luk alle faner</button>
</body>
</html>
