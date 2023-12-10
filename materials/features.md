# 1. Requirements Overview
## 1.1 What is OWLS - Operating with Lecturers & Students?
![Main Features of OWLS](images/main-features.png)
## 1.2 Quality Goals
![Quality Goals](images/quality-goals.png)
## 1.3 Stakeholder
![Stakeholder](images/stakeholder.png)

# 2. Architecture Constraints
## 2.1 Architecture Constraints
![Architecture Constraints](images/architecture_contstraints.png)
## 2.2 Business Context
![Business Context](images/business_context.png)
## 2.3 Architecture Decisions
Looking at architecture from different angles to get more viewpoints and decide on a proper solution.
![Architecture Decisions](images/architecture-decisions.png)

# 3. Solution Strategy
Recognizing difficulties and finding solutions for our goals.
![Solution Strategy](images/solution-strategy.png)

# 4. Building Block View
## 4.1 Level 1
![Level 1](images/Level1.png)
## 4.2 Level 2
![Level 2 Timetable](images/Level2Timetable.png)
## 4.3 Level 3
![Level 3 TimetableController](images/Level3TimetableController.png)

# 5. Runtime View
## 5.1 Lektor krank
Lektor meldet sich krank beim Systemadministrator, der Timetable muss angepasst werden.
![Lektor krank](images/Lektor_krank.png)
## 5.2 Harald zahlt
Ein neues Studiensemester beginnt, Harald, ein Student, muss seine Studiengebühren für das kommende Semester bezahlen.
![Harald zahlt](images/Harald_zahlt.png)

# 6. Deployment View
## 6.1 CAP-Theorem
Ein CP System ist für OWLS am Besten geeignet. <br>
<strong>Consistency</strong> verfügbar ist in allen Systemen. Wenn ein Lektor sich krankmeldet und der Systemadmin den Stundenplan anpasst, wird dieser sofort für alle Nutzer aktualisiert. Ebenso passiert dies bei Website Anpassungen. Für eine bessere <strong>Consistency</strong> wird ein to-face-commit implementiert um beispielsweise die Noten der Studenten fehlerfrei anzeigen zu lassen. <br>
Ebenso wichtig für uns ist <strong>Partitioning</strong>, da unser System nach einem Netzwerkausfall nicht weiterarbeiten kann und <strong>Partitioning</strong> zwingend notwendig ist für einen two-face-commit.<br>
<strong>Availability</strong> ist weniger wichtig, da bei Ausfall des Clients eine Datenpräservation nicht von besonders hoher Importanz ist. Wie in 5.2 erwähnt, brauchen wir für Updates unseres Systems einen gewissen Platz zum Atmen um diese vollständig zu implementieren. Hierfür würde allerdings das System für einige Zeit unverfügbar sein, was allerdings kein Problem sein sollte. OWLS wird bereitgestellt für Universitäten mit rund 5.000 Schülern von denen sich der Großteil in derselben Zeitzone befindet. 
## 6.2 Deployment Diagram
![Deployment Diagram](images/deployment-diagram.png)

# 7. Crosscutting Concepts
![Crosscutting Concepts](images/crosscutting-concepts.png)

# 8. Decisions
![Decisions](images/decisions.png)

# 9. Quality
## 9.1 Quality Goals and Scenarios
![Quality Goals and Scenarios](images/QualityGoalsScenarios.png)
## 9.2 Quality Tree
![Quality Tree](images/QualityTree.png)

# 10. Risks and Technical Debt
Recognizing risks with our architectural decision and suggesting measures to minimize the the technical debt.
![Risks and Technical Debt](images/technical-debt.png)

# 11. Glossary
