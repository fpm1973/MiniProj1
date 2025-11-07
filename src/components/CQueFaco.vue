<template>
<div class="info">
        <h1>👋 Apresentação Pessoal</h1>
        <h2>Fernando Monteiro</h2>
        
   
        <h3 class="section-title">💻 Percurso Profissional e Académico</h3>
        
        <ul class="career-list">
            <li><strong>Formação:</strong> Licenciatura em Informática</li>
            <li><strong>Cargo:</strong> Web Developer e PL/SQL Oracle</li>
            <li><strong>Local de Trabalho:</strong> Empresa em Paris, França 🇫🇷</li>
            <li><strong>Experiência:</strong> Na empresa atual desde 2014</li>
        </ul>

        <p>Um Amarantino com formação em Informática e mais de uma década de experiência a trabalhar em Paris como **Web Developer** e especialista em **PL/SQL Oracle**.</p>
    </div>
</template>    

<style scoped>
.info {
            background-color: #ffffff;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            width: 90%;
            max-width: 650px; /* Aumentado ligeiramente para acomodar o texto */
            text-align: center;
        }
        h1 {
            color: #2c3e50;
            font-size: 2.5em;
            margin-bottom: 10px;
            border-bottom: 3px solid #3498db;
            padding-bottom: 10px;
            display: inline-block;
        }
        h2 {
            color: #3498db;
            font-size: 1.5em;
            margin-top: 0;
        }
        .info-list, .career-list {
            list-style: none;
            padding: 0;
            text-align: left;
            margin: 30px 0;
        }
        .info-list li, .career-list li {
            background: #ecf0f1;
            margin-bottom: 10px;
            padding: 15px;
            border-left: 5px solid #3498db;
            border-radius: 5px;
            font-size: 1.1em;
            transition: background-color 0.3s;
        }
        .info-list li:hover, .career-list li:hover {
            background-color: #dbe4e6;
        }
        .info-list strong, .career-list strong {
            color: #2c3e50;
            min-width: 120px;
            display: inline-block;
        }
        .section-title {
            color: #2c3e50;
            margin-top: 30px;
            margin-bottom: 15px;
            font-size: 1.3em;
            border-bottom: 1px dashed #3498db;
            padding-bottom: 5px;
        }
</style>
