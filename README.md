# Pfsense
Firewall Lab

<h1> Instalação:</h1>
Vá ao site do pfsense e instale o netgate installer.

Como vou usar VM optei pelo ISO Virtual Machines abaixo:
<img width="932" height="468" alt="image" src="https://github.com/user-attachments/assets/14a0ad9d-f418-48ea-98a5-438bc097121f" />

Ao abrir o instalador aparece o seguinte .gz:
<p align="center">
<img width="620" height="77" alt="image" src="https://github.com/user-attachments/assets/5b4e14e3-fc58-4321-85d7-c4b98b50c9cb" />
<p>
Extraindo o .gz com uma ferramenta como WinRar você obtem o iso que está acima e portanto só precisa ser colocado num software como a virtualbox e dar boot:
<p align="center">
<img width="722" height="398" alt="image" src="https://github.com/user-attachments/assets/b68fbb63-75ce-40c9-b281-7fc41eb6b107" />
</p>
Se aparecer essa imagem então deu tudo certo no boot. Se não apareceu a tela então provavelmente você colocou em modo 32bit invés de 64bit então certifique-se de mudar isso na sua VM.
Aceite todas as condições e escolha sua interface de internet e avance.
<p align="center">
<img width="720" height="393" alt="image" src="https://github.com/user-attachments/assets/f47c6d3b-bacb-443f-9fd3-da59cbb0674f" />
<p>
Eu irei optar por usar a versão mais recente do PFsense

Ao terminar de instalar o sistema irá pedir o reboot.

Portanto, desligue a VM e retire o CD nas configs da VM:
<img width="1015" height="431" alt="image" src="https://github.com/user-attachments/assets/b6ab1128-8fbb-406e-a76a-36ede3a7a08a" />

Terminando isso, pode dar boot denovo.

E pronto!!!! Seu PFSense está instalado:
<p align="center">
<img width="726" height="403" alt="image" src="https://github.com/user-attachments/assets/987927a9-baca-4795-a46f-b4860e9c3fc9" />
<p>
