# Share File Portals

Need to put in files in or out your network? Think with portals. Very W.I.P.
Project name might change in the future, however, upon deciding on a better name, I personally will try to make sure I give a link to the new repository and then archive this repository.

## Why Portals?

I had envisioned Windows XP's file copying animation with portals when I got the idea for this.
Also I was slowly getting a file, that's why I was daydreaming lol.

## Proposed Features

Here is a list of probably not all features this project aims to cover.
The project will also update [the docs](#the-docs) section as the project gets updates.

- [ ] Viewing
  - [ ] the website
  - [ ] the files you have
  - [ ] the control panel, if you are an admin account
  - [ ] 
- [ ] Downloading files
  - [ ] directly
  - [ ] with signed link proxies
  - [ ] with chunking
    - [ ] and skipping the chunks you have downloaded (requires using the website)
  - [ ] with poor network optimized algorithm (again, requires using the website)
  - [ ] with speed limitations
  - [ ] with server-to-client encryption (requires using the website)
  - [ ] with server-to-client compression (especially for folders, requires using the website)
- [ ] Uploading files
  - [ ] directly
  - [ ] with signed link proxies
  - [ ] with chunking (requires using the website)
  - [ ] with poor network optimizations (requires using the website)
  - [ ] with speed limitations
  - [ ] with storage limitations
    - [ ] per account (includes special "customer" accounts)
    - [ ] for the whole system (as long as we are keeping a track of it)
  - [ ] with compression before recieving data
  - [ ] to a 3rd party storage service first, then downloading it to your network (requires using the website, token/credentials from the storage service)
- [ ] Logging in
  - [ ] with OpenID (open an issue if you are a company and need another login method)
  - [ ] with email + TOTP
  - [ ] with special customer/anonymous links (can also be temporary)
- [ ] Not self hosting but it will not be free
- [ ] Providing an API for internal use
  - [ ] for creating customer links
  - [ ] for uploading files with per-app token credentials
  - [ ] for checking user storage & storage quotas
  - [ ] for being notified when someone uploads a file (push notifications on the web, webhooks, e-mail)
- [ ] Testable builds
  - [ ] and auto create release builds
  
# The Docs

Nothing yet...

Also, _why do I feature creep everything I touch?_
