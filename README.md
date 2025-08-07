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
        "itemGrants": ["EID_Fresh"],
        "price": 0
    },
    "daily2": {
      "itemGrants": [ "CID_431_Athena_Commando_F_StormPilot"],
        "price": 800
    },
    "daily3": {
        "itemGrants": ["Pickaxe_ID_363_LollipopTricksterFemale"],
        "price": 1000
    },
    "daily4": {
        "itemGrants": ["EID_WaveDance"],
        "price": 500
    },
    "daily5": {
        "itemGrants": ["ID: Glider_ID_097_Feathers
"],
        "price": 500
    },
    "daily6": {
        "itemGrants": ["Pickaxe_ID_599_CavernFemale"],
        "price": 0
    },
    "featured1": {
        "itemGrants": ["CID_A_005_Athena_Commando_F_GlobalFB_E_GTH5I"],
        "price": 2000
    },
    "featured2": {
        "itemGrants": ["CID_A_365_Athena_Commando_F_FNCS_Blue"],
        "price": 1500
    },
    "featured3": {
        "itemGrants": ["CID_818_Athena_Commando_F_NeonTightSuit_A"],
        "price": 2000
    },
    "featured4": {
        "itemGrants": ["CID_A_206_Athena_Commando_F_TextileSparkle_V8YSA"],
        "price": 3000
    }   
}
```
Important:
**Please set the item prices thoughtfully, adjusting them based on each skin’s rarity and exclusivity to ensure a balanced and fair shop experience.**


---

## Tips for Editing

* Use a JSON-aware editor like Visual Studio Code for better validation and formatting.
* Use ChatGPT To validate your Json.
