#### SOLID in Go in 8 minutes (5m Friday #5) (2020)
  Single responsible principle - a class should have one and only one reason to change
  Open closed principle - objects/entities should be open for extension but closed for modification
  Liskov substitution principle - q(x) - x of type T - provable then q(y) y of type S & is a substype of T - also provable.
    From provided example - if we can pass into this function the human type then we can pass into this function also the teacher type and the student type and that is true because they both implement that interface by inheriting those fields and thos methods
  Interface Segragation Principle - a client should never be forced to implement an interfacetha it doesn't use
  Dependency inversion principle - entities must depend on abstractions, not on concretions


https://www.youtube.com/watch?v=AKdvlr-RzEA