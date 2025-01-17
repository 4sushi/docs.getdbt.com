---
title: What version of Python can I use?
description: "Python versions 3.7 and newer can be used with dbt Core"
---

<VersionBlock firstVersion="1.1">

The latest version of `dbt-core` is compatible with Python versions 3.7, 3.8, 3.9, and 3.10.

</VersionBlock>

<VersionBlock lastVersion="1.0">

As of v1.0, `dbt-core` is compatible with Python versions 3.7, 3.8, and 3.9.

</VersionBlock>

Adapter plugins and their dependencies are not always compatible with the latest version of Python. For example, dbt-snowflake v0.19 is not compatible with Python 3.9, but dbt-snowflake versions 0.20+ are.

New dbt minor versions will add support for new Python3 minor versions as soon as all dependencies can support it. In turn, dbt minor versions will drop support for old Python3 minor versions right before they reach [end of life](https://endoflife.date/python).

Since v0.15.0, dbt Core no longer supports Python2.
