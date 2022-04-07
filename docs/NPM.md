# NPM (Node Package Manager)

## Tool Summary

NPM is a software registry used for the installation and publication of node.js packages.
These packages can be shared both publically and privatly by anyone. NPM comes installed alongside with Node.js, as it is a commonly used tool.

## Useful Links

**NPM Package Search:** <https://www.npmjs.com>

**NPM Tutorial:** <https://nodesource.com/blog/an-absolute-beginners-guide-to-using-npm/>

## Presentation Questions

### What are the tool's goals?

To share javascript packages quickly over the internet to allow developers to utilize third party tools to develop their own software quicker

NPM also installs all package dependencies making sure there are no packages that are lacking any other packages in order to work

### How does tool work? (Design/architecture of tool.)

NPM can be accessed in two different ways

- Access packages over the web from an online repository <https://www.npmjs.com/>
- Through the command line interface using command (`npm install <package_name>`)
  Once install these packages are then added to your code and available for you to utilize in your own code

### What do you need to use the tool? What does it depend on?

To use the tool only need to install node.js which automatically installs npm and then just run command line code to install the packages and the dependencies

### What are the strengths and limitations of the tool?

- The biggest strength of the tool is that developers are able to freely share packages with one another on this open source platform
- The packages can however take over ten minutes to install due to the nature of dependencies
- Some packages have hundreds of dependencies needing to be install in order for the package to properly work
- Can leads to long install times

### What are the competitors/alternatives to the tool?

- [PNPM](https://pnpm.io/)
- [Yarn](https://yarnpkg.com/)

## Fun Facts

- Well over one million packages have been shared on NPM
- Package 'is-Odd' has over 100 million downloads
