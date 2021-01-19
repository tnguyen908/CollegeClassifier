Application is in a file called "CollegeApplicantClassifier-1.jar". Double click to run application.
*Need JAVA to run application*

Unit test in test directory

If on Windows please follow these steps to run application:
    1) Open a notepad.exe
    2) Write : java -jar CollegeApplicantClassifier-1.jar
    3) Save it with the extension .bat
    4) Copy it to the directory which has the .jar file
    5) Double click it to run your .jar file

Assumptions:
    -The team that is retrieving the data also does data validation (no empty fields, valid data such as String for name and number of age..etc)
    -Also data coming in is in the format:
        {
            "firstName": (String) firstName,
            "lastName": (String) lastName,
            "state": (String) state,
            "age": (Integer) age,
            "gpa": (Double) gpa,
            "gpaScale": (Double) gpaScale,
            "satScores": (Integer) satScores,
            "actScores": (Integer) actScores,
            "felonies": (Integer) felonies,
            "recentYearOfFelony", (Integer) recentYearOfFelony
        }
    -If had to do data validation based of some requirement, who implement that in separate class and would throw custom exceptions.
    -First and Last name only contain alphabets