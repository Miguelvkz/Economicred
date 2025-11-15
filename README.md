💰EconomicRed – Caixa Eletrônico Web

Projeto integrador do 1º semestre do curso de Desenvolvimento de Sistemas
(SENAI Armando de Arruda Pereira – período da tarde).

Grupo: Enzo Penido, Miguel Guedes e Gustavo Cagega.

🔧 Descrição do Projeto

O EconomicRed é um sistema de simulação de caixa eletrônico feito totalmente em HTML, CSS, JavaScript e PHP, sem banco de dados.
Todas as contas, saldos e dívidas são gerenciadas através de um arquivo usuarios.json.

O projeto inclui:

Login com validação por senha

Tela de menu com navegação entre operações

Sistema completo de saque, depósito, transferência, consulta de saldo e dívidas

Sistema de cartão de crédito

Sons, animações e interface parecida com um caixa eletrônico real

Página de confirmação de operação usando uma única senha para todas as ações
<details>
<summary>📁 Estrutura do Projeto</summary>
- Imagens
  - Banco24h.png
  - bg-menu-teste4.jpg
  - Foto-ultimo-teste.jpg
  - iconmaior.ico
  - Logocomnome.png
  - mulher.png
- index.html
- menu
  - confirmar_operacao.php
  - login.php
  - menu.css
  - menu.php
  - operacao_concluida.html
  - senha.php
- Operações
  - Credito
    - cartao_credito.php
    - credito.html
    - dívidas
      - dividas.html
      - d_cartao.php
  - Deposito
    - deposito.html
    - d_conta_corrente.php
    - d_conta_poupanca.php
  - Saldo
    - saldo.html
    - sa_conta_corrente.php
    - sa_conta_poupanca.php
  - Saque
    - saque.html
    - s_conta_corrente.php
    - s_conta_poupanca.php
  - Transferências
    - transferencias.html
    - t_conta_corrente.php
    - t_conta_poupanca.php
    - t_valor_corrente.php
    - t_valor_poupanca.php
- README.md
- Sons
  - beep.mp3
  - saque_deposito.mp3
- style.css
- usuarios.json
</details>

▶️ Como Rodar o Projeto

Instale o XAMPP ou outro servidor PHP.

Vá até a pasta htdocs:

C:\xampp\htdocs\


Coloque a pasta do projeto dentro de:

C:\xampp\htdocs\EconomicRed


Inicie o Apache no XAMPP

Acesse no navegador:

http://localhost/EconomicRed/index.html

🧪 Tecnologias Usadas

HTML5

CSS3

PHP

JSON

JavaScript (básico para efeitos e sons)

📌 Observações

Todas as operações são verificadas na página confirmar_operacao.php.

O arquivo usuarios.json guarda os dados atualizados dos usuários.

O layout segue a estética de caixas eletrônicos com sons e transições.
