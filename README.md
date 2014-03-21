Wox.Plugins
===========

Pull Requests to this repo if you want to upload a plugin.


Steps to add your plugins
===========
Notes:
  we use git submodule to manage the wox plugins. That means you need to create a plugin repo, and add your repo as the submodule of Wox.Plugins. **After you linked your plugin to Wox.Plugins, you can update your plugin by simply commit changes inside your repo, there is no more pull requests needed.**
  
  There are some conventions about your plugin repo. **In your plugin repo, it MUST contain a folder named Release and inside this folder, there should be a {any-name}.wox file.**
 
1. `git clone https://github.com/qianlifeng/Wox.Plugins.git`
2. `git submodule add https://github.com/{username}/{plugin-repo-name} {plugin-repo-name}`
3. `git add -A`
4. `git commit -m "add xxx plugin"`
5. `git push`
6. pull request and waiting for accept. Once we accept your plugin, you plugin will be available in [www.getwox.com/plugin](http://www.getwox.com/plugin) page. 
