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
