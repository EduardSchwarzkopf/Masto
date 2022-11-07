# **Masto OSINT Tool**

<img width="999" alt="Masto_logo" src="https://user-images.githubusercontent.com/104733166/200212151-c5eea622-adfe-4209-ad43-f667f743e5fd.png">

[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://github.com/C3n7ral051nt4g3ncy/Masto/blob/master/LICENSE) [![security: bandit](https://img.shields.io/badge/security-bandit-yellow.svg)](https://github.com/PyCQA/bandit)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

## **About Masto**

**Masto provides information/intelligence on Mastodon.social users** 
<br>
<br>
*Keep in mind there is a flaw with Mastodon, the same username can be used across various instances(servers), and this won't prove it's the same person behind each account. This will probably cause **impersonation issues** in the future.*

With **Masto OSINT Tool**, you will be able to:
- Find user ID
- Find all accounts belonging to a user without logging in to Mastodon (**Mastodon requires users to log in and after the first 5 results you get**: ```401Search queries pagination is not supported without authentication```
- Find user correlation (can't be found by searching on the Mastodon.social website)
- check if the user is a bot 
- Check if the user has to approve followers manually
- Check if the account is a group
- Check if the account is locked
- Check if the user opted to be listed on the profile directory
- Get avatar link witn an **additional choice** of opening the avatar in your browser
- Get profile creation date
- Get number of followers & following
- Get number of posts
- Get user last message date 
- Get user's bio
- Get user's hashtags
- Get header image link
- Get link to followers and following
- Get user public key (PEM -Privacy-enhanced Electronic Mail) 

## Additional instance (server) feature
**This is a nice feature**, if you type ```social.network.europa.eu``` on [Mastodon.social](https://mastodon.social/search) , you won't get a result as the instance is set to ```not discoverable```. <br>
With this function you will be able to:
- Get information on an instance
- Get instance ID
- Get instance email 
- Get a short description
- Get server thumbnail link
- Get instance creation date 
- Get instance language used
- Get instance count of followers and following
- Get instance last status date
- Get header image link and avatar link
- Get instance display name
- Get admin url
- Get admin avatar
- Check if instance account is locked
- Check if invites on the instance are enabled
- Check if registration is required and if the admin needs to approve the request
- Check if the instance is a bot 
