# To edit an existing lab:

1. Locate the GitHub repo containing the source content for the lab. If you need to determine where the existing source is, contact an admin for Learning Labs. For example, to edit the public learning lab howto at https://learninglabs.cisco.com/lab/learning-labs-howto/step/1, go to the public GitHub repo for that particular Learning Lab at  https://github.com/CiscoDevNet/devnet-writing-guidelines.
1. Fork the GitHub source of the existing lab in the CiscoDevNet organization to your namespace. For the example above, go to https://github.com/CiscoDevNet/devnet-writing-guidelines and click Fork.
1. Clone the fork to create a remote named “origin” with your fork by going to the fork. For example, with “annegentle” as the GitHub fork location, and SSH Keys already set up for my GitHub account, use this command locally:
  ```
  $ git clone git@github.com:annegentle/devnet-writing-guidelines.git
  ```
1. Create a remote named “upstream” locally:
  ``
  $ git remote add upstream git@github.com:CiscoDevNet/devnet-writing-guidelines.git
  ``
1. Check out a new branch based on the master branch:
  ```
  $ git checkout –b branch-with-edits
  ```
1. Make edits locally with your text editor.
1. Commit to the local branch. For example:
  ```
  $ git commit –a –m “Edits to the Learning Lab writing guidelines for DevNet”
  ```
1. Push your commit to the forked remote, named origin:
  ```
  $ git push origin branch-with-edits
  ```
1. Go to the GitHub website and create a pull request (PR) with edits on the fork by comparing to the upstream existing lab source. The review team meets regularly to review lab pull requests.
1. Get reviews on the PR, addressing any edit needs by pushing again to the same branch on the forked remote named origin. For example:
  ```
  $ git commit –a –m “Addresses review comments”
  $ git push origin ag-branch-with-edits
  ```
  Once the PR is merged by the reviewers, the reviewers create a release and then publish the release. The team can publish a release to staging as needed for output review.

