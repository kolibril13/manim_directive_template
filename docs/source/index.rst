 Example Gallery
========================================

Here is the directive example

.. manim:: ManimCELogo

    class DarkThemeBanner(Scene):
        def construct(self):
            banner = ManimBanner()
            self.play(banner.create())
            self.play(banner.expand())
            self.wait()
            self.play(Unwrite(banner))

.. .. toctree::
..    :maxdepth: 2
..
..       examples


.. Indices and tables
.. ==================

.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`