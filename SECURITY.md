# Security

## Vulnerability
Update bundler to a version higher, at least 2.2.33 :-: [vulnerability: CVE-2020-36327]

 - **Vuln Info [ENG]**
   
   - CVE: CVE-2020-36327

   - Package: bundler (RubyGems)

   - Affected versions: >= 1.16.0, < 2.2.10

   - Patched version: 2.2.10

   - Description: Bundler 1.16.0 through 2.2.9 and 2.2.11 through 2.2.17 sometimes chooses a dependency source based on the highest gem version number, which means that a rogue gem found at a public source may be chosen, even if the intended choice was a private gem that is a dependency of another private gem that is explicitly depended on by the application.

## Reporting a Vulnerability

Report vulnerabilities using the tab "issues".
