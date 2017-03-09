Session9
Assignment 1
1.	Why MapReduce program is needed in Pig Programming?
•	Pig is not a separate technique by which one can process the large data it’s just the toll by which one can produce MapReduce programs. It’s just a higher abstraction of the map reduce.  Pig is just a tool which has a scripting language called as the Pig Latin which is given to the pig engine with the help of the shell called as the grunt. 
•	Hence MapReduce program is needed in Pig Programming.
•	It is also true that pig cannot always used for getting the map reduce programs. Sometimes writing the map reduce programs is better than that of the Pig. Pig is basically used by the people who are no programming background.
2.	What are advantages of pig over MapReduce?
•	Decrease in development time. 
•	Learning curve is not steep, that is anyone could pick up and can write map-reduce jobs.
•	Procedural, so easier to follow the commands and provides better expressiveness in the transformation of data every step.
•	Control of the execution in every step can be achieved by writing user’s own UDF (User Defined Function) and inject in one specific part in the pipeline.
•	It is straightforward.
•	It is quite effective for unstructured and messy large datasets.
•	1/20 lines of code are needed than that map reduce.
3.	What is pig engine and what is its importance?
•	Pig Engine: It is a high-level platform for creating programs that run on Apache Hadoop. The language for this platform is called Pig Latin
•	Importance: It acts as an interpreter between Pig Latin script and MapReduce jobs. It creates environment to execute Pig scripts into series of MapReduce jobs in parallel manner.
4.	What are the modes of Pig execution?
•	There are two modes of Pig execution namely: Local Mode and MapReduce Mode.
•	Local Mode - To run Pig in local mode, you need access to a single machine; all files are installed and run using your local host and file system.
•	MapReduce Mode - To run Pig in MapReduce mode, you need access to a Hadoop cluster and HDFS installation.
5.	What is grunt shell in Pig?
•	The Grunt shell of Apache Pig is mainly used to write Pig Latin scripts.
•	Grunt shell is by which one can communicate with the pig engine.
•	Prior to that, we can invoke any shell commands using sh and fs.
6.	What are the features of Pig Latin language?
•	Procedural Data Flow Language
•	Easy to learn
•	Lesser lines of code
•	While processing data using Pig Latin, statements are the basic constructs.
7.	Is Pig Latin commands case sensitive?
•	No, the Pig Latin commands (name of parameters and all keywords) are not case sensitive.
•	The names (aliases) of relations and fields are case sensitive. The names of Pig Latin functions are case sensitive.
8.	What is a data flow language?
•	Dataflow programming languages are ones that focus on the state of the program and cause operations to occur according to any change in the state.
•	They are inherently parallel, because the operations rely on inputs that when met will cause the operation to execute.
•	In a dataflow language, you have a stream of data which is passed from instruction to instruction to be processed.
