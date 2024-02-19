# SWEET32: Birthday Attacks on 64-bit Block Ciphers in TLS and OpenVPN

## Overview
SWEET32 is a security vulnerability that affects block ciphers with 64-bit blocks, such as Triple DES (3DES) and Blowfish, when used in TLS and OpenVPN protocols. Discovered by researchers Karthikeyan Bhargavan and Gaëtan Leurent, the attack allows an attacker to recover sensitive plaintext data from encrypted connections under certain conditions.

## How It Works
The attack exploits the birthday paradox in cryptography, where the probability of two blocks of plaintext encrypting to the same ciphertext block significantly increases with the volume of data encrypted under the same key. In the context of SWEET32, an attacker can use this vulnerability to decrypt HTTPS traffic by generating and capturing a large number of encrypted requests.

## Affected Systems
- Systems using block ciphers with 64-bit blocks in CBC mode, particularly 3DES and Blowfish.
- TLS (Transport Layer Security) sessions that allow these ciphers.
- OpenVPN connections configured to use these vulnerable ciphers.

## Exploitation
Exploitation requires:
1. A Man-in-the-Middle (MitM) position to capture a large volume of encrypted traffic.
2. The victim's encrypted traffic must include some repetitive plaintext patterns.
3. Computational resources to analyze the captured data and identify cryptographic collisions.

## Mitigation
- Disable vulnerable 64-bit block ciphers and use stronger ciphers like AES.
- For TLS configurations, administrators should configure servers to prioritize secure cipher suites.
- Limit the amount of data encrypted with the same key in VPN connections and implement key renegotiation policies.

## Conclusion
SWEET32 underscores the importance of using modern cryptographic standards and the need for regular updates to encryption algorithms and configurations to protect against evolving threats.

For more detailed information, refer to the original research by Karthikeyan Bhargavan and Gaëtan Leurent at [https://sweet32.info/](https://sweet32.info/).