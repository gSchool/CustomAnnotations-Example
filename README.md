## Create a simple custom annotation

1. Create 3 custom annotations
   * `@JsonSerializable` - Indicates that class is serializable to json
   * `@JsonElement` - Indicates that the field is to be serialized
   * `@Init` - Identifies the method that will initialize the data before serialization
2. Create a `Person` class and add our new annotations
3. Create a `ObjectToJsonConverter` class to serialize the object to json
4. Create a test to exercise your code
