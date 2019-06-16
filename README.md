# Rock Central

Cydia allows users to add sources, where developers host their own packages. As a result, Cydia takes a long time to load and refreshing sources can take forever. The number of community apps on Cydia has increased exponentially since its release. As a result of this, the default APT implementation has become cumbersome, and loading times will only continue to get worse.

Instead of processing each source's list of available packages directly on the phone, Rock uses one central repository called Rock Central. Developers can still easily upload their packages on Rock Central, which then downloads the list of packages to its servers and simply sends Rock the small list of changes. This means that Rock loads way faster than Cydia and users will no longer have to sit around waiting for their sources to refresh. Every week, Rock will be updated and will include packages submitted by developers to Rock Central from that week.
