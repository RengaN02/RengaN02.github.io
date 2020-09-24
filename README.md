
![Image](https://img.shields.io/npm/v/saverdb?color=f)
![Image](https://img.shields.io/npm/dt/saverdb.svg?maxAge=3600)
![Image](https://discordapp.com/api/guilds/694184888655544392/embed.png?style=shield) 
#
![Image](https://nodei.co/npm/saverdb.png?downloads=true&downloadRank=true&stars=true)
#
![Image](https://cdn.glitch.com/95787f3d-bc92-4ddf-ba1d-8aa1593326ee%2FAds%C4%B1z.png?v=1596844623604)

Bu modül verleri direk olarak json dosyasını oluşturup üstüne yazar ayrıca kaydettiğiniz kodları düzenleyebilirsiniz.

This module creates and overwrites the data in the json file, and you can edit the codes you have saved.
#
# Installation
```npm
npm i saverdb
```





#
# Examples
```javascript

const db = require('saverdb')

setInterval(async () => {
    await db.add(`User`,`RengaN`) // ---> Add user data this value
    await db.set(`UserId`,'368695088718544896') // ---> Create user data
    await db.delete('UserAvatar') // ---> Delete user data
    await db.push(`User`,`RengaN`) // ---> Push to array
    await db.has('User') // ---> True Or False
    var data = await db.fetch(`User`)// ---> Fetch user data
    var data = await db.get(`User`)// ---> Fetch user data
    console.log(data)
    const data_2 = await db.fetchAll() // ---> Fetch all data
    console.log(data_2)
    const data_3 = await db.includes(`User`)// ---> Fetch all occurrences of the data you specify
    console.log(data_3)
    await db.deleteIncludes(`User`)// ---> Delete all occurrences of the data you specified
 
  },1800000)

```
# Warning 
**_Please use the most reliable version 2.4.x_**
#
If an error occurs, you can use **wio.db** as an alternative.
# Platforms
Internet coding platforms ➕
#
Windows ➕ 
#
MacOs ➕
#
Linux ➕
#
Github ➖
# Bugs Report
### RengaN
[Discord](https://discord.gg/W4geNJp) 
[İnstagram](https://instagram.com/tlhaltndg/) 
[Twitter](https://twitter.com/tlhaltndg)
