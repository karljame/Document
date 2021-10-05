## Install Tailwindcss 

 Kui ma hakkasin installima tailwindcss siis tuli suht palju probleeme ette ja stuff mida ma peasin muutma 

## Getting Started

    link kus install tailwindcss (https://tailwindcss.com/docs/installation)
    video mis help mul install (https://www.youtube.com/watch?v=9XeewBRtDKE)

### probleemid mis tulid ette 

    1."npm install -g npx" user polnud permissoneid 

        Solution: vaatates et see on mingi install siis ma lihsalt läksin ROOT accounte (sudo su) ja install lihsalt seal ja välja saada kirjutasin (exit) ja olin tagasi ennda user accountis 

    2.nodejs new update mis install ei läinud ubuntu peale 

        solution: ma install (curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash) see install sulle NVM ja seal sa võid valida mis version sa tahad with (source ~/.bashrc) ja (nvm --version) sa nvm version ei pea kasutama aga see näitab sulle mis verison sulle on install ennda desktop peal. Ja lõpuks panin (nvm install 16.10.0) ja see tegi korrda selle 

    3. Package.json ei tulnud 

        Solution: install uuesti lihsalt (npm install -D tailwindcss@latest postcss@latest autoprefixer@latest)
