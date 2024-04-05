Calculadora e Armazenamento da Taxa de Gestão
Este projeto consiste em uma aplicação desenvolvida em Python utilizando a biblioteca Streamlit para calcular e armazenar dados da taxa de gestão a ser cobrada dos clientes. O objetivo é fornecer uma ferramenta simples e eficiente para realizar esses cálculos e manter um registro dos dados em um banco de dados MySQL.

Funcionalidades
Calcula a taxa de gestão para diferentes instituições financeiras (BTG, Guide, Ágora).
Permite o upload de arquivos de controle de contratos e arquivos de PL (Planilha de Lucros).
Armazena os dados calculados no banco de dados MySQL.
Oferece a possibilidade de consultar os dados armazenados por período ou de forma completa.
Exporta os resultados para arquivos Excel para análise posterior.
Requisitos
Python 3.x
Bibliotecas: Streamlit, SQLAlchemy, pandas, numpy, openpyxl, xlsxwriter, dotenv.
Instalação
Clone este repositório:
bash
Copy code
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Instale as dependências:
Copy code
pip install -r requirements.txt
Configure as variáveis de ambiente no arquivo .env com as credenciais do banco de dados MySQL:
makefile
Copy code
DB_HOST=bluemetrix-teste.cziuya4oaa6t.us-east-2.rds.amazonaws.com
DB_PORT=3306
DB_USER=admin
DB_PASSWORD=SuaSenha
DB_NAME=Bluemetrix
Execute o aplicativo:
arduino
Copy code
streamlit run app.py
Utilização
Selecione a instituição financeira (BTG, Guide, Ágora) na barra lateral.
Faça o upload dos arquivos de controle de contratos e de PL conforme solicitado.
Os dados calculados serão exibidos na interface, onde você pode visualizá-los e armazená-los no banco de dados.
Utilize as opções de consulta para buscar os dados armazenados por período ou de forma completa.
Os resultados podem ser exportados para arquivos Excel para análise adicional.
Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar solicitações de recebimento.
