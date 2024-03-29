# POO-2

Programare avansata pe obiecte - Programare stomatolog

Acțiuni/Interogari
- Adaugare specializare: GestionarePersoane.adaugaSpecializare
- Adaugare persoana (Pacient sau Stomatolog): GestionarePersoane.adaugaPersoana
- Adaugare programare: GestionareProgramari.adaugaProgramare
- Selectare toti stomatologii ordonati dupa nume si prenume: GestionarePersoane.getStomatologi
- Selectare toti pacientii ordonati dupa nume si prenume: GestionarePersoane.getPacienti
- Selectare un stomatolog dupa cod parafa: GestionarePersoane.getParafa
- Selectare un pacient dupa cnp: GestionarePersoane.getCnp
- Anulare programare: GestionareProgramari.anuleazaProgramare
- Selectarea programarilor unui stomatolog dintr-o zi ordonata crescator dupa ora: GestionareProgramari.getProgramari
- Selectarea tuturor programarilor unui pacient: GestionareProgramari.getToateProgramariPacient
- Selectarea tuturor stomatologilor dupa o specializare ordonati dupa nume si prenume: GestionarePersoane.getStomatologiSpecializare
- Start operatii aplicatie: GestionareCabinetMedical.startExecutareaOperatilorAplicatiei

Clase/Interfete

- Persoana
    - Pacient
    - Stomatolog
- Programare
- SpecializareStomatolog
- Main
- GestionarePersoane (interfata)
    - GestionarePersoaneInMemorie
- GestionareProgramari (interfata)
    - GestionareProgramariInMemorie
- DataOraProgramariiComparator
- Constante
- NumePrenumeComparator
- GestionareCabinetMedical (interfata)
    - GestionareCabinetMedicalInMemorie
