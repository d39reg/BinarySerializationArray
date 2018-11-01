# BinarySerializationArray
Translate object and array types as binary data which could use for compression data.

Binary data presents:
First byte have 8 bits each four bits for type data.
Last bytes is a data. Data could be: (Undefined, Null, False, True, Integer, String, Array, Function, Object)
