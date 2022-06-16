## Comandos para gerar a :key: SSH

#### Para irmos aos comandos, primeiro precisamos estar cientes de que as chaves SSH foram criadas para estabelecer uma conexão segura. Podendo ser pública ou privada (criptografada).

> Na aba do Windows digitar **Git Bash**
>
> Em seguida, digitar o comando **ssh-keygen -t ed25519 -C (digitar o e-mail do usuário no GitHub)** e clicar no comando **enter**
>
> Digitar **cd C/Users/(usuario)/.ssh** e clicar no comando **Enter**
>
> Digitar **cat id_ed25519.pub** e clicar no comando **Enter**
>
> Digitar **eval(ssh-agent -s)** e clicar no comando **Enter**
>
> Digitar **ssh-add id_ed25519** e clicar no comando **Enter**
>
> 
>
> 
>
> 
>
> 