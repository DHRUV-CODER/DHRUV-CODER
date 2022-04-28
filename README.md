![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4&height=200&section=header&text=dscmobile)
# Display your Bot's status as Mobile

### Steps :
 - Clone the [repo](test)
 - `pip install -r requirements.txt`
 - `python3 minified_dscmobile.py` or `py minified_dscmobile.py`
 - paste your bot's token and hit enter
 - **to close the session gracefully press `ctrl+c`**
 
 # Running on User's Account , `Against Discord TOS`
 
 - Get [User's Token](https://www.youtube.com/watch?v=WWHZoa0SxCc)
 - Switch to **online mode** 
 - Exit Discord , Close the app or the browser 
 - (`in cli`) paste the token and hit enter , after this you can reopen your app

> I highly recommend to not try on some users account as it may lead to Ban.
> I am not responsible for any kind of malicious activity , use at your own risk.

## Hey how does this thing work ?

I used websockets and followed Discord's [Docs](https://discord.com/developers/docs/topics/gateway) , modified the payload and ran it.

[Discord gateway Boilerplate code](https://github.com/Anurag-gg/discord-gateway) 

You can display your bot's status as mobile by setting `$browser` to `Discord Android` or `Discord iOS` in the identify payload.

```
{
  "properties": {
    "$browser": "Discord Android"
  }
```
![Alt](https://repobeats.axiom.co/api/embed/0f0a6066974ab8538fc675159ba515d8fda8595e.svg "Repobeats analytics image")
