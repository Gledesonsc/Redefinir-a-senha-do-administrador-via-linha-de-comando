# 🔄 Redefinir credenciais de administrador no CyberPanel

Para redefinir tanto a senha quanto o nome de usuário do administrador no CyberPanel, siga estes passos simples:

### Passo 1️⃣: Acessar o Terminal

Abra o terminal no seu sistema operacional.

### Passo 2️⃣: Acesse o Diretório CyberPanel

Digite o seguinte comando para acessar o diretório onde o CyberPanel está instalado:

```bash
cd /usr/local/CyberPanel
```

### Passo 3️⃣: Redefinir a senha do administrador

Utilize o comando abaixo para redefinir a senha do administrador:

```bash
adminPass NovaSenha
```

Substitua "NovaSenha" pela nova senha desejada.

### Passo 4️⃣: Redefinir o nome de usuário do administrador

Use o comando a seguir para alterar o nome de usuário do administrador:

```bash
adminUser NovoNomeDeUsuario
```

Substitua "NovoNomeDeUsuario" pelo novo nome de usuário desejado.

### Passo 5️⃣: Reinicie o CyberPanel

Após redefinir a senha e o nome de usuário, reinicie o CyberPanel para aplicar as alterações:

```bash
systemctl restart lscpd
```

Agora você redefiniu com sucesso tanto a senha quanto o nome de usuário do administrador no Painel CyberPanel.

## Observação

Certifique-se de usar uma senha segura e exclusiva para manter a segurança do seu Painel CyberPanel.

---
Este documento foi criado para orientar sobre como redefinir as credenciais do administrador no Painel CyberPanel via linha de comando. Se precisar de ajuda adicional, sinta-se à vontade para entrar em contato.
