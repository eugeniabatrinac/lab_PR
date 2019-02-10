Laboratorul 1

Majoritate comenzilor utilizate le-am atasat in repozitoriul lab_PR u in forma de imagini cu extensia png.

Initial am instalat sistemul de control al versiunilor: GIT

Apoi am creat un directoriu local, aici am ales prin interface.

Am initializat repozitorul GIT in acest director prin  comanda git init.

Cele mai multe dificultati le-am intilnit din cauza ca din start, la instalarea git nu am configurat, indicind numele si email 
ca mai apoi sa fac aces lucru prin comenzile:
git config --global user.name "Eugenia Batrinac "
git config --global user.email eugenia.batrinac@gmail.com

Am adaugat repozitoriul distant git remote add origin
Dar eu am am facu rename in destination din motiv ca nu puteam face push
Apoi am  reinoit repozitoriul distant cu ajutorul comenzii  git push -u destination master

Am creat o ramura noua de dezvoltare dev: git branch dev

Am trecut in ramura nou creata: git checkout dev

Am reinnoit repozitoriul distant: git push-u destination dev

In sfirsit am unificat ramurile: git merge dev 



