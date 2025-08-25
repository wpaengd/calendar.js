<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Calendar JSON Output</title>
    <script src="dist/js-calendar-converter.js"></script>
</head>
<body>
<script>
    // 直接输出 calendar.solar2lunar() 的 JSON
    document.write(JSON.stringify(calendar.solar2lunar()));
</script>
</body>
</html>
