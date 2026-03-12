# 2ND EXERCISE FOR GIT-ACTIONS

Sa se faca un workflow care sa automatizeze diferite comenzi de github(creare branch, creare fisier ,commit ,push ,PR )


1. Creaza un workflow .github/workflow/github.yaml care sa fie rulat on workflow_dispatch

   
### Workflow-ul trebuie sa faca urm operatii:
1.Sa ruleze pe ubuntu-latest

2.Cloneaza repository-ul

3.Creaza un branch nou

* 4.Creaza un fisier .txt care sa contina urm informatii:
  * run_id
  * actor
  * repository
  * te vei fol. de var. puse la dispozitie de catre github,github.run_id,github.actor,github.repository)

5.da commit la fisier si push

6.sa se faca un PR fol. gh pr create din bracnchul tau catre main(GitHub CLI | Take Gitub to the command line).Sa se adauge label-ul "github-automation" la acest PR , sa se adauge un body si un title .Daca nu exista acel label poti sa il creezi manual din interfata inainte sa rulezi workflow-ul
    
