.. module:: doapi

Floating IPs
------------

FloatingIP
^^^^^^^^^^

.. autoclass:: FloatingIP()
   :special-members: __str__, __int__

   .. autoattribute:: action_url
   .. automethod:: act
   .. automethod:: wait_for_action
   .. automethod:: fetch_all_actions
   .. automethod:: fetch_last_action
   .. automethod:: fetch_current_action
