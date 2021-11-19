# Correction TP 2

## Se connecter à *server-4.scc-edu*

```Shell
ssh server-4.scc-edu
```


## créer un utilisateur *ansible* avec comme mot de passe *ansible*

```Shell
sudo useradd ansible
sudo passwd ansible
```

> Passer outre le message d'erreur sur la qualité du mot de passe

```Shell
exit
```

## Depuis *bastion-0* copier la clef ssh sur *ansible@server-4.scc-edu*

```Shell
ssh-copy-id ansible@server-4.scc-edu
```

## Sur *server-4.scc-edu*, supprimer le mot de passe de l’utilisateur *ansible*

```Shell
ssh server-4.scc-edu
```

```Shell
sudo passwd -d ansible
```

```Shell
exit
```

## Créer un fichier nommé *inventory*


```Shell
vi inventory
```

Lien vers fichier [inventory](inventory)