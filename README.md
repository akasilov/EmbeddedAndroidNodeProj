# EmbeddedAndroidNodeProj
### Setup node-red project

- Install node 
- Install node-red 
- Change settings.js to active projects feature which is disabled by default. 
More information about projects: https://nodered.org/docs/user-guide/projects/

`nano ~/.node-red/settings.js` 
```
editorTheme: {  
       projects: {  
           enabled: true
       }
   }
```

- Start node-red and from Projects menu clone git repository `git@github.com:akasilov/EmbeddedAndroidNodeProj.git`
- The repository will be cloned into `~/.node-red/projects/`.
- Committing the changes to the project shall be done from the "Project History" tab inside node-red.  

