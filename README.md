# AIT

Azure integration test


Integration test that makes uses of Azure function. While this does not applies to all test scenarios but it is a step to move away from build server integration test. Build machine agents are expensive and build times can only get longer and longer. 

While you don't want every pull request to kick start a lonooog running process, this could be a way forward.

1. Execute test - Specify your test with [ExecuteTest] attribute - you write your test and assert the way you would

2. Test will generate reports - which includes test cases status (pass / fail), execution times and probably allow you to do load test. 

3. 
