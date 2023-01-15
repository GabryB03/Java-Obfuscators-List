# Java Obfuscators List
* [Allatori](https://allatori.com/) - Commercial. Somewhat popular choice in industry.
* [avaj](https://github.com/cg-dot/avaj) - FOSS. Has a nice way of generating decryption subroutines on string constants. Also has some CFG flattening which is always nice to see.
* [BisGuard](http://www.bisguard.com/) - Commercial. Relies entirely on class encryption (last time I checked, at least) so protection has quite a bit of room for improvement.
* [Bozar](https://github.com/vimasig/Bozar) - Points for FOSS. Has some cheap tricks that I have seen being used in the Minecraft community.
* [Branchlock](https://branchlock.net/) - Commercial. Shows up a bit in the Minecraft community.
* [Caesium](https://github.com/sim0n/Caesium) - FOSS. Has a transformer that implements a well-known HTML injection into any Java reverse-engineering tool that parses HTML tags.
* [ClassGuard](https://zenofx.com/classguard/) - Commercial. Relies mostly on class encryption with hardcoded AES keys in native libs. Pretty easy IDA/Binary Ninja/Ghidra exercise if you want to flex on your blog on something.
* [DashO](https://www.preemptive.com/products/dasho/overview) - Commercial. Shows up a bit in industry and has some interesting ideas (albeit probably outdated) in flow obfuscation.
* [JBCO](http://www.sable.mcgill.ca/JBCO/) - FOSS. Some interesting flow obfuscation techniques that still work in modern Java. Based on the Soot library which is also something worthwhile checking out.
* [JObf](https://github.com/superblaubeere27/obfuscator) - FOSS. Pretty outdated. Some of the transformations done show up in the Minecraft community so it can be worthwhile spending a bit of time taking a look at this.
* [JObfuscator](https://www.pelock.com/products/jobfuscator) - A simple commercial obfuscator.
* [NeonObf](https://github.com/MoofMonkey/NeonObf) - Mostly points for FOSS. Made up of the easier to defeat obfuscation techniques. NeonObf is also the name inspiration for Radon.
* [Paramorphism](https://paramorphism.dev/) - Commerical. Was one of the most unusual and unique obfuscators at the time it was an active project in that relied a lot more on the JVM's unusual way of loading JAR archives including zip entries with duplicated names and the fake directory trick. Used to be more commonly used before people started ripping ideas from Paramorphism.
* [ProGuard](https://www.guardsquare.com/proguard) - ProGuard is a command-line tool that reduces app size by shrinking bytecode and obfuscates the names of classes, fields and methods. It’s an ideal fit for developers working with Java or Kotlin who are primarily interested in an Android optimizer.
* [qProtect](https://mdma.dev/) - Commercial. Implements a lot of the more common obfuscation techiques into a single tool. Shows up a bit in the Minecraft community.
* [Radon](https://github.com/ItzSomebody/radon) - Open Source. Common and criticized obfuscator for Java.
* [Sandmark](http://sandmark.cs.arizona.edu/) - FOSS. Really old obfuscator research project led by Christian Collberg at the University of Arizona. Some interesting ideas in watermarking are here and some of the flow obfuscation ideas are good.
* [Skid Obfuscator](https://github.com/skidfuscatordev/skidfuscator-java-obfuscator) - Public proof-of-concept obfuscator using the MapleIR framework designed by cts & bibl 
* [SkidSuite2](https://github.com/GenericException/SkidSuite/tree/master/archive/skidsuite-2) - FOSS. Some pretty basic obfuscation techniques, nothing too special.
* [Stringer](https://jfxstore.com/stringer/) - Commercial. Pretty infamous for its complicated AES-based encryption/decryption routines and price. Does not really offer a whole lot of protection, but sometimes does show up in industry.
* [yGuard](https://www.yworks.com/products/yguard) - FOSS. Functionally equivalent to ProGuard.
* [Zelix KlassMaster](http://www.zelix.com/) - The Zelix KlassMaster™ Java obfuscator protects your Java code from decompilation and reverse engineering. Its advanced Flow Obfuscation, String Encryption, Integer Constant Encryption, Method Parameter Obfuscation, Reference Obfuscation and Method Parameter Changing technologies make it a true heavy duty Java obfuscator.