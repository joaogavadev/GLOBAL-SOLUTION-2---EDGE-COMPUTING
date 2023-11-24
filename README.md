<h2>João Gava - RM550595</h2>

<h1>VitaTrack monitoramento de temperatura com ESP32</h1>

<p>Este é um projeto de demonstração de sensor de temperatura e umidade utilizando o VitaTrack em um dispositivo ESP32. O dispositivo mede as condições ambientais e publica os dados em um servidor MQTT.</p>

<h2>Configuração Inicial</h2>

<ol>
    <li>Acesse o simulador Wokwi para este projeto: <a href="https://wokwi.com/projects/322577683855704658">Wokwi</a>.</li>
    <li>Execute o código no simulador clicando no botão "Run" no canto superior direito.</li>
    <li>Observe o terminal na parte inferior do simulador para visualizar as informações de conexão com o Wi-Fi e MQTT.</li>
</ol>

<h2>Funcionamento</h2>

<p>O dispositivo mede continuamente as condições de temperatura e umidade usando um sensor DHT22..</p>

<p>Se a temperatura medida for maior ou igual a 37.5°C, o sistema exibirá um alerta indicando que a temperatura está em uma área de perigo. A mensagem de alerta será impressa no terminal do simulador.</p>

<h2>Acesso às Informações</h2>

<ul>
    <li>As informações do sensor, incluindo temperatura e umidade, são exibidas no terminal do simulador Wokwi.</li>
    <li>Para visualizar os dados publicados, você pode usar um cliente MQTT como <a href="http://mqtt-explorer.com/">MQTT Explorer</a> e se conectar ao servidor MQTT <code>broker.mqttdashboard.com</code>. Inscreva-se no tópico "wokwi-weather" para receber as atualizações.</li>
</ul>
