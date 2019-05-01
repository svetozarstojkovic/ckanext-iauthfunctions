This repository is used as example extension for CKAN.

Example extension created here is the one explained in [CKAN Docs - Creating extension.](https://docs.ckan.org/en/2.8/extensions/tutorial.html#creating-a-new-extension)

## Logic part

### Testing

1. Register as new user under some random name
2. Open **Groups** in Header as that new user
3. Button **Add Group** is not present on the page
4. Login as admin user
5. Create group under the name **curators**
6. Add created user in group **curators** 
7. Open **Groups** in Header as created user
8. Button **Add Group** is now present on the page

#### Conclusion

Only users which are in the group **curators** can create new group.

 
## Template part

Footer part is altered in a way that there is a link now that leads to this Github repo.

