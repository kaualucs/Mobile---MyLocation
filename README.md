# My Location

Exercício de Persistência de dados e permissões da disciplina de Soluções Mobile (UniSATC).

App em React Native com Expo que captura a localização atual do usuário e salva no banco de dados local.

## O que foi implementado

* Persistência do tema dark mode usando AsyncStorage
* Pedido de permissão de localização usando expo-location
* Persistência da lista de localizações usando expo-sqlite. Cada localização capturada é salva no banco e aparece na lista, e ao abrir o app as localizações salvas são carregadas.

## Como rodar

```bash
npm install
npx expo start
```

Com o emulador do Android Studio aberto, aperte `a` no terminal.
