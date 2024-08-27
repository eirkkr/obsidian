# StudyNav

## MVP Requirements

### Business

- [x] app name
	- [x] decide on a name
	- [x] update name in all places
- [ ] get ABN
	- [x] submit application
	- [ ] follow-up actions
- [x] register as sole trader
- [x] create dedicated email address
- [x] create separate bank account for business
- [ ] Record keeping

### App

- [ ] registration / login page
	- [x] combine registration and login page
	- [x] name (used for comms)
	- [ ] email auth
	- [x] change name and email address feature
	- [x] add log out
- [ ] admin page
	- [ ] Only visible to admin users (or greyed out?)
	- [ ] ability to add other admins (with warning) and other users
- [ ] spk page
	- [ ] display full study package details
	- [ ] display components properly
	- [ ] csv import for study packages
	- [ ] edit / import only for admins
	- [ ] Displays errors with study packages
	- [ ] Include pre-requisites in the check
- [ ] Home page
	- [x] Combine with 'about' page
	- [ ] Have content configurable per deployment
- [x] configuration
	- [x] Choose which features are available (just study package, home, admin for now)
- [ ] api
	- [ ] study package upload / download
	- [ ] upload available for admins only
- [ ] tests
	- [ ] comprehensive tests for all features
- [ ] Restore history feature
- [ ] https

### Deployment

- [ ] demo server
	- [ ] add example study packages to play with
	- [ ] no admin access to this
	- [ ] home page to have basic marketing info on how to get set up
- [x] test server
- [ ] Create workflow for setting up an app for each uni
- [ ] Get an elastic ip address so dns re-routes on ec2 restart
- [ ] Enable HTTPS (might need to get a certificate from somewhere other than AWS)

## Future

- [ ] course builder page
	- [ ] user-level study packages for experimenting
	- [ ] new collection, same as spk, except with user and a version
- [ ] study package page
	- [ ] users can copy spk into course builder
	- [ ] csv export?
- [ ] Single sign-on?
- [ ] MFA
- [ ] api
	- [ ] users
- [ ] admin page
	- [ ] other configuration
