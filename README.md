# Zasady korzystania z GITa

Opiszę tu główne zasady pracy których powinniśmy używać podczas korzystania z kołowych repozytoriów.
1) Każdy projekt będzie posiadał swoje repo.
2) Każde repo będzie miało przydzieloną osobę, tzw. `Repo mastera`, który będzie za nie odpowiedzialny.
3) Każda osoba w danym projekcie dodaje swoje zmiany do brancha nazwanego w konwencji `Imię_dev` lub innej uzgodnionej z `Repo masterem`.
4) Nie dodajemy swoich commitów bezpośrednio do brancha `master`. Będzie do gałąź produkcyjna. W celu dodania zmian w `masterze` należy:
  * Zrobić commita na swojej gałęzi i pushować ją do repo
  * Wykonać pull request ze swojej gałęzi do mastera
  * `Repo master` lub osoba wyznaczona robi review kodu i decyduje o zaakceptowania pull requestu
5) Kto będzie robił syf na repozytorium, tego czeka straszna kara ;)
