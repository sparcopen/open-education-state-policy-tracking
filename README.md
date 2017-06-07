# Open Education State Legislation Tracking
Since 2014, [SPARC](https://sparcopen.org/) and [Foresight Law + Policy](http://www.flpadvisors.com/) have worked to track U.S. state-level policies relating to open education. This includes legislation and regulations relating to open educational resources (OER), textbook costs, and digital course materials across all levels of education. This repository contains the datasets we created through this process.

A few up-front disclaimers. First, we've made an effort to ensure that the information is accurate, up to date, and representative of all relevant bills, BUT we don't make any guarantees. If you identify any errors or omissions, we encourage you to submit corrections (either through GitHub or by contacting [Nicole Allen](https://github.com/txtbks)). Second, our efforts to track this legislation are independent of any advocacy or policy positions on them, so please don't interpret inclusion in this dataset as an endorsement.

We hope that by posting this data openly, it can not only be useful to the public, but that it can also be improved. If you are interested in contributing to this project, please let us know. 

## Download & Technical Information

The datasets can be downloaded in CSV format from GitHub here: https://github.com/sparcopen

The files use UTF8 encoding, comma as field delimiter, quotation marks as text delimiter, and no byte order mark.

## License and Requests

These datasets are released to the public under a [CC0 Universal 1.0 Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/). 

We do have a few requests if you use the datasets. First, we’d love to know what you are doing with it, so we hope you'll drop us a line at the contact information below. Second, it would also be great if you would include a link back to this repository, so people can get the latest updates. Since the datasets are in the public domain you are not obligated to do any of this, but we'd really appreciate it!

## Data Fields

Below is more information about each of the data fields represented in the database. Note that some fields are only present in the current year (and are removed once all state legislatures have adjourned).

<table cellpadding="6"><tr align="left"><th>Field</th><th>Additional Information</th></tr>
<tr><td>State</td><td>The state where the policy originates from. The scope is limited to the 50 U.S. states.</td></tr>
<tr><td>Type</td><td>Type of policy. In most cases this is legislation, but regulations and directives are also marked when relevant.</td></tr>
<tr><td>Number</td><td>The number corresponding to the policy. For legislation, this is the bill number. For other types of policy, it varies.</td></tr>
<tr><td>Companion</td><td>For bills with a companion bill in the opposite chamber, the number of the companion bill is listed here. Companion bills are entered separately in pairs, and each bill's entry has the other's number listed in the companion field.</td></tr>
<tr><td>URL</td><td>The link to more information about the policy. This is the most difficult field to keep up to date, since links keep breaking. Corrections are encouraged.</td></tr>
<tr><td>Status</td><td>This field was used to keep track of the policy's status over time. In some cases it is a complete history, in others it is only the last known status. We have made an effort to at least ensure the final status is marked, but we would caution that some of the information may be incomplete. Also note that terminology varies between states.</td></tr>
<tr><td>Description</td><td>Brief description of the policy and how it relates to open education. In some cases, this is taken verbatim from the policy. In others, it is original writing. Note that some bills are much broader in scope, and the description only covers the relevant parts.</td></tr>
<tr><td>Author/Sponsor</td><td>The author or sponsor of the policy. For non-legislative policies, the body enacting the policy is typically listed.</td></tr>
<tr><td>Level</td><td>The level of education the policy applies to. This may be K-12, Higher Ed or Both.</td></tr>
<tr><td>Open Mentioned</td><td>When marked "yes", the bill explicitly relates to open education. In most cases, this means that the text of the policy mentions "open educational resources" or an equivalent term. When marked "no", the bill does not explicitly mention OER, but was still tracked because it addresses related themes (with varying levels of relevance).</td></tr>
<tr><td>Enacted</td><td>Whether or not the policy was ultimately enacted, to the best of our knowledge. Answers are "yes" or "no", and blank means unknown.</td></tr></table>

## Data Collection & Cleaning

The data are collected primarily by Foresight Law + Policy. Each week, as staff person runs a keyword search across all 50 states. When new bills are found, they are added to the spreadsheet. Then, the status of each existing bill is checked and updated. States are excluded from the search process once their state legislatures adjourn. There is currently no systematic process for searching for state-level policies beyond legislation (such as regulations or guidance), but they are included when identified.

The 2015 and 2016 data were cleaned by SPARC. First we went line by line to check that each of the links was still active. When links were broken, we found a new one. We gave preference to links to official state websites, and provided third party where information on the state website was not easily located. We also double checked most of the Bill Status fields. We also generated the Companion, Enacted and Open Mentioned fields (which were not originally tracked).

We have made an effort to ensure each of the links is archived in the Internet Archive Wayback Machine. 

## Contact

For inquires about these datasets, please contact [Nicole Allen](https://github.com/txtbks) at nicole@sparcopen.org.
