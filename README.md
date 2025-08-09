# Crystal Item Shop Tutorial!

> **Note:**
> All Fortnite cosmetics are available at [Fortnite.gg](https://fortnite.gg/cosmetics?game=br&type=outfit&season=1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19).

---

## Configuration File Structure

The item shop is defined by a JSON file containing slots for daily (`daily1` through `daily6`) and featured (`featured1` through `featured4`) items. Each slot includes:

**How To Get ID: To get the CID, etc for an item, go to Fortnite.gg, click on any item, and copy the ID shown at the bottom right of the pop-up. Use that ID to replace "CID_TBD" in your config.**
```json
{
    "//": "BR Item Shop Config",
    "daily1": {
        "itemGrants": ["CID_913_Athena_Commando_F_York_D"],
        "price": 500
    },
    "daily2": {
      "itemGrants": [ "CID_584_Athena_Commando_M_Nosh"],
        "price": 0
    },
    "daily3": {
        "itemGrants": ["Pickaxe_ID_202_AshtonBoardwalk"],
        "price": 500
    },
    "daily4": {
        "itemGrants": ["Pickaxe_ID_015_HolidayCandyCane"],
        "price": 800
    },
    "daily5": {
        "itemGrants": ["EID_GabbyHipHop_01"],
        "price": 500
    },
    "daily6": {
        "itemGrants": ["EID_PlayerEleven"],
        "price": 500
    },
    "featured1": {
        "itemGrants": ["CID_478_Athena_Commando_F_WorldCup"],
        "price": 500
    },
    "featured2": {
        "itemGrants": ["CID_892_Athena_Commando_F_VampireCasual"],
        "price": 1200
    },
    "featured3": {
        "itemGrants": ["CID_786_Athena_Commando_F_CavalryBandit_Ghost"],
        "price": 800
    },
    "featured4": {
        "itemGrants": ["CID_386_Athena_Commando_M_StreetOpsStealth"],
        "price": 2000
    }   
}
```
Important:
**Please set the item prices thoughtfully, adjusting them based on each skin’s rarity and exclusivity to ensure a balanced and fair shop experience.**


---

## Tips for Editing

* Use a JSON-aware editor like Visual Studio Code for better validation and formatting.
* Use ChatGPT To validate your Json.
