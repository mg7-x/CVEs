## CVE Disclosures 🛡️

Welcome to the CVE disclosures section of this repository! Here, you'll find a list of potential security vulnerabilities that I have discovered.

Below is a list of all the CVEs that I have discovered. Each entry links to a dedicated file inside the `cves/`.

| Finding | Description |
|---|---|
| *[CVE-2025-61417](/CVE-2025-61417/README.md)* | A stored cross-site scripting (XSS) vulnerability exists in TastyIgniter 3.7.7, affecting the /admin/media_manager component. Attackers who can upload files may craft a malicious SVG file containing JavaScript. When an administrator previews the SVG in the admin interface, the embedded script executes within the admin's browser context. This allows the attacker to modify the admin account credentials, enabling full account takeover. |



>  I will update this list as soon as any new vulnerabilities are found.



