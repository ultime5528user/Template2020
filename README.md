# Template 2020

> **Attention!** Ce projet correspond aux changements annoncés pour 2020 en date du 25 octobre 2019. Les changements finaux peuvent différer de ce qui est présenté dans ce projet. Le template officiel devrait être utilisé à partir de janvier 2020. 

Ce projet permet de débuter un projet FRC de type *Command Based* en respectant les nouveaux standards de 2020. Il est basé en grande partie sur le [template officiel de WPILibJ](https://github.com/wpilibsuite/allwpilib/tree/master/wpilibjExamples/src/main/java/edu/wpi/first/wpilibj/templates/commandbased).

Pour l'utiliser :
1. Téléchargez le projet en format `.zip` et extraire son contenu.
2. Ouvrir le dossier avec `FRC VS Code` ([installation](http://docs.wpilib.org/en/latest/docs/getting-started/getting-started-frc-control-system/wpilib-setup.html)).
3. Cliquer sur l'icône WPILib, sélectionner l'option `WPILib: Set Team Number` et saisisser votre numéro d'équipe.
4. Fermer VS Code et rouvrir votre projet.
5. Si l'avertissement :warning: `Classpath is incomplete. Only syntax errors will be reported.` apparaît, fermer à nouveau VS Code et rouvrir votre projet.

*****

Afin d'utiliser le nouveau *Command Framework*, ce projet utilise la librairie [command-rewrite-jitpack](https://github.com/Oblarg/command-rewrite-jitpack) via [jitpack.io](https://jitpack.io/). Cette dépendance est ajouté dans le fichier `build.gradle` du projet.

Sources :
- https://www.chiefdelphi.com/t/command-framework-rewrite-early-access/359418
- http://docs.wpilib.org/en/latest/docs/software/commandbased/index.html
- https://github.com/wpilibsuite/allwpilib/tree/master/wpilibjExamples/src/main/java/edu/wpi/first/wpilibj/templates/commandbased
