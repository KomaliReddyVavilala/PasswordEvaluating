
##  Objective
Evaluate what makes a password strong by creating and testing multiple password variations using online strength checkers, and document best practices for password security.

## Methodology
1. Created passwords with varying complexity:
   - Simple (common words, short length)
   - Moderate (mixed characters, medium length)
   - Strong (random characters, long length)
   - Passphrase (multiple uncommon words)
2. Tested each on [PasswordMeter.com](https://passwordmeter.com)
3. Analyzed results and identified patterns

## Password Test Results

| Password Type | Example | Score | Feedback Summary |
|--------------|---------|-------|------------------|
| **Weak** | `password123` | 12% | Too short, common words, lacks complexity |
| **Moderate** | `Summer2023!` | 68% | Mixed characters but predictable base word |
| **Strong** | `J#n7bX2!qL9$pR5*` | 100% | Excellent length and randomness |
| **Passphrase** | `CorrectHorseBatteryStaple!23` | 100% | Length compensates for word use |

## Key Findings
### What Makes a Password Strong?
 **Length matters most** (16+ characters ideal)  
 **Randomness** beats complexity (e.g., `XKc#2nP9` > `P@ssw0rd`)  
 **Passphrases** can be both strong and memorable  
 **Common substitutions** (`$` for `s`) don't fool modern crackers  

### Common Attack Methods
- **Brute Force**: Defeated by length (>12 chars)
- **Dictionary Attacks**: Avoid recognizable words
- **Credential Stuffing**: Never reuse passwords

##  Best Practices
1. **Use a password manager** (Bitwarden, 1Password)
2. **Enable MFA** wherever possible
3. **Never reuse** passwords across sites
4. **Prioritize length** over complexity
5. **Update regularly** (every 3-6 months)

