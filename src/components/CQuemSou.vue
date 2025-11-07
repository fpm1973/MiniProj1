<template>
<div class="info">
        <h1>👋 Apresentação Pessoal</h1>
        <h2>Fernando Monteiro</h2>
        
        <ul class="info-list">
            <li><strong>Idade:</strong> 52 anos</li>
            <li><strong>Naturalidade:</strong> Amarante, Portugal 🇵🇹</li>
            <li><strong>Local de Trabalho:</strong> França 🇫🇷</li>
            <li><strong>Estado Civil:</strong> Casado</li>
            <li><strong>Família:</strong> Pai de Duas Filhas</li>
        </ul>

        <p>Um Amarantino a trabalhar em França, dedicado à família e à vida profissional.</p>
    </div>
</template>    


<style scoped>
.info {
            background-color: #ffffff;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            width: 90%;
            max-width: 600px;
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
        .info-list {
            list-style: none;
            padding: 0;
            text-align: left;
            margin: 30px 0;
        }
        .info-list li {
            background: #ecf0f1;
            margin-bottom: 10px;
            padding: 15px;
            border-left: 5px solid #3498db;
            border-radius: 5px;
            font-size: 1.1em;
            transition: background-color 0.3s;
        }
        .info-list li:hover {
            background-color: #dbe4e6;
        }
        .info-list strong {
            color: #2c3e50;
            min-width: 120px;
            display: inline-block;
        }
</style>