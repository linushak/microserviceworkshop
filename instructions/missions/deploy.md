## Mission 1. Deploy your first fighter! ##

![Mission1](MapDeployMission.PNG)

Before you start your first mission, make sure you are ready as per below 

- [x] You understand the goal of the workshop
- [x] You have grouped together with your squad
- [x] You have recieved your squad's Identitiy Domain, the username and the password
- [x] You have selected which weapon you, as a member of your squad, will be using
- [x] You are able to clone the source code of your weapon to your local machine. Either by ```git clone``` command or with an IDE with Git support.

### Mission Description ###

In order to take up the battle against the Death Star, your squad would need to deploy at least one fighter (microservice) to the cloud. 

### Mission Awards ###

- Maximum number of points for this mission: **100**
- Lesser points will be given to subsequent squads.

### Mission Instructions ###

1. To deploy your fighter, you will select and use one of two deployment strategies.
+ Deployment strategy is completely up to your preference. Every squad member can have the same or different type of deployment strategy.
+ In short, the **Continuous Integration and Deployment** strategy means that you push the code from your local machine to the Git repository. Oracle Developer Cloud will then automatically build, package and deploy your application to Application Container Cloud. The **manual** approach means that you build and zip your application locally and then deploy that zip file in the Application Container Cloud user interface. This requires that you have the correct build tools installed on your local machine (Maven and JDK for Java, Ruby (interpreter) and Bundler for Ruby and NPM for Node.js).
+ Select your preferred deployment strategy by clicking them below. If you change your mind you can go back here and select another deployment strategy.

| [![Continuous](../cicd.png)](../deployment/cicd.md)  | [![Manual](../manually.png)](../deployment/manually.md)
|:---:|:---:

2. Monitor the Death Star dashboard to await your fighter being deployed! If you can't see the Dashboad well on the projector, just open the URL from the Excel document. Your fighter should appear in the dashboard and complete it's first strike to the Death Star!

### Next: Second Mission ###

If your microservice is already up and running [click here](scale.md) to continue on with the next mission!

![Mission1](MapDeployMission.PNG)

