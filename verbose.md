#***Testing***

###**Unit Testing:**
Unit Testing is testing the software by unit wich are seperated code blocks by functions, clases or blocks. The reason of seperating code is isolating the code blocks for getting accuracy and understanding the errors correctly. Some thirdparty libraries and frameworks like CppUtest, googleTest or Unity helps the unit testing process. For easy start basic assert libraries might be useful.

###**HIL Testing:**
Hardware in Loop testing  making hardware testing under a loop with bluepill and sensor datas. This testing are mostly became more useful with other proceses like profiling and testing.

###**Somke Testing:**
Testing Software quickly after every feature. in every little changes testing the software helps understanding the errors directly. In smoke testing none of the ci/cd proceses are using. 

###**Mock:**
A fake (fake is different for understanding) function, object or class for seperating target code for dependecies. if a function is depended to sensor datas, you can't get this data in test steps, but you can mock it. some tools are helpful for this process like Unity, Cmocka, CppUtest or PlatformIO.

###**Integration Test:**
Integration test is testing software(s) for checking if target software(s) is/are integrated correctly. Like UI and Backend might not be work correctly after some uptates even if they was work correctly.

###**Performance Tests:**
Performance tests are understanding of the performance of software. It has some subtests like load test, (normal), stress tests (pushing softwares to limits, or over the limits), or scability tests (giving more resource to program than expected).

#***Deployment***

###**Deployment:**
Sharing and deploying the program if it's ready. There are few methods like green-blue deployment (old version is blue, new is green. direct the program to green, if there are no errors delete blue and make green blue) or canary deployment (before deploying full version of project, some groups access the new version for getting feedback).

#***Profiling***

###**Profiling:**
Profiling means understanding the workdflow of the program with some features like "total time passed for the target functions" or "usage of ram", "usage of cpu". In some ways profiling might define of analysis of the project with some attributes (compiled with specific flags) wich are helps the getting logs and reports after the test. Profiling seeks lot of features like "memory leak" (some tools do it, example: valgrind) or other features help the improvment the efficiency, security and productivity of the software.

#***Keywords***

###**Verbose:**
verbose means "more detailed" such as more detailed log output. Like in profiling or testing verbose feature makes the output more detailed. might seen as "-v" flag or "verbose=true" attribute in some ways in computer science and engineering about software/middleware.