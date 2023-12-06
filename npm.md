[npm Commands]

1. Initialise a new project:
	- npm init
	- This command initialises a new `package.json` file by interactively prompting you for information about your project.
2. Install dependencies:
	- npm install
	- This command installs the dependencies listed in the `package.json` file.
3. Install a specific package:
	- npm install package-name
	- This installs a specific package and adds it to the `dependencies` section of your `package.json` file.
4. Install a development dependency:
	- npm install --save-dev package-name
	- This installs a package and adds it to the `devDependencies` section of your `package.json` file, which is typically used for development and testing dependencies.
5. Install a package globally:
	- npm insatll -g package-name
	- This removes a package from your project and udpates the `package.json` file accordingly.
6. Uninstall a package:
	- npm uninsatll package-name
	- This removes a package from your project and updates the `package.json` file accordingly.\
7. Update all dependencies:
	- npm update
	- This updates all packages to their lates versions based on the version constraints specified in your `package.json` file.
8. List installed packages:
	- npm list
	- This shows a tree-like view of installed packages and their versions.
9. Run a a script:
	- npm run script-name 
	- This executes a script defined in the `scripts` section of your `package.json` file.
10. Clean the npm cache:
	- npm cache clean -f
	- This command cleans the npm cache, useful when troubleshooting installation issues.
11. Install packages from a specific registry:
	- npm install --registry=https://registry.npmjs.org/package-name
	- This installs a package fromm a specified registry.
12. Check for outdated packages:
	- npm outdated
	- This command shows a list of outdated packages and their current versions.
13. View npm configurations:
	- npm config list
	- This displays
	
