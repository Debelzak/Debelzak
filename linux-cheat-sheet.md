# Lembretes de comandos unix

## Comandos
### SELinux
 Comando | Descrição
 --- | ---
`sestatus` | Mostra status do serviço SELinux
`getnforce` | Mostra se está em modo enforcing ou permissive.
`setenforce <opção>` | Define se em modo enforcing(1) ou permissive(0)
`audit2allow` | Gera regras SELinux de permissão / não auditoria de logs de operações negadas </br> `-a/--all` : Mostra todos os serviços. </br> `-M` : gera pacote de política de permissão do módulo. 
`semodule` | Controle de módulos. </br> `-i/-install` : Instala pacote de módulos. </br> `-r/--remove` : Remove módulo existente. </br> `-e/--enable` : Ativa módulo. <br> `-d/--disable` : Desativa módulo.

### OpenSSH
TODO

## Pacotes para instalar aplicações
`audit2allow` : Pacote presente em pacote `policycoreutils-python`.
