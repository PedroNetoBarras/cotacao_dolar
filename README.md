# Projeto de Cotação do Dólar

Este projeto é um script Python que consulta a cotação do dólar (USD) para o real brasileiro (BRL) e gera um relatório em PDF com os dados coletados. O relatório inclui a cotação atual, a data da consulta, o site onde a cotação foi obtida e um print da página.

## Funcionalidades

- **Consulta Automatizada**: Acessa um site de câmbio para obter a cotação do dólar em relação ao real.
- **Captura de Print**: Tira um print da página onde a cotação foi realizada.
- **Criação de Relatório**: Organiza os dados coletados e os insere em um documento Word.
- **Conversão para PDF**: Converte o documento Word gerado em um arquivo PDF.
- **Criação de Executável**: Transforma o script Python em um arquivo executável para facilitar a distribuição.

## Configuração para Usuários

1. **Instale as Dependências**:
   - Certifique-se de ter o Python instalado.
   - Instale as bibliotecas necessárias:
     ```bash
     pip install requests beautifulsoup4 selenium pillow python-docx fpdf
     ```

2. **Baixe o ChromeDriver**:
   - Baixe o [ChromeDriver](https://sites.google.com/chromium.org/driver/) compatível com sua versão do Chrome.
   - Coloque o arquivo `chromedriver` em um diretório acessível e atualize o caminho no script (`path/to/chromedriver`).

3. **Execute o Script**:
   - No terminal, navegue até o diretório do script e execute:
     ```bash
     python cotacao_dolar.py
     ```
   - O script gerará os arquivos `relatorio.docx` e `relatorio.pdf` no diretório atual.

## Configuração para Desenvolvedores

1. **Clone o Repositório**:
   - Clone o repositório para o seu ambiente local:
     ```bash
     git clone https://github.com/seu-usuario/cotacao_dolar.git
     ```

2. **Crie um Ambiente Virtual** (opcional, mas recomendado):
   - Navegue até o diretório do projeto e crie um ambiente virtual:
     ```bash
     python -m venv meu_ambiente
     ```
   - Ative o ambiente virtual:
     - No Windows:
       ```bash
       meu_ambiente\Scripts\activate
       ```
     - No macOS/Linux:
       ```bash
       source meu_ambiente/bin/activate
       ```

3. **Instale as Dependências**:
   - Com o ambiente virtual ativado, instale as dependências:
     ```bash
     pip install -r requirements.txt
     ```

4. **Contribua**:
   - Faça alterações no código e crie novos commits.
   - Envie suas alterações para o GitHub com `git push`.

## Exemplo de Uso

1. **Consulta da Cotação**:
   - Execute o script para consultar a cotação e gerar o relatório:
     ```bash
     python cotacao_dolar.py
     ```

2. **Relatórios Gerados**:
   - `relatorio.docx`: Relatório em formato Word contendo a cotação, data e print da página.
   - `relatorio.pdf`: Relatório convertido para formato PDF.

## Problemas Conhecidos

- **Problemas com o ChromeDriver**:
  - Certifique-se de que o ChromeDriver está atualizado e compatível com a versão do seu navegador Chrome.
  
- **Erros de Conexão**:
  - Verifique sua conexão com a Internet se o script não conseguir acessar o site de câmbio.

- **Erros de Dependências**:
  - Se você encontrar erros relacionados a bibliotecas, tente reinstalar as dependências ou atualizar o `requirements.txt`.

---

Para mais informações ou problemas, sinta-se à vontade para abrir uma [issue](https://github.com/seu-usuario/cotacao_dolar/issues) no GitHub ou entrar em contato com o mantenedor do projeto.
```

### Explicação das Seções

- **Funcionalidades**: Descreve o que o projeto faz.
- **Configuração para Usuários**: Passos para instalar e executar o script.
- **Configuração para Desenvolvedores**: Passos para configurar o ambiente de desenvolvimento e contribuir com o projeto.
- **Exemplo de Uso**: Mostra como executar o script e o que esperar como saída.
- **Problemas Conhecidos**: Lista problemas comuns e sugestões para resolvê-los.
