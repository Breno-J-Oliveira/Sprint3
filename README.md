🚦 Visão Geral do Projeto – Semáforo Inteligente
Este projeto tem como objetivo desenvolver um semáforo inteligente, iniciando com conceitos básicos de Arduino e evoluindo até a simulação de um cruzamento urbano realista, com múltiplas vias, sensores e botões para pedestres. A cada etapa, o sistema foi sendo aprimorado com novas funcionalidades, tornando-o mais completo e funcional.

🔧 Protótipo 1: Semáforo Básico
🔗 Ver no Tinkercad

Objetivo: Entender a conexão de LEDs ao Arduino e programar a sequência de sinais.

Componentes:

3 LEDs (vermelho, amarelo e verde)

Resistores de 220 Ω

Placa Arduino Uno

Protoboard e fios

Funcionamento:

LED verde acende por 5 segundos

Em seguida, o amarelo por 2 segundos

Depois, o vermelho por 5 segundos

O ciclo se repete continuamente

✅ Essa etapa foi essencial para aprender a base do controle de sinais com Arduino.

🚶 Protótipo 2: Botão para Pedestres
🔗 Ver no Tinkercad

Novidade: Adição de um botão para simular o pedido de travessia dos pedestres.

Como funciona:

O botão pode ser pressionado a qualquer momento.

O sistema armazena o pedido e aguarda o momento seguro para ativar o semáforo dos pedestres.

O semáforo de carros fica vermelho e o LED "pedestre verde" acende, permitindo a travessia.

🎯 Isso aproxima o sistema da realidade urbana, com controle de travessia sob demanda.

👁️ Protótipo 3: Sensor Infravermelho
🔗 Ver no Tinkercad

Novidade: Inclusão de sensor infravermelho (IR) para detectar a presença de veículos.

Como funciona:

O sensor monitora a presença de carros na via.

Se não há veículos, o tempo do sinal verde é reduzido.

Se houver tráfego intenso, o sinal verde permanece mais tempo.

🚗 Isso torna o sistema mais eficiente, simulando semáforos adaptativos usados em grandes cidades.

🚦🏙️ Protótipo Final – Sprint 3: Cruzamento Inteligente com Maquete Física
🔗 Ver no Tinkercad

Cenário: Simulação de um cruzamento real, com duas vias se cruzando (em "T" ou "+").

🆕 Novidades da Sprint 3:
Melhoria no código: Reestruturação para torná-lo mais modular, claro e organizado.

Divisão do sistema em dois Arduinos Uno:

Devido à limitação de entradas e saídas em um único Arduino.

Facilitou o manuseio e a organização dos cabos.

Construção de uma maquete física:

Criamos um modelo realista para testar os componentes e o comportamento do sistema na prática.

📸 (Inserir aqui uma ou duas fotos da maquete)

🧩 Componentes Utilizados:
4 LEDs vermelhos, 4 LEDs amarelos e 4 LEDs verdes para os semáforos dos veículos

4 LEDs vermelhos e 4 LEDs verdes para os semáforos dos pedestres

32 resistores (220 Ω)

2 visores de 7 segmentos

2 botões de pressão

2 placas de ensaio (protoboards)

2 placas Arduino Uno

Fios de conexão

Funcionalidades Integradas:
Controle de semáforo para duas vias independentes

Botões para pedestres com controle de travessia segura

Sensores IR para detectar presença de veículos

Lógica de sincronização para evitar conflitos entre os sinais

Ajuste dinâmico de tempos baseado no tráfego

🧠 Código:

Modular, com funções separadas para cada semáforo e pedestre

Lógica de prioridade para atender pedestres no tempo certo

Sistema reativo, que ajusta os sinais conforme o contexto

🎯 Conclusão
Durante o desenvolvimento, avançamos de um simples ciclo de LEDs para um sistema inteligente capaz de:

Coordenar fluxos de veículos e pedestres com segurança

Ajustar tempos de sinal de forma dinâmica e eficiente

Simular cruzamentos reais com múltiplas vias e sensores

Ser testado e validado em uma maquete física realista

Esse projeto é uma excelente demonstração prática da integração entre hardware (Arduino, sensores, LEDs, botões) e software (programação em C/C++) para resolver problemas do mundo real — como o controle inteligente do tráfego urbano.

💡 Explore os links no Tinkercad, clone o código e sinta-se livre para propor novas ideias!
