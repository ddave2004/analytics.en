---
title: Single page visits
description: A flag indicating that the visit consisted of a single page.
---

# Single page visits

*This help page describes how 'Single page visits' works as a dimension. See the [Single page visits](../metrics/single-page-visits.md) metric for more information.*

The 'Single page visits' dimension reports the number of visits that consisted of a single unique [Page](page.md) dimension value. It is the dimension form of the [Single page visits](../metrics/single-page-visits.md) metric.

This dimension is most commonly used as a component within [segmentation](../c-segmentation/seg-home.md). It is not typically used as a dimension in reports.

## Populate this dimension with data

This dimension works out of the box for all implementations. If a report suite contains data, this dimension works.

## Dimension values

The only dimension value is `"Enabled"`. If a visit consists of a single page, the hit is set to this value. All other hits are omitted from this report.
