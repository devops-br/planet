# Planet DevOps Brasil

Esse Planet tem como objetivo agregar artigos de blogs brasileiros que falem sobre a cultura DevOps.

http://devops-br.org/

Para adicionar seu site, basta enviar um pull request nesse repositório:

https://github.com/devops-br/planet

O arquivo a ser modificado é o "config.ini". Para adicionar seu blog, coloque a seguinte sintaxe:

```
[http://url-do-seu-feed]
name = Seu Nome
face = imagem-do-seu-avatar.png
github = https://github.com/seunick
facebook = https://www.facebook.com/seunick
twitter = https://twitter.com/seunick
tumblr = http://seunick.tumblr.com/
youtube = https://www.youtube.com/channel/seucanal
```

Exemplo:

```
[http://techfree.com.br/category/devops/feed/]
name = Gomex
face = Hackergotchi-Rafaelgomes.png
github = https://github.com/gomex
facebook = https://www.facebook.com/rbgomes
twitter = https://twitter.com/gomex
tumblr = http://devopsreactions-br.tumblr.com/
youtube = https://www.youtube.com/channel/UCPNrIITPNFFLmcU3VfoKuGQ
```

A imagem precisa estar na pasta "output/images"

Obs: Adicione o feed apenas da categoria devops ou qualquer outro método de controle do seu blog pra evitar que o planet pegue conteúdo que não seja do assunto DevOps.
