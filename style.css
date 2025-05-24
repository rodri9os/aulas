body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #f0f0f0;
    margin: 0;
    overflow: hidden;
}

.container {
    background-color: #fff;
    border: 1px solid #ccc;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    text-align: center;
    width: 90%;
    max-width: 1200px;
}

h1 {
    color: #333;
    margin-bottom: 20px;
}

.controls {
    margin-bottom: 30px;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 15px;
    flex-wrap: wrap;
}

.controls label {
    font-weight: bold;
    color: #555;
}

.controls input[type="number"] {
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
    width: 80px;
    text-align: center;
}

.controls button {
    padding: 10px 20px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    transition: background-color 0.3s ease;
}

.controls button:hover {
    background-color: #0056b3;
}

.simulation-area {
    border: 2px solid #ff69b4; /* Cor rosa como no original */
    background-color: #ffe0f0; /* Fundo rosa claro */
    padding: 20px;
    border-radius: 8px;
    min-height: 300px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    position: relative;
}

.nodes {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 50px; /* Para dar espaço para o time elapsed */
}

.node {
    width: 150px;
    height: 120px;
    border: 4px solid #00008b; /* Azul escuro */
    background-color: #f0f8ff; /* Azul claro */
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border-radius: 8px;
    position: relative;
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
}

.node h3 {
    margin: 0;
    color: #333;
}

.node p {
    margin: 5px 0 0;
    font-size: 0.9em;
    color: #666;
}

.buffer-container {
    display: flex;
    margin-top: 10px;
    gap: 5px;
}

.buffer {
    width: 30px;
    height: 30px;
    border: 2px solid #8b4513; /* Marrom para buffers */
    background-color: #ffdead; /* Cor de pele */
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
    color: #333;
    border-radius: 4px;
    font-size: 0.8em;
}

.queue {
    position: absolute;
    top: -40px; /* Ajuste para posicionar acima dos buffers */
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    flex-direction: column;
    gap: 2px;
    min-height: 50px; /* Garante que a área da fila seja visível */
    align-items: center;
    /* border: 1px dashed #ccc; /* Para depuração */
    /* padding: 5px; */
}

.packet {
    width: 20px;
    height: 20px;
    background-color: #ffff00; /* Amarelo para pacotes */
    border: 1px solid #c8c800;
    border-radius: 3px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.7em;
    color: #333;
    animation: pulse 1s infinite alternate; /* Animação para pacotes */
    position: absolute; /* Para animação de movimento */
}

.fragment {
    width: 15px;
    height: 15px;
    background-color: #00ff00; /* Verde para fragmentos */
    border: 1px solid #00a000;
    border-radius: 2px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.6em;
    color: #333;
    animation: pulse 1s infinite alternate; /* Animação para fragmentos */
    position: absolute; /* Para animação de movimento */
}


@keyframes pulse {
    0% { transform: scale(1); }
    100% { transform: scale(1.05); }
}

.link {
    flex-grow: 1;
    height: 8px;
    background-color: #808080; /* Cinza para os cabos */
    position: relative;
    margin: 0 10px;
}

.link::before {
    content: attr(id);
    position: absolute;
    top: -20px;
    left: 50%;
    transform: translateX(-50%);
    font-weight: bold;
    color: #555;
}

.time-elapsed {
    position: absolute;
    top: 20px;
    left: 50%;
    transform: translateX(-50%);
    font-size: 1.2em;
    font-weight: bold;
    color: #333;
    background-color: #f8f8f8;
    padding: 8px 15px;
    border-radius: 5px;
    border: 1px solid #ddd;
}

#simulationTime {
    color: #d11212;
}

/* Specific buffer positioning for queues */
#queueA { top: -60px; left: 60%; } /* Above Source T buffer */
#queueB-R { top: -60px; left: 15%; }
#queueB-B { top: -60px; left: 50%; }
#queueB-T { top: -60px; left: 85%; }
#queueC-R { top: -60px; left: 15%; }
#queueC-B { top: -60px; left: 50%; }
#queueC-T { top: -60px; left: 85%; }
#queueD-R { top: -60px; left: 30%; }
#queueD-B { top: -60px; left: 70%; }