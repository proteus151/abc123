====================
FAUCET Configuration
====================

Faucet is configured with a YAML-based configuration file, typically ``faucet.yaml`` Following is example.

.. code:: yaml

  dps:
      switch-1:
          dp_id: 0x1
          interfaces:
              1:
                  native_vlan: 2040
                  acl_in: 1
              2:
                  native_vlan: 2040

and more stuff here
