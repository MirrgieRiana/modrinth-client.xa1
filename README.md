# modrinth-client.xa1

modrinth-client.xa1: Modrinth client implemented in [Xarpite](https://github.com/MirrgieRiana/xarpite)

## Example

```shell
$ ./xarpite/xa --jvm '@USE("./modrinth-client"); search("Farmer$(APOS)s Delight").hits.0.description'
A cozy expansion to farming and cooking!

$ ./xarpite/xa --jvm '@USE("./modrinth-client"); getProject("R2OftAxM").title'
Farmer's Delight

$ ./xarpite/xa --jvm '@USE("./modrinth-client"); search("Create Addon").hits().title'
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
