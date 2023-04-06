# testTillerReact


# instructions:

opprett git repo på github
(kan godt lage gitignore preset for node allerede nå)

klon repo ned til klient
(feks gjennom vscode sin klon-repo-funksjonalitet)

npx create-react-app nameofapp

cd nameofapp

npm start 
(for å starte applikasjonen på localhost)
(ctrl + c for å avslutte)

installer prettier
(pass på at den er aktivert)

kan installere snippets
(ES7 snippets for react for eksempel)

# sette opp github:

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
(dette genererer changlog filen)
