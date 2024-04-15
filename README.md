<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Halaman E-commerce Sederhana</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif; 
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #add8e6; 
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: inline-block;
            margin-top: 20px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            text-align: center;
        }
        .product {
            display: inline-block;
            margin: 20px;
            border: 1px solid #ccc;
            padding: 10px;
            border-radius: 5px;
        }
        footer {
            background-color: #add8e6;
            color: #fff;
            text-align: center;
            padding: 1px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        input[type="file"] {
            display: none;
        }
        .custom-file-upload {
            border: 1px solid #ccc;
            display: inline-block;
            padding: 6px 12px;
            cursor: pointer;
            background-color: #f0f0f0;
        }
    </style>
</head>
<body>
    <header>
        <h1 style="font-family: 'Comic Sans MS', cursive;">Halaman E-commerce Sederhana</h1>
        <nav>
            <a href="#">Beranda</a>
            <a href="#">Produk</a>
            <a href="#">Keranjang</a>
            <a href="#">Kontak</a>
        </nav>
    </header>
        <h2 style="font-size: 1.2em;" class="text-center text-dark fw-bold p-4">ORDER NOW</p>
    </div>


<!-- catalog -->
        <h3 class="text-center" id="ProdukKami">Produk Kami</h3>
    <div class="text-center w-50 mx-auto fw-light">Dessert merupakan salah satu jenis makanan yang biasanya dihidangkan di akhir setelah hidangan utama atau sering disebut atau dikenal sebagai makanan pencuci mulut yang lucu dan juga manis </div>
<ul class="row row-cols-md-3 gx-5 p-5">
    <div class="container">
        <div class="product">
            <input type="file" id="file1">
            <img src="image7.jpg" alt="Taiyaki" id="img1">
            <h2>Taiyaki</h2>
            <p>Harga: Rp. 10.000</p>
            <button>Beli</button>
        </div>
        <div class="product">
            <input type="file" id="file2">
            <img src="image2.jpg" alt="Cocoa Tiramisu" id="img2">
            <h2>Cocoa Tiramisu</h2>
            <p>Harga: Rp.23.000</p>
            <button>Beli</button>
        </div>
        <div class="product">
            <input type="file" id="file3">
            <img src="image3.jpg" alt="Gelato Fruity" id="img3">
            <h2>Gelato Fruity</h2>
            <p>Harga: Rp. 35.000</p>
            <button>Beli</button>
        </div>
        <div class="product">
            <input type="file" id="file4">
            <img src="image4.jpg" alt="Cheese Grape Cake" id="img4">
            <h2>Cheese Grape Cake</h2>
            <p>Harga: Rp. 35.000</p>
            <button>Beli</button>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Riskia Salma Aulia. </p>
    </footer>
</body>
</html>
