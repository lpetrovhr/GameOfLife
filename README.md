# GameOfLife
Assignment from Eloquent JavaScript

Solution for chapter_7 assignments "Artificial stupidity" and "Predators".

In comments at the and you can find another soluction, when both PlantEaters and Predators are following the wall.


Few thoughts how this game could be improved:

- by making Predators more clever, so they can hunt without losing their energy on moving around without catching anything - this could be done by Predator counting the PlantEaters and if PlantEaters number is low he could stop and hibernate(save energy) and when it comes up on certain level Predator hunts, eats and reproduce.  

- one more solution is to make PlantEaters more clever, not to eat all the plants at once and reproduce with "speed of light" I think this could be done on Predators to, if both are hungry they'll eat, if not, thay will hibernate(in this way they wouldn't die because of headless wandering around, they would die by natural death)

-  I noticed that PlantEaters are little stupid, they wander around and literally hop in Predators mouth - this could be solved if we make PlantEaters "avare" that there are predators and make them run
