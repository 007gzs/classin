
ClassIn SDK 使用文档
========================================

ClassIn SDK 是 ClassIn Python SDK。

快速入门
-------------

.. toctree::
   :maxdepth: 2

   install


开始使用
--------------------
建议在使用前先阅读 `ClassIn API文档 <https://docs.eeo.cn/api/zh-hans/>`_

.. toctree::
   :glob:
   :maxdepth: 2

   client/index

调用示例::

    from classin import ClassInClient

    client = ClassInClient('<SID>', '<SECRET>')

    folders = client.cloud.get_folder_list()


Changelogs
---------------

.. toctree::
   :maxdepth: 1

   changelog

