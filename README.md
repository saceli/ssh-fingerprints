# SSH Fingerprints

This repository contains my public SSH key fingerprints for verification purposes.

All of my commits are signed with SSH!

## My Fingerprints

| Algorithm | Fingerprint |
|-----------|-------------|
| ED25519 (256-bit) | `SHA256:9YwuAPjhCPQvQfZyRtNvbbUu3RkdEol09crVHeMBqvM` |

---

## How to Verify My Commits

### Method 1: Verify Git Commit Signatures (SSH Signing)

After cloning the repository and being in the directory where it was cloned run one of these commands:

```bash
# Verify the latest commit
git verify-commit HEAD

# Verify a specific commit
git verify-commit <commit-hash>

# Verify all commits in the current branch
git log --show-signature
```

## Security Notes

- If the fingerprint ever changes unexpectedly, it could indicate a **man-in-the-middle attack**.
- This fingerprint is static for this key. If I rotate keys, this README will be updated.

## Keys Rotation Log
| Key Number | Date & Time | Algorithm | Fingerprint |
|------------|-------------|-----------|-------------|
|     01     | 16/07/2026 18:14 |  ED25519  |`SHA256:9YwuAPjhCPQvQfZyRtNvbbUu3RkdEol09crVHeMBqvM`|

> NOTE: All Date & Time formats are in DD/MM/YYYY HH:MM and their timezone is UTC since it's constant all year.

---

## Contact

If you notice a discrepancy or have questions about key verification, please reach out through a trusted channel.
