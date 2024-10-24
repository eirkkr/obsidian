# StudyNav

## MVP Requirements

### Business

- [ ] Complete follow-up ABN actions
- [ ] Develop an IP lawyer contact
- [ ] Develop a commercialisation expert contact
- [x] Develop financial record keeping processes
- [x] Decide app name
- [x] Get ABN
- [x] Register as sole trader
- [x] Create dedicated email address
- [x] create separate bank account for business

### GUI

#### Home

- [ ] Finalise default home page

#### Login/Register

- [ ] Email auth
- [ ] Validate email address regex
- [ ] Implement a password policy / validation
- [x] Change name and email
- [x] Log out button

#### Global Admin

- [ ] Customise home page content
- [ ] Customise footer link
- [ ] Customise font/theme
- [ ] Map terms, e.g. course -> program
- [ ] Enable/disable user self registration
- [ ] Enable/disable features
- [ ] Enable/disable user self delete

#### User Admin

- [ ] Create other users
- [ ] Disable other users
- [x] Add/remove admin privileges (with warning)
- [x] Delete other users

#### Study Package

- [ ] Tabular import/export single study package
- [ ] Delete components
- [ ] Check for broken pre-requisites
- [ ] View/restore history for single study package
- [x] Check for missing components
- [x] Check for duplicate components
- [x] Check for incorrect credits
- [x] Create/edit/delete permissions for admins only
- [x] Add components
- [x] Edit components
- [x] Create study package
- [x] Delete study package
- [x] Edit study package details (e.g. title, credits)
- [x] Add study package checks button
- [x] display components properly

#### Draft Study Package

- [ ] Same features as study package, but a few differences
- [ ] View existing drafts you have permission for (admins see all)
- [ ] Draft study packages are keyed on a study package draft code instead of study package code and version, allowing users to create multiple drafts for the same study package and version
- [ ] Create new blank draft study packages
- [ ] Give other users permission for the draft package
- [ ] Copy non-draft to a new draft study package
- [ ] Allow checks to be run on draft study packages
- [ ] Checks can refer to the live components or draft components

### UI

- [ ] Finalise design for default content size
- [ ] Create SVG logo and favicon
- [ ] Warn on delete
- [ ] Move buttons to top of page
- [ ] Add 'create' button instead of having to do a retrieve first

### API

- [ ] Study package upload / download
- [ ] Restrict to admins only

### Tests

- [ ] Develop comprehensive unit tests for all public methods
- [ ] Develop comprehensive integration tests?
- [ ] Develop comprehensive end-to-end tests?

### Deployment

- [ ] Demo server
	- [x] add example study packages to play with
	- [ ] no admin access to this
	- [ ] home page to have basic marketing info on how to get set up
- [ ] Create workflow for setting up an app for each uni
- [ ] Get an elastic ip address so dns re-routes on ec2 restart
- [ ] Create a workflow for setting up backups
- [x] Enable HTTPS (might need to get a certificate from somewhere other than AWS)
- [x] Enable permanent storage (EBS?). Currently if the instance is stopped data is lost.

## Future

- [ ] Single Sign On (SSO)
- [ ] MFA
- [ ] Users API
- [ ] Study Plan API
- [ ] Draft Study Package API
- [ ] Set up jobs on server to pull / push data?
- [ ] Add availabilities
- [ ] Check for availabilities
- [ ] Generate reports
- [ ] Add light mode
- [ ] Adjust layout depending on screen size
- [ ] Create test workflow / CI
- [ ] Mongo script should auto-remove deprecated indexes
