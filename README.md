<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Wasseda - Fabricadora de Equipamentos para Avicultura</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 15px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: #333;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact-info, .payment-section {
            margin-top: 20px;
        }
        .contact-info p, .payment-section p {
            font-size: 1.1em;
        }
        .product-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .product-item {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .product-item h3 {
            margin-top: 0;
        }
        .product-item p {
            font-size: 1.1em;
        }
        .product-item button {
            background-color: #2ba347;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
        .product-item button:hover {
            background-color: #218838;
        }
        .payment-options {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        .payment-option {
            border: 1px solid #ccc;
            padding: 20px;
            border-radius: 8px;
            width: 150px;
            text-align: center;
            transition: transform 0.3s;
        }
        .payment-option:hover {
            transform: scale(1.1);
            cursor: pointer;
        }
        .payment-option img {
            width: 80px;
            height: auto;
        }
    </style>
</head>
<body>

    <header>
        <h1>Wasseda</h1>
        <p>Fabricadora de Equipamentos para Avicultura</p>
    </header>

    <nav>
        <a href="#">Início</a>
        <a href="#">Sobre Nós</a>
        <a href="#">Serviços</a>
        <a href="#">Contato</a>
    </nav>

    <section>
        <h2>Bem-vindo à Wasseda</h2>
        <p>A Wasseda é uma empresa especializada na fabricação de equipamentos para avicultura. Nossa missão é fornecer soluções inovadoras e de alta qualidade para atender às necessidades do setor avícola, proporcionando maior eficiência e resultados para nossos clientes.</p>

        <div class="contact-info">
            <h3>Informações de Contato</h3>
            <p><strong>CNPJ:</strong> 53.521.449/0001-51</p>
            <p><strong>Endereço:</strong>  Av. Ver. José Gomes Duda, 860 - Pacaembu - São Paulo</p>
            <h4>Telefones:</h4>
            <p><strong>Jumberto:</strong> (18) 99753-4359</p>
            <p><strong>Osvino:</strong> (18) 99765-3955</p>
            <p><strong>Nelson:</strong> (18) 99712-9256</p>
        </div>

        <!-- Seção de Produtos -->
        <h2>Produtos para Compra</h2>
        <div class="product-list">
            <div class="product-item">
                <h3>100x45x40 Gaiola de Postura 2 Divisão MTS</h3>
                <p>Preço: R$ 100,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>100x50x40 Gaiola de Postura 2 Divisão MTS</h3>
                <p>Preço: R$ 104,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>100x50x50 Gaiola de Recria 2 Divisão MTS</h3>
                <p>Preço: R$ 110,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>100x60x35 Gaiola de Cria 2 Divisão MTS</h3>
                <p>Preço: R$ 132,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>100x80x35 Gaiola de Cria 2 Divisão MTS</h3>
                <p>Preço: R$ 150,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>100x38x17 Gaiola de Codorna 3 Divisão MTS</h3>
                <p>Preço: R$ 92,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>45-C Piso Postura UNID</h3>
                <p>Preço: R$ 40,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>45-E Piso Postura UNID</h3>
                <p>Preço: R$ 40,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>50-C Piso Postura UNID</h3>
                <p>Preço: R$ 45,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>50-E Piso Postura UNID</h3>
                <p>Preço: R$ 47,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>100x50 Piso Recria UNID</h3>
                <p>Preço: R$ 40,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>100x60 Piso Cria UNID</h3>
                <p>Preço: R$ 50,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>Emenda de Piso 23 cm UNID</h3>
                <p>Preço: R$ 22,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>330mm Cocho para Postura Galvalume Barra de 3 mts MTS</h3>
                <p>Preço: R$ 41,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>300mm Cocho para Recria Galvalume Barra de 3 mts MTS</h3>
                <p>Preço: R$ 37,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>250mm Cocho Cria Galvalume Barra de 3 mts MTS</h3>
                <p>Preço: R$ 32,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>200mm Cocho para Codorna Galvalume Barra de 3 mts MTS</h3>
                <p>Preço: R$ 29,00</p>
                <button>Comprar</button>
            </div>
            <div class="product-item">
                <h3>Tratador Automático Completo Sem Trilho de 6 Linhas UNID</h3>
                <p>Preço: R$ 25.000,00</p>
                <button>Comprar</button>
            </div>
            <!-- Continue com os outros produtos seguindo o mesmo padrão -->
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Wasseda - Todos os direitos reservados.</p>
    </footer>

</body>
</html>

