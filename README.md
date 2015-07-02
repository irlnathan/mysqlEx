# mysqlex

Super simple mysql config example.  Here's what I did for configuration:

- Setup the mysql config in `config/connections.js`  For example:

```
mysqlServer: {
    adapter: 'sails-mysql',
    host: 'localhost',
    user: 'root',
    password: '1234',
    database: 'mytest'
  },
```
- Installed the adapter. From the terminal window typed: npm install sails-mysql
- Entered the name of the connection (i.e. mysqlServer) in `config/models.js`
- Uncommented the migrate property in `config/models.js`
- Generated a model.  From the terminal window typed: sails generate api user

a [Sails](http://sailsjs.org) application
