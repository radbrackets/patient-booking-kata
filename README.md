# Domain

We are going to develop application which will support doctor in organise
day full of patient visits. Every doctor will admit patient in the asign room on given day.
Every patient will have 30 minutes(that should be configurable) on visit.


# Requirements

* Patient can reserve visit on given time which is correlated with visit time
  * eg. visit time = 30m, times when visit can be made 8:00, 8:30, 9:00...15:30
* Can't reserve visit on same time by 2 patient to same doctor
* When patient cancel visit we would like to propose reschedule for patient depend on: 
  * Visit frequency
  * Age of patient
  * Patient without no show on any visit
  * Planned visit is at least 1 week from now
* Visit can be canceled at most 24h before without reason
  * Visit can cancel at most 2h that require to provide a reason
  * In 2h to the visit, cancellation a visit is noted as no-show


