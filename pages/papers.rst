.. link:
.. description:
.. tags:
.. date: 2013/08/29 16:00:00
.. title: Publications
.. slug: papers

.. csv-table::
   :class: papertable
   :widths: 1, 99

   "|rss2013_img|", "|rss2013_desc|"
   "|tase2013_img|", "|tase2013_desc|"
   "|rss2012_f_img|", "|rss2012_f_desc|"
   "|ijrr2012_img|", "|ijrr2012_desc|"
   "|wafr2012_b_img|", "|wafr2012_b_desc|"
   "|arso2011_img|", "|arso2011_desc|"
   "|rss2011_b_img|", "|rss2011_b_desc|"
   "|icra2011_img|", "|icra2011_desc|"
   "|iv2011_img|", "|iv2011_desc|"
   "|ijcai2009_img|", "|ijcai2009_desc|"
   "|ijrr2008_img|", "|ijrr2008_desc|"


   
.. |rss2013_img| image:: http://cs.stanford.edu/people/teichman/img/rss2013-b.jpg

.. |rss2013_desc| raw:: html

    <p>
        <span class="papertitle"> Unsupervised intrinsic calibration of depth sensors via SLAM </span> <BR>
        <span class="authors">Alex Teichman, Stephen Miller, and Sebastian Thrun.</span> <BR>
        <span class="meeting">Robotics: Science and Systems (RSS),</span>&nbsp;<span class="year">2013.</span> <BR>
        <span class="summary">RGBD sensors such as the Xtion Pro Live or Kinect typically have
          significant depth distortion beyond two or three meters. This paper introduces
          a method of calibrating away the distortion just by recording data from a handheld sensor.
          No calibration target, specialized hardware, or precise measurement is necessary.
          The method is more generally applicable, too, as it requires only that the
          intrinsic parameter in question be <i>myopic</i>: error in the parameter
          setting generates greater measurement error as range increases.
          This includes, for example, focal length and center pixel of a depth camera.
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/rss2013.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/octo/clams/">code</a>,&nbsp;
        <a class="paperlink" href="http://roboticsproceedings.org/rss09/p27.html">rss link</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/rss2013.bib">bib</a>
    </p>


.. |tase2013_img| image:: http://cs.stanford.edu/people/teichman/img/tase2013-b.jpg

.. |tase2013_desc| raw:: html

    <p>
        <span class="papertitle"> Learning to segment and track in RGBD </span> <BR>
        <span class="authors">Alex Teichman, Jake Lussier, and Sebastian Thrun.</span> <BR>
        <span class="meeting">IEEE Transactions on Automation Science and Engineering,</span>&nbsp;<span class="year">2013.</span> <BR>
        <span class="summary">Extended journal version of previous work with the same title.
          This paper includes algorithmic optimizations that enable real-time
          segmentation and tracking of arbitrary objects, as well as an application
          example in which we use the algorithm to train an object detector without
          the usual hassles of a turntable or crowdsourced annotation.
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/tase2013.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/tase2013.bib">bib</a>
    </p>

   
.. |rss2012_f_img| image:: http://cs.stanford.edu/people/teichman/img/rss2012_f.png

.. |rss2012_f_desc| raw:: html

    <p>
        <span class="papertitle"> Online, semi-supervised learning for long-term interaction with object recognition systems </span> <BR>
        <span class="authors">Alex Teichman and Sebastian Thrun. </span> <BR>
        <span class="meeting">Invited talk at RSS Workshop on Long-term Operation of Autonomous Robotic Systems in Changing Environments,</span>&nbsp;<span class="year">2012.</span> <BR>
        <span class="summary">Tracking-based semi-supervised learning, as originally
          presented at RSS2011, was an offline algorithm.  This is fine in some
          contexts, but ideally a user could provide new hand-labeled training
          examples online, as the system runs, without retraining from scratch.
          Qualitatively, this would mean the ability to point out - from the
          back seat of your autonomous car - a few examples of, say, an
          <a class="paperlink" href="http://pbanews.org/wp-content/uploads/2010/09/Elliptical-Bike.jpg" target="_blank">
          elliptical bike</a> or
          <a class="paperlink" href="http://www.carve.cz/wp-content/uploads/2012/08/ladronkasurfskate-19.jpg" target="_blank">
          sk8poler</a>, and tracking-based semi-supervised learning would start learning to
          recognize them on the fly without you having to do anything else.
          This talk discusses some preliminary work in this direction.
        </span>
    </p>
    <p><a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/rss2012_presentation.pdf">presentation</a></p>


.. |ijrr2012_img| image:: http://cs.stanford.edu/people/teichman/img/ijrr2012.png

.. |ijrr2012_desc| raw:: html

    <p>
        <span class="papertitle">Tracking-based semi-supervised learning</span> <BR>
        <span class="authors">Alex Teichman and Sebastian Thrun.</span> <BR>
        <span class="meeting">International Journal of Robotics Research (IJRR),</span>&nbsp;<span class="year">2012</span>. <BR>
        <span class="summary">Extended journal version of previous work with the same title.
          More experiments, more intuition as to how the method works.
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://ijr.sagepub.com/content/31/7/804">sage</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/ijrr2012.bib">bib</a>
    </p>


.. |wafr2012_b_img| image:: http://cs.stanford.edu/people/teichman/img/wafr2012-b.jpg

.. |wafr2012_b_desc| raw:: html

    <p>
        <span class="papertitle">Learning to segment and track in RGBD</span> <BR>
        <span class="authors">Alex Teichman and Sebastian Thrun.</span> <BR>
        <span class="meeting">Workshop on the Algorithmic Foundations of Robotics (WAFR),</span>&nbsp;<span class="year">2012</span>. <BR>
        <span class="summary">Tracking-based semi-supervised learning requires some method
          of model-free segmentation and tracking. This paper describes a method
          of model-free segmentation and tracking that can work in a broad range
          of environments where segmentation is non-trivial.
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/wafr2012.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/wafr2012.bib">bib</a>
    </p>


.. |arso2011_img| image:: http://cs.stanford.edu/people/teichman/img/arso2011.png

.. |arso2011_desc| raw:: html
    
    <p>
        <span class="papertitle">Practical object recognition in autonomous driving and beyond</span> <BR>
        <span class="authors">Alex Teichman and Sebastian Thrun.</span> <BR>
        <span class="meeting">IEEE Workshop on Advanced Robotics and its Social Impacts (ARSO),</span>&nbsp;<span class="year">2011</span>. <BR>
        <span class="summary">This paper gives an overview of the recent object recognition
          research in our lab and what is needed to make it a fully functional,
          high accuracy object recognition system that is applicable beyond
          perception for autonomous driving.
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/arso2011.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/arso2011.bib">bib</a>
    </p>


.. |rss2011_b_img| image:: http://cs.stanford.edu/people/teichman/img/rss2011_b.jpg

.. |rss2011_b_desc| raw:: html

    <p>
        <span class="papertitle">Tracking-based semi-supervised learning</span> <BR>
        <span class="authors">Alex Teichman and Sebastian Thrun.</span> <BR>
        <span class="meeting">Robotics: Science and Systems (RSS),</span>&nbsp;<span class="year">2011</span>. <BR>
        <span class="summary">Building on previous work, we introduce a simple semi-supervised
          learning method that uses tracking information to find new, useful training
          examples automatically. This method achieves nearly the same accuracy
          as before, but with about two orders of magnitude less human labeling effort.
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/rss2011.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/rss2011.bib">bib</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/rss2011.html">project</a>,&nbsp;
        <a class="paperlink" href="http://www.roboticsproceedings.org/rss07/p42.html">RSS proceedings</a>
    </p>


.. |icra2011_img| image:: http://cs.stanford.edu/people/teichman/img/icra2011.jpg

.. |icra2011_desc| raw:: html

    <p>
        <span class="papertitle">Towards 3D object recognition via classification of arbitrary object tracks</span> <BR>
        <span class="authors">Alex Teichman, Jesse Levinson, and Sebastian Thrun.</span> <BR>
        <span class="meeting">International Conference on Robotics and Automation (ICRA),</span>&nbsp;<span class="year">2011</span>. <BR>
        <span class="summary">Breaking down the object recognition problem into segmentation,
          tracking, and track classification components, we show an accurate and
          real-time method of classifying tracked objects as car, pedestrian,
          bicyclist, or 'other'.
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/icra2011.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/icra2011.bib">bib</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/stc/">dataset</a>
    </p>


.. |iv2011_img| image:: http://cs.stanford.edu/people/teichman/img/iv2011.jpg

.. |iv2011_desc| raw:: html
    
    <p>
        <span class="papertitle"> Towards fully autonomous driving: systems and algorithms </span> <BR>
        <span class="authors"> Jesse Levinson, Jake Askeland, Jan Becker, Jennifer Dolson, David Held,
          Soeren Kammel, J. Zico Kolter, Dirk Langer, Oliver Pink, Vaughan Pratt,
          Michael Sokolsky, Ganymed Stanek, David Stavens, Alex Teichman,
          Moritz Werling, and Sebastian Thrun. </span> <BR>
        <span class="meeting">Intelligent Vehicles Symposium,</span>&nbsp;<span class="year">2011.</span> <BR>
        <span class="summary">This paper is a broad summary of recent work on Junior,
          Stanford's autonomous vehicle. Topics covered include object recognition,
          sensor calibration, planning, control, etc.
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/iv2011.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/iv2011.bib">bib</a>
    </p>


.. |ijcai2009_img| image:: http://cs.stanford.edu/people/teichman/img/ijcai2009.jpg

.. |ijcai2009_desc| raw:: html

    <p>
        <span class="papertitle"> Exponential family sparse coding with application to self-taught learning </span> <BR>
        <span class="authors"> Honglak Lee, Rajat Raina, Alex Teichman, and Andrew Y. Ng. </span> <BR>
        <span class="meeting"> International Joint Conference on Artificial Intelligence (IJCAI),</span>&nbsp;<span class="year">2009.</span> <BR>
        <span class="summary"> </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/ijcai2009.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/ijcai2009.bib">bib</a>
    </p>


.. |ijrr2008_img| image:: http://cs.stanford.edu/people/teichman/img/ijrr2008.jpg

.. |ijrr2008_desc| raw:: html

    <p>
        <span class="papertitle"> Automatic configuration recognition methods in modular robots </span> <BR>
        <span class="authors"> Michael Park, Sachin Chitta, Alex Teichman, Mark Yim </span> <BR>
        <span class="meeting"> International Journal of Robotics Research (IJRR),</span>&nbsp;<span class="year">2008.</span> <BR>
        <span class="summary"> </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/ijrr2008.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/ijrr2008.bib">bib</a>
    </p>
