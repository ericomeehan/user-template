# user template

### eric o meehan
### 2022-05-24

## description
template for automated and source controlled arch linux users

this repository is a template designed to be cloned and edited to create new users

## usage
1. fork the template repository to $gitServer:users/$userId
2. edit the repository contents to define the desired user:
	* edit the install script to add actions to user creation
	* define groups and policies in separate repositories
		- see "group-template" and "policy-template" repositories
	* add groups and policies to the user as git submodules
3. add the repository as a submodule to an installation or group repository
