.. include:: /Includes.rst.txt
.. _columns-group-properties-appearance:

==========
appearance
==========

.. confval:: appearance

   :type: array
   :Scope: Display
   :InternalType: all

   Options for refining the appearance of group-type fields.

   elementBrowserType (string)
      Allows set an alternative element browser type ("db" or "file") than would otherwise be rendered based on
      the "internal_type" setting. This is used internally for :ref:`FAL<t3fal:start>` file fields, where
      internal_type is "db" but the element browser should be the file element browser anyway.

   elementBrowserAllowed (string)
      Makes it possible to set an alternative element browser allowed string than would otherwise be taken from the
      "allowed" setting of this field. This is used internally for :ref:`FAL<t3fal:start>` file fields, where this
      is used to supply the comma list of allowed file types.
