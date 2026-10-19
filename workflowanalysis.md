What triggers this workflow to run? (Look at the on: section)
  push events to the main branch
What are the four main steps this workflow performs? (List each step name)
  1.checkout code
  2.setup node
  3. install dependencies
  4. deploy to github pages
What does the "Checkout code" step do and why is it necessary?
  It downloads your repository's code onto the virtual server runner so that         subsequent steps can access, build, and test actual project files
What is the purpose of the environment configuration?
  It sets up the correct runtime environment 
How does this automated deployment improve reliability compared to manual deployment?
  It ensures that every change goes through automated checks
What would happen if you pushed code to a different branch (not main)?
  Because the workflow is configured to only trigger on pushes to main, pushing code to a different branch will run local tests or skip the production deployment workflow entirely until it is merged into main
