# browserslist-config-lamb

LAMB standard broswerslist configuration to share target browsers with different front-end tools.

## Use LAMB configuration
Add this package as a devDependencies of the project. On your `package.json` add
```
"browserslist-config-lamb": "git+ssh://git@github.com/LAMB-GoCoGroup/browserslist-config-lamb.git"
```
Install the dependency
```
npm install
```
On the root of the project create a `.browserslistrc` and extends the configuration
```
extends browserslist-config-lamb
```