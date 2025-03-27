# 🏷️ PJeOffice Label Printing System

## 📌 Descrição Geral

Este sistema de impressão de etiquetas é uma aplicação web desenvolvida para a Justiça Federal (JFMS) que permite a geração e impressão de etiquetas de patrimônio de forma rápida e simples.

## ✨ Funcionalidades Principais

### 1. Impressão de Etiqueta Individual
- Permite inserir um número de patrimônio e descrição do item
- Gera uma etiqueta com código de barras personalizado
- Suporta impressão em tempo real com pré-visualização

### 2. Impressão em Lote
- Possibilita colar dados de uma planilha para impressão múltipla de etiquetas
- Processamento em lote de vários itens simultaneamente

## 🛠️ Tecnologias Utilizadas
- HTML5
- Bootstrap 5.3
- JavaScript
- PJeOffice Pro API para impressão

## 🖨️ Processo de Impressão

### Etiqueta Padrão
- Contém número de patrimônio
- Código de barras gerado dinamicamente
- Descrição do item

### Detalhes Técnicos
- Tamanho da etiqueta: 5 cm x 3.2 cm
- Suporte a impressoras via porta LPT1
- Formatação compatível com impressoras de etiquetas

## 🚀 Como Usar

### Impressão Individual
1. Digite o número do patrimônio
2. Insira a descrição do item
3. Clique em "IMPRIMIR ETIQUETA"

### Impressão em Lote
1. Cole dados da planilha no campo de texto
2. Formato: `[NÚMERO] [DESCRIÇÃO]`
3. Clique em "IMPRIMIR ETIQUETAS EM LOTE"

## ⚠️ Observações
- Remove automaticamente acentos e caracteres especiais
- Limita descrição para melhor visualização
- Requer PJeOffice Pro instalado e configurado

## 📋 Exemplo de Entrada em Lote
```
12345 MONITOR LCD 20 POLEGADAS
67890 TECLADO ERGONÔMICO
```

## 🔒 Requisitos
- Navegador web moderno
- PJeOffice Pro instalado
- Impressora compatível

## 📧 Suporte
Em caso de dúvidas, entre em contato com o suporte de TI da Justiça Federal.
