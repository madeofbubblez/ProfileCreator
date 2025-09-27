# ProfileCreator

ProfileCreator is a Roblox module that simplifies datastore setup using [ProfileStore](https://github.com/MadStudioRoblox/ProfileStore).

---

## 🚀 How to Set Up
1. Make a new Script in `ServerScriptService`.
2. Name it whatever you want (for organization).
3. Require the ProfileCreator module from the new script.
4. Add the following code:

```lua
local ProfileCreator = require(path.to.ProfileCreator)
ProfileCreator.newDatastore()
```

Fun fact: When the creator of this module/framework made this, he thought it would be bigger than just one folder and 3 module scripts!
Spoiler alert: He was wrong.
	
If you have any problems with using this module/framework, Please contact the following name on github: "madeofbubblez".

- NOTICE: In third-party, There is a framework, ProfileStore (LICENSE file under third-party, licensed Apache 2.0).

## FAQ:
Q: How Do I Add Values And How Do I Remove/Change them?

- A: Enter ProfileCreator > Essentials > Template and change/add/remove values inside the Template = {} table.

Q: Can i use ProfileCreator for commercial use?

- A: No, ProfileCreator is licensed under CC BY-NC 4.0 (As mentioned in LICENSE FILE) and prohibits using ProfileCreator for commercial use, HOWEVER You can contact the creator (madeofbubblez) and ask for permission.

Q: Why Does ProfileCreator Use ProfileStore?

- A: Its just really good for datastores! It handles Session Locks (from what i know (madeofbubblez)) GDPR Compliance and data reconciliation.

Q: Do I Need To Have ProfileStore And Where Do I Find It?

- A: ProfileStore IS required for ProfileCreator to work and Profile Store is found in ProfileCreator > third-party > ProfileStore.

Q: Do I Need To Change Anything for ProfileStore/ProfileCreator To Work?

- A: Yes! Please go to settings > Security > Enable Studio Access to API Services is set to TRUE (checkmarked).

Q: How Do I Check My Version Of ProfileCreator?
- A: Click ProfileCreator ONCE, then go to attributes and view "Version".  
If it is NOT the latest version, download the newest release from [GitHub](https://github.com/madeofbubblez/ProfileCreator).
---

## ⚖️ License
- ProfileCreator: CC BY-NC 4.0  
- ProfileStore (in `third-party/`): Apache 2.0  
