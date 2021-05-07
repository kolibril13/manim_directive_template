 Example Gallery
========================================

Here is the directive example

.. manim:: ManimCELogo

    class ManimCELogo(Scene):
        def construct(self):
            banner = ManimBanner().scale(0.5)
            self.play(banner.create())
            self.play(banner.expand())
            self.wait()

.. .. toctree::
..    :maxdepth: 2
..
..       examples


.. Indices and tables
.. ==================

.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`