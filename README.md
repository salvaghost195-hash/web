# web
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guía Completa sobre Tipos de Calzado</title>
    <style>
        /* Base styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 40px;
            background-color: #427BF5;
            color: #444;
            line-height: 1.7;
        }

        /* Headings common styles */
        h1, h2, h3 {
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
            transition: all 0.3s ease;
        }
        h1 {
            color: #6a329f;
            text-align: center;
            font-size: 3em;
            margin-bottom: 40px;
            padding-bottom: 15px;
            border-bottom: 3px solid #6a329f;
            text-shadow: 2px 2px 8px rgba(106, 50, 159, 0.4); /* Sombra más pronunciada para glow */
            /* Animación para el H1 */
            animation: textReveal 2s forwards ease-in-out;
            overflow: hidden; /* Para que la animación de texto se vea bien */
            white-space: nowrap; /* Para que no se rompa el texto durante la animación */
        }
        h1:hover {
            color: #53287e;
            text-shadow: 0 0 15px rgba(106, 50, 159, 0.8), 0 0 25px rgba(106, 50, 159, 0.6); /* Glow más fuerte al pasar el ratón */
        }
        h2 {
            color: #1a0dab;
            font-size: 2.2em;
            margin-top: 50px;
            margin-bottom: 20px;
            border-bottom: 2px solid #1a0dab;
            padding-bottom: 10px;
            text-shadow: 1px 1px 5px rgba(26, 13, 171, 0.3); /* Sombra sutil para glow */
        }
        h2:hover {
            color: #0d065a;
            padding-left: 10px;
            text-shadow: 0 0 10px rgba(26, 13, 171, 0.7); /* Glow más fuerte al pasar el ratón */
        }
        h3 {
            color: #333;
            font-size: 1.7em;
            margin-top: 35px;
            margin-bottom: 15px;
            text-shadow: 0.5px 0.5px 1px rgba(0,0,0,0.05); /* Sombra muy sutil */
        }
        h3:hover {
            color: #000;
            text-shadow: 0.5px 0.5px 2px rgba(0,0,0,0.2); /* Sombra más notoria al pasar el ratón */
        }

        p {
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
            margin-bottom: 18px;
            letter-spacing: 0.02em;
        }

        .instructions {
            border-left: 6px solid #007bff;
            padding: 20px 30px;
            margin: 0 auto 40px auto;
            max-width: 800px;
            background-color: rgba(224, 242, 247, 0.8);
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
            transition: all 0.3s ease;
        }
        .instructions:hover {
            box-shadow: 0 6px 16px rgba(0, 0, 0, 0.2);
            transform: translateY(-2px);
        }
        .instructions p {
            margin: 0;
            max-width: none;
        }

        ul, ol {
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 45px;
            margin-bottom: 20px;
        }
        ul li, ol li {
            margin-bottom: 10px;
            transition: transform 0.2s ease, color 0.2s ease; /* Transición para efecto hover */
        }
        ul li:hover, ol li:hover {
            transform: translateX(5px); /* Pequeño desplazamiento al pasar el ratón */
            color: #6a329f; /* Cambio de color al pasar el ratón */
        }

        /* Index specific styles */
        .index {
            max-width: 800px;
            margin: 20px auto 50px auto;
            padding: 25px;
            background-color: #FED9FF;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.08);
        }
        .index h2 {
            text-align: center;
            color: #6a329f;
            border-bottom: 2px solid #6a329f;
            padding-bottom: 10px;
            margin-top: 0;
            margin-bottom: 20px;
        }
        .index ol {
            padding-left: 20px;
            list-style-type: decimal;
        }
        .index ol li {
            margin-bottom: 8px;
        }
        .index ol li a {
            color: #1a0dab;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.2s ease;
        }
        .index ol li a:hover {
            color: #6a329f;
            text-decoration: underline;
        }


        /* Image Containers */
        .image-container {
            text-align: center;
            margin: 30px auto;
            max-width: 700px;
            background-color: rgba(255, 255, 255, 0.7);
            border: 1px solid rgba(204, 204, 204, 0.6);
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.15);
            transition: all 0.4s ease;
        }
        .image-container:hover {
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.25);
            transform: translateY(-5px);
        }
        .image-container img {
            max-width: 95%;
            height: auto;
            display: block;
            margin: 0 auto;
            border: 1px solid #ddd;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
            max-height: 350px;
            object-fit: contain;
            border-radius: 5px;
            transition: all 0.4s ease;
            filter: grayscale(0%);
        }
        .image-container img:hover {
            transform: scale(1.02);
            border-color: #6a329f;
            box-shadow: 0 6px 18px rgba(0, 0, 0, 0.25);
            filter: grayscale(20%) brightness(1.1);
        }
        .image-caption {
            margin-top: 12px;
            font-size: 1em;
            color: #555;
            font-style: italic;
            text-shadow: 0.5px 0.5px 1px rgba(0,0,0,0.03);
        }

        /* Form Section */
        .form-section {
            margin: 60px auto;
            max-width: 950px;
            background-color: #fff;
            border: 1px solid #c9c9c9;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
            overflow: hidden;
            transition: all 0.3s ease;
        }
        .form-section:hover {
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.25);
        }
        .form-section h2 {
            background-color: #6a329f;
            color: white;
            text-align: center;
            margin-top: 0;
            padding: 15px;
            font-size: 1.8em;
            border-bottom: 2px solid #53287e;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }
        .form-content {
            padding: 25px;
        }
        .form-group {
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            flex-wrap: wrap;
        }
        .form-group label {
            flex: 0 0 200px;
            margin-right: 15px;
            font-weight: bold;
            color: #1a0dab;
            text-align: right;
            text-shadow: 0.5px 0.5px 1px rgba(0,0,0,0.03);
        }
        .form-group .input-field {
            flex: 1;
        }
        .form-group input[type="text"],
        .form-group textarea,
        .form-group select {
            width: calc(100% - 22px);
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1em;
            box-sizing: border-box;
            max-width: 500px;
            transition: border-color 0.3s ease, box-shadow 0.3s ease;
        }
        .form-group input[type="text"]:focus,
        .form-group textarea:focus,
        .form-group select:focus {
            border-color: #6a329f;
            box-shadow: 0 0 5px rgba(106, 50, 159, 0.5);
            outline: none;
        }
        .form-group textarea {
            min-height: 80px;
            resize: vertical;
        }
        .form-group .radio-group,
        .form-group .checkbox-group {
            flex: 1;
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }
        .form-group .radio-group label,
        .form-group .checkbox-group label {
            flex: unset;
            text-align: left;
            font-weight: normal;
            color: #444;
            margin-right: 0;
            transition: color 0.3s ease;
        }
        .form-group .radio-group label:hover,
        .form-group .checkbox-group label:hover {
            color: #1a0dab;
        }

        /* Image-based form options */
        .image-radio-option,
        .image-checkbox-option {
            display: flex;
            flex-direction: column;
            align-items: center;
            cursor: pointer;
            border: 2px solid transparent;
            border-radius: 8px;
            padding: 10px;
            transition: all 0.3s ease;
            text-align: center;
            flex: 1 1 calc(33% - 20px);
            box-sizing: border-box;
            max-width: 200px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        .image-radio-option:hover,
        .image-checkbox-option:hover {
            background-color: #f0e6fa;
            border-color: #b592b5;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        .image-radio-option input[type="radio"]:checked + .image-content,
        .image-checkbox-option input[type="checkbox"]:checked + .image-content {
            border: 3px solid #6a329f;
            box-shadow: 0 0 10px rgba(106, 50, 159, 0.7);
            background-color: #f0e6fa;
            transform: scale(1.02);
        }
        .image-radio-option input[type="radio"],
        .image-checkbox-option input[type="checkbox"] {
            display: none;
        }
        .image-radio-option .image-content,
        .image-checkbox-option .image-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 100%;
            height: 100%;
            border-radius: 8px;
            padding: 5px;
            box-sizing: border-box;
            transition: all 0.3s ease;
        }
        .image-radio-option img,
        .image-checkbox-option img {
            width: 100%;
            max-height: 100px;
            object-fit: contain;
            border-radius: 4px;
            margin-bottom: 8px;
            border: 1px solid #ddd;
            background-color: #fff;
            transition: all 0.3s ease;
        }
        .image-radio-option img:hover,
        .image-checkbox-option img:hover {
            filter: brightness(1.05);
        }
        .image-radio-option .image-label,
        .image-checkbox-option .image-label {
            font-weight: bold;
            color: #333;
            font-size: 0.9em;
            transition: color 0.3s ease;
        }
        .image-radio-option:hover .image-label,
        .image-checkbox-option:hover .image-label {
            color: #6a329f;
        }
        .form-group.visual-options {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding-top: 15px;
            border-top: 1px solid #eee;
            margin-top: 20px;
        }
        .form-group.visual-options label {
            flex: 1 1 100%;
            text-align: center;
            margin-right: 0;
            margin-bottom: 20px;
            font-size: 1.2em;
            color: #1a0dab;
        }
        .form-group .radio-group-images,
        .form-group .checkbox-group-images {
            flex: 1 1 100%;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }

        .form-group.full-width {
            display: block;
            margin-left: auto;
            margin-right: auto;
            max-width: 800px;
        }
        .form-group.full-width label {
            text-align: left;
            display: block;
            margin-bottom: 10px;
            flex: unset;
        }

        /* Buttons */
        .button-group {
            text-align: center;
            padding: 20px;
            background-color: #f0f0f0;
            border-top: 1px solid #e0e0e0;
            margin-top: 30px;
        }
        .button-group button {
            padding: 12px 25px;
            margin: 0 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.1em;
            font-weight: bold;
            transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.2s ease;
        }
        .button-group button[type="submit"] {
            background-color: #6a329f;
            color: white;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
        }
        .button-group button[type="reset"] {
            background-color: #dc3545;
            color: white;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
        }
        .button-group button[type="submit"]:hover {
            background-color: #53287e;
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            text-shadow: 0 0 5px rgba(255,255,255,0.8); /* Efecto de glow en texto del botón */
        }
        .button-group button[type="reset"]:hover {
            background-color: #c82333;
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            text-shadow: 0 0 5px rgba(255,255,255,0.8); /* Efecto de glow en texto del botón */
        }

        /* Emphasis classes with more effects */
        .amortiguacion, .soporte, .maxima-ventilacion {
            color: #007bff;
            font-weight: bold;
            text-shadow: 0.5px 0.5px 2px rgba(0, 123, 255, 0.4); /* Sombra sutil de color */
            transition: all 0.3s ease;
        }
        .amortiguacion:hover, .soporte:hover, .maxima-ventilacion:hover {
            text-shadow: 0 0 5px rgba(0, 123, 255, 0.8), 0 0 10px rgba(0, 123, 255, 0.6); /* Glow al pasar el ratón */
        }
        .excelencia, .amplia-variedad, .versatiles, .alta-calidad {
            font-style: italic;
            color: #7d3c98; /* Un color púrpura para los itálicos */
            text-shadow: 0.5px 0.5px 1px rgba(125, 60, 152, 0.3);
            transition: all 0.3s ease;
        }
        .excelencia:hover, .amplia-variedad:hover, .versatiles:hover, .alta-calidad:hover {
            color: #5b2c6f;
            text-shadow: 1px 1px 3px rgba(125, 60, 152, 0.7);
        }

        .puntos-innovacion, .sandalias-data {
            font-size: 0.9em;
            vertical-align: super;
            color: #d9534f; /* Rojo para destacar */
            font-weight: bold;
            text-shadow: 0.5px 0.5px 1px rgba(217, 83, 79, 0.5);
            animation: pulse 1.5s infinite alternate; /* Animación de pulsación */
        }
        @keyframes pulse {
            from { opacity: 0.7; transform: scale(1); }
            to { opacity: 1; transform: scale(1.05); }
        }

        .meticulosamente, .elevar-significativamente, .mayor-cobertura, .durabilidad, .ideal {
            font-weight: bold;
            color: #3e8e41; /* Verde para palabras clave */
            text-shadow: 1px 1px 2px rgba(62, 142, 65, 0.3); /* Sombra que da profundidad */
            transition: text-shadow 0.3s ease;
        }
        .meticulosamente:hover, .elevar-significativamente:hover, .mayor-cobertura:hover, .durabilidad:hover, .ideal:hover {
            text-shadow: 2px 2px 4px rgba(62, 142, 65, 0.6); /* Sombra más fuerte al pasar el ratón */
        }

        .descompense {
            font-style: italic;
            color: #d9534f; /* Rojo para advertencia */
            text-shadow: 0.5px 0.5px 1px rgba(217, 83, 79, 0.4);
        }

        /* Media Sections (Audio/Video) */
        .video-section, .audio-section {
            text-align: center;
            margin-top: 50px;
            padding: 30px;
            box-shadow: inset 0 5px 10px rgba(0,0,0,0.05);
        }
        .video-section {
            background-color: #f8f8f8;
            border-top: 2px solid #ddd;
        }
        .audio-section {
            background-color: #f0f8ff;
            border-top: 2px solid #b0e0e6;
            border-bottom: 2px solid #b0e0e6;
        }
        .video-section h2, .audio-section h2 {
            margin-bottom: 30px;
            border-bottom: none;
        }
        .video-section h2 { color: #6a329f; }
        .audio-section h2 { color: #1a0dab; }

        .video-container, .audio-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 0 auto;
        }
        .video-container { gap: 40px; max-width: 1000px; }
        .audio-container { gap: 30px; max-width: 800px; }

        .video-item, .audio-item {
            text-align: center;
            background-color: #fff;
            padding: 15px; /* Unified padding */
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1); /* Unified shadow */
            transition: all 0.3s ease;
        }
        .video-item {
            flex: 1 1 450px;
            max-width: 500px;
            padding: 20px; /* Specific padding for video item */
        }
        .audio-item {
            flex: 1 1 350px;
            max-width: 400px;
        }

        .video-item:hover, .audio-item:hover {
            box-shadow: 0 8px 18px rgba(0,0,0,0.2);
            transform: translateY(-5px);
        }
        .video-item marquee { /* Keep if user wants marquee, otherwise remove */
            margin-bottom: 15px;
            font-size: 1.5em;
            color: #1a0dab;
            font-weight: bold;
            text-shadow: 1px 1px 1px rgba(0,0,0,0.05);
        }
        .audio-item h3 {
            color: #6a329f;
            margin-top: 0;
            margin-bottom: 10px;
            font-size: 1.3em;
        }
        embed { /* General embed styling */
            display: block;
            margin: 0 auto;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.08);
        }
        .audio-item embed {
            width: 100%;
            max-width: 350px;
            height: 50px;
        }
        .video-item embed {
            width: 500px; /* Fixed width as per original code */
            height: 500px; /* Fixed height as per original code */
        }

        /* Keyframe Animations */
        @keyframes textReveal {
            from {
                width: 0;
                border-bottom: 3px solid transparent; /* Oculta el borde al inicio */
            }
            to {
                width: 100%;
                border-bottom: 3px solid #6a329f; /* Muestra el borde al final */
            }
        }
    </style>
</head>
<body>

<p>Nombre del Alimno: Ortiz Paz Juan Salvador.</p>
<p>Materia: Construye Paginas Web</p>
<p>Maestra: Ana Moreno </p>
<p>tema asignado: Tipo de calzado</p>

    <h1>Guía Completa sobre Tipos de Calzado</h1>

    <div class="index">
        <h2>Índice de Contenidos</h2>
        <ol>
            <li><a href="#tenis-section">Tenis</a></li>
            <li><a href="#zapatos-vestir-section">Zapatos de Vestir (Formales)</a></li>
            <li><a href="#sandalias-section">Sandalias</a></li>
            <li><a href="#botas-section">Botas</a></li>
            <li><a href="#chanclas-huaraches-section">Chanclas y Huaraches</a></li>
            <li><a href="#calzado-comun-section">El Tipo de Calzado Más Común: Los Tenis</a></li>
            <li><a href="#encuesta-section">Encuesta sobre Preferencias de Calzado</a></li>
            <li><a href="#audios-section">Audios Relacionados</a></li>
            <li><a href="#videos-section">Videos Relacionados</a></li>
        </ol>
    </div>

    <h2>Explorando el Mundo del Calzado Común</h2>
<h3 id="tenis-section">En esta pagina les daremos informacion sobre los 5 tipos de calsado mas comunes en el mundo aparte de la informacion 
      tambien les podremos una encuesta y ha su ves videos sobre los tipos de calzado, adicional tambien audios para que si quieren poner mientras navegan en nuestra pagina</h3>
    <div class="instructions">

    <h3 id="tenis-section">1. Tenis</h3>
    <p>Los tenis, también conocidos como <em>sneakers</em> o zapatillas deportivas, son el calzado por <span class="excelencia">excelencia</span> para la actividad física. Su diseño se centra en ofrecer <span class="amortiguacion">amortiguación</span> y <span class="soporte">soporte</span>, minimizando el impacto en las articulaciones durante el ejercicio. Sin embargo, su inigualable comodidad y su creciente influencia en la moda urbana los han relegado a ser un básico para el uso diario, trascendiendo las pistas y los gimnasios. Un ejemplo de su impacto es la evolución del diseño de los modelos iniciales para correr que han culminado en tecnologías de punta como el Flyknit de Nike, que a veces parece tener 2.0x10<span class="puntos-innovacion">2</span> puntos de innovación.</p>
    <ul>
        <li>**Usos comunes:** Deportes, caminatas, uso casual.</li>
        <li>**Materiales típicos:** Mallas transpirables, cuero sintético, suelas de goma.</li>
    </ul>
    <div class="image-container">
        <img src="tenis.png" alt="Tenis">
        <p class="image-caption">Ejemplo de Tenis</p>
    </div>

    <h3 id="zapatos-vestir-section">2. Zapatos de Vestir (Formales)</h3>
    <p>Estos zapatos están <span class="meticulosamente">meticulosamente</span> diseñados para ocasiones formales o ambientes profesionales. Tradicionalmente, se caracterizan por su elegancia y están confeccionados con materiales de <span class="alta-calidad">alta calidad</span>, siendo el cuero genuino el más común. La elección de un buen par de zapatos de vestir puede <span class="elevar-significativamente">elevar significativamente</span> la percepción de un atuendo. Es crucial que el calzado complemente el estilo general, no que lo <span class="descompense">descompense</span>.</p>
    <ul>
        <li>**Usos comunes:** Eventos formales (bodas, galas), trabajo de oficina, reuniones de negocios.</li>
        <li>**Estilos populares:**
            <ol>
                <li>Oxford: <span style="font-weight: bold;">Diseño clásico</span> y formal.</li>
                <li>Derby: Ligeramente menos formal, con cordones abiertos.</li>
                <li>Mocasines: Sin cordones, para un estilo elegante pero cómodo.</li>
                <li>Brogues: Con perforaciones decorativas.</li>
                <li>Botines de vestir: Aportan un toque moderno y sofisticado.</li>
            </ol>
        </li>
    </ul>
    <div class="image-container">
        <img src="zapatos.png" alt="Zapatos de Vestir">
        <p class="image-caption">Ejemplo de Zapatos de Vestir</p>
    </div>

    <h3 id="sandalias-section">3. Sandalias</h3>
    <p>Las sandalias son el calzado <span class="ideal">ideal</span> para climas cálidos, ya que su diseño abierto permite la <span class="maxima-ventilacion">máxima ventilación</span> del pie. Vienen en una <span class="amplia-variedad">amplia variedad</span> de estilos, desde las casuales chanclas de playa hasta modelos más elegantes con tacón, adecuadas para eventos de verano. Su versatilidad las convierte en un elemento indispensable en cualquier guardarropa de temporada cálida. La historia de las sandalias data de civilizaciones antiguas como la 3000 a.C.<span class="sandalias-data">1</span> en Egipto.</p>
    <ul>
        <li>**Usos comunes:** Playa, piscina, verano, uso casual, vacaciones.</li>
    </ul>
    <div class="image-container">
        <img src="sandalias.png" alt="Sandalias">
        <p class="image-caption">Ejemplo de Sandalias</p>
    </div>

    <h3 id="botas-section">4. Botas</h3>
    <p>Las botas ofrecen una <span class="mayor-cobertura">mayor cobertura</span>, cubriendo no solo el pie sino también parte de la pierna. Esta característica les confiere protección adicional contra los elementos y soporte. Son increíblemente <span class="versatiles">versátiles</span> y existen para una multitud de funciones, desde el trabajo pesado y la aventura al aire libre hasta elementos clave de la moda de invierno. Su <span class="durabilidad">durabilidad</span> es una de sus principales ventajas.</p>
    <ul>
        <li>**Usos comunes:** Invierno, trabajo, aventura, moda, senderismo, equitación.</li>
        <li>**Tipos populares:**
            <ul>
                <li>Botas de trabajo o industriales.</li>
                <li>Botines (cubren hasta el tobillo).</li>
                <li>Botas altas (cubren hasta la rodilla o más).</li>
                <li>Botas de lluvia o agua.</li>
                <li>Botas vaqueras.</li>
            </ul>
        </li>
    </ul>
    <div class="image-container">
        <img src="botas.png" alt="Botas">
        <p class="image-caption">Ejemplo de Botas</p>
    </div>

    <h3 id="chanclas-huaraches-section">5. Chanclas y Huaraches</h3>
    <p>Las chanclas (o "flip-flops" en inglés) y los huaraches son tipos de calzado abierto, ligeros y fáciles de poner, ideales para climas cálidos y ambientes informales. Las chanclas suelen tener una tira entre el dedo gordo y el segundo dedo, mientras que los huaraches pueden tener múltiples tiras que cubren más el pie, a menudo con diseños más elaborados y de materiales naturales como el cuero, especialmente populares en culturas latinas.</p>
    <ul>
        <li>**Usos comunes:** Playa, piscina, ducha, uso doméstico, paseos informales, verano.</li>
    </ul>
    <div class="image-container">
        <img src="huaraches.png" alt="Chanclas y Huaraches">
        <p class="image-caption">Ejemplo de Chanclas y Huaraches</p>
    </div>

    <h2 id="calzado-comun-section">El Tipo de Calzado Más Común: Los Tenis</h2>
    <p>Si bien la "comunalidad" puede variar por región y cultura, los <strong>tenis</strong> son, sin duda, el tipo de calzado más extendido y usado globalmente en la vida diaria. Su adopción masiva se debe a una combinación de factores clave:</p>
    <ul>
        <li><strong>Comodidad Inigualable:</strong> Diseñados originalmente para el deporte, ofrecen amortiguación y soporte que los hacen ideales para largas horas de pie o caminando.</li>
        <li><strong>Versatilidad:</strong> Han trascendido su propósito original para convertirse en un elemento básico para el uso casual, el trabajo (donde el código de vestimenta lo permite), viajes y actividades recreativas.</li>
        <li><strong>Influencia Cultural y de Moda:</strong> La cultura sneaker ha impulsado su popularidad, con lanzamientos de modelos limitados y colaboraciones que los mantienen relevantes y deseables.</li>
        <li><strong>Accesibilidad:</strong> Existen tenis en una amplia gama de precios, haciéndolos accesibles para casi todos los presupuestos.</li>
        <li><strong>Innovación Constante:</strong> Las marcas invierten continuamente en nuevas tecnologías para mejorar la comodidad, durabilidad y rendimiento, lo que mantiene el interés de los consumidores.</li>
    </ul>
    <p>Aunque otros tipos de calzado como las sandalias o los zapatos de vestir tienen su nicho, los tenis han logrado una penetración de mercado y una presencia en la vida cotidiana que los posiciona como el tipo de calzado más universal y común.</p>
    <div class="image-container">
        <img src="tenis.png" alt="Calzado Más Común">
        <p class="image-caption">Los tenis son el calzado más común en la actualidad.</p>
    </div>
</div class="instructions">

    <div class="form-section" id="encuesta-section" style="background-color: #FFC0CB;">
        <h2>Encuesta sobre Preferencias de Calzado</h2>
        <div class="form-content">
            <form action="#" method="post">
                <div class="form-group">
                    <label for="nombre">Nombre (opcional):</label>
                    <div class="input-field">
                        <input type="text" id="nombre" name="nombre" placeholder="Introduce tu nombre completo">
                    </div>
                </div>

                <div class="form-group visual-options">

                 <labe>¿Cuál es tu tipo de calzado favorito para uso diario?</labe>

                        <div class="radio-group-images">
                        <label class="image-radio-option">
                            <input type="radio" id="fav_tenis" name="favorito_diario" value="tenis">
                            <div class="image-content">
                                <img src="tenis.png" alt="Tenis">
                                <span class="image-label">Tenis</span>
                            </div>
                        </label>

                        <label class="image-radio-option">
                            <input type="radio" id="fav_vestir" name="favorito_diario" value="vestir">
                            <div class="image-content">
                                <img src="zapatos.png" alt="Zapatos de Vestir">
                                <span class="image-label">Zapatos de Vestir</span>
                            </div>
                        </label>

                        <label class="image-radio-option">
                            <input type="radio" id="fav_sandalias" name="favorito_diario" value="sandalias">
                            <div class="image-content">
                                <img src="sandalias.png" alt="Sandalias">
                                <span class="image-label">Sandalias</span>
                            </div>
                        </label>

                        <label class="image-radio-option">
                            <input type="radio" id="fav_botas" name="favorito_diario" value="botas">
                            <div class="image-content">
                                <img src="botas.png" alt="Botas">
                                <span class="image-label">Botas</span>
                            </div>
                        </label>

                        <label class="image-radio-option">
                            <input type="radio" id="fav_chanclas" name="favorito_diario" value="chanclas">
                            <div class="image-content">
                                <img src="huaraches.png" alt="Chanclas/Huaraches">
                                <span class="image-label">Chanclas/Huaraches</span>
                            </div>
                        </label>

                        <label class="image-radio-option">
                            <input type="radio" id="fav_otro" name="favorito_diario" value="otro">
                            <div class="image-content">
                                <img src="2000.jpg" alt="Otro Calzado">
                                <span class="image-label">Otro</span>
                            </div>
                        </label>
                    </div>
                </div>

                <div class="form-group">
                    <label>¿Qué factor consideras más importante al elegir calzado?</label>
                    <div class="radio-group">
                        <input type="radio" id="imp_comodidad" name="importancia_calzado" value="comodidad">
                        <label for="imp_comodidad">Comodidad</label>

                        <input type="radio" id="imp_estilo" name="importancia_calzado" value="estilo">
                        <label for="imp_estilo">Estilo/Diseño</label>

                        <input type="radio" id="imp_durabilidad" name="importancia_calzado" value="durabilidad">
                        <label for="imp_durabilidad">Durabilidad</label>

                        <input type="radio" id="imp_precio" name="importancia_calzado" value="precio">
                        <label for="imp_precio">Precio</label>

                        <input type="radio" id="imp_funcionalidad" name="importancia_calzado" value="funcionalidad">
                        <label for="imp_funcionalidad">Funcionalidad (para actividad específica)</label>
                    </div>
                </div>
                
                <div class="form-group">
                    <label for="tipo_calzado_mas_comprado">¿Qué tipo de calzado compras con más frecuencia?</label>
                    <div class="input-field">
                        <select id="tipo_calzado_mas_comprado" name="tipo_calzado_mas_comprado">
                            <option value="">Selecciona una opción</option>
                            <option value="tenis">Tenis</option>
                            <option value="vestir">Zapatos de Vestir</option>
                            <option value="sandalias">Sandalias</option>
                            <option value="botas">Botas</option>
                            <option value="chanclas">Chanclas/Huaraches</option>
                            <option value="otro">Otro</option>
                        </select>
                    </div>
                </div>

                <div class="form-group full-width">
                    <label for="comentarios">Comentarios o sugerencias adicionales:</label>
                    <textarea id="comentarios" name="comentarios" placeholder="Escribe tus comentarios aquí iiii..."></textarea>
                </div>

                <div class="button-group">
                    <button type="submit">Enviar Respuestas</button>
                    <button type="reset">Limpiar Formulario</button>
                </div>
            </form>
        </div>
    </div>

    
<div class="instructions">
    <div class="video-section" id="videos-section">
        <h2>Videos y Aduios Relacionados</h2>
        <div class="video-container">
            <div class="video-item">
                <marquee direction="left" scrollamount="10">¡Conoce más sobre la fabricación de calzado!</marquee>
                <embed src="nike.MP4" type="video/mp4" width="500" height="500">
            </div>
            <div class="video-item">
                <marquee direction="left" scrollamount="10">¡Las tendencias de calzado que vienen!</marquee>
                <embed src="Colección zapatos de futbol profesionales. @nike @adidasFootball y @PUMA.MP4" type="video/mp4" width="500" height="500">
</div class="video-section" id="videos-section"> 
<div class="audio-container">
            <div class="audio-item">
            </h3>
                <embed src="rally.mp3" type="audio/mpeg">
            </div>
            <div class="audio-item">
               
                <embed src="teni.mp3" type="audio/mpeg">
            </div>
        </div>
<a href="#top" class="back-to-top">Regresar al Principio de la Página</a>
            </div>
        </div>
    </div>
</body>
</html>
