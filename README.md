# Fuzzy-Hashes
Large list of fuzzy hashes of well-known malware for use with SSDEEP

---

### How to use this

1. Install SSDEEP on your analysis machine.
2. Download this text file.
3. If you have a particular file that you want to scan, do so with the following command: ```ssdeep -s -m malwareFuzzyHashes.txt file.exe```
4. If you want to recursively hunt for matches use: ```ssdeep -r -m malwareFuzzyHashes.txt *```
