
# Mano pirmoji GIT repozitorija 


Ši repozitorija skirta tam, kad išmokti naudotis GIT **projektų versijavimo kontrolės komandinės eilutės sąsaja -  (GIT CLI)**. Tam Jums reikės parsisiusti ir įsirašyti:
https://git-scm.com/downloads

## Repozitorijos parsiuntimas 
1. Atidarykite GIT CLI (git bash)
2. Naudodami komandą <cd> pakeiskite savo darbinę kategoriją į tą, kurioje norite parsiųsti repozitoriją
3. Parsisiuntę ir įsirašę GIT CLI, parsisiųskite repo
git clone https://github.com/Rkunski/test.git
4. Pakeiskite darbinę kategoriją į parsiustos repozitorijos kategoriją
cd test
## Pagrindinės komandos
 * **git add** - failų paruošimas patvirtinimui
    * **git add 'failo-pavadinimas'**  -> prideda failą nurodytų pavadinimu
    * **git add** . -> prideda visus pakitusius failus
    
 * **git diff** -> skirtumas tarp dviejų failų arba tarp to paties failo versijos
    * **git diff 'failo-pavadinimas'** - failo nurotytu pavadinimu pakitimai nuo paskutinio commit'o
    * **git status** -> parodo pakitusių failų būseną

 * **git branch** -> komanda, kuri naudojama operacijomis su šakomis
    * **git branch -a** -> parodo visas parsiustas šakas ir šiuo metu aktyvią šaką
    
 * **git commit** -> komanda skirta užtvirtinti projekto pakitimui
    * **git commit -m 'Žinutė apibūdinanti pakitimą'**
    
 * **git push** -> komanda skirta paviešinti commit'us į atitinkamą globalią šaką



