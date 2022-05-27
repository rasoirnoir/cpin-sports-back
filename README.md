# cpin-sports-back

Backend for cpin-sports, une appli pour aider à se remettre au sport

# Conception fonctionnelle

## scénarios d'utilisation

Depuus cette application, un utilisateur doit pouvoir :

- se connecter à son compte
- créer des programmes d'entrainement
- créer des exercices
- lancer un programme.

Programme
: C'est une série d'exercices qui s'enchaînent.
Un programme est constitué d'un nom, d'une liste d'exercices, et d'un propriétaire

Exercice
: C'est une partie d'un programme. Il correspond à un geste physique de l'utilisateur.
Il est constitué d'un nom, d'un temps ou nombre d'execution, et un propriétaire. Il peut être lié à un programme.
