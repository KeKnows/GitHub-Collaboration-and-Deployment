#A. What triggers this workflow to run? (Look at the on: section)
  #The workflow is triggered by the on: section in the deploy.yml.
  #It runs when code is pushed to the main branch.
  
#B. What are the four main steps this workflow performs? (List each step name)
  #Checkout code, Set up environment, Build Project, Deploy Application
  
#C. What does the "Checkout code" step do and why is it necessary?
  #The checkout code step uses the actions/checkout action to pull the repository's contents into the workflow runner. 
  #Without it the repository's files can't be accessed by the workflow.
  
#D. What is the purpose of the environment configuration?
  #It ensures that the workflow has the correct runtime, dependencies, and environment variables needed for deployment. 
  
#E. How does this automated deployment improve reliability compared to manual deployment?
  #It eliminates human error in repetitive tasks, runs tests and builds steps consistently before deployment and takes logs so we can debug. 
  
#F. What would happen if you pushed code to a different branch (not main)?
  #The workflow would not run correctly, and the other branches would still need to be merged into the main before being deployed. 
