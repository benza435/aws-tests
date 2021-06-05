# AWS

I'm following this tutorial:
[Build a Full-Stack React Application](https://aws.amazon.com/getting-started/hands-on/build-react-app-amplify-graphql/module-one/)

The app is hosted [here](https://main.d31k6ohzuu4fcv.amplifyapp.com/) and is currently a blank(ish) React project.

I'll summarise what I'm doing for my own sanity and those who can't be arsed with the tutorial:

1. After you build a React app, bang it on Github, head over to the AWS console and find AWS Amplify.

2. Find the options for hosting a new app, get in there and link it up to your repo. You should now have a hosted app... It really is that simple.

3. Next steps are installing Amplify on my machine, wehich I've been trying to do for a while now. CONCENTRATE  
   `npm install -g @aws-amplify/cli`  
   Takes a good few mins. Failed first time around for me because of network issues or something.
4. Now run `amplify configure`  
   you'll go back and to between the web browser and command line for a bit.  
    [Here is a video explaining this step](https://www.youtube.com/watch?v=fWbM5DLh25U)  
   Don't forget to keep the keys safe, you won't be given them again for this user!

5. Go to your AWS Amplify console in the browser. Top right, orange button [new app], click it, then click create app backend. It took about 5 minutes to build and deploy before I could move on.

6. Open UI admin.... point c => then "Local Setup Instructions" is in the top corner. Copy the command and run it

7. this is becoming more like rewriting the tutorial in my own words than I had imagined.

## ABANDON SHIP

Authentication next...
https://aws.amazon.com/getting-started/hands-on/build-react-app-amplify-graphql/module-three/

## installing amplify locally

`npm install aws-amplify @aws-amplify/ui-react`  
`amplify add auth`  
`amplify push --y`  
wait 10 minutes...
