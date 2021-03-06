<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
Defines an &quot;Objective&quot;. An objective is a specific task you should accomplish in the game. These are referred to by: - Quest Steps (which are DestinyInventoryItemDefinition entities with Objectives) - Challenges (which are Objectives defined on an DestinyActivityDefintion) - Milestones (which refer to Objectives that are defined on both Quest Steps and Activities) - Anything else that the designers decide to do later. Objectives have progress, a notion of having been Completed, human readable data describing the task to be accomplished, and a lot of optional tack-on data that can enhance the information provided about the task.

## Schema
* **Schema Type:** Manifest Definition
* **Type:** object
* **Mobile Manifest:** Objectives

## Properties
Name | Type | Description
---- | ---- | -----------
displayProperties | [[DestinyDisplayPropertiesDefinition|Destiny-Definitions-Common-DestinyDisplayPropertiesDefinition]]:Definition | Ideally, this should tell you what your task is. I'm not going to lie to you though. Sometimes this doesn't have useful information at all. Which sucks, but there's nothing either of us can do about it.
completionValue | integer:int32 | The value that the unlock value defined in unlockValueHash must reach in order for the objective to be considered Completed. Used in calculating progress and completion status.
locationHash | [[Destiny.Definitions.DestinyLocationDefinition|Destiny-Definitions-DestinyLocationDefinition]]:integer:uint32 | OPTIONAL: a hash identifier for the location at which this objective must be accomplished, if there is a location defined. Look up the DestinyLocationDefinition for this hash for that additional location info.
allowNegativeValue | boolean | If true, the value is allowed to go negative.
allowValueChangeWhenCompleted | boolean | If true, you can effectively &quot;un-complete&quot; this objective if you lose progress after crossing the completion threshold. If False, once you complete the task it will remain completed forever by locking the value.
isCountingDownward | boolean | If true, completion means having an unlock value less than or equal to the completionValue. If False, completion means having an unlock value greater than or equal to the completionValue.
valueStyle | [[DestinyUnlockValueUIStyle|Destiny-DestinyUnlockValueUIStyle]]:Enum | The UI style applied to the objective. It's an enum, take a look at DestinyUnlockValueUIStyle for details of the possible styles. Use this info as you wish to customize your UI.
progressDescription | string | Text to describe the progress bar.
perks | [[DestinyObjectivePerkEntryDefinition|Destiny-Definitions-DestinyObjectivePerkEntryDefinition]]:Definition | If this objective enables Perks intrinsically, the conditions for that enabling are defined here.
stats | [[DestinyObjectiveStatEntryDefinition|Destiny-Definitions-DestinyObjectiveStatEntryDefinition]]:Definition | If this objective enables modifications on a player's stats intrinsically, the conditions are defined here.
hash | integer:uint32 | The unique identifier for this entity. Guaranteed to be unique for the type of entity, but not globally. When entities refer to each other in Destiny content, it is this hash that they are referring to.
index | integer:int32 | The index of the entity as it was found in the investment tables.
redacted | boolean | If this is true, then there is an entity with this identifier/type combination, but BNet is not yet allowed to show it. Sorry!

## Example
```javascript
{
    // Type: [[DestinyDisplayPropertiesDefinition|Destiny-Definitions-Common-DestinyDisplayPropertiesDefinition]]:Definition
    "displayProperties": {},
    // Type: integer:int32
    "completionValue": 0,
    // Type: [[Destiny.Definitions.DestinyLocationDefinition|Destiny-Definitions-DestinyLocationDefinition]]:integer:uint32
    "locationHash": 0,
    // Type: boolean
    "allowNegativeValue": false,
    // Type: boolean
    "allowValueChangeWhenCompleted": false,
    // Type: boolean
    "isCountingDownward": false,
    // Type: [[DestinyUnlockValueUIStyle|Destiny-DestinyUnlockValueUIStyle]]:Enum
    "valueStyle": {},
    // Type: string
    "progressDescription": "",
    // Type: [[DestinyObjectivePerkEntryDefinition|Destiny-Definitions-DestinyObjectivePerkEntryDefinition]]:Definition
    "perks": {},
    // Type: [[DestinyObjectiveStatEntryDefinition|Destiny-Definitions-DestinyObjectiveStatEntryDefinition]]:Definition
    "stats": {},
    // Type: integer:uint32
    "hash": 0,
    // Type: integer:int32
    "index": 0,
    // Type: boolean
    "redacted": false
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-Definitions-DestinyObjectiveDefinition.html#schema_Destiny-Definitions-DestinyObjectiveDefinition
