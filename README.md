# testTillerReact


# instructions:

opprett git repo på github
(kan godt lage gitignore preset for node allerede nå)

klon repo ned til klient
(feks gjennom vscode sin klon-repo-funksjonalitet)

npx create-react-app nameofapp
(https://create-react-app.dev/docs/getting-started/)

cd nameofapp

npm start 
(for å starte applikasjonen på localhost)
(ctrl + c for å avslutte)

installer prettier
(pass på at den er aktivert)
Dette ved å redigere settings.json med å legge til " "editor.defaultFormatter": "esbenp.prettier-vscode" "

kan installere snippets
(ES7 snippets for react for eksempel)

# sette opp github med agile-metodikk:

https://youtube.com/playlist?list=PL-DdwrWUDZnP-VXXLxP2eg7QcTsMav_6s

opprett prosjekt, kan godt velge feature template
endre iterations til sprint
kan også sette opp workflow for å automatisk legge til issues


# sette opp automatisk gen av changelog

npm install --save-dev standard-version
legg til i npm package.json:
"scripts": {
  "release": "standard-version"
}

npm run release
(dette genererer changlog filen, men pusher ikke til github)

