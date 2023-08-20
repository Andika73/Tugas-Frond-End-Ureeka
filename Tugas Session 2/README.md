<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Tugas.css">
    <title>Cita Rasa Indonesia</title>
</head>
<body>
    <header>
        <h1>Kuliner Indonesia</h1>
    </header>
    <div class="content">
        <div class="item">
            <img src="https://cdn0-production-images-kly.akamaized.net/fFUyKmdtLjQvF6-tvsZ0Li0Qiug=/1x112:1000x675/1200x675/filters:quality(75):strip_icc():format(jpeg)/kly-media-production/medias/3245094/original/043061400_1600750232-shutterstock_1786027046.jpg" alt="Rendang">
            <h2>Rendang</h2>
            <p>Makanan khas Minangkabau dari Sumatera Barat. Daging sapi dimasak dengan rempah-rempah hingga empuk dan berwarna coklat kehitaman.</p>
            <p>Asal: Sumatera Barat</p>
        </div>
        <div class="item">
            <img src="https://cdn-1.timesmedia.co.id/images/2022/12/21/gudeg-2.jpg" alt="Gudeg">
            <h2>Gudeg</h2>
            <p>Makanan khas Yogyakarta yang terbuat dari nangka muda yang dimasak dengan santan dan rempah-rempah, biasanya disajikan dengan nasi, ayam, krecek, dan telur.</p>
            <p>Asal: Yogyakarta</p>
        </div>
        <div class="item">
            <img src="https://cdn0-production-images-kly.akamaized.net/zX3tlUUWR1I-CfoDeHhMb7TZmy4=/1200x675/smart/filters:quality(75):strip_icc():format(jpeg)/kly-media-production/medias/1279284/original/029116500_1467357010-satujam.jpg" alt="Gado-gado">
            <h2>Gado-gado</h2>
            <p>Salad khas Indonesia yang terdiri dari sayuran rebus, tahu, tempe, dan lontong. Disajikan dengan bumbu kacang.</p>
            <p>Asal: Jawa Barat</p>
        </div>
    </div>
    <footer>
        <p>Cita Rasa Indonesia. Andika Ureeka.</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

header{
    background-color: black;
    color: white;
    text-align: center;
    padding: 0.3rem 0;
}

footer {
    background-color: #4a4848;
    color: white;
    text-align: center;
    padding: 0.1rem 0;
}

.content {
    display: grid;
    gap: 20px;
    padding: 25px;
    justify-items: center;
}

.item {
    background-color: white;
    border: 2px solid #ddd;
    padding: 20px;
    text-align: center;
}

.item img {
    max-width: 100%;
    height: auto;
}

@media only screen and (max-width: 676px){
    .content {
        grid-template-columns: 1fr;
    } 
}


@media only screen and (min-width: 1200px){
    .content {
        grid-template-columns: repeat(3, 1fr);
    }    
}
