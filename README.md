<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LUC.FOOD - Pedidos Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background-color: #ff5733;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .menu-item {
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 10px;
            padding: 15px;
            background-color: white;
            width: 250px;
            text-align: center;
            box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
        }
        .menu-item h3 {
            color: #ff5733;
        }
        .menu-item button {
            background-color: #ff5733;
            color: white;
            border: none;
            padding: 10px 20px;
            margin-top: 10px;
            border-radius: 5px;
            cursor: pointer;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>LUC.FOOD</h1>
        <p>¡Delicias que te hacen feliz!</p>
    </header>

    <main>
        <section class="menu">
            <!-- Hamburguesa Clásica -->
            <div class="menu-item">
                <h3>Hamburguesa Clásica</h3>
                <p>Carne 100% res, queso, lechuga y tomate.</p>
                <p><strong>$12.000</strong></p>
                <button>Ordenar Ahora</button>
            </div>

            <!-- Hot Dog Clásico -->
            <div class="menu-item">
                <h3>Hot Dog Clásico</h3>
                <p>Salchicha premium, papas trituradas y queso.</p>
                <p><strong>$8.000</strong></p>
                <button>Ordenar Ahora</button>
            </div>

            <!-- Combo Familiar -->
            <div class="menu-item">
                <h3>Combo Familiar</h3>
                <p>2 hamburguesas clásicas + papas grandes + 2 gaseosas.</p>
                <p><strong>$25.000</strong></p>
                <button>Ordenar Ahora</button>
            </div>

            <!-- Bebidas -->
            <div class="menu-item">
                <h3>Malteada</h3>
                <p>Sabores: Fresa, chocolate, vainilla.</p>
                <p><strong>$6.000</strong></p>
                <button>Ordenar Ahora</button>
            </div>
        </section>
    </main>

    <footer>
        <p>📍 Dirección: [Tu ubicación] | 📱 WhatsApp: [Tu número]</p>
        <p>© 2024 LUC.FOOD - Todos los derechos reservados</p>
    </footer>
</body>
</html>

