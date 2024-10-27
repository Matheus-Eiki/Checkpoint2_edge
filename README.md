<h1 align="center">Projeto Edge- Vinheria</h1>
<h2 align=”center”>
Projeto finalizado
</h2>
<hr></hr>

<h1>📘Sobre o que é o Projeto?</h1>
<p>Este projeto teve como base, o Checkpoint 2 dos alunos de Edge Computing & Computer Systems da Engenharia de Software da FIAP(Faculdade de Informática e Administração Paulista). O objetivo era criar um sensor de luz que alertasse sobre fatores que influenciam a qualidade do vinho, atendendo a uma solicitação de uma vinícola, que foi feito durante o nosso primeiro Checkpoint. Agora além de utilizar o sensor de luz e o buzzer, temos que utilizar umas novas peças, como por exemplo o LCD, o DHT11 e o RTC, sendo o DHT11 utilizado para trazer a temperatura e umidade do ambiente para um maior controle. Além disso o RTC nos mostra o dia e horário, enquanto o LCD nos trás estas informações por meio do mesmo.</p>
<p>A finalidade principal continua sendo proteger os vinhos da vinícola, evitando exposições excessivas à luz, a umidade e a temperatura, que podem causar degradação nos produtos.</p>
<p>O projeto consiste em um sistema de monitoramento de não apenas luminosidade mas desta vez, também contando com o controle de temperatura e umidade do local. E com esse controle podemos alertar a possíveis desastres, quanto aos objetos que devemos proteger, que no caso desse projeto seria os vinhos. Além disso ao termos uma indicação não apenas visual(leds e LCD), mas também algo sonoro(buzzer) podemos ter um sistema melhor no quesito de percepção aos dados.</p>
<hr></hr>
<h1>Funcionalidades do Projeto</h1>
<h2>1. Leitura de Luz</h2>
<ul>
  <ul>
    <li>O projeto capta a luz ambiental e mede sua intensidade.</li>
    <li>Os dados coletados são enviados para um Arduino, que processa as informações.</li>
  </ul>
</ul>
<h2>2. Umidade e temperatura</h2>
<ul>
  <li>O projeto capta a quantidade de umidade e temperatura no ambiente, medindo suas respectivas quantidades.</li>
  <li>Os dados coletados são enviados e armazenados dentro do RTC</li>
</ul>
<h2>3.RTC</h2>
<ul>
  <li>O RTC armazena dados, como por exemplo a temperatura e umidade além da data e hora.</li>
</ul>
<h2>2. Indicação Visual</h2>
<ul>
  <div>Com base na intensidade da luz detectada, um LED é aceso, indicando diferentes níveis de alerta:</div>
  <ul>
    <li>Vermelho: Nível de luz muito elevado (alerta crítico).</li>
    <li>Amarelo: Nível de luz moderado (alerta).</li>
    <li>Verde: Nível de luz normal (sem problemas).</li>
    <li>LCD: Apresenta os dados recebidos pelos sensores, nos mostrando exatamente as medidas de cada um</li>
  </ul>
</ul>



<h2>3. Alerta Sonoro</h2>
<ul>
  <ul>
    <li>Quando os LEDs vermelho ou amarelo são ativados, um buzzer emite um sinal sonoro.</li>
    <li>O som serve como um alerta adicional, informando sobre a ocorrência de um problema relacionado à iluminação.</li>
  </ul>
</ul>
<hr></hr>
<h1>Como reproduzir?</h1>

<h2>📁Acesso ao projeto</h2>

<div>O acesso ao projeto se encontra na plataforma de simulação do wokwi no link abaixo:</div>
<a href= "https://wokwi.com/projects/412919690825689089">Clique Aqui</a>

<h2>🙋Abrir e rodar o projeto</h2>
<div>Após abrir o link acima siga com as etapas abaixo:</div>
<ul> 
  <div>1.Para iniciar a simulação</div>
  <div>2.Procure o botão "Start the simulation";</div>
  <div>3.Clique no botão "Start the simulation";</div>
  <div>4.Procure o LDR ;</div>
  <div>5.Mude a quantidade de "Lux"(a partir da barra que aparece ao clicar no LDR)</div>
  <div>6.Procure o DHT22;</div>
  <div>7.Por fim aumente e diminua a quantidade de temperatura e humidade do DHT22(utilizando as barras que aparecem ao clicar no DHT22);</div>
  
</ul>
<h2>Para acompanhar a leitura do LDR e do DHT22</h2>
<ul>
  <div>Para acompanhar os valores gerados pelo LDR e pelo DHT22 olhe para o display(que aparece acima do DHT22);</div>
</ul>
<h2>🎯Tecnologias utilizadas</h2>

<h2>Linguagem</h2>
<li>Linguagem em C++</li>
<li>Hardware</li>
<li>Arduino uno R3</li>
<li>Placa de ensaio</li>
<li>LEDs ( verde, amarelo e vermelho)</li>
<li>Fotorresistor</li>
<li>Buzzer</li>
<li>Resistores ( 1kΩ para os leds; 10kΩ para o ldr)</li>
<li>RTC 1307</li>
<li>DHT22(no simulador e DHT11 no real)</li>
<li>LCD 16x2(I2C)</li>

<h2>Link Vídeo youtube:</h2>

<hr></hr>

<h2>Autores</h2>

<div>Nome: Matheus Eiki Irizawa Ikeda</div> 
<div>RM:559483</div>
<div>Github:https://github.com/Matheus-Eiki</div>
<div>@matheus.eiki</div>
<br></br>
<div>Nome: Kayque Carvalho do Silva</div> 
<div>RM:561189</div>
<div>Github:https://github.com/Kay-Carv</div>
<div>@carvalhokayque020</div>
<br></br>
<div>Nome: Marcelo Affonso Fonseca</div> 
<div>RM:559790</div>
<div>Github:https://github.com/tenebres-cpu</div>
<div>@marceloaffons</div>

<hr></hr>


<h2>Direitos autorais</h2>
É concedida permissão, gratuitamente, a qualquer pessoa que obtenha uma cópia deste software e arquivos de documentação associados (ao "Software"), para lidar no Software sem restrições, incluindo, sem limitação, os direitos de usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias do Software e permitir que as pessoas a quem o Software é capacitado para fazê-lo, sujeito às seguintes condições:

O SOFTWARE É FORNECIDO "COMO ESTÁ", SEM GARANTIA DE QUALQUER TIPO, EXPRESSA OU IMPLÍCITAS, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS DE COMERCIALIZAÇÃO,ADEQUAÇÃO A UM DETERMINADO FIM E NÃO VIOLAÇÃO. EM HIPÓTESE ALGUMA O/OS AUTORES OU DETENTORES DE DIREITOS AUTORAIS SERÃO RESPONSÁVEIS POR QUALQUER RECLAMAÇÃO, DANOS OU OUTRAS RESPONSABILIDADES, SEJA EM UMA AÇÃO DE CONTRATO, ATO ILÍCITO OU DE OUTRA FORMA, DECORRENTE DE,POR FORA, EM CONEXÃO COM O SOFTWARE,O USO OU OUTRAS NEGOCIAÇÕES NO SOFTWARE.
