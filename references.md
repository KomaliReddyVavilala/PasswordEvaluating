##References
## 1. Common Password Attacks

### Brute Force Attack
- **Definition**: Systematic trial of all possible character combinations
- **How it works**:
  - Starts with 1-character passwords, progressively increases length
  - Modern GPUs can test billions of combinations per second
- **Vulnerable passwords**:
  - Short passwords (<8 characters)
  - Simple character sets (only lowercase letters)
- **Protection**:
  - Minimum 12-character passwords
  - Account lockout after multiple failed attempts

### Dictionary Attack
- **Definition**: Uses precompiled lists of common passwords and words
- **How it works**:
  - Tests variations of dictionary words (e.g., "password1", "Password!")
  - Includes leaked passwords from data breaches
- **Vulnerable passwords**:
  - Any recognizable word or phrase
  - Common substitutions (e.g., "P@ssw0rd")
- **Protection**:
  - Use truly random character combinations
  - Avoid any dictionary words, even with substitutions

## 2. Password Strength Evaluation Tools

| Tool | URL | Key Features | Limitations |
|------|-----|-------------|------------|
| Password Meter | [passwordmeter.com](https://passwordmeter.com) | Detailed scoring breakdown, immediate feedback | Doesn't check against known breached passwords |
| Kaspersky Password Checker | [password.kaspersky.com](https://password.kaspersky.com) | Estimates cracking time, checks against dictionaries | Requires email for full report |
| Have I Been Pwned | [haveibeenpwned.com/Passwords](https://haveibeenpwned.com/Passwords) | Checks against known breached passwords | Doesn't evaluate complexity |

## 3. Password Security Best Practices

### Length vs Complexity
- **Priority**: Length > Complexity
  - A 16-character all-lowercase password is stronger than an 8-character complex one
  - Example: "correcthorsebatterystaple" vs "P@ssw0rd!"

### Multi-Factor Authentication (MFA)
- **Types**:
  1. Something you know (password)
  2. Something you have (phone, security key)
  3. Something you are (fingerprint, face ID)
- **Recommendation**: Always enable MFA where available


## 5. Password Managers

| Manager | Type | Platforms | Key Feature |
|---------|------|-----------|-------------|
| Bitwarden | Cloud-based | All | Open source, free tier available |
| KeePass | Local | Windows (with cross-platform ports) | Fully offline, highly customizable |
| 1Password | Cloud-based | All | Excellent UI, travel mode |
