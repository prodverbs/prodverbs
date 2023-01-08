# Security at the expense of usability comes at the expense of security

Referred to as [_AviD's Rule of Usability_](https://security.stackexchange.com/questions/6095/xkcd-936-short-complex-password-or-long-dictionary-passphrase/6116#6116).

Hackers may want to infiltrate your systems, but users just want to do their jobs.

Your users' job is not "security". It's something else, and security controls
need to be careful to not stand in the way. Systems should make the right
behavior the easy thing as well.

The harder a system makes it for users to do their jobs, the more users will look
for ways to make it easier for themeselves, likely nullifying security controls
along the way.

For example, if you system provides a way to "break glass" -- to bypass controls in
exceptional situations -- monitor to see if your users are using it
like a "make it go" button. If they are, then your security controls
are too onerous and/or not well thought-out, and your users are
bypassing them in order to get work done.

See also https://xkcd.com/936/ and [RedMonk: Developer Experience is Security](https://redmonk.com/rstephens/2022/02/17/devex-is-security/)
