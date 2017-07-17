:man_page: mongoc_session_destroy

mongoc_session_destroy()
========================

Synopsis
--------

.. code-block:: c

  void
  mongoc_session_destroy (mongoc_session_t *session);

End a server-side session, if one has been created for this :symbol:`mongoc_session_t`, and free all client resources associated with the session.

See the example code for :symbol:`mongoc_session_t`.

Parameters
----------

* ``session``: A :symbol:`mongoc_session_t`.

.. only:: html

  .. taglist:: See Also:
    :tags: session
