# An Approximate Tamarin Analysis of the X3DH Key Agreement Protocol
## Albert Qi, Ronak Malik, and Justin Ye
### Spring 2024

As technology becomes increasingly integral in our daily lives, more and more people rely on messaging apps to communicate. However, it is also paramount that communication through these apps is secure and privacy is maintained; users need to be certain that their messages to others will not be intercepted. Signal is one such platform that claims it has strong security guarantees, including both forward secrecy and cryptographic deniability. In order to achieve these guarantees, it utilizes the X3DH key agreement protocol.

How can we be absolutely certain that the X3DH protocol does in fact achieve its guarantees, though? To test this, we utilize Tamarin, a security protocol verification tool, in order to formally verify the properties of an approximate version of the X3DH protocol. Through our implementation, we verify that both forward secrecy and cryptographic deniability are achieved.
