# Run the jar file locally

1.	Have the JDK (17 or above) installed on your machine 

2.	Download the client application jar file from my github: https://github.com/abdelhadi-oulgour/ClientEnhancedUDP-Jar

3.	Download the SDK of JavaFX (version 17.0.3) from: https://gluonhq.com/products/javafx/

4.	Run the following command, replacing “`/path/to/javafx-sdk/lib`” by your own javafx sdk directory previously downloaded:
   `java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml   -jar ClientEnhancedUDP.jar`
