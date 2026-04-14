Analisador de Frequência de Texto 📊
Este projeto foi desenvolvido como parte dos exercícios práticos do curso Python Impressionador da Hashtag Treinamentos. O objetivo é aplicar conceitos de manipulação de strings, dicionários e o uso de bibliotecas padrão do Python para análise estatística de dados textuais.

Descrição do Projeto
O programa recebe um texto fornecido pelo usuário e realiza um processamento completo para extrair métricas relevantes. Ele é capaz de:

Contar o número total de palavras.

Calcular a frequência de cada palavra (léxico).

Calcular a frequência de cada caractere (letras), ignorando diferenciação entre maiúsculas e minúsculas (case-insensitive).

Realizar o tratamento automático de pontuação e caracteres especiais.

Tecnologias e Conceitos Utilizados
Linguagem: Python 3.x

Módulo string: Utilizado para manipulação eficiente de pontuações via tabelas de tradução (maketrans e translate).

Módulo collections (Counter): Utilizado para contagem otimizada de alta performance.

Docstrings: Funções documentadas seguindo boas práticas de engenharia de software.

Como executar
Certifique-se de ter o Python instalado em sua máquina.
Clone este repositório:

Bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Execute o script principal:

Bash
python main.py
Exemplo de Saída
Para o texto: "Olá mundo! Este é um teste. Olá novamente."

O sistema retorna:

Contagem de palavras: 8

Frequência de palavras: Contagem detalhada por termo.

Frequência de letras: Estatística de uso de cada caractere.
