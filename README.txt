The two prominent files for the modification were:
FirstPersonProjectile.uasset
clone.uasset

The FirstPersonProjectile nodes were altered to run a 'for loop' that would spawn the 'clone' asset a certain number of times upon impact with an actor. 
This simulated the 'cluster' effect. 

The clone file is a duplication of the FirstPersonProjectile that gave each child projectile the capability to emit an effect from the random choice of an explosion,
fire, or sparks. 

*NOTE* - The random feature for the clone file has a flaw in its logic; therefore each child projectile emits multiple fx.