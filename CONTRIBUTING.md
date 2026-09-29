# Cum lucrăm

## Responsabilități

- Proprietarul stabilește prioritățile și acceptă rezultatele.
- Cristian implementează, testează și documentează modificările după acceptarea invitației cu rol Write.
- Asistentul poate pregăti modificări și verifica rezultate prin accesul autorizat. Nu este un al doilea utilizator GitHub independent: operațiile pot apărea sub contul proprietarului.

## Fluxul unei sarcini

1. Creează un Issue cu obiectivul, limitele și criteriile de acceptare. Confirmă cerințele înaintea implementării.
2. Folosește o ramură separată: `feature/12-descriere`, `fix/12-descriere` sau `docs/12-descriere`.
3. Deschide devreme un Draft Pull Request și leagă Issue-ul. Păstrează schimbările mici și concentrate pe sarcină.
4. Trimite modificările la finalul fiecărei zile în care lucrezi. Actualizează Issue-ul cu progres, următorul pas și blocaje. Folosește [modelul de progres](docs/PROGRESS_UPDATE.md).
5. Completează modelul Pull Request. Furnizează pași de testare, rezultate reale și capturi sau o demonstrație dacă interfața se schimbă.
6. Solicită review când rezultatul este pregătit. Rezolvă observațiile; schimbările noi necesită o nouă aprobare.
7. Integrează doar după aprobarea cerută și acceptarea rezultatului. Închide sarcina și păstrează legătura cu livrarea.

## Protecția main

Regula activă cere Pull Request, o aprobare și rezolvarea discuțiilor; blochează ștergerea și rescrierea forțată. Nu modifica protecțiile ca să treci peste un review lipsă.

Autorul unui Pull Request nu își poate furniza propria aprobare. Modificările create prin conexiunea proprietarului pot avea nevoie de review de la alt colaborator eligibil; onboarding-ul lui Cristian rămâne necesar.

## Calitate

- Testele trebuie să acopere comportamentul schimbat și cazurile importante de eroare.
- Notează explicit verificările neefectuate și motivul. O captură nu înlocuiește testele.
- Actualizează instrucțiunile de pornire când se schimbă configurarea.
- Nu încărca parole, chei, date reale de clienți sau documente confidențiale.
- Separă mediul de test de producție. Folosește date fictive.
- Modificările care afectează accesul, datele sau publicarea includ riscurile și o metodă de revenire.

Vezi [criteriile de livrare](docs/DELIVERY.md).
