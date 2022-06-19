# Lighthouse-Demo 
<img align='right' src='https://cdn-icons-png.flaticon.com/512/3534/3534479.png' width='200"'>

Google Light House Integration with Github Actions 

**Lighthouse Check Action for automating Lighthouse audits. It can be used within a workflow - triggered by any event. This post will demonstrate how to use the action when triggered by a pull request event.**

**Basic Example**
With the following steps we can create a basic workflow.

- Create and checkout a new branch locally.
- Create a file in your project with a path similar to the following .github/workflows/my-workflow.yml (replacing my-workflow with any name of your choice).
- Populate the file from above with the example shown below, replacing the urls field with a comma separated list of the URLs you’d like to test.
- Commit changes locally and push the branch up to your remote.
- From your new branch, open a pull request.
