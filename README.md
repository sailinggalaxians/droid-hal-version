SailfishOS HW Adaptation droid

Version metapackage.

For each adaptation this package should be added as subpackage to the actual
version package e.g. <device>-version and in the rpm/<device>-version.spec one
should have:

%include droid-hal-version/droid-hal-version.inc

With the all device specific defines that are wanted.
