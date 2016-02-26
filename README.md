#CakePHP

##Comando para subir o servidor do cake:
Entra no diretorio e digita bin/cake server


##Método para passar o conteúdo de uma variavel do controller para a view:
$this->set((nome da variavel na view),(nome da variavel do controller));

##Arquivo para olhar todas as regras de validação:
Vendor/cakephp/cakephp/src/Validation/Validation.php

##Sempre que usar a key 'action' colocar dentro de um ['url' =>['action' => 'comando']] por causa da nova versão do cake

##Como deixa um texto traduzivel para outros idiomas:
coloca entre __()

##Tag php que escre diretamente o texto:
<?= >

##Comando para fazer um snapshot da versao atual do banco de dados:
bin/cake bake migration_snapshot (nome que sera dado a versao)

Obs: Tem que ser como SUDO


##Comando para criar uma migration
 bin/cake migrations create (nome que sera dado a migration)

Obs:Tem que ser como SUDO

##Comando para executar uma migration:
bin/cake migrations migrate

Obs:Tem que ser como SUDO

##Comando para reverter as ultimas alterações :
bin/cake migrations rollback

Obs:Tem que ser como SUDO

