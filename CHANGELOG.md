# Changelog

## 1.3.1

### Minor changes

* Frame sizes are once again required to be aligned to 16 bytes
  This restriction was relaxed in 1.3.0, but due to compatibility concerns
  we'll put this restriction back in for the time being.

## 1.3.0

### Major changes

* Synchronized version numbers with the Python release
* Added cryptographic materials managers
* Added data key caching
* Moved to deterministic IV generation

### Minor changes

* Added changelog
* Made elliptic curve signatures length deterministic
* Various minor improvements
