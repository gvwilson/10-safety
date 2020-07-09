# Ten Simple Rules for Staying Safe Online

-   [Leigh Honeywell](https://hypatia.ca/)
-   [Greg Wilson](http://third-bit.com)

## Introduction

-   Institutions have a lot of rules and guidelines for safeguarding sensitive information
    -   But they're not about *individuals* staying safe
    -   And mostly don't address targeted harassment (e.g., Climategate @Natu2010)
-   Hollywood depictions of everyday threats are as far from reality as their portrayals of scientists
-   A lot of guidance now available for personal digital security (@FLD, @EFJ2015, @EFF)
-   The 10 simple rules in this paper apply to everyone, but are particularly relevant to researchers
-   Can't guarantee complete safety
    -   Realistic goals are risk management (safe driving means fewer accident) and harm reduction (seatbelts mean less injury when accidents happen)
-   Remember, a bike lock can't stop a determined thief, but it *can* make it easier for the thief to steal something else

## Rule 1: Use realistic threat models.

-   Snowden and the journalists who worked with him took extraordinary measures to safeguard themselves against **state-level actors** @Snow2019
    -   But most of us aren't involved in issues of national security
-   A **casual threat**
    -   Monica (professor in psychology) is targeted by Mohan (undergraduate in computer science)
    -   Mohan spends hours every day in online echo chambers complaining about how "SJW bullshit" is ruining tech
    -   Really didn't enjoy Monica's guest lecture on discrimination and inclusivity in his software engineering class
    -   Thinks it would be a laugh to make the target of anonymous abuse online
    -   Attack may be backed up by more knowledgeable advisors in online forums
-   An **intimate threat** who may know passwords and may have installed spyware on devices (Leit2019)
    -   Elena (graduate student) targeted by her romantic partner Eric (also a graduate student but not in the same department)
    -   Their relationship had become increasingly abusive over the last two years
    -   With the help of friends, Elena has moved out of their shared apartment and is rebuilding her life
    -   Eric is obsessed with the idea that she left him for someone else and is now stalking her
-   An **insider threat** who may have legitimate access to accounts and devices
    -   Boris (professor of medicine) targeted by Bethany (university IT staff)
    -   Boris has agreed to serve as an expert witness for a large chemical company in an upcoming liability trial
    -   Bethany has been asked by friends to find out what he is going to say in order to discredit his testimony

## Rule 2: Digital security is rarely the weakest link.

-   At an airport several years ago, heard a professor of computer science try to re-set an online account over the phone
    -   Full name, address, date of birth, and what was almost certainly their mother's maiden name…
    -   …all loudly enough to be heard by two dozen people
-   On that same trip, a stranger (also a computer science professor, but a stranger) asked me to watch their laptop while they went to the washroom
    -   They were logged in to several online accounts at the time
-   Moral of the stories is that safety comes from habits, not technology
    -   Technology should make security the easy default—people should need to know which links to click—but
        a lot of what we use was designed in a more innocent time
    -   Things haven't gotten better in the last 20 years
-   **Social engineering** is far more common than hacking
    -   E.g., trick someone into giving you their password so you don't have to break in digitally

## Rule 3: Put on your own hard hat.

-   Can't rely on companies to protect us
    -   As recently as ten years ago we could blame the lack of legal liability for data breaches on the law being slow to catch up
    -   Today, it's clear that the law hasn't caught up because large tech companies don't want it to
    -   Weekly reports of data breaches have minimal impact on profitability and no individual ever goes to jail
-   Much of what companies force us to go through online is actually counter-productive **security theater**
    -   "Counter-productive" because it encourages us to cut corners in ways that actually make us *less* safe
    -   E.g., forcing people to change passwords every 3 months encourages poor password choice (and writing them down)

## Rule 4: Think before opening.

-   Documents can contain code that automatically executes when the document is opened
    -   Microsoft Office is particularly notorious for this
-   Most websites run code in your browser
-   Attempts to get you to open email attachments, click on a link, install software, or log in are called **phishing** attacks
-   Do not open email attachments without first running them through a virus scanner
    -   Even if you trust the person who sent it, because their computer might just have been compromised
    -   You'll often have to break this rule in the real world because you have to get your job done
-   When opening a web site, check the real domain name in the URL
    -   Even this is tricky: `wwwpaypal.com` is a different domain than `www.paypal.com`
    -   `paypaI.com` (with an upper-case 'I' instead of a lower-case 'l') is different again
-   **Spearphishing** (targeted attacks using data harvested from other victims) are even more tempting
-   Password managers keep track of sites and aren't fooled by similar-seeming letters
-   Verify suspicious emails (e.g., call people)
-   And verify instructions as well (e.g., password reset instructions from IT departments)
    -   Many IT departments send out instructions that are indistinguishable from spearphishing attacks
    -   Which just trains people to be victims

## Rule 5: Use a password manager.

-   Using a weak password is a good way to ensure that your account will eventually be compromised
    -   **Dictionary attacks** can be run offline against downloads of encrypted password files
-   Reusing passwords ensures that bad news spreads
    -   Using a different password for each site helps limit damage if (or when) some are compromised
    -   Your house key isn't also your car key…
-   But strong passwords are hard to remember and to type
    -   Prompts can often be harvested from social media profiles
-   Use a **password manager**
    -   Generates strong passwords
    -   Saves them all under a master pass phrase
    -   But creates a single point of attack
-   Writing passwords down and keeping them in your wallet is useful:
    at least you'll know if your written passwords go missing or get stolen

## Rule 6: Use two-factor authentication.

-   Authentication relies on something you *know*, something you *have*, or something you *are*
-   **Two-factor authentication** requires two of these together
    -   E.g., a password plus a random code generated by a hardware device (or an app on your phone)
    -   Attackers need access to you
-   Random URLs via email do this as well: you *have* access to the email address
    -   But anyone who gains access to your email can then trigger a password reset cycle and steal your account
-   Use app-based 2FA not SMS-based 2FA
    -   The latter has given the rise of attacks where an attacker social engineers their target's phone company into giving them the target's phone number

## Rule 7: Check your devices periodically.

-   App-based vs. SMS-based 2FA is an example of a Red Queen race: both sides are constantly evolving
-   So check devices periodically, just as you would take your car in for an oil change
    -   In fact, one of the authors does these things at the same time in order to remember both…
-   FIXME LH: what to recommend?
-   Do *not* plug a random USB into your device
    -   It's like letting a complete stranger into your home unsupervised
-   Used to recommend using separate devices or accounts for work and personal, but this is unrealistic
    -   Everyone checks their personal email from their work device eventually
-   And consider getting a second phone for international travel
    -   FIXME LH: is this realistic for this audience?

## Rule 8: Tighten your social media privacy settings.

-   Seemingly-innocuous information can give attackers valuable clues
    -   Restaurant "likes" reveal date and location
    -   Funny stories about childhood birthday parties reveal likely answers to security questions
-   Facebook, Twitter, and others make money selling targeted advertising to you and data about you
    -   Laws guaranteeing free speech don't actually require them to give a platform to hate speech
-   They have been forced to give users at least a little control over personal data,
    but frequently change their terms of service in opaque ways
-   "Authorized apps" are often the worst offenders
    -   And that's not even counting the ones that turn out to be government-sponsored spyware @Schn2019
-   Go through settings periodically and turn off almost everything
    -   As tedious and as necessary as cleaning leaves out of your gutters

## Rule 9: Erase before discarding.

-   Moving files into the trash and then emptying it does *not* actually erase the data
    -   Just tells the computer that the space is available for re-use
    -   Which is why reporters and private investigators go dumpster diving regularly
-   Best answer is to encrypt the drive in the first place
    -   But this leads to security fatigue @Stan2016
-   Act as if any account you shut down or any device you throw away is going to fall into unfriendly hands
-   So destroy devices if you can
    -   Many cities have electronics recycling programs
    -   Though that's someone else you now need to trust
-   And erase data if you can't destroy devices
    -   Practically impossible to truly delete data from social networking sites
    -   "Delete" usually means "don't show any more" rather than "erase all record of"
-   Use a secure deletion tool (e.g., BleachBit on Linux or Windows)
-   But none of this affects backups or files stored online (e.g., Dropbox)

## Rule 10: It's not all about you.

-   Keep others safe by putting passwords on PDFs you're sending that contains sensitive information
    -   Sending tax receipts as attachments that anyone could open is just inviting trouble
-   If you are compromised, let those affected know

## Conclusion

-   We haven't included VPNs or Tor
    -   A **Virtual Private Network (VPN)** connects your device to a server,
        then has the server make connections to other machines on your behalf
    -   All messages between your device and the server are encrypted
    -   And the server can be managed by professional IT staff, in a jurisdiction with tight privacy laws, etc.
-   Tor routes messages randomly through a network of servers, making traffic much harder to track
-   Both reduce risk but neither eliminates it
    -   If your device has been compromised
    -   If the VPN is compromised (or subpoenaed)
    -   If you log in to accounts over Tor (revealing your identity to those sites, which may then be compromised)

-   You *can* be safer
-   And if you want to be even safer, ask politicians about strengthening liability legislation
    -   Driving is safe in part because drivers and car manufacturers are legally liable
-   Thank to Claire Bowen (Urban Institute), Mike Hoye (Mozilla), Scott Jackson (RStudio), and Sydney Young (EFF) for their feedback

## Glossary

-   casual threat
-   dictionary attack
-   insider threat
-   intimate threat
-   password manager
-   phishing
-   security theater
-   social engineering
-   spearphishing
-   state-level actor
-   threat model
-   two-factor authentication (2FA)
-   Virtual Private Network (VPN)

## Bibliography

Amro2018:
:   Belal M. Amro, Mohanad O. Al-Jabari, Hussein M. Jabareen, Yousef S. Khader, and Adel Taweel:
    "[Design and Development of Case Studies in Security and Privacy for Health Informatics Education](https://doi.org/10.1109/aiccsa.2018.8612876)".
    In *2018 Conference on Computer Systems and Applications*, Oct 2018, doi:10.1109/aiccsa.2018.8612876.

Blue2015:
:   Violet Blue:
    *The Smart Girl's Guide to Privacy: Practical Tips for Staying Safe Online*.
    No Starch Press, 2015, 978-1593276485.

Cove2018:
:   Lynne Coventry and Dawn Branley:
    "[Cybersecurity in healthcare: A narrative review of trends,  threats and ways forward](https://doi.org/10.1016/j.maturitas.2018.04.008)".
    *Maturitas*, 113, Jul 2018, doi:10.1016/j.maturitas.2018.04.008.

EFF:
:   Electronic Frontier Foundation:
    "Surveillance Self-Defense: Tips, Tools and How-Tos for Safer Online Communications".
    <https://ssd.eff.org/>, Viewed 2020-01-25.

Filk2016:
:   Barbara Filkins, Ju Young Kim, Bruce L. Roberts, Winston Armstrong, Mark A. Miller, Michael L Hultner, Anthony P Castillo, Jean-Christophe Ducom, Eric J. Topol, and Steven R. Steinhubl:
    "Privacy and security in the era of digital health: what should translational researchers know and do about it?".
    *American Journal of Translational Research*, 8(3), 2016.

FLD:
:   Front Line Defenders:
    "Digital Security Resources".
    <https://www.frontlinedefenders.org/en/digital-security-resources>, Viewed 2020-01-25.

Leit2019:
:   Roxanne Leitão:
    "[Technology-Facilitated Intimate Partner Abuse: a qualitative analysis of data from online domestic abuse forums](https://doi.org/10.1080/07370024.2019.1685883)".
    *Human–Computer Interaction*, 12 2019, doi:10.1080/07370024.2019.1685883.

Natu2010:
:   Editorial:
    "[Closing the Climategate](https://doi.org/10.1038/468345a)".
    *Nature*, 468(7322), 11 2010, doi:10.1038/468345a.

Schn2019:
:   Bruce Schneier:
    "ToTok Is an Emirati Spying Tool".
    <https://www.schneier.com/blog/archives/2019/12/totok_is_an_emi.html>, Viewed 2020-01-25.

Snow2019:
:   Edward Snowden:
    *Permanent Record*.
    Metropolitan Books, 2019, 978-1250237231.

Stan2016:
:   Brian Stanton, Mary F. Theofanos, Sandra Spickard Prettyman, and Susanne Furman:
    "[Security Fatigue](https://doi.org/10.1109/mitp.2016.84)".
    *IT Professional*, 18(5), Sep 2016, doi:10.1109/mitp.2016.84.
