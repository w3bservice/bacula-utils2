*** Instalado o bacula no Clientes****

Execultar o Instalador de acordo com a versão do Windows.

Clicar em Next > I agree > Custom > Next

Desmarque a caixa de plugins, Documentation e Consoles.
Clicar em Next > Next > Next

* Manter diretorio de Instalação Original, Porta, e Nome.
* o Bacula, Pega Automaticamente o hostname da máquina.

Senha do Cliente: Hw6nx3t+wF+b8yM1iyxLvnsdsEqUB2XO/DnsGsd8kaWT
Senha do Monitor: FUtuXs2cPA863DRytWCINAuRR3qaImfbdQLjpRi/nvZI
Nome do Cliente : sacest01-fd

DIR Name: Eolo-dir 
* Atenção é de estrema importância coloca exatamente igual o nome do director inclusive letras maiúsculas!

Next > Next > Desmarque a caixa "Show Readme" > Finish

Reinicia a máquina!

*****************************************************************

Execultar o "Editar" como administrador para editar as configurações do Cliente.

Dentro do arquivo defina como:
FileDaemon { Name = Hostname do Cliente, Desative os plugins }
Director { Name= Nome do Director, Password= Senha do Cliente }

Atenção! Não há necessidade de configurar o console!

Reinicie o Cliente!


*** Configurando o cliente no Servidor *** 