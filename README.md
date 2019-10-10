A NLG component for the Minecraft domain
========================================

Compilation: run `./gradlew shadowJar`

Running: `java -cp build/libs/minecraft-inlg2019-generation-0.1.0-SNAPSHOT-all.jar de.saar.coli.minecraft.experiments.Inlg2019`
will run the example class for the iNLG paper, which constructs a model and generates instructions
using this model.

The grammar can be found in `src/main/resources/de/saar/coli/minecraft/experiments/inlg2019.irtg`.

The grammar for Section 4 of the paper can be found in `src/test/resources/minecraft.irtg`.
