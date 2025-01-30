# Document Classifier with spaCy

## 📌 Descrição
Este projeto classifica automaticamente documentos em **25 categorias** usando a biblioteca [spaCy](https://spacy.io/). O modelo analisa o texto e identifica seu tipo com base em palavras-chave predefinidas.

## 🚀 Tecnologias Utilizadas
- Python 3.x
- spaCy

## 📂 Categorias Suportadas
- E-mail
- Contrato
- Notícia
- Receita
- Artigo Científico
- Código de Programação
- Redação
- Relatório
- Blog Post
- Discurso
- Diário
- Poesia
- Manual de Usuário
- Carta
- Tese
- Resenha
- Anúncio Publicitário
- Fábula
- História em Quadrinhos
- Mensagem de Texto
- Comunicado Oficial
- Lista de Compras
- Roteiro de Filme
- Piada

## 📦 Instalação
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/document-classifier-spacy.git
   cd document-classifier-spacy
   ```
2. Instale as dependências:
   ```bash
   pip install spacy
   python -m spacy download pt_core_news_sm
   ```

## ▶️ Como Usar
Execute o script e insira um texto para classificação:
```bash
python classifier.py
```
Digite ou cole o texto quando solicitado e veja a categoria correspondente.

## 📜 Exemplo de Uso
Entrada:
```
Prezados, envio em anexo o relatório de desempenho do último mês.
```
Saída:
```
O documento foi classificado como: E-mail
```

## 🤝 Contribuição
Sinta-se à vontade para abrir issues e enviar PRs com melhorias!

## 📄 Licença
Este projeto está sob a licença MIT.
