%%%
title = "SACM Commands for XMPP-Grid"
abbrev = "sacm-gridCmds"
obsoletes =
ipr = "trust200902"
area = "Security"
workgroup = "Security Automation and Continuous Monitoring"
submissiontype = "IETF"
keyword = [""]
date = 2019-11-05T00:00:00Z
docName = "draft-inacio-sacm-gridCmds-00"

[seriesinfo]
name = "RFC"
value = "TBD"
stream = "IETF"
status = "informational"

[[author]]
initials = "C."
surname = "Inacio"
fullname = "Christopher Inacio"
abbrev = "CMU"
organization = "Carnegie Mellon University"
  [author.address]
  email = "inacio@cert.org"
  [author.address.postal]
  city = "Pittsburgh"
  street = "4500 5th Ave"
  code = "PA 15213"
  country = "United States"
[[author]]
initials = "B."
surname = "Munyan"
fullname = "Bill Munyan"
abbrev = "CIS"
organization = "Center for Internet Security"
  [author.address]
  email = "bill.munyan.ietf@gmail.com"
  [author.address.postal]
  city = "Albany"
  #street = ""
  #code  = "NY 99999"
  country = "United States"
%%%

.# Abstract

This document describes the set of commands and data that are the extensions to the XMPP protocol that enable security content messages to be
processed within the XMPP-Grid protocol. These commands enable the discovery, configuration, and exchange of data for security content and the
automation of that security content.

{mainmatter}

# Introduction

This document is designed as a working document to define the set of commands that will allow the creation of interoperable XMPP-Grid implementations supporting the exchange of security content information.  This document will also document the discovery, configuration, and repository access abilities needed to support the security content.

Not all of the commands and methods here are necessarily XMPP extensions.  That will be fixed / cleaned up at a later time.  This document is intended to allow an implementer sufficient specification to create an interoperable XMPP-Grid implementation that can exchange defined security content without additional protocol information.  This document is not intended to provide the background and design decisions for this work - other SACM working group documents are provided for that purpose.

## Terminology

The key words "**MUST**", "**MUST NOT**", "**REQUIRED**", "**SHALL**", "**SHALL NOT**", "**SHOULD**",
"**SHOULD NOT**", "**RECOMMENDED**", "**NOT RECOMMENDED**", "**MAY**", and "**OPTIONAL**" in this
document are to be interpreted as described in BCP 14 [@!RFC2119] [@!RFC8174] when, and only when,
they appear in all capitals, as shown here.

# SACM/XMPP Capability Negotiation Extensions

# SACM/XMPP Coordination/Action Commands

# SACM/XMPP Repository Access Extensions

#IANA Considerations

None?  Registry for the commands?  XMPP XEP's?

# Security Considerations

To be completed.

# Updates

{backmatter}

# Acknowledgements


