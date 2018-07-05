DutchX's documentation
==================================
The **Dutch Exchange (DutchX)** is a fully decentralized exchange, which
allows **everyone** to add any trading token pair.

It uses the `Dutch auction`_ principle, to prevent the problems that
other exchanges are experiencing (such as front running) getting a
fairer ecosystem for everyone to use.

There is no restriction besides the fact that tokens must be `ERC20`_
compliant.

Learn more about DutchX
-----------------------
One place you can learn all about the mechanisms of the DutchX is in:

* https://blog.gnosis.pm/tagged/dutchx

.. toctree::
   :hidden:

   Introduction <self>

.. toctree::
   :maxdepth: 2
   :caption: Guides:

   First steps <development-first-steps>
   Add a token pair <add-token-pair>
   Run your own bots <run-your-own-bots>


.. toctree::
   :maxdepth: 2
   :caption: Reference:

   reference_api
   reference_smart-contracts

You may be also interested on
-----------------------------
Related github projects:

* **Smart contracts**: https://github.com/gnosis/dx-contracts
* **Seller interface for DutchX**: https://github.com/gnosis/dx-react
* **Example on using the bots**: https://github.com/gnosis/dx-examples-liquidity-bots
* **Example on using the read API**: https://github.com/gnosis/dx-examples-api
* **Example on using the CLI**: https://github.com/gnosis/dx-example-cli-rinkeby

Contact the DutchX comunity
===========================
Find the comunity in: https://gitter.im/gnosis/DutchX

.. _Dutch auction: https://en.wikipedia.org/wiki/Dutch_auction
.. _ERC20: https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md
.. _First steps for development on top of DutchX: ./guides/development-first-steps.md
.. _How to add a trading token pair: ./guides/add-token-pair.md
.. _Run your own bots: ./guides/add-token-pair.md