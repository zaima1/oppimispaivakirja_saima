# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Kirjoita tähän vastauksesi
vaikeainta minulle oli yhdistää branchit toisiinsa. Helpointa oli luoda branch.
kun vauhtelee haaroja hei maailman paikka muuttu nettisivulla. 
Vaikka yhdistin ne silti kun vaihtelen sivuja hei maailman paikka edelleen muuttuu. 
Paikallisessa ja etärepossa näkyy samat tiedostot. 
Siihen tuli uusi tiedosto kun kommittasin etärepon koneelle. 
Kun ne yhdisti tuli uusi tiedosto. 
Huomasin että tiimikaveri oli tehnyt muutoksia sillä
 en saanut tietoja työnnettyä ennen kuin pullasin.


## Osiossa käyttämäni Git-komennot
git add style.css| lisää valmiuteen pushata 
git commit -m " lisätty tyylit"| puskee add tiedoston
git status| näen nykyisen haaran
git branch |näen olemassa olevat haarat
git switch tyylit| vaihtaa haaraa
git branch tyylit | luo tyylit nimisen haaran 
git merge tyylit | yhdistää masterin ja tyylin
git remote add origin https-osoite | luo etärepositorion
git push origin master | synkronoi repositorion 
git fetch origin | lataa etärepon paikallis repoon
git pull orgin | vetää etäreposta tiedot 
git checkout orgin | tarkistaa originin
git merge origin | yhdistää repot 
git remote add actions https://github.com/mruonavaara/git-actions.git | lisää repositorion
git fetch actions main | ottaa gitistä tiedot koneelle 
git merge actions/main --allow-unrelated-histories | antaa tallentaa historiaa joka ei liity aiheeseen
git branch develop | luo uuden haaran nimeltään develop
git checkout develop | menee develop haaraan 
git push -u origin develop | puskee tiedot haaraan 
git add index.html | laittaa sen valmiiksi puskuun 
git commit -m "laitettu nappula"| komittaa add laitetut toiminnot ja lisää noten mitä olen tehnyt 
git push origin master | työntää etärepoon tahdyt muutokset
git pull | vetää muutokset 
git push -u origin tehtava7 | puskee haaran remoterepoon 
git branch -d tehtava7  | poistaa tehtava paikallisen haaran


| Komento | Kuvaus |
| --------| ------ |
| kirjoita tähän komento | tähän lyhyt kuvaus, mitä komento tekee |
| kirjoita tähän komento | tähän lyhyt kuvaus, mitä komento tekee |