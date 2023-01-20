# Improving Reliability Doesn't Always

Also known as [Lorin's Law](https://surfingcomplexity.blog/2017/06/24/a-conjecture-on-why-reliable-systems-fail/).

Many major incidents are triggered by:
* An attempt to resolve minor incidents through manual intervention
* Unexpected behavior of a subsystem designed to improve reliability

[Fault injection](https://en.wikipedia.org/wiki/Fault_injection) testing and [chaos engineering](https://principlesofchaos.org/) help to identify areas that need automation and unexpected behavior of said automation on a predictable (convenient) and regular basis, and discourage poor practices. 

See also: [Global systems fail globally](global_systems_fail_globally.md)
