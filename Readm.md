# Relatório – Introdução à Web e Linguagens de Marcação

## Parte 1 – Engenharia Reversa de Sintaxe

### 1. Qual trecho foca na semântica personalizada dos dados?

O Trecho C, escrito em XML.

O XML permite criar tags personalizadas, como `<livro>`, `<titulo>` e `<autor>`. Seu objetivo principal é organizar e representar os dados, sem se preocupar diretamente com a forma como eles serão exibidos visualmente.

### 2. Qual sintaxe é mais eficiente para documentar um código?

O Markdown, apresentado no Trecho B.

Ele possui uma sintaxe simples, rápida e fácil de ler, sendo muito utilizado em arquivos README.md e documentações de projetos no GitHub e GitLab.

### 3. Qual linguagem seria usada como base para uma loja virtual?

O HTML5, apresentado no Trecho A.

O HTML é utilizado para estruturar páginas da Web e organizar elementos como títulos, textos, imagens, botões, menus e outras partes de um site.

---

# Parte 2 – Auditoria de Infraestrutura Real

## 1. Consulta de Valores de Mercado

O registro de um domínio `.com.br` pelo Registro.br custa atualmente:

* 1 ano: R$ 40,00
* 5 anos: R$ 184,00

Sim, existe desconto para períodos maiores.

Se fossem pagos 5 anos separadamente, o total seria:

R$ 40 × 5 = R$ 200,00

Ao registrar por 5 anos de uma vez, são pagos R$ 184,00, resultando em uma economia de R$ 16,00.

---

## 2. Rastreamento de IP – DNS na prática

Site escolhido: globo.com.br

No Prompt de Comando do Windows, foi utilizado:

`ping globo.com.br`

Endereço IPv4 retornado:

`186.192.83.5`

O comando ping consulta o domínio e permite identificar o endereço IP relacionado ao servidor, além de testar a comunicação entre o computador e o destino.

---

## 3. Investigação com Whois

Domínio pesquisado: globo.com.br

Empresa detentora:

Globo Comunicação e Participações S.A.

CNPJ:

27.865.757/0001-02

Data de criação do domínio:

25/10/1996

Data de expiração atual:

25/10/2029

Servidores DNS:

* ns01.oghost.com.br
* ns02.oghost.com.br
* ns03.oghost.com.br
* ns04.oghost.com.br

O servidor `ns01.oghost.com.br` aparece no registro SOA como servidor principal da zona. Os demais servidores funcionam como servidores DNS autoritativos adicionais.

Qual linguagem seria usada como base para uma loja virtual?

O HTML5, porque ele é usado para criar e organizar a estrutura das páginas de um site, como textos, imagens, menus e botões.    
---

## Conclusão

A atividade permitiu compreender a diferença entre HTML, XML e Markdown e suas principais aplicações. Também foi possível analisar na prática como funcionam elementos da infraestrutura da Web, como domínios, DNS, endereços IP e servidores responsáveis por um domínio.

# Projeto Nova-Web - Especificações de UI/UX (Tela de Login)

## 1. Conceitos de Usabilidade em Formulários

### Labels e Placeholders

O label serve para mostrar qual informação deve ser colocada em cada campo. Já o placeholder pode ser usado para dar um exemplo, mas não deve substituir o label, pois ele desaparece quando o usuário começa a digitar.

Por exemplo, em um campo de e-mail, podemos colocar "E-mail" como label e "[exemplo@email.com](mailto:exemplo@email.com)" como placeholder. Dessa forma, o usuário consegue entender o campo mesmo depois de começar a escrever. A W3C também recomenda que os campos dos formulários tenham labels claros e associados corretamente aos controles.

### Hierarquia Visual

Os botões precisam ter diferentes níveis de destaque para mostrar quais ações são mais importantes.

O botão principal, como "Entrar", deve chamar mais atenção, pois é a ação principal da tela. Já opções como "Criar Conta" e "Esqueci a Senha" podem ter menos destaque.

Isso ajuda o usuário a entender mais rapidamente o que deve fazer na tela e evita confusão entre as diferentes opções.

---

## 2. Estados dos Campos de Entrada

Os campos podem mudar de aparência dependendo da situação em que estão sendo usados.

### Default (Padrão)

É o estado normal do campo. Ele deve ter uma borda simples e um label fácil de entender, mostrando que está disponível para preenchimento.

### Focus (Foco)

Acontece quando o usuário seleciona um campo para digitar. Nesse momento, o campo deve receber algum destaque, como uma mudança na cor da borda ou um contorno.

Esse destaque ajuda a pessoa a saber exatamente em qual campo está digitando. A WCAG recomenda que o foco do teclado seja visível.

### Error (Erro)

Quando alguma informação está errada ou não foi preenchida corretamente, o campo pode ser destacado em vermelho. Também deve aparecer uma mensagem explicando o problema, para que o usuário saiba como corrigir.

### Success (Sucesso)

Quando o preenchimento está correto, pode aparecer uma indicação visual mostrando que aquela informação foi aceita. Isso ajuda o usuário a saber que não precisa alterar aquele campo.

### Disabled (Desabilitado)

Quando um campo não pode ser usado naquele momento, ele pode ficar com uma aparência mais apagada. Isso mostra que o campo está desativado e não pode receber informações.

---

## 3. Padrões de Acessibilidade

### Contraste das cores

As cores do texto e do fundo precisam ter uma boa diferença para facilitar a leitura. De acordo com a WCAG, textos comuns devem ter uma relação de contraste de pelo menos 4,5:1. Para textos maiores, o mínimo é 3:1.

Também é importante não depender apenas das cores para mostrar informações. Por exemplo, em um erro, além de usar vermelho, é melhor colocar uma mensagem explicando o problema.

### Leitores de tela

Os campos devem possuir nomes e informações claras para que programas de leitura de tela consigam identificar o que cada campo representa. O uso correto de labels ajuda nesse processo.

### Navegação pelo teclado

O formulário deve permitir que o usuário passe pelos campos usando a tecla Tab. Também é importante que seja possível identificar visualmente qual campo está selecionado no momento.

### Conclusão

As escolhas feitas para a tela de login foram pensadas para deixar o formulário simples, organizado e fácil de entender. O uso correto dos labels, a diferença entre os botões, os estados dos campos e os cuidados com acessibilidade ajudam a melhorar a experiência do usuário.

