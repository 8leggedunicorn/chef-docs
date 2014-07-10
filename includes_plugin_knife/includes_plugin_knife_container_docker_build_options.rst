.. The contents of this file are included in multiple topics.
.. This file describes a command or a sub-command for Knife.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


This argument has the following options:

``-d DOCKERFILES_PATH``, ``--force DOCKERFILES_PATH``
  Use to specify the path to the folder in which |dockerfile| contexts are located.

``--force``
  Use to force a build. Default value: ``false``.

``--no-berks``
  Use to prevent |berkshelf| from running, even when a |berksfile| exists.

``--no-cleanup``
  Use to disable the cleanup of Chef artifacts including Chef Node and Chef Client.
