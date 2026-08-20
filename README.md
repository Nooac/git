***Git Tehtävä
***1.	Mitä versiohallinalla tarkoitetaan?
Versiohalinalla tarkoitetaan työkalua, jolla seurataan ohjelmistokoodin muutoksia ja   tehdään yhteistyötä.
***2.	Mikä on Git-versiohallinta ja mikä on sen historia
Git-versiohallinta on ilmainen ja avoimen lähdekoodin hajautettu versionhallintajärjestelmä, jonka loi Linus Torvalds vuonna 2005 Linux-ytimen kehitystä varten, kun aiempi kaupallinen BitKeeper-järjestelmä ei enää sopinut ilmaiseen käyttöön. ilmainen ja avoimen lähdekoodin hajautettu
***3.	Selitä Git:n vesiohallinan tärkeimmät komennot sen peruskäytössä
Git-versionhallinnan tärkeimmät peruskomennot ovat:
( git innit ), ( git status), ( git add ), (git commit ), ( git push ), ( git pull )

***4.	Mitkä ovat mielestäsi Git versiohallinan tärkeimmät komennot 5 komentoa
1.	git log  --oneline
2.	git status
3.	git commit -m ” Tekstiä”
4.	git branch
5.	git merge

***5.	Mikä on muutoksen (commit) ottamisen prosessi?
1.	Tarkista tilanne: git status
2.	Valitse tiedostot: git add tiedostonimi.txt
3.	Tallenna muutos: git commit -m ”Tein muutoksia”

***6.	Mikä on muutoksen perumisen prosessi ja siihen liittyvät komennot
Jos ehdit jo tehdä commitin, mutta et ole vielä pushannut sitä etäpalvelimelle, käytä reset-komentoa. Mutta jos olet, niin käytä komentoa git revert [commit-id]
***7.	Luo Kuva/kaavio gittin käytöstä esm https://www.tidraw.com/ avulla 
<img width="358" height="243" alt="Kuva1" src="https://github.com/user-attachments/assets/fe4a2b4f-9533-453c-bda8-c0084f7ff2e6" />
***Tai
<img width="357" height="287" alt="Kuva2" src="https://github.com/user-attachments/assets/167e1c1f-8273-4a65-ad4c-deec562bfe08" />
***8.	Piirrä kaavioon työhakemisto git indeksi ja .git tietokanta ja sen miten muutos etenee työhakemistosta .git tietokantaan kirjoita myös asiaan kuuluvat git komennot
<img width="501" height="247" alt="Kuva3" src="https://github.com/user-attachments/assets/5c7d754c-5ec5-448b-8e1b-06d8fd9a4b71" />
***Extra: Missä voi tiedoston muotoa käyttää?
Markdown-tiedostomuotoa voi käyttää verkkosivujen, dokumenttien, muistiinpanojen, kirjojen, esitysten, sähköpostien ja teknisen dokumentaation tekemiseen.
