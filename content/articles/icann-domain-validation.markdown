---
title: ICANN domain validation requirements
excerpt: This support article explains what ICANN domain validation is and how to ensure that your domain name is not suspended by ICANN due to non-validation.
categories:
  - Domains
---

# ICANN domain validation

ICANN, the organization that oversees domain name registrations for most top-level domains, requires validation of your registrant email address whenever a new domain is registered, or your registrant email address or name is changed. Failure to validate your registrant email address results in suspension of the domain name after 15 days of non-compliance.

When you make a change to your registrant's email address or name, you will receive an email similar to the following:

![ICANN Verification Email](/files/icann-verification-email.png)

This email will be sent from the addresses `DNSimple <donotreply@name-services.com>` or `DNSimple <registrant-verification@ispapi.net>` and will include a link similar to the following:
- `http://raa.name-services.com/raaverification/verification.aspx?VerificationCode=A8E3763E-EE70-42DB-A654-20BF560300A00`
- `http://www.enom.com/raaverification/verification.aspx?VerificationCode=AAAAAAAA-1A11-11AA-1A1A-1111111111`
- `http://registrant-email-verification-ispapi.net/?approve&token=Fsjdklajdfoqewvoieioejrawkjnjasfie&lang=en`

Click the link to verify the registrant email address.

The link must be to `http://raa.name-services.com`, `http://www.enom.com`, or `http://registrant-email-verification-ispapi.net` - if you receive a verification email and this link is not in the email then please contact support@dnsimple.com, forwarding the email you received.

## Resend verification email

If you are having trouble finding the email verification in your inbox, you may want to resend it. Navigate to your domain page and locate the ICANN pending verification warning at the top of the page. Then click on "Send ICANN RAA verification email"

![ICANN resend email verification](/files/raa-resend-email-verification.png)

Once you have acted on the verification email, the warning above should not appear. If it does, it may be because our system hasn't refreshed the latest status yet. You can manually force a refresh by clicking on the "Refresh" button.

## What happens when a domain is suspended?

If your domain is suspended, the name servers will be changed to the following:

- DNS1.NAME-SERVICES.COM
- DNS2.NAME-SERVICES.COM
- DNS3.NAME-SERVICES.COM
- DNS4.NAME-SERVICES.COM
- DNS5.NAME-SERVICES.COM

Additionally, a message will appear indicating that your domain is suspended:

![ICANN Verification Web](/files/icann-verification-web.png)

On this verification page is an option to resend the verification email. Requesting a resend will schedule a new verification email that is sent to the registrant email address.

<note>
If your domain was suspended, it may take between 24 to 48 hours for the suspension to be removed once you have verified the registrant email address.
</note>

## What happens if the registrant email address cannot receive email?

You must be able to receive an email at the registrant email address to complete the verification process. You may set up the email address with an email provider or you may use our email forwarding service. If you set up the email address after registration or changing your registrant details then you may need to resend the verification email. Please contact support@dnsimple.com to do so. Include the domain name that you need to verify in your email to support.

Want to more about the policy requiring domain validation? Visit the ICANN web site to read about the [ICANN Whois Accuracy](https://www.icann.org/resources/pages/approved-with-specs-2013-09-17-en#whois-accuracy) program.
