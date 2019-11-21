# Ten Simple Rules for Staying Safe Online

-   [Greg Wilson](http://third-bit.com)

## Introduction

FIXME

-   Draw on healthcare for some guidance because of its experience with sensitive data
    -   But that's not about *individuals* staying safe
    -   And doesn't address harassment

## Rule 1: Use realistic threat models.

-   You can't protect yourself from serious professionals, but most of us aren't their targets
-   Hollywood depictions of real threats are as far from reality as their portrayals of scientists
-   **Monica** (professor in psychology) vs. **Mohan** (undergraduate in computer science)
    -   Mohan spends hours every day in online echo chambers complaining about how "SJW bullshit" is ruining tech
    -   *Really* didn't enjoy Monica's guest lecture on discrimination and inclusivity in his software engineering class
    -   Thinks it would be a laugh to make the target of anonymous abuse online
    -   A *casual threat* potentially backed up by knowledgeable advisors
-   **Elena** vs. **Eric** (graduate students at the same university but not in the same department)
    -   Their relationship had become increasingly abusive over the last two years
    -   With the help of friends, Elena has moved out of their shared apartment and is rebuilding her life
    -   Eric is obsessed with the idea that she left him for someone else and is now stalking her
    -   An *intimate threat* who may know passwords and may have installed spyware on devices
-   **Boris** (professor of medicine) vs. **Bethany** (university IT staff)
    -   Boris has agreed to serve as an expert witness for a large chemical company in an upcoming liability trial
    -   Bethany has been asked by friends to find out what he is going to say in order to discredit his testimony
    -   An *insider threat*: Bethany may have legitimate access to some of Boris's accounts and devices

## Rule 2: Digital security is rarely the weakest link.

-   Safety comes from habits, not technology
-   At an airport several years ago listening to a professor of computer science try to re-set an online account over the phone
    -   Full name, address, date of birth, and what was almost certainly their mother's maiden name…
    -   …all loudly enough to be heard by two dozen people
-   On that same trip, a stranger (also a computer science professor) asked me to watch their laptop while they went to the washroom
    -   They were logged in to several online accounts at the time

## Rule 3: You have to put on the condom yourself.

-   Can't rely on companies to protect us
    -   As recently as ten years ago we could blame the lack of legal liability for data breaches on the law being slow to catch up
    -   Today, it's clear that the law hasn't caught up because large tech companies don't want it to
    -   Weekly reports of data breaches have minimal impact on profitability and no individual ever goes to jail
-   Much of what companies force us to go through online is actually counter-productive security theater
    -   "Counter-productive" because it encourages us to cut corners in ways that actually make us *less* safe

## Rule 4: Don't open that.

-   Documents can contain code that automatically executes when the document is opened
-   Websites can run code in your browser
-   Attempts to get you to open email attachments, click on a link, install software, or log in are called *phishing* attacks
-   Do not open email attachments
    -   Even if you trust the person who sent it, because their computer might just have been compromised
-   When opening a web site, check the real domain name in the URL
    -   Even this is tricky: `wwwpaypal.com` is a different domain than `www.paypal.com`
    -   `paypaI.com` (with an upper-case 'I' instead of a lower-case 'l') is different again
-   *Spearphishing* (targeted attacks using data harvested from other victims) are even more tempting
-   Password managers keep track of sites and aren't fooled by similar-seeming letters
-   Verify emails (e.g., call people)
-   And verify instructions as well (e.g., password reset instructions from IT departments)
    -   Many IT departments send out instructions that are indistinguishable from spearphishing attacks
    -   Which just trains people to be victims

## Rule 5: Use a password manager.

-   Using a weak password is a good way to ensure that you're eventually going to have a bad day
    -   Offline dictionary attacks
-   Reusing passwords ensures that bad news spreads
-   But strong passwords are hard to remember and to type
    -   Prompts can often be harvested from social media profiles
-   Use a password manager
    -   Generates strong passwords
    -   Saves them all under a master pass phrase
    -   Creates a single point of attack
-   Writing passwords down and keeping them in your wallet is useful:
    at least you'll know if your written passwords go missing or get stolen

## Rule 6: Use two-factor authentication.

-   Authentication relies on something you *know*, something you *have*, or something you *are*
-   2FA relies on the first two
    -   Password plus a random code generated by a hardware device (or an app on your phone)
    -   Attackers need access to you
-   Random URLs via email do this as well: you *have* access to the email address
    -   But anyone who gains access to your email can then trigger a password reset cycle and steal your account

## Rule 7: Check your devices periodically.

-   Because everyone makes mistakes
-   FIXME: what to recommend
-   Do *not* plug a USB into your device
    -   See the note above about condoms

## Rule 8: Tighten your social media privacy settings.

-   Facebook, Twitter, and others make money selling targeted advertising to you and data about you
    -   Laws guaranteeing free speech don't actually require them to give a platform to hate speech
-   They have been forced to give users at least a little control over personal data,
    but frequently change their terms of service in opaque ways
-   Go through settings periodically and turn off almost everything
    -   As tedious and as necessary as cleaning leaves out of your gutters
-   Have a travel phone for crossing the border.

## Rule 9: Use Tor.

-   FIXME: explain how Tor works.
-   Describe similar applications.

## Rule 10: Erase, then discard.

-   Reporters and private investigators go dumpster diving regularly
-   Assume that any account you shut down or any device you throw away is going to fall into unfriendly hands
-   So erase data
    -   Practically impossible with social networking sites (though it should be required by law)
-   Moving files into the trash and then emptying it does *not* actually erase the data
    -   Just tells the computer that the space is available for re-use
-   Use a secure deletion tool (e.g., BleachBit on Linux or Windows)
-   But actually very hard on solid-state drives (SSDs)
    -   And none of this affects backups, files stored online (e.g., Dropbox)
-   Best answer is to encrypt the drive in the first place
    -   But this leads to security fatigue (Stan2016)

## Conclusion

-   FIXME: Ask candidates about strengthening liability legislation

## Bibliography

-   Violet Blue:
    *The Smart Girl's Guide to Privacy: Practical Tips for Staying Safe Online*
    No Starch Press, 2015, 978-1593276485.

-   Lynne Coventry and Dawn Branley:
    "[Cybersecurity in healthcare: A narrative review of trends, threats and ways forward](https://doi.org/10.1016/j.maturitas.2018.04.008)"
    *Maturitas*, 113, Jul 2018, doi:10.1016/j.maturitas.2018.04.008.

-   Electronic Frontier Foundation:
    "[Surveillance Self-Defense](https://ssd.eff.org/): Tips, Tools and How-tos for Safer Online Communications"
    https://ssd.eff.org, accessed November 2019.

-   Barbara Filkins, Ju Young Kim, Bruce L. Roberts, Winston Armstrong, Mark A. Miller, Michael L Hultner, Anthony P Castillo, Jean-Christophe Ducom, Eric J. Topol, and Steven R. Steinhubl:
    "Privacy and security in the era of digital health: what should translational researchers know and do about it?"
    *American journal of translational research*, 8(3), 2016.

-   Bruce Schneier:
    *Data and Goliath: The Hidden Battles to Collect Your Data and Control Your World*
    W. W. Norton & Company, 2016, 978-0393352177.

-   Bruce Schneier:
    *Click Here to Kill Everybody: Security and Survival in a Hyper-connected World*
    W. W. Norton & Company, 2018, 978-0393608885.

-   Brian Stanton, Mary F. Theofanos, Sandra Spickard Prettyman, and Susanne Furman:
    "[Security Fatigue](https://doi.org/10.1109/mitp.2016.84)"
    *IT Professional*, 18(5), Sep 2016, doi:10.1109/mitp.2016.84.
