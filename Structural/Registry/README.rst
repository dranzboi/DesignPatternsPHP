`Registry`_
===========

Purpose
-------

To implement a central storage for objects often used throughout the
application, is typically implemented using an abstract class with only
static methods (or using the Singleton pattern)

Examples
--------

-  Zend Framework: ``Zend_Registry`` holds the application's logger
   object, front controller etc.
-  Yii Framework: ``CWebApplication`` holds all the application
   components, such as ``CWebUser``, ``CUrlManager``, etc.

UML Diagram
-----------

.. image:: uml/uml.png
   :alt: Alt Registry UML Diagram
   :align: center

Code
----

You can also find these code on `GitHub`_

Registry.php

.. literalinclude:: Registry.php
   :language: php
   :linenos:

Test
----

Tests/RegistryTest.php

.. literalinclude:: Tests/RegistryTest.php
   :language: php
   :linenos:

.. _`GitHub`: https://github.com/domnikl/DesignPatternsPHP/tree/master/Structural/Registry
.. _`Registry`: http://en.wikipedia.org/wiki/Service_locator_pattern
