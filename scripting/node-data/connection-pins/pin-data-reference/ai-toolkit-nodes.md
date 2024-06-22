# AI Toolkit Nodes

<details>

<summary>Declare Encounter Variable</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Identifier\
Scope

pinId: Identifier\
dataType: identifier Editor Settings:

pinId: Initial Value\
dataType: encounter Editor Settings:

defaultValue: String: nil

pinId: Scope\
dataType: forge\_variable\_scope Editor Settings:

userData: Editor Settings:

#### Node Category: Unused\_AIToolkit\_Variables\\

</details>

<details>

<summary>Get Encounter Variable Storage</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Identifier\
Scope

pinId: Identifier\
dataType: identifier Editor Settings:

pinId: Scope\
dataType: forge\_variable\_scope Editor Settings:

pinId: Object\
dataType: object\
defaultValue: String: nil Editor Settings:

#### Output Pins

pinId: Out\
dataType: encounter\
userData: Editor Settings: Editor Settings:

#### Node Category: Unused\_AIToolkit\_Variables\\

</details>

<details>

<summary>Set Encounter Variable Storage\ Function</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Identifier\
Scope

pinId: ActionStart\
dataType: execute

pinId: Identifier\
dataType: identifier Editor Settings:

pinId: Value\
dataType: encounter\
defaultValue: String: nil Editor Settings:

pinId: Scope\
dataType: forge\_variable\_scope Editor Settings:

pinId: Object\
dataType: object\
defaultValue: String: nil Editor Settings:

#### Output Pins

pinId: ActionComplete\
dataType: execute

userData: Editor Settings:

#### Node Category: Unused\_AIToolkit\_Variables\\

</details>

<details>

<summary>Declare Squad Specification Variable</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Identifier\
Scope

pinId: Identifier\
dataType: identifier Editor Settings:

pinId: Initial Value\
dataType: squad\_specification Editor Settings:

defaultValue: String: nil

pinId: Scope\
dataType: forge\_variable\_scope Editor Settings:

userData: Editor Settings:

#### Node Category: Unused\_AIToolkit\_Variables\\

</details>

<details>

<summary>Get Squad Specification Variable Storage</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Identifier\
Scope

pinId: Identifier\
dataType: identifier Editor Settings:

pinId: Scope\
dataType: forge\_variable\_scope Editor Settings:

pinId: Object\
dataType: object\
defaultValue: String: nil Editor Settings:

#### Output Pins

pinId: Out\
dataType: squad\_specification\
userData: Editor Settings: Editor Settings:

#### Node Category: Unused\_AIToolkit\_Variables\\

</details>

<details>

<summary>Set Squad Specification Variable Storage\ Function</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Identifier\
Scope

pinId: ActionStart\
dataType: execute

pinId: Identifier\
dataType: identifier Editor Settings:

pinId: Value\
dataType: squad\_specification\
defaultValue: String: nil Editor Settings:

pinId: Scope\
dataType: forge\_variable\_scope Editor Settings:

pinId: Object\
dataType: object\
defaultValue: String: nil Editor Settings:

#### Output Pins

pinId: ActionComplete\
dataType: execute

userData: Editor Settings:

#### Node Category: Unused\_AIToolkit\_Variables\\

</details>

<details>

<summary>Create Encounter Storage</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Area Object\
Identifier

pinId: ActionStart\
dataType: execute

pinId: Area Object\
dataType: object Editor Settings:

pinId: Identifier\
dataType: identifier Editor Settings:

#### Output Pins

pinId: ActionComplete\
dataType: execute

userData: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Squad Follow Player Function</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Squad\
Player

pinId: ActionStart\
dataType: execute

pinId: Squad\
dataType: ai\_squad Editor Settings:

pinId: Player\
dataType: object Editor Settings:

properties: propertyName: Radius\
dataType: number\
defaultValue: Float: 50.0

MinRange: 10.0\
MaxRange: 100.0\
Step: 1.0 Editor Settings:

propertyName: Refresh Distance\
dataType: number\
defaultValue: Float: 30.0

MinRange: 10.0\
MaxRange: 100.0\
Step: 1.0 Editor Settings:

propertyName: Refresh Time\
dataType: number\
defaultValue: Float: 5.0

MinRange: 1.0\
MaxRange: 30.0\
Step: 1.0 Editor Settings:

#### Output Pins

pinId: ActionComplete\
dataType: execute

userData: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Squad Follow Storage</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Object\
Squad

pinId: ActionStart\
dataType: execute

pinId: Squad\
dataType: ai\_squad Editor Settings:

pinId: Object\
dataType: object Editor Settings:

properties: propertyName: Radius\
dataType: number\
defaultValue: Float: 50.0

MinRange: 10.0\
MaxRange: 100.0\
Step: 1.0 Editor Settings:

propertyName: Refresh Distance\
dataType: number\
defaultValue: Float: 30.0

MinRange: 10.0\
MaxRange: 100.0\
Step: 1.0 Editor Settings:

propertyName: Refresh Time\
dataType: number\
defaultValue: Float: 5.0

MinRange: 1.0\
MaxRange: 30.0\
Step: 1.0 Editor Settings:

#### Output Pins

pinId: ActionComplete\
dataType: execute

userData: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Squad Go To Position Storage</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Squad\
Position

pinId: ActionStart\
dataType: execute

pinId: Squad\
dataType: ai\_squad Editor Settings:

pinId: Position\
dataType: vector3 Editor Settings:

pinId: Radius\
dataType: number\
defaultValue: Float: 50.0

MinRange: 10.0\
MaxRange: 100.0\
Step: 1.0 Editor Settings:

#### Output Pins

pinId: ActionComplete\
dataType: execute

userData: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Spawn Squad Storage</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
SquadSpawnDefinition

pinId: ActionStart\
dataType: execute

pinId: SquadSpawnDefinition\
dataType: ai\_squad\_definition Editor Settings:

pinId: Identifier\
dataType: identifier\
defaultValue: String: nil Editor Settings:

#### Output Pins

pinId: ActionComplete\
dataType: execute

userData: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Assign Squad To Encounter Function</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Squad\
Encounter

pinId: ActionStart\
dataType: execute

pinId: Squad\
dataType: ai\_squad Editor Settings:

pinId: Encounter\
dataType: encounter Editor Settings:

#### Output Pins

pinId: ActionComplete\
dataType: execute

userData: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Assign Object to Team Function</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Target

pinId: ActionStart\
dataType: execute

pinId: Target\
dataType: object Editor Settings:

pinId: Team\
dataType: team\
defaultValue: String: nil Editor Settings:

pinId: Bias\
dataType: number\
defaultValue: String: nil Editor Settings:

MinRange: -1.0\
MaxRange: 1.0\
Step: 0.1

pinId: Targetable Object Overrides\
dataType: targetable\_object\_overrides\
defaultValue: String: nil Editor Settings:

#### Output Pins

pinId: ActionComplete\
dataType: execute

userData: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Brute General</summary>

#### Input Pins

pinId: Character Type\
dataType: ai\_brute\_character\_type\
defaultValue: String: AICharacterTypeIdTable.brute\_minor Editor Settings:\\

#### Output Pins

pinId: Character Specification\
dataType: character\_specification\
labels: brute\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Characters\\

</details>

<details>

<summary>Brute Officer General</summary>

#### Input Pins

pinId: Character Type\
dataType: ai\_brute\_officer\_character\_type\
defaultValue: String: AICharacterTypeIdTable.brute\_captain Editor Settings:\\

#### Output Pins

pinId: Character Specification\
dataType: character\_specification\
labels: brute\_officer\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Characters\\

</details>

<details>

<summary>Brute Chieftain General</summary>

#### Input Pins

pinId: Character Type\
dataType: ai\_brute\_chieftain\_character\_type\
defaultValue: String: AICharacterTypeIdTable.brute\_chieftan Editor Settings:\\

#### Output Pins

pinId: Character Specification\
dataType: character\_specification\
labels: brute\_chieftain\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Characters\\

</details>

<details>

<summary>Grunt General</summary>

#### Input Pins

pinId: Character Type\
dataType: ai\_grunt\_character\_type\
defaultValue: String: AICharacterTypeIdTable.grunt\_conscript\_a Editor Settings:\\

#### Output Pins

pinId: Character Specification\
dataType: character\_specification\
labels: grunt\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Characters\\

</details>

<details>

<summary>Elite General</summary>

#### Input Pins

pinId: Character Type\
dataType: ai\_elite\_character\_type\
defaultValue: String: AICharacterTypeIdTable.elite\_mercenary Editor Settings:\\

#### Output Pins

pinId: Character Specification\
dataType: character\_specification\
labels: elite\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Characters\\

</details>

<details>

<summary>Hunter General</summary>

#### Input Pins

pinId: Character Type\
dataType: ai\_hunter\_character\_type\
defaultValue: String: AICharacterTypeIdTable.hunter Editor Settings:\\

#### Output Pins

pinId: Character Specification\
dataType: character\_specification\
labels: hunter\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Characters\\

</details>

<details>

<summary>Jackal General</summary>

#### Input Pins

pinId: Character Type\
dataType: ai\_jackal\_character\_type\
defaultValue: String: AICharacterTypeIdTable.jackal\_freebooter Editor Settings:\\

#### Output Pins

pinId: Character Specification\
dataType: character\_specification\
labels: jackal\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Characters\\

</details>

<details>

<summary>Marine General</summary>

#### Input Pins

pinId: Character Type\
dataType: ai\_marine\_character\_type\
defaultValue: String: AICharacterTypeIdTable.marine\_assault Editor Settings:\\

#### Output Pins

pinId: Character Specification\
dataType: character\_specification\
labels: marine\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Characters\\

</details>

<details>

<summary>Skimmer General</summary>

#### Input Pins

pinId: Character Type\
dataType: ai\_skimmer\_character\_type\
defaultValue: String: AICharacterTypeIdTable.skimmer Editor Settings:\\

#### Output Pins

pinId: Character Specification\
dataType: character\_specification\
labels: skimmer\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Characters\\

</details>

<details>

<summary>Sentinel Boss General</summary>

#### Input Pins

pinId: Character Type\
dataType: ai\_sentinel\_boss\_character\_type\
defaultValue: String: AICharacterTypeIdTable.adjutant\_resolution\_spire Editor Settings:\\

#### Output Pins

pinId: Character Specification\
dataType: character\_specification\
labels: sentinel\_boss\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Characters\\

</details>

<details>

<summary>Harbinger General</summary>

#### Output Pins

pinId: Character Specification\
dataType: character\_specification\
labels: inquisitor\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Characters\\

</details>

<details>

<summary>Characters For Squad General</summary>

#### Input Pins

pinId: Entry1\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry2\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry3\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry4\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Squad Specification\
dataType: squad\_specification\
labels: character\_group\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Characters For Drop Pods General</summary>

#### Input Pins

pinId: Entry1\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry2\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry3\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry4\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Squad Specification\
dataType: squad\_specification\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>General Characters For Phantom General</summary>

#### Input Pins

pinId: Entry1\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry2\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry3\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry4\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Squad Specification\
dataType: squad\_specification\
labels: phantom\_general\_passenger\_group\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Large Characters For Phantom General</summary>

#### Input Pins

pinId: Entry1\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry2\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry3\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry4\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Phantom Large Passengers\
dataType: squad\_specification\
labels: phantom\_general\_passenger\_group\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Characters Groups For Phantom General</summary>

#### Input Pins

pinId: Entry1\
dataType: squad\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry2\
dataType: squad\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry3\
dataType: squad\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry4\
dataType: squad\_specification\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Phantom Passengers\
dataType: squad\_specification\
labels: phantom\_full\_passenger\_group\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Vehicle Cargo For Phantom General</summary>

#### Input Pins

pinId: Large Cargo\
dataType: vehicle\_specification\
defaultValue: String: nil Editor Settings:

pinId: Small Cargo 1\
dataType: vehicle\_specification\
defaultValue: String: nil Editor Settings:

pinId: Small Cargo 2\
dataType: vehicle\_specification\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Phantom Vehicle Cargo\
dataType: squad\_specification\
labels: phantom\_vehicle\_cargo\_group\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Loadout For Phantom General</summary>

#### Input Pins

pinId: Phantom Passengers\
dataType: squad\_specification\
defaultValue: String: nil Editor Settings:

pinId: Phantom Vehicle Cargo\
dataType: squad\_specification\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Phantom Passengers Out\
dataType: squad\_specification\
labels: phantom\_full\_loadout\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Ghost General</summary>

#### Input Pins

pinId: Driver\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Config\
dataType: number\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Vehicle Specification Entry\
dataType: vehicle\_specification\
labels: small\_vehicle\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Vehicles\\

</details>

<details>

<summary>Wraith General</summary>

#### Input Pins

pinId: Driver\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Gunner\
dataType: character\_specification\
defaultValue: String: nil Editor Settings:

pinId: Config\
dataType: number\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Vehicle Specification Entry\
dataType: vehicle\_specification\
labels: large\_vehicle\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\_Vehicles\\

</details>

<details>

<summary>Vehicles For Squad General</summary>

#### Input Pins

pinId: Entry1\
dataType: vehicle\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry2\
dataType: vehicle\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry3\
dataType: vehicle\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry4\
dataType: vehicle\_specification\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Squad Specification\
dataType: squad\_specification\
labels: vehicle\_group\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Merge Squad Specifications General</summary>

#### Input Pins

pinId: Entry1\
dataType: squad\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry2\
dataType: squad\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry3\
dataType: squad\_specification\
defaultValue: String: nil Editor Settings:

pinId: Entry4\
dataType: squad\_specification\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Squad Specification\
dataType: squad\_specification\
labels: full\_squad\_specification\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Build Squad Spawn Definition General</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Encounter\
Team\
Squad Specification

pinId: Encounter\
dataType: encounter Editor Settings:

pinId: Team\
dataType: team Editor Settings:

pinId: Squad Specification\
dataType: squad\_specification Editor Settings:

pinId: Spawn Overrides\
dataType: spawn\_overrides\
defaultValue: String: nil Editor Settings:

#### Output Pins

pinId: AI Squad Definition\
dataType: ai\_squad\_definition\
userData: Editor Settings: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Drop Pod Spawn Settings General</summary>

#### Input Pins

pinId: Spawn Time Window\
dataType: number\
defaultValue: Float: 3.0 Editor Settings:

pinId: Spawn Overrides\
dataType: spawn\_overrides\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Drop Pod Spawn Settings\
dataType: drop\_pod\_spawn\_settings\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Build Drop Pod Squad Spawn Definition General</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Encounter\
Team\
Squad Specification\
Drop Pod Spawn Settings

pinId: Encounter\
dataType: encounter Editor Settings:

pinId: Team\
dataType: team Editor Settings:

pinId: Squad Specification\
dataType: squad\_specification Editor Settings:

pinId: Drop Pod Spawn Settings\
dataType: drop\_pod\_spawn\_settings Editor Settings:

#### Output Pins

pinId: AI Squad Definition\
dataType: ai\_squad\_definition\
userData: Editor Settings: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Build Phantom Air Drop Squad Spawn Definition General</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Encounter\
Team\
Squad Specification\
Phantom Air Drop Settings

pinId: Encounter\
dataType: encounter Editor Settings:

pinId: Team\
dataType: team Editor Settings:

pinId: Squad Specification\
dataType: squad\_specification Editor Settings:

pinId: Phantom Air Drop Settings\
dataType: phantom\_air\_drop\_settings Editor Settings:

#### Output Pins

pinId: AI Squad Definition\
dataType: ai\_squad\_definition\
userData: Editor Settings: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Phantom Air Drop Settings General</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Location

pinId: Location\
dataType: object Editor Settings:

pinId: Phantom Air Drop Ship Modifiers\
dataType: phantom\_air\_drop\_ship\_modifiers\
defaultValue: String: nil Editor Settings:

pinId: Phantom Air Drop Drop Modifiers\
dataType: phantom\_air\_drop\_drop\_modifiers\
defaultValue: String: nil Editor Settings:

pinId: Spawn Behavior Overrides\
dataType: spawn\_behavior\_overrides\
defaultValue: String: nil Editor Settings:

#### Output Pins

pinId: Phantom Air Drop Settings\
dataType: phantom\_air\_drop\_settings\
userData: Editor Settings: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Phantom Air Drop Drop Modifiers General</summary>

#### Input Pins

pinId: Initial Combat State\
dataType: actor\_basic\_combat\_status\
defaultValue: String: nil Editor Settings:

pinId: Passenger Seat Preference\
dataType: air\_drop\_passenger\_seat\_preference\
defaultValue: Enumerable: PASSENGER\_SEAT\_PREFERENCE.Both Editor Settings:

pinId: Passenger Drop Height\
dataType: number\
defaultValue: Float: 2.0 Editor Settings:

pinId: Vehicle Drop Height\
dataType: number\
defaultValue: Float: 2.0 Editor Settings:\\

#### Output Pins

pinId: Phantom Air Drop Drop Modifiers\
dataType: phantom\_air\_drop\_drop\_modifiers\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Phantom Air Drop Ship Modifiers General</summary>

#### Input Pins

pinId: Chin Gun Present\
dataType: bool\
defaultValue: Bool: true Editor Settings:

pinId: Side Gunner Type\
dataType: phantom\_side\_gunner\
defaultValue: String: nil Editor Settings:

pinId: Attack After Drop Duration\
dataType: number\
defaultValue: Float: 0.0 Editor Settings:\\

#### Output Pins

pinId: Phantom Air Drop Ship Modifiers\
dataType: phantom\_air\_drop\_ship\_modifiers\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Spawn Behavior Overrides General</summary>

#### Input Pins

pinId: Braindead\
dataType: bool\
defaultValue: Bool: false Editor Settings:

pinId: Blind\
dataType: bool\
defaultValue: Bool: false Editor Settings:

pinId: Deaf\
dataType: bool\
defaultValue: Bool: false Editor Settings:

pinId: Magic Sight\
dataType: bool\
defaultValue: Bool: false Editor Settings:\\

#### Output Pins

pinId: Spawn Behavior Overrides\
dataType: spawn\_behavior\_overrides\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Spawn At Location General</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Location

pinId: Location\
dataType: object Editor Settings:

pinId: Radius\
dataType: number\
defaultValue: Float: 1.0 Editor Settings:

#### Output Pins

pinId: Spawn Location Override\
dataType: spawn\_location\_override\
userData: Editor Settings: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Spawn In Area General</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Area Object

pinId: Area Object\
dataType: object Editor Settings:

#### Output Pins

pinId: Spawn Location Override\
dataType: spawn\_location\_override\
userData: Editor Settings: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Spawn Overrides General</summary>

#### Input Pins

pinId: Initial Combat State\
dataType: actor\_basic\_combat\_status\
defaultValue: String: nil Editor Settings:

pinId: Initial Facing\
dataType: number\
defaultValue: String: nil Editor Settings:

pinId: Spawn Location Override\
dataType: spawn\_location\_override\
defaultValue: String: nil Editor Settings:

pinId: Spawn Behavior Overrides\
dataType: spawn\_behavior\_overrides\
defaultValue: String: nil Editor Settings:\\

#### Output Pins

pinId: Spawn Overrides\
dataType: spawn\_overrides\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Targetable Object Overrides General</summary>

#### Input Pins

pinId: Vehicle Targetable\
dataType: bool\
defaultValue: String: nil Editor Settings:

pinId: Grenade Targetable\
dataType: bool\
defaultValue: String: nil Editor Settings:

pinId: Minimum Range\
dataType: number\
defaultValue: String: nil Editor Settings:\
MinRange: 0.0\
MaxRange: 20.0\
Step: 0.5 Editor Settings:

pinId: Maximum Range\
dataType: number\
defaultValue: String: nil Editor Settings:\
MinRange: 0.0\
MaxRange: 20.0\
Step: 0.5 Editor Settings:\\

#### Output Pins

pinId: Targetable Object Overrides\
dataType: targetable\_object\_overrides\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Is Object AI Targetable General</summary>

#### Node Rules

ruleID: RequiredNodeInput\
RequiredProperties:\
Object

pinId: Object\
dataType: object Editor Settings:

#### Output Pins

pinId: Is Targetable\
dataType: bool\
userData: Editor Settings: Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Get Current AI Targetable Object Count General</summary>

#### Output Pins

pinId: Count\
dataType: number\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Max AI Targetable Objects General</summary>

#### Output Pins

pinId: Count\
dataType: number\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>

<details>

<summary>Get AI Targetable Objects General</summary>

#### Output Pins

pinId: Count\
dataType: object\_list\
userData:\
Editor Settings:

#### Node Category: Unused\_AIToolkit\\

</details>