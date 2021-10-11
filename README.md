# 1.8.9-forge-template

### how to setup
- `gradlew setupDecompWorkspace`
- `gradlew idea`
- add `-Dmixin.debug.verbose=true -Dmixin.debug.export=true -Dfml.coreMods.load=com.newwares.templatemod.FMLLoadingPlugin -DdebugBytecode=true` to your "run minecraft client" jvm args
- add `--tweakClass org.spongepowered.asm.launch.MixinTweaker --mixin.config "mixins.templatemod.json"` to your "run minecraft client" program args
- rename all instances of `templatemod` to your modid
- rename all instances of `newwares` to whatever you want
