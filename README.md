# Password-Strength-Analyzer
A real-time password strength analyzer that checks length, complexity, and patterns while calculating entropy and estimated crack time. Includes a secure password generator and SHA-256 hash preview to demonstrate basic cryptography concepts.

What it does:

Live strength meter — scores from Very Weak to Excellent as you type, with a color-coded bar
6 security checks — length ≥12, uppercase, lowercase, numbers, special characters, and no repeated patterns
Entropy metrics — shows bit entropy, charset pool size, and estimated crack time at 10 billion guesses/second
SHA-256 hash preview — demonstrates cryptographic hashing concepts in real-time
Password generator — creates cryptographically random 18-character passwords with full complexity, with a one-click copy button
Session history — tracks the last 5 passwords you've tested (masked for privacy)
Show/hide toggle — lets you mask the input field

Since browser APIs don't support MD5 natively, I've noted that in the hash section — in a real backend implementation you'd add MD5 + bcrypt/Argon2 for proper storage hashing.
