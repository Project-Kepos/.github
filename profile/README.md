# Projeto: Kêpos
"𝐊𝐞̂𝐩𝐨𝐬" 𝐞́ 𝐮𝐦𝐚 𝐩𝐚𝐥𝐚𝐯𝐫𝐚 𝐝𝐨 𝐠𝐫𝐞𝐠𝐨 𝐚𝐧𝐭𝐢𝐠𝐨 𝐪𝐮𝐞 𝐬𝐞 𝐫𝐞𝐟𝐞𝐫𝐞 𝐚 𝐮𝐦 𝐣𝐚𝐫𝐝𝐢𝐦 𝐨𝐮 𝐩𝐨𝐦𝐚𝐫. 𝐍𝐚 𝐦𝐢𝐭𝐨𝐥𝐨𝐠𝐢𝐚 𝐠𝐫𝐞𝐠𝐚, 𝐨 𝐉𝐚𝐫𝐝𝐢𝐦 𝐝𝐚𝐬 𝐇𝐞𝐬𝐩𝐞́𝐫𝐢𝐝𝐞𝐬, 𝐨𝐧𝐝𝐞 𝐜𝐫𝐞𝐬𝐜𝐞𝐦 𝐚𝐬 𝐦𝐚𝐜̧𝐚̃𝐬 𝐝𝐨𝐮𝐫𝐚𝐝𝐚𝐬 𝐪𝐮𝐞 𝐜𝐨𝐧𝐟𝐞𝐫𝐞𝐦 𝐚 𝐢𝐦𝐨𝐫𝐭𝐚𝐥𝐢𝐝𝐚𝐝𝐞, 𝐞́ 𝐟𝐫𝐞𝐪𝐮𝐞𝐧𝐭𝐞𝐦𝐞𝐧𝐭𝐞 𝐜𝐡𝐚𝐦𝐚𝐝𝐨 𝐝𝐞 "𝐊𝐞̂𝐩𝐨𝐬".

## Sistema de Gerenciamento de Estufa
O projeto Kêpos visa criar uma plataforma integrada à estufa, utilizando Internet das Coisas (IoT), para facilitar a gestão e automação do ambiente de cultivo.

## Funcionamento da Plataforma
Papel do Arduino
O Arduino será responsável pela coleta de dados, como temperatura, umidade e pH do solo, e pela automação de tarefas simples, como a rega das plantas na estufa.

## Papel da Plataforma
A plataforma se conectará ao Arduino pela internet e exibirá os dados coletados em tempo real por meio de uma página web e um aplicativo móvel.

## Conexão Arduino-Plataforma
Inicialmente, o Arduino precisará de acesso à internet, para o qual existem diversas opções, incluindo módulos de internet com fio (Ethernet) ou sem fio (Wi-Fi) e outras placas de prototipagem, como o ESP32, que já vêm com módulos de internet embutidos.

Depois de conectado à internet, podem ser exploradas duas abordagens: o uso de JSON para troca de dados bidirecional entre Arduino e plataforma, e a integração com MySQL para armazenamento e recuperação de dados.

## Funcionalidades Propostas
Relatórios
A plataforma pode gerar relatórios diários, mensais e anuais com os dados coletados da estufa, auxiliando os usuários na tomada de decisões. Isso pode incluir visualização em tela e exportação para PDF.

### Contas de Usuário
Implementar um sistema de contas de usuário permitiria aos usuários gerenciar suas estufas, com a possibilidade de registrar múltiplas estufas em uma única conta.

### Controle da Estufa pela Plataforma
Explorar a capacidade da plataforma para controlar dispositivos na estufa, como agendar regas baseadas em horário ou nível de umidade, utilizando a comunicação JSON.

### Configurações Específicas por Planta
Possibilitar ao usuário configurar parâmetros específicos para diferentes tipos de plantas na estufa, utilizando módulos individuais equipados com sensores e irrigadores. Cada "módulo" seria gerenciado individualmente pelo Arduino, permitindo cuidados personalizados para cada planta.

Nota: A viabilidade técnica dessa abordagem precisa ser testada para verificar a capacidade do Arduino de gerenciar múltiplos módulos.







<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
