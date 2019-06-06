Two factor authentication through SMS is a pretty convenient yet containing many risks of  security in it.  Some attacks get users to install a malicious app on their smartphone  that can then read SMS messages and forward the codes to the attackers. Another exploit redirects SMS messages by hacking the cellular service using a variety of technical methods, or through social engineering, to forward codes to an attacker. " It's also possible to snoop on SMS messages for example by a government who mostly have control over the telecomunication network.

One of the example of it is Verification Code Forwarding Attack (VCFA). An example of how In a VCFA attack, the attacker triggers the delivery of a verification code to a victim and shortly after that, the attacker sends a direct SMS to the victim and phishes her to forward the code. If the victim forwards the code, the attacker can successfully bypass the SMS verification and get access to the victim’s account. VCFA involves social engineering to lure the victims on to giving the verification code that's received through SMS. This attack are possible because of some factors:

- Lack of awareness of phissing and other digital crime activity
- Personal data disclosure (voluntarily or involutarily) that makes this crime easier to operate. Disclosing our phone number or email in public that we link to our personal account could be blamed that this activity can still operate regardless of how simple it is.
- Attackers effort to run their activity unsuspectibally (Formatting of message for example)
- Victims can't verify if the sender is the rightful party or not

An experiment was conducted with 20 people, age of 25-35 and 70% are students, to ask them to resend the verification code by replying to an sms that's formatted so it looks that this message is right indeed came from Google. As a result, 5 people replied with the verifiction code to the attackers phone number which means that the rate of success is 25%. Through the interview, they found out that they did not have a clear understanding of what a Google phone number looks like. These explains of the core problems of SMS-based verification since SMS system does not provide any effective and usable means for users to verify the sender of messages.



Advices for end user:

- Never forward any verification code you receive

- Read the message carefully. If it states that someone is trying to get into your account who is not you, you should pay attention and create new security measures like changing your password etc.

- Beware of many social hacking methods

- Limit to whom you share your phone number, email, address, and many  other personal data.

  

Advices for web application developper:

- Adding Google recaptcha will prevent automated requests and also works 
  on mobile, but it won't prevent manual malicious requests.



Anyway, using two-factor authentication is better than having nothing at all. Thus, there are some options as the alternatives to SMS verification:



- Authentication apps as an alternative to SMS verification. There are plenty of apps like these and they aren't tied to a particular phone number and don't use the insecure SMS channel. The downside is it requires you to have a smartphone, particularly Android or iOS.
- Using a physical security keys





Sources:

https://www.slashgear.com/sms-two-factor-authentication-is-unsafe-use-these-instead-27539168/



Verification Code Forwarding Attack Short Paper

https://www.slashgear.com/sms-two-factor-authentication-is-unsafe-use-these-instead-27539168/

https://www.howtogeek.com/310418/why-you-shouldnt-use-sms-for-two-factor-authentication/

https://www.schneier.com/blog/archives/2017/05/criminals_are_n.html







