Queuing System in JS

file description

0. Download, extract, and compile the latest stable Redis version (higher than 5.0.7 - https://redis.io/download/):
1. Using Babel and ES6, write a script named 0-redis_client.js. It should connect to the Redis server running on your machine
2. n a file 1-redis_op.js, copy the code you previously wrote (0-redis_client.js), Add two functions:
3. In a file 2-redis_op_async.js, let’s copy the code from the previous exercise (1-redis_op.js),Using promisify, modify the function displaySchoolValue to use ES6 async / await, Same result as 1-redis_op.js
4. In a file named 4-redis_advanced_op.js, let’s use the client to store a hash value
5. In a file named 5-subscriber.js, create a redis client:
6. In a file named 6-job_creator.js:, Create a queue with Kue, and Create an object containing the Job data with the following format:
7. n a file named 6-job_processor.js:, Create a queue with Kue,and Create a function named sendNotification.
8. n a file named 7-job_creator.js: Create an array jobs with the following data inside.
9. In a file named 7-job_processor.js: Create an array that will contain the blacklisted phone numbers. Add in it 4153518780 and 4153518781 - these 2 numbers will be blacklisted by our jobs processor.
10. In a file named 8-job.js, create a function named createPushNotificationsJobs
11. Now that you created a job creator, let’s add tests:
12. Create an array listProducts containing the list of the following products
13. Create a Redic client:Create a function reserveSeat, that will take into argument number, and set the key available_seats with the number
