# Custom Sheep

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`texture` | [String]() | *mandetory* | The location for the texture in the assets folder.

### Example Code

```json
{
	"type": "ccpacks:animal_entity",
	"subtype": "sheep",
	"identifier": "example_pack:sheep",
	"texture": "minecraft:textures/entity/sheep.png"
}
```