# 🧪Task Report

## 1. Password Generation

I created a set of passwords with different characteristics:

| Password         | Description                          |
|------------------|--------------------------------------|
| `password`       | Simple, lowercase                    |
| `Password123`    | Adds uppercase + numbers             |
| `Pass123!`       | Adds a symbol                        |
| `P@55w0rd123!`   | Complex, substitutions               |
| `jU7#qT&9*Lx`    | Random, high complexity              |
| `123456`         | Common and weak                      |

## 2. Testing Method

Each password was tested, and feedback was recorded.

## 🔐 Password Evaluation Table

| Password         | Description                    | Time to Crack         | Strength Score (1–5) | Feedback                                                                 |
|------------------|--------------------------------|------------------------|----------------------|--------------------------------------------------------------------------|
| `password`        | Simple, lowercase              | < 1 second             | 1/5                  | Extremely weak; common word and no variation                            |
| `Password123`     | Adds uppercase + numbers       | A few seconds          | 2/5                  | Better than basic password, but still predictable and commonly used     |
| `Pass123!`        | Adds a symbol                  | Less than a minute          | 3/5                  | Good start; includes symbol, upper/lowercase, but still short           |
| `P@55w0rd123!`    | Complex, substitutions         | Several hours to days  | 4/5                  | Strong; uses leetspeak, symbols, mixed characters                       |
| `jU7#qT&9*Lx`     | Random, high complexity        | 200+ years             | 5/5                  | Excellent; long, random, full character diversity                       |
| `123456`          | Common and numeric             | < 1 second             | 1/5                  | Extremely common; often in data breaches                                |

## 4. Best Practices Identified

- Use **at least 12 characters**
- Combine **uppercase**, **lowercase**, **numbers**, and **symbols**
- Avoid using **dictionary words** or **predictable patterns**
- Prefer **random** or **generated** passwords
- Consider using a **password manager**

## 5. Common Password Attacks

- **Brute Force**: Tries every possible combination until it works. Long, complex passwords are more resistant.
- **Dictionary Attack**: Uses a list of common words and phrases. Avoiding real words helps protect against this.
- **Credential Stuffing**: Reuses known passwords. Avoid reusing passwords across sites.

## 6. Password Complexity & Security

Password complexity directly correlates with the time and resources needed to crack it. A longer password with a mix of characters exponentially increases the difficulty for an attacker to guess or brute-force it.

| Complexity | Time to Crack |
|------------|----------------|
| Simple (6 chars) | < 1 second |
| Moderate (8 chars, mix) | Minutes to hours |
| Strong (12+ chars, full mix) | Centuries (estimated) |
