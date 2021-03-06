:man_page: mongoc_session_opts_get_causal_consistency

mongoc_session_opts_get_causal_consistency()
===================================================

Synopsis
--------

.. code-block:: c

  bool
  mongoc_session_opts_get_causal_consistency (mongoc_session_opt_t *opts);

Return true if this session is configured for causal consistency, else false (the default). See :symbol:`mongoc_session_opts_set_causal_consistency()`.

Parameters
----------

* ``opts``: A :symbol:`mongoc_session_opt_t`.

.. only:: html

  .. taglist:: See Also:
    :tags: session
