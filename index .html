<!DOCTYPE html>
<html lang="zh-TW">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>黃凱勇的房地產服務</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
        }

        .section {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
            padding: 20px;
        }

        h2 {
            color: #333;
            border-bottom: 1px solid #eee;
            padding-bottom: 10px;
            margin-bottom: 15px;
        }

        .property-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .property-card {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }

        .property-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .property-details {
            padding: 20px;
        }

        .property-details h3 {
            margin-top: 0;
        }

        input[type="text"],
        input[type="file"] {
            padding: 10px;
            margin: 5px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            margin: 5px;
        }

        button:hover {
            background-color: #0056b3;
        }

        .profile-picture {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 10px;
        }
    </style>
</head>

<body>
    <header>
        <h1>黃凱勇 - 中信房屋 大直加盟店</h1>
    </header>
    <div class="container">
        <div class="section">
            <h2>個人資料</h2>
            <img id="profile-image" class="profile-picture" src="https://dummyimage.com/200x200/000/fff" alt="個人照片">
            <button onclick="updateProfileImage()">更換照片</button>
            <ul>
                <li>姓名：黃凱勇</li>
                <li>從業年限：19年6個月</li>
                <li>就職公司：中信房屋 大直加盟店</li>
                <li>行動電話：0935-550-867</li>
                <li>服務區域：台北市中山區</li>
                <li>E-mail：kyle081899@gmail.com</li>
            </ul>
        </div>
        <div class="section">
            <h2>熟悉社區</h2>
            <ul>
                <li>忠泰風格</li>
                <li>輕井澤</li>
                <li>博物館</li>
            </ul>
        </div>
        <div class="section">
            <h2>業務特長</h2>
            <ul>
                <li>店面商辦</li>
                <li>電梯大樓</li>
                <li>中心商圈</li>
                <li>生活圈</li>
                <li>社區住宅</li>
            </ul>
        </div>
        <div class="section">
            <h2>新增售屋物件</h2>
            <input type="text" id="new-sale-name" placeholder="物件名稱">
            <input type="text" id="new-sale-price" placeholder="價格">
            <input type="text" id="new-sale-address" placeholder="地址">
            <input type="file" id="new-sale-image" accept="image/*">
            <button onclick="addSaleProperty()">新增</button>
        </div>
        <div class="section">
            <h2>售屋物件列表</h2>
            <div id="sale-properties" class="property-list">
                <div class="property-card">
                    <img src="https://dummyimage.com/600x400/000/fff" alt="售屋物件1">
                    <div class="property-details">
                        <h3>售屋物件1</h3>
                        <p>價格：500 萬</p>
                        <p>地址：台北市中山區某路某號</p>
                        <button onclick="updateSaleImage(this)">修改照片</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="section">
            <h2>新增租屋物件</h2>
            <input type="text" id="new-rent-name" placeholder="物件名稱">
            <input type="text" id="new-rent-price" placeholder="租金">
            <input type="text" id="new-rent-address" placeholder="地址">
            <input type="file" id="new-rent-image" accept="image/*">
            <button onclick="addRentProperty()">新增</button>
        </div>
        <div class="section">
            <h2>租屋物件列表</h2>
            <div id="rent-properties" class="property-list">
                <div class="property-card">
                    <img src="https://dummyimage.com/600x400/000/fff" alt="租屋物件1">
                    <div class="property-details">
                        <h3>租屋物件1</h3>
                        <p>租金：2 萬</p>
                        <p>地址：台北市中山區另某路某號</p>
                        <button onclick="updateRentImage(this)">修改照片</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <script>
        function addSaleProperty() {
            const name = document.getElementById('new-sale-name').value;
            const price = document.getElementById('new-sale-price').value;
            const address = document.getElementById('new-sale-address').value;
            const imageInput = document.getElementById('new-sale-image');
            const file = imageInput.files[0];
            if (name && price && address) {
                const container = document.getElementById('sale-properties');
                const card = document.createElement('div');
                card.className = 'property-card';
                if (file) {
                    const reader = new FileReader();
                    reader.onload = function (e) {
                        card.innerHTML = `
                            <img src="${e.target.result}" alt="${name}">
                            <div class="property-details">
                                <h3>${name}</h3>
                                <p>價格：${price}</p>
                                <p>地址：${address}</p>
                                <button onclick="updateSaleImage(this)">修改照片</button>
                            </div>
                        `;
                        container.appendChild(card);
                    };
                    reader.readAsDataURL(file);
                } else {
                    card.innerHTML = `
                        <img src="https://dummyimage.com/600x400/000/fff" alt="${name}">
                        <div class="property-details">
                            <h3>${name}</h3>
                            <p>價格：${price}</p>
                            <p>地址：${address}</p>
                            <button onclick="updateSaleImage(this)">修改照片</button>
                        </div>
                    `;
                    container.appendChild(card);
                }
                document.getElementById('new-sale-name').value = '';
                document.getElementById('new-sale-price').value = '';
                document.getElementById('new-sale-address').value = '';
                imageInput.value = '';
            }
        }

        function addRentProperty() {
            const name = document.getElementById('new-rent-name').value;
            const price = document.getElementById('new-rent-price').value;
            const address = document.getElementById('new-rent-address').value;
            const imageInput = document.getElementById('new-rent-image');
            const file = imageInput.files[0];
            if (name && price && address) {
                const container = document.getElementById('rent-properties');
                const card = document.createElement('div');
                card.className = 'property-card';
                if (file) {
                    const reader = new FileReader();
                    reader.onload = function (e) {
                        card.innerHTML = `
                            <img src="${e.target.result}" alt="${name}">
                            <div class="property-details">
                                <h3>${name}</h3>
                                <p>租金：${price}</p>
                                <p>地址：${address}</p>
                                <button onclick="updateRentImage(this)">修改照片</button>
                            </div>
                        `;
                        container.appendChild(card);
                    };
                    reader.readAsDataURL(file);
                } else {
                    card.innerHTML = `
                        <img src="https://dummyimage.com/600x400/000/fff" alt="${name}">
                        <div class="property-details">
                            <h3>${name}</h3>
                            <p>租金：${price}</p>
                            <p>地址：${address}</p>
                            <button onclick="updateRentImage(this)">修改照片</button>
                        </div>
                    `;
                    container.appendChild(card);
                }
                document.getElementById('new-rent-name').value = '';
                document.getElementById('new-rent-price').value = '';
                document.getElementById('new-rent-address').value = '';
                imageInput.value = '';
            }
        }

        function updateSaleImage(button) {
            const input = document.createElement('input');
            input.type = 'file';
            input.accept = 'image/*';
            input.onchange = function () {
                const file = this.files[0];
                if (file) {
                    const reader = new FileReader();
                    reader.onload = function (e) {
                        const img = button.parentNode.previousElementSibling;
                        img.src = e.target.result;
                    };
                    reader.readAsDataURL(file);
                }
            };
            input.click();
        }

        function updateRentImage(button) {
            const input = document.createElement('input');
            input.type = 'file';
            input.accept = 'image/*';
            input.onchange = function () {
                const file = this.files[0];
                if (file) {
                    const reader = new FileReader();
                    reader.onload = function (e) {
                        const img = button.parentNode.previousElementSibling;
                        img.src = e.target.result;
                    };
                    reader.readAsDataURL(file);
                }
            };
            input.click();
        }

        function updateProfileImage() {
            const input = document.createElement('input');
            input.type = 'file';
            input.accept = 'image/*';
            input.onchange = function () {
                const file = this.files[0];
                if (file) {
                    const reader = new FileReader();
                    reader.onload = function (e) {
                        const img = document.getElementById('profile-image');
                        img.src = e.target.result;
                    };
                    reader.readAsDataURL(file);
                }
            };
            input.click();
        }
    </script>
</body>

</html>    
