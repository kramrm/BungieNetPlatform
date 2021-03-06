<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
Returns advisor information about a given character.
* **URI:** [[/Destiny/{membershipType}/MyAccount/Character/{characterId}/Advisors/|https://www.bungie.net/Platform/Destiny/{membershipType}/MyAccount/Character/{characterId}/Advisors/]]
* **Method:** GET
* **Accessibility:** Private
* **Service:** [[DestinyService|Endpoints#DestinyService]]

## Parameters
### Path Parameters
Name | Description
---- | -----------
[[membershipType|Enums#BungieMembershipType]] | A valid Bungie.net membershipType.
characterId | A valid characterId that is associated with the given account.

### Query String Parameters
Name | Description
---- | -----------
definitions | Include definitions in the response. Use while testing.

### JSON POST Parameters
None

## Example
GET https://www.bungie.net/Platform/Destiny/2/MyAccount/Character/2305843009221011538/Advisors/
```javascript
{
    "Response": {
        "data": {
            "vendorAdvisors": {
                "4269570979": {
                    "rotationAckId": "",
                    "needsAck": false,
                    "nextRefreshDate": "2015-05-27T08:00:00Z",
                    "rewardClaimSales": {
                        "1932910919": {
                            "currencyItemHash": 1932910919,
                            "saleItems": [
                                {
                                    "item": {
                                        "itemHash": 3159615086,
                                        "bindStatus": 0,
                                        "isEquipped": false,
                                        "itemInstanceId": "0",
                                        "itemLevel": 0,
                                        "stackSize": 200,
                                        "qualityLevel": 0,
                                        "stats": [

                                        ],
                                        "canEquip": false,
                                        "equipRequiredLevel": 0,
                                        "unlockFlagHashRequiredToEquip": 0,
                                        "cannotEquipReason": 0,
                                        "damageType": 0,
                                        "damageTypeNodeIndex": -1,
                                        "damageTypeStepIndex": -1,
                                        "talentGridHash": 0,
                                        "nodes": [

                                        ],
                                        "useCustomDyes": false,
                                        "artRegions": {

                                        },
                                        "isEquipment": false,
                                        "isGridComplete": false,
                                        "perks": [

                                        ],
                                        "location": 3,
                                        "transferStatus": 2,
                                        "locked": false,
                                        "lockable": false
                                    },
                                    "vendorItemIndex": 19,
                                    "itemStatus": 0,
                                    "costs": [
                                        {
                                            "itemHash": 1932910919,
                                            "value": 1
                                        }
                                    ],
                                    "unlockStatuses": [

                                    ]
                                }
                            ]
                        }
                    },
                    "progression": {
                        "dailyProgress": 0,
                        "weeklyProgress": 0,
                        "currentProgress": 161259,
                        "level": 55,
                        "step": 0,
                        "progressToNextLevel": 1859,
                        "nextLevelAt": 3000,
                        "progressionHash": 529303302
                    }
                }
            },
            "activityAdvisors": {
                "3645919501": {
                    "activityBundleHash": 3645919501,
                    "materialUpgrades": {
                        "activityBundleHash": 3645919501,
                        "materialItemHash": 2882093969,
                        "itemSoidsUpgradable": [
                            "6917529042520979214",
                            "6917529048105882280",
                            "6917529040409199096",
                            "6917529044605328872",
                            "6917529050104128059"
                        ]
                    }
                },
                "2659248071": {
                    "activityBundleHash": 2659248071,
                    "raidActivities": {
                        "activityBundleHash": 2659248071,
                        "raidIdentifier": "RAID_VENUS1",
                        "expirationDate": "2015-06-02T09:00:00Z",
                        "tiers": [
                            {
                                "activityHash": 2659248071,
                                "stepsComplete": 0,
                                "stepsTotal": 4,
                                "difficultyIdentifier": "DIFFICULTY_NORMAL",
                                "activeRewardIndexes": [
                                    0
                                ]
                            },
                            {
                                "activityHash": 2659248068,
                                "stepsComplete": 0,
                                "stepsTotal": 4,
                                "difficultyIdentifier": "DIFFICULTY_HARD",
                                "activeRewardIndexes": [
                                    0
                                ]
                            }
                        ],
                        "iconPath": "\/common\/destiny_content\/icons\/6d867d1fe7870f952201bd9e7f42fcd4.png"
                    }
                }
            },
            "areOffersAvailable": true,
            "events": [
                {
                    "eventHash": 3,
                    "eventIdentifier": "SPECIAL_EVENT_VEHICLES",
                    "expirationDate": "2015-06-02T17:00:00Z",
                    "startDate": "2015-05-26T17:00:00Z",
                    "expirationKnown": true
                }
            ],
            "bonuses": [
                {
                    "cardId": 608070,
                    "cardName": "Salvage",
                    "statName": "Match Wins",
                    "bonusName": "Activity Reward Bonus",
                    "bonusDescription": "Cloaks, marks, and bonds can now drop in this Playlist.",
                    "bonusRank": {
                        "statId": 1,
                        "rank": 1
                    },
                    "value": 15,
                    "threshold": 25,
                    "smallImage": {
                        "rect": {
                            "x": 725,
                            "y": 0,
                            "height": 145,
                            "width": 145
                        },
                        "sheetPath": "\/common\/destiny_content\/grimoire\/hr_images\/CruciblePlaylists-csprites-sm_aec3a987077cb29050ad7f37c230627f.jpg",
                        "sheetSize": {
                            "x": 0,
                            "y": 0,
                            "height": 145,
                            "width": 1885
                        }
                    }
                }
            ],
            "earnedCurrency": [
                {
                    "dailyProgress": -85,
                    "weeklyProgress": -85,
                    "currentProgress": 15,
                    "level": 15,
                    "step": 0,
                    "progressToNextLevel": 0,
                    "nextLevelAt": 1,
                    "progressionHash": 2033897742
                },
                {
                    "dailyProgress": -80,
                    "weeklyProgress": -80,
                    "currentProgress": 0,
                    "level": 0,
                    "step": 0,
                    "progressToNextLevel": 0,
                    "nextLevelAt": 1,
                    "progressionHash": 2033897755
                }
            ],
            "factions": {
                "468098704": {
                    "factionHash": 468098704,
                    "progression": {
                        "dailyProgress": 0,
                        "weeklyProgress": 0,
                        "currentProgress": 48532,
                        "level": 20,
                        "step": 0,
                        "progressToNextLevel": 32,
                        "nextLevelAt": 2500,
                        "progressionHash": 3233510749
                    }
                }
            },
            "arena": [
                {
                    "activityHash": 2326253031,
                    "iconPath": "\/img\/destiny_content\/arena\/35_challenge.v2.png",
                    "rounds": [
                        {
                            "enemyRaceHash": 3265589059,
                            "skulls": [
                                3,
                                6
                            ]
                        },
                        {
                            "enemyRaceHash": 711470098,
                            "skulls": [
                                2,
                                4
                            ]
                        },
                        {
                            "enemyRaceHash": 546070638,
                            "skulls": [
                                7,
                                12
                            ]
                        },
                        {
                            "enemyRaceHash": 1636291695,
                            "skulls": [
                                8,
                                13
                            ]
                        },
                        {
                            "enemyRaceHash": 1636291695,
                            "skulls": [
                                1,
                                5
                            ]
                        }
                    ],
                    "bossFight": true,
                    "bossSkulls": [
                        9
                    ],
                    "activeRewardIndexes": [
                        0
                    ],
                    "isCompleted": false
                }
            ],
            "trials": {
                "highestWinRank": 0,
                "active": false,
                "scheduled": true,
                "startDate": "2015-05-29T17:00:00Z",
                "expirationDate": "2015-06-02T09:00:00Z",
                "ticket": {
                    "hasTicket": false,
                    "maxWins": 9,
                    "maxLosses": 3,
                    "wins": 0,
                    "losses": 0
                },
                "winDetails": [

                ],
                "buffs": [
                    {
                        "itemHash": 1592861599,
                        "saleItem": {
                            "item": {
                                "itemHash": 1592861599,
                                "bindStatus": 0,
                                "isEquipped": false,
                                "itemInstanceId": "0",
                                "itemLevel": 0,
                                "stackSize": 1,
                                "qualityLevel": 0,
                                "stats": [

                                ],
                                "canEquip": false,
                                "equipRequiredLevel": 0,
                                "unlockFlagHashRequiredToEquip": 0,
                                "cannotEquipReason": 0,
                                "damageType": 0,
                                "damageTypeNodeIndex": -1,
                                "damageTypeStepIndex": -1,
                                "talentGridHash": 0,
                                "nodes": [

                                ],
                                "useCustomDyes": false,
                                "artRegions": {

                                },
                                "isEquipment": false,
                                "isGridComplete": false,
                                "perks": [
                                    {
                                        "iconPath": "\/common\/destiny_content\/icons\/fe5666626479eb71de440c5d337f3b3e.png",
                                        "perkHash": 2339147975,
                                        "isActive": true
                                    }
                                ],
                                "location": 3,
                                "transferStatus": 2,
                                "locked": false,
                                "lockable": false
                            },
                            "vendorItemIndex": 25,
                            "itemStatus": 0,
                            "costs": [
                                {
                                    "itemHash": 605475555,
                                    "value": 3
                                }
                            ],
                            "unlockStatuses": [

                            ]
                        },
                        "isUsed": false,
                        "isActive": false
                    }
                ],
                "currency": {
                    "itemHash": 605475555,
                    "value": 0
                }
            }
        }
    },
    "ErrorCode": 1,
    "ThrottleSeconds": 0,
    "ErrorStatus": "Success",
    "Message": "Ok",
    "MessageData": {

    }
}
```

## References
