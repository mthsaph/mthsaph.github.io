Esta página web é uma aplicação simples para impressão de etiquetas. Vou explicar as principais funcionalidades:

### **Impressão de etiquetas individuais:**

- Permite inserir uma descrição e um número de patrimônio
- Ao clicar no botão "IMPRIMIR ETIQUETA", o sistema gera uma etiqueta com código de barras
- Cada etiqueta contém o número de patrimônio em texto e em código de barras
- A descrição é dividida em até duas linhas (máximo de 26 caracteres por linha)


### **Impressão em lote:**

- Inclui uma área de texto onde se pode colar dados de uma planilha
- O formato esperado é "número descrição" em cada linha
- Ao clicar em "IMPRIMIR ETIQUETAS EM LOTE", o sistema processa todas as linhas e imprime múltiplas etiquetas


### **Validações e tratamento de dados:**

- Remove acentos e cedilhas das descrições
- Verifica se o campo de patrimônio contém apenas números
- Limita o número de patrimônio a valores menores que 100.000.000
- Não permite campos em branco
- Formata automaticamente o texto para caber nas etiquetas


### **Tecnologia:**

- Utiliza o "PJeOffice Pro" para enviar comandos de impressão
- Gera etiquetas no formato ZPL (Zebra Programming Language), que é específico para impressoras térmicas de etiquetas
- Envia os dados para a porta de impressora "LPT1"
- Inclui funções de callback para sucesso, falha e indisponibilidade do serviço



A página tem um visual simples com o logo e identificação da Justiça Federal de Mato Grosso do Sul, e exibe alertas com mensagens bem-humoradas quando há erros na entrada de dados.
