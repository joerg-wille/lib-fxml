Welcome to `Lib-FXML` with the new release `0.2.0-PRERELEASE`.

`Lib-FXML` allows the developer to load [JavaFX] relevant files (.fxml, .css, .properties) 
and connect them to a controller (called the presenter).



#### Summary
* Extend the api from Lib-FXML with more methods, tests and internal validations.
* Prepare the documentation for the future releases.



#### Feature



#### Enhancement
#39 [api] Attribut 'baseBundleName' should be 'optional' in FXMLView.
#38 [api] Attribut 'urlForFXML' should be a 'must existing' in FXMLView.
#37 [api] Change FXMLPresenter to abstract class.
#29 [api] Extend the class FXMLView by error with msg from LoggerFacade.
#28 [api] Extend the method FXMLModel.get(String, Class'T').
#27 [api] Create new factory method FXMLView.create(String, FXMLModel).
#26 [test] Extend the class MyFXMLTest with functionalities to show the .fxml as gui.



#### Bug
#25 [test] Test resources (.css, .fxml, .properties) will be copied in the generated .jar file.



#### Documentation
#40 [doc] Extend the topics in the GitHub project.
#35 [doc] Create JavaDoc in folder 'doc/apidocs'.
#23 [doc] Create new concept 'Examples'.
#17 [doc] Create new concept 'Features'.
#16 [doc] Create new concept 'Conventions'.



#### Refactoring
#36 [api] Change in FXMLModel toString() the term 'data' to 'model'.



#### Additional



Greetings
Naoghuman



[//]: # (Issues which will be integrated in this release)



[//]: # (Links)
[JavaFX]:http://docs.oracle.com/javase/8/javase-clienttechnologies.htm
