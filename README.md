# DataManager

Datamanager is a python library where you can encrypt strings and values.

Here is a basic tutorial containing the functions we have currently.

## Importing the library

This code calls the library.

```python
# Call our library

import datamanager.datamanager as dm
```

## Creating the key

```python
# Create the key (This is important.)

key = dm.generate_key()
```

## Encryption and Decryption.

```python
# Encrypt our message, which is set as "Hello World"

enc = dm.encrypt_message(key, "Hello, World!")

dec = dm.decrypt_message(key, enc)
```

That is around *everything* we have in our library.

# Happy Coding from TunaCoders!