# modrinth-client.xa1

modrinth-client.xa1: Modrinth client implemented in [Xarpite](https://github.com/MirrgieRiana/xarpite)

## Example

```shell
$ ./.xarpite/xarpite/xa '@USE("io.github.mirrgieriana:modrinth-client:0.0.1-SNAPSHOT"); search("Farmer$(APOS)s Delight").hits.0.description'
A cozy expansion to farming and cooking!

$ ./.xarpite/xarpite/xa '@USE("io.github.mirrgieriana:modrinth-client:0.0.1-SNAPSHOT"); getProject("R2OftAxM").title'
Farmer's Delight

$ ./.xarpite/xarpite/xa '@USE("io.github.mirrgieriana:modrinth-client:0.0.1-SNAPSHOT"); getProject(fileSearch("FarmersDelight-1.21.1-1.2.9.jar").project_id).title'
Farmer's Delight

$ ./.xarpite/xarpite/xa '@USE("io.github.mirrgieriana:modrinth-client:0.0.1-SNAPSHOT"); search("Create Addon").hits().title'
Create: Addon Compatibility
Create: Addon frenzy
Create ADDONS
Create Addons Translations RU
Create: Addons Improved
Saro´s Create addon
The Create Addon
Vasi's Create addon
Create: Too Many Addons
Create: ALL THE ADDONS
```
