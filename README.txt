1) Add jsch-0.1.31.jar
	Go to Window -> Preferences... -> Ant -> Runtime -> Classpath -> Ant Home Entries
	Click in Add External JARs and choose the jsch-0.1.31.jar file and then click OK.

2) Remote site username and password
	Pass the username and password for the remote host by the command line
	-Dusername=username -Dpassword=password
	OR	
	In Eclipse go to Run -> External Tools -> External Tools...
	and put -Dusername=username -Dpassword=password in the Arguments box.
