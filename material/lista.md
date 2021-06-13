**Qual é a função do ITU-T no desenvolvimento de padrões para telecomunicações? Quando surgiu o ITU-T? O que significa CCITT?**

A função desempenhada pelo ITU-T é definir recomendações técnicas para interfaces de telefonia, telégrafos e comunicação de dados. O ITU-T se tornou um órgão das nações unidas em 1947. CCITT significa "Comitê Consultivo Internacional de Telegrafia e Telefonia".

**Em meados da década de 1990 a IEEE (Institute of Electrical and Electronics Engineers) recebeu a tarefa de elaborar um padrão de LANs sem Fios. Quais foram as versões deste padrão, as datas em que surgiram e as respectivas velocidades (taxas) de transmissão?**

O padrão inicial (de 1997) definia uma LAN sem fios que funcionava a 1 ou 2 Mbps. Em 1999 o 802.11b funcionava a 11 Mbps. Em 2003 aumentou a velocidade do 802.11a/g para 54 Mbps. Em 2009 o 802.11n chegou até 600 Mbps... Em 2012 o 802.11ad transmite até 6.7 Gbits/s.

**10 - Quais são as diferenças entre transmissão analógica e digital?**

A transmissão analógica os valores variam de forma contínua dentre todo o espectro permitido pelo meio de tranmissão, enquanto na transmissão digital os valores mudam de forma discreta entre dois valores (ou uma gama maior em alguns casos).

**11 - Quais são as diferenças entre modulação e demodulação por amplitude, frequência e fase?**

A modulação é o processo de inserir uma informação em uma onda a partir da variação de uma ou mais de suas propriedades, as mais comuns sendo amplitude, frequência e fase. A demodulação é o processo reverso, recuperando a informação contida na onde. A diferença entre os 3 tipos é apenas em qual propriedade será codificada a mensagem.

**12 - O que é um modem? Para que serve e como pode ser usado o modem? Quais são as diferenças entre um modem analógico e um modem banda base?**

A palavra modem vem de **MO**dulação-**DEM**odulação, ou seja, é um dispostivo capaz de realizar tanto o processo de modulação quanto de demodulação. Modem banda base é um tipo de modem que não executa modulação analógica de sinal digital, mas apenas converte um sinal digital em outro codificado. Enquanto o modem analógica realiza essa modulação.

**13 -Quais os tipos de modulação que temos, considerando a variação de moduladora e portadora como senoide e trem de pulso?**

Quando a moduladora é analógica:

a. AM ou modulação em amplitude
b. FM ou modulação em frequência
c. PM ou modulação em fase 

a. ASK ou modulação por salto de amplitudes
b. FSK ou modulação por salto de frequência
c. PSK ou modulação por salto de fases 

a. PCM – modulação em códigos de pulso 
b. DPCM – PCM diferencial, a informação é enviada por código representado e diferença dos valores
c. DM delta modulation

**14 - Quais as diferenças entre modem ADSL, cable modem e modem ótico?**

O modem ADSL deriva do DSL. A sigla A de ADSL significa Assimétrico Cabe modem utiliza o cabo coaxial como meio de transmissão.

**15 - Quais as diferenças entre distorção por atenuação, ruído e retardo?**

Distorções são mudanças nas características de uma onda durante a transmissão que botem afetar ou impedir o recebimento da mensagem. A distorção por atenuação acontece quando a onda perde energia enquanto se propaga, eventualmente a onda pode chegar a um estado onde nada pode ser recuperado. Já na distorção por ruído é quando temos a interferência externa de outra fonte de energia que interfere na qualidade do sinal. Por último, a distorção por retardo é onde o sinal é retardado mais em algumas frequências do que em outras.

**17 - Apresente o desenho do modelo completo de um sistema de comunicações, comentado sucintamente sobre seus componentes?**

Aplicando o modelo para redes de computadores é considerado que a fonte transmite letras e números. O codificador trabalha em bits e bytes. O emissor que ira adaptar este sinal ao meio, usando modulação e outras técnicas. O meio pode ser cabo trançado, fibra ótica, ou a atmosfera e reverbera o sinal. O receptor retira o sinal do meio adequando o mesmo aos níveis desejados do decodificador, através de modulação ou outras técnicas. O ruído gera interferências degradando as características do sinal transmitido. O decodificador transforma bits e bytes em números e letras. E o destinatário recebe a informação na forma de letras.

**20 - Em relação as características de um canal, defina operação simplex, half-duplex e fullduplex, apresentando exemplos e citando vantagens e desvantagens.**

Simplex: informação é transmitida apenas por um dos dois pontos. Exemplo: rádio de difusão comercial.
Half-duplex: informação é transmitida pelos dois pontos, de forma alternada. Exemplo: rádio amador.
Full-duplex: informação é transmitida pelos dois pontos, de forma simultânea. Exemplo: comunicação entre dois computadores.

**21 - Considerando uma linha ponto-a-ponto é possível ocorrer comunicação fullduplex, usando dois fios (par trançado)? Como?**

Sim, e sim. https://www.edn.com/how-to-send-full-duplex-data-over-a-single-twisted-pair-cat-5-cable/.

**22A - Quais são as definições, diferenças, vantagens e desvantagens entre transmissão serial e paralela? E entre transmissão serial síncrona e assíncrona? Nas respostas apresente desenhos e considere também a “eficiência” da transmissão (e = bits de informação / total de bits)**

A transmissão serial é feita bit-a-bit e a transmissão paralela é bit-a-byte. Na comunicação assíncrona se tem bits de start e stop para cada byte ou caracter transmitido Na comunicação síncrona é enviado um bit por vez.

**25 - Em relação a detecção de erros e retransmissão da informação, comente sobre o que é e como funciona paridade vertical e horizontal, com auxílio de desenhos.**

A paridade vertical adiciona um bit de controle a cada para cada caractere transmitido, enquanto a paridade horizontal adiciona um caractere ao final de um bloco de comprimento fixo de caracteres, onde cada bit é o resultado da aplicação da função XOR sobre os bits de posição correspondente dos caracteres do bloco.