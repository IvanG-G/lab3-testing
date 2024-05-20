# lab3-testing

###Test  1 

<img width="740" alt="image" src="https://github.com/IvanG-G/lab3-testing/assets/138608967/854d3882-6b37-4bb5-bb4d-12b37daa1c59">

In this test we were testing 2 functionality of the code, we need to focus on test 1 only one thing in each test, thats why I split them into to test, adding them a descriptive name



### Test 2 

<img width="737" alt="image" src="https://github.com/IvanG-G/lab3-testing/assets/138608967/54477dfe-69e8-4038-9a44-cc8ae24a940a">

In this test occurs the same thing that in test #1, I split them into 2 test cases, and one should receive an exception, so, we dont need a try catch, also, removed the assertEquals and replaced with assertThrows.



### Test 3

<img width="737" alt="image" src="https://github.com/IvanG-G/lab3-testing/assets/138608967/edb0d4fe-eeff-44f7-a410-12c036aa5983">

In this test case we had no opportunity to test the method adjustsToScreenSize, because were initialized on 1024, so we dont know if it works propperly, i use a variable named width, and initialized the component with a width of 10, after that i use the method adjustsToScreenSize and instead of using assertTrue, im using assertEquals, comparing the initial variable witdh to the widht of the component.
