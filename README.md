# Living Timetable

Family Planner 2.0 – AI-powered daily organization with LangChain4j and OpenAI Function Calling: Automate calendar and other timetable queries for family and leisure with just a voice command.

This repository is based on [LangChain4j Tools](https://docs.langchain4j.dev/tutorials/tools/) (implementation of [OpenAI Function Calling](https://platform.openai.com/docs/guides/function-calling)).

![Overview](docs/sc_overview.png)

## Calculator Integration with LangChain4j

The sample in the repository is based on the `ServiceWithToolsExample` calculator example of the [LangChain4j examples repository](https://github.com/langchain4j/langchain4j-examples/blob/main/other-examples/src/main/java/ServiceWithToolsExample.java).

![Sequence Diagram](docs/sq_calculator.png)

## Run the demos

* Web application with sample HTTP requests
  * Start `LivingTimetableApplication`
  * Execute `src/test/resources/testsuite.http` with IntelliJ HTTP client  
* Spring Boot Integration Tests of calculator example
  * Execute `ServiceWithToolsExample` as JUnit test 


