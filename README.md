## What is Medal.db ?
- It is a easy and quick storage unit that relies on `objects` to store data in **JSON** format

## Installation
- You need to install the package on your project
```sh-session
npm install medal.db
yarn add medal.db
```
## Example File
![encrypt](  
https://media.discordapp.net/attachments/921429672221343805/925798703195889795/unknown.png?width=456&height=144)
## How To Use
```js
const db = require('medal.db');

db.set('key','value');// to set a data to database.
db.get('key');// to get the data by key.
db.delete('key');// to delete key from database.
db.has('key','value');// return "true" or "false".

db.add('key', 10;);// to add a number to the key.
db.substract('key', 5);// to subtract a number from the key.
db.push('key', 10);// to set a data at the end.
db.math("key","+",5);// to math the numbers.

db.fetch(); // to fetch the data from database. 
db.fetchAll();// to fetchAll data.
db.all();// to get all data in database.

db.backup("Filename");// to make a backup file.
db.reset();// to delete all data and database.

```
## Contact

- Contact With Me Discord : [`5s.v or _zd.`](https://www.npmjs.com/package/medal.db)

## License 
- [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/legalcode)
