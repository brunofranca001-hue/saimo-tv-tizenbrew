# Saimo TV no TizenBrew

Atalho do [TizenBrew](https://github.com/reisxd/TizenBrew) que abre o site
[saimo-tv.pages.dev](https://saimo-tv.pages.dev/) na TV Samsung (Tizen). Não altera o site:
o `main.js` existe só porque o TizenBrew exige um script em módulos do tipo `mods`.

## Instalar

No TizenBrew, abra o gerenciador de módulos, escolha **Add GitHub Module** e digite:

```
brunofranca001-hue/saimo-tv-tizenbrew
```

Na versão 2.0.5 do TizenBrew, o gerenciador de módulos pode dar `ERR_ACCESS_DENIED` depois que
algum módulo já foi aberto ([reisxd/TizenBrew#245](https://github.com/reisxd/TizenBrew/issues/245)).
Feche o TizenBrew de vez, abra de novo e vá direto ao gerenciador.

## Atualizar

O TizenBrew pede o módulo sem versão, e o jsDelivr responde com a última tag. Depois de mudar,
crie uma tag nova (`git tag -a v1.0.1 -m "..." && git push --follow-tags`).
