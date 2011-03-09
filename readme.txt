
Description
===============
Multialias provides an interface for automatically generating multiple aliases per content type based off of patterns defined by the user. Multialias creates paths in the same way as Pathauto does.

Multialias is primarily for site builders and developers who want to do conditional business logic on a single node based on path. The goal is to have a single point of administration for a node that resolves at multiple paths.

Example: A content editor has a site that has a content type called "Product."  In the field settings there are two fieldgroups, one fieldgroup that displays only when the path is "/products/[title-raw]" and another set of fields that only displays when the path is "/products/drupal/[title-raw]". This way a content editor has a single point of administration for related content that resolves at muliple paths.

For more information on Multialias see ...drupal.org (replace with sandbox url)

Requirements
===============
Multialias requires the pathauto module. 

Installation
===============


API
===============


Usage
===============
/admin/settings/multialias

Contact/Contributors
===============
John Robert Wilson (LSU_JBob, jr@digitalrhino.com)
Hans Gutknecht (drupal.org - hansyg, hans@digitalrhino.com)