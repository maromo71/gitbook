# 3. Instalando o PHP

Uma boa opção para a instalação do PHP em uma máquina local para o desenvolvimento e testes dos scripts é o XAMPP. Trata-se de um conjunto de softwares que inclui o servidor Apache, o Sistema Gerenciador de Banco de Dados MariaDB, e o PHP.

## 3.1 Instalando no Windows

Para instalar o XAMPP para o windows, acesso o link: [https://www.apachefriends.org/pt\_br/download.html](https://www.apachefriends.org/pt_br/download.html).

![](/assets/xampp.png)

Escolha a opção mais recente, no caso da figura a versão 7.1.4 do PHP clicando sobre o botão baixar.

Após efetuar o download execute o arquivo instalador como Administrador, ou seja, clique com o botão direito do mouse sobre o nome do arquivo e selecione Executar como administrador.

![](/assets/instalador.PNG)

Ao abrir o arquivo de setup clique sobre o botão \[Next &gt;\], não é necessário alterar as opções de componentes que devem estar todas selecionadas.  Continue avançando, a pasta padrão para instalação é \[C:\xampp\], você pode alterar se desejar. Para o uso neste curso usarei esta pasta como a padrão, clique novamente no boão avançar até que comece a baixar os pacotes de arquivos. Como mostra a figura a seguir.

![](/assets/inslandoxampp.png)

Depois de completada a instalação, clique em Finish, deixando a opção de  
 abrir o painel do XAMPP checada.

![](/assets/xamppfinalizando.PNG)

Ao abrir o painel de controle do Xampp, clique apena no botão Start do serviço Apache.

![](/assets/xamppfinalizado.PNG)

O servidor web Apache será responsável por renderizar as páginas \(enviá-las\) ao cliente \(navegador\) quando houver solicitação por parte deste. Se surgir o Alerta de Segurança do Windows você deverá permitir o acesso para que o servidor seja inicializado.

![](/assets/permitiracesso.PNG)

## 3.2 Instalando no Linux

Caso você seja usuário do Sistema Operacional Linux, use o gerenciador de pacotes da sua distribuição para instalar o PHP. Use o apt-get no Ubuntu, Debian, ou o yum se utilizar Fedora ou Red Hat. Procure os pacotes do PHP e do Apache e faça a instalação.

### Instalar o Apache no Fedora

Pelo terminal, digite os seguintes comandos:

`#`**`su [Enter]`**

senha: \[digite sua senha\] \[enter\]

`#`**`yum install httpd [Enter]`**

Comando para iniciar  
`#`**`service httpd start`**`[enter]`  


Depois siga os procedimentos indicados no terminal.

### Comando para instalar o PHP

`#`**`yum install php`**`[enter]`

Comando para reiniciar o Apache:

`#`**`service httpd restart`**`[enter]`



# 3.3 **Testando Apache**

Para testar o apache e verificar se o funcionamento está correto, abra o nagevador web padrão e digite o endereço:`http://localhost`

![](/assets/localhost.PNG)

