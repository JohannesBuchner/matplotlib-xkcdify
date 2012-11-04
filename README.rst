XKCDify
==============

Sketchy, imprecise plotting theme for matplotlib. 

Sometimes you want to illustrate a point and do not want to emphasize on accuracy but on overall relations. This code originated at `jakevdp's blog 
<http://jakevdp.github.com/blog/2012/10/07/xkcd-style-plots-in-matplotlib/>`_.

Semi-log and log-log plots
---------------------------

Just take the logarithm before calling the plotting functions, i.e. give matplotlib the base-10 logarithms of the values. Then set the tick labels with the true values::

   ax.set_xticks([-3, -2, -1], ['1e-3', '1e-2', '1e-1'])

Sometimes XKCDify also does not appreciate large/negative values. You can solve this by transformations into a space it likes.

References:
-------------

* http://jakevdp.github.com/blog/2012/10/07/xkcd-style-plots-in-matplotlib/
* https://github.com/matplotlib/matplotlib/pull/1329


