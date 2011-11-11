========================
Sphinx デモドキュメント
========================

文字列をいれる

* 箇条書き１
* 箇条書き２
    1. foo
    2. bar


コードハイライト:

    .. code-block:: python

        class Foo(object):

            def __init__(self, value):
                print "value = %d" % value
                raise NotImplementedError(u'EmptyClass')


.. toctree::
   :maxdepth: 2

   20110304_osc_tokyo_spring
   sphinx-users-q-and-a


.. math:: (a + b)^2 = a^2 + 2ab + b^2

.. math::
   :nowrap:

   \begin{eqnarray}
      y    & = & ax^2 + bx + c \\
      f(x) & = & x^2 + 2xy + y^2
   \end{eqnarray}


BlockDiag
==========

.. blockdiag::

    {
      A [label="自分"];
      A -> B [label="Open"];
      A -> C;

      O -> P -> C;
    }

SeqDiag
========

.. seqdiag::

    {
      A  => B;
      A  -> B;
      A <-- B;

      A => C => D;
    }




Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

