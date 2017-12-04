# To publish a lab:

To publish a lab, the repo must be in the CiscoDevNet namespace on GitHub. Often this requirement means the author should fork their repo to CiscoDevNet.

1. Go to the repo where the labs is stored.
1. Create a release. The numbering should follow x.y or x.y.z versioning that is meaningful to the learning labs author.
1. Log in to the appropriate server (production or [staging](https://learninglabs.cisco.com:8867)). Staging requires a Cisco VPN connection.
1. From the admin menu (gear icon in upper right corner), select **Manage Gits**.
1. If the lab has never been published on this server:
   1. Click `New Git`.
   1. Fill in the form including Token, Owner/User, and Repo Name. Token here is a GitHub token created by a Learning Labs admin (Profile > Developer Settings > Personal access tokens) and fully scoped for OAuth. Typically this token has been held by Paul Zimmerman. Owner is the organization name, CiscoDevNet. Repo Name is the GitHub repo name.
   1. Click or clear Active depending on whether you want the Lab to publish immediately.
1. If the lab has previously been published, content is changed through the GitHub repo and a release created in GitHub, and then published again:
   1. Search for the repo name in the Gits tab.
   1. In the Actions menu, click the edit icon (blue pencil).
   1. Click or clear Active depending on whether you want the Lab to publish a release and be available for selection in Modules and Tracks.
   1. On the Labs tab, you can only set active to true or false and whitelist a lab on this page. Whitelisting means a log in is not required to view the lab.

## Production versus Staging server

Staging requires a Cisco VPN connection and uses the 8867 port. The production and staging servers are not completely identical and can be synchronized.

## Logging into the server

Contact a current Learning Labs administrator for access to the staging or production servers.

