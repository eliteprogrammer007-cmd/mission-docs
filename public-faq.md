# Public FAQ

## Can visitors access Mission Control?

No. The public site only links to the crew portal. Mission Control requires an
administrator session.

## Are cookies accessible to report scripts?

No. Session cookies are configured with `HttpOnly`, so browser JavaScript cannot
read them through `document.cookie`.
