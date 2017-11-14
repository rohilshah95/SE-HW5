# HW5
## Configuration Management   

### Concepts  
#### Why should developers use configuration management tools to manage their software programs? What can go wrong?  
Software Configuration Management is the task of tracking and controlling the changes in software so that if something goes wrong, it can be easily determined what change caused this failure and who made this change. Also, if some configuration is working well, SCM can replicate it across many hosts. Developers should use configuration management tools because they provide a variety of features to the developers. These include: 
  1. Configuration auditing: This ensures that all the configurations contain all their functionalities, and are in accordance with their requirements, manuals and architectural specifications.
  2. Build management: Help to manage the process used for builds
  3. Process management: Ensuring adherence to the organization's development process. 
  4. Teamwork: Help facilitate team interactions related to the process.  
  
They also help in :
  1. Reducing the redundant work
  2. Effectively manages updates
  3. Avoids configuration problems 
  4. Helps tracking defects and faults  
  
Things that can go wrong are: 
  * The wrong requirements being accepted
  * The wrong design being implemented
  * The wrong tools being used for development
  * The wrong software being tested
  * The wrong test suite being used
  * The wrong version of software being released




#### Explain the difference bewteen continuous integration, continuous delivery, and continuous deployment, in your own words.  
**Continuous Integration** is merging all the code from all the dvelopers to a central or master branch of a repository multiples times a day to avoid any conflicts in the code in the future. Continous integration enables automated building and testing so that teams can work together rapidly on a single project.

**Continuous Delivery** is the process where teams develop, build and test in short cycles where the aim is to key the code ina deployable state at any time. It does not mean that the code is complete, but the individual features that are available have been tested and are ready to deploy.

**Continuous Deployment** is the process where every change that is made is automatically deployed to the production without the need of any human supervision or human testing and debugging.

### Screencast : [Youtube](https://www.youtube.com/placeholder)  

### Steps for running Ansible and Playbook  


### References
  * https://en.wikipedia.org/wiki/Software_configuration_management
  * https://blog.feabhas.com/2011/05/what-is-configuration-management-and-why-is-it-important-to-me/
