# Inital setup and upload with git and GitHub. Written mainly for Windows.

1. Get a GitHub account

	1. http://github.com/

2. Create GitHub repository

	```Repositories -> New```
    
    ```Repository Name: helloWorld```
    
    ```Description: Initial GitHub Repository```

3. Install local application from:

	1. http://git-scm.com/downloads

4. Create location/directory on local drive for all git projects

	```mkdir \Users\Owner\Documents\git```

5. Create a location/directory on local drive for project

	```mkdir \Users\Owner\Documents\git\helloWorld```

6. Change to project directory

	```cd \Users\Owner\Documents\git\helloWorld```

7. Initalize local repository

	```git init```

8. Create local files

	```echo Hello World!!! > README```
    
	```echo ^<!DOCTYPE HTML^>^<html^>^<body^>Hello World!!!^</body^>^</html^> > hello.html```

9. Add local files to repository

	```git add README```
    
    ```git add hello.html```

10. Commit local files to repository "Change comment with reason for each commit"

    ```git commit -m "Inital Commit"```
    
11. Add remote information for repository. Change user name as needed.

	```git remote add origin https://github.com/djlerman/helloWorld.git```    
    
12. Push latest commit to remote repository

	```git push origin master```








