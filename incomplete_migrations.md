# Incomplete migrations are technical debt

When moving from one version of a library or service to another,
or when switching libraries entirely, clean up the old version/dependency
before declaring victory. Accreting multiple versions in your codebase
generates complexity and bugs -- aka technical debt.

If the old APIs, RPC endpoints, etc remain, users will continue to use them,
even if it's not the right thing to do.

See also
[Hyrum’s Law](hyrums_law.md) and
[Turndowns, not just deprecations](turndowns_not_deprecations.md)
