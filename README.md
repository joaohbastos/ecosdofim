# 🧩 Ecos do Fim
Ecos do Fim é um jogo de tabuleiro cooperativo, ambientado em um mundo pós-apocalíptico, que utiliza tecnologia embarcada para promover a inclusão de pessoas com deficiência auditiva por meio da Libras (Língua Brasileira de Sinais) como elemento central da comunicação entre os jogadores.

## 📘 Contexto
A deficiência auditiva impacta a comunicação, o aprendizado e a interação social. Causas como fatores genéticos, infecções, lesões ou exposição prolongada a ruídos podem gerar desde perdas auditivas leves até a surdez total. Considerando a relevância da inclusão e acessibilidade, Ecos do Fim surge como proposta lúdica e tecnológica para estimular o uso e a valorização da Libras em um ambiente colaborativo e imersivo.

## 🎯 Objetivos do Projeto
Tornar a Libras uma ferramenta natural de comunicação dentro da mecânica do jogo.
Estimular aprendizagem e empatia através da ludicidade e cooperação.
Criar um ambiente acessível onde pessoas com e sem deficiência auditiva possam interagir em igualdade.
Integrar hardware interativo (como sensores e RFID) com um tabuleiro físico para enriquecer a experiência.
## ⚙️ Tecnologias e Materiais Utilizados
💻 Software
Arduino IDE,
Programação em C++,
Modelagem de narrativa e missões
## 🔌 Hardware
Arduino MEGA,
Módulo leitor RFID (PN532),
Cartões RFID (para representar personagens, itens ou comandos),
LEDs (sinalizações visuais),
Sensores de toque ou botão,
Protoboard e jumpers,
Alimentação via cabo USB ou power bank
## 📦 Materiais do Tabuleiro
Tabuleiro físico impresso
Cartas com símbolos e sinais em Libras
Peças de personagens com tags RFID
Painel de missões
## 🕹️ Como Funciona o Jogo
Cenário Narrativo: Após um evento catastrófico, os jogadores precisam se unir para restaurar a comunicação em uma sociedade silenciosa.
Colaboração em Silêncio: Durante certos momentos do jogo, os participantes não podem se comunicar oralmente, devendo usar Libras ou símbolos visuais.
Tecnologia Integrada: Peças RFID e sensores ativam pistas, obstáculos ou informações adicionais no jogo ao serem posicionadas no tabuleiro.
Objetivo: Cumprir todas as missões de forma cooperativa até restaurar a comunicação entre as regiões do mapa.
## 💡 Exemplos de Interatividade
Ação do Jogador	Resultado Tecnológico
Colocar peça RFID no ponto X	LED acende, liberando carta com missão
Tocar botão durante fase de silêncio	Alarme toca, equipe penalizada
## 🧠 Benefícios Educacionais
Inclusão real no ambiente lúdico.
Estímulo ao alfabetismo visual e sinalizado.
Incentivo à cooperação silenciosa e leitura corporal.
Aproximação da Libras ao público ouvinte de forma divertida e prática.
Uso da tecnologia embarcada como ponte entre acessibilidade e interatividade.
## 🛠️ Instalação do Código (Arduino)
Instale a Arduino IDE.
Baixe as bibliotecas necessárias:
MFRC522 (para uso do leitor RFID)
SPI.h
Faça upload do código para seu Arduino via cabo USB.
Conecte os sensores e dispositivos conforme o esquema abaixo.
## 🔌 Exemplo de conexão RFID (PN532 com Arduino MEGA 2560)
|PN532|	Arduino MEGA 2650|
|-----|-----------------|
|SDA	|SDA 20|
|SCL	|SCL 21|
|2	|IRQ|
|GND|	GND|
|3	|RSTO|
|3.3V|	VCC|
## 👥 Equipe
Este projeto foi desenvolvido por estudantes de Ciência da Computação, com foco em acessibilidade e inovação educacional.

Breno, João Henrique, João Gomes — Desenvolvimento de Hardware
Breno, João Henrique, João Gomes, Leticia, Ana Clara — Narrativa e Design do Jogo\n
Julio e Emilia, Igor — Libras e Acessibilidade\n
Breno, João Henrique, João Gomes, Leticia, Ana Clara, Julio, Emilia, Igor — Documentação e Testes\n
## 📜 Licença
Este projeto está licenciado sob a MIT License.

## 🤝 Contribuições
Contribuições são bem-vindas! Se você deseja sugerir melhorias, corrigir erros ou expandir o projeto, sinta-se livre para abrir um pull request ou issue.
