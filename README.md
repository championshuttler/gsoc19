# GSoC 2019

Writing docs for Firefox's in-tree source docs is time consuming and difficult and the end result is difficult to navigate.

With MDN de-prioritizing build and workflow docs, we need a suitable replacement for all of Firefox's contribution and workflow documentation. The great advantage of documentation living in-tree, is that it can be updated along with the source. Unfortunately the current system to build and generate docs is difficult to write for, slow to build and generates poorly organized documentation. These factors discourage developers from creating or updating docs.

This project aims to improve the documentation experience via static analysis tools (e.g hint when docs might need to be updated), enabling linters, faster build times, additional language support and well structured hierarchies. Help make documentation a bigger part of our developer's day to day workflow. 

# Firefox Source Docs Infrastructure

This project aims to improve the infrastructure underpinning Firefox's in-tree documentation via enabling linters, faster build times, setting up redirect and well structured hierarchies.

# Issues
 * [Bug 1535452 - Make writing and reading our in-tree documentation a first class experience](https://bugzilla.mozilla.org/show_bug.cgi?id=1535452) (Meta Issue)
 * [Bug 1527361 - Stand up restructuredtext-lint to catch problems in our documentation early](https://bugzilla.mozilla.org/show_bug.cgi?id=1535452)
 * [Bug 1566097 - Register Sphinx specific directives in the RST linter](https://bugzilla.mozilla.org/show_bug.cgi?id=1566097)
 * [Bug 1486796 - Add mermaid package to Firefox source docs](https://bugzilla.mozilla.org/show_bug.cgi?id=1486796)
 * [Bug 1564799 - Use sphinx.util.logging instead of app.info()](https://bugzilla.mozilla.org/show_bug.cgi?id=1564799)
 * [Bug 1527363 - Add ability to specify redirects](https://bugzilla.mozilla.org/show_bug.cgi?id=1527363)
 * [Bug 1526796 - Removed Sphinx documentation output files is not removed from web server](https://bugzilla.mozilla.org/show_bug.cgi?id=1526796)
 * [Bug 1460678 - Improve |mach doc| performance](https://bugzilla.mozilla.org/show_bug.cgi?id=1460678)
 * [Bug 1574948 - Redirects don't preserve the firefox-source-docs host name](https://bugzilla.mozilla.org/show_bug.cgi?id=1574948)
 * [Bug 1569472 - Enable RST Linter on more directories](https://bugzilla.mozilla.org/show_bug.cgi?id=1569472)
 * [Bug 1574609 - Fix telemetry/telemetry path component in firefox-source-docs](https://bugzilla.mozilla.org/show_bug.cgi?id=1574609)
 * [Bug 1571671 - Enable RST linting on fluent docs in intl/l10n/docs](https://bugzilla.mozilla.org/show_bug.cgi?id=1571671)


# Pull Requests
 * [Use sphinx.util.logging instead of app.info()](https://phabricator.services.mozilla.com/D37539) [Merged]
 * [Setup rst linter for the documentation](https://phabricator.services.mozilla.com/D36586) [Merged]
 * [Setup rstcheck linter instead of restructuredtext-lint](https://phabricator.services.mozilla.com/D38339) [Merged]
 * [Add ability to specify redirects](https://phabricator.services.mozilla.com/D41548) [Merged]
 * [Fix Sphinx Warning - Unexpected indentation (1)](https://phabricator.services.mozilla.com/D35304) [Merged]
 * [Fix Sphinx Warning - Title Underline too short in 'mach doc' (2)](https://phabricator.services.mozilla.com/D35309) [Merged]
 * [Fix various Sphinx Warning in 'mach doc' (3)](https://phabricator.services.mozilla.com/D35314) [Merged]
 * [Fix various Sphinx Warning in 'mach doc' (4)](https://phabricator.services.mozilla.com/D38046) [Merged]
 * [Fix taskcluster docs linting errors](https://phabricator.services.mozilla.com/D39627) [Merged]
 * [Level Down the Error level to 2 in linter](https://phabricator.services.mozilla.com/D39663) [Merged]
 * [Add mermaid package to Firefox source docs](https://phabricator.services.mozilla.com/D39742) [Merged]
 * [Fix Sphinx Warning for not referenced hyperlinks](https://phabricator.services.mozilla.com/D39057) [Merged]
 * [Removed Sphinx documentation output files is not removed from web server](https://phabricator.services.mozilla.com/D35598) [Merged]
 * [Improve mach doc performance, use sphinx's -J argument](https://phabricator.services.mozilla.com/D41058) [Merged]
 * [Enable RST linter for browser/docs/ and tools/tryselect/docs/](https://phabricator.services.mozilla.com/D41991) [Merged]
 * [Preserve the firefox-source-docs host name](https://phabricator.services.mozilla.com/D42548) [Merged]
 * [Call delete after upload to avoid Contents key error](https://phabricator.services.mozilla.com/D42700) [Merged]
 * [Build regular and python API docs in parallel](https://phabricator.services.mozilla.com/D41062)
 
