.. title: Research
.. slug: research
.. date: 2016-01-17 09:19:26 UTC-07:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

My PhD research primarily involved the development of a confocal
microendoscope for optical biopsies in surgery. My specific
contributions to this project were:

1. developing the surgical imaging catheters
2. developing the contrast agent delivery system
3. developing the focus / depth scan mechanism
4. making the overall instrument smaller for operating room use
5. writing the instrument software interface
6. developing a higher resolution and larger NA objective lens targeted
   for use in esophageal cancer

We are currently in human trials using the device to image ovarian
cancer in high risk women.

I am still adding content to this page. Below are figures illustrating
the device. More information will be added soon.

The Confocal Microendoscope
===========================


.. figure:: endoscopes/ClinicalImagingWithCart.jpg
   :alt: System in use during surgery

   System in use during surgery

The surgical microendoscope system imaging the epithelial surface of an
ovary during surgery. In this image the surgeon has located the left
ovary using a wide field endoscope (left most display) and is inspecting
the epithelial cells using the microendoscope via the second display
from the left. The mobile instrument is on the far right.


.. media:: https://youtu.be/ewLRWBptY3Q

In vivo confocal microlaparoscope video of the human ovary using topically applied
fluorescein sodium as the contrast agent. The pathology report diagnosis was serous
cystadenoma. (Circular field of view is 450μm.)


Need for real-time optical biopsies in surgery
----------------------------------------------

Successful treatment of cancer is highly dependent on the stage at which
diagnosis occurs. Early diagnosis, when the disease is still localized
at its origin, results in very high cure rates—even for cancers that
typical have poor prognosis. Unfortunately, many cancers are not found
until later stages due to inadequate diagnostic techniques.
Approximately 90% of cancers arise from the epithelial cells that cover
organs [1]_. Development of surgical devices that can better interrogate
epithelial surfaces for abnormalities would enable earlier detection of
cancer and significant gains in overall patient survival.

Diagnosis of cancer is often done by pathologists using thin sections of
stained and processed biopsy tissue. Bright field microscopy has played
a central role in the diagnosis of disease from carefully prepared
biopsy slides. Confocal microscopy, a more recent innovation, is also
being used with greater frequency because it can directly image bulk
sections of tissue with high clarity. Bright field images of bulk tissue
appear very blurry due to simultaneous collection of out of focus
planes. However, confocal images of bulk tissue are sharp because the
microscope only collects light from in focus planes; light from out of
focus planes is rejected.

Since the confocal microscope alleviates the need for cutting tissue
into thin sections, it has significant potential as an in-vivo imaging
device that could supplant biopsies. However, a standard confocal
microscope is a large device that is not especially suited for accessing
the epithelial surface of most organs where biopsies are acquired.
Realizing the potential of confocal imaging to ultimately supplant
biopsies via in-vivo imaging, we worked on the initial technologies to
enable in-vivo confocal imaging via coherent fiber optic bundles [2]_.
Since the initial work, our research group has continued developing
technologies to allow live in-vivo human cellular imaging via confocal
microendoscopy during surgery.

Case study: patients at high risk of ovarian cancer
---------------------------------------------------

The American Cancer Society estimates that over 230,000 new cases of
ovarian cancer were diagnosed in 2007 while more than 141,000 women died
from the disease worldwide. [3]_ For those diagnosed with the disease,
only 30 to 45 percent will survive five years. [4]_  [5]_ The survival
rate for ovarian cancer is poor because the disease frequently has no
obvious signs until it has reached an advanced stage. Only 19 percent of
all cases are diagnosed during the early localized stages of the
disease; most of the population are diagnosed during the later stages
when the treatment is expensive and generally unsuccessful.

For the female population at large, most are at a low risk of acquiring
ovarian cancer. It is estimated that approximately 1 in 58 newborn
females (1.7 percent lifetime risk) will develop ovarian cancer in their
lifetime. [6]_ However, the lifetime risk for the disease increases by
two fold if the individual has one first or second-degree relative with
the disease. With two first-degree relatives the risk increases by 25x
(a 40 percent lifetime risk). [7]_  [8]_  [9]_  [10]_

For the subgroups of women at increased risk, few options exist to allow
early detection of the disease. The delicate epithelial surface of the
ovary is not amenable for biopsy. The NIH 1994 consensus stated that
there is no single acceptable screening test for ovarian cancer and no
evidence that combining the available screening tests—CA125,
transvaginal ultrasound, and pelvic exam—has an acceptable sensitivity
and specificity. [11]_ Ovarian cancer is thought to metastasize early in
the course of the disease and many experts believe that a different
biology occurs during Stage I cancer as compared to the later stages. In
Stage I, it is thought that the cancer often metastasizes before a
lesion in the ovary becomes grossly visible. Without a viable method for
early detection of the disease, most women at high risk are provided the
option of prophylactic oophorectomy. Preemptive oophorectomies have the
negative side effects of sterility and loss of natural hormone
production. Hormone replacement is typically not an option for this
subgroup since they are also at an increased risk for breast cancer and
hormone replacement can further increase this risk.

In the following sections we discuss a confocal microendoscope system
that is generally applicable to in-vivo imaging of epithelial cells. The
technology is applied to the subgroup of women at high risk for ovarian
cancer who have no suitable methods to detect cancer in its early
stages. Our mobile device provides the surgeon with real-time in-vivo
confocal images. The long term objective is to allow the physician to
determine if the ovary is healthy and circumvent unnecessary
prophylactic oophorectomy.

Surgical System
---------------


.. figure:: endoscopes/ClinicalCart.png
   :alt: Surgical cart

   Mobile surgical system.



Our surgical confocal microendoscope system consists of an imaging
catheter connected to a mobile cart. The mobile system can be easily
moved into an operating room when live cellular imaging is needed. All
the system components are housed on a mobile endoscopy cart. The above
figure depicts the system’s components. The top shelf houses the sterile
imaging catheter and other necessary surgical supplies. The second shelf
contains the optical scanning system—discussed in the following
paragraphs—which directly connects to the imaging catheter. The third
and fourth shelves house the laser, function generator, and computer.
The bottom shelf houses the medical grade isolation transformer and
laser safety goggles. The operator display and the controls for
collecting data during surgery are located on a platform at standing
height.

.. figure:: endoscopes/ClinicalOpticsLayout.png
   :alt: Optical components

   Optical components

Diagram of the optical scanning system. The left side illustrates the
standard mode of operation. A 488 nm laser is anamorphically shaped into
a line and scanned onto the coherent fiber bundle in the imaging
catheter. The excited signal re-enters the system, is descanned and
filtered through a confocal slit. Then the light is rescanned onto a two
dimensional detector. In the spectral imaging mode, the image scan
mirror is turned to its extreme position redirecting the light through a
dispersing prism.


At the core of the confocal microendoscope system is the optical
scanning system. The components and layout are shown above. The left
side of the figure shows how the system operates in the standard live
imaging mode. In this mode a 488 nm solid state laser beam is expanded
and anamorphically shaped into a line via a cylindrical lens. This laser
line is then reflected into the image path by a dichroic filter and
scanned across the coherent fiber bundle face at the proximal end of the
imaging catheter’s connector.

Tissue fluorescence is collected by the imaging catheter, collimated
back into the optical scanning system, and de-scanned using the object
scan mirror. The dichroic filter passes the fluorescence signal, which
is focused down to a stationary line. A slit serves as the confocal
aperture. The light exiting the slit is then re-collimated and rescanned
using the image scan mirror. A final filter removes residual excitation.
Finally the beam is refocused back into a line that sweeps across the
camera to collect a two-dimensional image every 1∕30th of a second. In
addition to live two-dimensional imaging, the system can also collect
multi-spectral data. [12]_  [13]_ This multi-spectral mode is instantly
achieved via a software button that deflects the object scan mirror to
its extreme position. In this configuration, the light passes through a
prism and the dispersed signal is collected by the camera. Since one
spatial dimension on the camera is used for spectral collection, the
second image spatial dimension is collected over time. The complete
spectral data collection procedure executes in a few seconds. Once
spectral collection is complete the system reverts back to its grayscale
operating mode.


.. figure:: endoscopes/ClinicalSoftware.png
   :alt: Surgical software

   Surgical software


The mobile system has been designed to streamline all operations during
surgery. Once the system is plugged in and the safety interlocks
engaged, the system boots and all hardware is initialized. Hardware
initialization includes the solid state laser, camera, dye delivery
system, and function generator for scan mirror control. After the
automatic initialization, the operator is presented with the software
control system auto-initialized for live imaging.

The above figure shows the software control system. It provides a simple
interface for viewing and collecting live images during the surgical
procedure. The software has controls to: (1) start live acquisition, (2)
save the current frame, (3) record video, (4) delivery dye, (5) load
dye, and (6) adjust histogram optimization. In addition to the basic
controls, the system also records procedure and patient information,
which is archived with the images. Basic diagnostic information such as
image dynamic range and frame rate are also visible. During operation
the surgeon can easily see real-time imagery in the main window along
with data acquisition and dye delivery status.

Imaging Catheters
-----------------


.. figure:: endoscopes/Endoscopes.png
   :alt: Endoscopes

   Endoscopes

The confocal imaging catheters. A laparoscopic version is shown on top
with an integrated dye delivery system that uses a piezo valve and
pressurized syringe. The lower left of the figure shows the flexible
endoscope version of the device. Both devices have the same handle that
uses a depth/focus knob to translate the coherent fiber bundle routed
through the center of the device (handle detail shown to the right).



The imaging catheter comes in two varieties, a rigid laparoscope 5 mm in
diameter and a flexible endoscope 4.2 mm in diameter; both provide the
same functionality. This compact instrument contains the
micro-objective, coherent fiber optic bundle, dye delivery system, and
depth/focus mechanism. In use, the imaging catheter feels like a wide
field endoscope except that imaging is done with the probe in contact
with the tissue.

Figure 4 depicts the two varieties of the imaging catheter. A twenty
foot flexible housing connects to the optical scanning system and
protects the coherent fiber optic bundle and electrical connections. The
distal tip of the instrument contains a micro-objective [14]_ lens that
images tissue onto the coherent fiber bundle. The micro-objective
connects to a housing that contains the fiber bundle. Running parallel
to the housing is a 21.5 gauge channel that delivers controlled volumes
of fluorescent dyes onto the tissue in the imaging catheter’s field of
view. The outer surface of the lens and the fiber housing (excluding the
face of the lens) are sealed inside a medical grade teflon sheath. The
imaging catheter is designed for reuse; it can be quickly disconnected
from the optical scanning system and sterilized using Ethylene Oxide.

We have investigated a variety of depth/focus mechanisms [15]_  [16]_
[17]_ and now present a new method that has proven to be more reliable
and easier to use during surgery. Rotation of the depth/focus knob on
the handle causes the fiber optic bundle to translate along the optical
axis. Translation of the fiber via the depth/focus knob allows the
surgeon to select the desired imaging plane in the tissue. Since the
system is designed for contact imaging on the epithelial surface of
organs, once optimal focus has been obtained refocus is not necessary.
The surgeon can simply move across the tissue and change sites while
maintaining focus since contacting the tissue will bring the epithelial
cells into focus. The surgeon can use the depth/focus knob to image
planes below the surface for further interrogation of abnormalities.


.. figure:: endoscopes/DyeDelivery.png
   :alt: Dye delivery

   Dye delivery

Demonstration of the imaging catheter's ability to locally deliver small
volumes of dye to the field of view. In this sequence of images (at
1/30th second intervals) the operator presses the dye delivery button
and the dye is delivered to the distal tip via actuation of the piezo
valve near the imaging catheters's handle. The delivered volume in this
example is approximately 1 uL.



We have developed a localized dye delivery system that minimizes patient
exposure to fluorescent contrast agents and provides a method to mark
imaged tissue sites. At the tip of the imaging catheter, a 21.5 gauge
channel conforms around the face of the micro-objective to deliver dye
directly to the field of view. The system is capable of delivering very
small dye quantities on demand, down to 0.1 μL. Once the operator pushes
the dye delivery button, a piezo valve located behind the imaging
catheter handle opens for a few milliseconds. A pressurized syringe
behind the valve containing a fluorescent contrast agent supplies dye
through the dye channel to the field of view. The above figure shows the
dye delivery process in 1∕30th second intervals; full delivery occurs in
approximately 1∕6th of a second.

Human results
-------------

The confocal microendoscope system is currently being evaluated in
clinical trials to image the epithelial surface of the ovary at the
University Medical Center in Tucson, Arizona. The device was granted
“non significant risk” status by the University of Arizona’s
Institutional Review Board and has been approved for use in humans using
a protocol that includes topical application of sodium fluorescein as
the contrast agent. [18]_

.. figure:: endoscopes/OvaryAO.png
   :alt: Ovarian tissue with Acridine Orange

   Images of human ovary epithelium obtained ex-vivo using acridine orange.
   Sub-captions contain pathology diagnosis.


.. media:: https://youtu.be/3c9ws2dsuwc

Ex vivo video of normal appearing ovary epithelium tissue stained with acridine
orange. (Circular field of view is 450 μm.)


.. media:: https://youtu.be/HbQFZHAFMhY

Ex vivo video of abnormal appearing ovary epithelium tissue stained with acridine orange.
The pathology report diagnosis was serous cystadenoma. (Circular field of view is 450 μm.)


The images with acridine orange, shown above, demonstrate the excellent
diagnostic ability of the instrument. The epithelial surface of a
healthy ovary is characterized by a homogeneous distribution of bright
nuclei seen in (a). The epithelial surface of the ovary is delicate and
partial denuding can occur, exposing the underlying stroma (b). Below
the epithelial surface, healthy stroma also exhibits a
characteristically homogenous structure albeit with a different nuclear
size distribution and shape (c).

In the case of carcinoma, the tissue structure is visibly differentiable
(d) from healthy epithelial cells (a). The epithelial surface is
irregular and the high degree of heterogeneity indicative of ovarian
cancer.

We have perviously shown [19]_ that the confocal microendoscope system
can easily differentiate normal epithelium from ovarian cancer—providing
a diagnostic advantage when the neoplasia is small and not visible at
the gross anatomic level. It also appears that the confocal
microendoscope system may also be able to visualize cellular changes
that happen prior to the onset of cancer. Less distinct tissue changes
such as tissue sclerosis and endometriosis may also be detectable

.. figure:: endoscopes/OvaryFluorescein.png
   :alt: Ovarian tissue with Fluorescein

   Images of ovary epithelium obtained in-vivo during clinical trials using
   fluorescein. The suboptimal cellular detail is a result of the minimal
   preferential binding exhibited by fluorescein.


For initial in-vivo clinical studies fluorescein was selected because of
its pre-existing approval for human use. The diagnostic utility of
fluorescein when used as a topical contrast agent on the ovary is not
very good as it provides little contrast and lacks preferential binding
to cellular level structures of interest. However, it has served its
purpose as a safe, pre-approved contrast agent allowing us to test the
safety and feasibility of the confocal microendoscope system.

The above figure shows three examples of in-vivo images obtained with
the confocal microendoscope system. The images demonstrate that the
device functions as designed. The imaging catheter can deliver
controlled volumes of dye to the image site and then display real-time
image data to the surgeon. The focus mechanism works well; after an
initial adjustment of the focus, the instrument can be moved to various
sites on the ovary while maintaining good focus on the epithelial
surface.


.. figure:: endoscopes/EsophagusAO.png
   :alt: Esophagus tissue with Acridine Orange

   Images of human esophagus epithelium obtained ex-vivo using acridine orange.




As previously discussed, any lumen or organ that is endoscopically or
laparoscopically accessible is a suitable candidate for microendoscope
imaging of the epithelium. Applications of the device to detect the
transformation of normal esophagus to adenocarcinoma are also being
investigated. Barrett’s Esophagus is the premalignant lesion for
adenocarcinoma of the esophagus. Due to a severe chronic
gastroesophageal reflux disease, these patient experience a
transformation of the normal squamous epithelium (a) into tissue that
closely resembles the intestine with columnar appearing mucosa and
intestinal metaplasia (b). Once this transformation has taken place, the
individual is at higher risk for adenocarcinoma of the esophagus. [20]_
Moreover, the 5-year survival rate for this cancer is only between
10-15%. [21]_ The American Cancer Society estimates that approximately
529,000 new cases of adenocarcinoma of the esophagus were diagnosed in
2007 while more than 442,000 people died worldwide from the
disease. [22]_ Yet again, one of the predominant factors causing low
survival rates is the late detection of this disease. Patients with
Barrett’s Esophagus identified with an increased risk for adenocarcinoma
typically undergo endoscopic surveillance and biopsy every one or two
years. Again, the confocal microendoscope system’s ability to resolve
cellular detail indicates that it would be a useful tool to improve the
detection of dysplasia and adenocarcinoma in-vivo. In the above figure
(c) illustrates the distinct difference when esophagus tissue has made
the transformation to tumorous tissue.


Modeling System Performance
---------------------------

To better understand the axial and lateral performance of the surgical confocal system,
a Monte Carlo model was developed to study the effects of tissue scattering.
Confocal microscopes use a small aperture to reject out of focus light, allowing
imaging of thin sections within thick samples. Standard confocal microscopes
employ a single pinhole aperture that must be spatially scanned to collect a two
or three dimensional image. To reduce im- age acquisition times, parallelized
confocal systems use an array of pinholes or a slit aperture to simultaneously
collect multiple image points, reducing acquisition times in proportion to the
number of simultaneous detection points used. The drawback of parallelized
systems is cross-talk between the individual apertures. In highly scattering
media, such as tissue, the cross- talk can be large resulting in a significant
reduction in system performance.

A Monte Carlo model was implemented that simulates the confocal system.
The system consists of a laser source and optical elements that uniformly illuminate
the confocal aperture. The aperture can be either a pinhole, slit, Nipkow disk, or
linear array. The aperture and illumination beam are imaged into the tissue via
the objective lens. Fluorescence signal is collected by the objective lens and
imaged back onto the confocal aperture. Light passing through the aperture is
brought back to focus. A dichroic beam splitter directs the emitted fluorescence
signal to a detector. In the case of a pinhole aperture, a single detector is used;
in the case of a parallelized aperture, an array of detectors are used.


.. media:: https://youtu.be/2zoCtMp-z4Y

Monte-Carlo simulation of confocal photon signal positions in tissue. Simulation
results of the three-dimensional distribution of collected photon signal positions
r_s for each aperture configuration (pinhole, slit, Nipkow disk, and linear array)
in simulated tissue. Tissue surface is at z = −62.5 μm (grid plane), focus
is at z = 0.

.. media:: https://youtu.be/lX5hpmnh2_Q

Monte-Carlo simulation of confocal photon error signal positions.
Simulation results shown in terms of error in collected position ε for each
aperture configuration  (pinhole, slit, Nipkow disk, and linear array) in esophagus tissue.



Further information
===================

To find out more about the research I am involved with visit `the
Biomedical Imaging Laboratory <http://bil.arizona.edu>`__.

.. [1]
   L. J. Kleinsmith, Principles of cancer biology, Pearson Benjamin
   Cummings, San Francisco, 2006.

.. [2]
   A. F. Gmitro and D. Aziz, “Confocal microscopy through a fiber-optic
   imaging bundle,” Optics Letters 18, November 1993.

.. [3]
   M. Garcia, A. Jemal, E. M. Ward, M. M. Center, Y. Hao, R. L. Siegel,
   and M. J. Thun, Global Cancer Facts & Figures, American Cancer
   Society, Atlanta, GA, 2007.

.. [4]
   National Cancer Institute, “NCI issues clinical announcement for
   preferred method of treatment for advanced ovarian cancer.”
   http://www.cancer.gov/newscenter/pressreleases/IPchemotherapyrelease,
   January 2006.

.. [5]
   P. A. Wingo, “Cancer statistics,” Cancer journal for clinicians
   45(1), pp. 8–30, 1995.

.. [6]
   K. Kerlikowske, J. S. Brown, and D. G. Grady, “Should women with
   familial ovarian cancer undergo prophylactic oophorectomy,”
   Obstetrics and Gynecology 80(4), pp. 700–707, 1992.

.. [7]
   K. Kerlikowske, J. S. Brown, and D. G. Grady, “Should women with
   familial ovarian cancer undergo prophylactic oophorectomy,”
   Obstetrics and Gynecology 80(4), pp. 700–707, 1992.

.. [8]
   J. F. Stratton, P. Pharoah, S. K. Smith, D. Easton, and B. Ponder, “A
   systematic review and meta-analysis of family history and risk of
   ovarian cancer,” British Journal of Obstetrics and Gynecology 105(5),
   pp. 493–499, 1998.

.. [9]
   I. Jacobs, “Genetic, biochemical, and multimodal approaches to
   screening for ovarian cancer,” Gynecologic Oncology 55(3), pp. 22–27,
   1994.

.. [10]
   Y. Miki, “A strong candidate for the breast and ovarian cancer
   susceptibility gene braca1,” Science 266(5182), pp. 66–71, 1994.

.. [11]
   B. S. Kramer, J. Gohagan, and P. C. Prorok, “NIH consensus 1994:
   screening,” Gynecologic Oncology 55(3), pp. 20–21, 1994.

.. [12]
   A. R. Rouse and A. F. Gmitro, “Multispectral imaging with a confocal
   microendoscope,” Optics Letters 25(23), 2000.

.. [13]
   H. Makhlouf, A. A. Tanbakuchi, A. R. Rouse, and A. F. Gmitro, “Design
   of a multi-spectral channel for in-vivo confocal microscopy,”
   Endoscopic Microscopy II 6432(1), p. 643206, SPIE, 2007.

.. [14]
   A. R. Rouse, A. Kano, J. A. Udovich, S. M. Kroto, and A. F. Gmitro,
   “Design and demonstration of a miniature catheter for a confocal
   microendoscope,” Applied Optics 43, pp. 5763–5771, November 2004.

.. [15]
   A. R. Rouse and A. F. Gmitro, “Multispectral imaging with a confocal
   microendoscope,” Optics Letters 25(23), 2000.

.. [16]
   A. R. Rouse, A. Kano, J. A. Udovich, S. M. Kroto, and A. F. Gmitro,
   “Design and demonstration of a miniature catheter for a confocal
   microendoscope,” Applied Optics 43, pp. 5763–5771, November 2004.

.. [17]
   A. A. Tanbakuchi, A. R. Rouse, J. A. Udovich, and A. F. Gmitro,
   “Surgical imaging catheter for confocal microendoscopy with advanced
   contrast delivery and focus systems,” Endoscopic Microscopy 6082(1),
   p. 608202, SPIE, 2006.

.. [18]
   J. A. Udovich, A. R. Rouse, A. Tanbakuchi, M. A. Brewer, R.
   Sampliner, and A. F. Gmitro, “Confocal micro-endoscope for use in a
   clinical setting,” Endoscopic Microscopy II 6432(1), p. 64320H, SPIE,
   2007.

.. [19]
   S. Srivastava, J. J. Rodriguez, A. R. Rouse, M. A. Brewer, and A. F.
   Gmitro, “Computer-aided identification of ovarian cancer in confocal
   microendoscope images.” in press, Journal of Biomedical Optics.

.. [20]
   P. Sharma and R. E. Sampliner, Barrett’s esophagus and esophageal
   adenocarcinoma, Blackwell Science, Malden, Mass., 2001.

.. [21]
   M. Garcia, A. Jemal, E. M. Ward, M. M. Center, Y. Hao, R. L. Siegel,
   and M. J. Thun, Global Cancer Facts & Figures, American Cancer
   Society, Atlanta, GA, 2007.

.. [22]
   M. Garcia, A. Jemal, E. M. Ward, M. M. Center, Y. Hao, R. L. Siegel,
   and M. J. Thun, Global Cancer Facts & Figures, American Cancer
   Society, Atlanta, GA, 2007.

