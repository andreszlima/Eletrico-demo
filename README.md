# Elétrico
## Aplicação para uso por engenheiros eletricistas

### Demonstração
Caso queira testar o aplicativo online, vá para o link: [https://eletrico.herokuapp.com](https://eletrico.herokuapp.com) - O primeiro carregamento deve demorar um pouco, já que o aplicativo hiberna após 30 min de inatividade. Caso ele não abra depois de algum tempo carregando me envie um e-mail que colocarei em funcionamento novamente.<br>

### Funcionalidades
O software tem como objetivo analisar redes radiais de distribuição e obter resultados importantes como Fluxo de Carga (para análise de tensões e correntes em todos os pontos do sistema) e estudos de Curto Circuito* (para parametrização de relés de proteção de sobrecorrente)

* Funcionalidade a ser adicionada

### Informações adicionais de segurança:
- Todos os arquivos enviados ao site são criptografados e armazenados na nuvem da Amazon. Os links para visualização expiram após 5 minutos que a página foi aberta. Isso possibilta maior segurança aos dados. Após este tempo basta recarregar a página que um novo link é gerado e o arquivo pode ser acessado automaticamente, sem que o usuário perceba.
- As senhas dos usuários também são criptografadas. Nem administrador nem quem tem acesso ao banco de dados tem acesso às senhas, que são armazenadas através do que é chamado de "hash". Um exemplo é a senha '123456', que está armazenada no banco de dados como "$2a$11$NRgCPQZWSI5gU64FB/aJ2uHYWIcetg6oLTxYYX.02B8S6CPDE59la". Isso é muito importante para a segurança das informações.
- O site possui certificado de segurança SSL, que permite a comunicação criptografada entre um site e um navegador, oferecendo mais uma camada de segurança.


### Este programa é gratuito/código aberto?

Não, já que foi criado para que empresas consigam ganhar dinheiro de forma mais rápida e eficiente! O repositório privado, que contém o código (proprietário e fechado) atualizado, está concluído. A versão do link [aqui](https://immense-escarpment-11106.herokuapp.com) está atualizada com a última versão

#### Dados técnicos

Linguagens de programação: Ruby, HTML5, CSS3, SCSS, Javascript, Coffeescript<br>
Framework: Ruby on Rails<br>
Banco de dados utilizado: PostgreSQL<br>

## Para mais informações: 

* Autor: André de Souza Lima
* E-mail: andre.szlima1@gmail.com / andreszlima@ufrn.edu.br
* Instagram: www.instagram.com/andreszlima
* Twitter: www.twitter.com/andreszlima
