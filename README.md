Quick-and-dirty obfuscation for strings, designed to
hide URL parameters from the casual experimenter without
adding too much length. A little randomness is baked
in to make it look like the parameters are constantly
changing, even if they're not.

Obviously this is NOT SECURE; don't rely on it for strong secrecy.
A chosen-plaintext attack will recover the key, just like xor.

Only works for ASCII strings.  Not Unicode-safe.
