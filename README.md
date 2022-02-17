# Dados-da-COVID-19-no-ano-de-2021
   Um site criado com Python-Flask e bibliotecas Python (Pandas e Matplotlib) para visualização e manipulação de dados. Os dados foram extraídos em formato CSV, diretamente do site do Ministério da Saúde, com dados até a data de 31/10/2021. Apesar deste Dataset possuir dados de todas as cidades do Brasil, este site desenvolvido por mim mostra apenas os dados das cidades de Taubaté, Tremembé e Pindamonhangaba, da região do Vale do Paraíba no estado de São Paulo.

**Projeto livre para ser continuado/melhorado! Caso o faça, por favor me mande por email - alicefkw@outlook.com - uma descrição/fotos/e até mesmo o projeto, gostarei muito de ver este retorno!**

**Dúvidas ou contato favor utilizar o e-mail citado acima.**

   Trabalho feito utilizando a linguagem PYTHON. Para tudo ocorrer corretamente, por favor siga os passos neste arquivo.
   É necessário instalar, preferencialmente na versão mais recente, a linguagem Python --disponível em https://www.python.org/downloads/, além de algumas de suas dependências.
 -Certifique-se de ter somente UMA versão do Python instalada: ter mais de uma pode gerar problemas ao tentar iniciar o projeto ou visualizar as tabelas e gráficos, se a versão do link recomendado apresentar problemas, é recomendado desinstalá-la e digitar “python3” no CMD para instalar a versão da Microsoft Store!
*Para ver todas as versões instaladas do Python eu recomendo o
aplicativo REVO Uninstaller, um desinstalador completo de
programas, que também varre todos os arquivos escondidos no PC
após uma desinstalação*

   Para instalar as dependências, abra o CMD (Prompt de Comando) no modo administrador e digite os comandos:
-Para Python3:
   pip3 install Flask
   pip3 install matplotlib
   pip3 install pandas
-Para Python2 ou anterior:
   pip install Flask
   pip install matplotlib
   pip install pandas

   Sem fechar o CMD, entre na pasta siteCOVID e copie o diretório (localização) dela. Digite então no CMD:
*Se o diretório da pasta siteCOVID não estiver no Disco Rígido C: digite
o correspondente (por exemplo D:)
cd ctrlV    (cd diretório/siteCOVID/)

Apenas visualização:
-Para Python3:
   python3 run.py
-Para Python2 ou anterior:
   python run.py
OU (do jeito a seguir o flask é configurado e ligado, assim a página atualiza com as devidas mudanças realizadas em código):
   set FLASK_APP=run.py
   set FLASK_ENV=development
   flask run

E abra no seu navegador o link 127.0.0.1:5000
*Os gráficos podem demorar para aparecer ou aparecer algum com
tamanho diferente do restante, este bug pode ser resolvido ao
atualizar a página!
SITE DO MINISTÉRIO DA SAÚDE (TODA A FONTE DE DADOS):
https://covid.saude.gov.br/
