---
about_this_resource_text: <p><strong>Instructor:</strong> Dennis Freeman</p> <p><strong>Description:</strong>
  The concept of the Fourier series can be applied to aperiodic functions by treating
  it as a periodic function with period T = infinity. This new transform has some
  key similarities and differences with the Laplace transform, its properties, and
  domains.</p>
course_id: 6-003-signals-and-systems-fall-2011
embedded_media:
- id: Video-YouTube-Stream
  media_location: iWZNTM139xQ
  parent_uid: 5fbda7f6030629109274f1988f447d39
  title: Video-YouTube-Stream
  type: Video
  uid: 9083b56f94578e1ee162648bf2aa4fb7
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/iWZNTM139xQ/default.jpg
  parent_uid: 5fbda7f6030629109274f1988f447d39
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 7e12060aebc45350616c8098bba5cd7a
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/lecture-16-fourier-transform/id602305810?i=132455952
  parent_uid: 5fbda7f6030629109274f1988f447d39
  title: Video-iTunes U-MP4
  type: Video
  uid: f66cdb4609ab8cd41506ffeaaef4b0f0
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.003F11/MIT6_003F11_lec16_300k.mp4
  parent_uid: 5fbda7f6030629109274f1988f447d39
  title: Video-Internet Archive-MP4
  type: Video
  uid: 2a22502de21c286f14457c34b199374e
- id: 3Play-3PlayYouTubeid-MP4
  media_location: iWZNTM139xQ
  parent_uid: 5fbda7f6030629109274f1988f447d39
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 6f91b310a99d429b4c34a06a081dab22
- id: iWZNTM139xQ.srt
  parent_uid: 5fbda7f6030629109274f1988f447d39
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-16-fourier-transform/iWZNTM139xQ.srt
  title: 3play caption file
  type: null
  uid: e1066d9f562b1f64b89700fb4bf4c7bb
- id: iWZNTM139xQ.pdf
  parent_uid: 5fbda7f6030629109274f1988f447d39
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-16-fourier-transform/iWZNTM139xQ.pdf
  title: 3play pdf file
  type: null
  uid: 4880224b3b459c3b3579e19055d58b7d
- id: Caption-3Play YouTube id-SRT
  parent_uid: 5fbda7f6030629109274f1988f447d39
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 265c7eabc6296b79409b2d8ad2e0f86c
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 5fbda7f6030629109274f1988f447d39
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 7a37a59eee8cee5c54bf2e5a12e52de0
inline_embed_id: 3894640lecture16:fouriertransform90378832
layout: video
order_index: null
parent_uid: 47b07fedf3a30be25f155f62399cdb59
related_resources_text: ''
short_url: lecture-16-fourier-transform
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-16-fourier-transform
template_type: Tabbed
title: 'Lecture 16: Fourier Transform'
transcript: <p><span m='90'>The</span> <span m='180'>following</span> <span m='630'>content</span>
  <span m='1200'>is</span> <span m='1320'>provided</span> <span m='1770'>under</span>
  <span m='2009'>a</span> <span m='2070'>Creative</span> <span m='2490'>Commons</span>
  <span m='2910'>license.</span> <span m='4030'>Your</span> <span m='4200'>support</span>
  <span m='4680'>will</span> <span m='4860'>help</span> <span m='5100'>MIT</span>
  <span m='5550'>OpenCourseWare</span> <span m='6330'>continue</span> <span m='6850'>to</span>
  <span m='6960'>offer</span> <span m='7380'>high</span> <span m='7590'>quality</span>
  <span m='8100'>educational</span> <span m='8730'>resources</span> <span m='9330'>for</span>
  <span m='9510'>free.</span> <span m='10720'>To</span> <span m='10740'>make</span>
  <span m='10920'>a</span> <span m='10980'>donation</span> <span m='11730'>or</span>
  <span m='11940'>view</span> <span m='12390'>additional</span> <span m='12810'>materials</span>
  <span m='13320'>from</span> <span m='13500'>hundreds</span> <span m='13920'>of</span>
  <span m='14040'>MIT</span> <span m='14460'>courses,</span> <span m='15550'>visit</span>
  <span m='15780'>MIT</span> <span m='16200'>OpenCourseWare</span> <span m='17280'>at</span>
  <span m='17430'>ocw.mit.edu.</span> </p><p><span m='21060'>DENNIS FREEMAN:</span>
  <span m='21225'>So</span> <span m='21390'>for</span> <span m='21510'>the</span>
  <span m='21570'>last</span> <span m='21780'>couple</span> <span m='21930'>of</span>
  <span m='21990'>times,</span> <span m='22320'>we've</span> <span m='22500'>been</span>
  <span m='22680'>looking</span> <span m='23100'>at</span> <span m='23370'>Fourier</span>
  <span m='23880'>series</span> <span m='25740'>as</span> <span m='25860'>a</span>
  <span m='25920'>way</span> <span m='26130'>of</span> <span m='26250'>looking</span>
  <span m='26580'>at</span> <span m='26700'>signals</span> <span m='27210'>as</span>
  <span m='27300'>a</span> <span m='27330'>way</span> <span m='27540'>of</span> <span
  m='27990'>being</span> <span m='28500'>composed</span> <span m='29040'>out</span>
  <span m='29190'>of</span> <span m='29250'>sinusoids,</span> <span m='29910'>much</span>
  <span m='30120'>the</span> <span m='30240'>way</span> <span m='30360'>we</span>
  <span m='30510'>had</span> <span m='30630'>previously</span> <span m='31140'>looked</span>
  <span m='31380'>at</span> <span m='31530'>frequency</span> <span m='32159'>responses</span>
  <span m='33990'>as</span> <span m='34110'>a</span> <span m='34140'>way</span> <span
  m='34290'>of</span> <span m='34350'>thinking</span> <span m='34560'>about</span>
  <span m='34740'>systems</span> <span m='36990'>characterized</span> <span m='37530'>by</span>
  <span m='37650'>sinusoids.</span> <span m='38970'>And</span> <span m='39150'>for</span>
  <span m='39300'>the</span> <span m='39390'>past</span> <span m='39630'>two</span>
  <span m='39810'>sessions,</span> <span m='40200'>we've</span> <span m='40380'>looked</span>
  <span m='40590'>at</span> <span m='40680'>Fourier</span> <span m='41130'>series</span>
  <span m='42600'>not</span> <span m='42900'>because</span> <span m='43260'>they</span>
  <span m='43350'>were</span> <span m='43470'>terribly</span> <span m='43800'>useful,</span>
  <span m='44220'>but</span> <span m='44330'>because</span> <span m='44670'>they</span>
  <span m='44760'>were</span> <span m='44880'>terribly</span> <span m='45240'>simple.</span>
  <span m='47170'>Today,</span> <span m='47330'>I</span> <span m='47460'>want</span>
  <span m='47610'>to</span> <span m='47670'>do</span> <span m='47910'>the</span> <span
  m='48060'>much</span> <span m='48330'>more</span> <span m='48570'>difficult</span>
  <span m='49290'>task,</span> <span m='49770'>but</span> <span m='49950'>much</span>
  <span m='50190'>more</span> <span m='50400'>interesting</span> <span m='51060'>task</span>
  <span m='51420'>of</span> <span m='51510'>thinking</span> <span m='51810'>about</span>
  <span m='52080'>the</span> <span m='52170'>general</span> <span m='52620'>case</span>
  <span m='53430'>for</span> <span m='53820'>thinking</span> <span m='54180'>about</span>
  <span m='55230'>a</span> <span m='56130'>sinusoidal</span> <span m='56700'>decomposition</span>
  <span m='57330'>of</span> <span m='57420'>an</span> <span m='57540'>arbitrary</span>
  <span m='58050'>signal,</span> <span m='58380'>one</span> <span m='58560'>that</span>
  <span m='58680'>is</span> <span m='58800'>not</span> <span m='58980'>necessarily</span>
  <span m='59670'>periodic.</span> </p><p><span m='60870'>So</span> <span m='61170'>I</span>
  <span m='61290'>should</span> <span m='61470'>say</span> <span m='61740'>upfront,</span>
  <span m='62580'>what</span> <span m='62790'>I'm</span> <span m='62910'>going</span>
  <span m='63180'>to</span> <span m='63300'>talk</span> <span m='63600'>about</span>
  <span m='64709'>is</span> <span m='64920'>motivational.</span> <span m='65790'>It's</span>
  <span m='66000'>not</span> <span m='66240'>a</span> <span m='66270'>proof.</span>
  <span m='66990'>Proving</span> <span m='68030'>Fourier</span> <span m='68490'>series</span>
  <span m='68880'>convergence</span> <span m='69450'>is</span> <span m='69570'>actually</span>
  <span m='70350'>very</span> <span m='70890'>complicated.</span> <span m='71650'>It's</span>
  <span m='71670'>something</span> <span m='72000'>that</span> <span m='72090'>mathematicians</span>
  <span m='72750'>worked</span> <span m='72960'>on</span> <span m='73080'>for</span>
  <span m='73200'>about</span> <span m='73320'>100</span> <span m='73590'>years.</span>
  <span m='74950'>So</span> <span m='76050'>I</span> <span m='76200'>am</span> <span
  m='76350'>not</span> <span m='76530'>going</span> <span m='76770'>to</span> <span
  m='76890'>try</span> <span m='77100'>to</span> <span m='77190'>prove</span> <span
  m='77460'>things</span> <span m='77730'>in</span> <span m='77820'>any</span> <span
  m='78000'>rigorous</span> <span m='78420'>fashion,</span> <span m='78840'>but</span>
  <span m='78960'>I</span> <span m='79020'>am</span> <span m='79200'>going</span>
  <span m='79470'>to</span> <span m='79560'>try</span> <span m='79740'>to</span> <span
  m='79830'>motivate</span> <span m='80250'>things</span> <span m='82080'>so</span>
  <span m='82290'>that</span> <span m='82410'>you</span> <span m='82560'>should</span>
  <span m='82770'>at</span> <span m='82860'>least</span> <span m='83130'>expect</span>
  <span m='83700'>that</span> <span m='83850'>such a</span> <span m='84110'>thing</span>
  <span m='84360'>should</span> <span m='84600'>exist.</span> </p><p><span m='86400'>So</span>
  <span m='87000'>the</span> <span m='87240'>idea,</span> <span m='88020'>the</span>
  <span m='88120'>motivation</span> <span m='88680'>is</span> <span m='88770'>going</span>
  <span m='89010'>to</span> <span m='89130'>be</span> <span m='89580'>how</span> <span
  m='89730'>can</span> <span m='89880'>I</span> <span m='89970'>think</span> <span
  m='90180'>about</span> <span m='91000'>an</span> <span m='91290'>aperiodic</span>
  <span m='92100'>signal</span> <span m='93810'>within</span> <span m='94140'>a</span>
  <span m='94200'>periodic</span> <span m='94740'>framework</span> <span m='95250'>because</span>
  <span m='95520'>I</span> <span m='95610'>already</span> <span m='95910'>have</span>
  <span m='96030'>worked</span> <span m='96210'>out</span> <span m='96360'>all</span>
  <span m='96690'>the</span> <span m='97740'>details.</span> <span m='98400'>The</span>
  <span m='98500'>details</span> <span m='98880'>for</span> <span m='99000'>Fourier</span>
  <span m='99330'>series</span> <span m='99720'>are</span> <span m='99810'>relatively</span>
  <span m='100290'>simple,</span> <span m='101650'>well,</span> <span m='102090'>at
  least</span> <span m='102270'>compared</span> <span m='102600'>to a</span> <span
  m='102810'>Fourier</span> <span m='103110'>transform,</span> <span m='103600'>which</span>
  <span m='103650'>is</span> <span m='103740'>harder.</span> <span m='104700'>Fourier</span>
  <span m='104950'>series</span> <span m='105270'>themselves</span> <span m='105630'>are</span>
  <span m='105720'>not</span> <span m='105960'>that</span> <span m='106260'>easy.</span>
  </p><p><span m='108370'>But</span> <span m='108480'>if</span> <span m='108600'>I</span>
  <span m='108720'>believe</span> <span m='109170'>the</span> <span m='109290'>Fourier</span>
  <span m='109510'>series</span> <span m='110040'>idea,</span> <span m='110820'>is</span>
  <span m='111030'>there</span> <span m='111150'>a</span> <span m='111180'>way</span>
  <span m='111360'>to</span> <span m='111480'>leverage</span> <span m='111900'>that</span>
  <span m='112380'>to</span> <span m='112500'>think</span> <span m='112710'>about</span>
  <span m='112950'>aperiodic</span> <span m='113610'>signals?</span> <span m='114300'>And</span>
  <span m='114420'>the</span> <span m='114540'>idea</span> <span m='114890'>is</span>
  <span m='114990'>going</span> <span m='115230'>to</span> <span m='115320'>be</span>
  <span m='115560'>let's</span> <span m='115770'>take</span> <span m='115950'>an</span>
  <span m='116100'>aperiodic</span> <span m='116790'>signal.</span> <span m='117840'>I've</span>
  <span m='117990'>tried</span> <span m='118230'>to</span> <span m='118320'>choose</span>
  <span m='118550'>something</span> <span m='118860'>terribly</span> <span m='119280'>simple.</span>
  <span m='120130'>It's</span> <span m='120240'>the</span> <span m='120360'>simplest</span>
  <span m='120720'>thing</span> <span m='120930'>that</span> <span m='121050'>I</span>
  <span m='121110'>could</span> <span m='121260'>think</span> <span m='121470'>of</span>
  <span m='121640'>it</span> <span m='121770'>isn't</span> <span m='122250'>zero.</span>
  </p><p><span m='124230'>So</span> <span m='124440'>it's</span> <span m='124590'>one</span>
  <span m='124860'>for</span> <span m='125010'>a</span> <span m='125070'>while</span>
  <span m='125430'>and</span> <span m='125510'>zero</span> <span m='125820'>most</span>
  <span m='126060'>of</span> <span m='126120'>the</span> <span m='126210'>time.</span>
  <span m='128600'>But</span> <span m='128789'>I</span> <span m='128910'>could</span>
  <span m='129120'>make</span> <span m='129389'>that</span> <span m='129600'>signal,</span>
  <span m='129930'>which</span> <span m='130110'>is</span> <span m='130199'>clearly</span>
  <span m='130560'>not</span> <span m='130770'>periodic,</span> <span m='131430'>by</span>
  <span m='131730'>thinking</span> <span m='132240'>about</span> <span m='132780'>periodically</span>
  <span m='133950'>extending</span> <span m='134580'>it.</span> <span m='135330'>Copy</span>
  <span m='135800'>it.</span> <span m='136170'>Add it</span> <span m='136500'>to</span>
  <span m='136680'>itself</span> <span m='137280'>many</span> <span m='137580'>times,</span>
  <span m='139210'>each</span> <span m='139350'>time</span> <span m='139800'>shifted</span>
  <span m='140220'>by a</span> <span m='140440'>capital</span> <span m='140930'>T.</span>
  </p><p><span m='141720'>This</span> <span m='141930'>signal</span> <span m='142320'>is</span>
  <span m='142440'>obviously</span> <span m='143670'>periodic.</span> <span m='144770'>This</span>
  <span m='145080'>transformation</span> <span m='145830'>is</span> <span m='145980'>obviously</span>
  <span m='146430'>going</span> <span m='146640'>to</span> <span m='146730'>take</span>
  <span m='146970'>any</span> <span m='147240'>signal</span> <span m='147570'>regardless</span>
  <span m='148710'>and</span> <span m='148830'>turn</span> <span m='149040'>it</span>
  <span m='149130'>into</span> <span m='149400'>something</span> <span m='149790'>that</span>
  <span m='149940'>is</span> <span m='150210'>periodic</span> <span m='150780'>in</span>
  <span m='150900'>cap T.</span> <span m='152550'>So</span> <span m='152760'>if</span>
  <span m='152970'>I</span> <span m='153120'>did</span> <span m='153420'>that,</span>
  <span m='154150'>then</span> <span m='154290'>I</span> <span m='154380'>could</span>
  <span m='154530'>kind of</span> <span m='155010'>trivially</span> <span m='155490'>say,</span>
  <span m='156270'>well,</span> <span m='156600'>the</span> <span m='156900'>aperiodic</span>
  <span m='157440'>thing</span> <span m='157650'>is</span> <span m='157770'>just</span>
  <span m='157950'>the</span> <span m='158100'>limit</span> <span m='158400'>when</span>
  <span m='158670'>capital</span> <span m='158970'>T</span> <span m='159270'>goes</span>
  <span m='159510'>to</span> <span m='159630'>infinity</span> <span m='160440'>of</span>
  <span m='160560'>the</span> <span m='160650'>periodic</span> <span m='161160'>thing.</span>
  <span m='161790'>OK,</span> <span m='162060'>that's</span> <span m='162330'>pretty</span>
  <span m='162540'>trivial.</span> <span m='163560'>OK,</span> <span m='163800'>that's</span>
  <span m='164190'>obviously</span> <span m='165030'>true.</span> </p><p><span m='166080'>The</span>
  <span m='166200'>trick</span> <span m='166620'>is,</span> <span m='167460'>what</span>
  <span m='167670'>if</span> <span m='167790'>I</span> <span m='167880'>took</span>
  <span m='168060'>a</span> <span m='168120'>Fourier</span> <span m='168570'>series</span>
  <span m='169200'>in</span> <span m='169380'>the</span> <span m='169470'>middle?</span>
  <span m='171000'>What</span> <span m='171210'>if</span> <span m='171360'>I</span>
  <span m='171480'>periodically</span> <span m='172290'>extended</span> <span m='172860'>this</span>
  <span m='173130'>thing</span> <span m='173760'>to</span> <span m='173850'>get</span>
  <span m='174000'>something</span> <span m='174450'>that</span> <span m='174600'>is</span>
  <span m='174720'>periodic,</span> <span m='175770'>take a</span> <span m='176040'>Fourier</span>
  <span m='176430'>series</span> <span m='177000'>of</span> <span m='177120'>this</span>
  <span m='177420'>thing,</span> <span m='178740'>and</span> <span m='178890'>then</span>
  <span m='179040'>take</span> <span m='179220'>the</span> <span m='179340'>limit</span>
  <span m='179580'>of</span> <span m='179640'>the</span> <span m='179840'>series?</span>
  <span m='182670'>So</span> <span m='182850'>that's</span> <span m='183180'>the</span>
  <span m='183300'>thing</span> <span m='183510'>I'm</span> <span m='183600'>going</span>
  <span m='183810'>to</span> <span m='183900'>do</span> <span m='184050'>over</span>
  <span m='184230'>the</span> <span m='184320'>next</span> <span m='184560'>three</span>
  <span m='184770'>slides.</span> </p><p><span m='186270'>So</span> <span m='186420'>think</span>
  <span m='186630'>about</span> <span m='186870'>a</span> <span m='186930'>general,</span>
  <span m='187770'>aperiodic</span> <span m='188610'>signal,</span> <span m='189960'>periodically</span>
  <span m='190770'>extended</span> <span m='191310'>so</span> <span m='191520'>it's</span>
  <span m='191670'>now</span> <span m='191910'>periodic</span> <span m='192480'>in</span>
  <span m='192600'>cap T,</span> <span m='194280'>take</span> <span m='194560'>a</span>
  <span m='194610'>Fourier</span> <span m='195190'>series--</span> <span m='199230'>just</span>
  <span m='199450'>to</span> <span m='199530'>motivate</span> <span m='199920'>the</span>
  <span m='200010'>kind</span> <span m='200250'>of</span> <span m='200340'>math</span>
  <span m='200610'>that</span> <span m='200730'>happens,</span> <span m='201090'>I've</span>
  <span m='201300'>written</span> <span m='201660'>out</span> <span m='201990'>the</span>
  <span m='202110'>math</span> <span m='202890'>for</span> <span m='203070'>this</span>
  <span m='203220'>particularly</span> <span m='203880'>simple</span> <span m='204240'>signal</span>
  <span m='205020'>that</span> <span m='205140'>is</span> <span m='205260'>one</span>
  <span m='205500'>for</span> <span m='205620'>a</span> <span m='205670'>while</span>
  <span m='205890'>and</span> <span m='205980'>zero</span> <span m='206230'>most</span>
  <span m='206430'>of</span> <span m='206490'>the</span> <span m='206580'>time.</span>
  <span m='208416'>The</span> <span m='208900'>Fourier</span> <span m='209460'>series</span>
  <span m='209910'>coefficient,</span> <span m='210370'>a</span> <span m='210600'>sub</span>
  <span m='210710'>k</span> <span m='211190'>is</span> <span m='211320'>obviously</span>
  <span m='211830'>1</span> <span m='212090'>over</span> <span m='212280'>t,</span>
  <span m='212670'>the</span> <span m='212760'>period,</span> <span m='214230'>integral</span>
  <span m='214650'>over</span> <span m='214830'>the</span> <span m='214920'>period--</span>
  <span m='215310'>I</span> <span m='215400'>took</span> <span m='215580'>the</span>
  <span m='215700'>symmetric</span> <span m='216180'>period</span> <span m='216480'>because</span>
  <span m='216780'>it's</span> <span m='216900'>the</span> <span m='216990'>easiest</span>
  <span m='217440'>one--</span> <span m='219590'>signal</span> <span m='220010'>of</span>
  <span m='220160'>interest,</span> <span m='220820'>basis</span> <span m='221240'>function</span>
  <span m='221960'>integrated</span> <span m='222410'>over</span> <span m='222620'>time.</span>
  <span m='225730'>And</span> <span m='225910'>that's</span> <span m='226090'>pretty</span>
  <span m='226420'>trivially--</span> <span m='228140'>those</span> <span m='228460'>integrals</span>
  <span m='228820'>are</span> <span m='228940'>easy.</span> <span m='229310'>That</span>
  <span m='229420'>was</span> <span m='229540'>chosen</span> <span m='229840'>that</span>
  <span m='229960'>way.</span> </p><p><span m='230750'>And</span> <span m='230800'>so</span>
  <span m='230950'>I</span> <span m='231010'>get</span> <span m='231160'>an</span>
  <span m='231250'>answer</span> <span m='231550'>that</span> <span m='231670'>looks</span>
  <span m='231850'>like</span> <span m='232060'>that.</span> <span m='233050'>The</span>
  <span m='233140'>thing</span> <span m='233290'>I</span> <span m='233380'>want</span>
  <span m='233530'>you</span> <span m='233620'>to</span> <span m='233740'>see</span>
  <span m='233890'>about</span> <span m='234100'>the</span> <span m='234280'>answer</span>
  <span m='237170'>is</span> <span m='237380'>that</span> <span m='237470'>I</span>
  <span m='237560'>can</span> <span m='237710'>think</span> <span m='237890'>about</span>
  <span m='238100'>it</span> <span m='238200'>as</span> <span m='238310'>a</span>
  <span m='238370'>function</span> <span m='238730'>of</span> <span m='238850'>omega</span>
  <span m='239480'>or</span> <span m='239750'>k.</span> <span m='241760'>And</span>
  <span m='241880'>that's</span> <span m='242090'>what</span> <span m='242240'>I've</span>
  <span m='242390'>plotted</span> <span m='242840'>here.</span> </p><p><span m='244610'>In</span>
  <span m='244790'>particular,</span> <span m='245700'>if</span> <span m='245780'>I</span>
  <span m='245870'>multiply</span> <span m='246590'>a</span> <span m='246950'>sub</span>
  <span m='247295'>k</span> <span m='247640'>by</span> <span m='247820'>capital</span>
  <span m='248225'>T,</span> <span m='248630'>so</span> <span m='248800'>as</span>
  <span m='248900'>to</span> <span m='248990'>kill</span> <span m='249230'>this</span>
  <span m='249440'>1</span> <span m='249760'>over t</span> <span m='250125'>thing,</span>
  <span m='251720'>and</span> <span m='251840'>if</span> <span m='251990'>I</span>
  <span m='252080'>plot</span> <span m='252890'>t</span> <span m='253160'>times</span>
  <span m='253520'>a</span> <span m='253730'>sub</span> <span m='253890'>k,</span>
  <span m='256480'>I</span> <span m='256630'>get</span> <span m='257100'>a</span>
  <span m='257230'>relationship</span> <span m='258459'>2</span> <span m='258640'>sine</span>
  <span m='258910'>omega</span> <span m='259750'>S</span> <span m='260140'>over</span>
  <span m='261579'>omega,</span> <span m='265660'>omega</span> <span m='265910'>being</span>
  <span m='266190'>k</span> <span m='266430'>2pi</span> <span m='266780'>over</span>
  <span m='266920'>t.</span> <span m='267790'>But</span> <span m='268420'>for</span>
  <span m='268600'>the</span> <span m='268690'>Fourier</span> <span m='268990'>series,</span>
  <span m='269350'>that</span> <span m='269500'>only</span> <span m='269740'>exists</span>
  <span m='270280'>for</span> <span m='270490'>k</span> <span m='271030'>and</span>
  <span m='271210'>integer.</span> <span m='272830'>So</span> <span m='272980'>that's</span>
  <span m='273160'>what's</span> <span m='273310'>represented</span> <span m='273760'>by</span>
  <span m='273850'>the</span> <span m='273940'>blue</span> <span m='274120'>bars.</span>
  </p><p><span m='276800'>But</span> <span m='276820'>what</span> <span m='277000'>I</span>
  <span m='277060'>want</span> <span m='277240'>you</span> <span m='277300'>to</span>
  <span m='277390'>see</span> <span m='277570'>is</span> <span m='277690'>just</span>
  <span m='277870'>from</span> <span m='278020'>the</span> <span m='278110'>math,</span>
  <span m='279670'>the</span> <span m='280000'>envelope</span> <span m='282310'>doesn't</span>
  <span m='282650'>depend</span> <span m='282760'>on</span> <span m='282870'>t.</span>
  <span m='285250'>OK,</span> <span m='285820'>that's</span> <span m='286060'>the</span>
  <span m='286180'>trick.</span> <span m='286880'>So</span> <span m='286900'>the</span>
  <span m='287050'>idea</span> <span m='287410'>is</span> <span m='287650'>I'm</span>
  <span m='287860'>plotting</span> <span m='288400'>the</span> <span m='288500'>Fourier</span>
  <span m='288850'>coefficients</span> <span m='289420'>a</span> <span m='289630'>sub</span>
  <span m='289750'>k</span> <span m='290920'>as</span> <span m='291040'>a</span> <span
  m='291100'>function</span> <span m='291430'>of</span> <span m='291550'>k.</span>
  <span m='292570'>So</span> <span m='292790'>k</span> <span m='293230'>equals</span>
  <span m='293490'>0,</span> <span m='293750'>1,</span> <span m='294410'>2,</span>
  <span m='294800'>3,</span> <span m='295190'>4,</span> <span m='295490'>5,</span>
  <span m='295750'>et cetera.</span> <span m='298990'>But</span> <span m='299290'>I</span>
  <span m='299380'>notice</span> <span m='299710'>that</span> <span m='299800'>the</span>
  <span m='299980'>envelope</span> <span m='300610'>can</span> <span m='300790'>be</span>
  <span m='300940'>written</span> <span m='301600'>strictly</span> <span m='302050'>as</span>
  <span m='302140'>a</span> <span m='302200'>function</span> <span m='302740'>of</span>
  <span m='303140'>omega</span> <span m='304010'>where</span> <span m='304290'>there</span>
  <span m='304450'>is</span> <span m='304520'>a</span> <span m='304570'>simple</span>
  <span m='304810'>relationship</span> <span m='305320'>between</span> <span m='305560'>omega</span>
  <span m='305890'>and</span> <span m='305990'>k.</span> <span m='306880'>But</span>
  <span m='307090'>omega</span> <span m='307480'>is</span> <span m='307690'>defined</span>
  <span m='308080'>across</span> <span m='308410'>the</span> <span m='308530'>entire</span>
  <span m='308890'>axis,</span> <span m='309760'>and</span> <span m='309910'>it's</span>
  <span m='310180'>represented</span> <span m='310720'>by</span> <span m='310900'>this</span>
  <span m='311080'>light</span> <span m='311350'>black</span> <span m='311590'>curve.</span>
  </p><p><span m='312640'>That's</span> <span m='312850'>more</span> <span m='313070'>apparent</span>
  <span m='313720'>if</span> <span m='313870'>I</span> <span m='314800'>think</span>
  <span m='315010'>about</span> <span m='315940'>increasing</span> <span m='316600'>capital</span>
  <span m='316990'>T.</span> <span m='317960'>What</span> <span m='318130'>if</span>
  <span m='318220'>I</span> <span m='318280'>were</span> <span m='318400'>to</span>
  <span m='318490'>keep</span> <span m='318640'>the</span> <span m='318760'>base</span>
  <span m='319120'>waveform</span> <span m='319570'>the</span> <span m='319690'>same,</span>
  <span m='321300'>but</span> <span m='321430'>change</span> <span m='321970'>capital</span>
  <span m='322355'>T?</span> <span m='323000'>Say</span> <span m='323260'>I</span>
  <span m='323380'>double</span> <span m='323710'>capital</span> <span m='324100'>T.</span>
  <span m='326440'>The</span> <span m='326560'>thing</span> <span m='326830'>that</span>
  <span m='326980'>happens</span> <span m='327850'>is</span> <span m='328120'>the</span>
  <span m='328270'>envelope</span> <span m='328780'>stays</span> <span m='329230'>the</span>
  <span m='329350'>same,</span> <span m='330340'>but</span> <span m='330520'>the</span>
  <span m='330610'>spacing</span> <span m='331930'>of</span> <span m='332050'>the</span>
  <span m='332170'>k's</span> <span m='333850'>becomes</span> <span m='334960'>condensed.</span>
  <span m='335740'>There's</span> <span m='335950'>more</span> <span m='336660'>k's</span>
  <span m='337180'>in</span> <span m='337300'>a</span> <span m='337360'>given</span>
  <span m='337810'>number</span> <span m='338230'>of</span> <span m='338410'>hertzes,</span>
  <span m='340140'>in</span> <span m='340300'>frequency,</span> <span m='341260'>than</span>
  <span m='341410'>there</span> <span m='341530'>was</span> <span m='341740'>before.</span>
  </p><p><span m='342100'>And</span> <span m='342190'>if</span> <span m='342280'>I</span>
  <span m='342340'>double</span> <span m='342550'>it</span> <span m='342640'>again,</span>
  <span m='343450'>it</span> <span m='343570'>doubles</span> <span m='343870'>again.</span>
  <span m='344890'>The</span> <span m='345130'>envelope</span> <span m='345700'>didn't</span>
  <span m='345970'>change.</span> <span m='346480'>The</span> <span m='347200'>k's</span>
  <span m='347800'>did.</span> </p><p><span m='351020'>The</span> <span m='351140'>interesting</span>
  <span m='351560'>thing</span> <span m='351710'>about</span> <span m='351890'>that</span>
  <span m='352010'>construction</span> <span m='352580'>is</span> <span m='352700'>that</span>
  <span m='352820'>it</span> <span m='353000'>has</span> <span m='353150'>separated</span>
  <span m='353780'>out</span> <span m='354050'>the</span> <span m='354140'>part</span>
  <span m='354470'>that</span> <span m='354560'>depends</span> <span m='354950'>on</span>
  <span m='355110'>capital</span> <span m='355510'>T</span> <span m='356330'>from</span>
  <span m='356540'>the</span> <span m='356630'>part</span> <span m='356840'>that</span>
  <span m='356960'>doesn't</span> <span m='357350'>depend</span> <span m='357680'>on</span>
  <span m='357920'>capital</span> <span m='358205'>T.</span> <span m='358490'>Capital</span>
  <span m='359180'>T</span> <span m='359400'>was</span> <span m='359570'>this</span>
  <span m='359810'>arbitrary</span> <span m='360500'>thing</span> <span m='362120'>that</span>
  <span m='362300'>I</span> <span m='362390'>used</span> <span m='362690'>to</span>
  <span m='362780'>take</span> <span m='363050'>an</span> <span m='363500'>aperiodic</span>
  <span m='364010'>signal</span> <span m='364280'>and</span> <span m='364370'>turn</span>
  <span m='364550'>it</span> <span m='364640'>into</span> <span m='364850'>a</span>
  <span m='364940'>periodic</span> <span m='365510'>signal.</span> <span m='366260'>And</span>
  <span m='367610'>it</span> <span m='367760'>has</span> <span m='368030'>an</span>
  <span m='368150'>effect</span> <span m='368600'>on</span> <span m='368750'>the</span>
  <span m='368900'>answer</span> <span m='369900'>that</span> <span m='370010'>can</span>
  <span m='370190'>be</span> <span m='370340'>separated</span> <span m='372020'>from</span>
  <span m='372290'>the</span> <span m='372530'>other</span> <span m='372860'>part</span>
  <span m='373160'>of</span> <span m='373250'>the</span> <span m='373400'>answer.</span>
  </p><p><span m='374420'>Some</span> <span m='374750'>part</span> <span m='375140'>of</span>
  <span m='375200'>the</span> <span m='375350'>answer</span> <span m='375650'>depends</span>
  <span m='376040'>on</span> <span m='376130'>the</span> <span m='376280'>base</span>
  <span m='376570'>waveform.</span> <span m='379070'>Some</span> <span m='379430'>other</span>
  <span m='379700'>part</span> <span m='379940'>of</span> <span m='380000'>the</span>
  <span m='380120'>answer</span> <span m='380390'>depends</span> <span m='380870'>on</span>
  <span m='380990'>capital</span> <span m='381420'>T.</span> <span m='383360'>Well,</span>
  <span m='383510'>that's</span> <span m='383750'>nice</span> <span m='384080'>because</span>
  <span m='384380'>now</span> <span m='384620'>if</span> <span m='384710'>I</span>
  <span m='384830'>think</span> <span m='385040'>about</span> <span m='385220'>taking</span>
  <span m='385580'>the</span> <span m='385700'>limit</span> <span m='386000'>as</span>
  <span m='386090'>capital</span> <span m='386360'>T</span> <span m='386630'>goes</span>
  <span m='386870'>to</span> <span m='386990'>infinity,</span> <span m='387950'>I</span>
  <span m='388040'>have</span> <span m='388190'>a</span> <span m='388260'>prayer</span>
  <span m='388440'>of</span> <span m='388550'>interpreting</span> <span m='389060'>things</span>
  <span m='389330'>because</span> <span m='389630'>part</span> <span m='390050'>of</span>
  <span m='390140'>my</span> <span m='390320'>answer</span> <span m='391310'>is</span>
  <span m='391490'>changing</span> <span m='391880'>with</span> <span m='392060'>t</span>
  <span m='392200'>and</span> <span m='392320'>part</span> <span m='392540'>of</span>
  <span m='392630'>it</span> <span m='392720'>isn't.</span> <span m='393470'>So</span>
  <span m='393590'>all</span> <span m='393770'>I</span> <span m='393860'>need</span>
  <span m='394040'>to</span> <span m='394130'>do</span> <span m='394280'>now</span>
  <span m='394490'>is</span> <span m='394610'>focus</span> <span m='394940'>on</span>
  <span m='395060'>the</span> <span m='395150'>part</span> <span m='395810'>that</span>
  <span m='395960'>is</span> <span m='396110'>changing</span> <span m='396590'>with</span>
  <span m='396740'>t</span> <span m='397010'>and</span> <span m='397220'>separate</span>
  <span m='397680'>it</span> <span m='397730'>from</span> <span m='397880'>the</span>
  <span m='397970'>part</span> <span m='398210'>that's</span> <span m='398420'>not</span>
  <span m='398750'>changing</span> <span m='399230'>with</span> <span m='399380'>t.</span>
  </p><p><span m='401160'>So</span> <span m='401180'>now,</span> <span m='401330'>I</span>
  <span m='401420'>can</span> <span m='401570'>think</span> <span m='401750'>about</span>
  <span m='401960'>taking--</span> <span m='403100'>so</span> <span m='403220'>I</span>
  <span m='403310'>just</span> <span m='403490'>plug</span> <span m='403780'>in</span>
  <span m='406370'>this</span> <span m='406640'>expression</span> <span m='407390'>here</span>
  <span m='409190'>for</span> <span m='409490'>this</span> <span m='409730'>integral.</span>
  <span m='411950'>And</span> <span m='412160'>what</span> <span m='412340'>I</span>
  <span m='412430'>get</span> <span m='412700'>then</span> <span m='413300'>is</span>
  <span m='413420'>something</span> <span m='413810'>that</span> <span m='413960'>looks</span>
  <span m='414290'>a</span> <span m='414380'>lot</span> <span m='414860'>like</span>
  <span m='416590'>a</span> <span m='416690'>Fourier</span> <span m='417200'>series</span>
  <span m='419810'>or</span> <span m='419960'>even</span> <span m='420180'>a</span>
  <span m='420400'>Laplace</span> <span m='420980'>transform.</span> <span m='421820'>I</span>
  <span m='421910'>get</span> <span m='422150'>an</span> <span m='422300'>integral--</span>
  <span m='423020'>ignore</span> <span m='423285'>the</span> <span m='423550'>limit</span>
  <span m='423830'>part</span> <span m='424100'>for</span> <span m='424250'>a</span>
  <span m='424310'>moment.</span> <span m='425570'>I</span> <span m='425690'>get</span>
  <span m='425870'>an</span> <span m='425960'>integral</span> <span m='426500'>of</span>
  <span m='426590'>something</span> <span m='427700'>times</span> <span m='428030'>some</span>
  <span m='428300'>sort</span> <span m='428600'>of</span> <span m='428720'>a</span>
  <span m='428810'>weighting</span> <span m='429230'>function.</span> </p><p><span
  m='431000'>And</span> <span m='431150'>I</span> <span m='431240'>get</span> <span
  m='431450'>something</span> <span m='431870'>over</span> <span m='432080'>here</span>
  <span m='432950'>where</span> <span m='433100'>the</span> <span m='433280'>integral</span>
  <span m='433760'>was</span> <span m='433970'>over</span> <span m='434270'>time,</span>
  <span m='436900'>but</span> <span m='437080'>the</span> <span m='437200'>function</span>
  <span m='437620'>over</span> <span m='437800'>here</span> <span m='437980'>doesn't</span>
  <span m='438220'>have</span> <span m='438370'>time</span> <span m='438730'>in</span>
  <span m='438880'>it.</span> <span m='439690'>It</span> <span m='439930'>only</span>
  <span m='440090'>has</span> <span m='440230'>omega</span> <span m='440720'>in it.</span>
  <span m='442090'>That's</span> <span m='442360'>the</span> <span m='442450'>sense</span>
  <span m='442720'>in</span> <span m='442810'>which</span> <span m='442990'>it</span>
  <span m='443140'>sort</span> <span m='443380'>of</span> <span m='443500'>looks</span>
  <span m='443830'>like</span> <span m='444790'>the</span> <span m='445300'>analysis</span>
  <span m='446110'>formula</span> <span m='448960'>for</span> <span m='449260'>either</span>
  <span m='449620'>Fourier</span> <span m='450100'>series</span> <span m='450610'>or</span>
  <span m='450730'>Laplace</span> <span m='451150'>transforms.</span> </p><p><span
  m='452110'>It</span> <span m='452200'>looks</span> <span m='452350'>like</span>
  <span m='452500'>the</span> <span m='452590'>analysis</span> <span m='453070'>formula</span>
  <span m='453400'>because</span> <span m='454270'>I'm</span> <span m='454470'>calculating</span>
  <span m='455470'>a</span> <span m='455610'>T</span> <span m='456070'>ak,</span>
  <span m='458190'>the</span> <span m='458280'>components</span> <span m='459000'>of</span>
  <span m='459120'>the</span> <span m='459210'>series,</span> <span m='460020'>or</span>
  <span m='460710'>this</span> <span m='460950'>new</span> <span m='461190'>thing,</span>
  <span m='461840'>E</span> <span m='462040'>of</span> <span m='462180'>omega,</span>
  <span m='462680'>that</span> <span m='462810'>doesn't</span> <span m='463140'>depend--</span>
  <span m='463530'>neither</span> <span m='463860'>of</span> <span m='463920'>those</span>
  <span m='464130'>depended</span> <span m='464550'>on</span> <span m='464700'>t.</span>
  <span m='467970'>OK,</span> <span m='468180'>so</span> <span m='468330'>the</span>
  <span m='468480'>idea</span> <span m='468900'>is</span> <span m='469200'>that</span>
  <span m='469770'>when</span> <span m='469950'>I</span> <span m='470070'>do</span>
  <span m='470340'>this</span> <span m='470580'>kind</span> <span m='470940'>of</span>
  <span m='471060'>a</span> <span m='471120'>limiting</span> <span m='471540'>operation</span>
  <span m='472200'>on</span> <span m='472380'>the</span> <span m='472470'>periodic</span>
  <span m='473040'>extension,</span> <span m='474000'>I</span> <span m='474090'>get</span>
  <span m='474300'>something</span> <span m='474750'>that</span> <span m='474900'>ends</span>
  <span m='475230'>up</span> <span m='475410'>looking</span> <span m='475890'>like</span>
  <span m='478110'>a</span> <span m='478620'>transform</span> <span m='479070'>relationship.</span>
  </p><p><span m='481590'>And</span> <span m='481740'>if</span> <span m='481830'>I</span>
  <span m='481920'>think</span> <span m='482160'>about</span> <span m='482430'>going</span>
  <span m='482760'>the</span> <span m='482910'>other</span> <span m='483180'>way,</span>
  <span m='483990'>doing</span> <span m='484320'>a</span> <span m='484410'>synthesis</span>
  <span m='484920'>operation,</span> <span m='486180'>I</span> <span m='486270'>can</span>
  <span m='486450'>think</span> <span m='486660'>about</span> <span m='486930'>how</span>
  <span m='487140'>I</span> <span m='487260'>would</span> <span m='487410'>construct</span>
  <span m='488010'>x</span> <span m='488310'>of</span> <span m='488460'>t</span> <span
  m='489300'>out</span> <span m='489510'>of</span> <span m='489580'>the</span> <span
  m='489680'>Fourier</span> <span m='490190'>coefficients</span> <span m='491220'>But</span>
  <span m='491370'>now,</span> <span m='491550'>there's</span> <span m='491750'>a</span>
  <span m='491790'>simple</span> <span m='492060'>relationship</span> <span m='492660'>between</span>
  <span m='493020'>the</span> <span m='493140'>Fourier</span> <span m='494100'>series</span>
  <span m='494980'>coefficients,</span> <span m='495630'>a</span> <span m='495970'>sub</span>
  <span m='496200'>k,</span> <span m='496920'>and</span> <span m='497040'>this</span>
  <span m='497220'>thing</span> <span m='497520'>Ew,</span> <span m='500370'>which</span>
  <span m='500580'>I've</span> <span m='500700'>represented</span> <span m='501300'>here.</span>
  </p><p><span m='504230'>And</span> <span m='504400'>I</span> <span m='504490'>don't</span>
  <span m='504700'>like</span> <span m='504940'>the</span> <span m='505060'>t.</span>
  <span m='506320'>So</span> <span m='506570'>I'll</span> <span m='506740'>do</span>
  <span m='506950'>a</span> <span m='507010'>substitution</span> <span m='508600'>from</span>
  <span m='508810'>here.</span> <span m='509620'>t</span> <span m='509800'>can</span>
  <span m='509950'>be</span> <span m='510070'>written</span> <span m='510460'>as</span>
  <span m='511540'>omega</span> <span m='511810'>0</span> <span m='512080'>over</span>
  <span m='512260'>2pi.</span> <span m='512740'>1</span> <span m='512950'>over</span>
  <span m='513100'>t</span> <span m='513309'>can</span> <span m='513429'>be</span>
  <span m='513520'>written</span> <span m='513760'>as</span> <span m='513880'>omega</span>
  <span m='514130'>0</span> <span m='514320'>ever</span> <span m='514510'>2pi.</span>
  </p><p><span m='517880'>And</span> <span m='518039'>now,</span> <span m='518250'>I've</span>
  <span m='518370'>got</span> <span m='518580'>everything</span> <span m='518940'>I</span>
  <span m='519030'>need</span> <span m='519330'>to</span> <span m='519480'>think</span>
  <span m='519780'>about</span> <span m='520380'>how</span> <span m='520650'>that</span>
  <span m='521159'>sum</span> <span m='522809'>approaches</span> <span m='523409'>an</span>
  <span m='523710'>integral</span> <span m='524760'>in</span> <span m='524910'>a</span>
  <span m='524970'>Riemann</span> <span m='525280'>sum</span> <span m='525540'>kind</span>
  <span m='525780'>of</span> <span m='525900'>sense.</span> <span m='527070'>Think</span>
  <span m='527250'>about</span> <span m='527490'>as</span> <span m='527640'>I</span>
  <span m='527760'>add</span> <span m='527970'>more</span> <span m='528390'>and</span>
  <span m='528600'>more--</span> <span m='529770'>as</span> <span m='529980'>I</span>
  <span m='530040'>make</span> <span m='530220'>capital</span> <span m='530640'>T</span>
  <span m='530820'>get</span> <span m='530970'>bigger</span> <span m='531240'>and</span>
  <span m='531330'>bigger,</span> <span m='532920'>omega</span> <span m='533340'>0</span>
  <span m='533610'>gets</span> <span m='533760'>smaller</span> <span m='534240'>and</span>
  <span m='534330'>smaller.</span> <span m='537840'>As</span> <span m='538020'>I</span>
  <span m='538110'>make</span> <span m='538500'>the</span> <span m='539850'>capital</span>
  <span m='540120'>T</span> <span m='540390'>bigger</span> <span m='540660'>and</span>
  <span m='540780'>bigger,</span> <span m='541020'>the</span> <span m='541140'>spacing</span>
  <span m='541650'>gets</span> <span m='541860'>smaller</span> <span m='542340'>and</span>
  <span m='542430'>smaller.</span> <span m='543720'>Increasingly,</span> <span m='544560'>I</span>
  <span m='544710'>can</span> <span m='544890'>think</span> <span m='545160'>about</span>
  <span m='545490'>this</span> <span m='545730'>function</span> <span m='546990'>E</span>
  <span m='547240'>of</span> <span m='547380'>omega</span> <span m='548640'>as</span>
  <span m='548850'>being</span> <span m='549180'>smooth</span> <span m='550170'>and</span>
  <span m='550320'>increasingly</span> <span m='550920'>constant</span> <span m='552630'>over</span>
  <span m='552900'>the</span> <span m='553020'>small</span> <span m='553410'>interval</span>
  <span m='553890'>between</span> <span m='554430'>the</span> <span m='554550'>bars.</span>
  <span m='556360'>So</span> <span m='556380'>I</span> <span m='556440'>can</span>
  <span m='556590'>think</span> <span m='556770'>about</span> <span m='557070'>the</span>
  <span m='557190'>sum</span> <span m='558450'>as</span> <span m='558930'>a</span>
  <span m='558990'>Riemann</span> <span m='559320'>sum</span> <span m='560380'>passed</span>
  <span m='560820'>to</span> <span m='561660'>the</span> <span m='561810'>integral</span>
  <span m='562140'>as</span> <span m='562260'>the</span> <span m='562370'>limit.</span>
  </p><p><span m='563970'>So</span> <span m='564120'>when</span> <span m='564270'>I</span>
  <span m='564360'>do</span> <span m='564600'>that,</span> <span m='564930'>omega</span>
  <span m='565320'>0</span> <span m='566310'>is</span> <span m='566550'>the</span>
  <span m='566700'>spacing</span> <span m='568590'>between</span> <span m='569070'>the</span>
  <span m='569190'>two</span> <span m='569340'>adjacents.</span> <span m='569930'>It's</span>
  <span m='570090'>the</span> <span m='570180'>region</span> <span m='570480'>over</span>
  <span m='570660'>which</span> <span m='570840'>I</span> <span m='570900'>want</span>
  <span m='571080'>to</span> <span m='571140'>think</span> <span m='571260'>about</span>
  <span m='571470'>that</span> <span m='572280'>integrand</span> <span m='572940'>being</span>
  <span m='573300'>constant.</span> <span m='575730'>And</span> <span m='576390'>so</span>
  <span m='576630'>that</span> <span m='577380'>in</span> <span m='577530'>the</span>
  <span m='577620'>limit,</span> <span m='578080'>this</span> <span m='578130'>omega</span>
  <span m='578460'>0</span> <span m='579120'>passes</span> <span m='579540'>to</span>
  <span m='579710'>d omega.</span> <span m='581730'>And</span> <span m='581850'>I'm</span>
  <span m='582000'>left</span> <span m='582240'>with</span> <span m='582390'>something</span>
  <span m='582780'>that</span> <span m='582930'>looks</span> <span m='583230'>like</span>
  <span m='584100'>a</span> <span m='584190'>synthesis</span> <span m='584760'>equation.</span>
  </p><p><span m='587190'>So</span> <span m='587840'>if</span> <span m='587990'>I</span>
  <span m='588080'>just</span> <span m='588320'>write</span> <span m='588560'>those</span>
  <span m='588800'>equations</span> <span m='589340'>here</span> <span m='590960'>and</span>
  <span m='591140'>think</span> <span m='591410'>about</span> <span m='591680'>this</span>
  <span m='591860'>Ew</span> <span m='592520'>thing</span> <span m='592850'>being</span>
  <span m='593150'>some</span> <span m='593360'>kind</span> <span m='593630'>of</span>
  <span m='593690'>a</span> <span m='593750'>transform,</span> <span m='594470'>which</span>
  <span m='594650'>I'll</span> <span m='594800'>mysteriously</span> <span m='595550'>write</span>
  <span m='595860'>as</span> <span m='596210'>x</span> <span m='596490'>of</span>
  <span m='596640'>j</span> <span m='596870'>omega,</span> <span m='600000'>then</span>
  <span m='600560'>the</span> <span m='600710'>result</span> <span m='602660'>for</span>
  <span m='602870'>the</span> <span m='602990'>aperiodic</span> <span m='603740'>case</span>
  <span m='604430'>has</span> <span m='604670'>a</span> <span m='604730'>structure</span>
  <span m='605330'>that</span> <span m='605450'>looks</span> <span m='605660'>very</span>
  <span m='605900'>much</span> <span m='606110'>like</span> <span m='606260'>the</span>
  <span m='606380'>Fourier</span> <span m='606770'>series,</span> <span m='607250'>or</span>
  <span m='607370'>for</span> <span m='607520'>that</span> <span m='607700'>matter</span>
  <span m='608390'>like</span> <span m='608600'>the</span> <span m='608690'>Laplace</span>
  <span m='609070'>transform.</span> <span m='610140'>What</span> <span m='610280'>it</span>
  <span m='610370'>says</span> <span m='610670'>is</span> <span m='610880'>that</span>
  <span m='611690'>I</span> <span m='611840'>can</span> <span m='612290'>synthesize</span>
  <span m='613820'>an</span> <span m='613970'>arbitrary</span> <span m='614510'>x</span>
  <span m='614720'>of</span> <span m='614870'>t</span> <span m='616460'>by</span>
  <span m='616910'>adding</span> <span m='617300'>together</span> <span m='618650'>a</span>
  <span m='618740'>whole</span> <span m='618980'>bunch</span> <span m='619280'>of</span>
  <span m='619370'>components</span> <span m='619970'>that</span> <span m='620120'>already</span>
  <span m='620350'>depend</span> <span m='620720'>on</span> <span m='620960'>omega</span>
  <span m='623830'>weighted</span> <span m='624340'>by</span> <span m='624640'>some</span>
  <span m='624850'>weighting</span> <span m='625270'>function.</span> </p><p><span
  m='625750'>s</span> <span m='625930'>this</span> <span m='626140'>looks</span> <span
  m='626410'>like</span> <span m='626830'>a</span> <span m='626920'>synthesis</span>
  <span m='627430'>equation</span> <span m='627910'>very</span> <span m='628120'>much</span>
  <span m='628330'>like</span> <span m='628510'>the</span> <span m='628590'>synthesis</span>
  <span m='629100'>equation</span> <span m='629560'>for</span> <span m='630070'>Fourier</span>
  <span m='630430'>series</span> <span m='631160'>or</span> <span m='631290'>for</span>
  <span m='631480'>Laplace</span> <span m='631870'>transforms.</span> <span m='633700'>And</span>
  <span m='633940'>I</span> <span m='634030'>get</span> <span m='634210'>an</span>
  <span m='634330'>analysis</span> <span m='634930'>equation</span> <span m='635360'>that</span>
  <span m='635430'>similarly</span> <span m='636900'>has</span> <span m='637150'>the</span>
  <span m='637240'>same</span> <span m='637450'>form</span> <span m='637690'>again.</span>
  <span m='638410'>I</span> <span m='638530'>take</span> <span m='638800'>the</span>
  <span m='639070'>x</span> <span m='639340'>of</span> <span m='639450'>t</span> <span
  m='640780'>and</span> <span m='640960'>figure</span> <span m='641350'>out</span>
  <span m='641710'>the</span> <span m='641830'>component</span> <span m='642430'>that</span>
  <span m='642610'>should</span> <span m='642850'>be</span> <span m='643030'>at</span>
  <span m='643180'>omega</span> <span m='644530'>by</span> <span m='645610'>multiplying</span>
  <span m='646450'>by</span> <span m='647280'>a</span> <span m='647350'>complex</span>
  <span m='647800'>exponential</span> <span m='648580'>and</span> <span m='648820'>integrating.</span>
  </p><p><span m='650980'>OK,</span> <span m='651220'>I</span> <span m='651280'>have</span>
  <span m='651430'>to</span> <span m='651640'>emphasize</span> <span m='652480'>this</span>
  <span m='652660'>is</span> <span m='652840'>not</span> <span m='653200'>a</span>
  <span m='653260'>proof.</span> <span m='654270'>All</span> <span m='654460'>I</span>
  <span m='654550'>wanted</span> <span m='654820'>to</span> <span m='654910'>do</span>
  <span m='655450'>was</span> <span m='655600'>kind</span> <span m='655810'>of</span>
  <span m='655930'>motivate</span> <span m='657040'>the</span> <span m='657160'>way</span>
  <span m='657430'>you</span> <span m='657580'>can</span> <span m='657760'>think</span>
  <span m='658090'>about</span> <span m='658810'>an</span> <span m='658960'>aperiodic</span>
  <span m='659680'>signal</span> <span m='660100'>as</span> <span m='660280'>being</span>
  <span m='660550'>periodic</span> <span m='661090'>in</span> <span m='661270'>some</span>
  <span m='661540'>time</span> <span m='661840'>interval</span> <span m='662620'>and</span>
  <span m='662770'>passed</span> <span m='663100'>to</span> <span m='663250'>the</span>
  <span m='663340'>limit.</span> <span m='664240'>And</span> <span m='664390'>if</span>
  <span m='664540'>you</span> <span m='664660'>do</span> <span m='664870'>that,</span>
  <span m='665410'>you</span> <span m='665500'>can</span> <span m='665620'>sort</span>
  <span m='665830'>of</span> <span m='665890'>see</span> <span m='666130'>where</span>
  <span m='666280'>the</span> <span m='666400'>equations</span> <span m='666880'>are</span>
  <span m='666940'>coming</span> <span m='667240'>from.</span> <span m='669900'>OK?</span>
  </p><p><span m='671540'>So</span> <span m='672560'>the</span> <span m='672740'>idea</span>
  <span m='673100'>then--</span> <span m='673860'>whoops.</span> <span m='678000'>So</span>
  <span m='678140'>the</span> <span m='678230'>idea</span> <span m='678620'>then</span>
  <span m='678980'>is</span> <span m='679280'>that</span> <span m='679880'>we</span>
  <span m='680030'>will</span> <span m='680180'>use</span> <span m='680570'>these</span>
  <span m='680870'>relationships</span> <span m='681980'>to</span> <span m='682130'>define</span>
  <span m='682580'>an</span> <span m='682700'>analysis</span> <span m='683240'>and</span>
  <span m='683330'>synthesis</span> <span m='684410'>of</span> <span m='684860'>aperiodic</span>
  <span m='686090'>signals.</span> <span m='686810'>And</span> <span m='686930'>we'll</span>
  <span m='687080'>refer</span> <span m='687350'>to</span> <span m='687440'>that</span>
  <span m='687650'>as</span> <span m='687740'>a</span> <span m='687800'>Fourier</span>
  <span m='688130'>transform.</span> </p><p><span m='689960'>The</span> <span m='690420'>Fourier</span>
  <span m='691190'>transform</span> <span m='692080'>will</span> <span m='692270'>let</span>
  <span m='692450'>us</span> <span m='692540'>have</span> <span m='693410'>insights</span>
  <span m='695880'>that</span> <span m='696060'>are</span> <span m='696210'>completely</span>
  <span m='696690'>analogous</span> <span m='697170'>to</span> <span m='697290'>the</span>
  <span m='697380'>Fourier</span> <span m='697770'>series,</span> <span m='698430'>except</span>
  <span m='698730'>they</span> <span m='698820'>now</span> <span m='699030'>apply</span>
  <span m='699330'>for</span> <span m='699480'>aperiodic</span> <span m='700080'>signals.</span>
  <span m='700450'>So</span> <span m='700560'>in</span> <span m='700680'>particular,</span>
  <span m='701460'>we'll</span> <span m='701550'>be</span> <span m='701700'>able</span>
  <span m='701850'>to</span> <span m='701910'>think</span> <span m='702120'>about</span>
  <span m='702660'>a</span> <span m='702720'>signal</span> <span m='703110'>being</span>
  <span m='703320'>composed</span> <span m='703770'>of</span> <span m='703860'>a</span>
  <span m='703920'>bunch</span> <span m='704160'>of</span> <span m='704230'>sinusoidal</span>
  <span m='704760'>components.</span> <span m='705240'>And</span> <span m='705330'>we'll</span>
  <span m='705420'>be</span> <span m='705540'>able</span> <span m='705720'>to</span>
  <span m='705810'>think</span> <span m='705960'>about</span> <span m='706650'>systems</span>
  <span m='708630'>as</span> <span m='708900'>filters.</span> </p><p><span m='712020'>OK,</span>
  <span m='712290'>so</span> <span m='712860'>I've</span> <span m='713070'>already</span>
  <span m='713340'>alluded</span> <span m='713610'>to</span> <span m='713700'>the</span>
  <span m='713790'>fact</span> <span m='714390'>that</span> <span m='714690'>the</span>
  <span m='714810'>Fourier</span> <span m='715740'>transform</span> <span m='716970'>relations</span>
  <span m='718350'>look</span> <span m='718770'>very</span> <span m='719280'>similar</span>
  <span m='720180'>in</span> <span m='720420'>form</span> <span m='721050'>to</span>
  <span m='721180'>the</span> <span m='721290'>Laplace</span> <span m='721800'>transform</span>
  <span m='722880'>relations.</span> <span m='723840'>And</span> <span m='723960'>so</span>
  <span m='724050'>I've</span> <span m='724290'>illustrated</span> <span m='726060'>the</span>
  <span m='726180'>analysis</span> <span m='726960'>equations</span> <span m='727560'>here</span>
  <span m='727800'>just</span> <span m='728010'>to</span> <span m='728190'>emphasize</span>
  <span m='728910'>the</span> <span m='729060'>similarity.</span> <span m='732130'>The</span>
  <span m='732210'>Laplace</span> <span m='732630'>transform,</span> <span m='733200'>you'll</span>
  <span m='733350'>remember,</span> <span m='733890'>had</span> <span m='734220'>the--</span>
  <span m='734750'>we</span> <span m='735240'>integrated</span> <span m='736500'>some</span>
  <span m='736740'>signal</span> <span m='737340'>that</span> <span m='737490'>was</span>
  <span m='737610'>a</span> <span m='737670'>function</span> <span m='737940'>of</span>
  <span m='738060'>time</span> <span m='739090'>times</span> <span m='739220'>a</span>
  <span m='739260'>complex</span> <span m='739650'>exponential</span> <span m='740280'>integrated</span>
  <span m='740670'>over</span> <span m='740820'>time</span> <span m='741540'>to</span>
  <span m='741690'>get</span> <span m='744310'>a</span> <span m='744420'>Laplace</span>
  <span m='744810'>transform</span> <span m='745740'>that</span> <span m='745890'>was</span>
  <span m='746010'>a</span> <span m='746070'>function</span> <span m='746500'>of</span>
  <span m='748410'>s,</span> <span m='749490'>not</span> <span m='749970'>time.</span>
  </p><p><span m='751860'>It</span> <span m='751950'>was</span> <span m='752070'>a</span>
  <span m='752100'>way</span> <span m='752370'>of</span> <span m='752670'>having</span>
  <span m='753930'>an</span> <span m='754110'>alternative</span> <span m='754830'>representation</span>
  <span m='755670'>for</span> <span m='755850'>the</span> <span m='755970'>signal.</span>
  <span m='756930'>There</span> <span m='757080'>was</span> <span m='757410'>no</span>
  <span m='757590'>new</span> <span m='757770'>information.</span> <span m='758370'>The</span>
  <span m='758460'>same</span> <span m='758640'>information</span> <span m='759120'>was</span>
  <span m='759270'>contained</span> <span m='759630'>in</span> <span m='759750'>s</span>
  <span m='759930'>of</span> <span m='760020'>x</span> <span m='760260'>as</span>
  <span m='760470'>was</span> <span m='760650'>contained</span> <span m='760980'>in</span>
  <span m='761100'>x</span> <span m='761250'>of</span> <span m='761340'>t.</span>
  <span m='761910'>Except</span> <span m='762210'>now,</span> <span m='763080'>where</span>
  <span m='763360'>it</span> <span m='763410'>was</span> <span m='763830'>organized</span>
  <span m='764310'>by</span> <span m='764490'>time,</span> <span m='764880'>now,</span>
  <span m='765090'>it's</span> <span m='765210'>organized</span> <span m='765630'>by</span>
  <span m='765810'>s.</span> </p><p><span m='767960'>We</span> <span m='768110'>get</span>
  <span m='768230'>the</span> <span m='768350'>same</span> <span m='768620'>sort</span>
  <span m='768830'>of</span> <span m='768890'>thing</span> <span m='769100'>with</span>
  <span m='769250'>a</span> <span m='769310'>Fourier</span> <span m='769670'>transform.</span>
  <span m='770250'>And</span> <span m='770270'>in</span> <span m='770360'>fact,</span>
  <span m='771450'>this</span> <span m='771680'>gives</span> <span m='772010'>away</span>
  <span m='773090'>the</span> <span m='773210'>mysterious</span> <span m='774050'>reason</span>
  <span m='774470'>for</span> <span m='774650'>calling</span> <span m='775070'>it</span>
  <span m='775760'>x</span> <span m='776000'>of</span> <span m='776150'>j</span> <span
  m='776380'>omega</span> <span m='776790'>in</span> <span m='776990'>the</span> <span
  m='777080'>previous</span> <span m='777550'>slide.</span> <span m='779070'>You</span>
  <span m='779090'>can</span> <span m='779240'>see</span> <span m='779540'>that</span>
  <span m='779780'>a</span> <span m='779870'>different</span> <span m='780230'>way</span>
  <span m='780410'>to</span> <span m='780500'>think</span> <span m='780650'>about</span>
  <span m='780830'>the</span> <span m='780920'>Fourier</span> <span m='781340'>transform</span>
  <span m='782360'>is</span> <span m='782600'>that</span> <span m='782840'>it's</span>
  <span m='783020'>simply--</span> <span m='784490'>a</span> <span m='784550'>trivial</span>
  <span m='784880'>way</span> <span m='785030'>to</span> <span m='785120'>think</span>
  <span m='785270'>about</span> <span m='785480'>it,</span> <span m='785980'>it's</span>
  <span m='786470'>the</span> <span m='786590'>value--</span> <span m='787100'>the</span>
  <span m='787190'>Fourier</span> <span m='787430'>transform</span> <span m='788420'>is</span>
  <span m='788630'>the</span> <span m='788780'>value</span> <span m='789440'>of</span>
  <span m='789570'>the</span> <span m='789650'>Laplace</span> <span m='790100'>transform</span>
  <span m='792010'>evaluated</span> <span m='792760'>s</span> <span m='792970'>equals</span>
  <span m='793210'>j</span> <span m='793450'>omega.</span> <span m='794690'>All</span>
  <span m='794930'>you</span> <span m='795140'>do</span> <span m='796130'>is</span>
  <span m='796280'>you</span> <span m='796370'>take</span> <span m='796640'>this</span>
  <span m='796880'>expression</span> <span m='799460'>for</span> <span m='799760'>the</span>
  <span m='799880'>Laplace</span> <span m='800270'>transform,</span> <span m='800780'>and</span>
  <span m='800840'>every</span> <span m='800990'>place</span> <span m='801170'>there</span>
  <span m='801260'>was</span> <span m='801410'>an</span> <span m='801530'>s,</span>
  <span m='802550'>make</span> <span m='802820'>s</span> <span m='803090'>equal</span>
  <span m='803330'>j omega.</span> <span m='804230'>And</span> <span m='804410'>you</span>
  <span m='804590'>get</span> <span m='804980'>this</span> <span m='805160'>equation.</span>
  </p><p><span m='807300'>So</span> <span m='807350'>that's</span> <span m='807620'>the</span>
  <span m='807710'>reason</span> <span m='808010'>we</span> <span m='808070'>like</span>
  <span m='808280'>the</span> <span m='808370'>notation.</span> <span m='809670'>The</span>
  <span m='809770'>Fourier</span> <span m='809990'>transform</span> <span m='810680'>is</span>
  <span m='811160'>x</span> <span m='811520'>of</span> <span m='811730'>j</span> <span
  m='812090'>omega.</span> <span m='813350'>There</span> <span m='813530'>are</span>
  <span m='813620'>confusions</span> <span m='814280'>that</span> <span m='814400'>arise</span>
  <span m='814760'>by</span> <span m='814880'>that.</span> <span m='815120'>And</span>
  <span m='815210'>I'll</span> <span m='815300'>talk</span> <span m='815500'>about</span>
  <span m='815720'>those</span> <span m='815960'>in</span> <span m='816050'>a</span>
  <span m='816110'>moment.</span> <span m='816930'>But</span> <span m='816950'>for</span>
  <span m='817100'>the</span> <span m='817220'>time</span> <span m='817520'>being,</span>
  <span m='817850'>the</span> <span m='817940'>important</span> <span m='818330'>thing</span>
  <span m='818630'>is</span> <span m='818990'>that</span> <span m='819230'>the</span>
  <span m='819350'>Fourier</span> <span m='819740'>transform</span> <span m='821510'>can</span>
  <span m='821750'>be</span> <span m='821930'>viewed</span> <span m='822890'>as</span>
  <span m='823040'>a</span> <span m='823100'>special</span> <span m='823550'>case</span>
  <span m='825800'>looking</span> <span m='826130'>at</span> <span m='826220'>the</span>
  <span m='826310'>j omega</span> <span m='826820'>axis</span> <span m='827480'>of</span>
  <span m='827630'>the</span> <span m='827930'>Laplace</span> <span m='828470'>transform.</span>
  <span m='831040'>OK?</span> </p><p><span m='833140'>So</span> <span m='833950'>that</span>
  <span m='834220'>view</span> <span m='835240'>points</span> <span m='835570'>out</span>
  <span m='835960'>two</span> <span m='836260'>things.</span> <span m='837250'>There's</span>
  <span m='837430'>a</span> <span m='837490'>lot</span> <span m='837670'>of</span>
  <span m='837730'>similarities,</span> <span m='838450'>and</span> <span m='838630'>there</span>
  <span m='838810'>are</span> <span m='838930'>some</span> <span m='839170'>differences.</span>
  <span m='839900'>First,</span> <span m='840100'>the</span> <span m='840220'>similarities--</span>
  <span m='841870'>because</span> <span m='842500'>you</span> <span m='842620'>can</span>
  <span m='842770'>regard</span> <span m='843190'>the</span> <span m='843310'>Fourier</span>
  <span m='843670'>transform</span> <span m='844840'>as</span> <span m='845050'>kind</span>
  <span m='845530'>of</span> <span m='845650'>a</span> <span m='845710'>special</span>
  <span m='846130'>case--</span> <span m='846490'>that's</span> <span m='846640'>not</span>
  <span m='846790'>really</span> <span m='847090'>true.</span> <span m='848060'>And</span>
  <span m='848120'>I</span> <span m='848180'>will</span> <span m='848290'>say</span>
  <span m='848500'>something</span> <span m='848800'>about</span> <span m='848980'>that</span>
  <span m='849160'>by</span> <span m='849310'>the</span> <span m='849430'>end</span>
  <span m='849550'>of</span> <span m='849610'>the</span> <span m='849730'>hour</span>
  <span m='849940'>as</span> <span m='850060'>well.</span> <span m='850820'>But</span>
  <span m='851200'>because</span> <span m='851530'>it's</span> <span m='851620'>kind</span>
  <span m='851830'>of</span> <span m='851920'>a</span> <span m='851950'>special</span>
  <span m='852280'>case</span> <span m='852580'>of</span> <span m='852640'>the</span>
  <span m='852960'>Laplace</span> <span m='853420'>transform,</span> <span m='854620'>the</span>
  <span m='854740'>Fourier</span> <span m='855100'>transform</span> <span m='855580'>inherits</span>
  <span m='858440'>a</span> <span m='858470'>lot</span> <span m='858680'>of</span>
  <span m='858740'>the</span> <span m='858830'>important</span> <span m='859130'>properties</span>
  <span m='859520'>of</span> <span m='859600'>a Laplace</span> <span m='859920'>transform.</span>
  </p><p><span m='861270'>In</span> <span m='861350'>particular,</span> <span m='862080'>the</span>
  <span m='862130'>two</span> <span m='862370'>things</span> <span m='862670'>that</span>
  <span m='862760'>we</span> <span m='862910'>looked</span> <span m='863120'>at</span>
  <span m='863270'>most</span> <span m='864950'>has</span> <span m='865190'>been</span>
  <span m='865710'>linearity.</span> <span m='867750'>Because</span> <span m='868210'>the</span>
  <span m='868310'>Laplace</span> <span m='868790'>transform</span> <span m='869360'>is</span>
  <span m='869540'>linear,</span> <span m='870000'>we</span> <span m='870140'>can</span>
  <span m='870260'>do</span> <span m='870440'>all</span> <span m='870680'>manner</span>
  <span m='871190'>of</span> <span m='871280'>things</span> <span m='871610'>with</span>
  <span m='871820'>it.</span> <span m='874120'>The</span> <span m='874280'>same</span>
  <span m='874640'>as</span> <span m='874790'>we</span> <span m='875000'>use</span>
  <span m='875390'>the</span> <span m='875540'>properties</span> <span m='876200'>of</span>
  <span m='876380'>linear</span> <span m='877250'>systems</span> <span m='878240'>to</span>
  <span m='878420'>simplify</span> <span m='879110'>our</span> <span m='879290'>view</span>
  <span m='879620'>of</span> <span m='879710'>how</span> <span m='879890'>to</span>
  <span m='880010'>think</span> <span m='880190'>about</span> <span m='880460'>a</span>
  <span m='880520'>system,</span> <span m='881480'>we</span> <span m='881630'>could,</span>
  <span m='881910'>for</span> <span m='882020'>example,</span> <span m='882860'>because</span>
  <span m='883220'>systems</span> <span m='883640'>are</span> <span m='883760'>linear,</span>
  <span m='884480'>we</span> <span m='884600'>can</span> <span m='884810'>look</span>
  <span m='885110'>at</span> <span m='885350'>the</span> <span m='885740'>response</span>
  <span m='886250'>of</span> <span m='886340'>a</span> <span m='886400'>system</span>
  <span m='887450'>to</span> <span m='887600'>a</span> <span m='887690'>sum</span>
  <span m='888550'>of</span> <span m='888710'>inputs</span> <span m='889310'>as</span>
  <span m='889580'>the</span> <span m='889730'>sum</span> <span m='889970'>of</span>
  <span m='890030'>the</span> <span m='890120'>responses</span> <span m='890690'>to</span>
  <span m='890810'>the</span> <span m='890960'>individuals.</span> <span m='891710'>That's</span>
  <span m='891890'>a</span> <span m='891950'>very</span> <span m='892190'>important</span>
  <span m='892520'>property</span> <span m='892880'>that</span> <span m='893000'>we</span>
  <span m='893120'>used</span> <span m='893590'>of</span> <span m='893750'>systems</span>
  <span m='894830'>as</span> <span m='894920'>a</span> <span m='894950'>result</span>
  <span m='895280'>of</span> <span m='895340'>linearity.</span> </p><p><span m='896300'>We</span>
  <span m='896420'>did</span> <span m='896540'>the</span> <span m='896660'>same</span>
  <span m='896930'>thing</span> <span m='897170'>with</span> <span m='897440'>Laplace</span>
  <span m='897890'>transforms.</span> <span m='899870'>The</span> <span m='900020'>Laplace</span>
  <span m='900380'>transform</span> <span m='900860'>of a</span> <span m='900980'>sum</span>
  <span m='901310'>is</span> <span m='901640'>the</span> <span m='901700'>sum of</span>
  <span m='901870'>a Laplace</span> <span m='902120'>transforms.</span> <span m='904340'>And</span>
  <span m='904550'>in</span> <span m='904670'>conjunction</span> <span m='905330'>with</span>
  <span m='905480'>the</span> <span m='905570'>differentiation</span> <span m='906350'>roll</span>
  <span m='907760'>by</span> <span m='907970'>which</span> <span m='908180'>we</span>
  <span m='908300'>knew</span> <span m='908450'>that</span> <span m='908600'>the</span>
  <span m='908690'>Laplace</span> <span m='909050'>transform</span> <span m='909530'>of</span>
  <span m='909650'>a</span> <span m='909710'>derivative</span> <span m='910790'>is</span>
  <span m='911060'>s</span> <span m='911300'>times</span> <span m='911660'>the Laplace</span>
  <span m='912110'>transform</span> <span m='912610'>the</span> <span m='912740'>function,</span>
  <span m='914540'>the</span> <span m='914630'>combination</span> <span m='915230'>of</span>
  <span m='915320'>linearity</span> <span m='917090'>and</span> <span m='917280'>the</span>
  <span m='917330'>differentiation</span> <span m='918140'>role</span> <span m='918680'>allowed</span>
  <span m='919040'>us</span> <span m='919160'>to</span> <span m='919310'>apply</span>
  <span m='919730'>Laplace</span> <span m='920120'>transforms</span> <span m='921200'>to</span>
  <span m='921380'>turn</span> <span m='922250'>differential</span> <span m='922850'>equations</span>
  <span m='923360'>into</span> <span m='923540'>algebraic</span> <span m='924260'>equations.</span>
  </p><p><span m='926870'>Precisely</span> <span m='927530'>the</span> <span m='927680'>same</span>
  <span m='927980'>thing</span> <span m='928530'>will</span> <span m='928820'>work</span>
  <span m='929150'>with</span> <span m='929360'>Fourier</span> <span m='929720'>transforms.</span>
  <span m='932580'>For</span> <span m='932880'>reasons</span> <span m='933340'>that</span>
  <span m='933450'>should</span> <span m='933660'>be</span> <span m='933840'>clear,</span>
  <span m='934620'>if</span> <span m='934800'>the</span> <span m='934860'>Laplace</span>
  <span m='935280'>transform</span> <span m='935880'>has</span> <span m='936090'>the</span>
  <span m='936210'>property</span> <span m='936600'>of</span> <span m='936690'>linearity,</span>
  <span m='937330'>so</span> <span m='937440'>does</span> <span m='937680'>the</span>
  <span m='937890'>Fourier.</span> <span m='940530'>And</span> <span m='940740'>if</span>
  <span m='940920'>the</span> <span m='941460'>Laplace</span> <span m='941850'>transform</span>
  <span m='942930'>is</span> <span m='943170'>simply</span> <span m='943560'>related</span>
  <span m='943950'>to</span> <span m='944070'>the</span> <span m='944160'>Fourier</span>
  <span m='944490'>transform,</span> <span m='945120'>then</span> <span m='945300'>there's</span>
  <span m='945480'>a</span> <span m='945540'>simple</span> <span m='945810'>relationship</span>
  <span m='946380'>between</span> <span m='946770'>the</span> <span m='946890'>Fourier</span>
  <span m='947190'>transform</span> <span m='947670'>of</span> <span m='947790'>a</span>
  <span m='947850'>derivative</span> <span m='948690'>and</span> <span m='948850'>the
  Fourier</span> <span m='949340'>transform</span> <span m='949770'>of</span> <span
  m='950910'>the</span> <span m='951120'>underlying</span> <span m='951510'>function.</span>
  <span m='952480'>So</span> <span m='952620'>in</span> <span m='952740'>the</span>
  <span m='952940'>Laplace</span> <span m='953240'>transform,</span> <span m='953490'>you</span>
  <span m='953550'>multiply</span> <span m='953910'>by</span> <span m='954120'>s.</span>
  <span m='955650'>Not</span> <span m='955920'>very</span> <span m='956130'>surprisingly,</span>
  <span m='956790'>in</span> <span m='956850'>the</span> <span m='956940'>Fourier</span>
  <span m='957240'>transform,</span> <span m='957600'>you</span> <span m='957690'>multiply</span>
  <span m='958020'>by</span> <span m='958140'>j</span> <span m='958260'>omega.</span>
  </p><p><span m='960300'>So</span> <span m='960480'>there's</span> <span m='960720'>enormous</span>
  <span m='961740'>similarity.</span> <span m='962850'>And</span> <span m='962970'>in</span>
  <span m='963060'>fact,</span> <span m='963460'>most</span> <span m='963690'>of</span>
  <span m='963810'>what</span> <span m='963990'>you</span> <span m='964110'>know</span>
  <span m='964320'>about</span> <span m='964670'>Laplace,</span> <span m='965670'>you</span>
  <span m='965760'>can</span> <span m='965880'>immediately</span> <span m='966330'>carry</span>
  <span m='966660'>over</span> <span m='966870'>into</span> <span m='967050'>Fourier.</span>
  <span m='969420'>There</span> <span m='969630'>are</span> <span m='969810'>some</span>
  <span m='970020'>differences.</span> <span m='972760'>And</span> <span m='973000'>if</span>
  <span m='973120'>there</span> <span m='973240'>weren't</span> <span m='973420'>differences,</span>
  <span m='973870'>we</span> <span m='973990'>probably</span> <span m='974350'>wouldn't</span>
  <span m='974530'>bother</span> <span m='974770'>with</span> <span m='974860'>talking</span>
  <span m='975190'>about</span> <span m='975340'>both</span> <span m='975580'>of</span>
  <span m='975670'>them.</span> <span m='976090'>Right?</span> </p><p><span m='976420'>There</span>
  <span m='976630'>are</span> <span m='976690'>some</span> <span m='976990'>things</span>
  <span m='977620'>that</span> <span m='977770'>will</span> <span m='977950'>be</span>
  <span m='978130'>easy</span> <span m='978490'>to</span> <span m='978610'>think</span>
  <span m='978790'>about</span> <span m='979030'>with</span> <span m='979180'>Fourier</span>
  <span m='979540'>transforms.</span> <span m='980110'>And</span> <span m='980200'>that's</span>
  <span m='980350'>the</span> <span m='980410'>reason</span> <span m='980680'>we</span>
  <span m='980740'>do</span> <span m='980890'>it.</span> <span m='982190'>There</span>
  <span m='982270'>are</span> <span m='982390'>some</span> <span m='982600'>things</span>
  <span m='982870'>that</span> <span m='982990'>are</span> <span m='983080'>easy</span>
  <span m='983290'>to</span> <span m='983410'>think</span> <span m='983560'>about</span>
  <span m='983710'>with</span> <span m='983890'>Laplace</span> <span m='984160'>transforms.</span>
  <span m='984760'>Otherwise,</span> <span m='985210'>we</span> <span m='985300'>would
  have</span> <span m='985510'>just</span> <span m='985690'>skipped</span> <span m='985960'>straight</span>
  <span m='986260'>to</span> <span m='986390'>Fourier.</span> </p><p><span m='988670'>So</span>
  <span m='988720'>there</span> <span m='988870'>are</span> <span m='988990'>some</span>
  <span m='989200'>things</span> <span m='989530'>that</span> <span m='991140'>Fourier</span>
  <span m='991460'>and</span> <span m='991730'>Laplace</span> <span m='992470'>share.</span>
  <span m='994270'>There</span> <span m='994450'>are</span> <span m='994510'>some</span>
  <span m='994750'>things</span> <span m='994990'>that</span> <span m='995140'>are</span>
  <span m='995230'>different.</span> <span m='995720'>One</span> <span m='995770'>of</span>
  <span m='995830'>the</span> <span m='995920'>biggest</span> <span m='996280'>differences</span>
  <span m='997480'>is</span> <span m='997720'>the</span> <span m='997840'>domain.</span>
  </p><p><span m='1000000'>When</span> <span m='1000180'>we</span> <span m='1000270'>think</span>
  <span m='1000420'>about</span> <span m='1000590'>a</span> <span m='1000950'>Laplace</span>
  <span m='1001050'>transform,</span> <span m='1001410'>we</span> <span m='1001470'>think</span>
  <span m='1001620'>about</span> <span m='1001830'>x</span> <span m='1002020'>of</span>
  <span m='1002150'>s.</span> <span m='1004860'>The</span> <span m='1004980'>domain</span>
  <span m='1005460'>or</span> <span m='1005550'>the</span> <span m='1006060'>Laplace</span>
  <span m='1006160'>transform</span> <span m='1006660'>is</span> <span m='1006780'>the</span>
  <span m='1006900'>domain</span> <span m='1007200'>of</span> <span m='1007290'>s.</span>
  <span m='1009300'>The</span> <span m='1009390'>domain</span> <span m='1009720'>of</span>
  <span m='1009810'>s,</span> <span m='1010200'>s</span> <span m='1010650'>is</span>
  <span m='1010740'>a</span> <span m='1010800'>complex</span> <span m='1011220'>number.</span>
  <span m='1012510'>For</span> <span m='1012660'>that</span> <span m='1012840'>reason,</span>
  <span m='1013740'>when</span> <span m='1013920'>we</span> <span m='1014010'>thought</span>
  <span m='1014190'>out</span> <span m='1014370'>Laplace</span> <span m='1014640'>transforms,</span>
  <span m='1015060'>we</span> <span m='1015150'>always</span> <span m='1015390'>talked</span>
  <span m='1015780'>about</span> <span m='1018330'>what</span> <span m='1018570'>does</span>
  <span m='1018750'>the</span> <span m='1018840'>Laplace</span> <span m='1018930'>transform</span>
  <span m='1019560'>look</span> <span m='1019710'>like</span> <span m='1019980'>in</span>
  <span m='1020070'>the s</span> <span m='1020290'>plane.</span> <span m='1022590'>And</span>
  <span m='1022740'>we</span> <span m='1022860'>thought</span> <span m='1023040'>about</span>
  <span m='1023250'>the</span> <span m='1023310'>real</span> <span m='1023520'>part</span>
  <span m='1023730'>of</span> <span m='1023790'>the</span> <span m='1024280'>s</span>
  <span m='1024770'>and the</span> <span m='1025260'>imaginary</span> <span m='1025740'>part</span>
  <span m='1025920'>of</span> <span m='1026030'>s.</span> </p><p><span m='1028390'>When</span>
  <span m='1028470'>we</span> <span m='1028530'>think</span> <span m='1028680'>about</span>
  <span m='1028829'>Fourier</span> <span m='1029099'>transforms,</span> <span m='1031950'>we're</span>
  <span m='1032069'>thinking</span> <span m='1032430'>about</span> <span m='1033020'>a</span>
  <span m='1033119'>transform</span> <span m='1034140'>with</span> <span m='1034349'>real</span>
  <span m='1034740'>domain.</span> <span m='1036720'>Rather</span> <span m='1037170'>than</span>
  <span m='1037380'>thinking</span> <span m='1037800'>about</span> <span m='1039319'>x</span>
  <span m='1039810'>of</span> <span m='1039960'>s</span> <span m='1040380'>as</span>
  <span m='1040619'>a</span> <span m='1040680'>complex</span> <span m='1041130'>number,</span>
  <span m='1041369'>we're</span> <span m='1041460'>going</span> <span m='1041579'>to</span>
  <span m='1041640'>think</span> <span m='1041849'>of</span> <span m='1041970'>x</span>
  <span m='1042150'>of</span> <span m='1042270'>j</span> <span m='1042585'>omega,</span>
  <span m='1042900'>omega</span> <span m='1043770'>a</span> <span m='1043920'>real</span>
  <span m='1044339'>number</span> <span m='1048210'>that's</span> <span m='1048390'>a</span>
  <span m='1048420'>little</span> <span m='1048630'>confusing,</span> <span m='1049790'>right?</span>
  <span m='1050550'>Just</span> <span m='1050730'>sort</span> <span m='1050910'>of</span>
  <span m='1051210'>to</span> <span m='1051360'>confuse</span> <span m='1051780'>you,</span>
  <span m='1052770'>we</span> <span m='1053990'>rewrite</span> <span m='1054900'>the</span>
  <span m='1055110'>one</span> <span m='1055620'>that</span> <span m='1055890'>is</span>
  <span m='1056670'>a</span> <span m='1056760'>complex</span> <span m='1057510'>number</span>
  <span m='1059600'>as</span> <span m='1059870'>s--</span> <span m='1060500'>no</span>
  <span m='1060740'>indication</span> <span m='1061250'>whatever</span> <span m='1061610'>that</span>
  <span m='1061790'>it's</span> <span m='1061880'>complex.</span> <span m='1063500'>And</span>
  <span m='1063680'>the</span> <span m='1063770'>one</span> <span m='1064010'>that</span>
  <span m='1064130'>is</span> <span m='1064250'>a</span> <span m='1064310'>real</span>
  <span m='1064520'>number,</span> <span m='1064890'>we</span> <span m='1064910'>put</span>
  <span m='1065030'>a</span> <span m='1065100'>j</span> <span m='1065360'>in</span>
  <span m='1065450'>front</span> <span m='1065660'>of</span> <span m='1065810'>it</span>
  <span m='1065930'>to</span> <span m='1066080'>remind</span> <span m='1066410'>you</span>
  <span m='1066590'>that</span> <span m='1066770'>it's</span> <span m='1066920'>real.</span>
  </p><p><span m='1069070'>I</span> <span m='1069260'>apologize,</span> <span m='1070160'>I</span>
  <span m='1070250'>don't</span> <span m='1070430'>know</span> <span m='1070520'>why</span>
  <span m='1070670'>we</span> <span m='1070790'>do</span> <span m='1070940'>this.</span>
  <span m='1072930'>So</span> <span m='1073040'>just</span> <span m='1073310'>remember</span>
  <span m='1073700'>that</span> <span m='1073910'>s,</span> <span m='1074750'>which</span>
  <span m='1074960'>looks</span> <span m='1075200'>kind</span> <span m='1075440'>of</span>
  <span m='1075530'>real</span> <span m='1075920'>isn't.</span> <span m='1076280'>It's</span>
  <span m='1076400'>complex.</span> <span m='1078830'>And</span> <span m='1078980'>j
  omega,</span> <span m='1079490'>which</span> <span m='1079700'>looks</span> <span
  m='1079910'>kind</span> <span m='1080150'>of</span> <span m='1080270'>complex,</span>
  <span m='1081290'>well,</span> <span m='1081500'>it's</span> <span m='1081620'>the</span>
  <span m='1081740'>omega</span> <span m='1081980'>part</span> <span m='1082220'>that</span>
  <span m='1082310'>matters.</span> <span m='1082640'>It's</span> <span m='1082790'>real.</span>
  </p><p><span m='1083620'>OK,</span> <span m='1084260'>so</span> <span m='1084410'>the</span>
  <span m='1084530'>important</span> <span m='1084980'>thing</span> <span m='1085220'>is</span>
  <span m='1085760'>the</span> <span m='1085880'>Laplace</span> <span m='1086130'>transform,</span>
  <span m='1086630'>the</span> <span m='1086720'>domain</span> <span m='1087260'>of</span>
  <span m='1087330'>a</span> <span m='1087500'>Laplace</span> <span m='1087890'>transform</span>
  <span m='1089680'>is</span> <span m='1090370'>complex</span> <span m='1091270'>number</span>
  <span m='1091660'>s,</span> <span m='1092110'>real</span> <span m='1092290'>and</span>
  <span m='1092380'>imaginary</span> <span m='1092800'>parts,</span> <span m='1093190'>characterized</span>
  <span m='1093730'>by a</span> <span m='1093910'>plane.</span> <span m='1096330'>The</span>
  <span m='1096480'>domain</span> <span m='1096990'>of</span> <span m='1097050'>the</span>
  <span m='1097170'>Fourier</span> <span m='1097440'>transform</span> <span m='1098160'>is</span>
  <span m='1098460'>real.</span> <span m='1099880'>That's</span> <span m='1100110'>enormously</span>
  <span m='1100920'>important.</span> <span m='1101880'>And</span> <span m='1102090'>we'll</span>
  <span m='1102180'>come</span> <span m='1102360'>back</span> <span m='1102570'>to</span>
  <span m='1102660'>that</span> <span m='1102960'>over</span> <span m='1103230'>and</span>
  <span m='1103320'>over</span> <span m='1103560'>again.</span> </p><p><span m='1105110'>But</span>
  <span m='1105270'>just</span> <span m='1105480'>to</span> <span m='1105570'>drive</span>
  <span m='1105870'>home</span> <span m='1106080'>the</span> <span m='1106170'>point,</span>
  <span m='1107430'>one</span> <span m='1107850'>of</span> <span m='1107970'>the</span>
  <span m='1108090'>things</span> <span m='1108450'>we</span> <span m='1108600'>thought</span>
  <span m='1108840'>about</span> <span m='1109110'>with</span> <span m='1109380'>the</span>
  <span m='1109450'>Laplace</span> <span m='1109750'>transform</span> <span m='1110790'>was</span>
  <span m='1110970'>this</span> <span m='1111120'>idea</span> <span m='1112110'>of</span>
  <span m='1112410'>eigenfunctions</span> <span m='1113280'>and</span> <span m='1113400'>eigenvalues.</span>
  <span m='1115590'>It</span> <span m='1115680'>was</span> <span m='1115890'>an</span>
  <span m='1116010'>idea</span> <span m='1116520'>of</span> <span m='1116730'>linearity.</span>
  <span m='1117360'>It</span> <span m='1117420'>was</span> <span m='1117570'>the</span>
  <span m='1117690'>idea</span> <span m='1118170'>that</span> <span m='1118290'>we</span>
  <span m='1118410'>can</span> <span m='1118530'>think</span> <span m='1118680'>about</span>
  <span m='1118860'>a</span> <span m='1118920'>system</span> <span m='1121820'>by</span>
  <span m='1122010'>how</span> <span m='1122190'>you</span> <span m='1122400'>put</span>
  <span m='1122760'>in</span> <span m='1122970'>a</span> <span m='1123060'>function,</span>
  <span m='1123570'>like</span> <span m='1123760'>E</span> <span m='1123990'>to the</span>
  <span m='1124300'>st,</span> <span m='1125190'>and</span> <span m='1125310'>calculate</span>
  <span m='1125820'>the</span> <span m='1125940'>output.</span> <span m='1126580'>Well,</span>
  <span m='1126800'>if</span> <span m='1126900'>the</span> <span m='1127020'>output,</span>
  <span m='1128050'>if</span> <span m='1128100'>the</span> <span m='1128220'>system</span>
  <span m='1129360'>is</span> <span m='1129480'>linear</span> <span m='1129720'>time</span>
  <span m='1129930'>invariant</span> <span m='1130350'>and</span> <span m='1130500'>can</span>
  <span m='1130620'>be</span> <span m='1130710'>characterized</span> <span m='1131430'>by
  a</span> <span m='1131610'>Laplace</span> <span m='1131940'>transform</span> <span
  m='1132360'>h</span> <span m='1132510'>of</span> <span m='1132600'>s,</span> <span
  m='1134970'>what's</span> <span m='1135270'>the</span> <span m='1135510'>output</span>
  <span m='1136860'>of</span> <span m='1136980'>that</span> <span m='1137220'>system</span>
  <span m='1137610'>when</span> <span m='1137760'>the</span> <span m='1137850'>input</span>
  <span m='1138090'>is</span> <span m='1138240'>e to the</span> <span m='1138560'>st?</span>
  </p><p><span m='1143950'>Everybody</span> <span m='1144340'>shout.</span> <span
  m='1144630'>It</span> <span m='1144730'>will</span> <span m='1144820'>make</span>
  <span m='1144970'>me</span> <span m='1145090'>feel</span> <span m='1145300'>much</span>
  <span m='1145720'>better.</span> <span m='1147940'>If</span> <span m='1148030'>you</span>
  <span m='1148150'>all</span> <span m='1148270'>shout</span> <span m='1148510'>at</span>
  <span m='1148570'>once,</span> <span m='1148900'>I</span> <span m='1148980'>won't</span>
  <span m='1149140'>be</span> <span m='1149230'>able</span> <span m='1149350'>to</span>
  <span m='1149470'>understand</span> <span m='1149890'>a</span> <span m='1149950'>word</span>
  <span m='1150160'>you</span> <span m='1150280'>said,</span> <span m='1150520'>and</span>
  <span m='1150610'>I'll</span> <span m='1150760'>assume</span> <span m='1151180'>you</span>
  <span m='1151270'>said</span> <span m='1151420'>the</span> <span m='1151510'>right</span>
  <span m='1151660'>thing.</span> </p><p><span m='1156610'>OK</span> <span m='1156940'>I</span>
  <span m='1157000'>didn't</span> <span m='1157210'>understand</span> <span m='1157570'>a</span>
  <span m='1157610'>thing</span> <span m='1157760'>you</span> <span m='1157840'>said.</span>
  <span m='1158140'>So</span> <span m='1158920'>I</span> <span m='1159040'>assume</span>
  <span m='1159370'>you</span> <span m='1159490'>all</span> <span m='1159670'>said</span>
  <span m='1161730'>h of s</span> <span m='1162040'>e to</span> <span m='1162450'>the</span>
  <span m='1162860'>st.</span> <span m='1165740'>Right,</span> <span m='1165950'>e</span>
  <span m='1166230'>to the</span> <span m='1166530'>st</span> <span m='1167760'>is</span>
  <span m='1168060'>an</span> <span m='1168210'>eigenfunction</span> <span m='1169470'>of
  a</span> <span m='1169740'>linear</span> <span m='1170310'>time</span> <span m='1170640'>invariant</span>
  <span m='1171240'>system.</span> <span m='1173010'>Eigenfunction</span> <span m='1173760'>means</span>
  <span m='1174210'>the</span> <span m='1174330'>function</span> <span m='1174860'>in</span>
  <span m='1175140'>is</span> <span m='1175290'>the</span> <span m='1175410'>same</span>
  <span m='1175860'>form</span> <span m='1176310'>as</span> <span m='1176460'>the</span>
  <span m='1176550'>function</span> <span m='1177000'>out</span> <span m='1177420'>except</span>
  <span m='1177740'>it</span> <span m='1177810'>could</span> <span m='1178020'>be</span>
  <span m='1178110'>multiplied</span> <span m='1178620'>by</span> <span m='1178800'>a</span>
  <span m='1178860'>constant.</span> <span m='1179740'>The</span> <span m='1179910'>constant
  is</span> <span m='1180390'>the</span> <span m='1180600'>eigenvalue.</span> <span
  m='1181500'>The</span> <span m='1181650'>eigenvalue</span> <span m='1182430'>is</span>
  <span m='1182610'>h</span> <span m='1182820'>of</span> <span m='1182940'>s.</span>
  </p><p><span m='1185640'>If</span> <span m='1185820'>we</span> <span m='1185940'>wanted</span>
  <span m='1186360'>to</span> <span m='1186540'>know,</span> <span m='1187330'>for</span>
  <span m='1187560'>example,</span> <span m='1188830'>if</span> <span m='1188880'>we</span>
  <span m='1188950'>wanted</span> <span m='1189180'>to</span> <span m='1189270'>characterize</span>
  <span m='1190710'>a</span> <span m='1190800'>very</span> <span m='1191100'>simple</span>
  <span m='1191430'>system,</span> <span m='1192690'>we</span> <span m='1192870'>might</span>
  <span m='1193050'>have</span> <span m='1193200'>a</span> <span m='1193230'>system</span>
  <span m='1193560'>of</span> <span m='1193620'>the</span> <span m='1193710'>form</span>
  <span m='1193980'>1 over</span> <span m='1194280'>1</span> <span m='1194430'>plus
  s.</span> <span m='1194910'>We</span> <span m='1195000'>might</span> <span m='1195120'>have</span>
  <span m='1195210'>a</span> <span m='1195270'>signal</span> <span m='1195530'>of</span>
  <span m='1195600'>the</span> <span m='1195690'>form</span> <span m='1195930'>1</span>
  <span m='1196040'>over</span> <span m='1196260'>1</span> <span m='1196410'>plus</span>
  <span m='1196660'>s.</span> <span m='1197540'>So let's</span> <span m='1197760'>say</span>
  <span m='1197910'>we</span> <span m='1198060'>have</span> <span m='1198150'>a</span>
  <span m='1198210'>system</span> <span m='1198570'>now.</span> <span m='1198860'>Let's</span>
  <span m='1198950'>say</span> <span m='1199110'>that</span> <span m='1199560'>x</span>
  <span m='1199860'>represents</span> <span m='1200280'>some</span> <span m='1200490'>kind</span>
  <span m='1200670'>of</span> <span m='1200760'>a</span> <span m='1200790'>system.</span>
  <span m='1201930'>Then</span> <span m='1202110'>we</span> <span m='1202260'>would</span>
  <span m='1202440'>have</span> <span m='1202590'>said</span> <span m='1202890'>that</span>
  <span m='1203010'>that's</span> <span m='1203250'>a</span> <span m='1203370'>pole.</span>
  </p><p><span m='1204270'>Where's</span> <span m='1204510'>the</span> <span m='1204600'>pole?</span>
  <span m='1207490'>Minus</span> <span m='1207950'>1--</span> <span m='1208580'>we</span>
  <span m='1208700'>would</span> <span m='1208820'>have</span> <span m='1208910'>said</span>
  <span m='1209090'>we</span> <span m='1209210'>have</span> <span m='1209360'>a</span>
  <span m='1209420'>system</span> <span m='1210410'>with</span> <span m='1210620'>a</span>
  <span m='1210680'>single</span> <span m='1210980'>pole</span> <span m='1211250'>at</span>
  <span m='1211340'>minus</span> <span m='1211670'>1.</span> <span m='1213518'>I</span>
  <span m='1213980'>would</span> <span m='1214130'>never</span> <span m='1214400'>have</span>
  <span m='1214550'>drawn</span> <span m='1214850'>this</span> <span m='1215000'>complicated</span>
  <span m='1216080'>picture</span> <span m='1216440'>at</span> <span m='1216530'>the</span>
  <span m='1216620'>bottom</span> <span m='1217010'>because</span> <span m='1217310'>it</span>
  <span m='1217370'>would</span> <span m='1217490'>be</span> <span m='1217580'>frightening.</span>
  <span m='1218780'>I</span> <span m='1218900'>would</span> <span m='1219050'>always</span>
  <span m='1219320'>draw</span> <span m='1219500'>something</span> <span m='1219830'>friendly</span>
  <span m='1220820'>like</span> <span m='1221060'>the</span> <span m='1221180'>picture</span>
  <span m='1221750'>over</span> <span m='1221960'>here.</span> <span m='1222830'>Right,</span>
  <span m='1223070'>the</span> <span m='1223190'>entire</span> <span m='1223520'>system</span>
  <span m='1223880'>can</span> <span m='1224000'>be</span> <span m='1224150'>understood</span>
  <span m='1224570'>by a</span> <span m='1224750'>single</span> <span m='1225260'>x.</span>
  </p><p><span m='1228110'>OK</span> <span m='1228440'>well,</span> <span m='1228800'>if</span>
  <span m='1228990'>you were</span> <span m='1229280'>computing</span> <span m='1229880'>eigenfunctions</span>
  <span m='1230780'>and</span> <span m='1230870'>eigenvalues,</span> <span m='1231650'>you</span>
  <span m='1231740'>would</span> <span m='1231860'>like</span> <span m='1232040'>to</span>
  <span m='1232190'>know</span> <span m='1232850'>what's</span> <span m='1233120'>the</span>
  <span m='1233240'>magnitude</span> <span m='1233720'>and</span> <span m='1233840'>phase.</span>
  <span m='1236920'>Sorry,</span> <span m='1237340'>the</span> <span m='1238180'>x</span>
  <span m='1238450'>of</span> <span m='1238570'>s</span> <span m='1239200'>is</span>
  <span m='1239500'>a</span> <span m='1239740'>complex</span> <span m='1240370'>valued</span>
  <span m='1240970'>function</span> <span m='1241690'>of</span> <span m='1241930'>complex</span>
  <span m='1242620'>domain.</span> <span m='1244100'>s</span> <span m='1244570'>is</span>
  <span m='1244630'>a</span> <span m='1244690'>complex</span> <span m='1245050'>number,</span>
  <span m='1245260'>and</span> <span m='1245350'>the</span> <span m='1245470'>answer</span>
  <span m='1245710'>is a</span> <span m='1245830'>complex</span> <span m='1246160'>number.</span>
  <span m='1248360'>So</span> <span m='1248410'>we'd</span> <span m='1248560'>like</span>
  <span m='1248710'>to</span> <span m='1248830'>know</span> <span m='1249010'>the</span>
  <span m='1249100'>real</span> <span m='1249280'>and</span> <span m='1249370'>imaginary</span>
  <span m='1249880'>parts</span> <span m='1251260'>of</span> <span m='1251590'>h of</span>
  <span m='1251950'>s</span> <span m='1252580'>or</span> <span m='1252820'>the</span>
  <span m='1252940'>magnitude</span> <span m='1253450'>and</span> <span m='1253570'>phase</span>
  <span m='1254320'>equivalently.</span> </p><p><span m='1256220'>If</span> <span
  m='1256300'>we</span> <span m='1256390'>want</span> <span m='1256570'>to</span>
  <span m='1256630'>know</span> <span m='1256750'>the</span> <span m='1256870'>magnitude</span>
  <span m='1257410'>and</span> <span m='1257530'>phase,</span> <span m='1257860'>for</span>
  <span m='1257950'>example,</span> <span m='1258370'>of</span> <span m='1258460'>h</span>
  <span m='1258640'>of</span> <span m='1258760'>s,</span> <span m='1259210'>in</span>
  <span m='1259390'>principle,</span> <span m='1259840'>we</span> <span m='1259990'>need</span>
  <span m='1260200'>to</span> <span m='1260320'>know</span> <span m='1261010'>what</span>
  <span m='1261250'>magnitude</span> <span m='1262000'>could</span> <span m='1262120'>it</span>
  <span m='1262180'>be</span> <span m='1262330'>for</span> <span m='1262480'>all</span>
  <span m='1262600'>the</span> <span m='1262690'>different</span> <span m='1262930'>s's.</span>
  <span m='1264280'>So</span> <span m='1264730'>what's</span> <span m='1264850'>plotted</span>
  <span m='1265270'>here</span> <span m='1266170'>is</span> <span m='1266350'>a</span>
  <span m='1266410'>picture</span> <span m='1266740'>of</span> <span m='1266800'>the</span>
  <span m='1266890'>magnitude</span> <span m='1269620'>of</span> <span m='1269770'>this</span>
  <span m='1270040'>function</span> <span m='1272070'>as</span> <span m='1272250'>a</span>
  <span m='1272310'>function</span> <span m='1272640'>of</span> <span m='1272700'>all</span>
  <span m='1272850'>the</span> <span m='1272940'>different</span> <span m='1273180'>s's</span>
  <span m='1273570'>that</span> <span m='1274860'>can</span> <span m='1276450'>be</span>
  <span m='1276660'>an</span> <span m='1276750'>eigenfunction.</span> <span m='1277860'>Right,</span>
  <span m='1278220'>so</span> <span m='1278430'>for</span> <span m='1278640'>all</span>
  <span m='1278940'>of</span> <span m='1279000'>the--</span> <span m='1279450'>so</span>
  <span m='1279900'>any</span> <span m='1280470'>s</span> <span m='1281370'>is</span>
  <span m='1281520'>an</span> <span m='1281610'>eigenfunction</span> <span m='1282180'>of</span>
  <span m='1282240'>the</span> <span m='1282360'>system.</span> <span m='1284420'>And</span>
  <span m='1284960'>that</span> <span m='1285530'>plot</span> <span m='1286040'>plots</span>
  <span m='1286370'>the</span> <span m='1286490'>magnitude</span> <span m='1287000'>of</span>
  <span m='1287060'>the</span> <span m='1287150'>associated</span> <span m='1287660'>eigenvalue.</span>
  </p><p><span m='1290690'>The</span> <span m='1290810'>point</span> <span m='1291200'>is</span>
  <span m='1291830'>that</span> <span m='1292050'>I</span> <span m='1292220'>have</span>
  <span m='1292370'>to</span> <span m='1292490'>tell</span> <span m='1292700'>you</span>
  <span m='1293390'>a</span> <span m='1293480'>complex</span> <span m='1293990'>plane</span>
  <span m='1295460'>number</span> <span m='1296390'>of</span> <span m='1296960'>values.</span>
  <span m='1298410'>Right?</span> <span m='1298800'>There</span> <span m='1299030'>a</span>
  <span m='1299090'>value</span> <span m='1299510'>for</span> <span m='1300790'>s
  equals</span> <span m='1301100'>1,</span> <span m='1301430'>s</span> <span m='1301550'>equals</span>
  <span m='1301790'>minus</span> <span m='1302060'>1,</span> <span m='1302360'>s</span>
  <span m='1302480'>equals</span> <span m='1302630'>2,</span> <span m='1302900'>s</span>
  <span m='1303020'>equals</span> <span m='1303290'>minus</span> <span m='1303650'>2,</span>
  <span m='1304010'>s</span> <span m='1304150'>equals</span> <span m='1304460'>j,</span>
  <span m='1304740'>s</span> <span m='1305020'>equals</span> <span m='1305270'>2j,</span>
  <span m='1306290'>s</span> <span m='1306440'>equals</span> <span m='1306660'>17</span>
  <span m='1307160'>plus</span> <span m='1307400'>5j.</span> <span m='1309320'>All</span>
  <span m='1309530'>the</span> <span m='1309590'>different</span> <span m='1309830'>values,</span>
  <span m='1310430'>all</span> <span m='1310580'>the</span> <span m='1310640'>different</span>
  <span m='1310880'>points</span> <span m='1311210'>in</span> <span m='1311270'>the</span>
  <span m='1311360'>s</span> <span m='1311570'>plane</span> <span m='1312230'>have</span>
  <span m='1312380'>a</span> <span m='1312440'>different</span> <span m='1312680'>associated</span>
  <span m='1313250'>eigenvalue.</span> <span m='1314120'>And</span> <span m='1314300'>to</span>
  <span m='1314420'>completely</span> <span m='1314960'>characterize</span> <span
  m='1315540'>this</span> <span m='1315620'>system,</span> <span m='1315920'>I</span>
  <span m='1315980'>have</span> <span m='1316100'>to</span> <span m='1316190'>tell</span>
  <span m='1316340'>you</span> <span m='1316460'>all</span> <span m='1316730'>of</span>
  <span m='1316820'>those.</span> </p><p><span m='1318050'>By</span> <span m='1318230'>contrast,</span>
  <span m='1319440'>if</span> <span m='1319490'>I</span> <span m='1319580'>think</span>
  <span m='1319730'>about</span> <span m='1319850'>the</span> <span m='1319970'>Fourier</span>
  <span m='1320390'>transform,</span> <span m='1321130'>the</span> <span m='1321380'>Fourier</span>
  <span m='1321710'>transform</span> <span m='1322160'>maps</span> <span m='1322490'>a</span>
  <span m='1322550'>function</span> <span m='1322910'>of</span> <span m='1323030'>time</span>
  <span m='1325670'>to</span> <span m='1325850'>a</span> <span m='1325910'>function</span>
  <span m='1326360'>of</span> <span m='1326450'>omega.</span> <span m='1328870'>The</span>
  <span m='1329050'>complete</span> <span m='1329470'>characterization</span> <span
  m='1330250'>of</span> <span m='1330330'>the</span> <span m='1330370'>Fourier</span>
  <span m='1330790'>transform</span> <span m='1331280'>is</span> <span m='1331340'>showed</span>
  <span m='1331630'>here.</span> <span m='1333220'>All</span> <span m='1333430'>I</span>
  <span m='1333520'>need</span> <span m='1333670'>to</span> <span m='1333790'>worry</span>
  <span m='1334060'>about</span> <span m='1334810'>is</span> <span m='1335020'>what</span>
  <span m='1335230'>are</span> <span m='1335350'>all</span> <span m='1335590'>the</span>
  <span m='1335710'>possible</span> <span m='1336250'>values</span> <span m='1336700'>of</span>
  <span m='1336820'>omega.</span> </p><p><span m='1337630'>I'm</span> <span m='1337780'>thinking</span>
  <span m='1338110'>now</span> <span m='1338380'>instead</span> <span m='1338710'>of</span>
  <span m='1338800'>thinking</span> <span m='1339130'>s,</span> <span m='1339520'>I'm</span>
  <span m='1339640'>thinking</span> <span m='1340450'>how</span> <span m='1340690'>would</span>
  <span m='1340900'>I</span> <span m='1341020'>compose</span> <span m='1342100'>x</span>
  <span m='1342370'>of</span> <span m='1342520'>t</span> <span m='1344050'>by</span>
  <span m='1344230'>summing</span> <span m='1344560'>together</span> <span m='1344950'>a</span>
  <span m='1344980'>bunch</span> <span m='1345190'>of</span> <span m='1345280'>sine</span>
  <span m='1345580'>waves.</span> <span m='1347350'>The</span> <span m='1347440'>reason</span>
  <span m='1347680'>I</span> <span m='1347740'>want</span> <span m='1347890'>to</span>
  <span m='1347950'>think</span> <span m='1348100'>about</span> <span m='1348310'>that</span>
  <span m='1348490'>is</span> <span m='1348580'>because</span> <span m='1349870'>I</span>
  <span m='1349930'>want</span> <span m='1350050'>to</span> <span m='1350110'>think</span>
  <span m='1350230'>about</span> <span m='1350410'>systems</span> <span m='1350950'>in</span>
  <span m='1351070'>terms</span> <span m='1351280'>of</span> <span m='1351340'>frequency</span>
  <span m='1351850'>responses.</span> <span m='1353420'>So</span> <span m='1353470'>I</span>
  <span m='1353530'>want</span> <span m='1353740'>to</span> <span m='1353800'>know</span>
  <span m='1354430'>which</span> <span m='1354760'>frequencies</span> <span m='1355360'>are</span>
  <span m='1355480'>amplified,</span> <span m='1356200'>which</span> <span m='1356410'>ones</span>
  <span m='1356590'>are</span> <span m='1356680'>attenuated,</span> <span m='1357370'>which</span>
  <span m='1357580'>ones</span> <span m='1357760'>are</span> <span m='1357850'>phase</span>
  <span m='1358320'>delayed,</span> <span m='1358780'>which</span> <span m='1358930'>ones</span>
  <span m='1359170'>are</span> <span m='1359260'>phase</span> <span m='1359770'>advanced.</span>
  <span m='1361690'>And</span> <span m='1361870'>in</span> <span m='1361960'>order</span>
  <span m='1362230'>to</span> <span m='1362350'>do</span> <span m='1362500'>that</span>
  <span m='1362680'>kind</span> <span m='1362920'>of</span> <span m='1363070'>construction,</span>
  <span m='1364060'>all</span> <span m='1364360'>I</span> <span m='1364450'>need</span>
  <span m='1364690'>to</span> <span m='1364840'>know</span> <span m='1365620'>is</span>
  <span m='1366010'>what's</span> <span m='1366310'>the</span> <span m='1366430'>magnitude</span>
  <span m='1367030'>and</span> <span m='1367120'>angle</span> <span m='1369700'>of</span>
  <span m='1369850'>the</span> <span m='1369970'>system</span> <span m='1370300'>function</span>
  <span m='1371140'>for</span> <span m='1371320'>all</span> <span m='1371500'>possible</span>
  <span m='1371980'>values</span> <span m='1372310'>of</span> <span m='1372440'>omega.</span>
  </p><p><span m='1375540'>So</span> <span m='1375560'>that's</span> <span m='1375770'>an</span>
  <span m='1375890'>enormous</span> <span m='1376340'>difference.</span> <span m='1377150'>Instead</span>
  <span m='1377510'>of</span> <span m='1377600'>having,</span> <span m='1378740'>in</span>
  <span m='1378950'>the</span> <span m='1379010'>previous</span> <span m='1379370'>case,</span>
  <span m='1380340'>I</span> <span m='1380440'>had</span> <span m='1380520'>a</span>
  <span m='1380660'>function</span> <span m='1381230'>of</span> <span m='1381410'>time</span>
  <span m='1381890'>turning</span> <span m='1382250'>into</span> <span m='1382550'>a</span>
  <span m='1382610'>function</span> <span m='1383210'>of</span> <span m='1383400'>two</span>
  <span m='1383710'>space.</span> <span m='1385640'>Function</span> <span m='1385970'>of</span>
  <span m='1386060'>one</span> <span m='1386300'>space</span> <span m='1386660'>turned</span>
  <span m='1386870'>into</span> <span m='1387080'>a</span> <span m='1387140'>function</span>
  <span m='1387500'>of</span> <span m='1387590'>two</span> <span m='1387800'>space.</span>
  <span m='1389030'>Here</span> <span m='1389450'>I</span> <span m='1389570'>have</span>
  <span m='1389750'>a</span> <span m='1389780'>function</span> <span m='1390050'>of</span>
  <span m='1390140'>one</span> <span m='1390350'>space</span> <span m='1390620'>turning</span>
  <span m='1390890'>into</span> <span m='1391070'>a</span> <span m='1391130'>function</span>
  <span m='1391400'>of</span> <span m='1391460'>one</span> <span m='1391700'>space.</span>
  <span m='1393990'>So</span> <span m='1394100'>that</span> <span m='1394580'>is</span>
  <span m='1395720'>conceptually</span> <span m='1396440'>a</span> <span m='1396470'>whole</span>
  <span m='1396620'>lot</span> <span m='1396800'>simpler.</span> </p><p><span m='1397670'>Even</span>
  <span m='1398000'>more</span> <span m='1398180'>importantly,</span> <span m='1399300'>it</span>
  <span m='1399440'>is</span> <span m='1399620'>going</span> <span m='1399890'>to</span>
  <span m='1400010'>give</span> <span m='1400250'>rise</span> <span m='1400670'>to</span>
  <span m='1400760'>something</span> <span m='1401120'>that</span> <span m='1401260'>we'll</span>
  <span m='1401430'>spend</span> <span m='1401630'>most</span> <span m='1401930'>of</span>
  <span m='1401990'>the</span> <span m='1402080'>time</span> <span m='1402350'>for</span>
  <span m='1402440'>the</span> <span m='1402530'>rest</span> <span m='1402680'>of</span>
  <span m='1402740'>the</span> <span m='1402860'>term</span> <span m='1403280'>on--</span>
  <span m='1404330'>the</span> <span m='1404450'>notion</span> <span m='1404900'>of</span>
  <span m='1405080'>signal</span> <span m='1405470'>processing</span> <span m='1407390'>where</span>
  <span m='1407660'>we</span> <span m='1407840'>can</span> <span m='1408260'>alternatively</span>
  <span m='1409190'>represent</span> <span m='1410000'>a</span> <span m='1410090'>signal</span>
  <span m='1410660'>x</span> <span m='1412310'>not</span> <span m='1412790'>by</span>
  <span m='1413180'>its</span> <span m='1413450'>time</span> <span m='1413930'>samples,</span>
  <span m='1415010'>but</span> <span m='1415190'>instead</span> <span m='1415670'>by</span>
  <span m='1415910'>its</span> <span m='1416120'>frequency</span> <span m='1416780'>samples.</span>
  <span m='1418930'>It</span> <span m='1419060'>would</span> <span m='1419240'>be</span>
  <span m='1419390'>very</span> <span m='1419750'>difficult</span> <span m='1420680'>to</span>
  <span m='1420860'>use</span> <span m='1421220'>that</span> <span m='1421490'>technique.</span>
  <span m='1422130'>Although</span> <span m='1422390'>it</span> <span m='1422480'>would</span>
  <span m='1422660'>work</span> <span m='1422990'>perfectly,</span> <span m='1426560'>there</span>
  <span m='1426710'>would</span> <span m='1426830'>be</span> <span m='1426980'>an</span>
  <span m='1427070'>explosion</span> <span m='1427700'>of</span> <span m='1427790'>information</span>
  <span m='1428330'>if</span> <span m='1428420'>we</span> <span m='1428510'>tried</span>
  <span m='1428720'>to</span> <span m='1428810'>use</span> <span m='1429350'>a</span>
  <span m='1429440'>signal</span> <span m='1429770'>processing</span> <span m='1430390'>technique</span>
  <span m='1431450'>with</span> <span m='1431840'>this</span> <span m='1433070'>where</span>
  <span m='1433250'>we</span> <span m='1433400'>represent</span> <span m='1433940'>this</span>
  <span m='1434120'>one-dimensional</span> <span m='1434840'>signal</span> <span m='1435140'>by
  a</span> <span m='1435340'>two-dimensional</span> <span m='1437600'>transform</span>
  <span m='1438740'>because</span> <span m='1439070'>we</span> <span m='1439250'>would</span>
  <span m='1439370'>be</span> <span m='1439790'>exploding</span> <span m='1440510'>the</span>
  <span m='1440600'>amount</span> <span m='1440870'>of</span> <span m='1440960'>information.</span>
  <span m='1441950'>We</span> <span m='1442070'>would</span> <span m='1442160'>be</span>
  <span m='1442310'>increasing</span> <span m='1442880'>substantially</span> <span
  m='1444140'>the</span> <span m='1444230'>amount</span> <span m='1444470'>of</span>
  <span m='1444530'>information</span> <span m='1445190'>required</span> <span m='1445700'>to</span>
  <span m='1445910'>specify</span> <span m='1446450'>the</span> <span m='1446600'>signal.</span>
  </p><p><span m='1448310'>When</span> <span m='1448640'>we</span> <span m='1448790'>do</span>
  <span m='1448970'>the</span> <span m='1449060'>Fourier,</span> <span m='1450620'>there</span>
  <span m='1450920'>is</span> <span m='1451190'>no</span> <span m='1451430'>such</span>
  <span m='1451760'>explosion.</span> <span m='1453120'>It</span> <span m='1453200'>was</span>
  <span m='1453650'>a</span> <span m='1453740'>one-dimensional</span> <span m='1454370'>function</span>
  <span m='1454730'>of</span> <span m='1454850'>time.</span> <span m='1455280'>It</span>
  <span m='1455510'>is</span> <span m='1456200'>a</span> <span m='1456350'>one-dimensional</span>
  <span m='1456920'>function</span> <span m='1457280'>of</span> <span m='1457370'>omega.</span>
  </p><p><span m='1461520'>OK,</span> <span m='1464020'>OK,</span> <span m='1464260'>I've</span>
  <span m='1464350'>been</span> <span m='1464470'>talking</span> <span m='1464740'>too</span>
  <span m='1464860'>much.</span> <span m='1466330'>I</span> <span m='1466450'>would</span>
  <span m='1466630'>like</span> <span m='1466870'>you</span> <span m='1467020'>to</span>
  <span m='1467110'>make</span> <span m='1467260'>sure</span> <span m='1467470'>that</span>
  <span m='1467560'>you</span> <span m='1467650'>understand</span> <span m='1468070'>the</span>
  <span m='1468130'>mechanics</span> <span m='1468640'>of</span> <span m='1468710'>what</span>
  <span m='1469120'>I've</span> <span m='1469330'>just</span> <span m='1469540'>said.</span>
  <span m='1470270'>So</span> <span m='1470980'>here's</span> <span m='1471250'>a</span>
  <span m='1471310'>signal,</span> <span m='1471640'>x1</span> <span m='1471850'>of
  t.</span> <span m='1473590'>Which</span> <span m='1473950'>of</span> <span m='1474070'>these,</span>
  <span m='1474490'>if</span> <span m='1474700'>any,</span> <span m='1475510'>represents</span>
  <span m='1476050'>the</span> <span m='1476170'>Fourier</span> <span m='1476550'>transform?</span>
  </p><p><span m='1479600'>You're</span> <span m='1479740'>all</span> <span m='1479860'>very</span>
  <span m='1480040'>quiet.</span> <span m='1480460'>Look</span> <span m='1480640'>at</span>
  <span m='1480700'>your</span> <span m='1480790'>neighbor.</span> <span m='1481660'>Don't</span>
  <span m='1481840'>be</span> <span m='1481900'>quiet.</span> <span m='1482590'>And</span>
  <span m='1482740'>then</span> <span m='1482920'>start.</span> <span m='1483430'>And</span>
  <span m='1483580'>then</span> <span m='1483700'>you</span> <span m='1483770'>can
  go</span> <span m='1483910'>back</span> <span m='1484090'>to</span> <span m='1484150'>being</span>
  <span m='1484870'>quiet.</span> </p><p><span m='1485195'>[SIDE CONVERSATIONS]</span>
  </p><p></p><p><span m='1565020'>So</span> <span m='1565190'>it's</span> <span m='1565310'>quiet.</span>
  <span m='1565640'>So</span> <span m='1565760'>I</span> <span m='1565850'>assume</span>
  <span m='1566090'>that</span> <span m='1566300'>means</span> <span m='1566600'>convergence.</span>
  <span m='1567220'>So</span> <span m='1569120'>which</span> <span m='1569390'>function</span>
  <span m='1570380'>represents</span> <span m='1570695'>the Fourier</span> <span m='1571010'>transform</span>
  <span m='1571640'>of</span> <span m='1571850'>x1</span> <span m='1572300'>of</span>
  <span m='1572420'>t?</span> <span m='1572780'>Everybody</span> <span m='1573110'>raise</span>
  <span m='1573260'>your</span> <span m='1573380'>hand.</span> <span m='1573830'>Indicate</span>
  <span m='1574190'>by</span> <span m='1574550'>a</span> <span m='1574730'>number</span>
  <span m='1575000'>of</span> <span m='1575060'>fingers.</span> </p><p><span m='1575960'>And</span>
  <span m='1576260'>it's</span> <span m='1576500'>overwhelmingly</span> <span m='1577250'>correct,</span>
  <span m='1577910'>which</span> <span m='1578120'>is</span> <span m='1578210'>wonderful.</span>
  <span m='1578900'>That's</span> <span m='1579110'>the</span> <span m='1579200'>point.</span>
  <span m='1580230'>The</span> <span m='1580330'>point</span> <span m='1580520'>is</span>
  <span m='1580670'>Fourier</span> <span m='1580940'>transforms</span> <span m='1581390'>are</span>
  <span m='1581570'>easy.</span> <span m='1582170'>And</span> <span m='1582320'>you've</span>
  <span m='1582470'>all</span> <span m='1582620'>got</span> <span m='1582830'>it.</span>
  </p><p><span m='1583820'>So</span> <span m='1586460'>it's</span> <span m='1586790'>trivial</span>
  <span m='1587570'>to</span> <span m='1587750'>run</span> <span m='1587990'>this</span>
  <span m='1588170'>kind</span> <span m='1588380'>of</span> <span m='1588470'>an</span>
  <span m='1588590'>integral.</span> <span m='1589100'>It's</span> <span m='1589310'>not</span>
  <span m='1589520'>very</span> <span m='1589760'>different</span> <span m='1590030'>from</span>
  <span m='1590240'>doing</span> <span m='1590450'>a</span> <span m='1590660'>Laplace</span>
  <span m='1590960'>transform.</span> <span m='1591590'>Here</span> <span m='1591770'>I've</span>
  <span m='1591860'>indicated</span> <span m='1592165'>the</span> <span m='1592470'>Laplace</span>
  <span m='1592760'>transform.</span> <span m='1593940'>Right?</span> <span m='1594260'>We</span>
  <span m='1594380'>do</span> <span m='1594600'>e to the</span> <span m='1594890'>minus</span>
  <span m='1595310'>t.</span> <span m='1595640'>x</span> <span m='1595820'>of</span>
  <span m='1595940'>t</span> <span m='1596120'>is</span> <span m='1596240'>1</span>
  <span m='1596480'>or</span> <span m='1596540'>0.</span> <span m='1597050'>We</span>
  <span m='1597590'>change</span> <span m='1597980'>the</span> <span m='1598130'>limits</span>
  <span m='1598550'>to</span> <span m='1598700'>indicate</span> <span m='1599150'>the</span>
  <span m='1599240'>1</span> <span m='1599420'>or</span> <span m='1599480'>zeroness.</span>
  </p><p><span m='1600860'>Very</span> <span m='1601220'>trivial</span> <span m='1601700'>here,</span>
  <span m='1601940'>we</span> <span m='1602060'>get a</span> <span m='1602240'>slightly</span>
  <span m='1602700'>different</span> <span m='1602990'>looking</span> <span m='1603230'>answer</span>
  <span m='1603530'>because</span> <span m='1603830'>instead</span> <span m='1604130'>of</span>
  <span m='1604550'>e</span> <span m='1604740'>to</span> <span m='1604820'>the</span>
  <span m='1604970'>st,</span> <span m='1605330'>we</span> <span m='1605420'>have</span>
  <span m='1605570'>e to</span> <span m='1605750'>the</span> <span m='1605860'>j omega</span>
  <span m='1606060'>t.</span> <span m='1608090'>But</span> <span m='1608570'>otherwise,</span>
  <span m='1608990'>it's</span> <span m='1609110'>pretty</span> <span m='1609350'>much</span>
  <span m='1609740'>the</span> <span m='1609860'>same.</span> <span m='1611700'>The</span>
  <span m='1611720'>big</span> <span m='1611990'>difference,</span> <span m='1612470'>though,</span>
  <span m='1612650'>is</span> <span m='1612780'>again</span> <span m='1613100'>the</span>
  <span m='1613190'>domain.</span> </p><p><span m='1615810'>So</span> <span m='1615890'>if</span>
  <span m='1616100'>you</span> <span m='1616220'>think</span> <span m='1616490'>about</span>
  <span m='1617000'>the</span> <span m='1617210'>answer--</span> <span m='1617890'>so</span>
  <span m='1618020'>the</span> <span m='1618110'>answer is</span> <span m='1618410'>four</span>
  <span m='1618800'>like</span> <span m='1619150'>all</span> <span m='1619280'>of</span>
  <span m='1619440'>you</span> <span m='1619550'>said--</span> <span m='1620450'>if</span>
  <span m='1620570'>you</span> <span m='1620630'>think</span> <span m='1620780'>about</span>
  <span m='1620960'>the</span> <span m='1621140'>answer</span> <span m='1621590'>from</span>
  <span m='1621830'>the</span> <span m='1621920'>point</span> <span m='1622160'>of</span>
  <span m='1622220'>view</span> <span m='1622400'>of</span> <span m='1622520'>eigenfunctions</span>
  <span m='1625480'>and</span> <span m='1625600'>eigenvalues,</span> <span m='1627830'>you</span>
  <span m='1627950'>have</span> <span m='1628040'>to</span> <span m='1628160'>think</span>
  <span m='1628310'>about</span> <span m='1628520'>a</span> <span m='1628580'>two</span>
  <span m='1628730'>space.</span> <span m='1630390'>The</span> <span m='1630590'>two</span>
  <span m='1630770'>space</span> <span m='1631190'>for</span> <span m='1631520'>even</span>
  <span m='1631940'>that</span> <span m='1632180'>simple</span> <span m='1632570'>function,</span>
  <span m='1633380'>sort</span> <span m='1633590'>of</span> <span m='1635430'>the</span>
  <span m='1635540'>least</span> <span m='1635810'>complicated</span> <span m='1636530'>function</span>
  <span m='1636860'>I</span> <span m='1636890'>could</span> <span m='1637040'>think</span>
  <span m='1637280'>of,</span> <span m='1638990'>is</span> <span m='1639230'>illustrated</span>
  <span m='1639860'>here.</span> <span m='1641460'>And</span> <span m='1641510'>what</span>
  <span m='1642050'>you're</span> <span m='1642200'>supposed</span> <span m='1642530'>to</span>
  <span m='1642620'>see</span> <span m='1642830'>there</span> <span m='1643070'>is</span>
  <span m='1643220'>if</span> <span m='1643940'>I</span> <span m='1644030'>were</span>
  <span m='1644180'>to</span> <span m='1644300'>integrate</span> <span m='1644870'>x</span>
  <span m='1645040'>of</span> <span m='1645210'>t</span> <span m='1646980'>e</span>
  <span m='1647080'>to</span> <span m='1647350'>the</span> <span m='1647430'>minus</span>
  <span m='1647720'>st</span> <span m='1647970'>dt</span> <span m='1648890'>to</span>
  <span m='1648980'>get</span> <span m='1649230'>x of</span> <span m='1649585'>s,</span>
  <span m='1652010'>if</span> <span m='1652130'>I</span> <span m='1652220'>think</span>
  <span m='1652400'>about</span> <span m='1652650'>s</span> <span m='1653946'>as</span>
  <span m='1654380'>sigma</span> <span m='1654740'>plus</span> <span m='1655030'>j</span>
  <span m='1655320'>omega--</span> <span m='1656670'>it</span> <span m='1657100'>has</span>
  <span m='1657290'>a</span> <span m='1657350'>real</span> <span m='1657500'>part
  and</span> <span m='1657740'>an</span> <span m='1657800'>imaginary</span> <span
  m='1658220'>part--</span> <span m='1659480'>the</span> <span m='1659690'>real</span>
  <span m='1659990'>part,</span> <span m='1660260'>as I</span> <span m='1660470'>make</span>
  <span m='1660590'>the</span> <span m='1660710'>real</span> <span m='1660890'>part</span>
  <span m='1661180'>big,</span> <span m='1662085'>e</span> <span m='1662470'>to the</span>
  <span m='1662720'>st</span> <span m='1663000'>becomes</span> <span m='1663400'>something</span>
  <span m='1663710'>that</span> <span m='1663860'>explodes.</span> </p><p><span m='1665780'>And</span>
  <span m='1665900'>you</span> <span m='1666020'>can</span> <span m='1666170'>see</span>
  <span m='1666410'>that</span> <span m='1666620'>manifest</span> <span m='1667190'>here</span>
  <span m='1667790'>over</span> <span m='1668060'>in</span> <span m='1668180'>this</span>
  <span m='1668390'>region.</span> <span m='1669020'>So</span> <span m='1669230'>this</span>
  <span m='1669440'>is</span> <span m='1669850'>the</span> <span m='1670070'>real</span>
  <span m='1670310'>axis</span> <span m='1670610'>this</span> <span m='1670760'>way.</span>
  <span m='1671030'>This</span> <span m='1671180'>is</span> <span m='1671270'>the</span>
  <span m='1671360'>imaginary</span> <span m='1671840'>axis</span> <span m='1672110'>that</span>
  <span m='1672290'>way.</span> <span m='1673550'>You</span> <span m='1673640'>can</span>
  <span m='1673760'>see</span> <span m='1673940'>that</span> <span m='1674120'>as</span>
  <span m='1674300'>you</span> <span m='1674390'>go</span> <span m='1674600'>to</span>
  <span m='1675980'>bigger</span> <span m='1676220'>numbers</span> <span m='1677330'>in</span>
  <span m='1677470'>the</span> <span m='1677510'>positive real</span> <span m='1677990'>direction,</span>
  <span m='1679310'>the</span> <span m='1679400'>magnitude</span> <span m='1679820'>explodes.</span>
  <span m='1682480'>If</span> <span m='1682690'>you</span> <span m='1682930'>go</span>
  <span m='1683320'>in</span> <span m='1684010'>the</span> <span m='1684130'>negative</span>
  <span m='1684490'>direction</span> <span m='1685000'>because</span> <span m='1685390'>there</span>
  <span m='1685510'>was</span> <span m='1685610'>a</span> <span m='1685690'>sum</span>
  <span m='1685990'>here,</span> <span m='1686590'>the</span> <span m='1686680'>magnitude</span>
  <span m='1687100'>explodes</span> <span m='1687430'>again.</span> <span m='1689300'>You</span>
  <span m='1689320'>get</span> <span m='1689470'>this</span> <span m='1689620'>horrible</span>
  <span m='1690130'>function</span> <span m='1690520'>that</span> <span m='1690700'>spends</span>
  <span m='1691240'>a</span> <span m='1691270'>lot</span> <span m='1691450'>of</span>
  <span m='1691540'>its</span> <span m='1691660'>time</span> <span m='1691990'>near</span>
  <span m='1692200'>infinity.</span> <span m='1692990'>Right?</span> </p><p><span
  m='1695020'>So</span> <span m='1695230'>that's</span> <span m='1695470'>a</span>
  <span m='1695530'>complicated</span> <span m='1696160'>picture</span> <span m='1696850'>by</span>
  <span m='1697060'>comparison</span> <span m='1697690'>to</span> <span m='1697780'>the</span>
  <span m='1697870'>picture</span> <span m='1698170'>that</span> <span m='1698290'>you</span>
  <span m='1698410'>get</span> <span m='1698590'>if</span> <span m='1698710'>you</span>
  <span m='1698800'>look</span> <span m='1698950'>at</span> <span m='1699160'>Fourier</span>
  <span m='1699490'>transform.</span> <span m='1700720'>So</span> <span m='1700840'>if</span>
  <span m='1700930'>you</span> <span m='1700990'>look</span> <span m='1701140'>at</span>
  <span m='1701300'>the Fourier</span> <span m='1701500'>transform,</span> <span m='1701980'>you</span>
  <span m='1702070'>get</span> <span m='1702220'>something</span> <span m='1702610'>that's</span>
  <span m='1702790'>relatively</span> <span m='1703420'>simpler.</span> <span m='1704530'>We're</span>
  <span m='1704680'>only</span> <span m='1704980'>looking</span> <span m='1705460'>along</span>
  <span m='1705760'>the</span> <span m='1705820'>imaginary</span> <span m='1706330'>axis</span>
  <span m='1706660'>now.</span> </p><p><span m='1707980'>Furthermore,</span> <span
  m='1708790'>there's</span> <span m='1708970'>an</span> <span m='1709150'>easy</span>
  <span m='1709510'>way</span> <span m='1709720'>to</span> <span m='1709840'>interpret</span>
  <span m='1710320'>this.</span> <span m='1710770'>This is</span> <span m='1710920'>explicitly</span>
  <span m='1711610'>telling</span> <span m='1712000'>us</span> <span m='1712540'>if</span>
  <span m='1712660'>you</span> <span m='1712750'>put</span> <span m='1712960'>a</span>
  <span m='1713020'>certain</span> <span m='1713320'>frequency</span> <span m='1713830'>into</span>
  <span m='1714010'>the</span> <span m='1714140'>system,</span> <span m='1714700'>say</span>
  <span m='1714850'>this</span> <span m='1715030'>represented</span> <span m='1715520'>a</span>
  <span m='1715600'>system</span> <span m='1715870'>function,</span> <span m='1716800'>if</span>
  <span m='1717010'>this</span> <span m='1717160'>represented</span> <span m='1717670'>a</span>
  <span m='1717770'>system</span> <span m='1718030'>function,</span> <span m='1718420'>it's</span>
  <span m='1718600'>telling</span> <span m='1718960'>you</span> <span m='1719590'>that</span>
  <span m='1719860'>there's</span> <span m='1720610'>a</span> <span m='1720670'>simple</span>
  <span m='1720970'>way</span> <span m='1721150'>of</span> <span m='1721240'>thinking</span>
  <span m='1721570'>about</span> <span m='1721840'>how</span> <span m='1721990'>it</span>
  <span m='1722080'>amplifies</span> <span m='1722620'>or</span> <span m='1722680'>attenuates</span>
  <span m='1723190'>frequencies.</span> <span m='1724150'>Right?</span> </p><p><span
  m='1724780'>It</span> <span m='1724960'>likes</span> <span m='1725320'>frequencies</span>
  <span m='1725920'>near</span> <span m='1726070'>the</span> <span m='1726190'>middle.</span>
  <span m='1727240'>There's</span> <span m='1727390'>a</span> <span m='1727450'>lot</span>
  <span m='1727660'>of</span> <span m='1727720'>frequencies--</span> <span m='1729020'>so</span>
  <span m='1729280'>if</span> <span m='1729490'>this</span> <span m='1729640'>represented</span>
  <span m='1730120'>a</span> <span m='1730200'>system</span> <span m='1730480'>function,</span>
  <span m='1732240'>it</span> <span m='1732400'>would</span> <span m='1732730'>pass</span>
  <span m='1733030'>with</span> <span m='1733210'>a</span> <span m='1733300'>gain</span>
  <span m='1733600'>of</span> <span m='1733750'>two</span> <span m='1734740'>frequencies</span>
  <span m='1735220'>near</span> <span m='1735370'>0.</span> <span m='1736990'>And</span>
  <span m='1737200'>the</span> <span m='1737290'>magnitude</span> <span m='1737740'>would</span>
  <span m='1737860'>be</span> <span m='1737980'>smaller</span> <span m='1738340'>for</span>
  <span m='1738460'>these</span> <span m='1738700'>others.</span> <span m='1739000'>And</span>
  <span m='1739080'>there</span> <span m='1739150'>is</span> <span m='1739270'>a</span>
  <span m='1739330'>phase</span> <span m='1739600'>relationship</span> <span m='1740230'>too.</span>
  </p><p><span m='1740560'>So</span> <span m='1740680'>there's</span> <span m='1740920'>insights</span>
  <span m='1741460'>that</span> <span m='1741550'>you</span> <span m='1741700'>can</span>
  <span m='1741850'>get</span> <span m='1743990'>from</span> <span m='1744200'>this</span>
  <span m='1744380'>Fourier</span> <span m='1744770'>representation</span> <span m='1745490'>that</span>
  <span m='1745610'>are</span> <span m='1745700'>less</span> <span m='1745970'>easy</span>
  <span m='1746300'>to</span> <span m='1746420'>get</span> <span m='1747080'>from</span>
  <span m='1747290'>the</span> <span m='1747480'>Laplace.</span> <span m='1747920'>I</span>
  <span m='1747980'>mean</span> <span m='1748310'>the</span> <span m='1748540'>Laplace</span>
  <span m='1748880'>was</span> <span m='1749710'>a</span> <span m='1749960'>complete</span>
  <span m='1750290'>specification</span> <span m='1750860'>of</span> <span m='1750950'>a</span>
  <span m='1751010'>signal</span> <span m='1752360'>or</span> <span m='1752510'>a</span>
  <span m='1752570'>system,</span> <span m='1753220'>either.</span> <span m='1754690'>So</span>
  <span m='1754790'>all</span> <span m='1754850'>the</span> <span m='1754940'>information</span>
  <span m='1755330'>is</span> <span m='1755420'>there.</span> <span m='1755690'>It's</span>
  <span m='1755810'>just</span> <span m='1756000'>that</span> <span m='1756140'>it's</span>
  <span m='1756230'>more</span> <span m='1756410'>apparent--</span> <span m='1758660'>some</span>
  <span m='1758930'>of</span> <span m='1758990'>the</span> <span m='1759050'>information</span>
  <span m='1759560'>is</span> <span m='1759680'>more</span> <span m='1759830'>apparent--</span>
  <span m='1760190'>in</span> <span m='1760310'>the</span> <span m='1760400'>Fourier</span>
  <span m='1760700'>representation.</span> </p><p><span m='1763910'>OK,</span> <span
  m='1764380'>second</span> <span m='1764650'>question,</span> <span m='1766060'>what</span>
  <span m='1766540'>if</span> <span m='1766840'>I</span> <span m='1767050'>stretched</span>
  <span m='1768280'>the</span> <span m='1768400'>time</span> <span m='1768700'>axis?</span>
  <span m='1769960'>x1</span> <span m='1770470'>was</span> <span m='1770680'>1</span>
  <span m='1770920'>between</span> <span m='1771250'>minus</span> <span m='1771520'>1</span>
  <span m='1771670'>and</span> <span m='1771760'>1.</span> <span m='1772060'>x2</span>
  <span m='1772720'>is</span> <span m='1772900'>1</span> <span m='1773230'>between</span>
  <span m='1773500'>minus</span> <span m='1773800'>2</span> <span m='1773890'>and</span>
  <span m='1773980'>2.</span> <span m='1775060'>So</span> <span m='1775210'>all</span>
  <span m='1775420'>I'm</span> <span m='1775510'>doing,</span> <span m='1775750'>stretching</span>
  <span m='1776560'>the</span> <span m='1776680'>axis.</span> <span m='1777460'>What</span>
  <span m='1777730'>happens</span> <span m='1778240'>to</span> <span m='1778390'>the</span>
  <span m='1778510'>Fourier</span> <span m='1778810'>transform?</span> <span m='1780760'>Look
  at your</span> <span m='1781240'>neighbor.</span> <span m='1781720'>Choose</span>
  <span m='1782000'>a</span> <span m='1782130'>number.</span> </p><p><span m='1783500'>[SIDE
  CONVERSATIONS]</span> </p><p></p><p><span m='1834520'>OK,</span> <span m='1835780'>which</span>
  <span m='1836210'>answer</span> <span m='1837140'>tells</span> <span m='1837470'>me</span>
  <span m='1837590'>what</span> <span m='1837740'>happens</span> <span m='1838100'>when</span>
  <span m='1838220'>I</span> <span m='1838340'>stretch</span> <span m='1838870'>time?</span>
  <span m='1839540'>So</span> <span m='1839660'>everybody</span> <span m='1839860'>raise</span>
  <span m='1840020'>your</span> <span m='1840140'>hand</span> <span m='1840500'>and</span>
  <span m='1840600'>tell</span> <span m='1840710'>me</span> <span m='1840860'>some</span>
  <span m='1841070'>number</span> <span m='1841310'>between</span> <span m='1841640'>0</span>
  <span m='1842030'>and</span> <span m='1842150'>5,</span> <span m='1843860'>1</span>
  <span m='1844010'>and</span> <span m='1844070'>5</span> <span m='1844310'>actually.</span>
  <span m='1846140'>OK,</span> <span m='1847970'>20%</span> <span m='1849710'>correct.</span>
  <span m='1850190'>S</span> </p><p><span m='1852890'>So</span> <span m='1854000'>what's</span>
  <span m='1854300'>going</span> <span m='1854420'>to</span> <span m='1854480'>happen?</span>
  <span m='1855180'>Well,</span> <span m='1856730'>it's</span> <span m='1856940'>pretty</span>
  <span m='1857270'>easy</span> <span m='1858170'>to</span> <span m='1858290'>simply</span>
  <span m='1859040'>do</span> <span m='1859250'>out</span> <span m='1859400'>the</span>
  <span m='1859510'>integral</span> <span m='1859790'>again.</span> <span m='1861440'>Right,</span>
  <span m='1861830'>so</span> <span m='1861980'>that's</span> <span m='1862250'>the</span>
  <span m='1862370'>sort</span> <span m='1862580'>of</span> <span m='1862700'>most</span>
  <span m='1862880'>primitive</span> <span m='1863270'>way</span> <span m='1863450'>you</span>
  <span m='1863570'>can</span> <span m='1863660'>think</span> <span m='1863840'>about</span>
  <span m='1864080'>it.</span> <span m='1865100'>If</span> <span m='1865250'>you</span>
  <span m='1865310'>simply</span> <span m='1865610'>run</span> <span m='1865790'>the</span>
  <span m='1865980'>integral,</span> <span m='1868690'>I've</span> <span m='1868810'>written</span>
  <span m='1869050'>it</span> <span m='1869170'>in</span> <span m='1869290'>a</span>
  <span m='1869350'>kind</span> <span m='1869590'>of</span> <span m='1869650'>funny</span>
  <span m='1870010'>way.</span> <span m='1870610'>Right?</span> </p><p><span m='1871750'>So</span>
  <span m='1871930'>a</span> <span m='1871960'>lot</span> <span m='1872080'>of</span>
  <span m='1872170'>you</span> <span m='1872260'>said</span> <span m='1872470'>one</span>
  <span m='1874650'>for</span> <span m='1874830'>the</span> <span m='1874980'>answer.</span>
  <span m='1878900'>This</span> <span m='1879010'>kind</span> <span m='1879220'>of</span>
  <span m='1879310'>looks</span> <span m='1879460'>like</span> <span m='1879640'>one.</span>
  <span m='1879970'>Why</span> <span m='1880120'>is</span> <span m='1880240'>that</span>
  <span m='1880330'>not</span> <span m='1880510'>one?</span> <span m='1882330'>That's</span>
  <span m='1882480'>actually</span> <span m='1882810'>three.</span> </p><p><span m='1886840'>Why</span>
  <span m='1887050'>do</span> <span m='1887170'>I</span> <span m='1887290'>like</span>
  <span m='1887500'>to</span> <span m='1887650'>write</span> <span m='1887920'>it</span>
  <span m='1888220'>as--</span> <span m='1890200'>instead</span> <span m='1890470'>of</span>
  <span m='1890530'>writing</span> <span m='1890800'>2</span> <span m='1890980'>since</span>
  <span m='1891250'>2</span> <span m='1891400'>omega over</span> <span m='1891740'>omega</span>
  <span m='1892180'>I</span> <span m='1892280'>like</span> <span m='1892450'>to</span>
  <span m='1892540'>write</span> <span m='1892720'>4</span> <span m='1892990'>signed</span>
  <span m='1893290'>2</span> <span m='1893470'>omega</span> <span m='1893770'>over</span>
  <span m='1893980'>2</span> <span m='1894100'>omega.</span> <span m='1894460'>Why</span>
  <span m='1894580'>do</span> <span m='1894700'>I</span> <span m='1894760'>like</span>
  <span m='1894940'>that?</span> <span m='1897070'>Because</span> <span m='1897460'>I'm</span>
  <span m='1897580'>completely</span> <span m='1898240'>random.</span> </p><p><span
  m='1901225'>AUDIENCE:</span> <span m='1901390'>Omega</span> <span m='1901555'>is</span>
  <span m='1901720'>the same</span> <span m='1902215'>that way?</span> </p><p><span
  m='1902710'>DENNIS FREEMAN:</span> <span m='1902875'>Excuse</span> <span m='1903040'>me.</span>
  </p><p><span m='1903205'>AUDIENCE:</span> <span m='1903452'>Omega</span> <span m='1903700'>can
  be</span> <span m='1904195'>the same--</span> <span m='1904690'>like you</span>
  <span m='1905185'>can have</span> <span m='1905680'>omega</span> <span m='1906175'>absorb</span>
  <span m='1906670'>the 2.</span> </p><p><span m='1907660'>DENNIS FREEMAN:</span>
  <span m='1907750'>That's</span> <span m='1907840'>kind</span> <span m='1908080'>of</span>
  <span m='1908140'>right.</span> <span m='1908730'>So</span> <span m='1909400'>can</span>
  <span m='1909550'>you</span> <span m='1909730'>unscramble</span> <span m='1910240'>the</span>
  <span m='1910360'>sentence</span> <span m='1910600'>slightly?</span> <span m='1913850'>What</span>
  <span m='1914360'>is</span> <span m='1914480'>more--</span> <span m='1914630'>yes.</span>
  </p><p><span m='1914900'>AUDIENCE:</span> <span m='1915111'>Aren't</span> <span
  m='1915323'>they the same</span> <span m='1915746'>form that</span> <span m='1916169'>we
  use?</span> </p><p><span m='1917440'>DENNIS FREEMAN:</span> <span m='1917520'>It's</span>
  <span m='1917600'>the</span> <span m='1917720'>same</span> <span m='1917960'>form</span>
  <span m='1918290'>in</span> <span m='1918380'>what</span> <span m='1918560'>sense?</span>
  <span m='1919700'>I</span> <span m='1919760'>mean</span> <span m='1919880'>what's</span>
  <span m='1920450'>the</span> <span m='1920570'>same</span> <span m='1920840'>about</span>
  <span m='1921080'>it?</span> <span m='1921140'>Yes.</span> <span m='1922330'>Yes.</span>
  </p><p><span m='1923152'>AUDIENCE:</span> <span m='1923398'>Like</span> <span m='1923644'>I
  thought</span> <span m='1924136'>I was</span> <span m='1924628'>going to say</span>
  <span m='1925612'>omega</span> <span m='1926104'>is near</span> <span m='1926596'>0</span>
  <span m='1927088'>when number two</span> <span m='1927580'>is 4.</span> </p><p><span
  m='1928080'>DENNIS FREEMAN:</span> <span m='1928325'>Correct,</span> <span m='1928770'>correct.</span>
  <span m='1929430'>If</span> <span m='1929580'>you</span> <span m='1929670'>think</span>
  <span m='1929880'>about</span> <span m='1930120'>what</span> <span m='1930330'>happens</span>
  <span m='1930780'>for</span> <span m='1931020'>omega</span> <span m='1931320'>near</span>
  <span m='1931530'>0,</span> <span m='1933830'>I've</span> <span m='1934070'>got</span>
  <span m='1934430'>the</span> <span m='1934580'>sine</span> <span m='1935000'>of</span>
  <span m='1935210'>2</span> <span m='1935480'>omega,</span> <span m='1935830'>which
  is--</span> <span m='1939450'>what's</span> <span m='1939630'>the</span> <span m='1939720'>sine</span>
  <span m='1939930'>of</span> <span m='1940020'>2</span> <span m='1940140'>omega</span>
  <span m='1940400'>when</span> <span m='1940500'>you</span> <span m='1940560'>make</span>
  <span m='1940710'>it</span> <span m='1940860'>0?</span> <span m='1942540'>0.</span>
  <span m='1943140'>So I have</span> <span m='1943410'>0</span> <span m='1943700'>over</span>
  <span m='1944150'>0.</span> <span m='1944580'>Bad.</span> <span m='1946020'>So</span>
  <span m='1946140'>what</span> <span m='1946230'>do</span> <span m='1946290'>I</span>
  <span m='1946380'>do?</span> <span m='1949980'>L'Hospital.</span> </p><p><span m='1951050'>So</span>
  <span m='1951200'>if</span> <span m='1951290'>I</span> <span m='1951380'>do</span>
  <span m='1951530'>L'Hospital's</span> <span m='1952160'>rule,</span> <span m='1952760'>then</span>
  <span m='1953000'>I</span> <span m='1953120'>can</span> <span m='1953330'>make</span>
  <span m='1953630'>this</span> <span m='1953810'>thing</span> <span m='1954020'>look</span>
  <span m='1954170'>like</span> <span m='1954410'>one.</span> <span m='1955490'>And</span>
  <span m='1955580'>if</span> <span m='1955730'>I</span> <span m='1955820'>write</span>
  <span m='1956090'>it</span> <span m='1956210'>in</span> <span m='1956330'>the</span>
  <span m='1956420'>form</span> <span m='1956750'>sine</span> <span m='1957150'>2</span>
  <span m='1957440'>omega</span> <span m='1957770'>over</span> <span m='1957980'>2</span>
  <span m='1958190'>omega,</span> <span m='1959510'>that</span> <span m='1960170'>has</span>
  <span m='1960380'>a</span> <span m='1960440'>value</span> <span m='1960890'>near</span>
  <span m='1961070'>0</span> <span m='1961460'>that</span> <span m='1961580'>approaches</span>
  <span m='1962030'>1.</span> <span m='1963350'>So</span> <span m='1963500'>the</span>
  <span m='1963680'>amplitude</span> <span m='1964160'>is</span> <span m='1964280'>4.</span>
  <span m='1965600'>So</span> <span m='1965750'>that's</span> <span m='1965900'>a</span>
  <span m='1965960'>way</span> <span m='1966140'>of</span> <span m='1966230'>separating</span>
  <span m='1966740'>out</span> <span m='1966890'>the</span> <span m='1966980'>part</span>
  <span m='1967280'>that's</span> <span m='1968630'>unity</span> <span m='1969110'>amplitude</span>
  <span m='1969680'>from</span> <span m='1969860'>the</span> <span m='1969950'>part</span>
  <span m='1970250'>that</span> <span m='1970400'>is</span> <span m='1970550'>the</span>
  <span m='1970640'>constant</span> <span m='1971030'>that</span> <span m='1971120'>multiplies</span>
  <span m='1971630'>the</span> <span m='1971750'>amplitude.</span> </p><p><span m='1972750'>So</span>
  <span m='1972770'>the</span> <span m='1972920'>amplitude</span> <span m='1973400'>is</span>
  <span m='1973560'>4.</span> <span m='1975230'>And</span> <span m='1975710'>frequency,</span>
  <span m='1976370'>which</span> <span m='1976580'>had</span> <span m='1976820'>been</span>
  <span m='1977030'>pi,</span> <span m='1977870'>moves</span> <span m='1978110'>to</span>
  <span m='1978230'>pi</span> <span m='1978440'>over</span> <span m='1978650'>2.</span>
  <span m='1979790'>So</span> <span m='1979940'>the</span> <span m='1980030'>point</span>
  <span m='1980330'>is</span> <span m='1980570'>that--</span> <span m='1982660'>so</span>
  <span m='1982910'>the</span> <span m='1983030'>answer</span> <span m='1983240'>is</span>
  <span m='1983330'>number</span> <span m='1983560'>three.</span> <span m='1985210'>The</span>
  <span m='1985870'>peak</span> <span m='1986350'>increases,</span> <span m='1988830'>and</span>
  <span m='1988990'>the</span> <span m='1989080'>frequency</span> <span m='1989590'>spacing</span>
  <span m='1990160'>decreases.</span> </p><p><span m='1991750'>But</span> <span m='1991960'>more</span>
  <span m='1992170'>generally,</span> <span m='1992620'>the</span> <span m='1992710'>point</span>
  <span m='1993040'>is</span> <span m='1993250'>that</span> <span m='1993400'>if</span>
  <span m='1993550'>I</span> <span m='1993670'>stretched</span> <span m='1994330'>time,</span>
  <span m='1997650'>I</span> <span m='1997780'>compress</span> <span m='1998260'>frequency.</span>
  <span m='1999970'>But</span> <span m='2000110'>I</span> <span m='2000240'>compress</span>
  <span m='2000570'>frequency</span> <span m='2000960'>in</span> <span m='2001020'>a</span>
  <span m='2001080'>very</span> <span m='2001230'>special</span> <span m='2001530'>way.</span>
  <span m='2001740'>I</span> <span m='2001830'>compress</span> <span m='2002160'>frequency</span>
  <span m='2003030'>in</span> <span m='2003180'>an</span> <span m='2003390'>area-preserving</span>
  <span m='2006300'>way.</span> <span m='2008360'>That's</span> <span m='2008440'>why</span>
  <span m='2008710'>the</span> <span m='2008980'>peak</span> <span m='2009340'>popped</span>
  <span m='2009730'>up.</span> </p><p><span m='2012080'>So</span> <span m='2012640'>what</span>
  <span m='2012910'>I'd</span> <span m='2013000'>like</span> <span m='2013150'>to</span>
  <span m='2013240'>do</span> <span m='2013360'>is</span> <span m='2013450'>think</span>
  <span m='2013600'>about</span> <span m='2013780'>a</span> <span m='2013840'>general</span>
  <span m='2014230'>scaling</span> <span m='2014680'>rule.</span> <span m='2014980'>If</span>
  <span m='2015100'>I</span> <span m='2015190'>wanted</span> <span m='2015580'>to</span>
  <span m='2015670'>think</span> <span m='2015940'>about</span> <span m='2016630'>scaling</span>
  <span m='2017620'>x1</span> <span m='2019000'>into</span> <span m='2019270'>x2,</span>
  <span m='2020050'>such</span> <span m='2020350'>that</span> <span m='2020530'>x2</span>
  <span m='2021550'>is</span> <span m='2021790'>a</span> <span m='2021850'>scaled</span>
  <span m='2022330'>version</span> <span m='2022900'>of</span> <span m='2023140'>time</span>
  <span m='2024400'>compared</span> <span m='2024730'>to</span> <span m='2024820'>x1,</span>
  <span m='2025340'>so</span> <span m='2025990'>if</span> <span m='2026140'>I</span>
  <span m='2026230'>wanted</span> <span m='2026510'>x2</span> <span m='2027070'>of</span>
  <span m='2027250'>t</span> <span m='2027610'>to</span> <span m='2027730'>be</span>
  <span m='2027850'>x1</span> <span m='2028260'>of</span> <span m='2028360'>at,</span>
  <span m='2029460'>and</span> <span m='2029590'>if</span> <span m='2029680'>I</span>
  <span m='2029740'>wanted</span> <span m='2030040'>to</span> <span m='2030130'>stretch</span>
  <span m='2031090'>x1</span> <span m='2031660'>to</span> <span m='2031780'>turn</span>
  <span m='2032020'>it</span> <span m='2032110'>into</span> <span m='2032290'>x2,</span>
  <span m='2033160'>should</span> <span m='2033340'>I</span> <span m='2033430'>make</span>
  <span m='2033670'>a1--</span> <span m='2034570'>should</span> <span m='2034720'>I</span>
  <span m='2034780'>make</span> <span m='2034990'>a</span> <span m='2035650'>bigger</span>
  <span m='2035950'>or</span> <span m='2036070'>less</span> <span m='2036280'>than</span>
  <span m='2036430'>1?</span> <span m='2041760'>I'm</span> <span m='2041850'>trying</span>
  <span m='2042060'>to</span> <span m='2042150'>generalize</span> <span m='2042720'>the</span>
  <span m='2042810'>result</span> <span m='2043110'>that</span> <span m='2043260'>I</span>
  <span m='2043350'>just</span> <span m='2043560'>did.</span> <span m='2043800'>Right?</span>
  </p><p><span m='2044880'>So</span> <span m='2045030'>I</span> <span m='2045120'>stretched</span>
  <span m='2045660'>x1</span> <span m='2046080'>into</span> <span m='2046230'>x2.</span>
  <span m='2046800'>And</span> <span m='2046890'>what</span> <span m='2047070'>I</span>
  <span m='2047130'>saw</span> <span m='2047400'>is</span> <span m='2047580'>that</span>
  <span m='2047700'>frequency</span> <span m='2048690'>shrunk,</span> <span m='2051000'>and</span>
  <span m='2051150'>amplitude</span> <span m='2051719'>went</span> <span m='2052020'>up.</span>
  <span m='2052770'>So</span> <span m='2052920'>now,</span> <span m='2053070'>I'm</span>
  <span m='2053190'>thinking</span> <span m='2053520'>about</span> <span m='2053760'>what</span>
  <span m='2053909'>would</span> <span m='2054060'>happen</span> <span m='2054420'>if</span>
  <span m='2054600'>I</span> <span m='2054690'>did</span> <span m='2054870'>that</span>
  <span m='2055080'>in</span> <span m='2055199'>general.</span> <span m='2056230'>If</span>
  <span m='2056280'>I</span> <span m='2056370'>took</span> <span m='2056580'>x1,</span>
  <span m='2057150'>and</span> <span m='2057239'>I</span> <span m='2057360'>stretched</span>
  <span m='2058139'>it</span> <span m='2059219'>by</span> <span m='2059429'>setting</span>
  <span m='2059850'>x2</span> <span m='2060540'>equal</span> <span m='2060870'>to</span>
  <span m='2060960'>x1</span> <span m='2061380'>of</span> <span m='2061469'>at,</span>
  <span m='2063000'>would</span> <span m='2063150'>I</span> <span m='2063239'>want</span>
  <span m='2063750'>a</span> <span m='2064350'>to</span> <span m='2064530'>be</span>
  <span m='2064710'>bigger</span> <span m='2065040'>or</span> <span m='2065219'>less</span>
  <span m='2065460'>than</span> <span m='2065770'>1</span> <span m='2066090'>if</span>
  <span m='2066270'>I</span> <span m='2066330'>want</span> <span m='2066510'>to</span>
  <span m='2066570'>stretch</span> <span m='2067199'>x1</span> <span m='2068219'>to</span>
  <span m='2068340'>turn</span> <span m='2068550'>it</span> <span m='2068639'>into</span>
  <span m='2068820'>x2?</span> </p><p><span m='2070324'>AUDIENCE:</span> <span m='2070478'>Less</span>
  <span m='2070632'>than</span> <span m='2070786'>1.</span> </p><p><span m='2071710'>DENNIS
  FREEMAN:</span> <span m='2071845'>Less</span> <span m='2071980'>than</span> <span
  m='2072159'>1</span> <span m='2073320'>because</span> <span m='2073580'>then</span>
  <span m='2073960'>the</span> <span m='2074110'>logic</span> <span m='2074530'>is</span>
  <span m='2074710'>that</span> <span m='2074920'>if</span> <span m='2075070'>I</span>
  <span m='2075159'>wanted,</span> <span m='2075730'>for</span> <span m='2075940'>example,</span>
  <span m='2077679'>x2</span> <span m='2078040'>of</span> <span m='2078230'>2</span>
  <span m='2078460'>to be</span> <span m='2078580'>x1</span> <span m='2078940'>of</span>
  <span m='2079030'>1,</span> <span m='2080050'>stretch</span> <span m='2080920'>x2--</span>
  <span m='2082199'>stretch</span> <span m='2082570'>x1,</span> <span m='2083050'>sorry,</span>
  <span m='2084310'>so</span> <span m='2084610'>that</span> <span m='2084969'>it's</span>
  <span m='2085270'>value</span> <span m='2086020'>x2</span> <span m='2087090'>at</span>
  <span m='2087280'>the</span> <span m='2087400'>position</span> <span m='2087909'>2</span>
  <span m='2088690'>is</span> <span m='2088870'>the</span> <span m='2088960'>same</span>
  <span m='2089230'>as</span> <span m='2089380'>the</span> <span m='2089530'>original</span>
  <span m='2090040'>function</span> <span m='2090460'>x1</span> <span m='2091000'>at</span>
  <span m='2091090'>1.</span> <span m='2093230'>If</span> <span m='2093409'>I</span>
  <span m='2093500'>stretched</span> <span m='2093949'>it,</span> <span m='2094429'>then</span>
  <span m='2094610'>I</span> <span m='2094670'>clearly</span> <span m='2095000'>have</span>
  <span m='2095120'>to</span> <span m='2095239'>have</span> <span m='2095449'>a</span>
  <span m='2095800'>equal</span> <span m='2095929'>to</span> <span m='2096050'>a</span>
  <span m='2096110'>half</span> <span m='2096469'>in</span> <span m='2096560'>that</span>
  <span m='2096710'>case.</span> <span m='2097070'>And</span> <span m='2097160'>in</span>
  <span m='2097280'>general,</span> <span m='2098420'>stretching</span> <span m='2098900'>would</span>
  <span m='2099020'>correspond</span> <span m='2099440'>to</span> <span m='2099500'>a</span>
  <span m='2099680'>less</span> <span m='2099920'>than</span> <span m='2100070'>1.</span>
  </p><p><span m='2100890'>And</span> <span m='2100910'>now,</span> <span m='2101030'>I</span>
  <span m='2101090'>can</span> <span m='2101240'>think</span> <span m='2101420'>about</span>
  <span m='2101660'>where</span> <span m='2101900'>that</span> <span m='2102170'>fits</span>
  <span m='2103010'>in</span> <span m='2103190'>the</span> <span m='2103380'>transform</span>
  <span m='2103880'>relationship.</span> <span m='2107300'>Think</span> <span m='2107410'>about</span>
  <span m='2107650'>finding</span> <span m='2108160'>the</span> <span m='2108280'>Fourier</span>
  <span m='2108660'>transform</span> <span m='2109260'>of</span> <span m='2109360'>x2,</span>
  <span m='2111990'>and</span> <span m='2112210'>substituting</span> <span m='2112930'>x1</span>
  <span m='2113330'>of</span> <span m='2113410'>at</span> <span m='2113920'>for</span>
  <span m='2114130'>x2,</span> <span m='2118350'>and</span> <span m='2118590'>then</span>
  <span m='2119550'>making</span> <span m='2120210'>this</span> <span m='2120510'>relationship</span>
  <span m='2121170'>look</span> <span m='2121350'>more</span> <span m='2121620'>like</span>
  <span m='2121830'>a</span> <span m='2121890'>Fourier</span> <span m='2122310'>transform.</span>
  <span m='2124450'>So</span> <span m='2124500'>I</span> <span m='2124590'>don't</span>
  <span m='2124860'>want</span> <span m='2125160'>the</span> <span m='2125340'>at</span>
  <span m='2125760'>to</span> <span m='2125850'>be</span> <span m='2126030'>here.</span>
  <span m='2126330'>I</span> <span m='2126420'>want</span> <span m='2126630'>function</span>
  <span m='2127080'>of</span> <span m='2127200'>t.</span> <span m='2128730'>So</span>
  <span m='2128850'>I</span> <span m='2128970'>can</span> <span m='2129480'>rewrite</span>
  <span m='2130470'>at</span> <span m='2130830'>as</span> <span m='2131190'>tau.</span>
  <span m='2134450'>Now,</span> <span m='2134720'>this</span> <span m='2134930'>looks</span>
  <span m='2135200'>like</span> <span m='2135750'>a</span> <span m='2136070'>Fourier</span>
  <span m='2136430'>transform</span> <span m='2137480'>except</span> <span m='2137780'>that</span>
  <span m='2137930'>I've</span> <span m='2138050'>changed</span> <span m='2138350'>all</span>
  <span m='2138440'>my</span> <span m='2138590'>t's</span> <span m='2138860'>to</span>
  <span m='2139010'>tau's.</span> </p><p><span m='2140720'>And</span> <span m='2140870'>the</span>
  <span m='2140930'>point</span> <span m='2141230'>is</span> <span m='2141470'>that</span>
  <span m='2141680'>that</span> <span m='2141860'>transformation</span> <span m='2142820'>of</span>
  <span m='2143360'>tau</span> <span m='2143660'>equals</span> <span m='2143960'>at</span>
  <span m='2144380'>shows</span> <span m='2144710'>up</span> <span m='2144890'>in</span>
  <span m='2145010'>two</span> <span m='2145250'>places.</span> <span m='2147200'>There's</span>
  <span m='2147500'>an</span> <span m='2147590'>explicit</span> <span m='2148130'>time</span>
  <span m='2148760'>here.</span> <span m='2150230'>And</span> <span m='2150410'>there's</span>
  <span m='2150590'>a</span> <span m='2150650'>time</span> <span m='2150980'>dependence</span>
  <span m='2151490'>in</span> <span m='2151610'>the</span> <span m='2151700'>dt.</span>
  <span m='2154830'>So</span> <span m='2155040'>the</span> <span m='2155170'>dt</span>
  <span m='2155730'>one</span> <span m='2155940'>is</span> <span m='2156090'>the</span>
  <span m='2156210'>one</span> <span m='2156420'>that</span> <span m='2156540'>gives</span>
  <span m='2156840'>me</span> <span m='2157050'>the</span> <span m='2157230'>shrinking</span>
  <span m='2157710'>and</span> <span m='2157830'>swelling</span> <span m='2158580'>of</span>
  <span m='2159060'>the</span> <span m='2159210'>axis.</span> <span m='2161280'>And</span>
  <span m='2162180'>the</span> <span m='2162900'>1</span> <span m='2163200'>over</span>
  <span m='2163440'>a</span> <span m='2163680'>from</span> <span m='2163890'>here</span>
  <span m='2165270'>is</span> <span m='2165480'>the</span> <span m='2165570'>one</span>
  <span m='2165780'>that</span> <span m='2165870'>gives</span> <span m='2166110'>me</span>
  <span m='2166320'>the</span> <span m='2166620'>changing</span> <span m='2167790'>amplitude.</span>
  </p><p><span m='2169410'>That's</span> <span m='2169620'>how</span> <span m='2169740'>you</span>
  <span m='2169890'>get</span> <span m='2170070'>the</span> <span m='2170190'>area-preserving</span>
  <span m='2171000'>property.</span> <span m='2172000'>However</span> <span m='2172260'>much</span>
  <span m='2172440'>it</span> <span m='2173130'>got</span> <span m='2174070'>compressed--</span>
  <span m='2174600'>however</span> <span m='2174990'>much</span> <span m='2175170'>it</span>
  <span m='2175290'>stretched</span> <span m='2175800'>in</span> <span m='2176010'>time</span>
  <span m='2176490'>so</span> <span m='2176700'>that</span> <span m='2176880'>it</span>
  <span m='2176970'>became</span> <span m='2177480'>compressed</span> <span m='2178110'>in</span>
  <span m='2178230'>frequency,</span> <span m='2179490'>whatever</span> <span m='2179820'>the</span>
  <span m='2179940'>factor</span> <span m='2180290'>is</span> <span m='2180520'>that</span>
  <span m='2180730'>compressed it</span> <span m='2181110'>in</span> <span m='2181200'>frequency,</span>
  <span m='2181710'>it</span> <span m='2181830'>also</span> <span m='2182250'>makes,</span>
  <span m='2182520'>by</span> <span m='2182700'>the</span> <span m='2182790'>same</span>
  <span m='2183030'>factor,</span> <span m='2183810'>it</span> <span m='2183930'>makes</span>
  <span m='2184140'>it</span> <span m='2184200'>taller.</span> <span m='2187030'>We'd</span>
  <span m='2187150'>like</span> <span m='2187300'>to</span> <span m='2187390'>build</span>
  <span m='2187630'>up</span> <span m='2187750'>intuition</span> <span m='2188230'>for</span>
  <span m='2188380'>how</span> <span m='2188530'>the</span> <span m='2188620'>Fourier</span>
  <span m='2188890'>transform</span> <span m='2189370'>works.</span> <span m='2189580'>That's</span>
  <span m='2189730'>the</span> <span m='2189790'>reason</span> <span m='2190060'>for</span>
  <span m='2190210'>doing</span> <span m='2190480'>these</span> <span m='2190690'>kinds</span>
  <span m='2190990'>of</span> <span m='2191140'>properties.</span> </p><p><span m='2194820'>So</span>
  <span m='2194900'>now,</span> <span m='2195890'>there's</span> <span m='2196130'>another</span>
  <span m='2196460'>way</span> <span m='2196640'>of</span> <span m='2196760'>thinking</span>
  <span m='2197120'>about</span> <span m='2197360'>that</span> <span m='2197570'>same</span>
  <span m='2197930'>thing</span> <span m='2198680'>by</span> <span m='2198800'>thinking</span>
  <span m='2199070'>about</span> <span m='2199910'>what</span> <span m='2200120'>we</span>
  <span m='2200240'>call</span> <span m='2200430'>the</span> <span m='2200510'>moment</span>
  <span m='2201180'>theorems.</span> <span m='2205730'>Here</span> <span m='2206420'>what</span>
  <span m='2206600'>we</span> <span m='2206750'>think</span> <span m='2206930'>about</span>
  <span m='2207260'>is</span> <span m='2207470'>what</span> <span m='2207650'>would</span>
  <span m='2207800'>happen</span> <span m='2208160'>if</span> <span m='2208310'>we</span>
  <span m='2208490'>evaluated</span> <span m='2208970'>the</span> <span m='2209090'>Fourier</span>
  <span m='2209420'>transform</span> <span m='2209950'>at</span> <span m='2210030'>omega</span>
  <span m='2210270'>equals</span> <span m='2210550'>0.</span> <span m='2212610'>Well,</span>
  <span m='2212880'>omega</span> <span m='2212950'>equals</span> <span m='2213310'>0</span>
  <span m='2214840'>is</span> <span m='2214990'>associated</span> <span m='2215500'>with</span>
  <span m='2215650'>a</span> <span m='2215730'>particularly</span> <span m='2216400'>simple</span>
  <span m='2218260'>complex</span> <span m='2218830'>exponential.</span> <span m='2220780'>If</span>
  <span m='2220990'>the</span> <span m='2221080'>frequency</span> <span m='2221620'>is</span>
  <span m='2221710'>0,</span> <span m='2222180'>e to</span> <span m='2222430'>the</span>
  <span m='2222570'>j0</span> <span m='2223150'>t</span> <span m='2223390'>is</span>
  <span m='2223540'>1.</span> </p><p><span m='2226560'>So</span> <span m='2226740'>what</span>
  <span m='2226890'>you</span> <span m='2227010'>see</span> <span m='2227400'>is</span>
  <span m='2227610'>that</span> <span m='2228390'>the</span> <span m='2228810'>value</span>
  <span m='2229260'>of</span> <span m='2229320'>the</span> <span m='2229430'>Fourier</span>
  <span m='2229830'>transform</span> <span m='2230490'>at</span> <span m='2230640'>omega</span>
  <span m='2230960'>equals</span> <span m='2231290'>0</span> <span m='2231660'>is</span>
  <span m='2231870'>the</span> <span m='2232020'>area</span> <span m='2232590'>under</span>
  <span m='2232860'>the</span> <span m='2232980'>curve.</span> <span m='2237200'>So</span>
  <span m='2237250'>the</span> <span m='2237400'>idea</span> <span m='2237760'>then</span>
  <span m='2238120'>is</span> <span m='2238510'>that</span> <span m='2239710'>if</span>
  <span m='2240010'>I</span> <span m='2240130'>took</span> <span m='2240640'>an</span>
  <span m='2240790'>x</span> <span m='2241000'>of</span> <span m='2241120'>t,</span>
  <span m='2241600'>which</span> <span m='2241810'>was</span> <span m='2242050'>x1,</span>
  <span m='2242740'>which</span> <span m='2242920'>was</span> <span m='2243100'>1</span>
  <span m='2243370'>between</span> <span m='2243850'>minus</span> <span m='2244180'>1</span>
  <span m='2244390'>and</span> <span m='2244480'>1,</span> <span m='2245270'>there's</span>
  <span m='2245320'>an</span> <span m='2245410'>area</span> <span m='2245770'>of</span>
  <span m='2245980'>2.</span> <span m='2246790'>And</span> <span m='2246910'>that's</span>
  <span m='2247090'>a</span> <span m='2247150'>way</span> <span m='2247330'>of</span>
  <span m='2247420'>directly</span> <span m='2247840'>saying,</span> <span m='2248140'>well,</span>
  <span m='2248300'>the</span> <span m='2248380'>Fourier</span> <span m='2248590'>transform</span>
  <span m='2248990'>at</span> <span m='2249060'>0</span> <span m='2249520'>better</span>
  <span m='2249760'>be</span> <span m='2249880'>2.</span> </p><p><span m='2252790'>And</span>
  <span m='2252950'>the</span> <span m='2253070'>intuitive</span> <span m='2253610'>thing</span>
  <span m='2253820'>that</span> <span m='2253910'>you're</span> <span m='2254030'>supposed</span>
  <span m='2254270'>to</span> <span m='2254330'>take</span> <span m='2254510'>away</span>
  <span m='2254720'>from</span> <span m='2254900'>that</span> <span m='2255380'>is</span>
  <span m='2255590'>when</span> <span m='2255710'>you</span> <span m='2255800'>look</span>
  <span m='2255950'>at</span> <span m='2256040'>a</span> <span m='2256100'>Fourier</span>
  <span m='2256370'>transform,</span> <span m='2257690'>the</span> <span m='2257780'>value</span>
  <span m='2258140'>at</span> <span m='2258200'>0</span> <span m='2258620'>is</span>
  <span m='2258770'>the</span> <span m='2258860'>dc.</span> <span m='2260450'>How</span>
  <span m='2260840'>much</span> <span m='2261320'>constant</span> <span m='2262490'>is</span>
  <span m='2262760'>there</span> <span m='2263630'>in</span> <span m='2263780'>that</span>
  <span m='2264020'>signal?</span> </p><p><span m='2266500'>So</span> <span m='2266710'>there's</span>
  <span m='2266950'>a</span> <span m='2267010'>very</span> <span m='2267370'>explicit</span>
  <span m='2267850'>representation</span> <span m='2268660'>for</span> <span m='2269470'>the</span>
  <span m='2269590'>frequency</span> <span m='2270220'>content.</span> <span m='2270700'>I</span>
  <span m='2270760'>mean</span> <span m='2270910'>that's</span> <span m='2271060'>what</span>
  <span m='2271180'>the</span> <span m='2271240'>Fourier</span> <span m='2271450'>transform</span>
  <span m='2271800'>is</span> <span m='2271900'>all</span> <span m='2272020'>about.</span>
  <span m='2272770'>And</span> <span m='2272890'>in</span> <span m='2272980'>particular,</span>
  <span m='2273490'>the</span> <span m='2273640'>zero</span> <span m='2274000'>frequency</span>
  <span m='2274480'>is</span> <span m='2274690'>dc.</span> <span m='2275200'>It's</span>
  <span m='2275350'>the</span> <span m='2275530'>average</span> <span m='2275980'>value.</span>
  </p><p><span m='2278770'>That</span> <span m='2278980'>kind</span> <span m='2279340'>of</span>
  <span m='2279430'>a</span> <span m='2279490'>relationship</span> <span m='2280120'>works</span>
  <span m='2280360'>both</span> <span m='2280630'>ways.</span> <span m='2281870'>If</span>
  <span m='2281950'>you</span> <span m='2282070'>were</span> <span m='2282190'>to</span>
  <span m='2282340'>use</span> <span m='2283030'>the</span> <span m='2284320'>synthesis</span>
  <span m='2284830'>formula</span> <span m='2286150'>and</span> <span m='2286360'>think</span>
  <span m='2286570'>about</span> <span m='2286810'>how</span> <span m='2286960'>do</span>
  <span m='2287050'>you</span> <span m='2287170'>synthesize</span> <span m='2287830'>x
  of</span> <span m='2288190'>0,</span> <span m='2291770'>well,</span> <span m='2292010'>it's</span>
  <span m='2292160'>the</span> <span m='2292220'>same</span> <span m='2292460'>sort</span>
  <span m='2292670'>of</span> <span m='2292730'>thing</span> <span m='2292940'>except</span>
  <span m='2293210'>now</span> <span m='2293450'>the</span> <span m='2293570'>t</span>
  <span m='2293960'>is</span> <span m='2294060'>0</span> <span m='2294380'>instead</span>
  <span m='2294680'>of</span> <span m='2294740'>the</span> <span m='2294860'>omega</span>
  <span m='2295130'>being</span> <span m='2295370'>0.</span> <span m='2297050'>And</span>
  <span m='2297200'>what</span> <span m='2297350'>we</span> <span m='2297560'>get</span>
  <span m='2298130'>is</span> <span m='2298310'>1</span> <span m='2298520'>over</span>
  <span m='2298740'>2pi</span> <span m='2299300'>times</span> <span m='2299660'>the</span>
  <span m='2299840'>area</span> <span m='2302030'>under</span> <span m='2302240'>the</span>
  <span m='2302340'>transform.</span> </p><p><span m='2305170'>So</span> <span m='2305220'>what</span>
  <span m='2305400'>that</span> <span m='2305550'>says</span> <span m='2305910'>is</span>
  <span m='2307230'>whatever</span> <span m='2307680'>is</span> <span m='2307830'>going</span>
  <span m='2308100'>on</span> <span m='2308310'>over</span> <span m='2308520'>in</span>
  <span m='2308610'>this</span> <span m='2308790'>wiggly</span> <span m='2308970'>thing,</span>
  <span m='2310200'>the</span> <span m='2310380'>net</span> <span m='2310770'>area,</span>
  <span m='2311220'>the</span> <span m='2311370'>average</span> <span m='2311730'>value,</span>
  <span m='2313800'>divided</span> <span m='2314280'>by</span> <span m='2314490'>2pi</span>
  <span m='2315180'>has</span> <span m='2315420'>to</span> <span m='2315540'>equal</span>
  <span m='2315870'>the</span> <span m='2315960'>value</span> <span m='2316350'>at</span>
  <span m='2316440'>x1</span> <span m='2316890'>of 0.</span> <span m='2318690'>x1</span>
  <span m='2318770'>of</span> <span m='2318900'>0</span> <span m='2319170'>is</span>
  <span m='2319290'>clearly</span> <span m='2319590'>1.</span> <span m='2321540'>So</span>
  <span m='2321690'>that</span> <span m='2321900'>means</span> <span m='2322470'>the</span>
  <span m='2322620'>area</span> <span m='2322980'>under</span> <span m='2323220'>this</span>
  <span m='2323400'>thing</span> <span m='2323580'>must</span> <span m='2323760'>be</span>
  <span m='2323850'>2pi.</span> </p><p><span m='2326370'>That</span> <span m='2326520'>wasn't</span>
  <span m='2326820'>particularly</span> <span m='2327480'>clear.</span> <span m='2328050'>I</span>
  <span m='2328110'>mean</span> <span m='2328290'>I</span> <span m='2328350'>don't</span>
  <span m='2328530'>know</span> <span m='2328800'>automatically</span> <span m='2329400'>the</span>
  <span m='2329580'>area</span> <span m='2329880'>under</span> <span m='2330090'>that</span>
  <span m='2330300'>curve.</span> <span m='2331140'>But</span> <span m='2331320'>that's</span>
  <span m='2331500'>such</span> <span m='2331710'>a</span> <span m='2331770'>frequently</span>
  <span m='2332340'>recurring</span> <span m='2332820'>thing</span> <span m='2333840'>that</span>
  <span m='2334470'>it's</span> <span m='2334710'>useful</span> <span m='2335070'>to</span>
  <span m='2335220'>notice</span> <span m='2335970'>that</span> <span m='2336660'>the</span>
  <span m='2336840'>area</span> <span m='2337350'>under</span> <span m='2337650'>this</span>
  <span m='2337890'>funny</span> <span m='2338250'>curve</span> <span m='2339240'>happens</span>
  <span m='2339630'>to</span> <span m='2339750'>be</span> <span m='2339900'>precisely</span>
  <span m='2340530'>the</span> <span m='2340680'>area</span> <span m='2341100'>of</span>
  <span m='2341220'>this</span> <span m='2341430'>inscribed</span> <span m='2341910'>triangle.</span>
  <span m='2344870'>So</span> <span m='2345440'>the</span> <span m='2345560'>height</span>
  <span m='2345770'>of</span> <span m='2345830'>the</span> <span m='2345920'>triangle</span>
  <span m='2346370'>is</span> <span m='2346490'>2.</span> <span m='2346910'>Half</span>
  <span m='2347270'>the</span> <span m='2347510'>base</span> <span m='2348020'>is</span>
  <span m='2348670'>pi.</span> <span m='2350300'>So</span> <span m='2350480'>the</span>
  <span m='2350660'>area</span> <span m='2351050'>is</span> <span m='2351260'>2pi.</span>
  </p><p><span m='2354080'>I'm</span> <span m='2354290'>sure</span> <span m='2355190'>some</span>
  <span m='2355640'>Greek</span> <span m='2357470'>knew this.</span> <span m='2360400'>But</span>
  <span m='2360640'>I</span> <span m='2360730'>don't.</span> <span m='2361390'>So</span>
  <span m='2361540'>if</span> <span m='2361630'>somebody</span> <span m='2362050'>can</span>
  <span m='2362200'>think</span> <span m='2362410'>of</span> <span m='2362470'>a</span>
  <span m='2362560'>way</span> <span m='2362800'>to</span> <span m='2362950'>derive</span>
  <span m='2363340'>that</span> <span m='2363610'>answer</span> <span m='2364300'>without</span>
  <span m='2364660'>using</span> <span m='2364960'>Fourier</span> <span m='2365260'>transforms--</span>
  <span m='2365760'>I</span> <span m='2365800'>can</span> <span m='2365890'>do it</span>
  <span m='2366010'>with</span> <span m='2366130'>Fourier</span> <span m='2366400'>transforms.</span>
  <span m='2367630'>And</span> <span m='2367750'>I</span> <span m='2367840'>can</span>
  <span m='2367960'>look</span> <span m='2368080'>it</span> <span m='2368170'>up</span>
  <span m='2368260'>in</span> <span m='2368380'>books</span> <span m='2370330'>where</span>
  <span m='2370480'>the</span> <span m='2370600'>authors</span> <span m='2370990'>also</span>
  <span m='2371350'>use</span> <span m='2371580'>Fourier</span> <span m='2371810'>transforms.</span>
  </p><p><span m='2372940'>But</span> <span m='2373090'>I'm</span> <span m='2373210'>sure</span>
  <span m='2373420'>some</span> <span m='2373630'>ancient</span> <span m='2373990'>Greek</span>
  <span m='2374350'>can</span> <span m='2374560'>do</span> <span m='2374740'>this.</span>
  <span m='2376030'>So</span> <span m='2376150'>the</span> <span m='2376240'>question</span>
  <span m='2376630'>is</span> <span m='2376810'>if</span> <span m='2376930'>anybody</span>
  <span m='2377260'>can</span> <span m='2377410'>figure</span> <span m='2377710'>out</span>
  <span m='2378160'>how</span> <span m='2378400'>the</span> <span m='2378550'>ancient</span>
  <span m='2378910'>Greeks</span> <span m='2379300'>would</span> <span m='2379420'>have</span>
  <span m='2379510'>come</span> <span m='2379660'>to</span> <span m='2379750'>that</span>
  <span m='2379870'>conclusion,</span> <span m='2381320'>I</span> <span m='2381340'>would</span>
  <span m='2381520'>be</span> <span m='2381610'>very</span> <span m='2381850'>interested</span>
  <span m='2382210'>to</span> <span m='2382300'>know.</span> <span m='2383430'>Does</span>
  <span m='2383890'>everybody</span> <span m='2384230'>get--</span> <span m='2384970'>so</span>
  <span m='2385930'>areas</span> <span m='2386350'>of</span> <span m='2386440'>inscribed</span>
  <span m='2387100'>whatevers,</span> <span m='2387670'>right,</span> <span m='2387850'>that's</span>
  <span m='2388030'>what</span> <span m='2388150'>they</span> <span m='2388300'>did.</span>
  <span m='2388660'>Right?</span> </p><p><span m='2389170'>So</span> <span m='2389680'>I</span>
  <span m='2389830'>would</span> <span m='2390010'>like</span> <span m='2390160'>to</span>
  <span m='2390310'>know</span> <span m='2390580'>how</span> <span m='2390820'>to</span>
  <span m='2391030'>get</span> <span m='2391780'>the</span> <span m='2391930'>fact</span>
  <span m='2392410'>that</span> <span m='2392650'>the</span> <span m='2392860'>area</span>
  <span m='2393730'>under</span> <span m='2393970'>this</span> <span m='2394210'>wiggly</span>
  <span m='2394600'>function</span> <span m='2395080'>2</span> <span m='2395320'>sine</span>
  <span m='2395620'>omega</span> <span m='2395950'>over</span> <span m='2396250'>omega</span>
  <span m='2396610'>is</span> <span m='2396820'>2pi</span> <span m='2397780'>without</span>
  <span m='2398170'>knowing</span> <span m='2398500'>Fourier</span> <span m='2398710'>transforms.</span>
  <span m='2400450'>So</span> <span m='2400570'>that's</span> <span m='2400810'>an</span>
  <span m='2400930'>open</span> <span m='2401260'>challenge.</span> <span m='2401790'>So</span>
  <span m='2402220'>try</span> <span m='2402400'>to</span> <span m='2402490'>figure</span>
  <span m='2402760'>out</span> <span m='2403270'>how</span> <span m='2403510'>to</span>
  <span m='2403600'>prove</span> <span m='2403840'>that</span> <span m='2404080'>without</span>
  <span m='2404350'>using</span> <span m='2404620'>Fourier</span> <span m='2404890'>transforms.</span>
  </p><p><span m='2408310'>So</span> <span m='2408530'>if</span> <span m='2408590'>we</span>
  <span m='2408650'>use</span> <span m='2408880'>the</span> <span m='2409000'>moment</span>
  <span m='2409420'>idea,</span> <span m='2410680'>and</span> <span m='2410800'>we</span>
  <span m='2410920'>think</span> <span m='2411100'>about</span> <span m='2411280'>this</span>
  <span m='2411400'>scaling</span> <span m='2411910'>thing,</span> <span m='2413620'>we</span>
  <span m='2413770'>come</span> <span m='2413950'>up</span> <span m='2414070'>with</span>
  <span m='2414190'>a</span> <span m='2414250'>very</span> <span m='2414520'>interesting</span>
  <span m='2415600'>result</span> <span m='2416560'>that</span> <span m='2416890'>if</span>
  <span m='2417100'>you</span> <span m='2417250'>were</span> <span m='2417400'>to</span>
  <span m='2417550'>stretch</span> <span m='2418210'>x1,</span> <span m='2418930'>which</span>
  <span m='2419110'>had</span> <span m='2419260'>been</span> <span m='2419410'>1</span>
  <span m='2419590'>just</span> <span m='2419770'>between</span> <span m='2420220'>minus</span>
  <span m='2420520'>1</span> <span m='2420700'>and</span> <span m='2420790'>1,</span>
  <span m='2421330'>to</span> <span m='2421450'>turn</span> <span m='2421630'>it</span>
  <span m='2421720'>into</span> <span m='2421900'>x2,</span> <span m='2422530'>which</span>
  <span m='2422740'>was</span> <span m='2422890'>1</span> <span m='2423100'>between</span>
  <span m='2423730'>minus</span> <span m='2424090'>2</span> <span m='2424270'>and</span>
  <span m='2424360'>2,</span> <span m='2424960'>and</span> <span m='2425080'>just</span>
  <span m='2425320'>keep</span> <span m='2425560'>stretching,</span> <span m='2427600'>what</span>
  <span m='2427720'>would</span> <span m='2427870'>happen?</span> <span m='2430250'>Well,</span>
  <span m='2430450'>it</span> <span m='2430540'>gets</span> <span m='2430720'>skinnier</span>
  <span m='2431200'>and</span> <span m='2431290'>skinnier</span> <span m='2431680'>and</span>
  <span m='2431770'>skinnier</span> <span m='2432130'>and</span> <span m='2432220'>skinnier.</span>
  <span m='2434150'>But</span> <span m='2434300'>in</span> <span m='2434420'>a</span>
  <span m='2434510'>very</span> <span m='2434810'>special</span> <span m='2435170'>way,</span>
  <span m='2435890'>the</span> <span m='2436070'>area</span> <span m='2436550'>is</span>
  <span m='2436820'>the</span> <span m='2436970'>same.</span> </p><p><span m='2437960'>Even</span>
  <span m='2438200'>though</span> <span m='2438290'>it</span> <span m='2438340'>got</span>
  <span m='2438500'>skinnier</span> <span m='2438890'>and</span> <span m='2438980'>skinnier</span>
  <span m='2439130'>and</span> <span m='2439360'>skinnier</span> <span m='2439520'>and</span>
  <span m='2439760'>skinnier,</span> <span m='2441350'>the</span> <span m='2441500'>area</span>
  <span m='2441890'>is</span> <span m='2442070'>the</span> <span m='2442190'>same.</span>
  <span m='2443030'>If</span> <span m='2443210'>you</span> <span m='2443360'>keep</span>
  <span m='2443630'>doing</span> <span m='2444020'>that,</span> <span m='2444470'>it</span>
  <span m='2444560'>turns</span> <span m='2444800'>into</span> <span m='2444980'>an</span>
  <span m='2445110'>impulse.</span> <span m='2447720'>Well,</span> <span m='2447960'>that's</span>
  <span m='2448230'>pretty</span> <span m='2448530'>interesting.</span> <span m='2450460'>That's</span>
  <span m='2450600'>an</span> <span m='2450720'>alternative</span> <span m='2451470'>way</span>
  <span m='2451800'>of</span> <span m='2451920'>deriving</span> <span m='2452430'>an</span>
  <span m='2452520'>impulse.</span> </p><p><span m='2452970'>An</span> <span m='2453060'>impulse,</span>
  <span m='2455150'>we</span> <span m='2455240'>think</span> <span m='2455390'>about</span>
  <span m='2455570'>an</span> <span m='2455680'>impulse</span> <span m='2455935'>as
  a</span> <span m='2456190'>generalized</span> <span m='2456710'>function.</span>
  <span m='2458120'>Any</span> <span m='2458420'>function</span> <span m='2458810'>that</span>
  <span m='2458900'>has</span> <span m='2459080'>the</span> <span m='2459170'>property</span>
  <span m='2460250'>that</span> <span m='2460790'>in</span> <span m='2461000'>some</span>
  <span m='2461270'>kind</span> <span m='2461540'>of</span> <span m='2461610'>a</span>
  <span m='2461680'>limit,</span> <span m='2462950'>the</span> <span m='2463160'>area</span>
  <span m='2464000'>shrinks</span> <span m='2464600'>towards</span> <span m='2464930'>0,</span>
  <span m='2466650'>but</span> <span m='2466820'>the</span> <span m='2466910'>area</span>
  <span m='2467180'>doesn't</span> <span m='2467450'>change,</span> <span m='2469310'>that</span>
  <span m='2470030'>turns</span> <span m='2470360'>into</span> <span m='2470810'>a</span>
  <span m='2470870'>delta</span> <span m='2471140'>function.</span> <span m='2471560'>That's</span>
  <span m='2471710'>a</span> <span m='2471770'>different</span> <span m='2472160'>way</span>
  <span m='2472430'>of</span> <span m='2472520'>thinking</span> <span m='2472880'>about</span>
  <span m='2473090'>the</span> <span m='2473180'>definition</span> <span m='2473630'>of</span>
  <span m='2473720'>a</span> <span m='2473750'>delta</span> <span m='2474050'>function.</span>
  </p><p><span m='2475140'>And</span> <span m='2475240'>so</span> <span m='2475280'>we</span>
  <span m='2475370'>just</span> <span m='2475550'>found</span> <span m='2475730'>something</span>
  <span m='2476030'>very</span> <span m='2476390'>interesting.</span> <span m='2477560'>The</span>
  <span m='2477890'>Fourier</span> <span m='2478520'>transform</span> <span m='2481050'>of</span>
  <span m='2481300'>the</span> <span m='2481450'>constant</span> <span m='2482110'>1</span>
  <span m='2483880'>seems</span> <span m='2484420'>to</span> <span m='2484570'>be</span>
  <span m='2485730'>a</span> <span m='2485830'>delta</span> <span m='2486130'>function</span>
  <span m='2486580'>as</span> <span m='2486820'>0</span> <span m='2487210'>of</span>
  <span m='2487450'>area</span> <span m='2487810'>2pi.</span> <span m='2488680'>Well,</span>
  <span m='2488830'>that's</span> <span m='2489010'>pretty</span> <span m='2489220'>interesting.</span>
  </p><p><span m='2490030'>What's</span> <span m='2490230'>the</span> <span m='2490480'>Laplace</span>
  <span m='2490580'>transform</span> <span m='2490910'>of</span> <span m='2491020'>1?</span>
  <span m='2498450'>Too</span> <span m='2498630'>shocking.</span> <span m='2499950'>What's</span>
  <span m='2500190'>the</span> <span m='2500310'>Laplace</span> <span m='2500700'>transform</span>
  <span m='2501210'>of</span> <span m='2501480'>1?</span> </p><p><span m='2504738'>AUDIENCE:</span>
  <span m='2504895'>It's</span> <span m='2505052'>a</span> <span m='2505211'>delta
  function.</span> </p><p><span m='2506160'>DENNIS FREEMAN:</span> <span m='2506310'>Delta</span>
  <span m='2506460'>function.</span> <span m='2508970'>What's</span> <span m='2509170'>the</span>
  <span m='2509230'>Laplace</span> <span m='2509620'>transform</span> <span m='2510040'>of
  1?</span> <span m='2510260'>And</span> <span m='2510940'>So</span> <span m='2511150'>Laplace</span>
  <span m='2511390'>transform,</span> <span m='2511740'>right,</span> <span m='2512260'>so</span>
  <span m='2512410'>x of</span> <span m='2512705'>s,</span> <span m='2514980'>integral</span>
  <span m='2515920'>1e</span> <span m='2517425'>to</span> <span m='2517780'>the</span>
  <span m='2517880'>minus</span> <span m='2518240'>st</span> <span m='2518550'>dt.</span>
  <span m='2520240'>What's</span> <span m='2520450'>the</span> <span m='2520620'>Laplace</span>
  <span m='2520900'>transform</span> <span m='2521500'>of</span> <span m='2521800'>1?</span>
  </p><p><span m='2532300'>AUDIENCE:</span> <span m='2532466'>1</span> <span m='2532632'>over</span>
  <span m='2532798'>s.</span> </p><p><span m='2533310'>DENNIS FREEMAN:</span> <span
  m='2533520'>1 over</span> <span m='2533730'>s.</span> <span m='2534180'>How</span>
  <span m='2534360'>about</span> <span m='2534450'>1</span> <span m='2534640'>over</span>
  <span m='2534800'>s?</span> <span m='2538990'>Yes?</span> <span m='2541420'>No?</span>
  <span m='2545880'>1 over</span> <span m='2546150'>s--</span> <span m='2546420'>yes.</span>
  <span m='2548000'>1 over</span> <span m='2548150'>s--</span> <span m='2548470'>no.</span>
  <span m='2551380'>Me.</span> <span m='2552710'>1 over s,</span> <span m='2553250'>no.</span>
  <span m='2554570'>Why</span> <span m='2554720'>not?</span> </p><p><span m='2557345'>AUDIENCE:</span>
  <span m='2557504'>You</span> <span m='2557663'>would</span> <span m='2557822'>just
  use</span> <span m='2558299'>the</span> <span m='2558776'>su</span> <span m='2559253'>of</span>
  <span m='2559730'>1</span> <span m='2560207'>u of t.</span> </p><p><span m='2561170'>DENNIS
  FREEMAN:</span> <span m='2561295'>It's</span> <span m='2561420'>1,</span> <span
  m='2561750'>yes.</span> <span m='2562500'>So</span> <span m='2563240'>the</span>
  <span m='2563650'>Laplace</span> <span m='2564060'>transform</span> <span m='2564570'>of</span>
  <span m='2564630'>u</span> <span m='2564840'>of</span> <span m='2564930'>t</span>
  <span m='2567520'>is</span> <span m='2568050'>1</span> <span m='2568290'>over</span>
  <span m='2568410'>s.</span> <span m='2568520'>Right?</span> <span m='2572130'>You</span>
  <span m='2572170'>remember</span> <span m='2572520'>there</span> <span m='2572640'>was</span>
  <span m='2572790'>a</span> <span m='2572820'>region</span> <span m='2573120'>of</span>
  <span m='2573240'>convergence</span> <span m='2573750'>associated</span> <span m='2574380'>with</span>
  <span m='2574620'>Laplace</span> <span m='2574980'>transforms.</span> <span m='2577080'>The</span>
  <span m='2577170'>region</span> <span m='2577440'>of</span> <span m='2577560'>convergence,</span>
  <span m='2578460'>we</span> <span m='2578610'>thought</span> <span m='2578820'>about</span>
  <span m='2579180'>like</span> <span m='2579810'>if</span> <span m='2579900'>you</span>
  <span m='2579960'>had</span> <span m='2580620'>a</span> <span m='2580740'>time</span>
  <span m='2580980'>function</span> <span m='2581370'>like</span> <span m='2582470'>u</span>
  <span m='2582870'>of</span> <span m='2583180'>t,</span> <span m='2586440'>then</span>
  <span m='2586590'>it</span> <span m='2586680'>would</span> <span m='2586830'>converge</span>
  <span m='2587400'>as</span> <span m='2587490'>long</span> <span m='2587710'>as</span>
  <span m='2587830'>you</span> <span m='2587940'>multiplied</span> <span m='2588510'>by</span>
  <span m='2588660'>some</span> <span m='2589170'>factor</span> <span m='2590440'>that</span>
  <span m='2591420'>generally</span> <span m='2592470'>attenuated.</span> </p><p><span
  m='2595020'>So</span> <span m='2595170'>that</span> <span m='2595410'>bounded</span>
  <span m='2595890'>what</span> <span m='2596040'>kinds</span> <span m='2596370'>of</span>
  <span m='2596460'>s's</span> <span m='2596820'>worked.</span> <span m='2598050'>We</span>
  <span m='2598200'>needed</span> <span m='2598500'>the</span> <span m='2598620'>real</span>
  <span m='2598830'>part</span> <span m='2599100'>of</span> <span m='2599190'>s</span>
  <span m='2599370'>bigger</span> <span m='2599640'>than</span> <span m='2599820'>0.</span>
  <span m='2602340'>Because</span> <span m='2602640'>if</span> <span m='2602760'>the</span>
  <span m='2602850'>real</span> <span m='2603000'>part</span> <span m='2603240'>of</span>
  <span m='2603330'>s</span> <span m='2603510'>was</span> <span m='2604080'>the</span>
  <span m='2604230'>other</span> <span m='2604410'>way,</span> <span m='2605790'>the</span>
  <span m='2605970'>interval</span> <span m='2606330'>would</span> <span m='2606390'>diverge--</span>
  <span m='2607450'>bad.</span> <span m='2609180'>Right</span> <span m='2610020'>so</span>
  <span m='2610890'>we</span> <span m='2611100'>could</span> <span m='2611460'>find</span>
  <span m='2611800'>the</span> <span m='2611880'>Laplace</span> <span m='2612270'>transform</span>
  <span m='2612900'>of</span> <span m='2613090'>u</span> <span m='2613290'>of</span>
  <span m='2613410'>t--</span> <span m='2618630'>real</span> <span m='2618870'>part</span>
  <span m='2619080'>of</span> <span m='2619180'>s</span> <span m='2619350'>bigger</span>
  <span m='2619620'>than</span> <span m='2619740'>0.</span> </p><p><span m='2621600'>Or</span>
  <span m='2621780'>we</span> <span m='2621930'>could</span> <span m='2622050'>find</span>
  <span m='2622320'>the</span> <span m='2622410'>Laplace</span> <span m='2622800'>transform</span>
  <span m='2624300'>of</span> <span m='2624420'>a</span> <span m='2624480'>backward</span>
  <span m='2624960'>step.</span> <span m='2628130'>The</span> <span m='2628850'>region</span>
  <span m='2629210'>of</span> <span m='2629300'>convergence</span> <span m='2629810'>would</span>
  <span m='2629990'>flip.</span> <span m='2632000'>And</span> <span m='2632150'>we</span>
  <span m='2632270'>got</span> <span m='2632450'>a</span> <span m='2632510'>sign</span>
  <span m='2633790'>change.</span> </p><p><span m='2636770'>But</span> <span m='2637190'>the</span>
  <span m='2637565'>Laplace</span> <span m='2638360'>transform</span> <span m='2638690'>of</span>
  <span m='2638810'>1</span> <span m='2639020'>doesn't</span> <span m='2639360'>exist.</span>
  <span m='2642500'>There</span> <span m='2642680'>is</span> <span m='2642830'>no</span>
  <span m='2643130'>region</span> <span m='2643490'>of</span> <span m='2643580'>convergence</span>
  <span m='2644540'>for</span> <span m='2644880'>the</span> <span m='2645140'>function</span>
  <span m='2645620'>1.</span> <span m='2646940'>That's</span> <span m='2647180'>a</span>
  <span m='2647270'>big</span> <span m='2647480'>difference</span> <span m='2647870'>between</span>
  <span m='2648230'>Fourier</span> <span m='2648560'>and</span> <span m='2648800'>Laplace
  as</span> <span m='2649250'>well.</span> </p><p><span m='2650030'>Even</span> <span
  m='2650360'>though</span> <span m='2650600'>Fourier,</span> <span m='2651190'>is</span>
  <span m='2651350'>in</span> <span m='2651470'>some</span> <span m='2651800'>sense,</span>
  <span m='2652710'>a</span> <span m='2652810'>subset</span> <span m='2653120'>of</span>
  <span m='2653240'>Laplace,</span> <span m='2656300'>there</span> <span m='2656540'>are</span>
  <span m='2656690'>some</span> <span m='2657020'>signals</span> <span m='2657590'>that</span>
  <span m='2657710'>have</span> <span m='2657840'>Fourier</span> <span m='2658210'>transforms</span>
  <span m='2658730'>and</span> <span m='2658820'>not</span> <span m='2658970'>Laplace</span>
  <span m='2659330'>transforms,</span> <span m='2659810'>and</span> <span m='2659930'>so</span>
  <span m='2660410'>in</span> <span m='2660620'>that</span> <span m='2660920'>sense,</span>
  <span m='2661980'>Laplace</span> <span m='2662260'>is</span> <span m='2662540'>a</span>
  <span m='2662600'>subset</span> <span m='2663020'>of</span> <span m='2663220'>Fourier.</span>
  <span m='2664330'>So</span> <span m='2664400'>in</span> <span m='2664490'>fact,</span>
  <span m='2664800'>you</span> <span m='2664900'>better</span> <span m='2665000'>think</span>
  <span m='2665210'>of</span> <span m='2665300'>them</span> <span m='2665450'>as</span>
  <span m='2665600'>Venn</span> <span m='2667430'>diagrams</span> <span m='2668000'>that</span>
  <span m='2668090'>overlap.</span> <span m='2668720'>So</span> <span m='2669350'>there</span>
  <span m='2669470'>are</span> <span m='2669560'>some</span> <span m='2669800'>signals</span>
  <span m='2670160'>that</span> <span m='2670280'>have</span> <span m='2670490'>both,</span>
  <span m='2672470'>but</span> <span m='2672620'>there</span> <span m='2672800'>are</span>
  <span m='2672890'>some</span> <span m='2673130'>signals</span> <span m='2673640'>that</span>
  <span m='2673760'>have</span> <span m='2674180'>one</span> <span m='2674420'>and</span>
  <span m='2674510'>not</span> <span m='2674720'>the</span> <span m='2674840'>other.</span>
  </p><p><span m='2676880'>OK,</span> <span m='2677840'>so</span> <span m='2680930'>the</span>
  <span m='2681110'>final</span> <span m='2681620'>and</span> <span m='2681800'>maybe</span>
  <span m='2682370'>most</span> <span m='2682850'>important</span> <span m='2684710'>property</span>
  <span m='2685370'>of</span> <span m='2685640'>Laplace</span> <span m='2686030'>transforms</span>
  <span m='2687410'>is</span> <span m='2687620'>that</span> <span m='2687710'>they</span>
  <span m='2687830'>have</span> <span m='2688010'>a</span> <span m='2688130'>simple,</span>
  <span m='2689000'>inverse</span> <span m='2689630'>relationship.</span> <span m='2691660'>You</span>
  <span m='2691780'>may</span> <span m='2691930'>remember</span> <span m='2692410'>that</span>
  <span m='2692560'>I</span> <span m='2692680'>talked</span> <span m='2692980'>about</span>
  <span m='2693250'>there</span> <span m='2693370'>being</span> <span m='2693730'>an</span>
  <span m='2693820'>inverse</span> <span m='2694150'>relationship</span> <span m='2694720'>for</span>
  <span m='2694880'>Laplace.</span> <span m='2699100'>So</span> <span m='2699230'>you</span>
  <span m='2699350'>can</span> <span m='2699470'>think</span> <span m='2699620'>about</span>
  <span m='2700250'>x</span> <span m='2700490'>of</span> <span m='2700640'>t</span>
  <span m='2701660'>being</span> <span m='2701930'>1</span> <span m='2702140'>over</span>
  <span m='2702410'>j</span> <span m='2702800'>2pi,</span> <span m='2703500'>the</span>
  <span m='2703880'>integral</span> <span m='2704690'>over</span> <span m='2704930'>some</span>
  <span m='2705200'>sort</span> <span m='2705410'>of</span> <span m='2705500'>a</span>
  <span m='2705560'>contour</span> <span m='2706340'>of</span> <span m='2706590'>x</span>
  <span m='2706860'>of s</span> <span m='2708174'>e to</span> <span m='2708612'>the</span>
  <span m='2709050'>st</span> <span m='2709488'>ds.</span> <span m='2711400'>And</span>
  <span m='2711580'>I</span> <span m='2711680'>told</span> <span m='2711890'>you</span>
  <span m='2711980'>don't</span> <span m='2712160'>ever</span> <span m='2712340'>try</span>
  <span m='2712490'>to</span> <span m='2712580'>do</span> <span m='2712700'>that</span>
  <span m='2713240'>without</span> <span m='2713540'>going</span> <span m='2713840'>over</span>
  <span m='2714020'>to</span> <span m='2714110'>math</span> <span m='2714410'>and</span>
  <span m='2714500'>talking</span> <span m='2714890'>to</span> <span m='2715010'>those</span>
  <span m='2715250'>folks</span> <span m='2715550'>first.</span> <span m='2717710'>That's</span>
  <span m='2718100'>complicated.</span> </p><p><span m='2720170'>The</span> <span
  m='2720290'>interesting</span> <span m='2720680'>thing</span> <span m='2720860'>about</span>
  <span m='2721070'>this</span> <span m='2721250'>relationship</span> <span m='2722210'>is</span>
  <span m='2722420'>that</span> <span m='2722540'>it's</span> <span m='2722720'>really</span>
  <span m='2723260'>simple.</span> <span m='2725690'>So</span> <span m='2725840'>there's</span>
  <span m='2726020'>a</span> <span m='2726080'>very</span> <span m='2726410'>simple</span>
  <span m='2726800'>relationship</span> <span m='2728720'>between</span> <span m='2729080'>a</span>
  <span m='2729170'>Fourier</span> <span m='2729560'>transform</span> <span m='2731780'>and</span>
  <span m='2731990'>its</span> <span m='2732150'>inverse.</span> <span m='2733860'>OK,</span>
  <span m='2735170'>so</span> <span m='2735890'>I</span> <span m='2736160'>think</span>
  <span m='2736370'>I'll</span> <span m='2736490'>defer</span> <span m='2737060'>talking</span>
  <span m='2737540'>about</span> <span m='2737870'>that</span> <span m='2738380'>until</span>
  <span m='2738740'>next</span> <span m='2738980'>time,</span> <span m='2741840'>the</span>
  <span m='2741930'>reason</span> <span m='2742230'>being</span> <span m='2742710'>that</span>
  <span m='2743880'>I</span> <span m='2744000'>want</span> <span m='2744150'>to</span>
  <span m='2744300'>end</span> <span m='2744570'>a</span> <span m='2744630'>little</span>
  <span m='2744870'>earlier</span> <span m='2745200'>today.</span> <span m='2745690'>So</span>
  <span m='2745730'>I'll</span> <span m='2746160'>finish</span> <span m='2746620'>talking</span>
  <span m='2747030'>about</span> <span m='2747330'>the</span> <span m='2747420'>rest</span>
  <span m='2747630'>of</span> <span m='2747690'>the</span> <span m='2747810'>slides</span>
  <span m='2748890'>on</span> <span m='2749160'>the</span> <span m='2749250'>next</span>
  <span m='2749550'>lecture.</span> </p>
type: course
uid: 5fbda7f6030629109274f1988f447d39

---
None