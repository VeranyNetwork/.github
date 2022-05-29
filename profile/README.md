## Hello There 👋

Trete jetzt unserem [Discord](https://dc.verany.net "Discord beitreten") bei um nichts zu verpassen!

```java

class VeranyNetwork {

     private String projectName;
     private double projectVersion;
     private int projectYear;
     private boolean projectReleased;



     public VeranyNetwork(){
         this.projectName = "Verany.net";
         this.projectVersion = 1.8;
         this.projectYear = 2022;
         this.projectReleased = false;

         if(isProjectReleased()){
             System.out.println("Join our Discord now!");
             System.out.println("dc.verany.net");
         } else {
             System.out.println("the Release is not yet.");
         }

     }

    public boolean isProjectReleased() {
        return projectReleased;
    }

    public void releaseVerany(){
         this.projectReleased = true;
         System.out.println("Verany.net has been Released!");
     }

     public void maintenanceVerany(){
         this.projectReleased = false;
         System.out.println("Verany.net is now in Maintenance!");
     }

     public void shutdownVerany(){
         System.out.println("System has been Shutdown!");
         System.exit(0);
     }
}
// programmieren macht spaß und das sehr sogar, probiert es ma aus ;)
```
