# ATS 590 System Configuration Package

A system configuration package for Mjolnir, for use with Dr. Nair's ATS 590 course on testing new low-cost environmental sensor networks.

**IMPORTANT:** When cloning for the first time, make sure to use the ``--recurse-submodules`` to automatically initialize and download the ``mjolnir-presets`` git submodule that stores the common configuration presets.
If you're already cloned the repo, you can run ``git submodule update --init`` to do the same.
Otherwise, the common presets won't be downloaded automatically under Git's default settings.
You only need to do this once; if you want to update your default presets, simply use ``git submodule update`` and commit the result.
