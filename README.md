# FILE-INTEGRITY-CHECKER

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: RAYAPATI MANOJ KUMAR

*INTERN ID*: CT04WK146

*DOMAIN*: CYBER SECURITY

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*Description : In today’s digital landscape, ensuring the integrity and authenticity of files is critical for maintaining trust, security, and operational reliability. Whether dealing with sensitive documents, configuration files, software packages, or logs, even a small unauthorized change could indicate a security breach, file corruption, or unintended error. To address this need, the File Integrity Checker project provides a lightweight and efficient Python-based solution for verifying the consistency of files over time using cryptographic hashing.

This tool is built using Python’s built-in hashlib library, which supports a variety of secure hash algorithms such as SHA-1, SHA-256, and SHA-512. The script primarily utilizes SHA-256, a robust and widely-used algorithm, to generate a unique digital fingerprint (hash) of a file. By comparing this fingerprint to a previously saved one, users can detect even the slightest modification in a file’s content.

The application follows a simple yet effective command-line interface (CLI) design. Upon execution, users can choose between two primary functionalities: (1) generating and saving a hash for a file, or (2) verifying a file’s integrity by comparing its current hash against a previously stored one.

In hash generation mode, the user selects a file, and the script reads it in binary mode, processes it in chunks to handle large files efficiently, and computes its SHA-256 hash. The resulting hash value is then saved to a text file specified by the user. This serves as a reference for future integrity checks.

In verification mode, the script again computes the hash of the selected file and compares it against the hash stored in the reference file. If the hashes match, it confirms that the file remains unaltered. If they do not match, the script warns the user that the file has likely been modified, either intentionally or due to corruption.

The File Integrity Checker is especially useful in environments that demand strict security, such as software development, forensic analysis, system administration, and data archival. It helps users detect tampering, monitor system files, validate backups, and maintain digital trust.

Since the tool is built entirely with Python’s standard libraries (hashlib and os), it requires no external dependencies, making it lightweight, portable, and easy to integrate into existing workflows or automation scripts. Additionally, the modular design allows for future enhancements such as GUI integration, multi-algorithm support, file watching capabilities, and email alert systems.

Overall, this project exemplifies how a simple yet powerful Python script can play a vital role in maintaining file security and operational integrity. It introduces users to core concepts of hashing, file handling, and basic cybersecurity practices, making it an excellent utility for students, professionals, and developers alike.

