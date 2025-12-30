# modrinth-client.xa1

modrinth-client.xa1: Modrinth client implemented in Xarpite

## Example

```shell
$ ./xarpite/xa --jvm '@USE("./modrinth-client"); search("Farmer$(APOS)s Delight").hits.0.description'
A cozy expansion to farming and cooking!

$ ./xarpite/xa --jvm '@USE("./modrinth-client"); getProject("R2OftAxM").title'
Farmer's Delight
```
