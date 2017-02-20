# outbounty
storing huge java objects outside local JVM (other jvms, nosql instances, fs?)

for example we have OOP with oversizing some specific object of type TooBigObject
we create Outside < TooBigObject > with very similar interface (operation set) and use it instead of TooBigObject
