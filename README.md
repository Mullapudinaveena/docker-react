view the application:
http://dockerreact-env.eba-jnrka337.us-east-2.elasticbeanstalk.com/

work-flow of the application:
1. Commit code changes to Development branch(Github).
2. Using pull request update the Master branch(Github).
3. Once the master branch is updated Travis-ci(continuous integration service) starts to build the project.
4. Once the build is successful the code is deployed to AWS ELasticbeanstalk environment and the code is stored in a S3 bucket.
5. Now the application is available to the end user.


