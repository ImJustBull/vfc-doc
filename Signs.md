SignSystem
===

This tutorial will help you to understand how to setup the SignSystem for your needs.


Sign Setup:
---

To place a ServerSign in minecraft you need to have this `virtualfalre.sign.setup` permission to do so.

Place Down a Sign and configer it like that:

**1) Simple Way**

```
1: vfc
2:
3: <ServerGroup>
4:
```

`<ServerGroup>` stands for the Server Group wich you want to display on the sign

**2.)**

```
1: vfc
2: <Template>
3: <ServerGroup>
4: 
```

`<ServerGroup>` stands for the Server Group wich you want to display on the sign  
`<Template>` stands for the template code, wich you can get in the Webpanel  

**3.)**
```
1: vfc
2: <Template>
3: <ServerGroup>
4: <Priority>
```
`<ServerGroup>` stands for the Server Group wich you want to display on the sign  
`<Template>` stands for the template code, wich you can get in the Webpanel  
`<Priority>` set the priority for this specific sign, (higher priority, against other signs)

Important, Save the file!
---
If you have changes/added or removed a Sign inGame you have to save the `plugin/VFCloud/serversigns.yml` file to your template folder, if not the progress will be lost!  

Commands associated with the SignSystem:
---

`/cloud sign`