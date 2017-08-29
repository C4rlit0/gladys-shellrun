# gladys-shellrun

**Installation :**

L'installer via le mode avancé : 

**Nom :** ShellRun

**Version :** 0.1.0

**URL git :** https://github.com/C4rlit0/gladys-shellrun.git

**Slug :** shellrun

ensuite

créez autant de script gladys que nécéssaire via :

gladys.modules.shellrun.shell.exec('path_to_ur_file.sh');

PS: pensez à rendre vos scripts exécutables via : chmod +x VOTRE_SCRIPT.sh


**Exemple : **

Un script de test HelloWorld.sh est disponible dans gladys/api/hooks/shellrun/scripts/test/

gladys.modules.shellrun.shell.exec('~/gladys/api/hooks/shellrun/scripts/test/HelloWorld.sh')
