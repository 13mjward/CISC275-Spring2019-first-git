# CISC275-Fall2018-first-git

My Repo: https://github.com/13mjward/CISC275-Spring2019-first-git

1. Create java files to make this code compile and run.

2. What five objects are created in the main?
	1. A List (ArrayList) of dogs
	2. A Dog with 4 legs named Fido
	3. A Dog with 3 legs named Fido
	4. A Dog with 4 legs named Alfie
	5. A comparator that compares animals

3. Can you spot the comparator constructor call? Where is the class definition for the comparator?
	It's in the line "Collections.sort(dogs, new Comparator<Animal>(){". 
	The class definition is in the utilities library, as shown by "import java.util.Comparator;"