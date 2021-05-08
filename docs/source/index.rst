 Example Gallery
========================================

Here is the directive example

.. manim:: ManimCELogo

    import pkg_resources
    version_num = pkg_resources.get_distribution("manim").version

    class ManimCELogo(Scene):
        def construct(self):
            banner = ManimBanner().scale(0.5)
            self.add(Text(f"manim version {version_num}").set_color(WHITE).shift(DOWN))
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