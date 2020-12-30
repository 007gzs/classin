ClassIn相关接口
===========================================

.. module:: classin.client

.. autoclass:: ClassInClient
   :members:
   :inherited-members:


`ClassInClient` 基本使用方法::

    from classin import ClassInClient

    client = ClassInClient('<SID>', '<SECRET>')

    folders = client.cloud.get_folder_list()


.. toctree::
   :maxdepth: 2
   :glob:

   api/*

