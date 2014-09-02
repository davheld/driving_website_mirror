.. link:
.. description:
.. tags:
.. date: 2013/08/29 16:00:00
.. title: Publications
.. slug: papers


.. raw:: html

    <table class="papertable">
    <tr><td class="img">&nbsp;</td><td class="desc">&nbsp;</td></tr>

    
    
    <tr><td><img src="/papers/RSS2014.png"/></td>
    <td>
    <p>
        <span class="papertitle">Combining 3D Shape, Color, and Motion for Robust Anytime Tracking</span> <BR>
        <span class="authors"> David Held, Jesse Levinson, Sebastian Thrun, Silvio Savarese.</span> <BR>
        <span class="meeting">Robotics: Science and Systems (RSS),</span>&nbsp;<span class="year">2014.</span> <BR>
        <span class="summary">Although object tracking has been studied for decades, real-time tracking algorithms often suffer from low accuracy and poor robustness when confronted with difficult, real-world data. We present a tracker that combines 3D shape, color (when available), and motion cues to accurately track moving objects in real-time. Our tracker allocates computational effort based on the shape of the posterior distribution. Starting with a coarse approximation to the posterior, the tracker successively refines this distribution, increasing in tracking accuracy over time. The tracker can thus be run for any amount of time, after which the current approximation to the posterior is returned. Even at a minimum runtime of 0.7 milliseconds, our method outperforms all of the baseline methods of similar speed by at least 10%. If our tracker is allowed to run for longer, the accuracy continues to improve, and it continues to outperform all baseline methods. Our tracker is thus anytime, allowing the speed or accuracy to be optimized based on the needs of the application. 
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://www.roboticsproceedings.org/rss10/p14.html">pdf (rss)</a>,&nbsp;
        <a class="paperlink" href="http://stanford.edu/~davheld/anytime_tracking.html">Project Page - Supplementary material, C++ code, poster, presentation</a>,&nbsp;
        <a class="paperlink" href="/papers/RSS2014.bib">bib</a>
    </p>
    </td></tr>
    
    
    <tr><td><img src="http://cs.stanford.edu/people/teichman/img/iros2013-group_induction-c.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Group Induction</span> <BR>
        <span class="authors">Alex Teichman and Sebastian Thrun.</span> <BR>
        <span class="meeting">Proc. of the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS),</span>&nbsp;<span class="year">2013</span>. <BR>
        <span class="summary">Tracking-based semi-supervised learning, as originally presented at RSS2011, was an offline algorithm. This is fine in some contexts, but ideally a user could provide new hand-labeled training examples online, as the system runs, without retraining from scratch. Qualitatively, this would mean the ability to point out - from the back seat of your autonomous car - a few examples of, say, an elliptical bike or sk8poler, and the algorithm would start learning to recognize them on the fly without you having to do anything else. Group induction is a mathematical framework for this kind of learning. 
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/iros2013-group_induction.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/iros2013-group_induction.bib">bib</a>
    </p>
    </td></tr>
    
    
    <tr><td><img src="http://cs.stanford.edu/people/teichman/img/iros2013-extrinsics-b.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Unsupervised extrinsic calibration of depth sensors in dynamic scenes </span> <BR>
        <span class="authors">Stephen Miller, Alex Teichman and Sebastian Thrun.</span> <BR>
        <span class="meeting">Proc. of the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS),</span>&nbsp;<span class="year">2013</span>. <BR>
        <span class="summary"> This paper shows how to find the relative pose of two stationary depth sensors using only motion cues. Like the CLAMS paper, no calibration target, specialized hardware, or precise measurement is necessary.
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/iros2013-extrinsics.bib">bib</a>
    </p>
    </td></tr>

    
    
    <tr><td><img src="/papers/RSS2013.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Automatic Online Calibration of Cameras and Lasers</span> <BR>
        <span class="authors">Jesse Levinson and Sebastian Thrun.</span> <BR>
        <span class="meeting">Robotics: Science and Systems (RSS),</span>&nbsp;<span class="year">2013.</span> <BR>
        <span class="summary">Extending previous work on offline 6-DOF calibration
          of 3D laser sensors to 2D cameras, this paper presents two new real-time
          techniques that enable camera-laser calibration online, automatically,
          and in arbitrary environments. The first is a probabilistic monitoring
          algorithm that can detect a sudden mis-calibration in a fraction of a second.
          The second is a continuous calibration optimizer that adjusts transform
          offsets in real time, tracking gradual sensor drift as it occurs.
          Together, these techniques allow significantly greater flexibility
          and adaptability of robots in unknown and potentially harsh environments.
        </span>
    </p>
    <p>
        <a class="paperlink" href="/papers/RSS2013.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="/papers/RSS2013.bib">bib</a>
    </p>
    </td></tr>



    <tr><td><img src="/papers/ICRA2013.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Precision Tracking with Sparse 3D and Dense Color 2D Data</span> <BR>
        <span class="authors">David Held, Jesse Levinson, and Sebastian Thrun.</span> <BR>
        <span class="meeting">International Conference on Robotics and Automation (ICRA),</span>&nbsp;<span class="year">2013.</span> <BR>
        <span class="summary">Precision tracking is important for predicting
          the behavior of other cars in autonomous driving. We present a novel
          method to combine sparse laser data with a high-resolution camera image
          to achieve accurate velocity estimates of moving objects. We present
          a color-augmented, pre-filtered grid search algorithm to align the
          points from a tracked object, thereby obtaining much more precise
          estimates of the tracked vehicle’s velocity than were possible with
          previous methods.
        </span>
    </p>
    <p>
        <a class="paperlink" href="/papers/ICRA2013.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="/papers/ICRA2013.bib">bib</a>
    </p>
    </td></tr>




    <tr><td><img src="/papers/ISER2012.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Automatic Calibration of Cameras and Lasers in Arbitrary Scenes</span> <BR>
        <span class="authors">Jesse Levinson and Sebastian Thrun.</span> <BR>
        <span class="meeting">International Symposium on Experimental Robotics (ISER),</span>&nbsp;<span class="year">2012.</span> <BR>
        <span class="summary">This paper presents a new algorithm for automatically
          calibrating cameras to multi-beam lasers on a mobile robot given a
          series of frames from both sensors. Our method does not require the
          use of a known calibration target, nor does it require any hand
          labeling of correspondences. Even without these requirements, by
          leveraging unsupervised data, it still outperforms previous
          state-of-the-art calibration techniques by a significant margin.
        </span>
    </p>
    <p>
        <!--<a class="paperlink" href="/papers/ISER2012.pdf">pdf</a>,&nbsp;-->
        <a class="paperlink" href="/papers/ISER2012.bib">bib</a>
    </p>
    </td></tr>




    <tr><td><img src="http://cs.stanford.edu/people/teichman/img/rss2012_f.png"/></td>
    <td>
    <p>
        <span class="papertitle">Online, semi-supervised learning for long-term interaction with object recognition systems</span> <BR>
        <span class="authors">Alex Teichman and Sebastian Thrun.</span> <BR>
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
    </td></tr>


    <tr><td><img src="http://cs.stanford.edu/people/teichman/img/ijrr2012.png"/></td>
    <td>
    <p>
        <span class="papertitle">Tracking-based semi-supervised learning</span> <BR>
        <span class="authors">Alex Teichman and Sebastian Thrun.</span> <BR>
        <span class="meeting">International Journal of Robotics Research (IJRR),</span>&nbsp;<span class="year">2012</span>. <BR>
        <span class="summary">Extended journal version of previous work with the same title.
          More experiments, more intuition as to how the method works.
        </span>
    </p>
    <p>
        <a class="paperlink" href="http://ijr.sagepub.com/content/31/7/804">pdf (sage)</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/ijrr2012.bib">bib</a>
    </p>
    </td></tr>


    <tr><td><img src="/papers/ICRA2012.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">A Probabilistic Framework for Object Detection in Images using Context and Scale</span> <BR>
        <span class="authors">David Held, Jesse Levinson, and Sebastian Thrun.</span> <BR>
        <span class="meeting">International Conference on Robotics and Automation (ICRA),</span>&nbsp;<span class="year">2012</span>. <BR>
        <span class="summary">Detecting cars in real-world images is an important
          task for autonomous driving, yet it remains unsolved. The system
          described in this paper takes advantage of context and scale to build
          a monocular single-frame image-based car detector that significantly
          outperforms previous state-of-the-art methods.  By using a calibrated
          camera and localization on a road map, we are able to obtain context
          and scale information from a single image without the use of a 3D laser.
        </span>
    </p>
    <p>
        <a class="paperlink" href="/papers/ICRA2012.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="/papers/ICRA2012.bib">bib</a>
    </p>
    </td></tr>

    

    <tr><td><img src="http://cs.stanford.edu/people/teichman/img/arso2011.png"/></td>
    <td>
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
    </td></tr>


    <tr><td><img src="http://cs.stanford.edu/people/teichman/img/rss2011_b.jpg"/></td>
    <td>
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
    </td></tr>


    <tr><td><img src="http://cs.stanford.edu/people/teichman/img/icra2011.jpg"/></td>
    <td>
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
    </td></tr>


    <tr><td><img src="http://cs.stanford.edu/people/teichman/img/iv2011.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Towards fully autonomous driving: systems and algorithms</span> <BR>
        <span class="authors">Jesse Levinson, Jake Askeland, Jan Becker, Jennifer Dolson, David Held,
          Soeren Kammel, J. Zico Kolter, Dirk Langer, Oliver Pink, Vaughan Pratt,
          Michael Sokolsky, Ganymed Stanek, David Stavens, Alex Teichman,
          Moritz Werling, and Sebastian Thrun.</span> <BR>
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
    </td></tr>



    <tr><td><img src="/papers/ICRA2011.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Traffic Light Mapping, Localization, and State Detection for Autonomous Vehicles</span> <BR>
        <span class="authors">Jesse Levinson, Jake Askeland, Jennifer Dolson, and Sebastian Thrun.</span> <BR>
        <span class="meeting">International Conference on Robotics and Automation (ICRA),</span>&nbsp;<span class="year">2011.</span> <BR>
        <span class="summary">We present a passive camera-based pipeline for
          traffic light state detection using imperfect vehicle localization
          and assuming prior knowledge of traffic light location. To achieve
          robust real-time detections in a variety of lighting conditions,
          we combine several probabilistic stages that explicitly account for
          the corresponding sources of sensor and data uncertainty.
        </span>
    </p>
    <p>
        <a class="paperlink" href="/papers/ICRA2011.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="/papers/ICRA2011.bib">bib</a>
    </p>
    </td></tr>


    <tr><td><img src="/papers/LevinsonThesis.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Automatic laser calibration, mapping, and localization for autonomous vehicles</span> <BR>
        <span class="authors">Jesse Levinson.</span> <BR>
        <span class="meeting">Thesis (Ph.D.), Stanford University,</span>&nbsp;<span class="year">2011.</span> <BR>
        <span class="summary">This dissertation presents several related algorithms
        that enable important capabilities for self-driving vehicles. These include
        offline mapping and online map-based localization techniques using GPS, IMU,
        and lasers, online localization without a prerecorded map as used in the
        DARPA Urban Challenge, intrinsic and extrinsic calibration algorithms
        for multi-beam lasers, and realtime detection of traffic lights.
        </span>
    </p>
    <p>
        <a class="paperlink" href="https://stacks.stanford.edu/file/druid:zx701jr9713/JesseThesisFinal2-augmented.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://purl.stanford.edu/zx701jr9713">Stanford Library</a>,&nbsp;
        <a class="paperlink" href="/papers/LevinsonThesis.bib">bib</a>
    </p>
    </td></tr>


    <tr><td><img src="/papers/ISER2010.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Unsupervised Calibration for Multi-beam Lasers</span> <BR>
        <span class="authors">Jesse Levinson and Sebastian Thrun.</span> <BR>
        <span class="meeting">International Symposium on Experimental Robotics (ISER),</span>&nbsp;<span class="year">2010.</span> <BR>
        <span class="summary">This paper introduces an unsupervised solution
          for solving the intrinsic and extrinsic calibration properties of a
            multi-beam laser on a mobile robot in arbitrary, unknown environments.
            By defining and optimizing an objective function that rewards
            3D consistency between points seem by different beams, we are able
            to calibrate internal angles, range offsets, and remittance response
            curves for each beam in addition to the 6-DOF position of the laser
            relative to the vehicle's inertial frame.
        </span>
    </p>
    <p>
        <a class="paperlink" href="/papers/ISER2010.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="/papers/ISER2010.bib">bib</a>
    </p>
    </td></tr>


    <tr><td><img src="/papers/ICRA2010.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Robust Vehicle Localization in Urban Environments Using Probabilistic Maps</span> <BR>
        <span class="authors">Jesse Levinson and Sebastian Thrun.</span> <BR>
        <span class="meeting">International Conference on Robotics and Automation (ICRA),</span>&nbsp;<span class="year">2010.</span> <BR>
        <span class="summary">We extend previous work on localization using GPS,
        IMU, and LIDAR data by modeling the environment as a probabilistic grid
        in which every cell is represented as its own gaussian distribution over
        remittance values. This approach offers higher precision, the ability
        to learn and improve maps over time, and increased robustness to
        environment changes and dynamic obstacles.
      </span>
    </p>
    <p>
        <a class="paperlink" href="/papers/ICRA2010.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="/papers/ICRA2010.bib">bib</a>
    </p>
    </td></tr>


    <tr><td><img src="http://cs.stanford.edu/people/teichman/img/ijcai2009.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Exponential family sparse coding with application to self-taught learning</span> <BR>
        <span class="authors">Honglak Lee, Rajat Raina, Alex Teichman, and Andrew Y. Ng.</span> <BR>
        <span class="meeting">International Joint Conference on Artificial Intelligence (IJCAI),</span>&nbsp;<span class="year">2009.</span> <BR>
        <span class="summary"> </span>
    </p>
    <p>
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/ijcai2009.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="http://cs.stanford.edu/people/teichman/papers/ijcai2009.bib">bib</a>
    </p>
    </td></tr>


    <tr><td><img src="/papers/RSS2007.jpg"/></td>
    <td>
    <p>
        <span class="papertitle">Map-Based Precision Vehicle Localization in Urban Environments</span> <BR>
        <span class="authors">Jesse Levinson and Sebastian Thrun.</span> <BR>
        <span class="meeting">Robotics: Science and Systems (RSS),</span>&nbsp;<span class="year">2007.</span> <BR>
        <span class="summary">GPS-based inertial guidance systems do not provide
          sufficient accuracy for many urban navigation applications, including
          autonomous navigation. We propose a technique for high-accuracy
          localization of moving vehicles that utilizes maps of urban environments.
          Our approach integrates GPS, IMU, wheel odometry, and LIDAR data to
          generate high-resolution environment maps. We use offline GraphSLAM
          techniques to align intersections and regions of self-overlap, and
          a particle filter to localize the vehicle relative to these maps in
          real time.
        </span>
    </p>
    <p>
        <a class="paperlink" href="/papers/RSS2007.pdf">pdf</a>,&nbsp;
        <a class="paperlink" href="/papers/RSS2007.bib">bib</a>
    </p>
    </td></tr>
    </table>

