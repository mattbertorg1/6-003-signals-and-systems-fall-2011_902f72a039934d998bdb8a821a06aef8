---
about_this_resource_text: <p><strong>Instructor:</strong> Dennis Freeman</p> <p><strong>Description:</strong>
  After reviewing concepts in discrete-time systems, the Z transform is introduced,
  connecting the unit sample response h[n] and the system function H(z). The lecture
  covers the Z transform's definition, properties, examples, and inverse transform.</p>
course_id: 6-003-signals-and-systems-fall-2011
embedded_media:
- id: Video-YouTube-Stream
  media_location: iI-ejO9hczw
  parent_uid: 400326ddbc2b7b0df39ad3a9eb7866cc
  title: Video-YouTube-Stream
  type: Video
  uid: 5a29df40e4c13717c452c67871a96ad6
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/iI-ejO9hczw/default.jpg
  parent_uid: 400326ddbc2b7b0df39ad3a9eb7866cc
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f97191c4ff3192c55ab404821242d1c2
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/lecture-5-z-transform/id602305810?i=132454033
  parent_uid: 400326ddbc2b7b0df39ad3a9eb7866cc
  title: Video-iTunes U-MP4
  type: Video
  uid: cf923f7f1d820b677dc6c8f012a65a0e
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.003F11/MIT6_003F11_lec05_300k.mp4
  parent_uid: 400326ddbc2b7b0df39ad3a9eb7866cc
  title: Video-Internet Archive-MP4
  type: Video
  uid: 6783605ceb8768a76c79dde3d2d245ca
- id: 3Play-3PlayYouTubeid-MP4
  media_location: iI-ejO9hczw
  parent_uid: 400326ddbc2b7b0df39ad3a9eb7866cc
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 3f38d68fcb8d0de98b124d59944f64ab
- id: iI-ejO9hczw.srt
  parent_uid: 400326ddbc2b7b0df39ad3a9eb7866cc
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-5-z-transform/iI-ejO9hczw.srt
  title: 3play caption file
  type: null
  uid: 0ce7871251327d9a63b58fe8268ea3a8
- id: iI-ejO9hczw.pdf
  parent_uid: 400326ddbc2b7b0df39ad3a9eb7866cc
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-5-z-transform/iI-ejO9hczw.pdf
  title: 3play pdf file
  type: null
  uid: 1e9be9dbb105bc9928efa107b0204c15
- id: Caption-3Play YouTube id-SRT
  parent_uid: 400326ddbc2b7b0df39ad3a9eb7866cc
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 7882a0c8c40fcaf0dde425a743a2660f
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 400326ddbc2b7b0df39ad3a9eb7866cc
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1409eba662c8139c04a0e97abcf9f303
inline_embed_id: 92249153lecture5:ztransform33825389
layout: video
order_index: null
parent_uid: 47b07fedf3a30be25f155f62399cdb59
related_resources_text: ''
short_url: lecture-5-z-transform
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-5-z-transform
template_type: Tabbed
title: 'Lecture 5: Z Transform'
transcript: <p><span m='90'>The</span> <span m='180'>following</span> <span m='630'>content</span>
  <span m='1200'>is</span> <span m='1320'>provided</span> <span m='1770'>under</span>
  <span m='2009'>a</span> <span m='2070'>Creative</span> <span m='2490'>Commons</span>
  <span m='2910'>license.</span> <span m='4030'>Your</span> <span m='4200'>support</span>
  <span m='4680'>will</span> <span m='4860'>help</span> <span m='5100'>MIT</span>
  <span m='5550'>OpenCourseWare</span> <span m='6330'>continue</span> <span m='6850'>to</span>
  <span m='6960'>offer</span> <span m='7380'>high-quality</span> <span m='8100'>educational</span>
  <span m='8730'>resources</span> <span m='9330'>for</span> <span m='9510'>free.</span>
  <span m='10720'>To</span> <span m='10740'>make</span> <span m='10920'>a</span> <span
  m='10980'>donation</span> <span m='11730'>or</span> <span m='11940'>view</span>
  <span m='12390'>additional</span> <span m='12810'>materials</span> <span m='13320'>from</span>
  <span m='13500'>hundreds</span> <span m='13920'>of</span> <span m='14040'>MIT</span>
  <span m='14460'>courses,</span> <span m='15550'>visit</span> <span m='15780'>MIT</span>
  <span m='16200'>OpenCourseWare</span> <span m='17280'>at</span> <span m='17430'>ocw.mit.edu.</span>
  </p><p><span m='22790'>DENNIS FREEMAN:</span> <span m='22925'>So</span> <span m='23330'>today's</span>
  <span m='23720'>topic</span> <span m='24200'>is</span> <span m='24440'>to</span>
  <span m='24530'>talk</span> <span m='24770'>about</span> <span m='25010'>Z-transforms.</span>
  <span m='27960'>But</span> <span m='28110'>before</span> <span m='28440'>I</span>
  <span m='28530'>start,</span> <span m='29140'>I</span> <span m='29240'>want</span>
  <span m='29280'>to</span> <span m='29340'>mention</span> <span m='29910'>that</span>
  <span m='30060'>we've</span> <span m='30240'>already</span> <span m='30690'>covered</span>
  <span m='31110'>a</span> <span m='31170'>great</span> <span m='31380'>deal</span>
  <span m='31620'>of</span> <span m='31740'>material.</span> <span m='33990'>Here,</span>
  <span m='34260'>I've</span> <span m='34410'>made</span> <span m='34620'>a</span>
  <span m='34680'>map</span> <span m='35220'>just</span> <span m='35730'>of</span>
  <span m='35970'>things</span> <span m='36390'>we've</span> <span m='36630'>done</span>
  <span m='36990'>in</span> <span m='37260'>DT,</span> <span m='39030'>and</span>
  <span m='39150'>there's</span> <span m='39330'>a</span> <span m='39390'>fair</span>
  <span m='39600'>number</span> <span m='39900'>of</span> <span m='39990'>entries.</span>
  <span m='42390'>More</span> <span m='42630'>importantly,</span> <span m='43840'>there's</span>
  <span m='43950'>a</span> <span m='44010'>fair</span> <span m='44250'>number</span>
  <span m='44640'>of</span> <span m='44850'>connections</span> <span m='45510'>between</span>
  <span m='45900'>those</span> <span m='46140'>entries.</span> </p><p><span m='47610'>And</span>
  <span m='48450'>if</span> <span m='48600'>you're</span> <span m='48750'>thinking</span>
  <span m='49170'>about</span> <span m='49470'>systems,</span> <span m='50010'>you</span>
  <span m='50130'>should</span> <span m='50280'>be</span> <span m='50460'>able</span>
  <span m='50790'>to</span> <span m='51000'>think</span> <span m='51270'>about,</span>
  <span m='51900'>what do</span> <span m='52350'>each</span> <span m='52650'>one</span>
  <span m='52860'>of</span> <span m='52950'>those</span> <span m='53220'>arrows</span>
  <span m='53760'>stand</span> <span m='54240'>for?</span> <span m='55950'>The</span>
  <span m='56070'>reason</span> <span m='56430'>that's</span> <span m='56640'>important</span>
  <span m='57660'>is</span> <span m='57930'>that</span> <span m='58110'>we</span>
  <span m='58290'>like</span> <span m='58560'>to</span> <span m='58710'>have</span>
  <span m='58950'>multiple</span> <span m='59430'>representations</span> <span m='60330'>for</span>
  <span m='60480'>the</span> <span m='60570'>system</span> <span m='61500'>so</span>
  <span m='61650'>that</span> <span m='61770'>we're</span> <span m='61920'>always</span>
  <span m='62310'>able</span> <span m='62550'>to</span> <span m='62670'>choose</span>
  <span m='63060'>the</span> <span m='63180'>one</span> <span m='63390'>that</span>
  <span m='63480'>lets</span> <span m='63720'>us</span> <span m='63870'>work</span>
  <span m='64230'>the</span> <span m='64410'>most</span> <span m='64680'>simply.</span>
  <span m='66800'>But</span> <span m='66990'>sometimes</span> <span m='67530'>that</span>
  <span m='67680'>involves</span> <span m='68130'>moving</span> <span m='68520'>between</span>
  <span m='68910'>the</span> <span m='69030'>squares.</span> <span m='70410'>So</span>
  <span m='70560'>the</span> <span m='70680'>way</span> <span m='70890'>the</span>
  <span m='71010'>problem</span> <span m='71490'>was</span> <span m='71640'>posed</span>
  <span m='72000'>to</span> <span m='72090'>you</span> <span m='72240'>may</span>
  <span m='72390'>not</span> <span m='72630'>be</span> <span m='72900'>the</span>
  <span m='73050'>simplest</span> <span m='73470'>way</span> <span m='73620'>to</span>
  <span m='73740'>solve</span> <span m='74040'>it,</span> <span m='74220'>and</span>
  <span m='74340'>that</span> <span m='74640'>involves,</span> <span m='75090'>then,</span>
  <span m='75270'>going</span> <span m='75510'>across</span> <span m='75840'>one</span>
  <span m='75990'>of</span> <span m='76050'>those</span> <span m='76230'>arrows.</span>
  </p><p><span m='77070'>So</span> <span m='77280'>for</span> <span m='77460'>example,</span>
  <span m='78420'>we</span> <span m='78570'>know</span> <span m='79200'>that</span>
  <span m='79980'>there's</span> <span m='80160'>a</span> <span m='80250'>simple</span>
  <span m='80670'>relationship</span> <span m='81270'>between</span> <span m='81600'>block</span>
  <span m='81870'>diagrams</span> <span m='82410'>and</span> <span m='82500'>system</span>
  <span m='82800'>functionals.</span> <span m='84510'>All</span> <span m='84690'>you</span>
  <span m='84840'>need</span> <span m='85050'>to</span> <span m='85200'>do</span>
  <span m='85830'>is</span> <span m='86010'>think</span> <span m='86190'>about</span>
  <span m='86430'>delays</span> <span m='86560'>as</span> <span m='86970'>being</span>
  <span m='87480'>the</span> <span m='87750'>right</span> <span m='87960'>shift</span>
  <span m='88200'>operator.</span> <span m='89910'>That's</span> <span m='90090'>a</span>
  <span m='90120'>way</span> <span m='90300'>of</span> <span m='90390'>thinking</span>
  <span m='90780'>about</span> <span m='91050'>the</span> <span m='91140'>system</span>
  <span m='91470'>functional</span> <span m='92370'>is</span> <span m='92580'>just</span>
  <span m='93150'>a</span> <span m='94260'>formula</span> <span m='95640'>picture</span>
  <span m='98250'>of</span> <span m='98380'>the</span> <span m='98480'>block</span>
  <span m='98710'>diagram.</span> <span m='100600'>Similarly,</span> <span m='101710'>we</span>
  <span m='101830'>can</span> <span m='101950'>think</span> <span m='102100'>about</span>
  <span m='102310'>moving</span> <span m='102640'>between</span> <span m='102940'>the</span>
  <span m='103030'>block</span> <span m='103270'>diagram</span> <span m='103740'>and</span>
  <span m='103830'>the</span> <span m='103900'>difference</span> <span m='104230'>equation</span>
  <span m='104980'>by</span> <span m='105160'>thinking</span> <span m='105490'>about</span>
  <span m='105910'>delay</span> <span m='106660'>being</span> <span m='107020'>a</span>
  <span m='107080'>shift</span> <span m='107410'>of</span> <span m='107470'>the</span>
  <span m='107620'>index.</span> <span m='110450'>So</span> <span m='110500'>you</span>
  <span m='110620'>should</span> <span m='110830'>be</span> <span m='110980'>able</span>
  <span m='111160'>to</span> <span m='111250'>think</span> <span m='111490'>of</span>
  <span m='111640'>ways</span> <span m='112060'>of</span> <span m='112180'>thinking</span>
  <span m='112570'>about</span> <span m='112900'>all</span> <span m='113120'>of</span>
  <span m='113160'>the</span> <span m='113230'>transformations</span> <span m='114010'>between</span>
  <span m='114370'>the</span> <span m='114430'>boxes.</span> </p><p><span m='115630'>Over</span>
  <span m='115870'>here,</span> <span m='116140'>we</span> <span m='116290'>thought</span>
  <span m='116530'>about</span> <span m='116950'>system</span> <span m='117370'>functionals.</span>
  <span m='118900'>How</span> <span m='119020'>do</span> <span m='119110'>you</span>
  <span m='119290'>think</span> <span m='119560'>about</span> <span m='119800'>a</span>
  <span m='119860'>system</span> <span m='120910'>as</span> <span m='121120'>a</span>
  <span m='121210'>sequence</span> <span m='121720'>of</span> <span m='122020'>operations</span>
  <span m='123190'>that</span> <span m='123370'>you</span> <span m='123460'>do</span>
  <span m='123910'>to</span> <span m='124120'>a</span> <span m='124180'>signal?</span>
  <span m='125920'>We</span> <span m='126040'>also</span> <span m='126370'>thought</span>
  <span m='126610'>about</span> <span m='126820'>system</span> <span m='127180'>functions,</span>
  <span m='127720'>and</span> <span m='127810'>there's</span> <span m='127990'>a</span>
  <span m='128020'>very</span> <span m='128259'>simple</span> <span m='128590'>relationship</span>
  <span m='129100'>between</span> <span m='129460'>those.</span> <span m='130300'>You</span>
  <span m='130449'>think</span> <span m='130690'>about</span> <span m='131140'>the</span>
  <span m='132160'>operator</span> <span m='132610'>expression</span> <span m='133090'>that</span>
  <span m='133210'>involves</span> <span m='133860'>Rs</span> <span m='136690'>and</span>
  <span m='136840'>replace</span> <span m='137260'>each</span> <span m='137470'>R</span>
  <span m='137680'>with</span> <span m='137860'>1/z.</span> </p><p><span m='140830'>OK,</span>
  <span m='141070'>that</span> <span m='141190'>was</span> <span m='141340'>all</span>
  <span m='141490'>a</span> <span m='141520'>big</span> <span m='141700'>set</span>
  <span m='141930'>up,</span> <span m='142600'>because</span> <span m='142870'>now</span>
  <span m='143050'>I</span> <span m='143140'>want</span> <span m='143290'>to</span>
  <span m='143350'>ask</span> <span m='143650'>a</span> <span m='143710'>question.</span>
  <span m='145300'>Using</span> <span m='145690'>your</span> <span m='145840'>vast</span>
  <span m='146230'>knowledge</span> <span m='146680'>of</span> <span m='146770'>how</span>
  <span m='146950'>all</span> <span m='147100'>these</span> <span m='147310'>things</span>
  <span m='147550'>interrelate,</span> <span m='148990'>what's</span> <span m='149320'>the</span>
  <span m='149440'>relationship</span> <span m='150550'>between</span> <span m='150880'>the</span>
  <span m='150980'>system</span> <span m='151390'>functional,</span> <span m='152290'>a
  function</span> <span m='152740'>of</span> <span m='152830'>R,</span> <span m='156070'>and</span>
  <span m='156220'>the</span> <span m='156280'>unit</span> <span m='156520'>sample</span>
  <span m='156880'>response?</span> <span m='162020'>As</span> <span m='162200'>usual,</span>
  <span m='162560'>I'd</span> <span m='162710'>like</span> <span m='162890'>you</span>
  <span m='162980'>to</span> <span m='163100'>talk</span> <span m='163340'>to</span>
  <span m='163490'>your</span> <span m='163610'>neighbor</span> <span m='163910'>to</span>
  <span m='164000'>figure</span> <span m='164300'>this</span> <span m='164480'>out,</span>
  <span m='164840'>and</span> <span m='164990'>as</span> <span m='165170'>usual,</span>
  <span m='166310'>you</span> <span m='166550'>won't</span> <span m='166820'>do</span>
  <span m='167030'>that</span> <span m='167300'>unless</span> <span m='167600'>I</span>
  <span m='167660'>tell</span> <span m='167840'>you</span> <span m='167960'>to</span>
  <span m='168050'>do</span> <span m='168200'>something</span> <span m='168560'>trivial</span>
  <span m='168950'>first.</span> <span m='169300'>So</span> <span m='169760'>look</span>
  <span m='169970'>toward</span> <span m='170240'>your</span> <span m='170420'>neighbor,</span>
  <span m='171410'>say,</span> <span m='171740'>"Hi."</span> <span m='174980'>Wonderful,</span>
  <span m='175640'>good.</span> <span m='176300'>Now,</span> <span m='176990'>figure</span>
  <span m='177260'>out</span> <span m='177410'>this</span> <span m='177560'>problem.</span>
  </p><p></p><p></p><p></p><p><span m='284160'>OK,</span> <span m='284500'>how</span>
  <span m='284650'>many</span> <span m='284950'>of</span> <span m='285100'>you--</span>
  <span m='285480'>I</span> <span m='285580'>want</span> <span m='285730'>a</span>
  <span m='285820'>show</span> <span m='286000'>of</span> <span m='286060'>hands.</span>
  <span m='286390'>How</span> <span m='286510'>many</span> <span m='286720'>of</span>
  <span m='286810'>you</span> <span m='287170'>know a</span> <span m='287530'>way</span>
  <span m='287860'>of</span> <span m='287980'>getting</span> <span m='288310'>between</span>
  <span m='288670'>those</span> <span m='288910'>boxes?</span> <span m='289420'>Raise</span>
  <span m='289600'>your</span> <span m='289720'>hand.</span> <span m='293150'>How</span>
  <span m='293170'>many</span> <span m='293380'>of</span> <span m='293440'>you</span>
  <span m='293560'>are</span> <span m='293650'>sitting</span> <span m='293950'>beside</span>
  <span m='294340'>somebody</span> <span m='294760'>who</span> <span m='294880'>knows</span>
  <span m='295270'>the</span> <span m='295390'>way</span> <span m='295570'>to</span>
  <span m='295660'>get</span> <span m='295780'>between</span> <span m='296140'>those</span>
  <span m='296320'>boxes?</span> <span m='299410'>No.</span> <span m='299770'>OK,</span>
  <span m='300070'>that didn't work</span> <span m='300370'>either.</span> </p><p><span
  m='301450'>OK,</span> <span m='301750'>can</span> <span m='301930'>somebody</span>
  <span m='302320'>tell</span> <span m='302530'>me,</span> <span m='302740'>if</span>
  <span m='302860'>I</span> <span m='302980'>told</span> <span m='303310'>you</span>
  <span m='303400'>a</span> <span m='303460'>system</span> <span m='303790'>functional,</span>
  <span m='304190'>say</span> <span m='304330'>I</span> <span m='304420'>told</span>
  <span m='304600'>you</span> <span m='304750'>that</span> <span m='305020'>one,</span>
  <span m='306460'>how</span> <span m='306700'>would</span> <span m='306850'>I</span>
  <span m='306970'>figure</span> <span m='307450'>out</span> <span m='307810'>the</span>
  <span m='307930'>unit</span> <span m='308230'>sample</span> <span m='308590'>response</span>
  <span m='309070'>from</span> <span m='309250'>the</span> <span m='309340'>system</span>
  <span m='309610'>function--</span> <span m='310230'>functional?</span> <span m='311880'>Yes.</span>
  </p><p><span m='312611'>AUDIENCE:</span> <span m='312754'>Don't</span> <span m='312897'>you</span>
  <span m='313042'>take the</span> <span m='313473'>inverse Laplace</span> <span m='313904'>of
  it?</span> </p><p><span m='314770'>DENNIS FREEMAN:</span> <span m='314970'>Inverse</span>
  <span m='315400'>Laplace.</span> <span m='316630'>OK,</span> <span m='316990'>that's</span>
  <span m='317200'>kind</span> <span m='317680'>of</span> <span m='318370'>right,</span>
  <span m='318880'>but</span> <span m='319060'>not</span> <span m='319300'>quite.</span>
  <span m='322366'>So</span> <span m='322750'>usually,</span> <span m='324310'>the</span>
  <span m='325150'>answer</span> <span m='325510'>to</span> <span m='325600'>the</span>
  <span m='325720'>question</span> <span m='326110'>is</span> <span m='326320'>either</span>
  <span m='326680'>the</span> <span m='326800'>slide</span> <span m='327190'>before</span>
  <span m='327670'>this</span> <span m='327880'>one</span> <span m='328060'>or</span>
  <span m='328150'>the</span> <span m='328240'>slide</span> <span m='328570'>after</span>
  <span m='329020'>this</span> <span m='329230'>one.</span> <span m='330290'>So</span>
  <span m='330670'>that</span> <span m='330880'>doesn't</span> <span m='331150'>quite</span>
  <span m='331390'>fit</span> <span m='331660'>this.</span> <span m='331955'>The</span>
  <span m='332250'>slide</span> <span m='332410'>before</span> <span m='332710'>this</span>
  <span m='332920'>one</span> <span m='332990'>said</span> <span m='333160'>something</span>
  <span m='333420'>about</span> <span m='333530'>Z-transforms.</span> </p><p><span
  m='339960'>Can</span> <span m='340120'>somebody</span> <span m='340480'>think</span>
  <span m='340660'>of</span> <span m='340780'>a</span> <span m='340840'>way,</span>
  <span m='341110'>if</span> <span m='341200'>I</span> <span m='341320'>told</span>
  <span m='341620'>you</span> <span m='341740'>the</span> <span m='341860'>system</span>
  <span m='342190'>functional</span> <span m='342730'>is</span> <span m='342880'>this</span>
  <span m='343090'>thing,</span> <span m='343690'>how</span> <span m='343840'>would</span>
  <span m='343990'>you</span> <span m='344200'>derive</span> <span m='346600'>the</span>
  <span m='346720'>unit</span> <span m='346960'>sample</span> <span m='347320'>response?</span>
  <span m='349190'>Yes.</span> </p><p><span m='349928'>AUDIENCE:</span> <span m='350177'>You
  could</span> <span m='350426'>convert it</span> <span m='350924'>into a difference</span>
  <span m='351422'>equation</span> <span m='351920'>and then</span> <span m='352418'>just
  work it out</span> <span m='352916'>manually.</span> </p><p><span m='353420'>DENNIS
  FREEMAN:</span> <span m='353645'>Convert it</span> <span m='353870'>into</span>
  <span m='354080'>a</span> <span m='354140'>difference</span> <span m='354470'>equation.</span>
  <span m='354920'>That</span> <span m='355070'>would</span> <span m='355220'>work.</span>
  <span m='355590'>So</span> <span m='355820'>what</span> <span m='356000'>you</span>
  <span m='356150'>could</span> <span m='356270'>do</span> <span m='356420'>is</span>
  <span m='356540'>go</span> <span m='356720'>from</span> <span m='356900'>this</span>
  <span m='357140'>box</span> <span m='358900'>to</span> <span m='359020'>that</span>
  <span m='359320'>box.</span> <span m='361030'>Then,</span> <span m='361330'>if</span>
  <span m='361540'>you</span> <span m='361630'>had</span> <span m='361780'>this</span>
  <span m='361960'>box</span> <span m='362230'>how</span> <span m='362350'>would</span>
  <span m='362470'>you</span> <span m='362530'>get</span> <span m='362680'>the</span>
  <span m='362770'>unit</span> <span m='362950'>sample</span> <span m='363250'>response?</span>
  <span m='368610'>Yes.</span> </p><p><span m='370056'>AUDIENCE:</span> <span m='370297'>[INAUDIBLE]</span>
  <span m='371984'>delta.</span> </p><p><span m='373430'>DENNIS FREEMAN:</span> <span
  m='373535'>Put</span> <span m='373640'>a</span> <span m='373700'>delta</span> <span
  m='374270'>into</span> <span m='374720'>the</span> <span m='374840'>difference.</span>
  <span m='375350'>Think</span> <span m='375530'>about</span> <span m='375710'>the</span>
  <span m='375830'>difference</span> <span m='376160'>equation</span> <span m='376610'>being</span>
  <span m='376910'>a</span> <span m='376970'>system.</span> <span m='377690'>Put</span>
  <span m='377870'>a</span> <span m='377960'>delta</span> <span m='378430'>in and</span>
  <span m='378770'>see</span> <span m='378980'>what</span> <span m='379160'>comes</span>
  <span m='379460'>out.</span> <span m='379970'>Exactly.</span> <span m='381350'>Can</span>
  <span m='381500'>somebody</span> <span m='381860'>think</span> <span m='382040'>of</span>
  <span m='382130'>a</span> <span m='382190'>more</span> <span m='382370'>direct</span>
  <span m='382730'>way</span> <span m='382940'>that</span> <span m='383060'>doesn't</span>
  <span m='383360'>skirt</span> <span m='383690'>through</span> <span m='383900'>the</span>
  <span m='383990'>difference</span> <span m='384290'>equation?</span> <span m='385250'>Yes.</span>
  </p><p><span m='385990'>AUDIENCE:</span> <span m='386210'>Multiply</span> <span
  m='386430'>the system</span> <span m='386870'>functional</span> <span m='387310'>by
  a delta</span> <span m='387750'>function.</span> </p><p><span m='389070'>DENNIS
  FREEMAN:</span> <span m='389272'>Multiply</span> <span m='389880'>the</span> <span
  m='390000'>functional</span> <span m='390570'>by</span> <span m='390810'>a</span>
  <span m='390930'>delta</span> <span m='391290'>function.</span> <span m='391650'>I'm</span>
  <span m='391710'>not</span> <span m='391830'>quite</span> <span m='392010'>sure</span>
  <span m='392190'>what</span> <span m='392280'>that</span> <span m='392430'>means,</span>
  <span m='393240'>but</span> <span m='393420'>I'm</span> <span m='393510'>willing</span>
  <span m='393750'>to</span> <span m='393870'>try</span> <span m='394110'>anything.</span>
  <span m='395250'>1</span> <span m='395550'>over</span> <span m='395790'>1</span>
  <span m='396030'>minus</span> <span m='396450'>R</span> <span m='396690'>minus</span>
  <span m='397060'>R</span> <span m='397435'>squared.</span> <span m='398250'>Multiply</span>
  <span m='398850'>that</span> <span m='399120'>times</span> <span m='399420'>a</span>
  <span m='399480'>delta</span> <span m='399780'>function.</span> <span m='404090'>What</span>
  <span m='404110'>do</span> <span m='404200'>I</span> <span m='404260'>do</span>
  <span m='404380'>next?</span> </p><p><span m='410040'>OK,</span> <span m='410250'>as</span>
  <span m='410430'>I</span> <span m='410490'>said,</span> <span m='411090'>the</span>
  <span m='411180'>answer</span> <span m='411420'>to</span> <span m='411480'>the</span>
  <span m='411570'>question</span> <span m='411900'>is</span> <span m='412050'>usually</span>
  <span m='412410'>something</span> <span m='412710'>that</span> <span m='412800'>we</span>
  <span m='412950'>just</span> <span m='413250'>did</span> <span m='413580'>or</span>
  <span m='413790'>something</span> <span m='414070'>we're</span> <span m='414180'>just</span>
  <span m='414390'>about</span> <span m='414630'>to</span> <span m='414750'>do.</span>
  <span m='416010'>Where</span> <span m='416130'>did</span> <span m='416190'>we</span>
  <span m='416310'>spend</span> <span m='416550'>the</span> <span m='416640'>last</span>
  <span m='416880'>three</span> <span m='417090'>weeks doing?</span> <span m='417500'>No,</span>
  <span m='417690'>it's</span> <span m='417990'>not</span> <span m='418140'>three</span>
  <span m='418320'>weeks.</span> <span m='418630'>It's</span> <span m='418860'>only</span>
  <span m='419640'>a</span> <span m='419730'>week,</span> <span m='420090'>but,</span>
  <span m='420450'>you</span> <span m='420510'>know,</span> <span m='420630'>I</span>
  <span m='420750'>exaggerate.</span> <span m='422990'>What</span> <span m='423150'>have</span>
  <span m='423270'>we</span> <span m='423360'>been</span> <span m='423540'>doing?</span>
  <span m='425010'>Yes.</span> </p><p><span m='426274'>AUDIENCE:</span> <span m='426500'>We</span>
  <span m='426726'>could</span> <span m='427178'>use</span> <span m='427630'>long
  division</span> <span m='428082'>[INAUDIBLE]</span> </p><p><span m='428990'>DENNIS
  FREEMAN:</span> <span m='429215'>One</span> <span m='429440'>way</span> <span m='429920'>would</span>
  <span m='430130'>be</span> <span m='430340'>use</span> <span m='430580'>long</span>
  <span m='430790'>division.</span> <span m='431240'>How</span> <span m='431360'>would</span>
  <span m='431510'>that</span> <span m='431690'>work?</span> <span m='431960'>If</span>
  <span m='432020'>we</span> <span m='432140'>did</span> <span m='432320'>1/1--</span>
  <span m='432840'>maybe</span> <span m='433580'>I'd</span> <span m='433640'>better</span>
  <span m='434390'>use</span> <span m='435010'>a</span> <span m='435050'>bigger</span>
  <span m='435320'>blackboard</span> <span m='435830'>space--</span> <span m='438650'>if</span>
  <span m='438830'>I</span> <span m='438890'>tried</span> <span m='439220'>to</span>
  <span m='439340'>do</span> <span m='441350'>1</span> <span m='441560'>over</span>
  <span m='441770'>1</span> <span m='442010'>minus</span> <span m='442370'>R</span>
  <span m='442600'>minus</span> <span m='442910'>R</span> <span m='443235'>squared,</span>
  <span m='444080'>if</span> <span m='444230'>I</span> <span m='444290'>tried</span>
  <span m='444530'>to</span> <span m='444620'>think</span> <span m='444740'>about</span>
  <span m='444950'>that</span> <span m='445100'>by</span> <span m='445250'>long</span>
  <span m='445460'>division,</span> <span m='445850'>I</span> <span m='445940'>would</span>
  <span m='446030'>do</span> <span m='446180'>1</span> <span m='446330'>minus</span>
  <span m='446630'>R</span> <span m='446780'>minus</span> <span m='447050'>R</span>
  <span m='447365'>squared</span> <span m='447980'>into</span> <span m='448520'>1.</span>
  <span m='450110'>How</span> <span m='450260'>would</span> <span m='450380'>that</span>
  <span m='450560'>work?</span> </p><p><span m='453070'>Well,</span> <span m='453170'>I'd</span>
  <span m='453230'>go</span> <span m='453440'>1--</span> <span m='453800'>I'd</span>
  <span m='453950'>go</span> <span m='454850'>1</span> <span m='455090'>goes</span>
  <span m='455300'>into</span> <span m='455480'>1</span> <span m='455750'>once.</span>
  <span m='456290'>I</span> <span m='456350'>get</span> <span m='456530'>1</span>
  <span m='456710'>minus R</span> <span m='457170'>minus</span> <span m='457440'>R</span>
  <span m='457765'>squared.</span> <span m='458690'>This</span> <span m='458870'>minus</span>
  <span m='459230'>this</span> <span m='459440'>gives</span> <span m='459620'>me</span>
  <span m='459760'>R</span> <span m='459970'>plus</span> <span m='460250'>R</span>
  <span m='460620'>squared.</span> <span m='461660'>This</span> <span m='461900'>goes</span>
  <span m='462110'>into</span> <span m='462320'>this</span> <span m='462530'>plus</span>
  <span m='462830'>R.</span> <span m='464170'>That</span> <span m='464330'>gives</span>
  <span m='464540'>me</span> <span m='466010'>whatever.</span> </p><p><span m='468690'>Having</span>
  <span m='469070'>done</span> <span m='469310'>it</span> <span m='470660'>in</span>
  <span m='470840'>the</span> <span m='470960'>solitude</span> <span m='471710'>of</span>
  <span m='471950'>my</span> <span m='472130'>own</span> <span m='472310'>breakfast</span>
  <span m='472790'>this</span> <span m='472970'>morning,</span> <span m='473480'>here's</span>
  <span m='473780'>an</span> <span m='473900'>answer</span> <span m='474230'>that</span>
  <span m='474380'>I</span> <span m='474500'>got</span> <span m='474770'>there.</span>
  <span m='477130'>So</span> <span m='477350'>if</span> <span m='477500'>I</span>
  <span m='477770'>perform</span> <span m='478130'>long</span> <span m='478370'>division</span>
  <span m='478790'>on</span> <span m='478940'>the</span> <span m='479180'>functional,</span>
  <span m='480050'>I</span> <span m='480140'>get</span> <span m='480380'>this</span>
  <span m='480620'>kind</span> <span m='480980'>of</span> <span m='481070'>an</span>
  <span m='481160'>answer.</span> <span m='483410'>The</span> <span m='483530'>question</span>
  <span m='483980'>was,</span> <span m='484290'>how</span> <span m='484340'>do</span>
  <span m='484460'>I</span> <span m='484550'>relate</span> <span m='485000'>the</span>
  <span m='485090'>functional</span> <span m='486050'>to</span> <span m='486170'>the</span>
  <span m='486290'>unit</span> <span m='486530'>sample</span> <span m='486890'>response?</span>
  <span m='487400'>How</span> <span m='487580'>do</span> <span m='487670'>I--</span>
  <span m='488300'>how</span> <span m='488450'>do</span> <span m='488540'>I</span>
  <span m='488660'>relate</span> <span m='488990'>this</span> <span m='489230'>to</span>
  <span m='489350'>the</span> <span m='489440'>unit</span> <span m='489620'>sample</span>
  <span m='489890'>response?</span> </p><p><span m='490947'>AUDIENCE:</span> <span
  m='491190'>The coefficient</span> <span m='491434'>[INAUDIBLE]</span> </p><p><span
  m='492410'>DENNIS FREEMAN:</span> <span m='492510'>Excuse</span> <span m='492610'>me?</span>
  </p><p><span m='492710'>AUDIENCE:</span> <span m='492911'>The</span> <span m='493112'>coefficients</span>
  <span m='493514'>[INAUDIBLE]</span> </p><p><span m='494720'>DENNIS FREEMAN:</span>
  <span m='494780'>The</span> <span m='494840'>coefficients</span> <span m='495620'>of</span>
  <span m='495800'>this</span> <span m='496100'>expression</span> <span m='497130'>are</span>
  <span m='498620'>the</span> <span m='498740'>unit</span> <span m='498980'>sample</span>
  <span m='499370'>response.</span> <span m='502330'>OK?</span> <span m='503440'>So</span>
  <span m='503620'>there's</span> <span m='503770'>a</span> <span m='503830'>very</span>
  <span m='504190'>straightforward</span> <span m='504910'>way.</span> <span m='505210'>If</span>
  <span m='505330'>I</span> <span m='505450'>tell</span> <span m='505720'>you</span>
  <span m='505900'>the</span> <span m='506020'>system</span> <span m='506380'>functional,</span>
  <span m='507610'>if</span> <span m='507730'>I</span> <span m='507850'>tell</span>
  <span m='508000'>you</span> <span m='508180'>this</span> <span m='508420'>representation,</span>
  <span m='509360'>there's</span> <span m='509410'>a</span> <span m='509470'>very</span>
  <span m='509740'>simple</span> <span m='510310'>way</span> <span m='511060'>that</span>
  <span m='511240'>we've</span> <span m='511510'>thought</span> <span m='511840'>about</span>
  <span m='512679'>by</span> <span m='512860'>which</span> <span m='513130'>you</span>
  <span m='513250'>can</span> <span m='514840'>automatically</span> <span m='515440'>calculate</span>
  <span m='516330'>what</span> <span m='516500'>is</span> <span m='516640'>the unit</span>
  <span m='516890'>sample</span> <span m='517600'>response?</span> <span m='519160'>OK?</span>
  </p><p><span m='520090'>In</span> <span m='520240'>fact,</span> <span m='520539'>it's</span>
  <span m='520659'>so</span> <span m='520929'>simple</span> <span m='522400'>that</span>
  <span m='522520'>we</span> <span m='522669'>can</span> <span m='522820'>write</span>
  <span m='522970'>a</span> <span m='523030'>formula</span> <span m='523450'>for</span>
  <span m='523630'>it.</span> <span m='525610'>Think</span> <span m='525850'>about</span>
  <span m='526060'>the</span> <span m='526150'>unit</span> <span m='526360'>sample</span>
  <span m='526690'>response</span> <span m='527140'>being</span> <span m='527380'>h</span>
  <span m='527705'>of n.</span> <span m='529710'>Associate</span> <span m='530370'>the</span>
  <span m='530520'>h</span> <span m='530760'>0</span> <span m='531090'>term</span>
  <span m='531450'>with</span> <span m='531630'>a</span> <span m='531690'>constant,</span>
  <span m='532340'>the</span> <span m='532500'>h</span> <span m='532710'>1</span>
  <span m='533010'>term</span> <span m='533340'>with</span> <span m='533520'>an</span>
  <span m='533670'>R,</span> <span m='534060'>with</span> <span m='534240'>the</span>
  <span m='534390'>h</span> <span m='534600'>2</span> <span m='534840'>term</span>
  <span m='535590'>with</span> <span m='535770'>an</span> <span m='535860'>R</span>
  <span m='536040'>squared.</span> <span m='536550'>Add</span> <span m='536730'>them</span>
  <span m='536880'>all</span> <span m='537000'>together,</span> <span m='538800'>that's</span>
  <span m='539100'>the</span> <span m='539220'>answer.</span> </p><p><span m='541270'>So</span>
  <span m='541630'>the</span> <span m='541810'>way</span> <span m='542140'>you</span>
  <span m='542290'>get</span> <span m='542590'>between</span> <span m='543040'>these</span>
  <span m='543280'>representations</span> <span m='544270'>is</span> <span m='544420'>very</span>
  <span m='544660'>simple.</span> <span m='546260'>Here's</span> <span m='546520'>the</span>
  <span m='546640'>unit</span> <span m='546850'>sample</span> <span m='547180'>response,</span>
  <span m='547840'>here's</span> <span m='548110'>the</span> <span m='548200'>system</span>
  <span m='548500'>functional,</span> <span m='548950'>and</span> <span m='549070'>here's</span>
  <span m='549370'>an</span> <span m='549460'>equation</span> <span m='550870'>that</span>
  <span m='551080'>relates</span> <span m='551470'>the</span> <span m='551590'>two</span>
  <span m='551920'>representations.</span> <span m='552910'>That</span> <span m='553120'>all</span>
  <span m='553510'>completely</span> <span m='553870'>clear?</span> <span m='555650'>Simple.</span>
  <span m='556030'>Yes,</span> <span m='556400'>hi.</span> <span m='558380'>Everything</span>
  <span m='558740'>clear?</span> <span m='560740'>Questions,</span> <span m='561220'>comments?</span>
  </p><p><span m='564980'>OK,</span> <span m='565940'>a</span> <span m='566210'>follow-up</span>
  <span m='566600'>question.</span> <span m='567800'>So</span> <span m='567950'>here's</span>
  <span m='568190'>a</span> <span m='568250'>relationship</span> <span m='568820'>between</span>
  <span m='569240'>these</span> <span m='569480'>two</span> <span m='569630'>representations.</span>
  <span m='570990'>How</span> <span m='571090'>about</span> <span m='571160'>a</span>
  <span m='571220'>relationship</span> <span m='571730'>between</span> <span m='572030'>these</span>
  <span m='572270'>two</span> <span m='572390'>representations?</span> <span m='579000'>Yes.</span>
  </p><p><span m='579210'>AUDIENCE:</span> <span m='579437'>Same</span> <span m='579664'>relationship.</span>
  <span m='580118'>Just use</span> <span m='580572'>one of</span> <span m='581026'>the
  place</span> <span m='581480'>markers.</span> </p><p><span m='582390'>DENNIS FREEMAN:</span>
  <span m='582560'>Precisely.</span> <span m='584020'>So</span> <span m='584190'>it's</span>
  <span m='584340'>really--</span> <span m='584780'>so</span> <span m='584940'>we</span>
  <span m='585090'>got</span> <span m='585330'>this</span> <span m='585510'>one</span>
  <span m='585690'>in</span> <span m='585780'>the</span> <span m='585840'>previous</span>
  <span m='586300'>step.</span> <span m='587000'>R</span> <span m='587280'>is</span>
  <span m='587400'>just</span> <span m='587580'>1/z,</span> <span m='588340'>so</span>
  <span m='588540'>we</span> <span m='588690'>get</span> <span m='588840'>this.</span>
  <span m='590400'>So</span> <span m='590580'>we</span> <span m='590670'>get</span>
  <span m='590820'>a</span> <span m='590880'>relationship</span> <span m='591450'>that</span>
  <span m='591540'>looks</span> <span m='591720'>like</span> <span m='591900'>that.</span>
  </p><p><span m='594810'>OK,</span> <span m='595170'>that</span> <span m='595590'>relationship</span>
  <span m='596310'>is</span> <span m='596460'>the</span> <span m='596550'>basis</span>
  <span m='596940'>of</span> <span m='597030'>today's</span> <span m='597390'>lecture.</span>
  <span m='598600'>We</span> <span m='598680'>call</span> <span m='598980'>that</span>
  <span m='599190'>relationship--</span> <span m='601280'>so</span> <span m='601950'>that</span>
  <span m='602130'>relationship</span> <span m='602700'>represents</span> <span m='603210'>a</span>
  <span m='603270'>mathematical</span> <span m='604050'>relationship</span> <span
  m='604680'>between</span> <span m='605730'>a</span> <span m='605820'>function</span>
  <span m='606240'>of</span> <span m='606440'>z</span> <span m='610210'>and</span>
  <span m='610360'>a</span> <span m='610390'>function</span> <span m='610780'>of</span>
  <span m='610900'>n,</span> <span m='612300'>and</span> <span m='612430'>we</span>
  <span m='612550'>call</span> <span m='612790'>that</span> <span m='612970'>relationship</span>
  <span m='614300'>the</span> <span m='614730'>Z-transform.</span> <span m='616530'>So</span>
  <span m='616650'>that's</span> <span m='616920'>the</span> <span m='617010'>topic</span>
  <span m='617340'>for</span> <span m='617460'>today.</span> <span m='617710'>We're</span>
  <span m='617790'>going</span> <span m='617910'>to</span> <span m='617970'>think</span>
  <span m='618180'>about</span> <span m='618750'>systems,</span> <span m='619500'>not</span>
  <span m='619770'>as</span> <span m='619920'>an</span> <span m='620010'>operator,</span>
  <span m='622140'>but</span> <span m='622290'>as</span> <span m='622410'>a</span>
  <span m='622470'>mathematical</span> <span m='623130'>function,</span> <span m='623520'>h</span>
  <span m='623730'>of</span> <span m='623850'>z.</span> </p><p><span m='626160'>So</span>
  <span m='626610'>the</span> <span m='626820'>first</span> <span m='627090'>thing</span>
  <span m='627270'>to</span> <span m='627720'>realize</span> <span m='628290'>is</span>
  <span m='628470'>that</span> <span m='628700'>this</span> <span m='628890'>transform</span>
  <span m='629580'>then,</span> <span m='629820'>this</span> <span m='630000'>thing</span>
  <span m='630330'>that</span> <span m='630450'>we're</span> <span m='630570'>going</span>
  <span m='630690'>to</span> <span m='630750'>be</span> <span m='630840'>worried</span>
  <span m='631110'>about</span> <span m='631320'>today</span> <span m='632070'>is</span>
  <span m='632420'>a</span> <span m='632570'>map</span> <span m='634920'>between</span>
  <span m='635280'>a</span> <span m='635340'>discrete</span> <span m='635760'>function</span>
  <span m='637810'>and</span> <span m='638550'>a</span> <span m='640020'>continuous</span>
  <span m='640500'>function</span> <span m='640820'>of</span> <span m='640880'>z.</span>
  <span m='642210'>And</span> <span m='642390'>even</span> <span m='642660'>though</span>
  <span m='642810'>it's</span> <span m='642930'>been</span> <span m='643110'>motivated,</span>
  <span m='643680'>I</span> <span m='643770'>motivated</span> <span m='644270'>it</span>
  <span m='644340'>by</span> <span m='644460'>thinking</span> <span m='644790'>about</span>
  <span m='645000'>how</span> <span m='645210'>it</span> <span m='645270'>would</span>
  <span m='645420'>relate</span> <span m='645660'>to</span> <span m='645780'>a</span>
  <span m='645840'>system,</span> <span m='647880'>that</span> <span m='648060'>relationship</span>
  <span m='648780'>between</span> <span m='649140'>a</span> <span m='649200'>function</span>
  <span m='649530'>of</span> <span m='649620'>z</span> <span m='649860'>and</span>
  <span m='649950'>a</span> <span m='649980'>function</span> <span m='650310'>of</span>
  <span m='650430'>n</span> <span m='650790'>is</span> <span m='650880'>something</span>
  <span m='651180'>that</span> <span m='651300'>you</span> <span m='651390'>could</span>
  <span m='651510'>do</span> <span m='651690'>on</span> <span m='651870'>any</span>
  <span m='653490'>discrete</span> <span m='653940'>time</span> <span m='654270'>signal.</span>
  <span m='655830'>So</span> <span m='656070'>in</span> <span m='656220'>fact,</span>
  <span m='656790'>if</span> <span m='656970'>you</span> <span m='657060'>have</span>
  <span m='657240'>any</span> <span m='657510'>signal</span> <span m='657840'>x</span>
  <span m='658110'>of n,</span> <span m='658380'>we</span> <span m='658500'>can</span>
  <span m='658650'>think</span> <span m='658800'>about</span> <span m='659010'>the</span>
  <span m='659100'>Z-transform</span> <span m='659820'>of</span> <span m='659940'>it</span>
  <span m='660270'>by</span> <span m='660450'>simply</span> <span m='660750'>thinking</span>
  <span m='660990'>about</span> <span m='661230'>what</span> <span m='661380'>that</span>
  <span m='662100'>equation</span> <span m='662550'>is</span> <span m='662670'>telling</span>
  <span m='662970'>us.</span> <span m='663180'>How</span> <span m='663390'>does</span>
  <span m='663570'>it</span> <span m='663690'>map</span> <span m='665190'>from</span>
  <span m='665370'>a</span> <span m='665430'>function</span> <span m='665790'>of</span>
  <span m='665910'>n</span> <span m='666630'>to</span> <span m='666750'>a</span> <span
  m='666810'>function</span> <span m='667140'>of</span> <span m='667230'>z?</span>
  </p><p><span m='669040'>I've</span> <span m='669250'>written</span> <span m='669550'>it</span>
  <span m='669930'>in</span> <span m='670140'>a</span> <span m='670170'>little--</span>
  <span m='670990'>in</span> <span m='671140'>a</span> <span m='671200'>way</span>
  <span m='671380'>that</span> <span m='671500'>you</span> <span m='671590'>might</span>
  <span m='671800'>not</span> <span m='672010'>have</span> <span m='672130'>anticipated.</span>
  <span m='672890'>You</span> <span m='672990'>might</span> <span m='673030'>have</span>
  <span m='673120'>thought</span> <span m='673330'>I</span> <span m='673390'>would</span>
  <span m='673510'>have</span> <span m='673600'>started</span> <span m='673910'>at</span>
  <span m='674020'>0.</span> <span m='675700'>That's</span> <span m='675970'>just</span>
  <span m='676180'>because</span> <span m='676630'>we're</span> <span m='676720'>going</span>
  <span m='676840'>to</span> <span m='676930'>do</span> <span m='677140'>what's</span>
  <span m='677320'>called</span> <span m='677560'>the</span> <span m='677680'>bilateral</span>
  <span m='678220'>transform.</span> <span m='679690'>There</span> <span m='679900'>are</span>
  <span m='679990'>many</span> <span m='680320'>kinds</span> <span m='680710'>of</span>
  <span m='680960'>Z-transforms.</span> <span m='682210'>We're</span> <span m='682390'>going</span>
  <span m='682540'>to</span> <span m='682600'>do</span> <span m='682780'>this</span>
  <span m='683020'>particular</span> <span m='683560'>one.</span> </p><p><span m='683920'>Other</span>
  <span m='684160'>classes</span> <span m='684580'>that</span> <span m='684670'>you</span>
  <span m='684820'>might</span> <span m='685030'>take</span> <span m='685390'>may</span>
  <span m='685660'>use</span> <span m='685930'>something</span> <span m='686350'>called</span>
  <span m='686590'>a</span> <span m='686680'>unilateral.</span> <span m='688360'>If</span>
  <span m='688510'>you're</span> <span m='688660'>not</span> <span m='688840'>taking</span>
  <span m='689200'>such</span> <span m='689410'>a</span> <span m='689470'>class,</span>
  <span m='689830'>there's</span> <span m='689980'>no</span> <span m='690130'>good</span>
  <span m='690310'>reason</span> <span m='690580'>for</span> <span m='690730'>you</span>
  <span m='690850'>to</span> <span m='690970'>know</span> <span m='691210'>that.</span>
  <span m='691600'>If</span> <span m='691720'>you</span> <span m='691840'>are</span>
  <span m='692020'>taking</span> <span m='692320'>such</span> <span m='692530'>a</span>
  <span m='692590'>class,</span> <span m='693280'>we're</span> <span m='693490'>doing</span>
  <span m='694120'>bilateral.</span> <span m='694990'>That</span> <span m='695140'>just</span>
  <span m='695350'>means</span> <span m='695740'>two-sided,</span> <span m='696460'>and</span>
  <span m='696550'>we'll</span> <span m='696700'>see</span> <span m='696880'>by</span>
  <span m='697000'>the</span> <span m='697120'>end</span> <span m='697270'>of</span>
  <span m='697330'>the</span> <span m='697450'>hour</span> <span m='698230'>how</span>
  <span m='698380'>that</span> <span m='698560'>makes</span> <span m='698800'>some</span>
  <span m='699070'>things</span> <span m='699340'>simpler.</span> <span m='701580'>The</span>
  <span m='701700'>big</span> <span m='701880'>picture</span> <span m='702510'>is</span>
  <span m='702660'>identical</span> <span m='703510'>whether</span> <span m='703920'>you</span>
  <span m='704040'>do</span> <span m='704640'>unilateral</span> <span m='705390'>or</span>
  <span m='705630'>bilateral,</span> <span m='706260'>but</span> <span m='706380'>there</span>
  <span m='706530'>are</span> <span m='706620'>differences.</span> </p><p><span m='708750'>OK.</span>
  <span m='709710'>Simple</span> <span m='710090'>Z-transforms.</span> <span m='710790'>What's</span>
  <span m='711000'>the</span> <span m='711120'>Z-transform</span> <span m='712260'>of</span>
  <span m='712470'>the</span> <span m='712590'>simplest</span> <span m='713130'>signal</span>
  <span m='713460'>that</span> <span m='713580'>we</span> <span m='713730'>can</span>
  <span m='713880'>imagine?</span> <span m='714630'>Simplest</span> <span m='714990'>signal</span>
  <span m='715290'>that</span> <span m='715410'>we</span> <span m='715500'>can</span>
  <span m='715650'>imagine</span> <span m='716580'>is</span> <span m='716790'>the</span>
  <span m='716880'>unit</span> <span m='717090'>sample</span> <span m='717420'>signal.</span>
  <span m='718170'>It's</span> <span m='718380'>0</span> <span m='718770'>everywhere</span>
  <span m='719220'>except</span> <span m='719580'>n equals</span> <span m='719940'>0.</span>
  <span m='720390'>At</span> <span m='720570'>n equals</span> <span m='720930'>0,</span>
  <span m='721530'>it's</span> <span m='721710'>the</span> <span m='721830'>simplest</span>
  <span m='722220'>possible</span> <span m='722610'>non-zero</span> <span m='723120'>answer,</span>
  <span m='723720'>which</span> <span m='723900'>is</span> <span m='724020'>1.</span>
  </p><p><span m='726950'>What's</span> <span m='727190'>the</span> <span m='727310'>Z-transform?</span>
  <span m='727810'>Well,</span> <span m='728130'>that's</span> <span m='728300'>trivial.</span>
  <span m='729080'>You</span> <span m='729200'>stick</span> <span m='729410'>it</span>
  <span m='729500'>in</span> <span m='729590'>the</span> <span m='729680'>formula.</span>
  <span m='731970'>The</span> <span m='732050'>only</span> <span m='732380'>non-zero</span>
  <span m='733010'>answer</span> <span m='733430'>is</span> <span m='733610'>at</span>
  <span m='733730'>n equals</span> <span m='734150'>0.</span> <span m='735520'>Stick</span>
  <span m='735900'>in</span> <span m='736040'>n equals</span> <span m='736460'>0,</span>
  <span m='736880'>and</span> <span m='737000'>we</span> <span m='737120'>get</span>
  <span m='737240'>that</span> <span m='737390'>the</span> <span m='737540'>answer</span>
  <span m='737870'>is</span> <span m='738380'>the</span> <span m='738470'>Z-transform</span>
  <span m='739160'>is</span> <span m='739280'>1.</span> <span m='740960'>What</span>
  <span m='741230'>could</span> <span m='741410'>be</span> <span m='741560'>easier?</span>
  <span m='742080'>Good.</span> <span m='742760'>Simple</span> <span m='743180'>signal</span>
  <span m='743600'>in</span> <span m='743750'>time,</span> <span m='745590'>simple</span>
  <span m='745950'>signal</span> <span m='746220'>in</span> <span m='746490'>the</span>
  <span m='746550'>Z-transform.</span> </p><p><span m='748860'>What's</span> <span
  m='749160'>the</span> <span m='749790'>Z-transform</span> <span m='750630'>for</span>
  <span m='750870'>a</span> <span m='750930'>delayed</span> <span m='751420'>unit</span>
  <span m='752180'>sample</span> <span m='752550'>signal?</span> <span m='753720'>What</span>
  <span m='753870'>happens</span> <span m='754260'>if</span> <span m='754440'>the</span>
  <span m='755730'>only</span> <span m='756000'>place</span> <span m='756270'>that</span>
  <span m='756410'>it's</span> <span m='756510'>not</span> <span m='756720'>0</span>
  <span m='757050'>is</span> <span m='757110'>shifted</span> <span m='757470'>to</span>
  <span m='757590'>n</span> <span m='757800'>equals</span> <span m='758070'>1?</span>
  <span m='759910'>Not</span> <span m='760170'>a</span> <span m='760230'>big</span>
  <span m='760410'>deal.</span> <span m='761510'>Again,</span> <span m='762300'>there's</span>
  <span m='762510'>a</span> <span m='762630'>single</span> <span m='763050'>non-zero</span>
  <span m='763650'>answer,</span> <span m='763950'>it's</span> <span m='764100'>just</span>
  <span m='764310'>that</span> <span m='764430'>it's</span> <span m='764550'>now</span>
  <span m='764760'>at</span> <span m='764820'>n</span> <span m='765030'>equals</span>
  <span m='765240'>1.</span> <span m='767420'>So</span> <span m='767600'>this</span>
  <span m='767870'>answer</span> <span m='768290'>is</span> <span m='768580'>z</span>
  <span m='768680'>to</span> <span m='768740'>the</span> <span m='768830'>minus</span>
  <span m='769130'>1.</span> </p><p><span m='769870'>We</span> <span m='770240'>took</span>
  <span m='770450'>a</span> <span m='770510'>signal</span> <span m='771080'>that</span>
  <span m='771230'>was</span> <span m='771410'>a</span> <span m='771470'>function</span>
  <span m='771860'>of</span> <span m='771980'>n,</span> <span m='773750'>and</span>
  <span m='773900'>we</span> <span m='774050'>represent</span> <span m='774395'>it</span>
  <span m='774740'>by a</span> <span m='774980'>Z-transform,</span> <span m='775800'>which</span>
  <span m='775820'>is</span> <span m='775940'>a</span> <span m='776000'>function</span>
  <span m='776360'>of</span> <span m='776480'>z.</span> <span m='778040'>Delta</span>
  <span m='778420'>of</span> <span m='778725'>n</span> <span m='779030'>is</span>
  <span m='779210'>1.</span> <span m='780590'>Delta</span> <span m='780920'>of n</span>
  <span m='781250'>minus</span> <span m='781610'>1</span> <span m='782120'>is</span>
  <span m='782310'>z</span> <span m='782460'>to</span> <span m='782570'>the</span>
  <span m='782660'>minus</span> <span m='782960'>1.</span> </p><p><span m='784800'>OK,</span>
  <span m='785260'>with</span> <span m='785370'>that</span> <span m='785610'>vast</span>
  <span m='785940'>knowledge</span> <span m='786450'>of</span> <span m='786820'>Z-transforms,</span>
  <span m='788460'>figure</span> <span m='788970'>out</span> <span m='789300'>the</span>
  <span m='789450'>Z-transform</span> <span m='790380'>for</span> <span m='790560'>a</span>
  <span m='790620'>slightly</span> <span m='791010'>more</span> <span m='791190'>complicated</span>
  <span m='791850'>sequence</span> <span m='792870'>of</span> <span m='792990'>the</span>
  <span m='793110'>type--</span> <span m='793560'>of</span> <span m='793710'>the</span>
  <span m='793800'>type</span> <span m='794040'>that</span> <span m='794160'>we</span>
  <span m='794310'>saw</span> <span m='794970'>when</span> <span m='795120'>we</span>
  <span m='795210'>were</span> <span m='795270'>looking</span> <span m='795570'>at</span>
  <span m='795660'>systems.</span> <span m='796920'>What</span> <span m='797160'>if</span>
  <span m='797460'>the</span> <span m='797700'>signal</span> <span m='798060'>that</span>
  <span m='798180'>we're</span> <span m='798360'>interested</span> <span m='798810'>in</span>
  <span m='799020'>is</span> <span m='799110'>7/8</span> <span m='799650'>to</span>
  <span m='799770'>the</span> <span m='799970'>n,</span> <span m='800490'>u</span>
  <span m='800670'>of</span> <span m='800820'>n,</span> <span m='801030'>where</span>
  <span m='801150'>I'm</span> <span m='801270'>using</span> <span m='801570'>the</span>
  <span m='801660'>u</span> <span m='801810'>of</span> <span m='801930'>n</span> <span
  m='802080'>just</span> <span m='802230'>to</span> <span m='802350'>cut</span> <span
  m='802560'>off</span> <span m='802740'>the</span> <span m='802830'>negative</span>
  <span m='803190'>parts</span> <span m='803670'>of</span> <span m='803940'>7/8</span>
  <span m='804480'>to</span> <span m='804600'>the</span> <span m='804700'>n.</span>
  <span m='806500'>So</span> <span m='806580'>find</span> <span m='806940'>the</span>
  <span m='807030'>Z-transform,</span> <span m='807840'>and</span> <span m='807960'>find</span>
  <span m='808350'>if</span> <span m='808470'>it</span> <span m='808590'>looks</span>
  <span m='808800'>like</span> <span m='809010'>one</span> <span m='809280'>of</span>
  <span m='809400'>those</span> <span m='809790'>four</span> <span m='810150'>answers</span>
  <span m='810630'>or</span> <span m='810900'>none,</span> <span m='811260'>which</span>
  <span m='811440'>is</span> <span m='811560'>number</span> <span m='811800'>five.</span>
  </p><p></p><p></p><p></p><p><span m='913020'>So</span> <span m='913650'>what</span>
  <span m='913950'>answer</span> <span m='914460'>best</span> <span m='915510'>represents</span>
  <span m='916140'>the</span> <span m='916230'>Z-transform</span> <span m='917130'>of</span>
  <span m='917340'>the</span> <span m='917430'>signal</span> <span m='917850'>x?</span>
  <span m='919020'>Raise</span> <span m='919200'>your</span> <span m='919320'>hand,</span>
  <span m='919680'>number</span> <span m='920010'>one</span> <span m='920280'>through</span>
  <span m='920650'>five.</span> <span m='925020'>It's</span> <span m='925180'>a</span>
  <span m='925210'>participatory</span> <span m='925990'>sport.</span> <span m='928510'>Good</span>
  <span m='929680'>97%</span> <span m='931360'>correct,</span> <span m='931810'>I</span>
  <span m='931900'>think.</span> </p><p><span m='932260'>So</span> <span m='934780'>OK.</span>
  <span m='935230'>Everybody</span> <span m='935620'>says</span> <span m='935830'>two.</span>
  <span m='936160'>How</span> <span m='936250'>do</span> <span m='936310'>you</span>
  <span m='936400'>get</span> <span m='936520'>two?</span> <span m='936910'>What</span>
  <span m='937000'>do</span> <span m='937060'>you</span> <span m='937120'>do?</span>
  <span m='938000'>Plug in</span> <span m='938350'>the</span> <span m='938440'>formula,</span>
  <span m='938850'>right?</span> <span m='939190'>It's</span> <span m='939370'>a</span>
  <span m='939430'>very</span> <span m='939640'>simple-minded</span> <span m='940240'>thing.</span>
  </p><p><span m='942490'>If</span> <span m='942700'>you</span> <span m='942850'>were</span>
  <span m='943000'>to</span> <span m='943090'>think</span> <span m='943270'>about</span>
  <span m='943540'>this</span> <span m='943720'>signal</span> <span m='944590'>and</span>
  <span m='944800'>think</span> <span m='945010'>about</span> <span m='945310'>the</span>
  <span m='945430'>definition</span> <span m='946090'>of</span> <span m='946240'>the</span>
  <span m='946540'>Z-transform,</span> <span m='947710'>just</span> <span m='947890'>substitute</span>
  <span m='948700'>this</span> <span m='948970'>particular</span> <span m='949450'>signal,</span>
  <span m='950190'>7/8</span> <span m='950710'>to</span> <span m='950830'>the</span>
  <span m='950950'>n, u</span> <span m='951280'>of</span> <span m='951430'>n,</span>
  <span m='951910'>in</span> <span m='952180'>where</span> <span m='952720'>there</span>
  <span m='952870'>would</span> <span m='953050'>have</span> <span m='953230'>been</span>
  <span m='953530'>the</span> <span m='955560'>x</span> <span m='955780'>of</span>
  <span m='955900'>n</span> <span m='957440'>and</span> <span m='957590'>try</span>
  <span m='957770'>to</span> <span m='957830'>close</span> <span m='958130'>the</span>
  <span m='958220'>sum,</span> <span m='959210'>right?</span> <span m='959990'>It's</span>
  <span m='960490'>a</span> <span m='960830'>geometric</span> <span m='961400'>sequence.</span>
  <span m='962480'>We've</span> <span m='962690'>had</span> <span m='962870'>lots</span>
  <span m='963170'>of</span> <span m='963770'>experience</span> <span m='964280'>with</span>
  <span m='964460'>geometric</span> <span m='964940'>sequences.</span> <span m='965550'>It</span>
  <span m='965660'>was</span> <span m='965780'>in</span> <span m='965900'>the</span>
  <span m='965960'>homework,</span> <span m='966710'>and</span> <span m='966830'>so</span>
  <span m='966980'>we</span> <span m='967100'>all</span> <span m='967250'>know</span>
  <span m='967490'>that</span> <span m='967670'>the</span> <span m='967850'>answer</span>
  <span m='968360'>to</span> <span m='969290'>summing</span> <span m='969620'>a</span>
  <span m='969710'>geometric--</span> <span m='970000'>a</span> <span m='970290'>one-sided</span>
  <span m='970910'>geometric</span> <span m='971420'>sequence</span> <span m='972260'>is</span>
  <span m='972620'>something</span> <span m='972980'>of</span> <span m='973080'>the</span>
  <span m='973160'>form</span> <span m='973400'>1</span> <span m='973490'>over</span>
  <span m='973760'>1</span> <span m='973970'>minus</span> <span m='974280'>a.</span>
  <span m='975340'>OK,</span> <span m='975800'>easy,</span> <span m='976390'>right?</span>
  </p><p><span m='979360'>So</span> <span m='980290'>the</span> <span m='980470'>idea,</span>
  <span m='980830'>then,</span> <span m='981490'>is</span> <span m='981700'>that</span>
  <span m='981820'>we</span> <span m='982060'>understand</span> <span m='982660'>a</span>
  <span m='982720'>general</span> <span m='983200'>rule</span> <span m='983530'>by</span>
  <span m='983710'>which</span> <span m='983890'>we</span> <span m='984010'>can</span>
  <span m='984130'>map</span> <span m='984490'>a</span> <span m='984550'>function</span>
  <span m='984970'>of</span> <span m='985120'>time</span> <span m='985570'>into</span>
  <span m='985810'>a</span> <span m='985870'>function</span> <span m='986290'>of</span>
  <span m='986380'>z.</span> <span m='988420'>So</span> <span m='988570'>the</span>
  <span m='988690'>function</span> <span m='988990'>of</span> <span m='989110'>time</span>
  <span m='991140'>has</span> <span m='991530'>to</span> <span m='991650'>make</span>
  <span m='991830'>sense</span> <span m='992130'>everywhere.</span> <span m='993030'>That's--</span>
  <span m='993370'>we</span> <span m='994260'>want</span> <span m='994500'>that</span>
  <span m='994710'>to</span> <span m='994830'>be</span> <span m='994920'>true.</span>
  <span m='996180'>We</span> <span m='996330'>want</span> <span m='996540'>to</span>
  <span m='996660'>know</span> <span m='996990'>what</span> <span m='997230'>was</span>
  <span m='997500'>the</span> <span m='997650'>system's</span> <span m='998460'>unit</span>
  <span m='998910'>sample</span> <span m='999300'>response,</span> <span m='999720'>for</span>
  <span m='999870'>example,</span> <span m='1000860'>or</span> <span m='1001040'>what</span>
  <span m='1001250'>was</span> <span m='1001400'>the</span> <span m='1001550'>input</span>
  <span m='1001880'>to</span> <span m='1002000'>the</span> <span m='1002120'>system,</span>
  <span m='1002420'>or</span> <span m='1002510'>whatever.</span> <span m='1002900'>We
  want</span> <span m='1003080'>to</span> <span m='1003140'>know</span> <span m='1003260'>that</span>
  <span m='1003440'>at</span> <span m='1003530'>all</span> <span m='1003800'>possible</span>
  <span m='1004250'>values</span> <span m='1004670'>of</span> <span m='1004790'>n.</span>
  </p><p><span m='1006050'>How</span> <span m='1006230'>about</span> <span m='1006440'>the</span>
  <span m='1006590'>other</span> <span m='1006800'>case?</span> <span m='1007310'>Does</span>
  <span m='1007490'>it</span> <span m='1007580'>make</span> <span m='1007880'>sense?</span>
  <span m='1009140'>Is</span> <span m='1009380'>x</span> <span m='1009680'>of</span>
  <span m='1009830'>z</span> <span m='1010570'>makes</span> <span m='1010820'>sense</span>
  <span m='1011180'>for</span> <span m='1011360'>all</span> <span m='1011570'>possible</span>
  <span m='1012050'>values</span> <span m='1012590'>of</span> <span m='1012740'>z?</span>
  </p><p><span m='1015710'>And</span> <span m='1016070'>since</span> <span m='1016310'>I</span>
  <span m='1016430'>ask</span> <span m='1016610'>the</span> <span m='1016700'>question,</span>
  <span m='1017210'>the</span> <span m='1017360'>answer</span> <span m='1017690'>is</span>
  <span m='1019310'>no.</span> <span m='1019940'>Yes,</span> <span m='1020210'>of</span>
  <span m='1020330'>course.</span> <span m='1021120'>I</span> <span m='1021270'>wouldn't</span>
  <span m='1021450'>have</span> <span m='1021590'>asked</span> <span m='1021800'>the</span>
  <span m='1021920'>question</span> <span m='1022700'>if</span> <span m='1023090'>the</span>
  <span m='1023240'>answer</span> <span m='1023570'>were</span> <span m='1023930'>yes,</span>
  <span m='1024710'>right?</span> <span m='1025369'>So</span> <span m='1025550'>by</span>
  <span m='1025700'>the</span> <span m='1025819'>theory</span> <span m='1026150'>of</span>
  <span m='1026240'>lecturers,</span> <span m='1026750'>you</span> <span m='1026839'>can</span>
  <span m='1026990'>tell</span> <span m='1027619'>the</span> <span m='1027740'>answer</span>
  <span m='1027980'>has</span> <span m='1028250'>to</span> <span m='1028369'>have</span>
  <span m='1028550'>been</span> <span m='1028760'>no.</span> <span m='1029660'>So</span>
  <span m='1029810'>the</span> <span m='1029930'>question</span> <span m='1030410'>is,</span>
  <span m='1030920'>what</span> <span m='1031190'>values</span> <span m='1031760'>of</span>
  <span m='1031880'>z</span> <span m='1032119'>don't</span> <span m='1032390'>make</span>
  <span m='1032630'>sense?</span> <span m='1037300'>Shout.</span> </p><p><span m='1039079'>AUDIENCE:</span>
  <span m='1039230'>The</span> <span m='1039381'>summation</span> <span m='1039532'>of
  the</span> <span m='1039985'>[INAUDIBLE]</span> </p><p><span m='1041800'>DENNIS
  FREEMAN:</span> <span m='1041890'>The</span> <span m='1041980'>summation</span>
  <span m='1042310'>has</span> <span m='1042550'>to</span> <span m='1042640'>converge,</span>
  <span m='1044109'>so</span> <span m='1045400'>it's</span> <span m='1045700'>only</span>
  <span m='1045910'>going</span> <span m='1046060'>to</span> <span m='1046450'>be</span>
  <span m='1046640'>defined</span> <span m='1047410'>if</span> <span m='1047800'>this</span>
  <span m='1048140'>sum,</span> <span m='1048940'>which</span> <span m='1049150'>happens</span>
  <span m='1049540'>to</span> <span m='1049690'>be</span> <span m='1049810'>an</span>
  <span m='1049900'>infinite</span> <span m='1050290'>sum</span> <span m='1050650'>and</span>
  <span m='1050770'>therefore</span> <span m='1051490'>may</span> <span m='1051760'>not</span>
  <span m='1052210'>converge,</span> <span m='1054230'>it's</span> <span m='1054310'>going</span>
  <span m='1054430'>to</span> <span m='1054490'>have</span> <span m='1054670'>to</span>
  <span m='1054790'>be</span> <span m='1054910'>the</span> <span m='1055030'>case</span>
  <span m='1055480'>that</span> <span m='1055600'>that</span> <span m='1055780'>infinite</span>
  <span m='1056140'>sum</span> <span m='1056620'>does</span> <span m='1056860'>converge.</span>
  <span m='1057370'>Otherwise,</span> <span m='1057700'>it</span> <span m='1057790'>won't</span>
  <span m='1057890'>make</span> <span m='1058060'>sense</span> <span m='1058300'>to</span>
  <span m='1058420'>talk</span> <span m='1058630'>about</span> <span m='1058870'>it.</span>
  </p><p><span m='1059740'>So</span> <span m='1059860'>then</span> <span m='1060040'>the</span>
  <span m='1060130'>question</span> <span m='1060530'>is,</span> <span m='1060880'>for</span>
  <span m='1061030'>what</span> <span m='1061210'>values</span> <span m='1061630'>of</span>
  <span m='1061690'>z</span> <span m='1061930'>will</span> <span m='1062080'>that</span>
  <span m='1062290'>converge?</span> <span m='1063910'>And</span> <span m='1064060'>again,</span>
  <span m='1064390'>we</span> <span m='1064540'>know</span> <span m='1064720'>from</span>
  <span m='1064900'>our</span> <span m='1065050'>experience</span> <span m='1065530'>with</span>
  <span m='1065680'>geometric</span> <span m='1067000'>sequences</span> <span m='1068500'>that</span>
  <span m='1068890'>the</span> <span m='1070780'>base</span> <span m='1071140'>of</span>
  <span m='1071200'>the</span> <span m='1071320'>geometric,</span> <span m='1073280'>a,</span>
  <span m='1073900'>when</span> <span m='1074020'>we</span> <span m='1074140'>did</span>
  <span m='1074290'>homework</span> <span m='1074680'>one,</span> <span m='1075730'>the</span>
  <span m='1075820'>base</span> <span m='1076030'>of</span> <span m='1076090'>the</span>
  <span m='1076210'>geometric</span> <span m='1076720'>has</span> <span m='1076900'>to</span>
  <span m='1076990'>have</span> <span m='1077260'>what?</span> <span m='1078230'>What's</span>
  <span m='1078310'>the</span> <span m='1078400'>property</span> <span m='1078760'>of</span>
  <span m='1078820'>the</span> <span m='1078940'>base</span> <span m='1079120'>of</span>
  <span m='1079180'>the--</span> <span m='1080150'>the</span> <span m='1080290'>geometric</span>
  <span m='1080800'>that'll</span> <span m='1080990'>make</span> <span m='1081100'>it</span>
  <span m='1081220'>work?</span> </p><p><span m='1084650'>So</span> <span m='1084670'>if</span>
  <span m='1084760'>I</span> <span m='1084850'>want</span> <span m='1085000'>to</span>
  <span m='1085060'>sum</span> <span m='1085330'>some</span> <span m='1085600'>series</span>
  <span m='1086050'>of</span> <span m='1086140'>the</span> <span m='1086240'>form</span>
  <span m='1087740'>n</span> <span m='1088070'>equals</span> <span m='1088360'>0</span>
  <span m='1088690'>to</span> <span m='1088810'>infinity</span> <span m='1089390'>a
  to</span> <span m='1089610'>the</span> <span m='1089750'>n,</span> <span m='1091730'>what's</span>
  <span m='1092020'>the</span> <span m='1092080'>values--</span> <span m='1092800'>what's</span>
  <span m='1093070'>the</span> <span m='1093190'>limitation</span> <span m='1093700'>on</span>
  <span m='1093880'>a</span> <span m='1094200'>that</span> <span m='1094330'>makes</span>
  <span m='1094540'>it</span> <span m='1094630'>work?</span> </p><p><span m='1096425'>AUDIENCE:</span>
  <span m='1096900'>[INAUDIBLE]</span> </p><p><span m='1101650'>DENNIS FREEMAN:</span>
  <span m='1101755'>OK,</span> <span m='1101860'>you're</span> <span m='1102310'>not</span>
  <span m='1102550'>saying</span> <span m='1102850'>it</span> <span m='1102940'>loud</span>
  <span m='1103150'>enough</span> <span m='1103690'>or</span> <span m='1103870'>clearly</span>
  <span m='1104200'>enough,</span> <span m='1104530'>or</span> <span m='1104770'>I'm</span>
  <span m='1104950'>too</span> <span m='1105130'>dense</span> <span m='1105430'>or</span>
  <span m='1105520'>something.</span> </p><p><span m='1106432'>AUDIENCE:</span> <span
  m='1106576'>Abs</span> <span m='1106720'>less</span> <span m='1106864'>than</span>
  <span m='1107296'>1?</span> </p><p><span m='1108160'>DENNIS FREEMAN:</span> <span
  m='1108265'>So</span> <span m='1108370'>we</span> <span m='1108790'>need</span>
  <span m='1108970'>something--</span> <span m='1109330'>we</span> <span m='1109540'>need</span>
  <span m='1109720'>abs</span> <span m='1110050'>less</span> <span m='1110260'>than</span>
  <span m='1110410'>1,</span> <span m='1110590'>right.</span> <span m='1113440'>So</span>
  <span m='1113560'>we</span> <span m='1113650'>do</span> <span m='1113770'>the</span>
  <span m='1113890'>same</span> <span m='1114100'>thing</span> <span m='1114280'>here.</span>
  <span m='1114950'>We're</span> <span m='1114970'>going</span> <span m='1115090'>to</span>
  <span m='1115180'>have</span> <span m='1115390'>to</span> <span m='1115510'>have</span>
  <span m='1116170'>that</span> <span m='1116840'>the</span> <span m='1119650'>geometric</span>
  <span m='1120100'>base,</span> <span m='1121150'>7/8</span> <span m='1122780'>1</span>
  <span m='1123180'>over</span> <span m='1123500'>z</span> <span m='1125560'>has</span>
  <span m='1125860'>to</span> <span m='1125980'>be</span> <span m='1126100'>less--</span>
  <span m='1126490'>has</span> <span m='1126700'>to</span> <span m='1126760'>have</span>
  <span m='1126910'>a</span> <span m='1126970'>magnitude</span> <span m='1127510'>that</span>
  <span m='1127660'>is</span> <span m='1127780'>less</span> <span m='1128020'>than</span>
  <span m='1128200'>1.</span> <span m='1129950'>And</span> <span m='1130000'>if</span>
  <span m='1130120'>we</span> <span m='1130240'>torture</span> <span m='1130630'>our</span>
  <span m='1130720'>minds</span> <span m='1131260'>with</span> <span m='1131800'>inequalities</span>
  <span m='1132560'>and</span> <span m='1132640'>magnitude</span> <span m='1133150'>signs,</span>
  <span m='1134110'>that</span> <span m='1134290'>says</span> <span m='1134590'>that</span>
  <span m='1134710'>the</span> <span m='1134830'>magnitude</span> <span m='1135370'>of</span>
  <span m='1135460'>z</span> <span m='1135760'>has</span> <span m='1135940'>to</span>
  <span m='1136060'>be</span> <span m='1136210'>bigger</span> <span m='1136540'>than</span>
  <span m='1136690'>7/8.</span> <span m='1138700'>OK?</span> </p><p><span m='1139950'>The</span>
  <span m='1140100'>important</span> <span m='1140700'>idea</span> <span m='1141960'>is</span>
  <span m='1142320'>that</span> <span m='1142800'>when</span> <span m='1143040'>we</span>
  <span m='1143220'>characterize</span> <span m='1144110'>the</span> <span m='1144220'>Z-transform,</span>
  <span m='1147390'>we</span> <span m='1147540'>should</span> <span m='1147690'>be</span>
  <span m='1147840'>expecting</span> <span m='1148380'>it</span> <span m='1148470'>to</span>
  <span m='1148590'>work</span> <span m='1148800'>for</span> <span m='1148920'>all</span>
  <span m='1149130'>values</span> <span m='1149580'>of</span> <span m='1149700'>n,</span>
  <span m='1149850'>but</span> <span m='1149970'>not</span> <span m='1150150'>necessarily</span>
  <span m='1150840'>all</span> <span m='1150990'>values</span> <span m='1151410'>of</span>
  <span m='1151500'>z.</span> <span m='1153030'>So</span> <span m='1153180'>we</span>
  <span m='1153300'>have</span> <span m='1153450'>to</span> <span m='1153570'>be</span>
  <span m='1153660'>cognizant</span> <span m='1154290'>of</span> <span m='1154380'>that.</span>
  <span m='1154690'>We</span> <span m='1154710'>have</span> <span m='1154890'>to</span>
  <span m='1155010'>know</span> <span m='1155280'>which</span> <span m='1155520'>values</span>
  <span m='1156000'>of</span> <span m='1156090'>z</span> <span m='1156510'>are</span>
  <span m='1156660'>you</span> <span m='1156840'>talking</span> <span m='1157260'>about.</span>
  <span m='1158640'>We</span> <span m='1158760'>call</span> <span m='1158970'>that</span>
  <span m='1159180'>idea</span> <span m='1159560'>the</span> <span m='1159660'>region</span>
  <span m='1159990'>of</span> <span m='1160080'>convergence.</span> <span m='1160720'>We</span>
  <span m='1160740'>say</span> <span m='1160920'>the</span> <span m='1161040'>Z-transform</span>
  <span m='1161760'>converged</span> <span m='1162390'>for</span> <span m='1162570'>all</span>
  <span m='1162750'>z</span> <span m='1163560'>inside</span> <span m='1164010'>the</span>
  <span m='1164100'>region</span> <span m='1164430'>of</span> <span m='1164520'>convergence.</span>
  </p><p><span m='1165790'>So</span> <span m='1166020'>when</span> <span m='1166170'>you</span>
  <span m='1166290'>specify</span> <span m='1167490'>a</span> <span m='1167670'>Z-transform,</span>
  <span m='1168480'>generally,</span> <span m='1169170'>you</span> <span m='1169290'>have</span>
  <span m='1169500'>to</span> <span m='1169590'>tell</span> <span m='1169920'>me</span>
  <span m='1170430'>not</span> <span m='1170730'>just</span> <span m='1171000'>some</span>
  <span m='1171270'>functional</span> <span m='1171780'>form,</span> <span m='1172650'>but</span>
  <span m='1172800'>you</span> <span m='1172860'>also</span> <span m='1173160'>have</span>
  <span m='1173310'>to</span> <span m='1173400'>tell</span> <span m='1173640'>me</span>
  <span m='1174120'>what</span> <span m='1174270'>was</span> <span m='1174450'>the</span>
  <span m='1174540'>region</span> <span m='1175320'>for</span> <span m='1175470'>which</span>
  <span m='1175680'>that</span> <span m='1175830'>functional</span> <span m='1176250'>form</span>
  <span m='1176550'>converged.</span> <span m='1178780'>So</span> <span m='1179340'>in</span>
  <span m='1179490'>general,</span> <span m='1180100'>you</span> <span m='1180120'>have</span>
  <span m='1180240'>to</span> <span m='1180330'>tell</span> <span m='1180480'>me</span>
  <span m='1180570'>the</span> <span m='1180660'>region</span> <span m='1180930'>of</span>
  <span m='1181050'>convergence.</span> <span m='1182010'>In</span> <span m='1182160'>this</span>
  <span m='1182310'>particular</span> <span m='1182790'>case,</span> <span m='1183060'>you</span>
  <span m='1183180'>have</span> <span m='1183330'>to</span> <span m='1183420'>tell</span>
  <span m='1183630'>me</span> <span m='1184290'>that</span> <span m='1184470'>you</span>
  <span m='1184680'>should</span> <span m='1184890'>restrict</span> <span m='1185280'>your</span>
  <span m='1185430'>attention</span> <span m='1185910'>to</span> <span m='1186330'>values</span>
  <span m='1186870'>of</span> <span m='1187030'>z</span> <span m='1187830'>whose</span>
  <span m='1188070'>magnitude</span> <span m='1188640'>is</span> <span m='1188730'>bigger</span>
  <span m='1189030'>than</span> <span m='1189360'>7/8.</span> <span m='1191250'>OK?</span>
  </p><p><span m='1193380'>OK,</span> <span m='1193680'>that's</span> <span m='1194070'>completely</span>
  <span m='1194850'>the</span> <span m='1194940'>whole</span> <span m='1195120'>definition</span>
  <span m='1195660'>of</span> <span m='1195750'>Z-transforms.</span> <span m='1196470'>We're</span>
  <span m='1196620'>done</span> <span m='1196890'>from</span> <span m='1197070'>a</span>
  <span m='1197130'>point</span> <span m='1197400'>of</span> <span m='1197460'>view</span>
  <span m='1197670'>of</span> <span m='1197760'>mathematics,</span> <span m='1199880'>right?</span>
  <span m='1200090'>So</span> <span m='1200540'>all</span> <span m='1200660'>we</span>
  <span m='1200810'>need</span> <span m='1200990'>to</span> <span m='1201110'>know</span>
  <span m='1201470'>is</span> <span m='1201890'>that</span> <span m='1202580'>the</span>
  <span m='1202700'>Z-transform</span> <span m='1203450'>of</span> <span m='1203540'>a</span>
  <span m='1203600'>signal</span> <span m='1206030'>is</span> <span m='1206210'>some</span>
  <span m='1206480'>sum</span> <span m='1210500'>of</span> <span m='1210650'>the</span>
  <span m='1210770'>signal</span> <span m='1211830'>z</span> <span m='1212130'>to
  the</span> <span m='1212300'>minus</span> <span m='1212650'>n,</span> <span m='1213030'>and</span>
  <span m='1213130'>we're</span> <span m='1213230'>done.</span> <span m='1214280'>We</span>
  <span m='1214370'>need</span> <span m='1214550'>to</span> <span m='1214640'>know</span>
  <span m='1214760'>about</span> <span m='1214970'>the</span> <span m='1215060'>region</span>
  <span m='1215330'>of</span> <span m='1215420'>convergence,</span> <span m='1216590'>but</span>
  <span m='1216770'>mathematically,</span> <span m='1217490'>we've</span> <span m='1217670'>completely</span>
  <span m='1218120'>specified</span> <span m='1218630'>the</span> <span m='1218720'>problem</span>
  <span m='1219080'>at</span> <span m='1219170'>this</span> <span m='1219320'>point.</span>
  </p><p><span m='1220160'>To</span> <span m='1220250'>make</span> <span m='1220430'>it</span>
  <span m='1220550'>useful,</span> <span m='1221190'>however,</span> <span m='1221750'>what</span>
  <span m='1221900'>we</span> <span m='1222020'>need</span> <span m='1222170'>to</span>
  <span m='1222290'>do</span> <span m='1222410'>is</span> <span m='1222530'>investigate</span>
  <span m='1223040'>properties</span> <span m='1223490'>of</span> <span m='1223610'>that</span>
  <span m='1224840'>transformation.</span> <span m='1225740'>If</span> <span m='1225890'>the</span>
  <span m='1225980'>transformation</span> <span m='1226940'>were</span> <span m='1227060'>not</span>
  <span m='1227330'>easy</span> <span m='1227660'>to</span> <span m='1227780'>manipulate,</span>
  <span m='1228350'>we</span> <span m='1228500'>wouldn't</span> <span m='1228680'>bother</span>
  <span m='1229010'>with</span> <span m='1229160'>it.</span> <span m='1231090'>So</span>
  <span m='1231140'>we</span> <span m='1231260'>want</span> <span m='1231440'>to</span>
  <span m='1231500'>know</span> <span m='1231740'>what's</span> <span m='1232040'>easy</span>
  <span m='1232400'>to</span> <span m='1232520'>do</span> <span m='1232700'>with</span>
  <span m='1232880'>the</span> <span m='1232940'>Z-transform</span> <span m='1235810'>and</span>
  <span m='1235940'>what's</span> <span m='1236110'>not</span> <span m='1236320'>easy</span>
  <span m='1236590'>to</span> <span m='1236680'>do</span> <span m='1236830'>with</span>
  <span m='1236950'>the</span> <span m='1237010'>Z-transform.</span> </p><p><span
  m='1238210'>When</span> <span m='1238390'>something's</span> <span m='1238780'>easy</span>
  <span m='1239140'>to</span> <span m='1239260'>do</span> <span m='1239410'>with</span>
  <span m='1239570'>the</span> <span m='1239620'>Z-transform,</span> <span m='1240370'>we'll</span>
  <span m='1240490'>use</span> <span m='1240820'>it.</span> <span m='1240940'>When</span>
  <span m='1241120'>things</span> <span m='1241330'>are</span> <span m='1241450'>easier</span>
  <span m='1241870'>to</span> <span m='1241960'>do</span> <span m='1242110'>some</span>
  <span m='1242290'>other</span> <span m='1242470'>way,</span> <span m='1242920'>we</span>
  <span m='1243070'>use</span> <span m='1243310'>the</span> <span m='1243430'>other</span>
  <span m='1243610'>way.</span> <span m='1244420'>That's</span> <span m='1244660'>the</span>
  <span m='1244750'>game</span> <span m='1244960'>plan.</span> </p><p><span m='1245980'>So</span>
  <span m='1246160'>there's</span> <span m='1246340'>a</span> <span m='1246400'>number</span>
  <span m='1246670'>of</span> <span m='1246790'>properties</span> <span m='1247360'>of</span>
  <span m='1247480'>the</span> <span m='1247720'>Z-transform</span> <span m='1248650'>that</span>
  <span m='1248830'>make</span> <span m='1249100'>it</span> <span m='1249220'>easy</span>
  <span m='1249700'>or</span> <span m='1249910'>hard</span> <span m='1250330'>to</span>
  <span m='1250450'>do</span> <span m='1250630'>things.</span> <span m='1251210'>So</span>
  <span m='1251350'>we'll</span> <span m='1251500'>talk</span> <span m='1251710'>about</span>
  <span m='1251920'>the</span> <span m='1252010'>easy</span> <span m='1252280'>ones.</span>
  <span m='1253420'>The</span> <span m='1253750'>most</span> <span m='1254020'>fundamental</span>
  <span m='1254560'>one</span> <span m='1255970'>is</span> <span m='1256120'>linearity.</span>
  <span m='1258610'>Basically,</span> <span m='1259270'>this</span> <span m='1259450'>entire</span>
  <span m='1259960'>subject</span> <span m='1260890'>is</span> <span m='1261040'>about</span>
  <span m='1261490'>linear</span> <span m='1261880'>things.</span> <span m='1263590'>If</span>
  <span m='1263710'>it's</span> <span m='1263830'>not</span> <span m='1264040'>linear,</span>
  <span m='1264880'>largely,</span> <span m='1265360'>we</span> <span m='1265480'>don't</span>
  <span m='1265660'>talk</span> <span m='1265930'>about</span> <span m='1266200'>it.</span>
  </p><p><span m='1266650'>The</span> <span m='1266710'>reason</span> <span m='1267040'>is</span>
  <span m='1267160'>we</span> <span m='1267280'>have</span> <span m='1267400'>such</span>
  <span m='1267640'>powerful</span> <span m='1268060'>tools</span> <span m='1268390'>for</span>
  <span m='1268510'>thinking</span> <span m='1268840'>about</span> <span m='1269080'>things</span>
  <span m='1269290'>that</span> <span m='1269380'>are</span> <span m='1269470'>linear.</span>
  <span m='1270980'>This</span> <span m='1271270'>is</span> <span m='1271390'>one</span>
  <span m='1271610'>of</span> <span m='1271740'>them.</span> <span m='1273090'>If--</span>
  <span m='1273700'>so</span> <span m='1274810'>we</span> <span m='1274960'>say</span>
  <span m='1275140'>that</span> <span m='1275290'>the</span> <span m='1275380'>Z-transform</span>
  <span m='1276010'>is</span> <span m='1276100'>a linear</span> <span m='1276460'>operator,</span>
  <span m='1277060'>and</span> <span m='1277240'>all</span> <span m='1277390'>that</span>
  <span m='1277600'>means</span> <span m='1277990'>is</span> <span m='1279100'>if</span>
  <span m='1279250'>you</span> <span m='1279310'>apply</span> <span m='1279640'>the</span>
  <span m='1279760'>Z-transform</span> <span m='1280690'>to</span> <span m='1281020'>the</span>
  <span m='1281140'>sum</span> <span m='1281410'>of</span> <span m='1281530'>two</span>
  <span m='1281740'>things,</span> <span m='1283120'>you</span> <span m='1283270'>get</span>
  <span m='1283420'>the</span> <span m='1283540'>sum</span> <span m='1283960'>of</span>
  <span m='1284110'>the</span> <span m='1284200'>things</span> <span m='1284470'>out.</span>
  </p><p><span m='1285210'>It's</span> <span m='1285400'>a</span> <span m='1285430'>little</span>
  <span m='1285610'>more</span> <span m='1285730'>complicated</span> <span m='1286270'>than</span>
  <span m='1286390'>that.</span> <span m='1286640'>If</span> <span m='1286660'>I</span>
  <span m='1286720'>were</span> <span m='1286810'>being</span> <span m='1286990'>a</span>
  <span m='1287050'>little</span> <span m='1287260'>more</span> <span m='1287410'>careful--</span>
  <span m='1288250'>in</span> <span m='1288340'>fact,</span> <span m='1288630'>I</span>
  <span m='1288730'>didn't</span> <span m='1288790'>quite</span> <span m='1289060'>say</span>
  <span m='1289240'>a</span> <span m='1289360'>complete</span> <span m='1290710'>definition</span>
  <span m='1291220'>here.</span> <span m='1292420'>This</span> <span m='1292690'>is</span>
  <span m='1292750'>certainly</span> <span m='1293080'>true,</span> <span m='1293350'>but</span>
  <span m='1293500'>there</span> <span m='1293680'>are</span> <span m='1293950'>additional</span>
  <span m='1294370'>things</span> <span m='1294580'>that</span> <span m='1294670'>are</span>
  <span m='1294760'>also</span> <span m='1295030'>true.</span> <span m='1295870'>We</span>
  <span m='1296020'>say</span> <span m='1296260'>that</span> <span m='1296410'>the</span>
  <span m='1296470'>Z-transform</span> <span m='1297130'>is</span> <span m='1297220'>linear</span>
  <span m='1297550'>because</span> <span m='1298720'>if</span> <span m='1298870'>we</span>
  <span m='1298990'>knew</span> <span m='1299170'>the</span> <span m='1299260'>z-transform</span>
  <span m='1299980'>for</span> <span m='1300100'>X</span> <span m='1300520'>1,</span>
  <span m='1302770'>that</span> <span m='1302950'>includes</span> <span m='1303310'>a</span>
  <span m='1303370'>functional</span> <span m='1303820'>form</span> <span m='1304210'>and</span>
  <span m='1304450'>a</span> <span m='1304480'>region</span> <span m='1304780'>of</span>
  <span m='1304870'>convergence,</span> <span m='1306760'>and</span> <span m='1306970'>if</span>
  <span m='1307060'>we</span> <span m='1307150'>knew</span> <span m='1307300'>the</span>
  <span m='1307440'>Z-transform</span> <span m='1307940'>for</span> <span m='1308160'>X</span>
  <span m='1308505'>2,</span> <span m='1309380'>again,</span> <span m='1309880'>a</span>
  <span m='1309940'>functional</span> <span m='1310360'>form</span> <span m='1310720'>and</span>
  <span m='1311040'>a</span> <span m='1311080'>region</span> <span m='1311380'>of</span>
  <span m='1311470'>convergence,</span> <span m='1312580'>then</span> <span m='1313000'>by</span>
  <span m='1313120'>the</span> <span m='1313240'>linearity</span> <span m='1313730'>of</span>
  <span m='1313780'>the</span> <span m='1313900'>operator,</span> <span m='1314710'>we</span>
  <span m='1314860'>can</span> <span m='1315010'>figure</span> <span m='1315370'>out</span>
  <span m='1316480'>just</span> <span m='1316750'>from</span> <span m='1316960'>the</span>
  <span m='1317110'>two</span> <span m='1317250'>Z-transforms,</span> <span m='1318400'>what</span>
  <span m='1318520'>is</span> <span m='1318820'>the</span> <span m='1318940'>Z-transform</span>
  <span m='1319450'>of</span> <span m='1319510'>the</span> <span m='1319600'>sum.</span>
  </p><p><span m='1322300'>And</span> <span m='1322420'>that's</span> <span m='1322630'>trivial</span>
  <span m='1323050'>to</span> <span m='1323200'>see.</span> <span m='1324860'>It's</span>
  <span m='1324940'>easy</span> <span m='1325300'>to</span> <span m='1325390'>see</span>
  <span m='1325600'>why</span> <span m='1325810'>it</span> <span m='1325900'>ought</span>
  <span m='1326110'>to</span> <span m='1326230'>be</span> <span m='1326350'>that</span>
  <span m='1326590'>way.</span> <span m='1327340'>Just</span> <span m='1327580'>look</span>
  <span m='1327880'>at--</span> <span m='1328660'>let's</span> <span m='1328870'>think</span>
  <span m='1329020'>about</span> <span m='1329290'>y,</span> <span m='1329680'>which</span>
  <span m='1329920'>is</span> <span m='1330040'>the</span> <span m='1330160'>signal,</span>
  <span m='1330430'>which</span> <span m='1330610'>is</span> <span m='1330760'>the</span>
  <span m='1330880'>sum.</span> <span m='1332890'>By</span> <span m='1333070'>the</span>
  <span m='1333190'>definition</span> <span m='1333700'>of</span> <span m='1333760'>Z-transform,</span>
  <span m='1334930'>the</span> <span m='1335170'>Z-transform</span> <span m='1335455'>of</span>
  <span m='1335740'>the</span> <span m='1335860'>sum</span> <span m='1336730'>is</span>
  <span m='1337300'>that</span> <span m='1337510'>formula.</span> <span m='1341500'>Y,</span>
  <span m='1342060'>by</span> <span m='1342240'>definition,</span> <span m='1342780'>is</span>
  <span m='1342900'>that</span> <span m='1343130'>thing.</span> <span m='1345550'>Z</span>
  <span m='1346560'>commutes--</span> <span m='1347430'>distributes</span> <span m='1348030'>over</span>
  <span m='1348300'>addition,</span> <span m='1351460'>and</span> <span m='1352020'>the</span>
  <span m='1352180'>sum</span> <span m='1352510'>separates.</span> <span m='1355080'>So</span>
  <span m='1355800'>we</span> <span m='1355950'>can</span> <span m='1356190'>always</span>
  <span m='1356640'>reduce</span> <span m='1357030'>this</span> <span m='1357270'>to</span>
  <span m='1357390'>this,</span> <span m='1358050'>at</span> <span m='1358200'>least</span>
  <span m='1358560'>when</span> <span m='1358770'>the</span> <span m='1358860'>case</span>
  <span m='1360240'>that</span> <span m='1360480'>z</span> <span m='1361380'>is</span>
  <span m='1361590'>in</span> <span m='1361770'>both</span> <span m='1362010'>regions</span>
  <span m='1362400'>of</span> <span m='1362490'>convergence.</span> </p><p><span m='1364850'>Though</span>
  <span m='1365030'>later</span> <span m='1365340'>in</span> <span m='1365400'>the</span>
  <span m='1365460'>course,</span> <span m='1365760'>we'll</span> <span m='1365850'>see</span>
  <span m='1366000'>that</span> <span m='1366150'>that's</span> <span m='1366390'>a</span>
  <span m='1366450'>little</span> <span m='1366840'>overly</span> <span m='1367260'>restrictive.</span>
  <span m='1367830'>Sometimes</span> <span m='1368310'>it</span> <span m='1368370'>works</span>
  <span m='1368640'>for</span> <span m='1368970'>more</span> <span m='1369330'>zs</span>
  <span m='1370960'>than</span> <span m='1371220'>in</span> <span m='1371370'>the</span>
  <span m='1371460'>intersection.</span> <span m='1372940'>But</span> <span m='1373040'>it's</span>
  <span m='1373080'>guaranteed</span> <span m='1373680'>to</span> <span m='1373770'>work</span>
  <span m='1373980'>in</span> <span m='1374070'>the</span> <span m='1374190'>intersection,</span>
  <span m='1374790'>because</span> <span m='1375780'>I</span> <span m='1375930'>know</span>
  <span m='1376170'>that</span> <span m='1376320'>I</span> <span m='1376440'>can</span>
  <span m='1376620'>do</span> <span m='1376860'>this</span> <span m='1377100'>sum</span>
  <span m='1377910'>if</span> <span m='1378300'>z</span> <span m='1378660'>is</span>
  <span m='1378840'>in</span> <span m='1379800'>ROC</span> <span m='1380250'>1.</span>
  <span m='1380880'>I</span> <span m='1381000'>know</span> <span m='1381180'>I</span>
  <span m='1381270'>can</span> <span m='1381420'>do</span> <span m='1381640'>this</span>
  <span m='1381930'>sum</span> <span m='1382220'>if</span> <span m='1382410'>z</span>
  <span m='1382590'>is</span> <span m='1382740'>in</span> <span m='1382860'>ROC</span>
  <span m='1383310'>2.</span> </p><p><span m='1384090'>So</span> <span m='1384240'>I</span>
  <span m='1384330'>know</span> <span m='1384570'>I</span> <span m='1384690'>can</span>
  <span m='1384840'>do</span> <span m='1384990'>both</span> <span m='1385260'>of</span>
  <span m='1385410'>them</span> <span m='1385530'>if</span> <span m='1385650'>it's</span>
  <span m='1385770'>in</span> <span m='1385890'>the</span> <span m='1386010'>intersection.</span>
  <span m='1386640'>We'll</span> <span m='1386760'>see</span> <span m='1387090'>a</span>
  <span m='1387150'>little</span> <span m='1387330'>later</span> <span m='1387660'>that</span>
  <span m='1387750'>sometimes</span> <span m='1388230'>you</span> <span m='1388290'>can</span>
  <span m='1388410'>do</span> <span m='1388530'>it</span> <span m='1388890'>even</span>
  <span m='1389130'>when</span> <span m='1389250'>it's</span> <span m='1389340'>not</span>
  <span m='1389520'>in</span> <span m='1389640'>the</span> <span m='1389730'>intersection.</span>
  <span m='1390340'>But</span> <span m='1390440'>for</span> <span m='1390480'>the</span>
  <span m='1390570'>time</span> <span m='1390810'>being,</span> <span m='1391350'>we</span>
  <span m='1391470'>know</span> <span m='1391650'>you</span> <span m='1391770'>can</span>
  <span m='1391890'>do</span> <span m='1392010'>it</span> <span m='1392100'>if</span>
  <span m='1392220'>it's</span> <span m='1392340'>in</span> <span m='1392410'>the</span>
  <span m='1392530'>intersection.</span> </p><p><span m='1394980'>So</span> <span
  m='1395280'>because</span> <span m='1395700'>of</span> <span m='1395820'>linearity,</span>
  <span m='1397410'>we</span> <span m='1398730'>know</span> <span m='1399000'>that</span>
  <span m='1399420'>the</span> <span m='1400080'>Z-transform</span> <span m='1400830'>of</span>
  <span m='1400930'>a</span> <span m='1401010'>sum</span> <span m='1401610'>is</span>
  <span m='1401790'>the</span> <span m='1401850'>sum</span> <span m='1402080'>of</span>
  <span m='1402160'>the</span> <span m='1402250'>Z-transforms.</span> <span m='1403680'>I</span>
  <span m='1403740'>didn't</span> <span m='1403950'>realize</span> <span m='1404340'>when</span>
  <span m='1404460'>I</span> <span m='1404520'>made</span> <span m='1404700'>this</span>
  <span m='1404790'>slide,</span> <span m='1406190'>linearity</span> <span m='1406680'>implies</span>
  <span m='1407040'>more</span> <span m='1407280'>than</span> <span m='1407430'>that.</span>
  <span m='1408240'>I</span> <span m='1408360'>could</span> <span m='1408600'>have</span>
  <span m='1408720'>done</span> <span m='1408900'>a</span> <span m='1408960'>weighted</span>
  <span m='1409380'>sum.</span> <span m='1413110'>I</span> <span m='1413200'>could</span>
  <span m='1413410'>have</span> <span m='1413500'>said</span> <span m='1415810'>if</span>
  <span m='1416380'>X 1</span> <span m='1416770'>goes</span> <span m='1417010'>to</span>
  <span m='1417070'>X1</span> <span m='1417430'>and</span> <span m='1417550'>X 2</span>
  <span m='1417880'>goes</span> <span m='1418130'>to X 2,</span> <span m='1418570'>then</span>
  <span m='1419350'>alpha</span> <span m='1419770'>1,</span> <span m='1420550'>X 1</span>
  <span m='1420940'>plus</span> <span m='1421360'>alpha</span> <span m='1421690'>2,</span>
  <span m='1422080'>X</span> <span m='1422380'>2</span> <span m='1422650'>goes</span>
  <span m='1422950'>to</span> <span m='1423100'>alpha</span> <span m='1423490'>1,</span>
  <span m='1423840'>X</span> <span m='1424190'>1</span> <span m='1424540'>plus</span>
  <span m='1424870'>alpha</span> <span m='1425200'>2,</span> <span m='1425470'>X</span>
  <span m='1425770'>2.</span> <span m='1426430'>I</span> <span m='1426520'>should</span>
  <span m='1426780'>have</span> <span m='1426910'>put</span> <span m='1427090'>that</span>
  <span m='1427270'>in</span> <span m='1427390'>the</span> <span m='1427480'>slide,</span>
  <span m='1427690'>and</span> <span m='1427900'>it just</span> <span m='1428110'>didn't</span>
  <span m='1428310'>occur</span> <span m='1428480'>to me.</span> </p><p><span m='1430660'>So</span>
  <span m='1430870'>the</span> <span m='1431050'>idea</span> <span m='1431620'>of</span>
  <span m='1431770'>linearity</span> <span m='1432340'>is</span> <span m='1432460'>slightly</span>
  <span m='1432820'>more</span> <span m='1433000'>powerful</span> <span m='1433480'>than</span>
  <span m='1433660'>the</span> <span m='1433780'>example</span> <span m='1434200'>that</span>
  <span m='1434350'>I</span> <span m='1434410'>gave</span> <span m='1434680'>here.</span>
  <span m='1436300'>But</span> <span m='1436480'>again,</span> <span m='1437050'>linearity</span>
  <span m='1437530'>is</span> <span m='1437620'>the</span> <span m='1437710'>most</span>
  <span m='1437920'>fundamental</span> <span m='1438400'>property</span> <span m='1438760'>of</span>
  <span m='1438850'>Z-transforms.</span> <span m='1439910'>If</span> <span m='1440020'>the
  Z-transform</span> <span m='1440650'>weren't</span> <span m='1440860'>linear,</span>
  <span m='1441190'>we</span> <span m='1441310'>wouldn't</span> <span m='1441490'>bother</span>
  <span m='1441730'>with</span> <span m='1441910'>it.</span> <span m='1442910'>But</span>
  <span m='1443050'>it</span> <span m='1443110'>is,</span> <span m='1443590'>so</span>
  <span m='1443740'>we</span> <span m='1443830'>do.</span> </p><p><span m='1446080'>Another</span>
  <span m='1446590'>important</span> <span m='1447100'>property</span> <span m='1447730'>is</span>
  <span m='1448060'>the</span> <span m='1448180'>delay</span> <span m='1448540'>property.</span>
  <span m='1452930'>Think</span> <span m='1453140'>about</span> <span m='1453380'>what</span>
  <span m='1453560'>we</span> <span m='1453710'>do</span> <span m='1453980'>with</span>
  <span m='1454130'>discrete</span> <span m='1454550'>signals.</span> <span m='1455030'>We</span>
  <span m='1455120'>put</span> <span m='1455270'>them</span> <span m='1455420'>through</span>
  <span m='1455660'>discrete</span> <span m='1456140'>systems.</span> <span m='1458660'>Discrete</span>
  <span m='1459110'>systems</span> <span m='1459530'>of</span> <span m='1459650'>the</span>
  <span m='1459740'>type</span> <span m='1459980'>we've</span> <span m='1460130'>looked</span>
  <span m='1460340'>at</span> <span m='1460490'>so</span> <span m='1460700'>far</span>
  <span m='1461000'>have</span> <span m='1461210'>adders,</span> <span m='1461720'>delays,</span>
  <span m='1462740'>gains.</span> <span m='1464570'>Delays.</span> <span m='1465730'>If</span>
  <span m='1466400'>the</span> <span m='1466460'>Z-transform</span> <span m='1467120'>couldn't</span>
  <span m='1467330'>handle</span> <span m='1467630'>delays,</span> <span m='1468050'>again,</span>
  <span m='1468380'>we</span> <span m='1468530'>wouldn't</span> <span m='1469100'>do</span>
  <span m='1469310'>it,</span> <span m='1469790'>right?</span> </p><p><span m='1470690'>Delays</span>
  <span m='1471200'>are</span> <span m='1471290'>so</span> <span m='1471500'>fundamental</span>
  <span m='1472040'>to</span> <span m='1472130'>the</span> <span m='1472250'>way</span>
  <span m='1472370'>we</span> <span m='1472490'>think</span> <span m='1472670'>about</span>
  <span m='1472910'>discrete</span> <span m='1473270'>systems</span> <span m='1474080'>that</span>
  <span m='1474410'>it</span> <span m='1474590'>must</span> <span m='1474920'>be</span>
  <span m='1475070'>the</span> <span m='1475190'>case</span> <span m='1475520'>that</span>
  <span m='1475610'>Z-transforms</span> <span m='1476420'>deal</span> <span m='1476660'>with</span>
  <span m='1476870'>delays</span> <span m='1477230'>well,</span> <span m='1477560'>and</span>
  <span m='1477710'>they</span> <span m='1477860'>do.</span> <span m='1479310'>We've</span>
  <span m='1479420'>already</span> <span m='1479750'>seen</span> <span m='1479990'>two</span>
  <span m='1480200'>examples.</span> <span m='1480900'>The</span> <span m='1481000'>first</span>
  <span m='1481130'>example</span> <span m='1481520'>I</span> <span m='1481640'>did</span>
  <span m='1481850'>was</span> <span m='1482570'>the</span> <span m='1482690'>unit</span>
  <span m='1482900'>sample</span> <span m='1483980'>signal</span> <span m='1485340'>has
  a</span> <span m='1485480'>transform</span> <span m='1485990'>of</span> <span m='1486160'>1,</span>
  <span m='1487490'>and</span> <span m='1487640'>the</span> <span m='1487760'>delayed</span>
  <span m='1488150'>unit</span> <span m='1488440'>sample's</span> <span m='1489200'>signal</span>
  <span m='1489620'>has</span> <span m='1489770'>transform</span> <span m='1490280'>of</span>
  <span m='1490400'>z</span> <span m='1490620'>to</span> <span m='1490740'>the</span>
  <span m='1490820'>minus</span> <span m='1491120'>1.</span> <span m='1492050'>So</span>
  <span m='1492230'>there's</span> <span m='1492410'>a</span> <span m='1492470'>simple</span>
  <span m='1492800'>relationship--</span> <span m='1493460'>if</span> <span m='1493580'>I</span>
  <span m='1493640'>knew</span> <span m='1493820'>the</span> <span m='1493940'>first,</span>
  <span m='1494810'>how</span> <span m='1494990'>I</span> <span m='1495050'>could</span>
  <span m='1495260'>find</span> <span m='1495500'>the</span> <span m='1495590'>second.</span>
  </p><p><span m='1497060'>More</span> <span m='1497270'>generally,</span> <span m='1498330'>if</span>
  <span m='1498500'>I</span> <span m='1498680'>had</span> <span m='1499040'>a</span>
  <span m='1499130'>signal</span> <span m='1499790'>X</span> <span m='1502170'>and</span>
  <span m='1502350'>I</span> <span m='1502440'>knew</span> <span m='1502680'>its</span>
  <span m='1502830'>transform</span> <span m='1503630'>X,</span> <span m='1506060'>then</span>
  <span m='1506690'>I</span> <span m='1506840'>could</span> <span m='1507380'>readily</span>
  <span m='1507830'>compute</span> <span m='1508310'>the</span> <span m='1508530'>transform</span>
  <span m='1509710'>of</span> <span m='1509870'>the</span> <span m='1509990'>shifted</span>
  <span m='1510440'>version</span> <span m='1511280'>just</span> <span m='1511520'>from</span>
  <span m='1511670'>the</span> <span m='1511860'>transform</span> <span m='1512570'>of</span>
  <span m='1512720'>the</span> <span m='1512840'>unshifted</span> <span m='1513500'>version,</span>
  <span m='1514260'>and</span> <span m='1514400'>that's--</span> <span m='1514760'>you</span>
  <span m='1514880'>can</span> <span m='1515000'>see</span> <span m='1515180'>how</span>
  <span m='1515330'>that</span> <span m='1515510'>would</span> <span m='1515690'>work</span>
  <span m='1515900'>mathematically.</span> <span m='1516950'>Let's</span> <span m='1517130'>call</span>
  <span m='1517370'>the</span> <span m='1517460'>shifted</span> <span m='1517850'>version</span>
  <span m='1518260'>Y,</span> <span m='1520520'>then</span> <span m='1520700'>the</span>
  <span m='1520790'>transform</span> <span m='1521045'>of</span> <span m='1521300'>the</span>
  <span m='1521390'>shifted</span> <span m='1521720'>version</span> <span m='1522110'>is</span>
  <span m='1522200'>given</span> <span m='1522470'>by</span> <span m='1522590'>this</span>
  <span m='1522770'>expression.</span> <span m='1525390'>By</span> <span m='1525540'>the</span>
  <span m='1525660'>definition</span> <span m='1526200'>of</span> <span m='1526320'>shift,</span>
  <span m='1527020'>y</span> <span m='1527320'>of</span> <span m='1527420'>n</span>
  <span m='1527670'>is</span> <span m='1527820'>the</span> <span m='1527910'>same</span>
  <span m='1528120'>as</span> <span m='1528240'>x</span> <span m='1528530'>of n</span>
  <span m='1528660'>minus</span> <span m='1528990'>1.</span> </p><p><span m='1530862'>And</span>
  <span m='1531330'>now</span> <span m='1531580'>all</span> <span m='1531660'>we</span>
  <span m='1531780'>need</span> <span m='1531960'>to</span> <span m='1532080'>do</span>
  <span m='1532230'>is</span> <span m='1532350'>massage</span> <span m='1532890'>the</span>
  <span m='1533010'>math</span> <span m='1535350'>so</span> <span m='1535500'>it</span>
  <span m='1535590'>ends</span> <span m='1535770'>up</span> <span m='1535920'>looking</span>
  <span m='1536340'>like</span> <span m='1536940'>the</span> <span m='1537060'>definition</span>
  <span m='1537720'>of</span> <span m='1537900'>a</span> <span m='1537930'>Z-transform.</span>
  <span m='1539550'>So</span> <span m='1540570'>the</span> <span m='1540720'>way</span>
  <span m='1540900'>to</span> <span m='1540990'>do</span> <span m='1541140'>that</span>
  <span m='1541410'>would</span> <span m='1541530'>be</span> <span m='1541650'>to</span>
  <span m='1541770'>substitute</span> <span m='1542340'>m</span> <span m='1542640'>for</span>
  <span m='1542820'>n</span> <span m='1543000'>minus</span> <span m='1543360'>1.</span>
  <span m='1546060'>We</span> <span m='1546150'>get</span> <span m='1546300'>something</span>
  <span m='1546630'>that</span> <span m='1546720'>looks</span> <span m='1546930'>more</span>
  <span m='1547230'>like</span> <span m='1547490'>a</span> <span m='1547540'>Z-transform.</span>
  <span m='1548730'>And</span> <span m='1548850'>if</span> <span m='1548970'>we</span>
  <span m='1549060'>bring</span> <span m='1549270'>this</span> <span m='1549450'>minus
  1</span> <span m='1549810'>out</span> <span m='1550200'>front,</span> <span m='1550950'>it</span>
  <span m='1551040'>looks</span> <span m='1551220'>exactly</span> <span m='1551640'>like</span>
  <span m='1551880'>a</span> <span m='1552060'>Z-transform</span> <span m='1552450'>pre-multiplied</span>
  <span m='1553290'>by</span> <span m='1553440'>z</span> <span m='1553620'>to</span>
  <span m='1553710'>the</span> <span m='1553770'>minus</span> <span m='1554070'>1.</span>
  <span m='1556070'>So</span> <span m='1556860'>the</span> <span m='1557850'>delay</span>
  <span m='1558150'>theorem</span> <span m='1558720'>just</span> <span m='1558990'>says</span>
  <span m='1559650'>if</span> <span m='1559770'>I</span> <span m='1559890'>already</span>
  <span m='1560190'>know</span> <span m='1560340'>the</span> <span m='1560460'>Z-transform</span>
  <span m='1561060'>of</span> <span m='1561150'>a</span> <span m='1561180'>signal,</span>
  <span m='1562020'>then</span> <span m='1562380'>to</span> <span m='1562500'>find</span>
  <span m='1562770'>the</span> <span m='1562860'>Z-transform</span> <span m='1563550'>of</span>
  <span m='1563640'>the</span> <span m='1563730'>delayed</span> <span m='1564090'>version</span>
  <span m='1564600'>of</span> <span m='1564690'>that</span> <span m='1564840'>signal,</span>
  <span m='1565440'>simply</span> <span m='1565830'>multiply</span> <span m='1566460'>the</span>
  <span m='1566580'>original</span> <span m='1566865'>Z-transform</span> <span m='1567660'>by</span>
  <span m='1567870'>z to the</span> <span m='1568050'>minus</span> <span m='1568270'>1.</span>
  </p><p><span m='1570660'>OK?</span> <span m='1571140'>So</span> <span m='1571780'>so</span>
  <span m='1571960'>far,</span> <span m='1572170'>I've</span> <span m='1572260'>talked</span>
  <span m='1572500'>about</span> <span m='1572740'>two</span> <span m='1572950'>properties</span>
  <span m='1575020'>of</span> <span m='1575140'>Z-transforms,</span> <span m='1575890'>linearity</span>
  <span m='1577060'>and</span> <span m='1577810'>the</span> <span m='1577930'>delay</span>
  <span m='1578200'>property.</span> <span m='1578740'>And</span> <span m='1578980'>in</span>
  <span m='1579160'>combination,</span> <span m='1580210'>they</span> <span m='1580510'>let</span>
  <span m='1580720'>me</span> <span m='1580900'>do</span> <span m='1581290'>a</span>
  <span m='1581410'>lot</span> <span m='1581650'>of</span> <span m='1581710'>stuff</span>
  <span m='1584530'>with</span> <span m='1584710'>discrete</span> <span m='1585130'>systems.</span>
  <span m='1587470'>So</span> <span m='1587650'>think,</span> <span m='1587960'>for</span>
  <span m='1588010'>example,</span> <span m='1588650'>of</span> <span m='1588730'>a</span>
  <span m='1588880'>system,</span> <span m='1589450'>a</span> <span m='1589510'>discrete</span>
  <span m='1589870'>system</span> <span m='1590200'>that</span> <span m='1590290'>can</span>
  <span m='1590410'>be</span> <span m='1590500'>described</span> <span m='1590920'>by
  a</span> <span m='1591070'>linear</span> <span m='1591370'>difference</span> <span
  m='1591700'>equation</span> <span m='1592120'>with</span> <span m='1592240'>constant</span>
  <span m='1592620'>coefficients.</span> <span m='1596740'>If</span> <span m='1596980'>you</span>
  <span m='1597100'>can</span> <span m='1597250'>describe</span> <span m='1597760'>a</span>
  <span m='1597820'>system</span> <span m='1598210'>that</span> <span m='1598390'>way,</span>
  <span m='1599290'>then</span> <span m='1599560'>you</span> <span m='1599710'>can</span>
  <span m='1599950'>write</span> <span m='1601040'>the</span> <span m='1601190'>relationship</span>
  <span m='1601840'>between</span> <span m='1602170'>the</span> <span m='1602260'>input</span>
  <span m='1602560'>signal</span> <span m='1603460'>X</span> <span m='1604030'>and</span>
  <span m='1604180'>the</span> <span m='1604300'>output</span> <span m='1604600'>signal</span>
  <span m='1605010'>Y</span> <span m='1605860'>that</span> <span m='1605950'>looks</span>
  <span m='1606130'>like</span> <span m='1606250'>a</span> <span m='1606280'>difference</span>
  <span m='1606610'>equation.</span> </p><p><span m='1610810'>Then,</span> <span m='1611710'>if</span>
  <span m='1611860'>you</span> <span m='1611980'>take</span> <span m='1612220'>into</span>
  <span m='1612490'>account</span> <span m='1612880'>that</span> <span m='1613030'>the</span>
  <span m='1613120'>Z-transform</span> <span m='1613900'>is</span> <span m='1613990'>both</span>
  <span m='1614260'>linear</span> <span m='1615550'>and</span> <span m='1615880'>has</span>
  <span m='1616060'>a</span> <span m='1616120'>simple</span> <span m='1616480'>representation</span>
  <span m='1617260'>for</span> <span m='1617410'>delays,</span> <span m='1620460'>I</span>
  <span m='1620580'>can</span> <span m='1620730'>take</span> <span m='1620940'>the</span>
  <span m='1621030'>Z-transform</span> <span m='1622410'>of</span> <span m='1622530'>that</span>
  <span m='1622920'>difference</span> <span m='1623340'>equation</span> <span m='1623910'>and</span>
  <span m='1624060'>get</span> <span m='1624300'>a</span> <span m='1624360'>new</span>
  <span m='1626310'>expression.</span> <span m='1628030'>So</span> <span m='1628110'>the</span>
  <span m='1628290'>difference</span> <span m='1628740'>equation</span> <span m='1629190'>represents</span>
  <span m='1629730'>an equality</span> <span m='1630420'>between</span> <span m='1631260'>two</span>
  <span m='1631470'>sums</span> <span m='1632010'>of</span> <span m='1633120'>time</span>
  <span m='1633390'>domain</span> <span m='1633720'>signals.</span> <span m='1635730'>Taking</span>
  <span m='1636060'>the</span> <span m='1636180'>Z-transform</span> <span m='1636900'>of</span>
  <span m='1636990'>that</span> <span m='1637380'>equality</span> <span m='1638460'>tells</span>
  <span m='1638790'>me</span> <span m='1638970'>some</span> <span m='1640440'>equivalent</span>
  <span m='1641040'>relationship</span> <span m='1641670'>of the</span> <span m='1641820'>Z-transforms.</span>
  </p><p><span m='1644850'>So</span> <span m='1645810'>if</span> <span m='1646050'>I--</span>
  <span m='1646410'>so I</span> <span m='1646890'>think</span> <span m='1647070'>about</span>
  <span m='1647250'>the</span> <span m='1647340'>left-hand</span> <span m='1647760'>side</span>
  <span m='1648090'>by</span> <span m='1648240'>linearity,</span> <span m='1649890'>I</span>
  <span m='1650010'>can</span> <span m='1650220'>find</span> <span m='1650730'>the</span>
  <span m='1652140'>Z-transform</span> <span m='1652770'>of</span> <span m='1652860'>this</span>
  <span m='1653010'>sum</span> <span m='1653520'>by</span> <span m='1653730'>finding</span>
  <span m='1654090'>the</span> <span m='1654180'>sum</span> <span m='1654390'>of</span>
  <span m='1654450'>the</span> <span m='1654510'>Z-transforms.</span> <span m='1658620'>And</span>
  <span m='1659610'>so</span> <span m='1660060'>this</span> <span m='1660210'>one's</span>
  <span m='1660390'>easy,</span> <span m='1660720'>right?</span> <span m='1661500'>The</span>
  <span m='1661650'>Z-transform</span> <span m='1662490'>of</span> <span m='1662850'>y</span>
  <span m='1663120'>of</span> <span m='1663220'>n</span> <span m='1663480'>is,</span>
  <span m='1663630'>by</span> <span m='1663840'>assumption,</span> <span m='1664320'>y</span>
  <span m='1664590'>of</span> <span m='1664710'>z.</span> <span m='1666690'>By</span>
  <span m='1666870'>linearity,</span> <span m='1667530'>the</span> <span m='1667650'>part</span>
  <span m='1667890'>I</span> <span m='1667950'>didn't</span> <span m='1668220'>show</span>
  <span m='1668490'>you,</span> <span m='1669600'>if</span> <span m='1669750'>I</span>
  <span m='1669810'>pre-multiply</span> <span m='1670360'>by</span> <span m='1670510'>b</span>
  <span m='1670820'>nought,</span> <span m='1671040'>it's</span> <span m='1671310'>pre-multiplied</span>
  <span m='1671820'>by</span> <span m='1671970'>b</span> <span m='1672120'>nought.</span>
  </p><p><span m='1676040'>Because</span> <span m='1676370'>it's</span> <span m='1676520'>linear,</span>
  <span m='1677030'>I</span> <span m='1677120'>can</span> <span m='1677270'>just</span>
  <span m='1677480'>add</span> <span m='1677750'>the</span> <span m='1677870'>next</span>
  <span m='1678110'>term</span> <span m='1678380'>to</span> <span m='1678590'>it.</span>
  <span m='1678830'>The</span> <span m='1678920'>next</span> <span m='1679160'>term</span>
  <span m='1679430'>looks</span> <span m='1679640'>a</span> <span m='1679670'>lot</span>
  <span m='1679910'>like</span> <span m='1680090'>the</span> <span m='1680180'>previous</span>
  <span m='1680540'>term</span> <span m='1680990'>except</span> <span m='1681320'>that</span>
  <span m='1681500'>it's</span> <span m='1681560'>shifted,</span> <span m='1682210'>but</span>
  <span m='1682400'>shift</span> <span m='1682670'>is</span> <span m='1682820'>easy.</span>
  <span m='1683150'>You just</span> <span m='1683290'>put</span> <span m='1683580'>z
  to</span> <span m='1683690'>the</span> <span m='1683760'>minus</span> <span m='1683860'>1</span>
  <span m='1684240'>in</span> <span m='1684310'>front.</span> <span m='1686420'>So</span>
  <span m='1687650'>this</span> <span m='1687920'>term</span> <span m='1688280'>just</span>
  <span m='1688460'>becomes</span> <span m='1688880'>b</span> <span m='1689170'>one,</span>
  <span m='1689475'>z to the</span> <span m='1689780'>minus</span> <span m='1690100'>1.</span>
  <span m='1691300'>This</span> <span m='1691700'>just</span> <span m='1691880'>becomes</span>
  <span m='1692330'>b</span> <span m='1692510'>2,</span> <span m='1692780'>z to the</span>
  <span m='1693050'>minus</span> <span m='1693360'>2,</span> <span m='1694040'>and</span>
  <span m='1694190'>the</span> <span m='1694280'>whole</span> <span m='1694430'>thing</span>
  <span m='1694640'>factors.</span> </p><p><span m='1697190'>Same</span> <span m='1697550'>sort</span>
  <span m='1697820'>of</span> <span m='1697880'>thing</span> <span m='1698060'>happens</span>
  <span m='1698390'>on</span> <span m='1698480'>the X</span> <span m='1698790'>side,</span>
  <span m='1699590'>and</span> <span m='1699710'>you</span> <span m='1699860'>end</span>
  <span m='1700070'>up</span> <span m='1700160'>with</span> <span m='1700310'>a</span>
  <span m='1700340'>very</span> <span m='1700580'>simple</span> <span m='1700910'>statement.</span>
  <span m='1701300'>The</span> <span m='1701380'>Z-transform</span> <span m='1704340'>of</span>
  <span m='1704490'>a</span> <span m='1704520'>system</span> <span m='1704850'>that</span>
  <span m='1704940'>can</span> <span m='1705060'>be</span> <span m='1705180'>represented</span>
  <span m='1705750'>by</span> <span m='1705960'>a</span> <span m='1705980'>difference</span>
  <span m='1706350'>equation</span> <span m='1706770'>with</span> <span m='1706860'>constant</span>
  <span m='1707220'>coefficients</span> <span m='1708900'>is</span> <span m='1709110'>the</span>
  <span m='1709230'>ratio</span> <span m='1709740'>of</span> <span m='1709890'>two</span>
  <span m='1710070'>polynomials</span> <span m='1711450'>in</span> <span m='1712200'>z</span>
  <span m='1712410'>to</span> <span m='1712520'>the</span> <span m='1712620'>minus</span>
  <span m='1712920'>1--</span> <span m='1713730'>this is</span> <span m='1713790'>a</span>
  <span m='1713850'>polynomial</span> <span m='1714150'>in</span> <span m='1714450'>z</span>
  <span m='1714690'>to</span> <span m='1714870'>the</span> <span m='1714930'>minus</span>
  <span m='1715260'>1.</span> <span m='1716054'>Or</span> <span m='1716850'>if</span>
  <span m='1717000'>I</span> <span m='1717060'>multiply</span> <span m='1717510'>top</span>
  <span m='1717720'>and</span> <span m='1717810'>bottom</span> <span m='1718080'>by</span>
  <span m='1718240'>z</span> <span m='1718410'>to</span> <span m='1718500'>the</span>
  <span m='1718620'>k,</span> <span m='1720210'>I</span> <span m='1720300'>can</span>
  <span m='1720450'>make</span> <span m='1720660'>it</span> <span m='1720780'>look</span>
  <span m='1720960'>like</span> <span m='1721140'>a</span> <span m='1721200'>ratio</span>
  <span m='1721590'>of</span> <span m='1721680'>polynomials</span> <span m='1722340'>in</span>
  <span m='1722460'>z.</span> <span m='1723768'>Yeah.</span> </p><p><span m='1724242'>AUDIENCE:</span>
  <span m='1724400'>Why is</span> <span m='1724558'>it</span> <span m='1724716'>y</span>
  <span m='1725190'>to the</span> <span m='1725664'>x</span> <span m='1726138'>on
  the</span> <span m='1726612'>b 0</span> <span m='1727086'>[INAUDIBLE]</span> </p><p><span
  m='1729460'>DENNIS FREEMAN:</span> <span m='1729625'>Why</span> <span m='1729790'>is</span>
  <span m='1730000'>it</span> <span m='1730120'>y</span> <span m='1730360'>the</span>
  <span m='1730510'>x?</span> <span m='1730690'>Because</span> <span m='1731110'>of</span>
  <span m='1731350'>my</span> <span m='1732070'>poor</span> <span m='1732390'>typography.</span>
  <span m='1733390'>Thank</span> <span m='1733570'>you</span> <span m='1733720'>very</span>
  <span m='1733930'>much.</span> <span m='1734230'>That's</span> <span m='1734560'>completely</span>
  <span m='1735250'>wrong.</span> <span m='1737500'>OK,</span> <span m='1737890'>so</span>
  <span m='1738130'>I'll</span> <span m='1738310'>try</span> <span m='1738550'>to</span>
  <span m='1738640'>remember</span> <span m='1739000'>that</span> <span m='1739180'>when</span>
  <span m='1739330'>I</span> <span m='1739420'>get</span> <span m='1739600'>to</span>
  <span m='1740410'>my</span> <span m='1740590'>office</span> <span m='1741040'>and</span>
  <span m='1741190'>change</span> <span m='1741460'>it</span> <span m='1741550'>before</span>
  <span m='1741820'>I</span> <span m='1741910'>post it</span> <span m='1742300'>on</span>
  <span m='1742390'>the</span> <span m='1742480'>web.</span> <span m='1742720'>Thank</span>
  <span m='1742930'>you.</span> </p><p><span m='1743650'>So</span> <span m='1743920'>this</span>
  <span m='1744160'>is</span> <span m='1744340'>y</span> <span m='1744610'>of</span>
  <span m='1744730'>z,</span> <span m='1745000'>this</span> <span m='1745210'>is</span>
  <span m='1745310'>y of</span> <span m='1745530'>z,</span> <span m='1745940'>this</span>
  <span m='1746140'>is</span> <span m='1746240'>y of</span> <span m='1746595'>z.</span>
  <span m='1747370'>That</span> <span m='1747640'>is--</span> <span m='1748000'>and</span>
  <span m='1748180'>you</span> <span m='1748300'>can</span> <span m='1748420'>see</span>
  <span m='1748630'>I</span> <span m='1748690'>used</span> <span m='1748930'>[? e-max,
  ?]</span> <span m='1750220'>so</span> <span m='1751330'>I</span> <span m='1751600'>copied</span>
  <span m='1752020'>the</span> <span m='1752140'>formula</span> <span m='1752710'>and</span>
  <span m='1753490'>I</span> <span m='1753670'>got</span> <span m='1753910'>the</span>
  <span m='1755050'>single</span> <span m='1755530'>error</span> <span m='1755800'>to</span>
  <span m='1755920'>turn</span> <span m='1756130'>into</span> <span m='1756310'>two.</span>
  <span m='1757660'>It's</span> <span m='1757750'>always</span> <span m='1757990'>very</span>
  <span m='1758170'>good</span> <span m='1758320'>when</span> <span m='1758470'>you</span>
  <span m='1758560'>can</span> <span m='1758680'>do</span> <span m='1758800'>that,</span>
  <span m='1759040'>right?</span> <span m='1760780'>Something</span> <span m='1761110'>like</span>
  <span m='1761230'>that.</span> </p><p><span m='1762160'>OK,</span> <span m='1763000'>so</span>
  <span m='1763180'>the</span> <span m='1763270'>point</span> <span m='1763600'>then</span>
  <span m='1764320'>is</span> <span m='1764650'>that</span> <span m='1764890'>simply</span>
  <span m='1765280'>by</span> <span m='1765460'>knowing</span> <span m='1765820'>that</span>
  <span m='1766030'>the</span> <span m='1766120'>Z-transform</span> <span m='1766810'>is</span>
  <span m='1766930'>linear</span> <span m='1767890'>and</span> <span m='1768010'>has</span>
  <span m='1768190'>a</span> <span m='1768250'>delay</span> <span m='1768540'>property,</span>
  <span m='1769270'>it</span> <span m='1769390'>results</span> <span m='1769780'>in</span>
  <span m='1769900'>a</span> <span m='1769960'>very</span> <span m='1770230'>simple</span>
  <span m='1770560'>statement</span> <span m='1771070'>about</span> <span m='1771430'>the</span>
  <span m='1771490'>Z-transform</span> <span m='1772390'>for</span> <span m='1772840'>a</span>
  <span m='1772870'>system</span> <span m='1773260'>that</span> <span m='1773350'>can</span>
  <span m='1773500'>be</span> <span m='1773620'>represented</span> <span m='1774130'>by</span>
  <span m='1774280'>such</span> <span m='1774520'>a</span> <span m='1774550'>difference</span>
  <span m='1774880'>equation.</span> <span m='1778120'>OK.</span> <span m='1779080'>Now</span>
  <span m='1779350'>we</span> <span m='1779500'>use</span> <span m='1779680'>a</span>
  <span m='1779740'>little</span> <span m='1780130'>bit</span> <span m='1780460'>of</span>
  <span m='1781660'>knowledge</span> <span m='1782080'>about</span> <span m='1782290'>polynomials.</span>
  <span m='1783040'>We</span> <span m='1783190'>use</span> <span m='1783430'>the</span>
  <span m='1783580'>idea</span> <span m='1784510'>that</span> <span m='1785140'>the</span>
  <span m='1785260'>fundamental</span> <span m='1785620'>theorem in</span> <span m='1785950'>algebra--</span>
  <span m='1786640'>anybody</span> <span m='1786970'>have</span> <span m='1787060'>any</span>
  <span m='1787210'>idea</span> <span m='1787450'>what</span> <span m='1787570'>that</span>
  <span m='1787750'>is?</span> <span m='1788890'>Nah.</span> <span m='1790120'>Fundamental</span>
  <span m='1790480'>theorem</span> <span m='1790720'>of</span> <span m='1790810'>algebra,</span>
  <span m='1791140'>what?</span> </p><p><span m='1791430'>AUDIENCE:</span> <span m='1791535'>That</span>
  <span m='1791640'>was</span> <span m='1791745'>a</span> <span m='1791853'>long time</span>
  <span m='1792276'>ago.</span> </p><p><span m='1792700'>DENNIS FREEMAN:</span> <span
  m='1792910'>Long</span> <span m='1793120'>time</span> <span m='1793360'>ago.</span>
  <span m='1793690'>If</span> <span m='1793840'>it</span> <span m='1793930'>was</span>
  <span m='1794080'>long</span> <span m='1794320'>for</span> <span m='1794470'>you,</span>
  <span m='1794740'>think</span> <span m='1794920'>about</span> <span m='1795130'>when</span>
  <span m='1795310'>it</span> <span m='1795370'>was</span> <span m='1795610'>for</span>
  <span m='1795730'>me.</span> </p><p><span m='1796010'>[LAUGHTER]</span> </p><p><span
  m='1797290'>No,</span> <span m='1797470'>you</span> <span m='1797620'>can't</span>
  <span m='1797800'>think</span> <span m='1797980'>that</span> <span m='1798130'>way.</span>
  <span m='1799450'>Yes?</span> </p><p><span m='1800279'>AUDIENCE:</span> <span m='1800528'>Are
  we</span> <span m='1800778'>[INAUDIBLE]</span> </p><p><span m='1806270'>DENNIS FREEMAN:</span>
  <span m='1806490'>Wonderful.</span> <span m='1807460'>Everybody</span> <span m='1807790'>hear</span>
  <span m='1807940'>that?</span> <span m='1808310'>Because</span> <span m='1808480'>I</span>
  <span m='1808570'>can't</span> <span m='1808840'>repeat</span> <span m='1809200'>it.</span>
  <span m='1809320'>But</span> <span m='1809920'>everybody</span> <span m='1810310'>hear</span>
  <span m='1810430'>that?</span> </p><p><span m='1811750'>An</span> <span m='1811900'>nth</span>
  <span m='1812050'>order</span> <span m='1812230'>polynomial</span> <span m='1812740'>has</span>
  <span m='1812880'>n</span> <span m='1813010'>roots.</span> <span m='1815800'>Roughly</span>
  <span m='1816160'>speaking.</span> <span m='1817690'>I'm</span> <span m='1817870'>not</span>
  <span m='1818050'>a</span> <span m='1818110'>mathematician,</span> <span m='1818800'>right?</span>
  <span m='1819040'>I'm</span> <span m='1819160'>an</span> <span m='1819250'>engineer.</span>
  <span m='1820120'>Right?</span> <span m='1820930'>An</span> <span m='1821050'>nth</span>
  <span m='1821230'>order</span> <span m='1821410'>polynomial</span> <span m='1821980'>has</span>
  <span m='1822130'>n</span> <span m='1822280'>roots.</span> </p><p><span m='1824140'>OK,</span>
  <span m='1824860'>and</span> <span m='1825040'>then</span> <span m='1825190'>the</span>
  <span m='1825280'>factor</span> <span m='1825610'>theorem.</span> <span m='1826780'>Surprisingly</span>
  <span m='1827320'>enough,</span> <span m='1827560'>that</span> <span m='1827680'>says</span>
  <span m='1827860'>you</span> <span m='1827950'>can</span> <span m='1828070'>factor</span>
  <span m='1828370'>things.</span> <span m='1831170'>So</span> <span m='1831820'>the</span>
  <span m='1832000'>idea</span> <span m='1832390'>then</span> <span m='1832630'>is</span>
  <span m='1832780'>that</span> <span m='1832900'>if</span> <span m='1832990'>I</span>
  <span m='1833080'>can</span> <span m='1833290'>represent</span> <span m='1834280'>the</span>
  <span m='1834610'>Z-transform</span> <span m='1835600'>as</span> <span m='1835750'>a</span>
  <span m='1835810'>ratio</span> <span m='1836200'>of</span> <span m='1836290'>polynomials</span>
  <span m='1836980'>and</span> <span m='1837100'>z,</span> <span m='1837820'>there's</span>
  <span m='1837970'>a</span> <span m='1838030'>factored</span> <span m='1838350'>form.</span>
  <span m='1840530'>And</span> <span m='1840680'>that's</span> <span m='1841010'>the</span>
  <span m='1841100'>basis</span> <span m='1841550'>of</span> <span m='1841640'>a</span>
  <span m='1841700'>decomposition</span> <span m='1842810'>that</span> <span m='1842930'>we</span>
  <span m='1843080'>will</span> <span m='1843230'>make</span> <span m='1843590'>extensive</span>
  <span m='1844250'>use</span> <span m='1844520'>of.</span> </p><p><span m='1845150'>You've</span>
  <span m='1845330'>already</span> <span m='1845750'>seen,</span> <span m='1846020'>extensively,</span>
  <span m='1847040'>the</span> <span m='1847190'>roots</span> <span m='1847460'>of</span>
  <span m='1847520'>the</span> <span m='1847640'>denominator.</span> <span m='1848300'>They're</span>
  <span m='1848510'>the</span> <span m='1848600'>poles.</span> <span m='1849560'>We</span>
  <span m='1849680'>will</span> <span m='1849800'>similarly</span> <span m='1850450'>define,</span>
  <span m='1850910'>because</span> <span m='1851210'>of</span> <span m='1851270'>this</span>
  <span m='1851420'>manipulation,</span> <span m='1852110'>the</span> <span m='1852200'>roots</span>
  <span m='1852470'>of</span> <span m='1852530'>the</span> <span m='1852600'>numerator.</span>
  <span m='1853420'>They're</span> <span m='1853670'>the</span> <span m='1853760'>zeros.</span>
  <span m='1855890'>OK?</span> </p><p><span m='1859630'>So--</span> <span m='1860260'>and</span>
  <span m='1860500'>it's</span> <span m='1860650'>pretty</span> <span m='1860950'>easy</span>
  <span m='1861340'>to</span> <span m='1861460'>think</span> <span m='1861670'>through,</span>
  <span m='1862000'>then,</span> <span m='1862960'>how</span> <span m='1863320'>there</span>
  <span m='1863380'>is</span> <span m='1863530'>a</span> <span m='1863590'>relationship--</span>
  <span m='1865120'>it's</span> <span m='1865240'>all</span> <span m='1865390'>about</span>
  <span m='1865570'>relationships,</span> <span m='1866130'>right?</span> <span m='1867040'>When</span>
  <span m='1867310'>I</span> <span m='1867430'>introduce</span> <span m='1867820'>something,</span>
  <span m='1868180'>I</span> <span m='1868240'>want</span> <span m='1868390'>to</span>
  <span m='1868450'>think</span> <span m='1868600'>about</span> <span m='1868810'>how</span>
  <span m='1869000'>the</span> <span m='1869120'>thing</span> <span m='1869380'>I</span>
  <span m='1869470'>just</span> <span m='1869740'>said</span> <span m='1870100'>relates</span>
  <span m='1870460'>to</span> <span m='1870550'>everything</span> <span m='1870940'>else</span>
  <span m='1871150'>I've</span> <span m='1871270'>ever</span> <span m='1871510'>said.</span>
  <span m='1873130'>There's</span> <span m='1873280'>a</span> <span m='1873340'>simple</span>
  <span m='1873670'>relationship</span> <span m='1874300'>between</span> <span m='1874690'>poles</span>
  <span m='1876970'>and</span> <span m='1877180'>regions</span> <span m='1877570'>of</span>
  <span m='1877690'>convergence.</span> <span m='1879700'>Turns</span> <span m='1880000'>out</span>
  <span m='1880210'>the</span> <span m='1880300'>regions</span> <span m='1880660'>of</span>
  <span m='1880780'>convergence</span> <span m='1882010'>are</span> <span m='1882190'>always</span>
  <span m='1882490'>going</span> <span m='1882610'>to</span> <span m='1882700'>be</span>
  <span m='1882850'>circles.</span> <span m='1883570'>That</span> <span m='1883720'>has--</span>
  <span m='1884200'>circles</span> <span m='1884560'>in</span> <span m='1884650'>the</span>
  <span m='1884710'>z</span> <span m='1884890'>plane.</span> <span m='1885670'>That</span>
  <span m='1885880'>has</span> <span m='1886060'>to</span> <span m='1886180'>do</span>
  <span m='1886660'>with</span> <span m='1886870'>things</span> <span m='1887140'>like</span>
  <span m='1887290'>convergence</span> <span m='1887830'>of</span> <span m='1887890'>geometric</span>
  <span m='1888340'>sequences.</span> </p><p><span m='1892490'>If</span> <span m='1892700'>I</span>
  <span m='1892790'>build</span> <span m='1893030'>my</span> <span m='1893180'>system</span>
  <span m='1893510'>out</span> <span m='1893690'>of</span> <span m='1893810'>adders</span>
  <span m='1894290'>and</span> <span m='1894410'>delays</span> <span m='1895100'>and</span>
  <span m='1895310'>gains,</span> <span m='1897380'>then</span> <span m='1897560'>I</span>
  <span m='1897650'>have</span> <span m='1897800'>that</span> <span m='1897950'>complex</span>
  <span m='1898430'>set</span> <span m='1898820'>of</span> <span m='1899000'>reasoning</span>
  <span m='1899570'>that</span> <span m='1899720'>gives</span> <span m='1899990'>rise</span>
  <span m='1900290'>to</span> <span m='1900350'>the</span> <span m='1900470'>idea</span>
  <span m='1900740'>that</span> <span m='1900860'>I</span> <span m='1900920'>have</span>
  <span m='1901070'>polynomials.</span> <span m='1902590'>That's</span> <span m='1902810'>going</span>
  <span m='1902930'>to</span> <span m='1903020'>be--</span> <span m='1903380'>that's</span>
  <span m='1903560'>going</span> <span m='1903710'>to</span> <span m='1904430'>give</span>
  <span m='1904640'>rise</span> <span m='1905030'>to,</span> <span m='1905300'>if</span>
  <span m='1905450'>you</span> <span m='1905570'>think</span> <span m='1905750'>about</span>
  <span m='1906020'>poles,</span> <span m='1909020'>partial</span> <span m='1909320'>fractions,</span>
  <span m='1911180'>each</span> <span m='1911390'>of</span> <span m='1911510'>those</span>
  <span m='1911810'>is</span> <span m='1911900'>going</span> <span m='1912050'>to</span>
  <span m='1912110'>have</span> <span m='1912260'>some</span> <span m='1912620'>kind</span>
  <span m='1912920'>of a</span> <span m='1913070'>characteristic</span> <span m='1913760'>response.</span>
  <span m='1914240'>It's</span> <span m='1914330'>going</span> <span m='1914450'>to</span>
  <span m='1914540'>be</span> <span m='1914630'>a</span> <span m='1914690'>geometric</span>
  <span m='1915260'>sequence.</span> <span m='1915710'>Each</span> <span m='1915860'>of</span>
  <span m='1915980'>those</span> <span m='1916310'>is</span> <span m='1916400'>going</span>
  <span m='1916550'>to</span> <span m='1916610'>have</span> <span m='1916760'>a</span>
  <span m='1916820'>convergence</span> <span m='1917330'>property</span> <span m='1918110'>that</span>
  <span m='1918260'>has</span> <span m='1918380'>something</span> <span m='1918710'>to</span>
  <span m='1918830'>do</span> <span m='1918980'>with</span> <span m='1919100'>a</span>
  <span m='1919160'>circle</span> <span m='1919520'>in</span> <span m='1919640'>the</span>
  <span m='1919700'>z</span> <span m='1919880'>plane.</span> <span m='1923170'>Each</span>
  <span m='1923380'>of</span> <span m='1923440'>those</span> <span m='1923620'>circles</span>
  <span m='1924100'>is</span> <span m='1924160'>going</span> <span m='1924310'>to</span>
  <span m='1924400'>be</span> <span m='1924490'>bounded</span> <span m='1924880'>by</span>
  <span m='1925030'>a</span> <span m='1925090'>pole.</span> </p><p><span m='1927580'>So</span>
  <span m='1927850'>the</span> <span m='1927970'>upshot</span> <span m='1928330'>of</span>
  <span m='1928420'>all</span> <span m='1928540'>that</span> <span m='1928750'>stuff</span>
  <span m='1929320'>is</span> <span m='1930670'>there's</span> <span m='1930850'>a</span>
  <span m='1930910'>relationship</span> <span m='1931510'>between</span> <span m='1931840'>poles</span>
  <span m='1932320'>and</span> <span m='1932440'>regions</span> <span m='1932830'>of</span>
  <span m='1932920'>convergence.</span> <span m='1934180'>Regions</span> <span m='1934540'>of</span>
  <span m='1934660'>convergence</span> <span m='1935230'>are</span> <span m='1935320'>always</span>
  <span m='1935560'>going</span> <span m='1935680'>to</span> <span m='1935740'>be</span>
  <span m='1935830'>circles</span> <span m='1936220'>in</span> <span m='1936340'>the
  z</span> <span m='1936520'>plane,</span> <span m='1937510'>and</span> <span m='1937630'>they're</span>
  <span m='1937730'>always</span> <span m='1937960'>going</span> <span m='1938110'>to</span>
  <span m='1938170'>be</span> <span m='1938290'>bounded</span> <span m='1938740'>by
  a</span> <span m='1938920'>pole.</span> <span m='1940240'>And</span> <span m='1940390'>we've</span>
  <span m='1940540'>seen</span> <span m='1940750'>an</span> <span m='1940840'>example</span>
  <span m='1941290'>of</span> <span m='1941350'>that</span> <span m='1941500'>already.</span>
  </p><p><span m='1942430'>If</span> <span m='1942580'>we</span> <span m='1942760'>had</span>
  <span m='1943660'>a</span> <span m='1943930'>geometric</span> <span m='1944410'>sequence</span>
  <span m='1944830'>that</span> <span m='1944980'>was</span> <span m='1945520'>defined</span>
  <span m='1946780'>only</span> <span m='1947080'>to</span> <span m='1947230'>the</span>
  <span m='1947320'>right</span> <span m='1948070'>of</span> <span m='1948190'>n</span>
  <span m='1948410'>equals</span> <span m='1948630'>0--</span> <span m='1949800'>if</span>
  <span m='1949860'>it</span> <span m='1950330'>is</span> <span m='1950560'>non-zero,</span>
  <span m='1951460'>only</span> <span m='1951760'>at</span> <span m='1951850'>n</span>
  <span m='1952140'>equals</span> <span m='1952410'>0</span> <span m='1952780'>or</span>
  <span m='1952900'>bigger--</span> <span m='1954190'>then</span> <span m='1955300'>we</span>
  <span m='1955480'>get</span> <span m='1955750'>convergence</span> <span m='1956440'>inside</span>
  <span m='1957880'>some</span> <span m='1958600'>region</span> <span m='1959050'>defined</span>
  <span m='1959530'>by</span> <span m='1959800'>when</span> <span m='1960040'>the</span>
  <span m='1960160'>base</span> <span m='1962260'>has</span> <span m='1962470'>an</span>
  <span m='1962590'>absolute</span> <span m='1963070'>value</span> <span m='1963400'>that's</span>
  <span m='1963580'>less</span> <span m='1963790'>than</span> <span m='1963970'>1.</span>
  <span m='1965590'>That's</span> <span m='1965860'>a</span> <span m='1965980'>circle</span>
  <span m='1966760'>in</span> <span m='1967030'>the</span> <span m='1967150'>z</span>
  <span m='1967420'>plane.</span> <span m='1970120'>And</span> <span m='1970900'>the</span>
  <span m='1971050'>pole,</span> <span m='1971830'>which</span> <span m='1972040'>is</span>
  <span m='1972190'>alpha,</span> <span m='1973150'>turns</span> <span m='1973540'>into</span>
  <span m='1974680'>the</span> <span m='1974920'>edge</span> <span m='1976000'>of</span>
  <span m='1976150'>that</span> <span m='1976420'>circle</span> <span m='1977080'>of</span>
  <span m='1977440'>convergence.</span> <span m='1979100'>So</span> <span m='1979120'>the</span>
  <span m='1979240'>regions</span> <span m='1979630'>of</span> <span m='1979750'>convergence</span>
  <span m='1980380'>for</span> <span m='1980560'>these</span> <span m='1980800'>kinds</span>
  <span m='1981220'>of</span> <span m='1981340'>systems</span> <span m='1981790'>will</span>
  <span m='1981940'>always</span> <span m='1982330'>be</span> <span m='1982450'>circles</span>
  <span m='1982900'>in</span> <span m='1983020'>the</span> <span m='1983080'>z</span>
  <span m='1983260'>plane,</span> <span m='1984130'>always</span> <span m='1984580'>bounded</span>
  <span m='1984970'>by</span> <span m='1985150'>a</span> <span m='1985220'>pole.</span>
  </p><p><span m='1989750'>OK,</span> <span m='1990770'>enough</span> <span m='1991040'>of</span>
  <span m='1991160'>my</span> <span m='1991310'>talking.</span> <span m='1993650'>What</span>
  <span m='1994010'>DC--</span> <span m='1994850'>what</span> <span m='1995170'>DT</span>
  <span m='1995720'>signal</span> <span m='1996200'>has</span> <span m='1996410'>the</span>
  <span m='1996530'>following</span> <span m='1996980'>Z-transform?</span> <span m='2003120'>I</span>
  <span m='2003210'>want</span> <span m='2003330'>to</span> <span m='2003390'>know</span>
  <span m='2004045'>a</span> <span m='2004400'>DT</span> <span m='2004650'>signal</span>
  <span m='2005040'>that</span> <span m='2005130'>has</span> <span m='2005310'>transform</span>
  <span m='2005920'>of</span> <span m='2006060'>the</span> <span m='2006510'>form</span>
  <span m='2007170'>z over</span> <span m='2007380'>z</span> <span m='2007740'>minus</span>
  <span m='2008060'>7/8</span> <span m='2009750'>with</span> <span m='2009900'>a</span>
  <span m='2010170'>region</span> <span m='2010530'>of</span> <span m='2010620'>convergence</span>
  <span m='2011310'>inside</span> <span m='2014980'>absolute</span> <span m='2015400'>value</span>
  <span m='2015760'>of</span> <span m='2015880'>z</span> <span m='2016810'>equals</span>
  <span m='2017110'>7/8.</span> </p><p></p><p></p><p></p><p><span m='2143450'>So</span>
  <span m='2143600'>what's</span> <span m='2143810'>the</span> <span m='2143930'>DT</span>
  <span m='2144290'>signal</span> <span m='2144620'>that</span> <span m='2144740'>has</span>
  <span m='2144950'>that</span> <span m='2145640'>Z-transform?</span> </p><p><span
  m='2148194'>AUDIENCE:</span> <span m='2148437'>It would be</span> <span m='2148801'>Y</span>
  <span m='2148922'>to</span> <span m='2149043'>the</span> <span m='2149166'>n is
  equal</span> <span m='2149652'>to x to</span> <span m='2150138'>the n</span> <span
  m='2150624'>plus 7/8y</span> <span m='2151110'>to the</span> <span m='2151596'>n
  minus</span> <span m='2152082'>1?</span> </p><p><span m='2154040'>DENNIS FREEMAN:</span>
  <span m='2154190'>Sounded</span> <span m='2154340'>like</span> <span m='2154430'>a</span>
  <span m='2154490'>difference</span> <span m='2154790'>equation.</span> <span m='2155180'>Say</span>
  <span m='2155330'>it</span> <span m='2155380'>again.</span> </p><p><span m='2155580'>AUDIENCE:</span>
  <span m='2155711'>Oh</span> <span m='2155842'>yeah.</span> <span m='2155975'>Isn't
  that what</span> <span m='2156370'>you're</span> <span m='2156765'>looking for?</span>
  </p><p><span m='2157370'>DENNIS FREEMAN:</span> <span m='2157480'>No.</span> <span
  m='2157590'>I</span> <span m='2157670'>wanted</span> <span m='2157880'>the</span>
  <span m='2157940'>signal.</span> </p><p><span m='2158800'>AUDIENCE:</span> <span
  m='2158956'>Oh,</span> <span m='2159112'>OK.</span> </p><p><span m='2159740'>DENNIS
  FREEMAN:</span> <span m='2159830'>So</span> <span m='2159920'>I</span> <span m='2160040'>want</span>
  <span m='2160220'>to</span> <span m='2160280'>think</span> <span m='2160520'>about--</span>
  <span m='2161150'>this</span> <span m='2161390'>is</span> <span m='2161480'>a</span>
  <span m='2161540'>little</span> <span m='2161720'>confusing.</span> <span m='2162240'>I</span>
  <span m='2162320'>apologize</span> <span m='2162830'>if</span> <span m='2162920'>I</span>
  <span m='2162980'>didn't</span> <span m='2163160'>say</span> <span m='2163310'>this</span>
  <span m='2163490'>clearly.</span> <span m='2164220'>We</span> <span m='2164420'>motivated</span>
  <span m='2164870'>the</span> <span m='2164990'>idea</span> <span m='2165280'>of</span>
  <span m='2165340'>Z-transform</span> <span m='2165920'>by</span> <span m='2166040'>looking</span>
  <span m='2166280'>at</span> <span m='2166370'>systems,</span> <span m='2169940'>but</span>
  <span m='2170150'>the</span> <span m='2170270'>result,</span> <span m='2170900'>the</span>
  <span m='2171020'>Z-transform's</span> <span m='2171740'>just a</span> <span m='2171950'>relationship.</span>
  <span m='2172700'>It's</span> <span m='2172820'>a</span> <span m='2172880'>map</span>
  <span m='2173420'>between</span> <span m='2173720'>a</span> <span m='2173780'>function</span>
  <span m='2174080'>of</span> <span m='2174170'>n</span> <span m='2174350'>and</span>
  <span m='2174440'>a</span> <span m='2174500'>function</span> <span m='2174770'>of</span>
  <span m='2174830'>z.</span> <span m='2175050'>So</span> <span m='2175190'>we</span>
  <span m='2175250'>can</span> <span m='2175340'>do</span> <span m='2175460'>that</span>
  <span m='2175610'>for</span> <span m='2175790'>every</span> <span m='2176120'>signal.</span>
  </p><p><span m='2177750'>So</span> <span m='2177770'>if</span> <span m='2177860'>I</span>
  <span m='2177980'>tell</span> <span m='2178280'>you</span> <span m='2178400'>the</span>
  <span m='2178520'>function</span> <span m='2178850'>of</span> <span m='2178940'>z,</span>
  <span m='2179570'>you</span> <span m='2179690'>can</span> <span m='2179840'>figure</span>
  <span m='2180170'>out</span> <span m='2180380'>the</span> <span m='2180500'>function</span>
  <span m='2180830'>of</span> <span m='2180890'>n.</span> <span m='2181550'>The</span>
  <span m='2181670'>question</span> <span m='2182030'>here</span> <span m='2182340'>is</span>
  <span m='2182380'>intended--</span> <span m='2183110'>what</span> <span m='2183290'>I</span>
  <span m='2183380'>intended</span> <span m='2183770'>was,</span> <span m='2184250'>what's</span>
  <span m='2184490'>the</span> <span m='2184580'>function</span> <span m='2184910'>of</span>
  <span m='2185020'>n</span> <span m='2186950'>that</span> <span m='2187130'>corresponds</span>
  <span m='2187910'>to</span> <span m='2188060'>that</span> <span m='2189260'>function</span>
  <span m='2189650'>of</span> <span m='2189870'>z?</span> <span m='2196499'>Yes?</span>
  </p><p><span m='2196982'>AUDIENCE:</span> <span m='2197223'>[INAUDIBLE]</span> </p><p><span
  m='2200150'>DENNIS FREEMAN:</span> <span m='2200320'>7/8</span> <span m='2200490'>to
  the</span> <span m='2200810'>n,</span> <span m='2200940'>u</span> <span m='2201150'>of
  n.</span> <span m='2201990'>That</span> <span m='2202110'>sounds</span> <span m='2202350'>like</span>
  <span m='2202440'>something</span> <span m='2202710'>we</span> <span m='2202770'>did</span>
  <span m='2202890'>before.</span> <span m='2205650'>7/8</span> <span m='2207400'>to</span>
  <span m='2207670'>the</span> <span m='2207840'>n,</span> <span m='2208140'>u</span>
  <span m='2208320'>of n.</span> <span m='2209500'>That</span> <span m='2209730'>sounds</span>
  <span m='2210000'>like</span> <span m='2210090'>something</span> <span m='2210330'>we</span>
  <span m='2210390'>did</span> <span m='2210510'>before,</span> <span m='2210840'>actually.</span>
  <span m='2214590'>Yes,</span> <span m='2215160'>no?</span> </p><p><span m='2215900'>Something</span>
  <span m='2216150'>we</span> <span m='2216240'>did</span> <span m='2216360'>before</span>
  <span m='2216630'>is</span> <span m='2216720'>a</span> <span m='2216750'>good</span>
  <span m='2216930'>thing,</span> <span m='2217150'>right?</span> <span m='2217380'>That's</span>
  <span m='2217560'>one</span> <span m='2217710'>of</span> <span m='2217770'>the</span>
  <span m='2217860'>general</span> <span m='2218190'>rules,</span> <span m='2218610'>right?</span>
  <span m='2218820'>When</span> <span m='2218970'>I</span> <span m='2219000'>ask</span>
  <span m='2219170'>a</span> <span m='2219210'>question,</span> <span m='2219600'>look</span>
  <span m='2219780'>at</span> <span m='2219840'>what</span> <span m='2219930'>we</span>
  <span m='2220020'>did</span> <span m='2220140'>before.</span> <span m='2221250'>That's</span>
  <span m='2221400'>a</span> <span m='2221460'>good</span> <span m='2221580'>rule.</span>
  <span m='2224420'>Is</span> <span m='2224600'>that</span> <span m='2224900'>the</span>
  <span m='2225050'>same</span> <span m='2225740'>Z-transform</span> <span m='2226610'>we</span>
  <span m='2226700'>did</span> <span m='2226850'>before?</span> <span m='2227180'>Yes?</span>
  </p><p><span m='2227590'>AUDIENCE:</span> <span m='2227820'>[INAUDIBLE]</span> </p><p><span
  m='2230360'>DENNIS FREEMAN:</span> <span m='2230532'>Yes,</span> <span m='2231050'>yes.</span>
  <span m='2232310'>The</span> <span m='2232400'>region</span> <span m='2232730'>of</span>
  <span m='2232820'>convergence</span> <span m='2233360'>that</span> <span m='2233450'>we</span>
  <span m='2233570'>did</span> <span m='2233720'>before</span> <span m='2235490'>was</span>
  <span m='2235670'>outside</span> <span m='2237520'>7/8,</span> <span m='2238970'>and</span>
  <span m='2239120'>the</span> <span m='2239180'>region</span> <span m='2239510'>of</span>
  <span m='2239600'>convergence</span> <span m='2240110'>I</span> <span m='2240260'>asked</span>
  <span m='2240470'>for</span> <span m='2240680'>in</span> <span m='2240770'>this</span>
  <span m='2240950'>problem</span> <span m='2241340'>is</span> <span m='2241460'>inside</span>
  <span m='2241940'>7/8</span> <span m='2244490'>So</span> <span m='2244670'>what's</span>
  <span m='2244970'>the</span> <span m='2245120'>effect</span> <span m='2247430'>of</span>
  <span m='2247550'>switching</span> <span m='2248150'>the</span> <span m='2248240'>region</span>
  <span m='2248600'>of</span> <span m='2248720'>convergence?</span> <span m='2253380'>What</span>
  <span m='2253620'>happens</span> <span m='2254400'>if</span> <span m='2254580'>I</span>
  <span m='2254700'>switch</span> <span m='2255120'>the</span> <span m='2255240'>region</span>
  <span m='2255570'>of</span> <span m='2255690'>convergence?</span> </p><p><span m='2260490'>AUDIENCE:</span>
  <span m='2260656'>Does</span> <span m='2260822'>z</span> <span m='2260990'>change?</span>
  <span m='2262490'>Does</span> <span m='2262990'>the value of z</span> <span m='2263490'>change?</span>
  </p><p><span m='2264990'>DENNIS FREEMAN:</span> <span m='2265140'>Z.</span> <span
  m='2266070'>It's</span> <span m='2266250'>hard</span> <span m='2266490'>to</span>
  <span m='2266850'>talk</span> <span m='2267120'>about</span> <span m='2267330'>the</span>
  <span m='2267450'>value</span> <span m='2267870'>of</span> <span m='2267990'>z,</span>
  <span m='2268930'>right?</span> <span m='2269630'>Z.</span> </p><p><span m='2271276'>AUDIENCE:</span>
  <span m='2271525'>[INAUDIBLE]</span> </p><p><span m='2273268'>DENNIS FREEMAN:</span>
  <span m='2273435'>Excuse</span> <span m='2273602'>me.</span> <span m='2273770'>So</span>
  <span m='2274020'>z</span> <span m='2274320'>is</span> <span m='2274470'>defined--</span>
  <span m='2275390'>the</span> <span m='2275580'>Z-transform</span> <span m='2276900'>is</span>
  <span m='2277020'>defined</span> <span m='2277470'>this</span> <span m='2277650'>way.</span>
  <span m='2277940'>So</span> <span m='2278270'>I</span> <span m='2278400'>want</span>
  <span m='2278550'>to</span> <span m='2278610'>say</span> <span m='2278820'>that</span>
  <span m='2278970'>h</span> <span m='2279190'>of z</span> <span m='2281490'>is</span>
  <span m='2281640'>always</span> <span m='2282890'>z over</span> <span m='2283180'>z</span>
  <span m='2283590'>minus</span> <span m='2284930'>7/8.</span> <span m='2287910'>What</span>
  <span m='2288060'>happens</span> <span m='2288450'>if</span> <span m='2288570'>I</span>
  <span m='2288660'>say</span> <span m='2288930'>the</span> <span m='2289050'>region</span>
  <span m='2289560'>switched?</span> </p><p><span m='2291470'>Well,</span> <span m='2291810'>it</span>
  <span m='2291870'>says</span> <span m='2292050'>something</span> <span m='2292260'>about</span>
  <span m='2292440'>convergence.</span> <span m='2293160'>What's</span> <span m='2293280'>convergence</span>
  <span m='2293760'>have</span> <span m='2293910'>to</span> <span m='2294000'>do</span>
  <span m='2294120'>with?</span> <span m='2294540'>Convergence</span> <span m='2294940'>has</span>
  <span m='2295080'>to</span> <span m='2295200'>do</span> <span m='2295320'>with,</span>
  <span m='2295630'>well,</span> <span m='2296610'>I'm</span> <span m='2296760'>thinking</span>
  <span m='2297060'>about</span> <span m='2299870'>h</span> <span m='2300840'>of</span>
  <span m='2301030'>z</span> <span m='2302610'>is</span> <span m='2302940'>some</span>
  <span m='2303210'>sum</span> <span m='2303540'>over</span> <span m='2303810'>n</span>
  <span m='2304210'>of</span> <span m='2304620'>h</span> <span m='2305020'>of</span>
  <span m='2305340'>n,</span> <span m='2305700'>z</span> <span m='2305910'>to</span>
  <span m='2306000'>the</span> <span m='2306090'>minus</span> <span m='2306480'>n.</span>
  <span m='2309030'>So</span> <span m='2309180'>convergent</span> <span m='2309600'>has</span>
  <span m='2309750'>to</span> <span m='2309840'>do</span> <span m='2309990'>with</span>
  <span m='2310170'>which</span> <span m='2310440'>ones</span> <span m='2310980'>of</span>
  <span m='2311190'>those</span> <span m='2312780'>ns</span> <span m='2314340'>can</span>
  <span m='2314520'>be</span> <span m='2314760'>in</span> <span m='2314850'>the</span>
  <span m='2314990'>sum,</span> <span m='2317120'>because</span> <span m='2317450'>some</span>
  <span m='2317720'>of</span> <span m='2317870'>these</span> <span m='2318410'>terms,</span>
  <span m='2318920'>z</span> <span m='2319250'>to</span> <span m='2319460'>the</span>
  <span m='2319580'>minus</span> <span m='2320060'>n,</span> <span m='2321200'>when</span>
  <span m='2321380'>I</span> <span m='2321440'>switch</span> <span m='2321770'>the</span>
  <span m='2321890'>region,</span> <span m='2323060'>I</span> <span m='2323150'>consider</span>
  <span m='2323720'>a</span> <span m='2323780'>different</span> <span m='2324200'>family</span>
  <span m='2324740'>of</span> <span m='2324860'>z.</span> </p><p><span m='2326900'>In</span>
  <span m='2327050'>the</span> <span m='2327140'>first</span> <span m='2327530'>one,</span>
  <span m='2328760'>that</span> <span m='2329000'>sum</span> <span m='2329600'>had</span>
  <span m='2329840'>to</span> <span m='2329930'>converge</span> <span m='2330980'>outside</span>
  <span m='2332330'>the</span> <span m='2332450'>circle.</span> <span m='2333780'>And</span>
  <span m='2333810'>in</span> <span m='2333920'>the</span> <span m='2334010'>question</span>
  <span m='2334400'>of</span> <span m='2334590'>interest</span> <span m='2334760'>now,</span>
  <span m='2334970'>it</span> <span m='2335060'>has</span> <span m='2335210'>to</span>
  <span m='2335270'>converge</span> <span m='2335720'>inside.</span> <span m='2336590'>So</span>
  <span m='2336740'>it's</span> <span m='2336830'>a</span> <span m='2336890'>different</span>
  <span m='2337280'>set</span> <span m='2337970'>of</span> <span m='2338210'>zs</span>
  <span m='2338840'>for</span> <span m='2339080'>which</span> <span m='2339410'>the</span>
  <span m='2339560'>sum</span> <span m='2340160'>has</span> <span m='2340580'>to</span>
  <span m='2340710'>converge.</span> </p><p><span m='2343290'>There's</span> <span
  m='2343500'>a</span> <span m='2343540'>way</span> <span m='2343690'>you</span> <span
  m='2343780'>can</span> <span m='2343900'>think</span> <span m='2344080'>about</span>
  <span m='2344260'>that.</span> <span m='2344930'>Think</span> <span m='2344980'>about</span>
  <span m='2345160'>that</span> <span m='2345340'>sum--</span> <span m='2345910'>think</span>
  <span m='2346090'>about</span> <span m='2346270'>exploding</span> <span m='2346780'>that</span>
  <span m='2346960'>sum.</span> <span m='2349560'>In</span> <span m='2349720'>general,</span>
  <span m='2350110'>we're</span> <span m='2350200'>going</span> <span m='2350320'>to</span>
  <span m='2350380'>go</span> <span m='2350530'>from</span> <span m='2350710'>minus</span>
  <span m='2351010'>infinity</span> <span m='2351430'>to</span> <span m='2351550'>infinity,</span>
  <span m='2351980'>so</span> <span m='2352270'>explode</span> <span m='2352690'>that.</span>
  <span m='2353020'>So</span> <span m='2353260'>we</span> <span m='2353380'>get</span>
  <span m='2354520'>a</span> <span m='2354940'>whole</span> <span m='2355120'>bunch</span>
  <span m='2355360'>of</span> <span m='2355420'>stuff.</span> </p><p><span m='2356290'>Then</span>
  <span m='2356440'>we</span> <span m='2356530'>get</span> <span m='2356710'>up</span>
  <span m='2356860'>to</span> <span m='2357730'>h</span> <span m='2358050'>of</span>
  <span m='2358270'>minus</span> <span m='2358660'>2,</span> <span m='2360180'>z</span>
  <span m='2360580'>squared.</span> <span m='2361780'>Then</span> <span m='2361930'>we</span>
  <span m='2362080'>have</span> <span m='2362470'>h of</span> <span m='2362950'>minus</span>
  <span m='2363370'>1,</span> <span m='2364244'>z.</span> <span m='2365890'>Then</span>
  <span m='2366040'>we</span> <span m='2366160'>have</span> <span m='2366850'>h</span>
  <span m='2367020'>of</span> <span m='2367130'>0,</span> <span m='2368474'>z to the</span>
  <span m='2368922'>0,</span> <span m='2369370'>which</span> <span m='2369550'>is</span>
  <span m='2369670'>1.</span> <span m='2370790'>Then</span> <span m='2370840'>we</span>
  <span m='2370960'>have</span> <span m='2371200'>h</span> <span m='2371500'>of</span>
  <span m='2371660'>1,</span> <span m='2374610'>z</span> <span m='2374890'>to</span>
  <span m='2375020'>the</span> <span m='2375100'>minus</span> <span m='2375460'>1.</span>
  <span m='2376060'>Then</span> <span m='2376180'>we</span> <span m='2376270'>have</span>
  <span m='2376390'>h</span> <span m='2376630'>of</span> <span m='2376780'>2,</span>
  <span m='2378760'>z to</span> <span m='2379000'>the</span> <span m='2379090'>minus</span>
  <span m='2379640'>2,</span> <span m='2380460'>et</span> <span m='2380795'>cetera.</span>
  <span m='2381130'>Right?</span> <span m='2381340'>That's</span> <span m='2381520'>what</span>
  <span m='2381670'>the</span> <span m='2381730'>Z-transform</span> <span m='2382420'>always</span>
  <span m='2382870'>looks</span> <span m='2383110'>like.</span> </p><p><span m='2384160'>Which</span>
  <span m='2384490'>of</span> <span m='2384580'>those</span> <span m='2384910'>terms</span>
  <span m='2385540'>are</span> <span m='2385720'>the</span> <span m='2385840'>most</span>
  <span m='2386260'>convergent</span> <span m='2389160'>when</span> <span m='2389360'>I</span>
  <span m='2389420'>have</span> <span m='2389660'>a</span> <span m='2389720'>z</span>
  <span m='2390260'>with</span> <span m='2390470'>a</span> <span m='2390590'>large</span>
  <span m='2391130'>magnitude?</span> <span m='2397030'>So</span> <span m='2397350'>I'm</span>
  <span m='2397550'>thinking</span> <span m='2397820'>about</span> <span m='2398660'>the</span>
  <span m='2398870'>n equals</span> <span m='2399320'>minus</span> <span m='2399680'>2,</span>
  <span m='2400020'>n</span> <span m='2400220'>equals</span> <span m='2400490'>minus</span>
  <span m='2400850'>1,</span> <span m='2401300'>n</span> <span m='2401390'>equals</span>
  <span m='2401630'>0.</span> <span m='2402410'>I'm</span> <span m='2402530'>thinking</span>
  <span m='2402710'>about</span> <span m='2402860'>all</span> <span m='2403100'>the</span>
  <span m='2403220'>terms</span> <span m='2403610'>and</span> <span m='2403790'>Ys.</span>
  <span m='2405500'>Which</span> <span m='2405710'>of</span> <span m='2405830'>those</span>
  <span m='2406130'>terms</span> <span m='2406700'>is</span> <span m='2406850'>the</span>
  <span m='2406970'>most</span> <span m='2407390'>convergent</span> <span m='2409730'>if</span>
  <span m='2409970'>z</span> <span m='2411260'>has</span> <span m='2411530'>a</span>
  <span m='2411620'>large</span> <span m='2412160'>magnitude?</span> </p><p><span
  m='2414800'>AUDIENCE:</span> <span m='2414899'>I</span> <span m='2414998'>think</span>
  <span m='2415097'>it</span> <span m='2415196'>would</span> <span m='2415295'>be</span>
  <span m='2415790'>z of</span> <span m='2416285'>negative</span> <span m='2416780'>n.</span>
  <span m='2417275'>Like, any</span> <span m='2417770'>negative.</span> </p><p><span
  m='2419260'>DENNIS FREEMAN:</span> <span m='2419285'>So</span> <span m='2419310'>they</span>
  <span m='2419460'>get</span> <span m='2419730'>increasingly</span> <span m='2420550'>convergent</span>
  <span m='2421290'>as</span> <span m='2421470'>I</span> <span m='2421560'>go</span>
  <span m='2421830'>to</span> <span m='2422010'>the</span> <span m='2422250'>right.</span>
  <span m='2424360'>If</span> <span m='2424510'>I</span> <span m='2424630'>have</span>
  <span m='2424870'>z</span> <span m='2425320'>with</span> <span m='2425530'>a</span>
  <span m='2425620'>big</span> <span m='2426010'>magnitude,</span> <span m='2427600'>each</span>
  <span m='2427900'>term</span> <span m='2428770'>is</span> <span m='2428920'>getting</span>
  <span m='2429220'>increasingly</span> <span m='2429850'>convergent</span> <span
  m='2430420'>as</span> <span m='2430570'>I</span> <span m='2430660'>go</span> <span
  m='2430870'>to</span> <span m='2430990'>the</span> <span m='2431110'>right.</span>
  <span m='2433080'>That</span> <span m='2433280'>means</span> <span m='2434960'>that</span>
  <span m='2435410'>these</span> <span m='2435740'>numbers</span> <span m='2437250'>h</span>
  <span m='2437590'>0,</span> <span m='2437920'>h 1,</span> <span m='2438140'>h</span>
  <span m='2438563'>2,</span> <span m='2438986'>h 3,</span> <span m='2439760'>they</span>
  <span m='2439940'>can</span> <span m='2440150'>keep</span> <span m='2440480'>being</span>
  <span m='2440930'>some</span> <span m='2441230'>finite</span> <span m='2441710'>number.</span>
  <span m='2442250'>They</span> <span m='2442370'>don't</span> <span m='2442550'>need</span>
  <span m='2442700'>to</span> <span m='2442790'>be</span> <span m='2442910'>0.</span>
  <span m='2444230'>And</span> <span m='2444380'>it</span> <span m='2444500'>will</span>
  <span m='2444680'>increasingly</span> <span m='2445640'>come</span> <span m='2445970'>closer</span>
  <span m='2446450'>to</span> <span m='2446630'>0</span> <span m='2447650'>as</span>
  <span m='2447800'>I</span> <span m='2447890'>keep</span> <span m='2448100'>going</span>
  <span m='2448430'>to</span> <span m='2448550'>the</span> <span m='2448640'>right.</span>
  </p><p><span m='2450180'>The</span> <span m='2450280'>implication</span> <span m='2450740'>of</span>
  <span m='2450830'>that</span> <span m='2451370'>is</span> <span m='2451490'>something</span>
  <span m='2451760'>that's</span> <span m='2451910'>very</span> <span m='2452120'>important.</span>
  <span m='2453630'>So</span> <span m='2455780'>the</span> <span m='2455870'>implication</span>
  <span m='2456380'>of</span> <span m='2456470'>that</span> <span m='2457280'>is</span>
  <span m='2457520'>that</span> <span m='2458180'>a</span> <span m='2458330'>right-sided</span>
  <span m='2459170'>signal--</span> <span m='2463730'>signal,</span> <span m='2464900'>not</span>
  <span m='2465110'>single--</span> <span m='2469340'>has</span> <span m='2469520'>a--</span>
  <span m='2470180'>maps</span> <span m='2470510'>to</span> <span m='2470720'>an</span>
  <span m='2470870'>outside</span> <span m='2471410'>region.</span> <span m='2477130'>If</span>
  <span m='2477250'>I</span> <span m='2477370'>want</span> <span m='2477740'>the</span>
  <span m='2478180'>sum</span> <span m='2478870'>to</span> <span m='2479200'>get</span>
  <span m='2479680'>increasingly</span> <span m='2480490'>convergent</span> <span
  m='2482720'>for</span> <span m='2483560'>large</span> <span m='2484010'>values</span>
  <span m='2484550'>of</span> <span m='2484640'>z,</span> <span m='2485420'>outside</span>
  <span m='2485930'>regions--</span> <span m='2486560'>outside</span> <span m='2486920'>regions</span>
  <span m='2487220'>have</span> <span m='2487370'>to</span> <span m='2487520'>take</span>
  <span m='2487760'>all</span> <span m='2488010'>the</span> <span m='2488120'>values,</span>
  <span m='2488540'>no</span> <span m='2488660'>matter</span> <span m='2488900'>how</span>
  <span m='2489050'>big</span> <span m='2489260'>they</span> <span m='2489410'>get.</span>
  <span m='2491180'>OK,</span> <span m='2491430'>I</span> <span m='2491570'>want</span>
  <span m='2491750'>things</span> <span m='2492020'>to</span> <span m='2492140'>be</span>
  <span m='2492290'>on</span> <span m='2492410'>the</span> <span m='2492530'>right.</span>
  <span m='2492860'>I</span> <span m='2492920'>don't</span> <span m='2493040'>want</span>
  <span m='2493220'>things</span> <span m='2493400'>to</span> <span m='2493520'>be</span>
  <span m='2493640'>on</span> <span m='2493730'>the</span> <span m='2493790'>left.</span>
  <span m='2495710'>Things</span> <span m='2495980'>on</span> <span m='2496100'>the</span>
  <span m='2496190'>left</span> <span m='2496490'>become</span> <span m='2496860'>decreasingly</span>
  <span m='2497640'>convergent.</span> </p><p><span m='2500650'>And</span> <span m='2500910'>a</span>
  <span m='2501560'>corollary</span> <span m='2501950'>of that,</span> <span m='2502850'>left-sided</span>
  <span m='2503510'>signals</span> <span m='2509270'>map</span> <span m='2509750'>to</span>
  <span m='2510140'>inside</span> <span m='2512450'>regions.</span> <span m='2514370'>So</span>
  <span m='2514460'>in</span> <span m='2514520'>fact,</span> <span m='2514860'>it's</span>
  <span m='2514960'>not</span> <span m='2515060'>a</span> <span m='2515120'>fluke</span>
  <span m='2516050'>that</span> <span m='2516260'>this</span> <span m='2516500'>right-handed</span>
  <span m='2517190'>signal</span> <span m='2518000'>mapped</span> <span m='2518300'>to</span>
  <span m='2518450'>this</span> <span m='2518750'>outside</span> <span m='2519350'>region.</span>
  <span m='2520370'>That's</span> <span m='2520610'>where</span> <span m='2520850'>the</span>
  <span m='2520970'>convergence</span> <span m='2521600'>for</span> <span m='2521780'>things</span>
  <span m='2522110'>to</span> <span m='2522260'>the</span> <span m='2522380'>right</span>
  <span m='2522740'>are</span> <span m='2522920'>the</span> <span m='2523010'>best.</span>
  </p><p><span m='2525450'>OK.</span> <span m='2525790'>Now</span> <span m='2525960'>I've</span>
  <span m='2526000'>just</span> <span m='2526150'>told</span> <span m='2526360'>you</span>
  <span m='2526450'>everything</span> <span m='2526780'>you</span> <span m='2526840'>need</span>
  <span m='2527020'>to</span> <span m='2527110'>know.</span> <span m='2527800'>What's</span>
  <span m='2528050'>it</span> <span m='2528130'>going</span> <span m='2528280'>to--</span>
  <span m='2528580'>what</span> <span m='2528850'>do</span> <span m='2528970'>I</span>
  <span m='2529060'>need</span> <span m='2529240'>to</span> <span m='2529330'>have</span>
  <span m='2529630'>happen</span> <span m='2531400'>if</span> <span m='2531550'>I</span>
  <span m='2531640'>want it</span> <span m='2531940'>to</span> <span m='2532090'>converge</span>
  <span m='2532450'>to</span> <span m='2532570'>the</span> <span m='2532660'>inside</span>
  <span m='2532960'>region?</span> <span m='2536540'>Flip</span> <span m='2536840'>the</span>
  <span m='2536960'>signal.</span> <span m='2537860'>More</span> <span m='2538190'>or</span>
  <span m='2538280'>less,</span> <span m='2538660'>I</span> <span m='2538760'>want</span>
  <span m='2538960'>it</span> <span m='2539120'>to</span> <span m='2539240'>go</span>
  <span m='2539450'>to</span> <span m='2539630'>the</span> <span m='2539940'>left.</span>
  <span m='2540860'>I</span> <span m='2540920'>don't</span> <span m='2541130'>want</span>
  <span m='2541340'>it</span> <span m='2541400'>to</span> <span m='2541490'>go</span>
  <span m='2541640'>to</span> <span m='2541730'>the</span> <span m='2541820'>right.</span>
  </p><p><span m='2543880'>So</span> <span m='2545190'>the</span> <span m='2545340'>way</span>
  <span m='2545550'>I</span> <span m='2545640'>can</span> <span m='2545790'>think</span>
  <span m='2546000'>about</span> <span m='2546270'>that</span> <span m='2548400'>is</span>
  <span m='2548580'>by</span> <span m='2549090'>thinking</span> <span m='2549510'>about</span>
  <span m='2550440'>the</span> <span m='2550560'>functional</span> <span m='2551070'>form</span>
  <span m='2551850'>is</span> <span m='2552090'>the</span> <span m='2552210'>same</span>
  <span m='2555490'>for</span> <span m='2555640'>the</span> <span m='2555730'>inside</span>
  <span m='2556000'>and the</span> <span m='2556060'>outside</span> <span m='2556330'>region.</span>
  <span m='2558550'>That</span> <span m='2558760'>means</span> <span m='2559060'>they</span>
  <span m='2559180'>have</span> <span m='2559390'>the</span> <span m='2559510'>same</span>
  <span m='2559810'>difference</span> <span m='2560230'>equation,</span> <span m='2562400'>because</span>
  <span m='2562670'>you</span> <span m='2562760'>can</span> <span m='2562850'>find</span>
  <span m='2563060'>the</span> <span m='2563150'>difference</span> <span m='2563420'>equation</span>
  <span m='2563780'>from</span> <span m='2563960'>the</span> <span m='2563990'>functional</span>
  <span m='2564350'>form.</span> <span m='2566210'>But</span> <span m='2566690'>the</span>
  <span m='2566840'>way</span> <span m='2566990'>I</span> <span m='2567050'>want</span>
  <span m='2567230'>to</span> <span m='2567290'>think</span> <span m='2567500'>about</span>
  <span m='2567770'>it</span> <span m='2567970'>is</span> <span m='2568130'>propagating</span>
  <span m='2568820'>the</span> <span m='2568940'>signal</span> <span m='2569390'>that</span>
  <span m='2569540'>came</span> <span m='2569900'>in</span> <span m='2570290'>to</span>
  <span m='2570440'>the</span> <span m='2570560'>right</span> <span m='2570800'>or</span>
  <span m='2570890'>to</span> <span m='2571010'>the</span> <span m='2571100'>left.</span>
  <span m='2572450'>So</span> <span m='2572660'>rather</span> <span m='2573080'>then</span>
  <span m='2573320'>iterating</span> <span m='2573860'>forward</span> <span m='2574340'>in</span>
  <span m='2574460'>time,</span> <span m='2575390'>which</span> <span m='2575570'>is</span>
  <span m='2575660'>what</span> <span m='2575750'>we</span> <span m='2575840'>did</span>
  <span m='2575960'>before,</span> <span m='2577370'>one</span> <span m='2577610'>way</span>
  <span m='2577790'>I</span> <span m='2577880'>can</span> <span m='2578030'>think</span>
  <span m='2578180'>about</span> <span m='2578430'>it is,</span> <span m='2578900'>let's</span>
  <span m='2579080'>iterate</span> <span m='2579470'>backwards</span> <span m='2579980'>in</span>
  <span m='2580070'>time.</span> </p><p><span m='2581690'>Rather</span> <span m='2582050'>than</span>
  <span m='2582230'>solving</span> <span m='2584060'>for</span> <span m='2584270'>y</span>
  <span m='2584510'>of</span> <span m='2584630'>n</span> <span m='2584750'>plus</span>
  <span m='2584990'>1</span> <span m='2585200'>in</span> <span m='2585290'>terms</span>
  <span m='2585560'>of</span> <span m='2585650'>y</span> <span m='2585990'>of n,</span>
  <span m='2587270'>solve</span> <span m='2587600'>instead</span> <span m='2588110'>for</span>
  <span m='2588230'>y</span> <span m='2588500'>of n</span> <span m='2588680'>in</span>
  <span m='2588770'>terms</span> <span m='2588980'>of</span> <span m='2589040'>y</span>
  <span m='2589350'>of n</span> <span m='2589400'>plus</span> <span m='2589610'>1.</span>
  <span m='2591050'>Run</span> <span m='2591320'>it</span> <span m='2591440'>backwards.</span>
  <span m='2593180'>Difference</span> <span m='2593480'>equation</span> <span m='2593840'>doesn't</span>
  <span m='2594080'>care.</span> <span m='2596160'>If</span> <span m='2596310'>the</span>
  <span m='2596400'>difference</span> <span m='2596730'>equation</span> <span m='2597090'>doesn't</span>
  <span m='2597300'>care,</span> <span m='2597580'>the</span> <span m='2597680'>functional</span>
  <span m='2597990'>form</span> <span m='2598260'>will</span> <span m='2598350'>be</span>
  <span m='2598470'>the</span> <span m='2598560'>same.</span> <span m='2601180'>So</span>
  <span m='2601590'>run</span> <span m='2601860'>the</span> <span m='2601950'>difference</span>
  <span m='2602310'>equation</span> <span m='2602730'>backwards.</span> </p><p><span
  m='2604580'>So</span> <span m='2604630'>if</span> <span m='2604720'>you</span> <span
  m='2604810'>think</span> <span m='2604990'>about</span> <span m='2605200'>doing</span>
  <span m='2605530'>that,</span> <span m='2607780'>rest</span> <span m='2609070'>starts</span>
  <span m='2609460'>to</span> <span m='2609580'>say,</span> <span m='2610290'>the</span>
  <span m='2610400'>system</span> <span m='2610780'>starts--</span> <span m='2612670'>starts</span>
  <span m='2613030'>means</span> <span m='2613660'>future</span> <span m='2614020'>times,</span>
  <span m='2615010'>OK,</span> <span m='2615430'>because</span> <span m='2615790'>we're</span>
  <span m='2615940'>flipped.</span> <span m='2617620'>So</span> <span m='2617770'>the</span>
  <span m='2617890'>signal</span> <span m='2618220'>starts</span> <span m='2618580'>at</span>
  <span m='2618640'>0.</span> <span m='2619000'>That</span> <span m='2619120'>means</span>
  <span m='2619330'>it</span> <span m='2619420'>starts--</span> <span m='2619960'>that</span>
  <span m='2620080'>means</span> <span m='2620300'>at</span> <span m='2620800'>large</span>
  <span m='2621280'>values</span> <span m='2621730'>of</span> <span m='2621860'>n,</span>
  <span m='2622450'>the</span> <span m='2622570'>signal</span> <span m='2622990'>y</span>
  <span m='2623350'>is</span> <span m='2623440'>0.</span> <span m='2625450'>So</span>
  <span m='2625570'>I</span> <span m='2625660'>fill</span> <span m='2625900'>in</span>
  <span m='2626050'>this</span> <span m='2626200'>table</span> <span m='2626500'>with</span>
  <span m='2626650'>a</span> <span m='2626680'>bunch</span> <span m='2626890'>of</span>
  <span m='2626980'>zeros</span> <span m='2628330'>for</span> <span m='2628960'>big</span>
  <span m='2629200'>values</span> <span m='2629890'>of</span> <span m='2630410'>n.</span>
  <span m='2631420'>So</span> <span m='2632100'>n's</span> <span m='2632380'>decreasing</span>
  <span m='2632950'>this</span> <span m='2633130'>way.</span> <span m='2633640'>I'm</span>
  <span m='2633760'>working</span> <span m='2634150'>from</span> <span m='2634630'>toward--</span>
  <span m='2635140'>0</span> <span m='2635560'>toward</span> <span m='2635830'>the</span>
  <span m='2635950'>left.</span> </p><p><span m='2638340'>So</span> <span m='2638460'>I</span>
  <span m='2638640'>assume</span> <span m='2639120'>that</span> <span m='2639270'>I</span>
  <span m='2639390'>start</span> <span m='2639690'>at</span> <span m='2639900'>rest.</span>
  <span m='2640290'>That</span> <span m='2640440'>means</span> <span m='2640740'>the</span>
  <span m='2641310'>output</span> <span m='2641880'>is</span> <span m='2642000'>0</span>
  <span m='2642405'>for</span> <span m='2642810'>times</span> <span m='2643260'>on</span>
  <span m='2643410'>the</span> <span m='2643530'>right.</span> <span m='2646880'>I</span>
  <span m='2647000'>want</span> <span m='2647150'>to</span> <span m='2647210'>find</span>
  <span m='2647420'>the</span> <span m='2647510'>unit</span> <span m='2647720'>sample</span>
  <span m='2648050'>response,</span> <span m='2648500'>so</span> <span m='2648740'>x</span>
  <span m='2649130'>is</span> <span m='2649340'>1</span> <span m='2649730'>only</span>
  <span m='2650140'>at n</span> <span m='2650300'>equals</span> <span m='2651260'>0.</span>
  <span m='2653070'>And</span> <span m='2653170'>now</span> <span m='2653390'>I</span>
  <span m='2653450'>just</span> <span m='2653630'>compute</span> <span m='2654440'>each</span>
  <span m='2654710'>entry</span> <span m='2656780'>by</span> <span m='2656930'>sticking</span>
  <span m='2657320'>it</span> <span m='2657410'>into</span> <span m='2657590'>the</span>
  <span m='2657680'>difference</span> <span m='2657980'>equation.</span> </p><p><span
  m='2659610'>And</span> <span m='2659660'>so</span> <span m='2659780'>I've</span>
  <span m='2659900'>done</span> <span m='2660080'>that.</span> <span m='2660970'>So</span>
  <span m='2661130'>you</span> <span m='2661700'>stick</span> <span m='2662960'>these</span>
  <span m='2663320'>values</span> <span m='2663890'>into</span> <span m='2664100'>the</span>
  <span m='2664220'>difference</span> <span m='2664550'>equation,</span> <span m='2665060'>and</span>
  <span m='2665180'>that</span> <span m='2665330'>lets</span> <span m='2665510'>you</span>
  <span m='2665630'>compute</span> <span m='2667000'>y</span> <span m='2667280'>of</span>
  <span m='2667400'>minus</span> <span m='2667730'>1.</span> <span m='2669210'>So</span>
  <span m='2669320'>substitute</span> <span m='2669800'>y</span> <span m='2670010'>of</span>
  <span m='2670100'>minus</span> <span m='2670430'>1.</span> <span m='2671300'>Y</span>
  <span m='2671500'>of</span> <span m='2671600'>minus</span> <span m='2671930'>1,</span>
  <span m='2672350'>it</span> <span m='2672530'>depends</span> <span m='2672920'>on</span>
  <span m='2673040'>y</span> <span m='2673280'>of</span> <span m='2673400'>0</span>
  <span m='2674810'>and</span> <span m='2675140'>x</span> <span m='2675350'>of</span>
  <span m='2675440'>0.</span> <span m='2677720'>Similarly</span> <span m='2678290'>for</span>
  <span m='2678440'>all</span> <span m='2678560'>the</span> <span m='2678680'>entries,</span>
  <span m='2680540'>and</span> <span m='2680690'>then</span> <span m='2680840'>I</span>
  <span m='2680930'>can</span> <span m='2681050'>make</span> <span m='2681230'>a</span>
  <span m='2681260'>plot</span> <span m='2681560'>of</span> <span m='2681680'>that,</span>
  <span m='2682190'>and</span> <span m='2682340'>I</span> <span m='2682400'>get</span>
  <span m='2682550'>a</span> <span m='2682610'>function</span> <span m='2682910'>that</span>
  <span m='2683000'>looks</span> <span m='2683180'>like</span> <span m='2683380'>this.</span>
  </p><p><span m='2687250'>It's</span> <span m='2687380'>a</span> <span m='2687440'>geometric.</span>
  <span m='2688130'>I'm</span> <span m='2688250'>not</span> <span m='2688400'>surprised</span>
  <span m='2688820'>by</span> <span m='2689000'>that.</span> <span m='2690590'>The</span>
  <span m='2690770'>geometric</span> <span m='2691370'>is</span> <span m='2691490'>kind</span>
  <span m='2691700'>of</span> <span m='2691760'>facing</span> <span m='2692120'>the</span>
  <span m='2692210'>wrong</span> <span m='2692480'>way.</span> <span m='2693230'>It</span>
  <span m='2693350'>was</span> <span m='2693700'>7/8</span> <span m='2693980'>to</span>
  <span m='2694260'>the</span> <span m='2694530'>end.</span> <span m='2694750'>It</span>
  <span m='2694850'>looked</span> <span m='2695150'>convergent.</span> <span m='2697130'>This</span>
  <span m='2697310'>one</span> <span m='2697490'>looks</span> <span m='2697790'>divergent</span>
  <span m='2698390'>that</span> <span m='2698660'>way,</span> <span m='2700210'>but</span>
  <span m='2700640'>I'm</span> <span m='2700790'>multiplying</span> <span m='2702590'>these</span>
  <span m='2702890'>h</span> <span m='2703220'>numbers,</span> <span m='2704130'>which</span>
  <span m='2704240'>are</span> <span m='2704330'>blowing</span> <span m='2704780'>up</span>
  <span m='2705170'>that</span> <span m='2705590'>way,</span> <span m='2707480'>by</span>
  <span m='2707720'>numbers</span> <span m='2708110'>that</span> <span m='2708230'>look</span>
  <span m='2708380'>like</span> <span m='2708590'>z</span> <span m='2708770'>squared.</span>
  <span m='2709740'>So</span> <span m='2709760'>if</span> <span m='2709850'>I</span>
  <span m='2709940'>make</span> <span m='2710090'>z</span> <span m='2710270'>squared</span>
  <span m='2710540'>small</span> <span m='2710900'>enough,</span> <span m='2711500'>it'll</span>
  <span m='2711680'>still</span> <span m='2711860'>converge.</span> </p><p><span m='2715320'>That's</span>
  <span m='2715530'>the</span> <span m='2715650'>idea.</span> <span m='2717140'>OK?</span>
  <span m='2717770'>By</span> <span m='2717950'>flipping</span> <span m='2718730'>the</span>
  <span m='2718970'>region</span> <span m='2719420'>of</span> <span m='2719540'>convergence,</span>
  <span m='2720290'>I've</span> <span m='2720530'>changed</span> <span m='2722030'>the</span>
  <span m='2722150'>magnitudes</span> <span m='2722900'>of</span> <span m='2723020'>these</span>
  <span m='2723290'>numbers,</span> <span m='2725000'>and</span> <span m='2725190'>I've</span>
  <span m='2725360'>changed</span> <span m='2726260'>which</span> <span m='2726530'>side</span>
  <span m='2726920'>converges</span> <span m='2727460'>best.</span> <span m='2727730'>I've</span>
  <span m='2727850'>made</span> <span m='2728450'>something</span> <span m='2728930'>that--</span>
  <span m='2730600'>it's</span> <span m='2730850'>an</span> <span m='2730970'>inside</span>
  <span m='2731420'>region.</span> <span m='2731990'>It</span> <span m='2732080'>was</span>
  <span m='2732230'>converging</span> <span m='2732800'>for</span> <span m='2733820'>z</span>
  <span m='2734030'>values</span> <span m='2734480'>inside</span> <span m='2735020'>some</span>
  <span m='2735200'>region,</span> <span m='2736280'>so</span> <span m='2736490'>it's</span>
  <span m='2736640'>become</span> <span m='2737000'>left-sided.</span> </p><p><span
  m='2738440'>So</span> <span m='2738590'>the</span> <span m='2738740'>idea</span>
  <span m='2739040'>then</span> <span m='2739610'>is</span> <span m='2739940'>that</span>
  <span m='2741410'>I</span> <span m='2741530'>have</span> <span m='2741740'>two</span>
  <span m='2742100'>different</span> <span m='2743510'>kinds</span> <span m='2744020'>of</span>
  <span m='2744200'>time</span> <span m='2744590'>signals</span> <span m='2745490'>that</span>
  <span m='2745610'>are</span> <span m='2745700'>both</span> <span m='2745940'>associated</span>
  <span m='2746690'>with</span> <span m='2746870'>the</span> <span m='2747020'>same</span>
  <span m='2747620'>functional</span> <span m='2748190'>form</span> <span m='2748520'>of</span>
  <span m='2748610'>z.</span> <span m='2749270'>They</span> <span m='2749450'>differ</span>
  <span m='2749750'>by</span> <span m='2749900'>the</span> <span m='2749990'>region</span>
  <span m='2750290'>of</span> <span m='2750380'>convergence.</span> <span m='2751580'>That's</span>
  <span m='2751880'>why</span> <span m='2752270'>when</span> <span m='2752420'>you</span>
  <span m='2752540'>tell</span> <span m='2752840'>me</span> <span m='2753110'>a</span>
  <span m='2753190'>Z-transform,</span> <span m='2754220'>you</span> <span m='2754340'>have</span>
  <span m='2754460'>to</span> <span m='2754550'>tell</span> <span m='2754760'>me</span>
  <span m='2754880'>the</span> <span m='2754970'>region</span> <span m='2755240'>of</span>
  <span m='2755330'>convergence.</span> <span m='2757550'>OK?</span> </p><p><span
  m='2760770'>OK.</span> <span m='2762140'>So</span> <span m='2762290'>I've</span>
  <span m='2762410'>given</span> <span m='2762650'>some</span> <span m='2762830'>exercises.</span>
  <span m='2764480'>I'm</span> <span m='2764630'>running</span> <span m='2764870'>out</span>
  <span m='2765020'>of</span> <span m='2765110'>time.</span> <span m='2766530'>The</span>
  <span m='2766550'>best</span> <span m='2766790'>thing</span> <span m='2766970'>to</span>
  <span m='2767120'>do</span> <span m='2767450'>is</span> <span m='2767690'>to</span>
  <span m='2767810'>think</span> <span m='2768020'>about</span> <span m='2768230'>the</span>
  <span m='2768380'>exercises</span> <span m='2769040'>offline.</span> </p><p><span
  m='2771650'>I</span> <span m='2771770'>could</span> <span m='2771950'>lead</span>
  <span m='2772220'>you</span> <span m='2772340'>through</span> <span m='2772520'>the</span>
  <span m='2772610'>math.</span> <span m='2772910'>That's</span> <span m='2773090'>never</span>
  <span m='2773330'>very</span> <span m='2773600'>inspirational.</span> <span m='2776670'>So</span>
  <span m='2778190'>what</span> <span m='2778460'>I</span> <span m='2778520'>wanted</span>
  <span m='2778790'>to</span> <span m='2778970'>show</span> <span m='2779240'>you</span>
  <span m='2779450'>is</span> <span m='2779660'>that</span> <span m='2779820'>there's</span>
  <span m='2780020'>many</span> <span m='2780380'>ways</span> <span m='2780880'>that</span>
  <span m='2781020'>you</span> <span m='2781130'>can</span> <span m='2781310'>go</span>
  <span m='2781550'>about</span> <span m='2783230'>expressing</span> <span m='2784160'>a</span>
  <span m='2784220'>complicated</span> <span m='2785030'>form</span> <span m='2786800'>by</span>
  <span m='2786950'>partial</span> <span m='2787340'>fractions</span> <span m='2788810'>to</span>
  <span m='2788930'>get</span> <span m='2789080'>a</span> <span m='2789140'>simpler</span>
  <span m='2789590'>form</span> <span m='2790910'>that</span> <span m='2791060'>can</span>
  <span m='2791270'>then</span> <span m='2791990'>be</span> <span m='2793520'>inverted</span>
  <span m='2794090'>this</span> <span m='2794300'>way.</span> <span m='2796160'>So</span>
  <span m='2796210'>that's</span> <span m='2796420'>the</span> <span m='2796510'>point</span>
  <span m='2796780'>of</span> <span m='2796870'>this</span> <span m='2797050'>exercise.</span>
  </p><p><span m='2798560'>So</span> <span m='2798670'>I</span> <span m='2798820'>went</span>
  <span m='2799090'>through</span> <span m='2799390'>in</span> <span m='2799510'>the</span>
  <span m='2799600'>notes,</span> <span m='2799960'>and</span> <span m='2800050'>the</span>
  <span m='2800140'>notes</span> <span m='2800410'>are</span> <span m='2800800'>online.</span>
  <span m='2802070'>So</span> <span m='2802720'>in</span> <span m='2802930'>the</span>
  <span m='2803020'>notes,</span> <span m='2803260'>I</span> <span m='2803320'>went</span>
  <span m='2803500'>through</span> <span m='2803740'>three</span> <span m='2803980'>different</span>
  <span m='2804250'>ways</span> <span m='2804580'>you</span> <span m='2804670'>can</span>
  <span m='2804790'>think</span> <span m='2805030'>of</span> <span m='2805120'>the</span>
  <span m='2805810'>answer,</span> <span m='2806560'>and</span> <span m='2806740'>all</span>
  <span m='2807010'>of</span> <span m='2807070'>those</span> <span m='2807280'>answers</span>
  <span m='2808000'>give</span> <span m='2808170'>you</span> <span m='2808270'>the</span>
  <span m='2808390'>same</span> <span m='2808630'>functional</span> <span m='2809050'>form,</span>
  <span m='2810220'>right?</span> <span m='2810760'>So</span> <span m='2810880'>it</span>
  <span m='2810940'>was</span> <span m='2811060'>an</span> <span m='2811210'>exercise</span>
  <span m='2811870'>in</span> <span m='2811990'>thinking</span> <span m='2812380'>through</span>
  <span m='2813190'>how</span> <span m='2813370'>you</span> <span m='2813550'>do</span>
  <span m='2813700'>partial</span> <span m='2814090'>fractions.</span> </p><p><span
  m='2815680'>But</span> <span m='2815800'>there's</span> <span m='2815950'>one</span>
  <span m='2816100'>more</span> <span m='2816280'>thing</span> <span m='2816460'>that</span>
  <span m='2816580'>I</span> <span m='2816670'>want</span> <span m='2816820'>to</span>
  <span m='2816880'>talk</span> <span m='2817090'>about,</span> <span m='2818320'>and</span>
  <span m='2818440'>that</span> <span m='2818680'>is</span> <span m='2819430'>that</span>
  <span m='2819790'>a</span> <span m='2819850'>lot</span> <span m='2820120'>of</span>
  <span m='2820180'>these</span> <span m='2820390'>problems--</span> <span m='2821000'>one</span>
  <span m='2821050'>of</span> <span m='2821110'>the</span> <span m='2821380'>biggest</span>
  <span m='2821860'>uses</span> <span m='2822250'>of</span> <span m='2822340'>Z-transforms</span>
  <span m='2823450'>is</span> <span m='2823750'>to</span> <span m='2823990'>solve</span>
  <span m='2824590'>difference</span> <span m='2824950'>equations.</span> <span m='2828290'>Z-transforms</span>
  <span m='2829040'>are</span> <span m='2829130'>great</span> <span m='2829460'>for</span>
  <span m='2829640'>that.</span> <span m='2829880'>I've</span> <span m='2830000'>already</span>
  <span m='2830240'>talked</span> <span m='2830540'>about</span> <span m='2830780'>that.</span>
  </p><p><span m='2831500'>With--</span> <span m='2832070'>by</span> <span m='2832280'>using</span>
  <span m='2832670'>a</span> <span m='2832790'>Z-transform,</span> <span m='2833360'>you</span>
  <span m='2833450'>can</span> <span m='2833580'>take</span> <span m='2833750'>a</span>
  <span m='2833810'>difference</span> <span m='2834170'>equation,</span> <span m='2836270'>think</span>
  <span m='2836510'>about</span> <span m='2836750'>the</span> <span m='2836840'>difference</span>
  <span m='2837170'>equation,</span> <span m='2837680'>think</span> <span m='2837860'>about</span>
  <span m='2838040'>the</span> <span m='2838190'>input,</span> <span m='2839000'>take</span>
  <span m='2839180'>the</span> <span m='2839350'>Laplace</span> <span m='2839690'>transform</span>
  <span m='2840140'>of</span> <span m='2840260'>everything</span> <span m='2840650'>you</span>
  <span m='2840800'>get--</span> <span m='2842260'>Laplace</span> <span m='2842450'>transform--</span>
  <span m='2842870'>a Z-transform,</span> <span m='2843710'>sorry.</span> <span m='2845120'>Slipped.</span>
  <span m='2845810'>Next</span> <span m='2846050'>time</span> <span m='2846320'>it</span>
  <span m='2846380'>will</span> <span m='2846470'>be</span> <span m='2846560'>Laplace</span>
  <span m='2846940'>transform.</span> <span m='2848370'>Take a</span> <span m='2848570'>Z-transform.</span>
  <span m='2849800'>You</span> <span m='2849980'>end</span> <span m='2850220'>up</span>
  <span m='2850340'>with</span> <span m='2850490'>a</span> <span m='2850520'>Z-transform,</span>
  <span m='2851630'>and</span> <span m='2851840'>then</span> <span m='2852050'>the</span>
  <span m='2852170'>trick</span> <span m='2852500'>is</span> <span m='2852650'>to</span>
  <span m='2852770'>recognize</span> <span m='2853430'>the</span> <span m='2853550'>inverse</span>
  <span m='2853805'>Z-transform.</span> </p><p><span m='2857270'>There</span> <span
  m='2860330'>are</span> <span m='2860510'>ways</span> <span m='2860930'>of</span>
  <span m='2861020'>thinking</span> <span m='2861440'>about</span> <span m='2861770'>that</span>
  <span m='2862130'>as</span> <span m='2862340'>a</span> <span m='2862400'>mathematician.</span>
  <span m='2864680'>Those</span> <span m='2864980'>ways</span> <span m='2865340'>are</span>
  <span m='2865490'>not</span> <span m='2865850'>easy,</span> <span m='2868900'>so</span>
  <span m='2869500'>by</span> <span m='2869770'>and</span> <span m='2869890'>large,</span>
  <span m='2870250'>we</span> <span m='2870430'>will</span> <span m='2870580'>never</span>
  <span m='2870910'>do</span> <span m='2871120'>this.</span> <span m='2872410'>If</span>
  <span m='2872620'>you</span> <span m='2872740'>would</span> <span m='2872860'>like</span>
  <span m='2873070'>to</span> <span m='2873220'>do</span> <span m='2873400'>that,</span>
  <span m='2873640'>I</span> <span m='2873790'>highly</span> <span m='2874150'>recommend</span>
  <span m='2874570'>course</span> <span m='2874870'>18.</span> <span m='2876730'>OK?</span>
  <span m='2877660'>It</span> <span m='2877840'>is</span> <span m='2877990'>certainly</span>
  <span m='2878500'>something</span> <span m='2878890'>that</span> <span m='2879010'>people</span>
  <span m='2879330'>in</span> <span m='2879400'>course</span> <span m='2879610'>18</span>
  <span m='2879940'>do</span> <span m='2880090'>all</span> <span m='2880210'>the</span>
  <span m='2880330'>time,</span> <span m='2881380'>but</span> <span m='2881650'>there</span>
  <span m='2881860'>are</span> <span m='2881980'>always</span> <span m='2882430'>simpler</span>
  <span m='2882880'>ways</span> <span m='2883210'>that</span> <span m='2883330'>we</span>
  <span m='2883540'>will</span> <span m='2883690'>do</span> <span m='2883900'>it,</span>
  <span m='2884800'>and</span> <span m='2884950'>those</span> <span m='2885130'>simpler</span>
  <span m='2885550'>ways</span> <span m='2886270'>derive</span> <span m='2886900'>from</span>
  <span m='2887200'>thinking</span> <span m='2887620'>about</span> <span m='2888280'>properties</span>
  <span m='2888790'>of</span> <span m='2888910'>the</span> <span m='2889150'>z-transform.</span>
  <span m='2890440'>And</span> <span m='2890530'>we'll</span> <span m='2890650'>think</span>
  <span m='2890860'>more</span> <span m='2891040'>about</span> <span m='2891250'>those</span>
  <span m='2891520'>as</span> <span m='2891610'>we</span> <span m='2891730'>go</span>
  <span m='2891850'>forward</span> <span m='2892180'>in</span> <span m='2892240'>the</span>
  <span m='2892330'>course.</span> </p><p><span m='2893300'>So</span> <span m='2893320'>the</span>
  <span m='2893440'>point</span> <span m='2893680'>of</span> <span m='2893800'>today</span>
  <span m='2894670'>was</span> <span m='2894910'>to</span> <span m='2895210'>emphasize</span>
  <span m='2896350'>that</span> <span m='2896650'>there</span> <span m='2896920'>are</span>
  <span m='2897100'>lots</span> <span m='2897520'>of</span> <span m='2897640'>different</span>
  <span m='2898210'>ways</span> <span m='2898660'>of</span> <span m='2898750'>thinking</span>
  <span m='2899140'>about</span> <span m='2899420'>DT</span> <span m='2899770'>systems.</span>
  <span m='2901540'>You</span> <span m='2901690'>should</span> <span m='2901870'>be</span>
  <span m='2902020'>able</span> <span m='2902260'>to</span> <span m='2902380'>think</span>
  <span m='2902560'>of</span> <span m='2902650'>all</span> <span m='2902800'>the</span>
  <span m='2902890'>relations</span> <span m='2903370'>between</span> <span m='2903760'>them.</span>
  <span m='2904270'>And</span> <span m='2904390'>in</span> <span m='2904510'>particular,</span>
  <span m='2905110'>today</span> <span m='2905410'>we</span> <span m='2905530'>talked</span>
  <span m='2905800'>about</span> <span m='2906100'>this</span> <span m='2906310'>thing,</span>
  <span m='2906980'>a</span> <span m='2907180'>mathematical</span> <span m='2907870'>relationship</span>
  <span m='2908560'>for</span> <span m='2908770'>how</span> <span m='2908980'>you</span>
  <span m='2909160'>can</span> <span m='2909310'>go</span> <span m='2909520'>from</span>
  <span m='2909670'>a</span> <span m='2909740'>unit</span> <span m='2910000'>sample</span>
  <span m='2910300'>response</span> <span m='2911320'>to</span> <span m='2911620'>a</span>
  <span m='2911680'>system</span> <span m='2911950'>function.</span> <span m='2915850'>See
  you</span> <span m='2916150'>next</span> <span m='2916450'>week.</span> </p>
type: course
uid: 400326ddbc2b7b0df39ad3a9eb7866cc

---
None