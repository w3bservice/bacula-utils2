## Configurando Clientes no Bacula.
1. Execute o Instalador do Bacula conforme a versão do Windows: **"32 bits ou 64 bits"**

2. Clique em  **"Next > I agree > Custom > Next"**

3. Desmarque a caixa **"Consoles, Plugins e Documentation"**

4. Clique em  **"Next > Next"**
* Para manter o diretorio de instalação original.

5. Altere a senha para a padrão de configuração do Bacula.
* O Bacula, pega automaticamente o hostname da máquina.
* Mantenha a porta, nome, max jobs e ambas caixas marcadas.
* Anote exatamente como está escrito o **"name"**.

6. Clique em  **"Next"**

7. Digite exatamente como está anotado no caderno o nome do **"DIR Name"**.

8. Clique em **"Install > Next"** 

9. Desmarque a caixa **"Show Readme"**

10. Clique em **"Finish"**

11. **Reinicia a máquina!**

## Configurando o Cliente no Servidor.

11. Abra o **"putty"**

12. Digite o IP do Servidor em Host Name.

13. Clique em **"Open"**.

14. Digite o nome do usuário, senha e faça login.

15. Digite **su**

16. Digite **cd /etc/bacula**

17. Digite **cp -r Exemplo /elstc/bacula/clients-and-jobs/Nome_do_Cliente_Aqui**

18. Digite **cd clients-and-jobs/Nome_do_Cliente_Aqui**

19. Digite **nano fd.conf**
* Altere o **"name"** e **"Hostname"** para o nome do cliente, anotado no passo 5.

17. Digite **
