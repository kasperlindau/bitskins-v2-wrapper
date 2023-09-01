# bitskins-v2-wrapper
An unofficial wrapper for the Bitskins API V2 in Python.

.. code:: bash
  pip install bitskins-v2

.. code:: python
  from bitskins.client import Client
  client = Client(api_key)

  # get all available items on sale
  items = client.get_all_items_for_sale_list(app_id=730)

  # get account balance
  balance = client.get_account_balance()

