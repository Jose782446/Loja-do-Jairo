# Loja-do-Jairo
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Loja do Jairo - Eletrônicos</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <header>
        <h1>Loja do Jairo</h1>
        <p>Eletrônicos de Qualidade, Tecnologia de Ponta</p>
    </header>

    <section class="products">
        <div class="product">
            <img src="iphone.jpg" alt="iPhone 15 Pro Max" />
            <h2>iPhone 15 Pro Max</h2>
            <p>R$ 9.999,00</p>
            <button>Comprar Agora</button>
        </div>
        <div class="product">
            <img src="macbook.jpg" alt="MacBook Pro M3" />
            <h2>MacBook Pro M3</h2>
            <p>R$ 14.999,00</p>
            <button>Comprar Agora</button>
        </div>
        <div class="product">
            <img src="tv.jpg" alt="Smart TV LG OLED 55" />
            <h2>Smart TV LG OLED 55"</h2>
            <p>R$ 6.499,00</p>
            <button>Comprar Agora</button>
        </div>
        <div class="product">
            <img src="jbl.jpg" alt="Fone de Ouvido Bluetooth JBL" />
            <h2>Fone de Ouvido Bluetooth JBL</h2>
            <p>R$ 499,00</p>
            <button>Comprar Agora</button>
        </div>
    </section>

    <footer>
        <div class="payment-methods">
            <img src="credit-card.png" alt="Cartão de Crédito" />
            <img src="paypal.png" alt="PayPal" />
            <img src="pix.png" alt="Pix" />
        </div>
        <p>&copy; 2025 Loja do Jairo. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
/* Estilo Geral */
body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    color: #333;
    margin: 0;
    padding: 0;
}

header {
    background-color: #111;
    color: #fff;
    padding: 20px;
    text-align: center;
}

h1 {
    font-size: 2.5rem;
    margin: 0;
}

p {
    font-size: 1.2rem;
    margin-top: 10px;
}

/* Produtos */
.products {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    padding: 20px;
}

.product {
    background-color: #fff;
    border: 1px solid #ddd;
    padding: 20px;
    text-align: center;
    border-radius: 8px;
    transition: transform 0.2s ease-in-out;
}

.product img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.product h2 {
    font-size: 1.5rem;
    margin: 10px 0;
}

.product p {
    font-size: 1.2rem;
    color: #555;
}

.product button {
    background-color: #111;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 10px;
    font-size: 1rem;
    transition: background-color 0.3s ease;
}

.product button:hover {
    background-color: #333;
}

.product:hover {
    transform: translateY(-5px);
}

/* Rodapé */
footer {
    background-color: #111;
    color: #fff;
    text-align: center;
    padding: 20px;
    margin-top: 20px;
}

.payment-methods img {
    width: 40px;
    margin: 0 10px;
    vertical-align: middle;
}

footer p {
    margin-top: 10px;
    font-size: 1rem;
}