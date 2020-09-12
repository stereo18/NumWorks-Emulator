<p align="center"><img src="icon.png" width="150px" draggable="false" height="150px"></p>

<h1 align="center">NumWorks Emulator</h1>



<p align="center">L'émulateur de la calculatrice NumWorks basé sur l'émulateur en ligne !</p>
<a align="center" href="https://www.numworks.com/" target="_blank"><p align="center">Cliquez ici pour acceder au site de NumWorks</p></a>

![TuTune Player](https://i.imgur.com/eAtF8BO.png)

## Téléchargement

Vous pouvez le télécharger pour windows depuis les [GitHub Releases](https://github.com/stereo18/NumWorks-Emulator/releases). Pour les autres plateformes, veuillez suivre le guide de dévelopement et build pour votre OS.

## Console

Pour utiliser la console de devellopement de l'environnement chromium :

```console
ctrl + shift + i
```

## Developement

### Pré-requis

**Nécessaire**

* Node.js v12
* Dépendances disponibles avec ```npm install```

---

**clone et installation des dépendances**

```console
> git clone https://github.com/stereo18/NumWorks-Emulator.git
> cd NumWorks-Emulator
> npm install
```

---

**Lancer l'application**

```console
> npm start
```

---

**Fabriquer l'application**

Pour build sur votre plateforme actuelle.

```console
> npm run dist
```

Faire pour une plateforme spécifique.

| Platform    | Command              |
| ----------- | -------------------- |
| Windows x64 | `npm run dist:win`   |
| macOS       | `npm run dist:mac`   |
| Linux x64   | `npm run dist:linux` |



### Sources.

Les flux sont lus depuis les serveur de distribution respectif des radios présentées et l'application est basée sur le [heliosLauncher](https://github.com/dscalzi/helioslauncher)
