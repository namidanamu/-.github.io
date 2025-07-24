<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Галерея фото</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            margin-bottom: 20px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            transition: transform 0.3s ease;
            cursor: pointer;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>

    <h1>Моя фотогалерея</h1>
    <div class="gallery">
        <img src="https://picsum.photos/id/1015/400/300" alt="Фото 1" />
        <img src="https://picsum.photos/id/1016/400/300" alt="Фото 2" />
        <img src="https://picsum.photos/id/1018/400/300" alt="Фото 3" />
        <img src="https://picsum.photos/id/1020/400/300" alt="Фото 4" />
        <img src="https://picsum.photos/id/1024/400/300" alt="Фото 5" />
        <img src="https://picsum.photos/id/1027/400/300" alt="Фото 6" />
    </div>

</body>
</html>
