### To be used in case of importing existing project.

1. Start by cloning the project into local machine.
2. Open intellij and click on open existing project. <br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img width="250" alt="image" src="https://user-images.githubusercontent.com/34827180/222455799-14692b98-d101-4e7d-b797-170dbf0eaef3.png">

3. In case of multiple repos clone them in a single folder and select that folder and open.
4. Now you'll see all repos in intellij which are in the project but they'll not have any blue box on the folder as shown below.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img width="22" alt="image" src="https://user-images.githubusercontent.com/34827180/222457053-62c18d23-e893-49e4-991e-0ca4484934af.png">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<- should be like ->
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img width="22" alt="image" src="https://user-images.githubusercontent.com/34827180/222457491-c5e84c6e-1dda-4555-97b1-0ee87a7d7400.png">

5. To do this go to "File" icon on the top left in mac and select project structure.
6. In Project - Select the SDK as per the java installation in your system and language level as per java version.
7. In Modules - Click on "Import Module" and select the same parent folder which contains all the repos.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img width="212" alt="image" src="https://user-images.githubusercontent.com/34827180/222458999-10bb6693-9475-4715-aa84-b3681880bd04.png">

8. Now click on "Import module from external model" and select maven.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img width="500" alt="image" src="https://user-images.githubusercontent.com/34827180/222459659-1954b220-f630-444e-862a-bf8db606699e.png">

9. I'll automatically scan all the folders and see the pom files and import seamlessly.
10. By clicking on save you should now see the blue box icon on your folders on the left hand side and with this the setup is almost done.
11. Now you can create configurations to run your files, Process is straightforward in case of any arguments like ```-DskipTests=true``` put them in VM Options block.
12. Your setup is now complete go ahead and run your project through the play or debug button.
