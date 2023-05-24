---
title: "Duplicate Clustering"
date: 2021-12-13
lastmod: 2023-03-24
draft: false
weight: 58
authors: ["Katie Pearson"]
keywords: ["duplicates","duplicate specimens"]
---

{{< notice info >}}
  This page describes how to view and batch link duplicate specimens (specimens of the same taxon collected on the same day by the same person in the same place) using the Duplicate Clustering tool.
{{</ notice >}}

Occurrences can be linked as duplicates individually during or after data entry using tools in the occurrence editor. See [this page](https://biokic.github.io/symbiota-docs/editor/links/) for more information about linking duplicates on an individual basis and [this page](https://biokic.github.io/symbiota-docs/editor/edit/duplicates/) for information about using the duplicate matching tool during data entry.

Occurrences can also be batch-linked automatically by the Duplicate Clustering tool. This tool creates a temporary index of your occurrences' collection dates, collector numbers, and collector last names, then links any occurrences that share all three of these characteristics.

{{< notice note >}}
  Because creating duplicate specimens is not universal among collection types, tools that facilitate batch duplicate matching are not available in all portals. Contact your portal administrator to activate this function, if necessary.
{{</ notice >}}

To view or link duplicates, navigate to your Administration Control Panel (My Profile > Occurrence Management > name of collection) and click Duplicate Clustering.
* To view existing duplicates, click *Specimen duplicate clusters*
* To view duplicates with taxonomic identifications that do not match, click *Specimen duplicate clusters with conflicted identifications*. An example output of this tool is shown in the screenshot below.
* To batch link duplicates, click *Batch link specimen duplicates*. This will automatically run the batch linking script to create duplicate clusters.

{{< notice note >}}
  When viewing clustered duplicates, you can view the record for any occurrence by clicking the catalog number in blue font.
{{</ notice >}}

![Example Duplicate Conflicts](/symbiota-docs/images/exampleduplicateconflicts.PNG)

A video walkthrough of how duplicate clustering tools can be used to resolve conflicting identifications can be found here:

{{< youtube kMUzwoHmXw4 >}}