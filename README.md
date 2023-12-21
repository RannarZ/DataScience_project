# LLM based course finder

This is a project by Anton Berik and Rannar Zirk. The motivation for this project is that the courses in ÕIS II are very well hidden and it is very difficult to discover new courses. Goal of the project is to make it a lot easier to discover new courses and to also find certain courses.

The project contains an .ipynb file, which has the main product in it. Then there is a tokenCount.json file, which keeps track of the tokens got from GPT model. Then there are some .txt files: kõik_uuid.txt contains uuids of every course in ÕIS II, kõik_võtmed.txt contains every course's key in ÕIS II, uus_kõik_võtmed.txt contains every key of a bachelor's level course in it and finally sample.txt contains a sample embedding vector, which we used to test the distance finding algorithm. We also have some folders in our project: folder Ained contains descriptions of every course in ÕIS II, folder Ained_kod contains embedding vectors of each bachelor's course in ÕIS II and Bach_courses include every bachelor's level course's description in it. All of the entities in the folders are .txt files, which have the course's name and key as the file name. 

The project works on GPT 3.5 model and is aimed for bachelor's students. 

Currently it is usable only via the .ipynb file where it is mandatory to run the blocks that have a mark for running and at the end there is a prototype block where you can type an input. After typing an input the GPT model does it's magic and the user will get 10 courses that fit the best to his/her request. Current model works only in Estonian.
