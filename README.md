<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mateken2</title>
    <style>
        body { 
            font-family: 'Segoe UI', sans-serif; 
            background-color: #f4f4f9; 
            margin: 0; 
            padding: 20px 10px; 
        }
        .card { 
            max-width: 800px; 
            margin: auto; 
            background: white; 
            padding: 25px; 
            border-radius: 20px; 
            box-shadow: 0 4px 15px rgba(0,0,0,0.1); 
        }
        .header-content { 
            display: flex; 
            flex-wrap: wrap; 
            align-items: center; 
            justify-content: center; /* Centra el contenido superior */
            gap: 20px; 
        }
        .text-side { 
            flex: 1; 
            min-width: 280px; 
        }
        .fila-grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); 
            gap: 15px; 
            margin-top: 20px; 
        }
        .item-lista { 
            padding: 15px; 
            text-align: center; 
            border: 2px solid #f0f0f0; 
            border-radius: 15px; 
            background: #FAFAFA;
        }
        h1 { 
            color: #1565C0; 
            font-size: 1.8rem; 
            margin: 0 0 10px 0; 
            text-align: center; /* Centra el título principal */
        }
        h2 { 
            color: #FF9800; 
            text-align: center; 
            font-size: 1.4rem; 
        }
        .text-blue { color: #1565C0; font-weight: bold; }
        .text-orange { color: #FF9800; font-weight: bold; }
        .text-green { color: #4CAF50; font-weight: bold; }
    </style>
</head>
<body>

<div class="card">
    <div class="header-content">
        <div class="text-side">
            <h1>🏠 Mate <span class="text-orange">Digital</span> Ken2</h1>
            <div style="border-left: 5px solid #1565C0; padding-left: 15px; margin: 15px 0;">
                <h3 style="color: #1565C0; margin: 0;">🌐 Innovación Educativa</h3>
                <p style="font-size: 15px; line-height: 1.5; color: #555; font-style: italic;">
                    "Migramos de la teoría abstracta hacia <span class="text-blue">entornos digitales de alto impacto</span>, donde los estudiantes desarrollan competencias clave para un futuro tecnológico."
                </p>
            </div>
        </div>
    </div> <!-- Cierre correcto de header-content -->

    <hr style="margin: 25px 0; border: none; border-top: 2px solid #EEE;">

    <h2>🚀 Características Principales</h2>
    <div class="fila-grid">
        <div class="item-lista">
            <div style="font-size: 30px;">📚</div>
            <h3 style="color: #1565C0; margin: 5px 0;">Currículo</h3>
            <p style="font-size: 0.9rem;">Actividades basadas en <span class="text-blue">operaciones fundamentales</span>.</p>
        </div>
        <div class="item-lista">
            <div style="font-size: 30px;">🎯</div>
            <h3 style="color: #FF9800; margin: 5px 0;">Adaptativo</h3>
            <p style="font-size: 0.9rem;">Avanza al <span class="text-orange">ritmo único</span> del estudiante.</p>
        </div>
        <div class="item-lista">
            <div style="font-size: 30px;">🔒</div>
            <h3 style="color: #4CAF50; margin: 5px 0;">Seguridad</h3>
            <p style="font-size: 0.9rem;">Entorno <span class="text-green">100% libre</span> de publicidad.</p>
        </div>
    </div>

    <h2 style="margin-top: 30px;">🎮 Gamificación y Contexto</h2>
    <div style="background: #FFF3E0; border-radius: 15px; padding: 15px; text-align: center; border: 1px solid #FFE0B2;">
        <p style="line-height: 1.6; color: #333; margin: 0;">
            Los estudiantes pasan a ser <span class="text-blue">arquitectos de soluciones</span>, aplicando lógica y razonamiento para resolver retos del mundo real.
        </p>
    </div>

    <div style="margin-top: 25px; background: linear-gradient(90deg,#1565C0,#4CAF50); color: white; padding: 15px; border-radius: 12px; text-align: center; font-weight: bold; font-size: 1.1rem;">
        🎓 Aprendizaje educativo disfrazado de diversión pura
    </div>
</div> <!-- Cierre correcto de card -->

</body>
</html>
