I got fed-up with the complexity of JAXB, and The incompatibility issues between 2.0 and 2.1.
I needed flexible, and simple serialization of POJOs that have polymorphic lists.  Or of Tree like POJOs.  JAXB forces you to use weird annotations to have that work, and sometimes it does not.
This will be very simple.  Annotate just the fields you need and that is it.  Your annotated class methods will be called as they should.
Only limitations is that you must have a default constructor.