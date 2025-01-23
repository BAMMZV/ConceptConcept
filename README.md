* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
}

header {
    display: flex;
    justify-content: space-between;
    padding: 20px;
    background-color: #333;
    color: white;
}

header .logo h1 {
    font-size: 24px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

section#home {
    background-color: #f7f7f7;
    text-align: center;
    padding: 50px 0;
}

.hero h2 {
    font-size: 36px;
}

.hero p {
    font-size: 18px;
    margin-bottom: 20px;
}

.hero button a {
    color: white;
    background-color: #007BFF;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

section#shop {
    padding: 50px;
    background-color: #fff;
    text-align: center;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.product-item {
    background-color: #f1f1f1;
    padding: 20px;
    border-radius: 8px;
}

.product-item img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}

.product-item h3 {
    margin: 10px 0;
}

.product-item p {
    font-size: 18px;
    margin: 5px 0;
}

.product-item button {
    background-color: #007BFF;
    color: white;
    border: none;
    padding: 10px;
    width: 100%;
    border-radius: 5px;
    cursor: pointer;
}

section#about, section#contact {
    padding: 50px;
    background-color: #f7f7f7;
    text-align: center;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: white;
}
