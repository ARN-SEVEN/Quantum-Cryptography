# QUANTUM_ENCRYPTION
So this project is hybrid post-quantum encryption system for text messages, built for the post-quantum cryptography challenge at the Tinkerspace Kochi hackathon (with QuantumX and IBM), where our team placed 5th.
This project shows how to protect text messages against future quantum-capable attackers.
It's a hybrid encryption setup that combines:
 - **ML-KEM** (the NIST-standardised post-quantum key encapsulation mechanism) for establishing shared keys
 - **AES-256** for fast, widely trusted symmetric message encryption

The idea: quantum computers could eventually break the public-key schemes we rely on today, so key establishment needs to be quantum-resistant, while AES-256 continues to handle the actual message encryption efficiently.
This project is to learn how hybrid encryption works in practice and how post-quantum cryptography can be paired with a cipher that's already battle-tested, as quantum computing advances.
