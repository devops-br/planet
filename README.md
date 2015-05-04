# Planet DevOps Brasil

Esse Planet tem como objetivo agregar artigos de blogs brasileiros que falem sobre a cultura DevOps.

http://devops-br.org/

Para adicionar seu site, basta enviar um pull request nesse repositório:

https://gitlab.com/devops-br/planet

O arquivo a ser modificado é o "config.ini". Para adicionar seu blog, coloque a seguinte sintaxe:

```
[http://url-do-seu-feed]
name = Seu Nome
face = imagem-do-seu-avatar.png
```

Exemplo:

```
[http://techfree.com.br/category/devops/feed/]
name = Rafael Gomes
face = Hackergotchi-Rafaelgomes.png
```

A imagem precisa estar na pasta "output/images"

Obs: Adicione o feed apenas da categoria devops ou qualquer outro método de controle do seu blog pra evitar que o planet pegue conteúdo que não seja do assunto DevOps.