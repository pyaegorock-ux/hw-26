# hw-26
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Design to Code Example</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
</head>
<body>

<div class="content-wrapper">
    <div class="image-container">
        <img src="https://via.placeholder.com/450x240" alt="Sample View" class="main-image">
        <button id="infoBtn" class="spec-button">查看資訊</button>
    </div>

    <div id="infoPanel" class="info-panel hidden">
        <p><strong>修改日期:</strong> 2017/10/12</p>
        <p><strong>類型:</strong> JPG</p>
        <p><strong>大小:</strong> 466.97KB</p>
        <p><strong>路徑:</strong> /vdesigncenter.qnap.com/tw/DesignCenter/...</p>
    </div>
</div>

<script>
    const btn = document.getElementById('infoBtn');
    const panel = document.getElementById('infoPanel');

    btn.addEventListener('click', () => {
        panel.classList.toggle('hidden');
    });
</script>

</body>
</html>
