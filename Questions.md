# Questions and Answers

### Answers to security-related questions from clients and the curious. All submissions treated with the utmost confidentiality

#### Who Should You Believe?

> I read your book and it all made sense to me. I like that there are simple and cheap options for the problems I've struggled to deal with (which no salesman has ever pointed out oddly enough) but I was reading something from <noted cybersecurity expert> yesterday and he basically said the exact opposite of what you did on several issues. He agreed in other areas, but still. This is the problem I have with cybersecurity: everyone sounds like they know what they're talking about but I can't follow your advice, his advice, the advice of my IT people.
>
> - Logistics Company CEO

I hope I made it very clear in the book that my advice was not the be-all and end-all, but a starting point. I actively encourage everyone who is struggling with these issues to start here, and expand the voices they listen to once they get comfortable with the issues at hand.

Having said that, you’re right in that there are a lot of opinions that all sound good and make perfect sense. Who to believe? Or rather who’s advice should you follow? Two things to consider:

- What specifically is the problem you’re facing and which piece of advice IS THE MOST APPROPRIATE FOR YOUR CURRENT SITUATION?
- Things will change. Rapidly. What makes sense today might not make sense in a year, or even a few months. Constant vigilance is one of the prices you have to pay in order to maintain a reasonably secure enterprise. TODAY I MIGHT BE RIGHT, BUT TOMORROW I COULD VERY WELL BE WRONG.

The subject matter expert who has never held a position in industry, or is speaking about a lab-perfect solution that’s never been put to use in real-world environments is still the last person you should be listening to for reasons that should be obvious. Solutions or advice that don’t take into consideration how you work or how people behave are no solutions at all. I might not give advice that meets their ideal, but then I’m not doing this gain nerd cred, I’m doing it to help you – the SMB owner/executive – make sense of one of the most confusing yet critical issues of the day.

---

#### Old, Old School

Today’s edition of “how in the world is that possible?” I bring you the curious case of the antique shop. Well, the business is not about buying and selling antiques, its a widget (actual line of business obfuscated to protect the innocent) factory. It employs just over a dozen people, who mainly work with their hands. It is precision work, but fairly dirty. “Skilled labor” is the term I’m looking for.

No, the “antique” aspect of this business is the three computers it uses. They were procured in the early ‘00s by a much larger firm, a customer of our client, and passed on to them when the bigger company upgraded their IT infrastructure a few years later. The operating system and software that runs on these systems would be familiar to you…but look quite dated. The thing is though, it is all perfectly functional from the perspective of the client. They boot up in the morning, they connect to the internet and the EDI system, the spreadsheet program does math, the word processing program churns out invoices and so on.

> “Everything works just fine. I don’t need the latest equipment. I can’t see anyone thinking I’m worth hacking. We print off copies of everything and file it the old fashioned way. I don’t even do online banking; almost everyone I do business with pays by check.”
> - CEO

With one exception, its hard to argue with that kind of logic. Security people in particular love to make fun of people who use old technology. “OMG don’t you know how vulnerable that is? Its hasn’t been supported (by the manufacturer) for years! The epic pwnage is seconds away!” All of that is true, but as a business owner the calculus is a little more complicated than “old vulnerable system vs. new better protected system.”

The client and his business is the reason why all of his employees can pay their mortgages, feed their kids, and go to the lake for a week every summer. It isn’t a super high margin business, so while everyone is doing OK, its not like there is a ton of money to throw at fresh-off-the-boat PCs and next-generation cyber awesomeness. If it ain’t broke, so the saying goes, don’t fix it.

The exception? That he’s not a target. [As we talk about in the book](/You_Are_A_Target.md), the mere presence of a CPU makes someone a target. Now the one saving grace is that the juice from these geriatric processors might not be worth the squeeze to pwn, but that’s not up to him or me, its up to the bad guys. And if they decide he’s worth attacking, and they’re successful (high probability), then he’s in for a hard (and expensive) time.

Yes, he could recover his business files from manual records. In that sense he’s luckier than most small firms who put their trust in their hard drives. Most of his equipment is analog and what is digital is fairly “dumb” and easily reset to factory settings. Work will continue, but trust is gone. Increasingly, large companies are getting their security act together and requiring that all their suppliers do too. Our client will need to upgrade sooner rather than later.

Thankfully, IT is relatively cheap, and he doesn’t need top-of-the-line equipment to start with. And the whole point of the book is that there is a lot he can do to protect himself, his business, his people, and his reputation that costs nothing.

If this situation resonates with you and what you do for a living, don’t be shamed or bullied by your choice of technology. Its OK to use old tech if you’ve taken a number (OK, a LOT) of precautions and taken the time to do a cost-benefit analysis and determined that getting the latest gear and defensive technology would be an ideal way to go broke. You’re in business, you’re not in the security business. Security is a process, and as long as you’re working the process, and making progress, that is all any reasonable person can ask.

---

#### You Always Have Options

A “Florida man” story, [ransomware edition](https://www.wcjb.com/content/news/City-of-Lake-City-moves-Forward-after-Cyber-Attack-511802711.html):

> The city manager of Lake City, Joe Helfenberg confirmed that the director of information technology, Brian Hawkins, was fired.
> The decision comes after a “Triple Threat” cyber attack that disables city servers, phones, and email that resulted in ransom.

A couple of things…

- It is the IT manager’s fault in the sense that he’s the person responsible for the IT systems, and the buck has to stop somewhere.

- It is also probably the case that, like every municipality I’ve ever dealt with, the IT manager never had the resources (financial, human, or technical) to do things properly. A ransomware infection was an inevitability. Where the buck should stop is the city manager, city council, or mayor, but good luck with that.
- Note the consulant (who has never had his business held ransom) and his advice to not pay. As I said in the book, paying is not a guarantee of success, but a “good” data-napper knows that a successful transaction is the key to financial success. Taking a ransom and not giving up keys is bad business. A “good” data-napper will let you decrypt a small sample of your files to demonstrate that you’ll get what you pay for; no digital forensics or incident response company is going to give you a couple of hours of labor for free to determine if they can recover ransomware keys. Just saying.
- Also note the comment that bitcoin is untracable. The ability to know exactly who is a part of a transaction is actually a feature of bitcoin (or rather the underlying blockchain technology). This is not to say that the money is recoverable, but depending on how badly the city wants to push this, they could come up with an identity…and then…I guess…indict them and hope for the best.
- If you really, really have a problem paying a ransom, and you happen to be hit with one of the variants for which decryption tools have been created, you can go to a site like No More Ransom! and see if you can sort things out yourself (or with the help of your own consultant).

There are no good courses of action when it comes to ransomware. If you don’t have current backups, you’re damned if you do and damned if you don’t. It is important to remember that this is not personal, just business. What is the best business decision for the role your organization plays in the lives of your employees, your customers, and in the case of government: citizens?

---

#### Pay the Ransom (Its OK, Really)

Nobody likes to be held hostage. I get it. I do. But when it comes to ransomware I’ve said from the beginning - and now others are starting to say it to - this is not personal: its just business.Find me someone who says “Don’t pay the ransom! Never pay the ransom!” and I’ll show you someone whose never been infected with ransomware and doesn’t have the fate of their business - and everyone who works for them - hanging in the balance. City administrations like Atlanta and Baltimore can take the high ground because its not their money. They’re civil servants who will have a job whether a ransom is paid or not. Hell, they’ll probably get bigger budgets and increase the size of their fiefdoms because of it.The ransomware market already exists, just like armed robbery exists. No one says strike your best Bruce Lee pose when accosted by a mugger: that’s a great way to get shot. No, you hand over your wallet and live to file a police report. Trying to bring morals into the mix is a great way to make victims feel bad about being victimized. Drawing parallels between “we don’t negotiate with terrorists” falls apart when you realize that that’s a position only a nation-state can hold.

---

#### Write Down Your Passwords

Want to start a security nerd slap fight? Ask two of them their opinions of one of [these little gems:](https://www.amazon.com/Internet-Password-Logbook-Cognac-Leatherette/dp/1631061941/ref=asc_df_1631061941/?tag=hyprod-20&linkCode=df0&hvadid=312128454859&hvpos=1o3&hvnetw=g&hvrand=15776274176568148044&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9028806&hvtargid=pla-492740856648&psc=1)

For years the conventional wisdom has been: never write down your passwords.

Conventional wisdom has also said: use unique, long, complex passwords on each and every account.

I don’t know about you, but I log into over a dozen different systems/accounts every day. I can’t remember that many long, complex passwords without resorting to some kind of trick or mnemonic or pattern that, in time, someone will be able to figure out and crack. The next best thing to a photographic memory is a password manager (something we talk about in the book). But what about writing down long, complex passwords?

That advice came from a different age. When computers were permeating the workplace and anyone could walk around the office and sneak a peek at the Post-It notes you stuck to your monitor with your password, and then commence their shenanigans posing as you online. Commercial cybersecurity was relatively new and its tools were rudimentary. Today, in an enterprise of any size, that sort of activity would be noticed and investigated.

There are still offices where anyone can walk around and see what’s on your desk (the dreaded ‘open office’ floor plan), and in those situations, no, you shouldn’t write down your passwords. But are you going to force a password manager onto your grandpa, who is retired, lives alone, and is never going to adopt the elaborate security practices common in an enterprise setting? No, you’re not. Grandpa can and should write down his passwords because if that’s how you get him to use unique, strong passwords, and not “password123” then that’s what you do because.

Grandpa’s threat model is not your threat model is not my threat model. Security principals are universal, but there are a thousand ways to implement those principals.

---

#### Do I HAVE to Use a Password Manager?

From a client:

> I understand the reasons why you recommend the use of password managers. I’m not sure that we’re going to have widespread adoption. As we discussed, my people know how to do their jobs, and things that get in the way of that or that slow things down tend to get ignored. Its an incentive thing of course, so I’m wondering if there is a middle ground we can strike? <Browser> has a builtin password manager. Would it be OK for folks to use it instead of Keepass or any of the other options?

A lot of experts in this field would say “no,” but I’m going to go out on a limb and say that none of them are running a multi-million dollar manufacturing operation that does business domestically and overseas, and supports a workforce that is…not technically sophisticated and incented to produce, not produce securely.

If the use of a browser’s built-in password management capability will drive the use of strong(er) passwords, reduce if not eliminate account/credential sharing, and reduce password reuse, I’m going to give it the thumbs up. No, I don’t know how rigorous an effort has been made to secure that capability, but the alternative is basically all the bad password practices and we know how that story ends.

Success in security is like football: measured in inches. A “better” solution used vice “a markedly better solution” ignored? I’ll take that inch.

---

#### So Much For the Cloud?

> Google on Tuesday said that some passwords for its G Suite customers were stored in an unhashed format since 2005.
>
> “We are writing to inform you that due to legacy functionality that enabled customer Domain Admins to view passwords, some of your users’ passwords were stored in our encrypted systems in an unhashed format,” an email notice to G Suite administrators reads. “This primarily impacted system generated or admin generated passwords intended for one-time use.” ([read more](https://www.securityweek.com/google-warns-g-suite-customers-passwords-stored-unhashed))

Yes, the cloud is “someone else’s computer,” but those someone elses are still a lot better at security than you are (no offense). The is not the problem some have made it out to be, but its also a signal to everyone that you can still be world class at this stuff and make mistakes. **Pushing as much as you can to a reputable cloud provider is still one of the smarter moves you can make to help improve the security posture of your company.**

---

#### Two-Factor Authentication: Still Better With Than Without It

> Google has published the results of a study of the efficacy of standard anti-account-hijacking techniques like two-factor authentication (2FA), secret questions, and passwords: the good news is that when these are used, they are incredibly effective at stopping both automated and targeted attacks, including "advanced" attacks of the sort that are often characterized as unstoppable.

[Read more…](https://boingboing.net/2019/05/20/screw-security-nihilism.html)

**Bottom Line:** MFA/2FA is not perfect, but it is still far and away one of the best defenses you can implement (often at no cost).

---

#### 
