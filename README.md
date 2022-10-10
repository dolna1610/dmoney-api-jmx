# dmoney-api-jmx

<p>This is a Jmeter Project where the DmoneyAPI is tested by creating test cases for <b>Login to user</b>, <b>Get user list</b>, <b>Create a user</b>, <b>Search the newly created user by id</b>, <b>Search the newly created user by phone number</b>, <b>Search the newly created user by email</b>
and also performing <b>Update the user phone number</b> and <b>Delete the user</b> operations. The ramp-up and the number of threads were kept as Create a user can also be used from the csv file without explicitly writing it in the body.</p>

Steps to run this project:

  - Clone this project or download the .jmx file in the project directory.
  - You can generate your own HTML summery report by running the following code in the terminal:
   ``` jmeter -n -t dmoney-load-Test.jmx -l dmoney-load-Test.csv -e -o Reports ```
   
## Whole project structure in Jmeter
   ![dmoneyload1](https://user-images.githubusercontent.com/93023509/194761666-9aa8bbb6-8852-4f90-8a16-66f25da0aab2.PNG)
 - All test cases passed can be viewed from Jmeter result tree:
    
    ![dmoneyload2](https://user-images.githubusercontent.com/93023509/194761747-5f7df269-860f-4548-8a71-e9383580fe33.PNG)

## Summery report in Jmeter.
![dmoneyload3](https://user-images.githubusercontent.com/93023509/194761792-8baffe92-83f6-4f8f-873c-c201d4ebaba1.PNG)

## HTML summery report.

![dmoneyload-4-requests-ummery](https://user-images.githubusercontent.com/93023509/194761844-fe8459bd-aaa1-44a5-be1a-4f6c556b18a4.PNG)
![dmoneyload5summery](https://user-images.githubusercontent.com/93023509/194761859-8a614253-9bf3-4126-b834-1ed2f75cdcfb.PNG)
