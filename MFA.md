# IMPLEMENT MULTI-FACTOR AUTHENTICATION

*When an account is protected by a single password, the compromise of that password means the compromise of that account. Depending on the role a person plays in a company, the compromise of that account could lead to substantial losses. Multi-factor authentication makes it radically harder for the bad guys to compromise accounts, which in turn makes it harder for them to steal your data, money, etc. Multi-factor authentication adds another step to accessing accounts and services, but those extra seconds—literally seconds—are a small price to pay for one of the most cost-effective and powerful defenses you can put in place.*

Using either multi-factor authentication (MFA) – often called two-factor authentication (2FA) - is a way to harden accounts against compromise in the event a password is stolen or guessed. It adds one or more additional pieces of information as factors required in a login process. 

For about as long as we’ve had computers, accessing them has been, and continues to be, dependent upon two pieces of information: who you are, and what you know. “Who you are” is generally manifested in your login ID: Jane.Smith or JSmith or JaneS@gmail.com. “What you know” is your password (such as, rolltide123). 

A second security factor adds the concept of “what you have” to the mix. If you’ve ever logged into your bank’s website when you were away from home, you may have been presented with a message that said they didn’t recognize where you were logging in from, and asked you to enter a numeric code that was sent via text to your mobile phone.  That numeric code is the second factor, the “what you have,” which in this case is your cell phone, in addition to what you know (your password). The use of a second factor is a way to reduce the risk that an unauthorized person is trying to access your account. The odds of someone having your login credentials AND your mobile phone, for example, is pretty low.

*(If someone has taken you, and your devices, and is demanding your passwords and other factors, you've probably got a bag over your head, are rolling around in the back of a van, and have more pressing things to worry about than a little fraud).*

[...]

## Resources

### Native Capabilities
Check to see if any of the applications or web-based services you’re using offer MFA. An increasing number of them do. If they do, make sure all employees with accounts on that service implement it immediately.

### Google Authenticator
Google apps and services benefit from their own [MFA capability]( https://www.google.com/landing/2step/), which you install on your mobile phone. Google has also made the capability available to other web-based services. If it is compatible with the apps or services you use, implement it as soon as possible.

### Duo Security
[A commercial product](https://duo.com/) that is well done, highly regarded, and not terribly expensive (free up to 10 users). 

### Yubikey
If you’re really taking this 2FA thing seriously, and don’t want to use personal cell phones for receiving factors, [Yubikey](https://www.yubico.com/) is a very small and easy to use hardware-based solution. It is more expensive than Duo and requires a little more management on the part of your IT people. 


Next: [Make Backups and Check Them](/Backups.md)

---

Order your own copy of [The First Cybersecurity Book Your Company Will Ever Need](https://www.amazon.com/dp/B07S1RMRY1) at Amazon.com
