---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const team = {
   template@odata.bind:"https://graph.microsoft.com/v1.0/teamsTemplates('standard')",
   group@odata.bind:"https://graph.microsoft.com/v1.0/groups('groupId')",
   channels:[
      {
         displayName:"Class Announcements 📢",
         isFavoriteByDefault:true
      },
      {
         displayName:"Homework 🏋️",
         isFavoriteByDefault:true
      }
   ],
   memberSettings:{
      allowCreateUpdateChannels:false,
      allowDeleteChannels:false,
      allowAddRemoveApps:false,
      allowCreateUpdateRemoveTabs:false,
      allowCreateUpdateRemoveConnectors:false
   },
   installedApps:[
      {
         teamsApp@odata.bind:"https://graph.microsoft.com/v1.0/appCatalogs/teamsApps('com.microsoft.teamspace.tab.vsts')"
      },
      {
         teamsApp@odata.bind:"https://graph.microsoft.com/v1.0/appCatalogs/teamsApps('1542629c-01b3-4a6d-8f76-1938b779e48d')"
      }
   ]
};

let res = await client.api('/teams')
	.post(team);

```