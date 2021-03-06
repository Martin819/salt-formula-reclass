
===============
reclass formula
===============

reclass is an “external node classifier” (ENC) as can be used with automation
tools, such as Puppet, Salt, and Ansible. It is also a stand-alone tool for
merging data sources recursively.


Sample pillars
==============

Reclass storage with data fetched from git

.. literalinclude:: tests/pillar/storage_git.sls
   :language: yaml

Reclass storage with local data source

.. literalinclude:: tests/pillar/storage_local.sls
   :language: yaml

Reclass model with single node definition

.. literalinclude:: tests/pillar/generate_single.sls
   :language: yaml

Reclass model with multiple node defined

.. literalinclude:: tests/pillar/generate_multi.sls
   :language: yaml

Reclass storage with arbitrary class mappings

.. literalinclude:: tests/pillar/class_mapping.sls
   :language: yaml


External links
==============

* http://reclass.pantsfullofunix.net/index.html
* http://reclass.pantsfullofunix.net/operations.html


Documentation and Bugs
======================

To learn how to install and update salt-formulas, consult the documentation
available online at:

    http://salt-formulas.readthedocs.io/

In the unfortunate event that bugs are discovered, they should be reported to
the appropriate issue tracker. Use Github issue tracker for specific salt
formula:

    https://github.com/salt-formulas/salt-formula-reclass/issues

For feature requests, bug reports or blueprints affecting entire ecosystem,
use Launchpad salt-formulas project:

    https://launchpad.net/salt-formulas

You can also join salt-formulas-users team and subscribe to mailing list:

    https://launchpad.net/~salt-formulas-users

Developers wishing to work on the salt-formulas projects should always base
their work on master branch and submit pull request against specific formula.

    https://github.com/salt-formulas/salt-formula-reclass

Any questions or feedback is always welcome so feel free to join our IRC
channel:

    #salt-formulas @ irc.freenode.net
