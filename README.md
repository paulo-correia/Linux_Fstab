# Fstab

Mapeamento automático de compartilhamento(s) windows/samba/nfs/...

Exemplo de compartilhamento Windows/Samba:

`//servidor/compartilhamento     /media/diretorio    cifs    username=usuario,password=senha        0       0`

Se o usuario for guest, colocar apenas guest e senha igual a nada

Para recarregar o fstab sem reiniciar como **root** dê o comando:
`mount -a`