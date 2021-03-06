.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


Each individual ``rule`` must be associated with a specific message type. As a rule is triggered during the |chef client| run, a message is sent to the |chef analytics| server. A rule may be configured to send notifications about a message to recipients that are located outside of the |chef analytics| server.

A message type must be one of the following:

.. list-table::
   :widths: 60 420
   :header-rows: 1

   * - Message Type
     - Description
   * - ``action``
     - Use to build rules for messages about actions that occur on the |chef server|.
   * - ``run_control``
     - Use to build rules for a single audit to be evaluated.
   * - ``run_control_group``
     - Use to build rules for a group of audits to be evaluated.
   * - ``run_converge``
     - Use to build rules for messages that are sent at the end of a |chef client| run.
   * - ``run_resource``
     - Use to build rules for messages that are sent as each resource is converged during a |chef client| run.
   * - ``run_start``
     - Use to build rules for messages that are sent at the start of a |chef client| run.
