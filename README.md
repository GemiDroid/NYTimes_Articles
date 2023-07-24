<h2 align="center">NewYork Times Article App</h2>

### Technologies and pattern:
- Applying Clean architecture-> Dividing code to (data layer, domain layer(UseCases) and presentation layer).
- MVP: Model-View-Presenter-> For dealing with data layer and presentation layer.
- RxJava & RxAndroid-> For asynchronous operations 
- Retrofit-> For dealing with webServices and OkHTTP requests.
- UI Testing-> By using Espresso, I applied some tests on UI.
- Unit Testing-> By using JUnit, I created test cases and made assertion to test.
- CICD: Conitious Integration/Conitious Delivery-> For building, validating and releasing by using CircleCI.

### How to test UI test:
- Navigate to src/test.
- Navigate to java, then open com.example.newyorktimearticles.presentation.ui.
- Run 2 UI tests.

### How to test unit test:
- Navigate to src/androidTest.
- Navigate to java, then open com.example.newyorktimearticles.presentation.presenter.
- Run 1 Unit test.

### Finally:
- It's used by Kotlin not Java.
- Resource: https://play.kotlinlang.org/.
