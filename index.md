---

layout: col-sidebar
title: OWASP Open Security Information Base
tags: OWASP-Projects OWASP-Top10 standards integration appsec application-security attackers builders defenders
level: 2
type: code, documentation
pitch: The project delivers MkDocs macros that provide a central management of links in MkDocs documents. This includes the versioning of links inside a project, standard or a group of documents and to external sources.

---
# Open Security Information Base (OSIB): Project Homepage
* The project delivers MkDocs macros that provide a central management of links in MkDocs documents. This includes the versioning of links inside a project, standard or a group of documents and to external sources.
* By exporting and sharing the compiled or updated OSIB structure in a YAML file all efforts done by one volunteering group can be used by any other project, standard or document that refers to the same links.
<br>
This reduces or even avoids a lot of unnecessary, redundant work to track and to update links.
The OSIB tree and the macros are capable to handle multilingual versions for links.
<br>

## Easy Linking, Referencing and Versioning
- OWASP Top 10 and most other projects use and generate links to references and to previous versions
- Let’s support each other and avoid redundant work
- Let’s use, generate and share links to other OWASP projects, versions and external references
- Open Security Information Base (OSIB)-Repro: [https://github.com/OWASP/OSIB](https://github.com/OWASP/OSIB)
- <b>Features</b>:
  - Manages links centrally by the project
  - Supports versioning internal and external Links by the project
  - (Manually) installable module that provides MkDocs macros to use with Markdown 
  - Easy to use, provides actually 2 Mkdocs macros (osib_anchor, osib_link)
  - Uses and generates a YAML data structure than can be shared among projects ([osib.yml](https://github.com/OWASP/OSIB/blob/main/osib.yml))
  - Share your YAML-File, to help others
  - The YAML-File can be imported and exported by https://opencre.org/ (perhaps the interface needs to be updated there)
-	The provided version is a first working release that should be reviewed.

This repository is for the Open Security Information Base (OSIB) page on the OWASP website, available at [https://owasp.org/www-project-open-security-information-base](https://owasp.org/www-project-open-security-information-base/).

Please create issues on this [repository](https://github.com/OWASP/www-project-open-security-information-base) only for content hosted under this subfolder on the OWASP site.<br>
For issues or suggestions related to the code and contents of the OSIB macro, use the [https://github.com/OWASP/OSIB](https://github.com/OWASP/OSIB) repository, please.

<!------------------------
This is an example of a Project or Chapter Page.  Please change these items to indicate the actual information you wish to present.  In addition to this information, the 'front-matter' above this text should be modified to reflect your actual information.  An explanation of each of the front-matter items is below:

layout: This is the layout used by project and chapter pages.  You should leave this value as col-sidebar

title: This is the title of your project or chapter page, usually the name.  For example, OWASP Zed Attack Proxy or OWASP Baltimore

tags: This is a space-delimited list of tags you associate with your project or chapter.  If you are using tabs, at least one of these tags should be unique in order to be used in the tabs files (an example tab is included in this repo) 

level: For projects, this is your project level (2 - Incubator, 3 - Lab, 3.5 - Production, 4 - Flagship)

type: code, tool, documentation, or other
------------------------>
