This is a quick toolbox full of easy-to-use information security solutions that anyone can adopt to prevent having their accounts and vital data compromised. It's particularly useful for journalists looking to establish secure channels of communication with sources.

Also check out [EFF's Surveillance Self-Defense guides](https://ssd.eff.org/en).

_Last updated October 17, 2017_

**[Pretty Good Privacy (PGP)](https://ssd.eff.org/en/module/introduction-public-key-cryptography-and-pgp)**: PGP is a type of encryption that involves a pair of keys – one public and one private – to encrypt messages that only people with the key can decrypt. 

PGP can be complex for the layperson to setup, but there’s a simple solution for browsers in the form of [Mailvelope](https://www.mailvelope.com/en/) where you can easily generate new keys, encrypt emails and other online text fields. The main drawback with Mailvelope is that it’s only for webpages and webmail. 

If you’re using Outlook, Thunderbird or another local email client, there are detailed instructions for both [Mac](https://ssd.eff.org/en/module/how-use-pgp-mac-os-x) and [Windows](https://www.deepdotweb.com/2013/11/11/pgp-tutorial-for-newbs-gpg4win/). 

Once you have it setup though, encrypting and decrypting messages is a straightforward process.

Here's a simplified primer on basic Windows PGP setup and use, regardless of what email app you're using. Things are similar for Mac, though the menu names and placement might be a little different:

1. Download for GPA4Win: http://gpg4win.org/download.html

2. Make certain GPA is checked among the things to install (it's unchecked by default)

3. Finish the install

4. Click "Keys > New key...""

5. Add alias information -- your email and name

6. Create a password. This is VERY important to remember as you'll use it each time you encrypt or decrypt something

7. Select to make a backup key (it will save as an .asc file)

8. Find where it stored your key. Save this somewhere safe.

IMPORTING OTHER PEOPLE'S KEYS

If someone sends you their public PGP key block, here's how to add it to your keychain:

1. Click "Keys > Import Keys...""

2. Select the .asc or .txt file of person's key

3. Should say 1 public key imported

FINDING PUBLIC PGP KEYS

Sometimes you want to contact someone who shares their PGP key online publicly but who hasn't sent it to you directly. To do this:

1. Go to "Server > Retrieve keys..." to search for PGP keys by email, fingerprint or key ID. If you see someone has shared their fingerprint online, this is how you would find it

ENCRYPTING MESSAGES

To encrypt secret messages you want to send via whatever messaging means you want:

1. Go to Clipboard

2. Type message

3. Click Encrypt

4. Select the key sending the message (yours) and the one receiving it (the receiver's)

4. Copy and paste encoded text from the "-----BEGIN PGP MESSAGE-----" to "-----END PGP MESSAGE-----" lines into an email or other message and send it

DECRYPTING MESSAGES

If you receive an encrypted PGP message from someone whose key is in your chain:

1. Copy PGP string from received email

2. Paste into Clipboard

3. Click Decrypt and enter your password if prompted

DISPLAYING YOUR PGP KEY ONLINE

1. Right click your key in the Keyring Manager and click "Send key..."" to upload it to the MIT public directory. This will allow potential sources to find your public key without you having to send it. Note: it may take about 20-30 minutes for the server to full sync before people can find your key once you've submitted it.

2. Then copy your Fingerprint and either put it on a Github page or tweet it out

3. Link in Twitter handle to .asc file or tweet containing the fingerprint


### Secure Messaging

**[Signal](https://en.wikipedia.org/wiki/Signal_(software))**: This is an effective encrypted texting app for your [Android smartphone](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms&hl=en) or [iPhone](https://itunes.apple.com/us/app/signal-private-messenger/id874139669?mt=8). It only works when texting people who also use Signal, but it's about as fast and secure as encrypted texting can be.


**[ProtonMail](https://protonmail.com/signup)**: If you really need secure email communications, using ProtonMail is free and [allegedly the only email system the NSA can’t hack](http://www.forbes.com/forbes/welcome/?toURL=http://www.forbes.com/sites/hollieslade/2014/05/19/the-only-email-system-the-nsa-cant-access/&refURL=&referrer=).


**[Telegram](https://telegram.org/)**: A secure messaging app integrated across mobile and desktop platforms.


**[WhatsApp](https://www.whatsapp.com/)**: Another end-to-end encrypted private messaging app that's pretty popular internationally. Be aware of WhatsApp's [past security issues](http://www.telegraph.co.uk/technology/2017/03/16/whatsapp-security-problem-leaves-millions-users-exposed-hackers/).


### Secure Accounts

**[LastPass](https://www.lastpass.com/)**: This is a password manager extension for your browser and with the [mobile app]( https://lastpass.com/misc_download2.php) on your phone. The beauty of LastPass, aside from being a free password manager (many other services cost) is that it encrypts all your information on the server side. So even if someone cracked LastPass’ server, they still wouldn’t be able to get at your stored information. It will also generate strong passwords for you and save them automatically.


**[Strong Password Generator](https://strongpasswordgenerator.com/)**: If you don't want to use the LastPass password generator, this is a great alternative that actually generates even stronger random passwords. Because it shows you the password that's been generated, you can make certain it follows whatever arcane password rules a certain website may require. Just plug it into LastPass and you're set.


**[Two-factor authentication](https://en.wikipedia.org/wiki/Multi-factor_authentication)**: Also known as 2FA, this provides another layer of security where once your login password is entered, the website texts an additional verification code to your phone, which you must enter before proceeding. This insures that only those in physical possession of your smartphone can login to your services. This, ostensibly, confines the only valid user to you. [EFF has specific guides for major websites](https://www.eff.org/deeplinks/2016/12/12-days-2fa-how-enable-two-factor-authentication-your-online-accounts). If the feature is available, input your smartphone number. 


**[Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=en)**: A great 2FA app for your phone, which you should use wherever available.


### Secure Browsing

**[HTTPS Everywhere](https://www.eff.org/https-everywhere)**: For your daily browsing activities, at the very least install this simple browser extension and mobile app that enforces the use of the HTTPS protocol, which is more secure than the standard HTTP.


**[The Onion Router (TOR)](https://www.torproject.org/download/download)**: For more robust browsing protection, TOR is slow-ish but effective for masking your online activities from prying eyes. Simple download the installer and it will setup a Firefox browser instance configured for super secure encrypted Internet connections. You don’t have to use TOR for everything, but it’s great for browsing you really don’t want to have tracked.


**[Lookout](https://play.google.com/store/apps/details?id=com.lookout&hl=en)**: This is another VPN, only geared toward mobile devices.


**[DuckDuckGo](https://duckduckgo.com/)**: To avoid being tracked every step of your online research, a secure, anonymous alternative to Google Search is DuckDuckGo, which claims not to collect anything on its users.


### Secure Devices

**Biometrics**: If your smartphone, laptop or tablet supports biometric access, use it. The app version of LastPass will usually ask you to set this up. Unlocking the phone with a fingerprint swipe or facial recognition takes a little getting used to and might be annoying at first, but it’s far more secure should you somehow lose your device.