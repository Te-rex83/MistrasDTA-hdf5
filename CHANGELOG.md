\# Changelog



All notable changes to this project will be documented in this file.



This project follows semantic versioning:

https://semver.org/



---



\## \[0.1.0] – 2026-01-XX



\### Added

\- Streaming parser for Mistras DTA files using generator-based API

\- Incremental processing of hit, waveform, and metadata records

\- Native HDF5 export with chunked, append-only datasets

\- Separation of hit data, waveform data, and waveform metadata

\- Support for large DTA files without full in-memory loading



\### Changed

\- New package name: `mistrasdta-hdf5`

\- New Python import namespace: `mistrasdta\_hdf5`

\- API redesigned for streaming and application integration



\### Removed

\- Legacy `read\_bin()` API from upstream MistrasDTA

\- Implicit full-file loading behavior



\### Notes

\- This release is \*\*not API-compatible\*\* with the original MistrasDTA package.

\- The project is released as \*\*alpha\*\* while the API stabilizes.




\## \[0.1.1] – 2026-01-29



\### Changed

\- Fix in hdf5.py to explicitly handle None before writing to HDF5.


