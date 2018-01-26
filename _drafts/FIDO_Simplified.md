The purpose of this article is to simplify the explanation of FIDO open standard protocols with minimal technical jargons.

Reality of OTP/Password

Let make the analogy of online authentication method with the physical access to your home/apartment.
The current dominant method of getting access to your home is by utilizing your identity via the key(username &password/PIN). So..what is wrong with that?

1. Key can get replicated easily. 
2. Key lock is vulnerable and attracted spot for intruders.
3. Maintaining too many keys is tiresome and difficult.
4. You can lost the key.
5. Using the same (master)key for all your homes is such a bad idea especially if you lost it. 

New Paradigm of Online Auth

FIDO improves traditional direct authentication to the server with a new approach. FIDO introduces a new proxy mechanism called "authenticator" to decouple the online authentication process. The user authentication event is happened entirely inside the user's device such as mobile device or token. The centralized FIDO server only verify the validity of the user device. In that way, the attacker can't temper user data and also the server is less interested for the attackers since there is no sensitive information stored there.

FIDO Alliance 

FIDO Alliance is initiated by companies like Google & Yubico to establish stronger authentication with interoperability.  


FIDO Protocols

There is 2 FIDO protocols called UAF and U2F. Basically, UAF provides password-less authentication by using biometric modialities and hardware tokens. U2F is a better MFA methodology for existing authentication approach (username/password). The design of authenticator in FIDO protocol depends on the needs of business and organization. Most of the FIDO vendors offers a way to integrate with existing identity management architecture of the system. 

