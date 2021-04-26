---
about_this_resource_text: <p><strong>Instructor:</strong> Dennis Freeman</p> <p><strong>Description:</strong>
  Today's lecture continues the discussion of control systems by demonstrating how
  feedback loops can add speed and bandwidth to the LM741 op-amp, and allow better
  control of a robot arm's angular position.</p>
course_id: 6-003-signals-and-systems-fall-2011
embedded_media:
- id: Video-YouTube-Stream
  media_location: 5w2BvCPuYY0
  parent_uid: 5277acbc3461158b2e3212b4e39d343c
  title: Video-YouTube-Stream
  type: Video
  uid: 8b5e52a9236f6b010111d556b6b5623e
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/5w2BvCPuYY0/default.jpg
  parent_uid: 5277acbc3461158b2e3212b4e39d343c
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 957fe1f5009fa9c6eea666f800a5aef3
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/lecture-12-continuous-time/id602305810?i=132454030
  parent_uid: 5277acbc3461158b2e3212b4e39d343c
  title: Video-iTunes U-MP4
  type: Video
  uid: 375d322ddeb3e70d3be0764ecb1c1851
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.003F11/MIT6_003F11_lec12_300k.mp4
  parent_uid: 5277acbc3461158b2e3212b4e39d343c
  title: Video-Internet Archive-MP4
  type: Video
  uid: ecb18ee234c87c617dd4705c2b12fa9a
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 5w2BvCPuYY0
  parent_uid: 5277acbc3461158b2e3212b4e39d343c
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: b678e73502d63ac8c83e08cba11d4283
- id: 5w2BvCPuYY0.srt
  parent_uid: 5277acbc3461158b2e3212b4e39d343c
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-12-continuous-time-ct-feedback-and-control-part-1/5w2BvCPuYY0.srt
  title: 3play caption file
  type: null
  uid: 4b12f434dbd679321b3ad77ca6d9c359
- id: 5w2BvCPuYY0.pdf
  parent_uid: 5277acbc3461158b2e3212b4e39d343c
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-12-continuous-time-ct-feedback-and-control-part-1/5w2BvCPuYY0.pdf
  title: 3play pdf file
  type: null
  uid: 6530b4a17893d42255fcc8590fef2d80
- id: Caption-3Play YouTube id-SRT
  parent_uid: 5277acbc3461158b2e3212b4e39d343c
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 41811f69eb44352a9e01b90d28c23791
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 5277acbc3461158b2e3212b4e39d343c
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 83b82129053539cc51af5a45f4e007fd
inline_embed_id: 46629911lecture12:continuous-time(ct)feedbackandcontrol,part170268493
layout: video
order_index: null
parent_uid: 47b07fedf3a30be25f155f62399cdb59
related_resources_text: ''
short_url: lecture-12-continuous-time-ct-feedback-and-control-part-1
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-12-continuous-time-ct-feedback-and-control-part-1
template_type: Tabbed
title: 'Lecture 12: Continuous-Time (CT) Feedback and Control, Part 1'
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
  <span m='17430'>ocw.mit.edu.</span> </p><p><span m='22722'>DENNIS FREEMAN:</span>
  <span m='22756'>Hello,</span> <span m='22790'>and</span> <span m='22880'>welcome.</span>
  <span m='24950'>So</span> <span m='25790'>like</span> <span m='26060'>last</span>
  <span m='26300'>time,</span> <span m='28250'>the</span> <span m='28400'>important</span>
  <span m='28730'>announcement</span> <span m='29480'>is</span> <span m='29750'>of</span>
  <span m='29870'>course</span> <span m='30500'>that</span> <span m='30650'>we</span>
  <span m='30800'>have</span> <span m='30950'>an</span> <span m='31040'>exam</span>
  <span m='31370'>coming</span> <span m='31670'>up.</span> <span m='32090'>So</span>
  <span m='32180'>exam</span> <span m='32570'>2,</span> <span m='33640'>Wednesday,</span>
  <span m='34910'>everything's</span> <span m='35480'>very</span> <span m='35720'>similar,</span>
  <span m='36230'>analogous</span> <span m='36770'>to</span> <span m='36860'>last</span>
  <span m='37130'>time,</span> <span m='37590'>with</span> <span m='37670'>the</span>
  <span m='37760'>exception</span> <span m='38210'>that</span> <span m='38330'>we</span>
  <span m='38540'>are in</span> <span m='38690'>Walker.</span> <span m='40040'>Don't</span>
  <span m='40220'>go</span> <span m='40400'>to</span> <span m='40490'>Building</span>
  <span m='40760'>26.</span> <span m='41420'>Go</span> <span m='41600'>to</span> <span
  m='41690'>Walker.</span> </p><p><span m='43370'>Other</span> <span m='43580'>than</span>
  <span m='43730'>that</span> <span m='43940'>things</span> <span m='44240'>look</span>
  <span m='44450'>very</span> <span m='44840'>similar</span> <span m='47090'>to</span>
  <span m='47270'>before.</span> <span m='49210'>The</span> <span m='49540'>idea</span>
  <span m='50080'>will</span> <span m='50260'>be</span> <span m='51220'>that</span>
  <span m='51400'>the</span> <span m='51580'>exam</span> <span m='51940'>will</span>
  <span m='52030'>focus</span> <span m='52450'>on</span> <span m='52570'>things</span>
  <span m='52810'>since</span> <span m='53320'>exam</span> <span m='53770'>1.</span>
  <span m='54070'>However,</span> <span m='55210'>this</span> <span m='55510'>subject</span>
  <span m='56140'>builds</span> <span m='56500'>on</span> <span m='56650'>itself.</span>
  <span m='57800'>So</span> <span m='57970'>the</span> <span m='58120'>official</span>
  <span m='58510'>coverage</span> <span m='59060'>is</span> <span m='59170'>1</span>
  <span m='59390'>the</span> <span m='59500'>12,</span> <span m='59950'>lectures</span>
  <span m='60280'>1</span> <span m='60460'>to</span> <span m='60550'>12,</span> <span
  m='60970'>recitations</span> <span m='61570'>1</span> <span m='61780'>to</span>
  <span m='61870'>12,</span> <span m='62200'>and</span> <span m='62290'>homeworks</span>
  <span m='62660'>1</span> <span m='62830'>to</span> <span m='62960'>7.</span> <span
  m='64819'>Questions?</span> <span m='65300'>Comments?</span> <span m='67260'>All</span>
  <span m='67490'>the</span> <span m='67970'>logistical</span> <span m='68510'>issues</span>
  <span m='68810'>are</span> <span m='68900'>clear?</span> </p><p><span m='71244'>AUDIENCE:</span>
  <span m='71409'>I</span> <span m='71574'>had</span> <span m='71740'>one question.</span>
  <span m='72732'>[INAUDIBLE]</span> <span m='73228'>how much</span> <span m='73724'>do
  we have</span> <span m='74220'>to know</span> <span m='74716'>about</span> <span
  m='75212'>[INAUDIBLE].</span> </p><p><span m='78690'>DENNIS FREEMAN:</span> <span
  m='78885'>So</span> <span m='79410'>there</span> <span m='79620'>was</span> <span
  m='79770'>an</span> <span m='79860'>introduction</span> <span m='80430'>to</span>
  <span m='80580'>root</span> <span m='80790'>locus.</span> <span m='82660'>Sorry,</span>
  <span m='82930'>so</span> <span m='83080'>everybody</span> <span m='83290'>knows</span>
  <span m='83530'>what</span> <span m='83630'>root locus</span> <span m='84100'>is?</span>
  <span m='87240'>You</span> <span m='87360'>can</span> <span m='87540'>find</span>
  <span m='87780'>out</span> <span m='88170'>after</span> <span m='88500'>class.</span>
  <span m='88810'>You</span> <span m='88900'>know,</span> <span m='89020'>it will</span>
  <span m='89280'>just</span> <span m='89430'>making</span> <span m='89670'>me feel</span>
  <span m='89790'>a</span> <span m='89850'>lot</span> <span m='89970'>better</span>
  <span m='90210'>if</span> <span m='90300'>you</span> <span m='90360'>nod</span>
  <span m='90570'>your</span> <span m='90660'>head</span> <span m='90810'>yes.</span>
  <span m='91500'>Root</span> <span m='92430'>locus</span> <span m='92850'>is</span>
  <span m='93030'>the</span> <span m='93180'>way</span> <span m='93450'>you</span>
  <span m='93870'>figure</span> <span m='94440'>out</span> <span m='95220'>the</span>
  <span m='95340'>locus</span> <span m='95730'>of</span> <span m='95850'>possible</span>
  <span m='96360'>points</span> <span m='96930'>that</span> <span m='97260'>a</span>
  <span m='97350'>pole</span> <span m='98310'>could</span> <span m='98880'>move</span>
  <span m='99120'>to.</span> </p><p><span m='100880'>There</span> <span m='101080'>is</span>
  <span m='101240'>an</span> <span m='101330'>enormous</span> <span m='102080'>number</span>
  <span m='102620'>of</span> <span m='103640'>rules</span> <span m='104180'>for</span>
  <span m='104420'>thinking</span> <span m='104870'>about</span> <span m='105380'>how</span>
  <span m='105860'>root</span> <span m='106130'>locuses</span> <span m='106760'>evolve.</span>
  <span m='107270'>And</span> <span m='107400'>if</span> <span m='107570'>you're</span>
  <span m='107810'>really</span> <span m='108230'>good</span> <span m='108710'>signals</span>
  <span m='109370'>and</span> <span m='109460'>systems</span> <span m='109880'>person,</span>
  <span m='110270'>you know</span> <span m='110660'>50</span> <span m='111050'>rules.</span>
  <span m='112070'>That's</span> <span m='112370'>not</span> <span m='112790'>the</span>
  <span m='112880'>point</span> <span m='113150'>of</span> <span m='113240'>this</span>
  <span m='113390'>class.</span> </p><p><span m='115880'>You</span> <span m='115960'>should</span>
  <span m='116200'>know</span> <span m='116890'>that</span> <span m='117040'>poles</span>
  <span m='117490'>move</span> <span m='117700'>around</span> <span m='118090'>when</span>
  <span m='118210'>there</span> <span m='118260'>is</span> <span m='118420'>feedback.</span>
  <span m='118940'>We'll</span> <span m='119020'>have</span> <span m='119140'>examples</span>
  <span m='119620'>of</span> <span m='119710'>that</span> <span m='119920'>in</span>
  <span m='120040'>class</span> <span m='120580'>today.</span> <span m='122880'>You</span>
  <span m='122930'>should</span> <span m='123110'>be</span> <span m='123260'>able</span>
  <span m='123530'>to</span> <span m='123680'>calculate</span> <span m='124400'>how</span>
  <span m='124610'>they</span> <span m='124790'>move</span> <span m='125030'>around</span>
  <span m='125510'>for</span> <span m='125720'>simple</span> <span m='126140'>problems.</span>
  </p><p><span m='126770'>You're</span> <span m='126950'>not</span> <span m='127310'>expected</span>
  <span m='127820'>to</span> <span m='128000'>know</span> <span m='128210'>the</span>
  <span m='128330'>rules.</span> <span m='129680'>OK,</span> <span m='129979'>so</span>
  <span m='130550'>you</span> <span m='130669'>shouldn't</span> <span m='130940'>be</span>
  <span m='131060'>surprised</span> <span m='131750'>by</span> <span m='131900'>the</span>
  <span m='132020'>rules.</span> <span m='134210'>If</span> <span m='134360'>we</span>
  <span m='134510'>ask</span> <span m='134750'>you</span> <span m='134900'>to</span>
  <span m='135020'>derive</span> <span m='135560'>one</span> <span m='135680'>of</span>
  <span m='135770'>the</span> <span m='135860'>rules,</span> <span m='136220'>you</span>
  <span m='136340'>probably</span> <span m='136820'>could.</span> <span m='137390'>But</span>
  <span m='137570'>we</span> <span m='137690'>don't</span> <span m='137900'>expect</span>
  <span m='138200'>that</span> <span m='138290'>you've</span> <span m='138500'>memorized</span>
  <span m='139130'>the</span> <span m='139250'>rules.</span> <span m='140300'>Does
  that</span> <span m='140480'>sounds</span> <span m='141260'>roughly</span> <span
  m='141980'>correct?</span> </p><p><span m='144470'>OK,</span> <span m='146230'>other</span>
  <span m='146340'>questions</span> <span m='146730'>or</span> <span m='146820'>comments?</span>
  <span m='147270'>Content,</span> <span m='148050'>administration,</span> <span m='148780'>anything</span>
  <span m='149100'>like</span> <span m='149220'>that?</span> </p><p><span m='153700'>OK,</span>
  <span m='154860'>so</span> <span m='155130'>about</span> <span m='155400'>a</span>
  <span m='155490'>week</span> <span m='155730'>ago,</span> <span m='157140'>Russ</span>
  <span m='157560'>introduced</span> <span m='158220'>the</span> <span m='158490'>idea</span>
  <span m='159210'>of</span> <span m='159450'>using</span> <span m='159810'>feedback</span>
  <span m='160350'>for</span> <span m='160470'>the</span> <span m='160590'>purpose</span>
  <span m='160920'>of</span> <span m='161010'>controlling.</span> <span m='161650'>And</span>
  <span m='161760'>the</span> <span m='161880'>example</span> <span m='162270'>in</span>
  <span m='162450'>lecture</span> <span m='163200'>was</span> <span m='163350'>controlling</span>
  <span m='163740'>a</span> <span m='163800'>robot.</span> <span m='165880'>You've</span>
  <span m='166030'>seen</span> <span m='166240'>that</span> <span m='166390'>before.</span>
  <span m='167050'>Right?</span> <span m='167350'>That's</span> <span m='167500'>6.01.</span>
  </p><p><span m='169450'>And</span> <span m='169630'>then</span> <span m='169870'>in</span>
  <span m='169960'>recitation</span> <span m='170590'>yesterday,</span> <span m='171460'>he</span>
  <span m='171730'>ran</span> <span m='171910'>over</span> <span m='172150'>some</span>
  <span m='172300'>more</span> <span m='172990'>ways</span> <span m='173410'>of</span>
  <span m='173500'>thinking</span> <span m='173890'>about</span> <span m='174550'>more</span>
  <span m='174760'>sophisticated</span> <span m='175570'>ways</span> <span m='175870'>to</span>
  <span m='175990'>do</span> <span m='176140'>control</span> <span m='178920'>with</span>
  <span m='179130'>feedback.</span> <span m='180510'>And</span> <span m='180660'>the</span>
  <span m='180750'>point</span> <span m='181110'>of</span> <span m='181200'>those</span>
  <span m='181380'>more</span> <span m='181530'>sophisticated</span> <span m='182250'>ways</span>
  <span m='182490'>to</span> <span m='182610'>do</span> <span m='182730'>control</span>
  <span m='183510'>is</span> <span m='183660'>really</span> <span m='183960'>performance.</span>
  <span m='185140'>The</span> <span m='185160'>idea</span> <span m='185550'>is</span>
  <span m='185790'>to</span> <span m='185970'>enhance</span> <span m='186360'>performance.</span>
  <span m='187770'>And</span> <span m='187950'>that's</span> <span m='188280'>the</span>
  <span m='188430'>theme</span> <span m='188700'>that</span> <span m='188820'>I</span>
  <span m='188910'>want</span> <span m='189060'>to</span> <span m='189150'>build</span>
  <span m='189480'>on</span> <span m='189690'>today,</span> <span m='191160'>today</span>
  <span m='191640'>and</span> <span m='192030'>on</span> <span m='192270'>Tuesday.</span>
  <span m='193440'>How</span> <span m='193620'>do</span> <span m='193680'>you</span>
  <span m='193830'>enhance</span> <span m='194250'>performance</span> <span m='194850'>by</span>
  <span m='195600'>using</span> <span m='195990'>feedback?</span> </p><p><span m='196890'>And</span>
  <span m='197010'>we'll</span> <span m='197160'>go</span> <span m='197400'>through</span>
  <span m='197790'>a</span> <span m='197820'>number</span> <span m='198180'>of</span>
  <span m='198270'>examples.</span> <span m='198960'>You</span> <span m='199080'>can</span>
  <span m='199230'>use</span> <span m='199500'>feedback</span> <span m='199980'>to</span>
  <span m='200070'>increase</span> <span m='200550'>speed</span> <span m='200910'>and</span>
  <span m='201000'>bandwidth.</span> <span m='202690'>You</span> <span m='202710'>can</span>
  <span m='202860'>use</span> <span m='203100'>feedback</span> <span m='203640'>to</span>
  <span m='203850'>change</span> <span m='204330'>the</span> <span m='204540'>control</span>
  <span m='205170'>variable</span> <span m='205830'>from--</span> <span m='206520'>I'll</span>
  <span m='206680'>do</span> <span m='206860'>an</span> <span m='206970'>example--</span>
  <span m='207570'>speed</span> <span m='207920'>to</span> <span m='208050'>position.</span>
  <span m='209670'>You</span> <span m='209820'>can</span> <span m='210060'>reduce</span>
  <span m='210570'>distortion,</span> <span m='211410'>reduce</span> <span m='211800'>sensitivity</span>
  <span m='212520'>to</span> <span m='212610'>parameter</span> <span m='213150'>variation.</span>
  <span m='214290'>You</span> <span m='214410'>can</span> <span m='214560'>stabilize</span>
  <span m='215220'>unstable</span> <span m='215730'>systems.</span> </p><p><span m='216180'>We'll</span>
  <span m='216330'>do</span> <span m='216540'>a</span> <span m='216600'>bunch</span>
  <span m='216960'>of</span> <span m='217050'>examples.</span> <span m='217650'>The</span>
  <span m='217770'>point</span> <span m='218190'>is</span> <span m='219210'>that</span>
  <span m='219390'>you</span> <span m='219480'>can</span> <span m='219630'>use</span>
  <span m='219870'>feedback</span> <span m='220500'>to</span> <span m='220620'>accomplish</span>
  <span m='221160'>a</span> <span m='221220'>lot</span> <span m='221460'>of</span>
  <span m='221520'>different</span> <span m='221940'>tasks</span> <span m='223320'>that</span>
  <span m='223470'>generally</span> <span m='223980'>speaking</span> <span m='224980'>improve</span>
  <span m='225540'>performance.</span> <span m='228550'>So</span> <span m='228660'>with</span>
  <span m='228840'>that,</span> <span m='229240'>let</span> <span m='229290'>me</span>
  <span m='229650'>think</span> <span m='229920'>about</span> <span m='230730'>an</span>
  <span m='230960'>op-amp.</span> <span m='231720'>You</span> <span m='231860'>all</span>
  <span m='231990'>know</span> <span m='232110'>about</span> <span m='232320'>op-amps,</span>
  <span m='232740'>right?</span> <span m='232920'>That's</span> <span m='233100'>also</span>
  <span m='233340'>a</span> <span m='233370'>6.01</span> <span m='233910'>sort</span>
  <span m='234120'>of</span> <span m='234210'>thing.</span> </p><p><span m='236620'>So</span>
  <span m='236860'>an</span> <span m='237100'>ideal</span> <span m='237670'>op-amp</span>
  <span m='238210'>would</span> <span m='238360'>have</span> <span m='238540'>a</span>
  <span m='238600'>bunch</span> <span m='239020'>of</span> <span m='239140'>properties</span>
  <span m='239770'>that</span> <span m='239890'>we</span> <span m='240040'>would</span>
  <span m='240190'>like.</span> <span m='241360'>We'd</span> <span m='241540'>like</span>
  <span m='241810'>it</span> <span m='241920'>to</span> <span m='242080'>have--</span>
  <span m='242890'>it</span> <span m='243010'>we'd</span> <span m='243190'>like</span>
  <span m='243340'>it</span> <span m='243430'>to</span> <span m='243520'>be</span>
  <span m='243610'>very</span> <span m='243910'>high</span> <span m='244120'>speed.</span>
  <span m='244480'>We'd</span> <span m='244630'>like</span> <span m='244780'>it</span>
  <span m='244840'>to</span> <span m='244930'>have</span> <span m='245110'>a</span>
  <span m='245140'>very</span> <span m='245470'>broad</span> <span m='246100'>bandwidth.</span>
  <span m='247630'>We'd</span> <span m='247780'>like</span> <span m='247960'>it</span>
  <span m='248050'>to</span> <span m='248170'>be</span> <span m='248320'>fast.</span>
  <span m='249040'>We'd</span> <span m='249220'>like</span> <span m='249430'>it</span>
  <span m='249520'>to</span> <span m='249640'>have</span> <span m='250240'>a</span>
  <span m='250300'>very</span> <span m='250600'>low</span> <span m='250870'>output</span>
  <span m='251290'>impedance</span> <span m='251720'>so</span> <span m='251890'>it</span>
  <span m='251950'>works</span> <span m='252250'>like</span> <span m='252430'>a</span>
  <span m='252490'>perfect</span> <span m='252850'>voltage</span> <span m='253330'>source.</span>
  <span m='255500'>We</span> <span m='255650'>like</span> <span m='255890'>it</span>
  <span m='256010'>have</span> <span m='256160'>a</span> <span m='256220'>very</span>
  <span m='256459'>high</span> <span m='256880'>input</span> <span m='257240'>impedance</span>
  <span m='258019'>so</span> <span m='258200'>that</span> <span m='258320'>when</span>
  <span m='258500'>we</span> <span m='258589'>hook</span> <span m='258769'>it</span>
  <span m='258860'>up</span> <span m='258980'>to</span> <span m='259070'>something</span>
  <span m='259399'>it</span> <span m='259490'>doesn't</span> <span m='259760'>change</span>
  <span m='260120'>the</span> <span m='260240'>something</span> <span m='260570'>that</span>
  <span m='260690'>we</span> <span m='260810'>hooked</span> <span m='260970'>it up</span>
  <span m='261110'>to.</span> </p><p><span m='263350'>There's</span> <span m='263510'>lots</span>
  <span m='263900'>of</span> <span m='263990'>things</span> <span m='264260'>we'd</span>
  <span m='264440'>like</span> <span m='264710'>it</span> <span m='264800'>to</span>
  <span m='264950'>have.</span> <span m='265650'>Unfortunately,</span> <span m='266930'>it's</span>
  <span m='267110'>difficult</span> <span m='267560'>to</span> <span m='267680'>build</span>
  <span m='267860'>a</span> <span m='267920'>circuit</span> <span m='268220'>that</span>
  <span m='268370'>has</span> <span m='268550'>all</span> <span m='268730'>of</span>
  <span m='268820'>those</span> <span m='269060'>things.</span> <span m='273000'>And</span>
  <span m='273200'>so</span> <span m='273410'>here</span> <span m='273640'>is</span>
  <span m='273770'>an</span> <span m='273860'>example</span> <span m='274340'>of</span>
  <span m='274430'>that.</span> <span m='275340'>Here's</span> <span m='275510'>one</span>
  <span m='275690'>of</span> <span m='275750'>the</span> <span m='275840'>world's</span>
  <span m='276140'>most</span> <span m='276410'>popular</span> <span m='276860'>op-amps,</span>
  <span m='277370'>the</span> <span m='277490'>LM741,</span> <span m='279170'>invented</span>
  <span m='279800'>eons</span> <span m='280190'>ago</span> <span m='280490'>and</span>
  <span m='280610'>still</span> <span m='280880'>used</span> <span m='281150'>today.</span>
  </p><p><span m='283260'>The</span> <span m='283550'>idea</span> <span m='284150'>that's</span>
  <span m='284390'>plotted</span> <span m='284930'>here</span> <span m='285380'>is</span>
  <span m='285620'>the</span> <span m='285770'>frequency</span> <span m='286430'>response.</span>
  <span m='287000'>You</span> <span m='287100'>remember</span> <span m='287330'>frequency</span>
  <span m='287720'>response.</span> <span m='288620'>What's</span> <span m='288800'>the</span>
  <span m='288920'>frequency</span> <span m='289490'>response</span> <span m='290270'>of</span>
  <span m='290420'>an</span> <span m='290550'>LM741?</span> <span m='293580'>Well,</span>
  <span m='293730'>if</span> <span m='293880'>you</span> <span m='294000'>plot</span>
  <span m='294780'>as</span> <span m='294990'>a</span> <span m='295050'>function</span>
  <span m='295440'>of</span> <span m='295500'>frequency,</span> <span m='297720'>how</span>
  <span m='298050'>does</span> <span m='298320'>the</span> <span m='298440'>gain</span>
  <span m='298890'>change?</span> </p><p><span m='299280'>Well,</span> <span m='299370'>the</span>
  <span m='299460'>gain</span> <span m='299630'>is</span> <span m='299760'>enormous.</span>
  <span m='301250'>High</span> <span m='301530'>gain,</span> <span m='301860'>that's</span>
  <span m='302070'>what</span> <span m='302150'>we'd</span> <span m='302310'>like</span>
  <span m='302610'>it to</span> <span m='302820'>have.</span> <span m='303630'>The</span>
  <span m='303750'>gain is</span> <span m='304050'>enormous</span> <span m='305010'>at</span>
  <span m='305160'>low</span> <span m='305400'>frequencies,</span> <span m='306130'>at</span>
  <span m='306330'>1</span> <span m='307380'>radian</span> <span m='307860'>per</span>
  <span m='308010'>second.</span> <span m='310950'>But</span> <span m='311100'>the</span>
  <span m='311160'>gain</span> <span m='311430'>becomes</span> <span m='311790'>very</span>
  <span m='312120'>small</span> <span m='313080'>out</span> <span m='313350'>at</span>
  <span m='313560'>high</span> <span m='313920'>speeds</span> <span m='314550'>at</span>
  <span m='314670'>the</span> <span m='314790'>speeds</span> <span m='315260'>we</span>
  <span m='315420'>think</span> <span m='315780'>we</span> <span m='316530'>think</span>
  <span m='316710'>about</span> <span m='316920'>when</span> <span m='317050'>we're</span>
  <span m='317160'>thinking</span> <span m='317370'>about</span> <span m='317550'>communication</span>
  <span m='318250'>systems</span> <span m='318900'>or</span> <span m='319170'>when</span>
  <span m='319320'>we're</span> <span m='319380'>thinking</span> <span m='319560'>about</span>
  <span m='319710'>computation</span> <span m='320430'>or</span> <span m='320520'>things.</span>
  <span m='321030'>When</span> <span m='321150'>we</span> <span m='321240'>think</span>
  <span m='321450'>about</span> <span m='321930'>speeds</span> <span m='322860'>that</span>
  <span m='323100'>are</span> <span m='323790'>electronic</span> <span m='324420'>speeds,</span>
  <span m='325800'>the</span> <span m='325890'>gain</span> <span m='326090'>is</span>
  <span m='326190'>actually</span> <span m='326520'>pretty</span> <span m='326760'>small.</span>
  </p><p><span m='328260'>Similarly,</span> <span m='328770'>the</span> <span m='328890'>phase</span>
  <span m='329160'>changes.</span> <span m='329670'>The</span> <span m='329790'>phase</span>
  <span m='330030'>of</span> <span m='330090'>very</span> <span m='330300'>low</span>
  <span m='330450'>frequencies</span> <span m='330990'>is</span> <span m='331110'>near</span>
  <span m='331290'>0.</span> <span m='331950'>That's</span> <span m='332160'>kind</span>
  <span m='332490'>of</span> <span m='332580'>ideal.</span> <span m='333480'>0</span>
  <span m='333930'>would</span> <span m='334050'>mean</span> <span m='334500'>in</span>
  <span m='334750'>phase.</span> <span m='336990'>The</span> <span m='337170'>output</span>
  <span m='338220'>reliably</span> <span m='338850'>tells</span> <span m='339150'>you</span>
  <span m='339210'>what's</span> <span m='339410'>the</span> <span m='339540'>input</span>
  <span m='340110'>doing.</span> <span m='340440'>So</span> <span m='340590'>that's</span>
  <span m='340830'>good.</span> </p><p><span m='341900'>But</span> <span m='342030'>as</span>
  <span m='342150'>you</span> <span m='342210'>go</span> <span m='342330'>to</span>
  <span m='342420'>higher</span> <span m='342660'>frequencies,</span> <span m='343170'>you</span>
  <span m='343230'>start</span> <span m='343470'>to</span> <span m='343560'>pick</span>
  <span m='343740'>up</span> <span m='343860'>a</span> <span m='343920'>phase</span>
  <span m='344220'>delay,</span> <span m='344940'>which</span> <span m='345090'>means</span>
  <span m='345300'>the</span> <span m='345420'>output is</span> <span m='345810'>telling</span>
  <span m='346140'>you</span> <span m='347070'>what</span> <span m='347220'>the</span>
  <span m='347340'>input</span> <span m='347580'>did</span> <span m='347760'>a</span>
  <span m='347820'>little</span> <span m='347970'>while</span> <span m='348270'>ago.</span>
  <span m='349800'>OK,</span> <span m='350010'>that's</span> <span m='350220'>less</span>
  <span m='350430'>good.</span> <span m='352020'>So</span> <span m='352170'>the</span>
  <span m='352290'>performance</span> <span m='353310'>in</span> <span m='353490'>terms</span>
  <span m='353760'>of</span> <span m='353910'>providing</span> <span m='354390'>a</span>
  <span m='354450'>lot</span> <span m='354630'>of</span> <span m='354750'>gain</span>
  <span m='355140'>is</span> <span m='355260'>quite</span> <span m='355530'>good</span>
  <span m='355830'>for</span> <span m='356010'>some</span> <span m='356250'>frequencies,</span>
  <span m='356790'>but</span> <span m='356940'>not</span> <span m='357180'>for</span>
  <span m='357390'>others.</span> </p><p><span m='359810'>Unfortunately,</span> <span
  m='360570'>the</span> <span m='360690'>range</span> <span m='360990'>where</span>
  <span m='361140'>it's</span> <span m='361260'>not</span> <span m='361470'>very</span>
  <span m='361710'>good</span> <span m='363250'>is</span> <span m='363690'>most</span>
  <span m='363960'>of</span> <span m='364020'>the</span> <span m='364110'>range.</span>
  <span m='365140'>So</span> <span m='365250'>if</span> <span m='365340'>you</span>
  <span m='365430'>thought</span> <span m='365610'>about</span> <span m='365850'>an</span>
  <span m='365940'>op-amp</span> <span m='366270'>doing</span> <span m='366510'>even</span>
  <span m='366780'>a</span> <span m='366840'>very</span> <span m='367080'>low</span>
  <span m='368490'>frequency</span> <span m='369000'>problem,</span> <span m='369420'>like</span>
  <span m='369690'>audio</span> <span m='370050'>signal</span> <span m='370320'>processing,</span>
  <span m='372130'>most</span> <span m='372390'>of</span> <span m='372480'>the</span>
  <span m='372570'>frequencies</span> <span m='374220'>that</span> <span m='374370'>are</span>
  <span m='374520'>of</span> <span m='374610'>interest</span> <span m='374940'>to</span>
  <span m='375090'>audio</span> <span m='376260'>are</span> <span m='376380'>in</span>
  <span m='376500'>the</span> <span m='376590'>region</span> <span m='376950'>where</span>
  <span m='377100'>the</span> <span m='377190'>op-amp</span> <span m='377520'>is</span>
  <span m='377580'>not</span> <span m='377700'>working</span> <span m='377970'>too</span>
  <span m='378120'>well.</span> </p><p><span m='379710'>We</span> <span m='379920'>hear</span>
  <span m='380130'>sounds</span> <span m='380580'>from</span> <span m='380790'>about</span>
  <span m='381000'>20</span> <span m='381510'>Hertz</span> <span m='382020'>to</span>
  <span m='382170'>about</span> <span m='382410'>20</span> <span m='382800'>kilohertz.</span>
  <span m='383820'>And</span> <span m='384390'>that</span> <span m='384660'>range</span>
  <span m='384960'>is</span> <span m='385050'>indicated</span> <span m='385470'>by</span>
  <span m='385590'>the</span> <span m='385680'>red</span> <span m='385860'>arrow.</span>
  <span m='386220'>And</span> <span m='386340'>you</span> <span m='386400'>can</span>
  <span m='386520'>see</span> <span m='386700'>that's</span> <span m='386910'>not</span>
  <span m='387450'>where</span> <span m='387660'>the</span> <span m='387840'>op-amp</span>
  <span m='388350'>is</span> <span m='388440'>working</span> <span m='388800'>ideally.</span>
  </p><p><span m='391470'>Similarly,</span> <span m='391980'>we</span> <span m='392160'>would</span>
  <span m='392340'>like</span> <span m='392550'>the</span> <span m='392670'>op-amp</span>
  <span m='393030'>to</span> <span m='393150'>be</span> <span m='393270'>fast.</span>
  <span m='396040'>Fast</span> <span m='396400'>is</span> <span m='396520'>indicated</span>
  <span m='397000'>here</span> <span m='397240'>by</span> <span m='397360'>thinking</span>
  <span m='397660'>about</span> <span m='397870'>the</span> <span m='397960'>step</span>
  <span m='398200'>response.</span> <span m='400600'>So</span> <span m='400990'>if</span>
  <span m='401170'>you</span> <span m='401300'>thought</span> <span m='401440'>about</span>
  <span m='401710'>having</span> <span m='402010'>an</span> <span m='402160'>ideal</span>
  <span m='402670'>step</span> <span m='403060'>at</span> <span m='403120'>the</span>
  <span m='403300'>input,</span> <span m='404950'>what</span> <span m='405130'>would</span>
  <span m='405280'>the</span> <span m='405400'>output</span> <span m='405760'>look</span>
  <span m='405970'>like?</span> </p><p><span m='407030'>Well,</span> <span m='407170'>we'd</span>
  <span m='407380'>like</span> <span m='407650'>it</span> <span m='407740'>to</span>
  <span m='407830'>be</span> <span m='407980'>an</span> <span m='408070'>ideal</span>
  <span m='408430'>step,</span> <span m='408790'>but</span> <span m='408940'>it</span>
  <span m='409000'>generally</span> <span m='409510'>isn't.</span> <span m='410590'>Generally,</span>
  <span m='411130'>there's</span> <span m='411320'>some</span> <span m='411550'>lag.</span>
  <span m='412300'>That's</span> <span m='412510'>associated</span> <span m='413050'>with</span>
  <span m='413190'>that</span> <span m='413590'>phase</span> <span m='413770'>delay</span>
  <span m='413980'>that</span> <span m='414100'>I</span> <span m='414190'>talked</span>
  <span m='414430'>about.</span> <span m='415730'>And</span> <span m='415750'>in</span>
  <span m='415840'>fact,</span> <span m='416360'>what</span> <span m='416440'>I'd</span>
  <span m='416560'>like</span> <span m='416710'>you</span> <span m='416800'>to</span>
  <span m='416890'>do</span> <span m='417010'>is</span> <span m='417100'>figure</span>
  <span m='417370'>out</span> <span m='417490'>exactly</span> <span m='417880'>how</span>
  <span m='418120'>it's</span> <span m='418240'>associated</span> <span m='418810'>with</span>
  <span m='418940'>that</span> <span m='419080'>phase</span> <span m='419340'>delay.</span>
  </p><p><span m='421390'>Think</span> <span m='421690'>about--</span> <span m='422620'>so</span>
  <span m='422860'>figure</span> <span m='423280'>out--</span> <span m='423490'>it</span>
  <span m='423580'>will</span> <span m='423730'>turn</span> <span m='423970'>out</span>
  <span m='424630'>that</span> <span m='424960'>the</span> <span m='425200'>step</span>
  <span m='425590'>response</span> <span m='426190'>can</span> <span m='426340'>be</span>
  <span m='426430'>characterized</span> <span m='427150'>by</span> <span m='427660'>a</span>
  <span m='427810'>time</span> <span m='428200'>constant</span> <span m='428740'>tau.</span>
  <span m='429580'>The</span> <span m='429670'>time</span> <span m='429940'>constant</span>
  <span m='430400'>tau</span> <span m='430690'>is</span> <span m='430900'>the</span>
  <span m='431050'>time</span> <span m='431950'>required</span> <span m='432760'>for</span>
  <span m='433000'>the</span> <span m='433120'>signal</span> <span m='433960'>to</span>
  <span m='434080'>get</span> <span m='434260'>within</span> <span m='434650'>1</span>
  <span m='434860'>over</span> <span m='435220'>e</span> <span m='437250'>of</span>
  <span m='437460'>this</span> <span m='437710'>final</span> <span m='438040'>value</span>
  <span m='439780'>determined</span> <span m='440530'>from</span> <span m='440890'>this.</span>
  <span m='441460'>I've</span> <span m='441640'>already</span> <span m='441910'>told</span>
  <span m='442210'>you</span> <span m='442660'>the</span> <span m='442780'>performance</span>
  <span m='443320'>parameters</span> <span m='443920'>in</span> <span m='444010'>terms</span>
  <span m='444310'>of</span> <span m='444400'>frequency.</span> <span m='445630'>You</span>
  <span m='445780'>should</span> <span m='445960'>be</span> <span m='446110'>able</span>
  <span m='446350'>to</span> <span m='446470'>use</span> <span m='446710'>6.003</span>
  <span m='447580'>to</span> <span m='447670'>figure</span> <span m='447940'>out</span>
  <span m='448060'>what</span> <span m='448210'>that</span> <span m='448360'>implies</span>
  <span m='448780'>about</span> <span m='449020'>time.</span> </p><p><span m='451660'>So</span>
  <span m='452050'>look</span> <span m='452200'>at</span> <span m='452290'>your</span>
  <span m='452390'>neighbor--</span> <span m='454010'>OK,</span> <span m='454410'>look,</span>
  <span m='455240'>look,</span> <span m='456220'>look.</span> <span m='458640'>And</span>
  <span m='458740'>now,</span> <span m='459000'>figure</span> <span m='459330'>out</span>
  <span m='459780'>which</span> <span m='460110'>answer--</span> <span m='460920'>what's</span>
  <span m='461190'>tau</span> <span m='462270'>for</span> <span m='462510'>the</span>
  <span m='462620'>741</span> <span m='463090'>op-amp?</span> </p><p><span m='467853'>[SIDE
  CONVERSATION]</span> </p><p></p><p><span m='523080'>OK,</span> <span m='523360'>it's</span>
  <span m='523510'>dead</span> <span m='523750'>quiet.</span> <span m='524230'>So
  I</span> <span m='524560'>assume</span> <span m='524890'>that</span> <span m='525040'>means</span>
  <span m='525340'>convergence.</span> <span m='530060'>So</span> <span m='530140'>what's</span>
  <span m='530320'>the</span> <span m='530440'>answer?</span> <span m='530870'>What's</span>
  <span m='531040'>the</span> <span m='531730'>time</span> <span m='532090'>constant</span>
  <span m='532590'>tau</span> <span m='533470'>of</span> <span m='533620'>the</span>
  <span m='533710'>741?</span> <span m='534490'>Raise</span> <span m='534700'>your</span>
  <span m='534850'>hand</span> <span m='535150'>with</span> <span m='535360'>a</span>
  <span m='535420'>number</span> <span m='535660'>between</span> <span m='536020'>1</span>
  <span m='536200'>and</span> <span m='536320'>5.</span> <span m='538400'>Don't</span>
  <span m='538730'>look</span> <span m='538910'>at</span> <span m='539060'>other</span>
  <span m='539270'>people,</span> <span m='539570'>just</span> <span m='539780'>raise</span>
  <span m='540020'>your</span> <span m='540110'>hand.</span> </p><p><span m='543110'>OK,</span>
  <span m='543410'>I</span> <span m='543500'>can</span> <span m='543620'>see</span>
  <span m='543980'>a</span> <span m='544040'>couple</span> <span m='544320'>of</span>
  <span m='544400'>answers</span> <span m='544860'>I</span> <span m='544960'>don't</span>
  <span m='545210'>like.</span> <span m='550670'>How</span> <span m='550850'>do</span>
  <span m='550940'>I</span> <span m='551030'>think</span> <span m='551270'>about</span>
  <span m='551510'>converting</span> <span m='552140'>this</span> <span m='552350'>representation</span>
  <span m='553100'>to</span> <span m='553190'>that</span> <span m='553370'>representation?</span>
  <span m='553980'>What</span> <span m='554090'>should</span> <span m='554210'>I</span>
  <span m='554270'>do</span> <span m='554390'>first?</span> <span m='559480'>Shout.</span>
  <span m='560890'>I</span> <span m='561190'>start</span> <span m='561430'>with</span>
  <span m='561550'>the</span> <span m='561640'>thing</span> <span m='561850'>on</span>
  <span m='561940'>the</span> <span m='562030'>right.</span> <span m='562210'>What</span>
  <span m='562330'>should</span> <span m='562480'>I</span> <span m='562540'>do</span>
  <span m='562690'>next?</span> </p><p><span m='563050'>AUDIENCE:</span> <span m='563277'>[INAUDIBLE]</span>
  <span m='564415'>of like</span> <span m='564870'>doing a</span> <span m='565325'>2
  over</span> <span m='565780'>tau</span> <span m='566235'>or something</span> <span
  m='566690'>like that?</span> </p><p><span m='567150'>DENNIS FREEMAN:</span> <span
  m='567186'>So</span> <span m='567222'>we're</span> <span m='567260'>looking for</span>
  <span m='567680'>something</span> <span m='568010'>like</span> <span m='568220'>e</span>
  <span m='568280'>to</span> <span m='568430'>the</span> <span m='568520'>minus</span>
  <span m='568830'>t</span> <span m='569000'>over</span> <span m='569180'>tau.</span>
  <span m='569510'>That's</span> <span m='569660'>right.</span> <span m='572870'>We're</span>
  <span m='572960'>looking</span> <span m='573170'>for</span> <span m='573290'>something</span>
  <span m='573620'>like</span> <span m='573800'>that.</span> <span m='574670'>How</span>
  <span m='574790'>do</span> <span m='574880'>I</span> <span m='574970'>get</span>
  <span m='575270'>that</span> <span m='575780'>starting</span> <span m='576230'>with</span>
  <span m='576350'>the</span> <span m='576440'>thing</span> <span m='576620'>on</span>
  <span m='576710'>the</span> <span m='576770'>right?</span> </p><p><span m='578036'>AUDIENCE:</span>
  <span m='578285'>It's</span> <span m='578534'>like using</span> <span m='579032'>poles.</span>
  </p><p><span m='580030'>DENNIS FREEMAN:</span> <span m='580227'>Poles,</span> <span
  m='580820'>what</span> <span m='581060'>a</span> <span m='581120'>good</span> <span
  m='581300'>idea.</span> <span m='582830'>How</span> <span m='583070'>do</span> <span
  m='583190'>I</span> <span m='583310'>figure</span> <span m='583700'>out</span> <span
  m='583970'>poles</span> <span m='585050'>from</span> <span m='585230'>the</span>
  <span m='585320'>thing</span> <span m='585530'>on</span> <span m='585620'>the</span>
  <span m='585710'>right?</span> <span m='586440'>6.003,</span> <span m='587420'>poles,</span>
  <span m='587840'>that</span> <span m='587960'>should</span> <span m='588140'>be</span>
  <span m='588260'>like</span> <span m='588760'>hard</span> <span m='589090'>wire.</span>
  <span m='589640'>Right?</span> <span m='590480'>So</span> <span m='591320'>when</span>
  <span m='591530'>you</span> <span m='591680'>hear</span> <span m='592040'>the</span>
  <span m='592190'>word</span> <span m='592520'>003,</span> <span m='592990'>you</span>
  <span m='593360'>should</span> <span m='593600'>think</span> <span m='593960'>the</span>
  <span m='594080'>word</span> <span m='594410'>pole.</span> <span m='595850'>How</span>
  <span m='595970'>do</span> <span m='596030'>you</span> <span m='596240'>associate</span>
  <span m='596780'>a</span> <span m='596840'>pole?</span> <span m='597320'>Can</span>
  <span m='597500'>somebody</span> <span m='597740'>tell</span> <span m='597890'>me</span>
  <span m='598010'>what</span> <span m='598130'>the</span> <span m='598250'>poles</span>
  <span m='598700'>of</span> <span m='598850'>the</span> <span m='598970'>right-hand</span>
  <span m='599480'>system</span> <span m='599930'>should</span> <span m='600170'>look</span>
  <span m='600350'>like?</span> </p><p><span m='603554'>AUDIENCE:</span> <span m='603786'>Where</span>
  <span m='604018'>the line</span> <span m='604482'>is.</span> </p><p><span m='605410'>DENNIS
  FREEMAN:</span> <span m='605515'>Where</span> <span m='605620'>the</span> <span
  m='605740'>line</span> <span m='606100'>is--</span> <span m='606420'>there's a</span>
  <span m='606490'>couple</span> <span m='606760'>of</span> <span m='606820'>lines</span>
  <span m='607180'>there.</span> </p><p><span m='608123'>AUDIENCE:</span> <span m='608264'>The</span>
  <span m='608405'>vertical</span> <span m='608546'>line.</span> </p><p><span m='608970'>DENNIS
  FREEMAN:</span> <span m='609035'>The</span> <span m='609100'>vertical</span> <span
  m='609550'>line--</span> <span m='610450'>how</span> <span m='610600'>many</span>
  <span m='610810'>poles</span> <span m='611110'>are</span> <span m='611170'>on</span>
  <span m='611290'>the</span> <span m='611380'>right?</span> <span m='612260'>How</span>
  <span m='612320'>many</span> <span m='612430'>poles</span> <span m='612620'>are</span>
  <span m='612770'>in</span> <span m='612910'>the</span> <span m='612990'>system</span>
  <span m='613240'>represented</span> <span m='613630'>by</span> <span m='613720'>the</span>
  <span m='613930'>right-hand</span> <span m='614080'>figure?</span> </p><p><span
  m='614380'>AUDIENCE:</span> <span m='614555'>One.</span> </p><p><span m='615430'>DENNIS
  FREEMAN:</span> <span m='615565'>One.</span> <span m='615700'>How many</span> <span
  m='615910'>zeros?</span> <span m='618930'>Zero,</span> <span m='619390'>wonderful.</span>
  <span m='620260'>So</span> <span m='620450'>we</span> <span m='620590'>have</span>
  <span m='620740'>to</span> <span m='620830'>think</span> <span m='621010'>about</span>
  <span m='621220'>a</span> <span m='621280'>pole,</span> <span m='622720'>just</span>
  <span m='622930'>one</span> <span m='623170'>pole.</span> <span m='624010'>So</span>
  <span m='624160'>we</span> <span m='624250'>think</span> <span m='624400'>about</span>
  <span m='624580'>the</span> <span m='624730'>s-plane.</span> <span m='625360'>Right?</span>
  <span m='626680'>Where's</span> <span m='626950'>the</span> <span m='627070'>pole?</span>
  <span m='634680'>You</span> <span m='634920'>already</span> <span m='635160'>told</span>
  <span m='635310'>me.</span> </p><p><span m='635510'>AUDIENCE:</span> <span m='635752'>80</span>
  <span m='635994'>halves,</span> <span m='636478'>so it was</span> <span m='636962'>40.</span>
  </p><p><span m='637930'>DENNIS FREEMAN:</span> <span m='638150'>40--</span> <span
  m='638630'>OK,</span> <span m='638870'>where's</span> <span m='639090'>40</span>
  <span m='639420'>over</span> <span m='639600'>here?</span> <span m='643510'>Somewhere</span>
  <span m='643900'>in</span> <span m='644020'>there.</span> <span m='644650'>Got</span>
  <span m='644920'>it.</span> <span m='647620'>Where's</span> <span m='647920'>the</span>
  <span m='648040'>pole</span> <span m='648290'>over</span> <span m='648430'>here?</span>
  <span m='650240'>It's at</span> <span m='650460'>location</span> <span m='650970'>40.</span>
  <span m='651270'>That's</span> <span m='651480'>actually</span> <span m='651750'>correct,</span>
  <span m='653010'>well,</span> <span m='653220'>sort</span> <span m='653430'>of.</span>
  <span m='656790'>Negative</span> <span m='657120'>40,</span> <span m='657420'>that's</span>
  <span m='657600'>exactly</span> <span m='658140'>correct.</span> <span m='660360'>So</span>
  <span m='660630'>negative</span> <span m='660990'>40,</span> <span m='661600'>so</span>
  <span m='661680'>the</span> <span m='661800'>pole</span> <span m='662190'>is</span>
  <span m='662460'>right</span> <span m='662700'>here.</span> </p><p><span m='665460'>OK,</span>
  <span m='666490'>so</span> <span m='666640'>the</span> <span m='666730'>pole is</span>
  <span m='667030'>at</span> <span m='667120'>minus</span> <span m='667450'>40</span>
  <span m='668440'>radians</span> <span m='668860'>per</span> <span m='668980'>second.</span>
  <span m='670450'>How</span> <span m='670600'>do</span> <span m='670660'>you</span>
  <span m='670810'>know</span> <span m='671050'>that?</span> <span m='673380'>Well,</span>
  <span m='673820'>that's</span> <span m='673950'>that</span> <span m='674190'>Bode</span>
  <span m='674600'>stuff</span> <span m='674870'>we</span> <span m='674960'>talked</span>
  <span m='675200'>about</span> <span m='675380'>last</span> <span m='675620'>time.</span>
  <span m='675830'>Right?</span> </p><p><span m='676760'>So</span> <span m='677180'>if</span>
  <span m='677480'>the</span> <span m='677600'>pole</span> <span m='677960'>were</span>
  <span m='678170'>here,</span> <span m='678570'>you</span> <span m='678620'>would</span>
  <span m='678710'>think</span> <span m='678920'>about</span> <span m='679160'>a</span>
  <span m='679220'>vector.</span> <span m='680100'>So</span> <span m='680150'>this</span>
  <span m='680360'>is</span> <span m='680480'>the</span> <span m='680760'>j omega</span>
  <span m='681040'>axis.</span> <span m='681500'>Right?</span> <span m='682790'>You</span>
  <span m='682880'>would</span> <span m='682970'>think</span> <span m='683150'>about</span>
  <span m='683510'>a</span> <span m='683570'>vector</span> <span m='683990'>connecting</span>
  <span m='684380'>the</span> <span m='684500'>pole</span> <span m='684740'>to</span>
  <span m='684860'>some</span> <span m='685790'>location</span> <span m='686360'>on</span>
  <span m='686450'>the</span> <span m='686540'>j omega</span> <span m='687000'>axis.</span>
  <span m='688440'>If</span> <span m='688550'>the</span> <span m='688640'>location</span>
  <span m='689210'>is</span> <span m='689510'>omega</span> <span m='689900'>small,</span>
  <span m='691610'>it's</span> <span m='691760'>going</span> <span m='691880'>to</span>
  <span m='691940'>have</span> <span m='692090'>some--</span> <span m='692450'>that</span>
  <span m='692600'>vector</span> <span m='692810'>is</span> <span m='692980'>going</span>
  <span m='693110'>to</span> <span m='693180'>have</span> <span m='693260'>some</span>
  <span m='693440'>length</span> <span m='693710'>like</span> <span m='693950'>that.</span>
  <span m='694520'>It's</span> <span m='694610'>going</span> <span m='694730'>to</span>
  <span m='694790'>have</span> <span m='694880'>an</span> <span m='694970'>angle</span>
  <span m='695390'>of</span> <span m='695510'>0.</span> </p><p><span m='698070'>And</span>
  <span m='698320'>as</span> <span m='698600'>frequency</span> <span m='699290'>goes</span>
  <span m='699590'>up,</span> <span m='700590'>the</span> <span m='700610'>vector</span>
  <span m='700910'>gets</span> <span m='701150'>longer,</span> <span m='704030'>which</span>
  <span m='704270'>means</span> <span m='704600'>that</span> <span m='704900'>the</span>
  <span m='705590'>magnitude</span> <span m='706250'>gets</span> <span m='706490'>smaller</span>
  <span m='707060'>because</span> <span m='707300'>poles</span> <span m='707570'>and</span>
  <span m='707660'>bottom.</span> <span m='708920'>Right?</span> <span m='711000'>And</span>
  <span m='712290'>the</span> <span m='712620'>phase</span> <span m='713460'>goes</span>
  <span m='713880'>increasingly</span> <span m='714510'>toward pi</span> <span m='714860'>over</span>
  <span m='715430'>2.</span> <span m='715870'>But it's</span> <span m='716230'>in
  the</span> <span m='716310'>bottom.</span> <span m='716670'>So</span> <span m='716790'>it's</span>
  <span m='716880'>minus</span> <span m='717290'>pi over</span> <span m='717660'>2.</span>
  </p><p><span m='719940'>Right,</span> <span m='720450'>so</span> <span m='720630'>the</span>
  <span m='720750'>frequency</span> <span m='721620'>at</span> <span m='721860'>which</span>
  <span m='722160'>you</span> <span m='722280'>get</span> <span m='722430'>to</span>
  <span m='722550'>pi</span> <span m='722840'>over</span> <span m='723090'>4--</span>
  <span m='724860'>OK,</span> <span m='725640'>0pi</span> <span m='726000'>over</span>
  <span m='726390'>2--</span> <span m='726600'>the</span> <span m='726690'>frequency</span>
  <span m='727080'>at</span> <span m='727140'>which</span> <span m='727350'>you</span>
  <span m='727410'>get</span> <span m='727560'>to</span> <span m='727770'>pi</span>
  <span m='728180'>over</span> <span m='728820'>4</span> <span m='729870'>is--</span>
  <span m='730410'>so</span> <span m='730590'>pi over</span> <span m='730980'>4</span>
  <span m='731430'>is</span> <span m='731670'>here.</span> <span m='732230'>Right?</span>
  <span m='734560'>So</span> <span m='734800'>the</span> <span m='734950'>distance</span>
  <span m='735430'>here,</span> <span m='736510'>the</span> <span m='736600'>critical</span>
  <span m='736990'>frequency,</span> <span m='738970'>the</span> <span m='739090'>frequency</span>
  <span m='739660'>at</span> <span m='739720'>which</span> <span m='739990'>the</span>
  <span m='740110'>phase</span> <span m='740410'>is pi</span> <span m='740530'>over</span>
  <span m='741020'>4,</span> <span m='741340'>minus</span> <span m='741640'>pi over</span>
  <span m='742000'>4,</span> <span m='742810'>is</span> <span m='742990'>going</span>
  <span m='743290'>to</span> <span m='743380'>be</span> <span m='743560'>the</span>
  <span m='743710'>same</span> <span m='744160'>as</span> <span m='744520'>the</span>
  <span m='744640'>frequency</span> <span m='745360'>of</span> <span m='745600'>the</span>
  <span m='745660'>pole.</span> <span m='747100'>So</span> <span m='747250'>that's</span>
  <span m='747400'>how</span> <span m='747520'>we</span> <span m='747610'>know</span>
  <span m='747730'>it's</span> <span m='747820'>at</span> <span m='747910'>minus</span>
  <span m='748150'>40.</span> <span m='748390'>Right?</span> </p><p><span m='750770'>So</span>
  <span m='750950'>we</span> <span m='751100'>know</span> <span m='751310'>that</span>
  <span m='751610'>this</span> <span m='751910'>then</span> <span m='752360'>is</span>
  <span m='752540'>a</span> <span m='753530'>characterization</span> <span m='754310'>of</span>
  <span m='754370'>that</span> <span m='754550'>system.</span> <span m='754910'>It's</span>
  <span m='755000'>not</span> <span m='755120'>quite</span> <span m='755390'>done.</span>
  <span m='756060'>So</span> <span m='756260'>what's</span> <span m='756560'>the</span>
  <span m='757250'>h</span> <span m='757500'>of</span> <span m='757640'>s</span> <span
  m='759620'>for</span> <span m='759800'>this</span> <span m='759920'>system?</span>
  <span m='762170'>If</span> <span m='762290'>I've</span> <span m='762380'>got</span>
  <span m='762540'>a</span> <span m='762570'>pole</span> <span m='762880'>at</span>
  <span m='763490'>minus</span> <span m='763880'>40,</span> <span m='764150'>what's</span>
  <span m='764360'>h of s</span> <span m='764700'>look</span> <span m='764860'>like?</span>
  <span m='770385'>Shout,</span> <span m='770870'>shout.</span> <span m='772325'>These</span>
  <span m='772810'>answers coming</span> <span m='773295'>up,</span> <span m='773780'>this
  is</span> <span m='774265'>perfect</span> <span m='774750'>practice.</span> </p><p><span
  m='776992'>AUDIENCE:</span> <span m='777154'>I've</span> <span m='777316'>already</span>
  <span m='777478'>talked too</span> <span m='777964'>much.</span> </p><p><span m='779660'>DENNIS
  FREEMAN:</span> <span m='779758'>What's</span> <span m='779856'>h</span> <span m='779954'>of</span>
  <span m='780052'>s</span> <span m='780150'>look like?</span> </p><p><span m='780640'>AUDIENCE:</span>
  <span m='780803'>Is</span> <span m='780966'>this</span> <span m='781130'>something
  over</span> <span m='781620'>s plus</span> <span m='782110'>40.</span> </p><p><span
  m='782600'>DENNIS FREEMAN:</span> <span m='782845'>Exactly,</span> <span m='783580'>something</span>
  <span m='783940'>over s</span> <span m='784090'>plus 40.</span> <span m='784810'>What
  would you</span> <span m='785170'>like the</span> <span m='785470'>something</span>
  <span m='785860'>to</span> <span m='785950'>be?</span> <span m='789630'>We'd</span>
  <span m='789750'>like</span> <span m='789900'>it</span> <span m='789960'>to</span>
  <span m='790050'>be</span> <span m='790170'>some</span> <span m='790530'>k.</span>
  <span m='791430'>We'd</span> <span m='791700'>actually</span> <span m='792000'>like</span>
  <span m='792240'>it</span> <span m='792330'>to</span> <span m='792450'>be</span>
  <span m='792660'>related,</span> <span m='793170'>for</span> <span m='793380'>example,</span>
  <span m='794250'>to</span> <span m='794370'>the</span> <span m='794520'>open-loop</span>
  <span m='795060'>gain.</span> <span m='800700'>How</span> <span m='800880'>big</span>
  <span m='801060'>is</span> <span m='801180'>the</span> <span m='801300'>gain</span>
  <span m='801660'>when</span> <span m='801780'>frequencies</span> <span m='802680'>go</span>
  <span m='803100'>towards</span> <span m='803630'>0?</span> <span m='804280'>What's</span>
  <span m='804630'>the</span> <span m='804720'>gain</span> <span m='804990'>at</span>
  <span m='805080'>0?</span> </p><p><span m='808120'>Let's</span> <span m='808240'>say</span>
  <span m='808390'>the</span> <span m='808480'>gain</span> <span m='808720'>of</span>
  <span m='808810'>0--</span> <span m='809220'>let's</span> <span m='809390'>define</span>
  <span m='809890'>the</span> <span m='809950'>gain</span> <span m='810190'>of</span>
  <span m='810280'>0,</span> <span m='810580'>k0,</span> <span m='811690'>let's</span>
  <span m='811880'>define</span> <span m='813250'>the</span> <span m='813790'>gain</span>
  <span m='814250'>at 0</span> <span m='814720'>to</span> <span m='814870'>be--</span>
  <span m='816070'>so</span> <span m='816230'>what</span> <span m='816610'>is</span>
  <span m='816700'>the</span> <span m='816790'>gain at</span> <span m='817030'>0?</span>
  <span m='823260'>10</span> <span m='823400'>to</span> <span m='823540'>the</span>
  <span m='823670'>5,</span> <span m='824580'>2</span> <span m='824750'>times</span>
  <span m='825080'>10</span> <span m='825230'>to</span> <span m='825320'>the</span>
  <span m='825410'>5.</span> <span m='827080'>Right?</span> <span m='827300'>It's</span>
  <span m='827430'>a</span> <span m='827740'>little</span> <span m='827900'>bit</span>
  <span m='828020'>above the</span> <span m='828920'>10</span> <span m='829100'>to</span>
  <span m='829160'>the</span> <span m='829250'>5</span> <span m='829490'>line.</span>
  </p><p><span m='831540'>OK,</span> <span m='832280'>so</span> <span m='832460'>now</span>
  <span m='832910'>if</span> <span m='833120'>I</span> <span m='833210'>define</span>
  <span m='833660'>k0</span> <span m='834090'>to</span> <span m='834230'>be</span>
  <span m='834380'>that</span> <span m='834530'>gain</span> <span m='834830'>at</span>
  <span m='834890'>0,</span> <span m='835640'>what's</span> <span m='835910'>the</span>
  <span m='836030'>numerator</span> <span m='836570'>over</span> <span m='836750'>here?</span>
  <span m='840240'>If</span> <span m='840420'>the</span> <span m='840510'>numerator</span>
  <span m='841040'>over</span> <span m='841230'>here</span> <span m='841440'>were</span>
  <span m='841680'>1,</span> <span m='842190'>what</span> <span m='842370'>would</span>
  <span m='842490'>be</span> <span m='843180'>the</span> <span m='844110'>low-frequency</span>
  <span m='845070'>gain?</span> <span m='847420'>1</span> <span m='847660'>over</span>
  <span m='847930'>40,</span> <span m='849340'>right?</span> </p><p><span m='850180'>To</span>
  <span m='850270'>think</span> <span m='850450'>about</span> <span m='850630'>frequency,</span>
  <span m='851110'>we</span> <span m='851230'>think</span> <span m='851410'>about</span>
  <span m='851910'>1</span> <span m='852160'>over</span> <span m='852430'>j</span>
  <span m='852670'>omega</span> <span m='853270'>plus</span> <span m='853570'>40.</span>
  <span m='854010'>Right?</span> <span m='854220'>You</span> <span m='854480'>substitute</span>
  <span m='854940'>s</span> <span m='855130'>equals</span> <span m='855430'>j omega</span>
  <span m='856450'>to</span> <span m='856540'>think</span> <span m='856720'>about</span>
  <span m='856930'>frequency.</span> <span m='858280'>And</span> <span m='858490'>if</span>
  <span m='858610'>omega</span> <span m='859000'>is</span> <span m='859150'>very</span>
  <span m='859390'>small,</span> <span m='860060'>you</span> <span m='860080'>get</span>
  <span m='860200'>1</span> <span m='860410'>over</span> <span m='860590'>40.</span>
  <span m='861880'>Right?</span> <span m='862690'>So</span> <span m='862870'>if</span>
  <span m='863020'>you</span> <span m='863140'>wanted</span> <span m='863380'>that</span>
  <span m='863560'>to</span> <span m='863650'>be</span> <span m='863800'>1,</span>
  <span m='864580'>you'd</span> <span m='864730'>have</span> <span m='864850'>to</span>
  <span m='864940'>make</span> <span m='865120'>it</span> <span m='865210'>40.</span>
  </p><p><span m='869060'>But</span> <span m='869180'>we</span> <span m='869270'>don't</span>
  <span m='869420'>want</span> <span m='869570'>it</span> <span m='869630'>to</span>
  <span m='869720'>be</span> <span m='869840'>1.</span> <span m='870140'>We</span>
  <span m='870230'>want</span> <span m='870340'>it</span> <span m='870410'>to</span>
  <span m='870500'>k0.</span> <span m='870980'>So</span> <span m='871100'>you'd</span>
  <span m='871250'>want</span> <span m='871430'>it</span> <span m='871490'>to</span>
  <span m='871610'>be</span> <span m='871730'>40</span> <span m='872000'>k0.</span>
  <span m='874500'>Or</span> <span m='874710'>to</span> <span m='874830'>be</span>
  <span m='874950'>a</span> <span m='874980'>little</span> <span m='875220'>bit</span>
  <span m='875310'>more</span> <span m='875490'>general,</span> <span m='876240'>we'd</span>
  <span m='876390'>like</span> <span m='876570'>this</span> <span m='876780'>to</span>
  <span m='876900'>be</span> <span m='877890'>of</span> <span m='878220'>the</span>
  <span m='878320'>form</span> <span m='879420'>alpha</span> <span m='879940'>k0</span>
  <span m='880980'>divided</span> <span m='881340'>by</span> <span m='881490'>s</span>
  <span m='881670'>plus</span> <span m='881910'>alpha.</span> <span m='882650'>Right?</span>
  </p><p><span m='884850'>So</span> <span m='885030'>now,</span> <span m='885390'>we've</span>
  <span m='885570'>got</span> <span m='885870'>the</span> <span m='886650'>Laplace</span>
  <span m='887040'>transform.</span> <span m='888270'>We</span> <span m='888390'>can</span>
  <span m='888540'>figure</span> <span m='888750'>out</span> <span m='888870'>the</span>
  <span m='888960'>time</span> <span m='889200'>response.</span> <span m='889720'>What's</span>
  <span m='889860'>the</span> <span m='889950'>time</span> <span m='890220'>response</span>
  <span m='890580'>associated</span> <span m='891030'>with</span> <span m='891150'>that</span>
  <span m='891300'>Laplace</span> <span m='891600'>transform?</span> </p><p><span
  m='895230'>You</span> <span m='895370'>remember</span> <span m='895670'>the</span>
  <span m='895820'>impulse</span> <span m='896390'>response</span> <span m='897170'>of</span>
  <span m='897290'>a</span> <span m='897350'>system</span> <span m='899240'>is</span>
  <span m='899390'>related</span> <span m='899840'>to</span> <span m='899960'>the</span>
  <span m='900080'>system</span> <span m='900440'>function</span> <span m='900860'>via</span>
  <span m='901160'>the</span> <span m='901280'>Laplace</span> <span m='901640'>transform.</span>
  <span m='902210'>Right?</span> <span m='903230'>So</span> <span m='903350'>all</span>
  <span m='903470'>we</span> <span m='903590'>need</span> <span m='903770'>to</span>
  <span m='903860'>do</span> <span m='903980'>is</span> <span m='904100'>take</span>
  <span m='904250'>the</span> <span m='904400'>inverse</span> <span m='904730'>Laplace</span>
  <span m='905090'>transform</span> <span m='905540'>of</span> <span m='905630'>that</span>
  <span m='905840'>thing.</span> <span m='906410'>And</span> <span m='906530'>we</span>
  <span m='906620'>get</span> <span m='906800'>h</span> <span m='907010'>of</span>
  <span m='907130'>t.</span> <span m='908450'>So</span> <span m='908600'>what's</span>
  <span m='908750'>h</span> <span m='908960'>of</span> <span m='909050'>t?</span>
  </p><p><span m='921440'>OK,</span> <span m='922010'>it's</span> <span m='922420'>such</span>
  <span m='922780'>a</span> <span m='922840'>strain,</span> <span m='923590'>all</span>
  <span m='923800'>those</span> <span m='924010'>weeks</span> <span m='924250'>ago.</span>
  <span m='926020'>e</span> <span m='926370'>to</span> <span m='926900'>the</span>
  <span m='927060'>minus</span> <span m='927430'>t,</span> <span m='927660'>e to the</span>
  <span m='927910'>minus</span> <span m='928530'>something</span> <span m='928910'>t.</span>
  <span m='929230'>So</span> <span m='929380'>we</span> <span m='929470'>need</span>
  <span m='929620'>something</span> <span m='929920'>like</span> <span m='930360'>e</span>
  <span m='930640'>to</span> <span m='930690'>the</span> <span m='930760'>minus</span>
  <span m='931120'>what?</span> <span m='932680'>Alpha.</span> <span m='933395'>e
  to the</span> <span m='933750'>M</span> <span m='934030'>alpha</span> <span m='934270'>t</span>
  <span m='934690'>u of</span> <span m='934780'>t.</span> <span m='939120'>And</span>
  <span m='939270'>there's</span> <span m='939450'>going</span> <span m='939600'>to</span>
  <span m='939660'>be</span> <span m='939780'>that--</span> <span m='941100'>that</span>
  <span m='941540'>thing is</span> <span m='941760'>going</span> <span m='941880'>to</span>
  <span m='941940'>come</span> <span m='942120'>out</span> <span m='942240'>here</span>
  <span m='942390'>too.</span> <span m='942660'>And it's</span> <span m='942990'>going</span>
  <span m='943110'>to</span> <span m='943170'>be</span> <span m='943230'>like</span>
  <span m='943410'>that.</span> </p><p><span m='947620'>And</span> <span m='947770'>then</span>
  <span m='947920'>if</span> <span m='948010'>you</span> <span m='948100'>wanted</span>
  <span m='948280'>to</span> <span m='948370'>find</span> <span m='948580'>the</span>
  <span m='948670'>step</span> <span m='948910'>response</span> <span m='949300'>what</span>
  <span m='949420'>would</span> <span m='949540'>you</span> <span m='949630'>do?</span>
  <span m='959440'>h of</span> <span m='959695'>t</span> <span m='959950'>is</span>
  <span m='960070'>the</span> <span m='960160'>impulse</span> <span m='960430'>response.</span>
  <span m='960820'>How</span> <span m='960970'>would</span> <span m='961060'>you</span>
  <span m='961120'>find</span> <span m='961330'>the</span> <span m='961420'>step</span>
  <span m='961600'>response?</span> <span m='962950'>A</span> <span m='963370'>step</span>
  <span m='963670'>is</span> <span m='963790'>related</span> <span m='964150'>to</span>
  <span m='964210'>the</span> <span m='964360'>impulse</span> <span m='964820'>by</span>
  <span m='966510'>integrating.</span> <span m='967970'>The</span> <span m='968120'>step</span>
  <span m='968390'>response is</span> <span m='968840'>related</span> <span m='969140'>to</span>
  <span m='969200'>the</span> <span m='969260'>impulse</span> <span m='969530'>response</span>
  <span m='969800'>by,</span> <span m='970910'>surprisingly,</span> <span m='971690'>integrating.</span>
  </p><p><span m='972630'>So</span> <span m='972680'>you</span> <span m='972800'>would</span>
  <span m='972920'>integrate</span> <span m='973310'>that</span> <span m='973520'>thing,</span>
  <span m='974900'>and</span> <span m='975050'>you</span> <span m='975170'>would</span>
  <span m='975290'>end</span> <span m='975440'>up</span> <span m='975560'>with</span>
  <span m='975650'>something.</span> <span m='975980'>Right?</span> <span m='976220'>So</span>
  <span m='976370'>you would</span> <span m='976520'>get</span> <span m='976700'>something</span>
  <span m='977000'>like</span> <span m='977490'>k0</span> <span m='978720'>1</span>
  <span m='979040'>minus</span> <span m='979540'>e</span> <span m='979640'>to</span>
  <span m='979740'>the</span> <span m='979790'>minus</span> <span m='980240'>alpha</span>
  <span m='980740'>t</span> <span m='981080'>u</span> <span m='981250'>of</span> <span
  m='981380'>t,</span> <span m='982070'>something</span> <span m='982370'>like</span>
  <span m='982490'>that.</span> <span m='984240'>I</span> <span m='984340'>think</span>
  <span m='984440'>that's</span> <span m='984640'>right.</span> </p><p><span m='986450'>OK,</span>
  <span m='987600'>the</span> <span m='987660'>time</span> <span m='987900'>constant</span>
  <span m='988350'>is</span> <span m='988500'>given</span> <span m='988890'>by</span>
  <span m='989420'>alpha.</span> <span m='992220'>Right?</span> <span m='993840'>So</span>
  <span m='994080'>what</span> <span m='994320'>is</span> <span m='994470'>the</span>
  <span m='994560'>time</span> <span m='994800'>constant</span> <span m='995190'>now?</span>
  <span m='1000310'>1</span> <span m='1000610'>over</span> <span m='1000960'>40,</span>
  <span m='1002500'>right?</span> <span m='1003190'>So</span> <span m='1003460'>it's</span>
  <span m='1004240'>alpha</span> <span m='1004600'>t.</span> <span m='1005410'>But</span>
  <span m='1005590'>the</span> <span m='1005680'>time</span> <span m='1005950'>constant</span>
  <span m='1006550'>is</span> <span m='1007080'>t</span> <span m='1007300'>over</span>
  <span m='1007620'>tau.</span> </p><p><span m='1009170'>So</span> <span m='1009360'>the</span>
  <span m='1009480'>time</span> <span m='1009690'>constant</span> <span m='1010080'>is</span>
  <span m='1010230'>the</span> <span m='1010380'>inverse</span> <span m='1010740'>of</span>
  <span m='1010800'>frequency.</span> <span m='1011520'>Right?</span> <span m='1012090'>Frequency</span>
  <span m='1012630'>is</span> <span m='1013350'>per</span> <span m='1013710'>second.</span>
  <span m='1015290'>Time</span> <span m='1015530'>constant</span> <span m='1015920'>is</span>
  <span m='1016310'>seconds.</span> <span m='1017040'>They're</span> <span m='1017210'>reciprocals</span>
  <span m='1017555'>of</span> <span m='1017900'>each</span> <span m='1018050'>other.</span>
  </p><p><span m='1018900'>OK,</span> <span m='1020600'>so</span> <span m='1020810'>the</span>
  <span m='1021020'>idea</span> <span m='1021350'>then</span> <span m='1021560'>is</span>
  <span m='1021710'>that</span> <span m='1021830'>we</span> <span m='1021950'>can</span>
  <span m='1022100'>associate</span> <span m='1022580'>a</span> <span m='1022640'>time</span>
  <span m='1023150'>response</span> <span m='1023630'>with</span> <span m='1023780'>that.</span>
  <span m='1024410'>And</span> <span m='1024530'>that</span> <span m='1024680'>time</span>
  <span m='1024980'>response</span> <span m='1025310'>is</span> <span m='1025400'>pretty</span>
  <span m='1025640'>slow.</span> <span m='1027730'>A</span> <span m='1027770'>40th</span>
  <span m='1028140'>of</span> <span m='1028240'>a</span> <span m='1028530'>second,</span>
  <span m='1029579'>40</span> <span m='1030050'>things</span> <span m='1030440'>per</span>
  <span m='1030589'>second</span> <span m='1030950'>kind</span> <span m='1031160'>of.</span>
  <span m='1031250'>That's</span> <span m='1031400'>my</span> <span m='1031609'>speed.</span>
  <span m='1032839'>Right,</span> <span m='1033030'>that's</span> <span m='1033230'>not</span>
  <span m='1033410'>computation</span> <span m='1034069'>speed.</span> <span m='1034520'>Right?</span>
  <span m='1035540'>So</span> <span m='1035750'>that's</span> <span m='1035960'>pretty</span>
  <span m='1036290'>slow.</span> </p><p><span m='1036910'>So</span> <span m='1037069'>we'd</span>
  <span m='1037190'>like</span> <span m='1037339'>to</span> <span m='1037819'>improve</span>
  <span m='1038180'>that.</span> <span m='1038500'>And</span> <span m='1038510'>one</span>
  <span m='1038660'>way</span> <span m='1038780'>that</span> <span m='1038900'>we</span>
  <span m='1039020'>can</span> <span m='1039140'>improve</span> <span m='1039560'>it</span>
  <span m='1040700'>is</span> <span m='1040880'>by</span> <span m='1041000'>thinking</span>
  <span m='1041300'>about</span> <span m='1041510'>feedback.</span> <span m='1044460'>So</span>
  <span m='1044640'>the</span> <span m='1044790'>idea</span> <span m='1045210'>would</span>
  <span m='1045390'>be</span> <span m='1045900'>we</span> <span m='1046050'>don't</span>
  <span m='1046380'>use</span> <span m='1046740'>the</span> <span m='1046890'>op-amp</span>
  <span m='1047430'>just</span> <span m='1047670'>out</span> <span m='1047819'>of</span>
  <span m='1047880'>the</span> <span m='1047970'>package</span> <span m='1048450'>the</span>
  <span m='1048540'>way</span> <span m='1048660'>it</span> <span m='1048720'>comes.</span>
  <span m='1049140'>We</span> <span m='1049290'>put</span> <span m='1049470'>it</span>
  <span m='1049560'>in</span> <span m='1049660'>a</span> <span m='1049710'>feedback</span>
  <span m='1050130'>loop.</span> </p><p><span m='1053100'>So</span> <span m='1053210'>for</span>
  <span m='1053360'>example,</span> <span m='1053900'>here</span> <span m='1054320'>you</span>
  <span m='1054500'>could</span> <span m='1054650'>put</span> <span m='1054890'>it</span>
  <span m='1054980'>into</span> <span m='1056060'>a</span> <span m='1056330'>non-inverting</span>
  <span m='1057710'>amplifier</span> <span m='1059720'>where</span> <span m='1059870'>you</span>
  <span m='1060050'>take</span> <span m='1060350'>the</span> <span m='1060530'>output</span>
  <span m='1061430'>divided</span> <span m='1062120'>by</span> <span m='1062390'>a</span>
  <span m='1062480'>voltage</span> <span m='1062930'>divider</span> <span m='1063740'>and</span>
  <span m='1063890'>feed</span> <span m='1064190'>that</span> <span m='1064490'>back</span>
  <span m='1064820'>in.</span> <span m='1066260'>In</span> <span m='1066740'>6.003,</span>
  <span m='1068060'>the</span> <span m='1068150'>way</span> <span m='1068300'>we'll</span>
  <span m='1068450'>think</span> <span m='1068630'>about</span> <span m='1068870'>that</span>
  <span m='1069590'>is</span> <span m='1069830'>that</span> <span m='1069980'>the</span>
  <span m='1070130'>effectiveness</span> <span m='1070940'>plus</span> <span m='1071360'>and</span>
  <span m='1071440'>minus</span> <span m='1071840'>input</span> <span m='1072560'>is</span>
  <span m='1072740'>to</span> <span m='1072830'>take</span> <span m='1073040'>the</span>
  <span m='1073130'>difference</span> <span m='1073520'>between</span> <span m='1073850'>two</span>
  <span m='1074000'>signals.</span> <span m='1076850'>Right,</span> <span m='1077060'>we're</span>
  <span m='1077150'>going</span> <span m='1077270'>to</span> <span m='1077330'>take</span>
  <span m='1077540'>a</span> <span m='1077600'>circuit</span> <span m='1078020'>diagram</span>
  <span m='1078530'>and</span> <span m='1078620'>turn</span> <span m='1078860'>it</span>
  <span m='1078950'>into</span> <span m='1079940'>a</span> <span m='1083330'>integrator,</span>
  <span m='1085520'>gain-adder</span> <span m='1086810'>diagram,</span> <span m='1088100'>a</span>
  <span m='1088220'>block</span> <span m='1088670'>diagram.</span> <span m='1089120'>We're</span>
  <span m='1089210'>going to take</span> <span m='1089500'>a</span> <span m='1089600'>circuit</span>
  <span m='1089960'>and</span> <span m='1090050'>turn</span> <span m='1090200'>it</span>
  <span m='1090290'>into</span> <span m='1090410'>a</span> <span m='1090440'>block</span>
  <span m='1090650'>diagram.</span> </p><p><span m='1091700'>So</span> <span m='1091940'>the</span>
  <span m='1092060'>way</span> <span m='1092270'>we</span> <span m='1092450'>think</span>
  <span m='1092660'>about</span> <span m='1092900'>the</span> <span m='1092990'>plus</span>
  <span m='1093220'>and</span> <span m='1093290'>minus</span> <span m='1093620'>input</span>
  <span m='1093890'>of</span> <span m='1093950'>the</span> <span m='1094040'>op-amp</span>
  <span m='1094460'>is</span> <span m='1094610'>as</span> <span m='1094790'>a</span>
  <span m='1095380'>subtractor.</span> <span m='1099020'>And</span> <span m='1099740'>then</span>
  <span m='1100100'>this</span> <span m='1100310'>k</span> <span m='1100600'>of</span>
  <span m='1100730'>s</span> <span m='1101540'>that</span> <span m='1101690'>characterized--</span>
  <span m='1102470'>so</span> <span m='1102800'>this</span> <span m='1103070'>thing,</span>
  <span m='1103670'>right,</span> <span m='1103930'>this</span> <span m='1104720'>thing</span>
  <span m='1104940'>here,</span> <span m='1105920'>we</span> <span m='1106070'>plug-in</span>
  <span m='1106490'>there</span> <span m='1107180'>just</span> <span m='1107390'>as</span>
  <span m='1107510'>a</span> <span m='1107570'>box.</span> <span m='1109280'>And</span>
  <span m='1109400'>the</span> <span m='1109520'>effect</span> <span m='1109790'>of</span>
  <span m='1109850'>the</span> <span m='1109940'>resistors</span> <span m='1110480'>is</span>
  <span m='1110600'>to</span> <span m='1110690'>divide</span> <span m='1111710'>the</span>
  <span m='1111890'>output</span> <span m='1112340'>signal</span> <span m='1112730'>by</span>
  <span m='1112910'>some</span> <span m='1113150'>constant</span> <span m='1113700'>beta.</span>
  </p><p><span m='1115680'>So</span> <span m='1115860'>we</span> <span m='1116010'>can</span>
  <span m='1116190'>reduce</span> <span m='1117420'>the</span> <span m='1117840'>circuit</span>
  <span m='1118950'>to</span> <span m='1119160'>a</span> <span m='1119310'>6.003</span>
  <span m='1120120'>equivalent.</span> <span m='1120930'>And</span> <span m='1121050'>then</span>
  <span m='1121200'>we</span> <span m='1121290'>can</span> <span m='1121440'>use</span>
  <span m='1121710'>Black's</span> <span m='1122010'>equation</span> <span m='1122430'>and</span>
  <span m='1122550'>all</span> <span m='1122670'>those</span> <span m='1122850'>other</span>
  <span m='1123030'>things</span> <span m='1123250'>that</span> <span m='1123340'>we</span>
  <span m='1123420'>do</span> <span m='1123560'>in</span> <span m='1123730'>6.003.</span>
  <span m='1124900'>So</span> <span m='1124950'>we</span> <span m='1125070'>can</span>
  <span m='1125250'>write</span> <span m='1125640'>an</span> <span m='1125760'>expression</span>
  <span m='1126360'>for</span> <span m='1126510'>the</span> <span m='1126600'>closed-loop</span>
  <span m='1127050'>system</span> <span m='1127760'>the</span> <span m='1127860'>looks</span>
  <span m='1128070'>like</span> <span m='1128190'>k</span> <span m='1128400'>of</span>
  <span m='1128520'>s</span> <span m='1128850'>over</span> <span m='1129060'>1</span>
  <span m='1129240'>plus</span> <span m='1129480'>beta</span> <span m='1129720'>k
  of</span> <span m='1129990'>s.</span> <span m='1130800'>Make</span> <span m='1130950'>sense?</span>
  </p><p><span m='1133480'>So</span> <span m='1133780'>then,</span> <span m='1134590'>as</span>
  <span m='1134770'>we've</span> <span m='1134950'>already</span> <span m='1135280'>seen,</span>
  <span m='1135760'>the</span> <span m='1135910'>op-amp</span> <span m='1136930'>by</span>
  <span m='1137200'>itself</span> <span m='1138160'>looks</span> <span m='1138370'>like</span>
  <span m='1138550'>a</span> <span m='1138610'>pole</span> <span m='1138970'>at</span>
  <span m='1139060'>minus</span> <span m='1139420'>40.</span> <span m='1141680'>So</span>
  <span m='1141760'>we</span> <span m='1141910'>can</span> <span m='1142060'>substitute</span>
  <span m='1143140'>this</span> <span m='1143440'>expression</span> <span m='1144520'>into</span>
  <span m='1144880'>that</span> <span m='1145600'>expression</span> <span m='1146140'>for</span>
  <span m='1146260'>the</span> <span m='1146350'>closed</span> <span m='1146710'>loop.</span>
  <span m='1147760'>And</span> <span m='1147850'>we</span> <span m='1147970'>get</span>
  <span m='1148120'>a</span> <span m='1148180'>new</span> <span m='1148330'>closed</span>
  <span m='1148690'>loop.</span> <span m='1149530'>So</span> <span m='1149740'>h</span>
  <span m='1150010'>of</span> <span m='1150130'>s,</span> <span m='1152260'>which</span>
  <span m='1152500'>had</span> <span m='1152800'>been</span> <span m='1153130'>alpha</span>
  <span m='1153440'>k0</span> <span m='1154000'>over</span> <span m='1154280'>s</span>
  <span m='1154480'>plus</span> <span m='1154960'>alpha</span> <span m='1155620'>becomes--</span>
  <span m='1157030'>the</span> <span m='1157150'>new</span> <span m='1157360'>value</span>
  <span m='1157960'>is</span> <span m='1159550'>alpha</span> <span m='1159820'>k0</span>
  <span m='1162160'>over</span> <span m='1162430'>s</span> <span m='1162610'>plus</span>
  <span m='1162940'>alpha</span> <span m='1163420'>plus</span> <span m='1165490'>alpha</span>
  <span m='1166750'>beta</span> <span m='1167440'>k0.</span> <span m='1169740'>OK,</span>
  <span m='1169950'>so</span> <span m='1170760'>the</span> <span m='1170880'>point</span>
  <span m='1171300'>is</span> <span m='1171600'>that</span> <span m='1171750'>we</span>
  <span m='1171930'>can</span> <span m='1172080'>think</span> <span m='1172350'>about</span>
  <span m='1172650'>the</span> <span m='1172770'>way</span> <span m='1173130'>the</span>
  <span m='1173400'>feedback</span> <span m='1174240'>changes</span> <span m='1175050'>the</span>
  <span m='1175350'>system</span> <span m='1175920'>function</span> <span m='1177000'>by</span>
  <span m='1177150'>just</span> <span m='1177360'>formulating</span> <span m='1178350'>what's</span>
  <span m='1178710'>the</span> <span m='1178830'>circuit</span> <span m='1179160'>look</span>
  <span m='1179350'>like</span> <span m='1179640'>in</span> <span m='1179730'>terms</span>
  <span m='1180060'>of</span> <span m='1180150'>a</span> <span m='1180210'>6.003</span>
  <span m='1181020'>block</span> <span m='1181290'>diagram.</span> </p><p><span m='1185610'>So</span>
  <span m='1185690'>now,</span> <span m='1187310'>the</span> <span m='1187550'>effect</span>
  <span m='1187970'>of</span> <span m='1188150'>that,</span> <span m='1188630'>it</span>
  <span m='1188810'>looks</span> <span m='1189140'>as</span> <span m='1189290'>though</span>
  <span m='1189650'>what</span> <span m='1189800'>happens</span> <span m='1190250'>is</span>
  <span m='1191090'>the</span> <span m='1191210'>pole</span> <span m='1192140'>went</span>
  <span m='1192440'>from</span> <span m='1192680'>here</span> <span m='1193070'>to</span>
  <span m='1193220'>here.</span> <span m='1195020'>How</span> <span m='1195950'>big</span>
  <span m='1196190'>of</span> <span m='1196280'>a</span> <span m='1196310'>change</span>
  <span m='1196670'>is</span> <span m='1196820'>that?</span> <span m='1198740'>What's</span>
  <span m='1199010'>the</span> <span m='1199130'>biggest</span> <span m='1199610'>change</span>
  <span m='1200210'>in</span> <span m='1200420'>the</span> <span m='1200720'>position</span>
  <span m='1201290'>of</span> <span m='1201420'>the</span> <span m='1201530'>pole</span>
  <span m='1202580'>that</span> <span m='1202760'>you</span> <span m='1202850'>can</span>
  <span m='1203030'>achieve</span> <span m='1203840'>using</span> <span m='1204260'>feedback?</span>
  </p><p><span m='1224600'>AUDIENCE:</span> <span m='1224846'>[INAUDIBLE]</span> <span
  m='1225092'>distance.</span> </p><p><span m='1226568'>DENNIS FREEMAN:</span> <span
  m='1226732'>I'm</span> <span m='1226896'>sorry.</span> </p><p><span m='1228044'>AUDIENCE:</span>
  <span m='1228208'>[? Is ?]</span> <span m='1228372'>[? beta ?]</span> <span m='1228536'>the</span>
  <span m='1229028'>[INAUDIBLE]</span> <span m='1229520'>distance.</span> <span m='1230012'>Or
  where</span> <span m='1230504'>are they</span> <span m='1230996'>located?</span>
  </p><p><span m='1232010'>DENNIS FREEMAN:</span> <span m='1232070'>I</span> <span
  m='1232130'>want</span> <span m='1232280'>a</span> <span m='1232370'>factor</span>
  <span m='1233090'>by</span> <span m='1233270'>which</span> <span m='1233540'>you</span>
  <span m='1233660'>multiply</span> <span m='1234200'>alpha</span> <span m='1234530'>to</span>
  <span m='1234650'>find</span> <span m='1235010'>the</span> <span m='1235160'>biggest</span>
  <span m='1235700'>place</span> <span m='1236180'>that</span> <span m='1236360'>you</span>
  <span m='1236480'>could</span> <span m='1236690'>have</span> <span m='1236810'>put</span>
  <span m='1236990'>the</span> <span m='1237110'>new</span> <span m='1238460'>pole.</span>
  <span m='1245780'>I</span> <span m='1245870'>didn't</span> <span m='1246020'>say</span>
  <span m='1246170'>that</span> <span m='1246290'>right.</span> <span m='1246680'>I
  didn't</span> <span m='1246870'>say</span> <span m='1247010'>that</span> <span m='1247130'>right.</span>
  <span m='1247580'>I</span> <span m='1247640'>want</span> <span m='1247760'>to</span>
  <span m='1247820'>know</span> <span m='1247970'>where is</span> <span m='1248270'>the</span>
  <span m='1248390'>new</span> <span m='1248540'>pole.</span> <span m='1249630'>Sorry,</span>
  <span m='1250180'>I</span> <span m='1250340'>confused</span> <span m='1250670'>myself.</span>
  </p><p><span m='1251780'>Where</span> <span m='1252080'>is</span> <span m='1252260'>the</span>
  <span m='1252380'>new</span> <span m='1252560'>pole?</span> <span m='1253220'>How</span>
  <span m='1253520'>left</span> <span m='1254120'>can</span> <span m='1254300'>you</span>
  <span m='1254420'>put</span> <span m='1254600'>the</span> <span m='1254690'>new--</span>
  <span m='1255200'>how</span> <span m='1255650'>left</span> <span m='1256010'>can</span>
  <span m='1256190'>you</span> <span m='1256280'>get</span> <span m='1256460'>the</span>
  <span m='1256550'>new</span> <span m='1256700'>pole</span> <span m='1256910'>to</span>
  <span m='1257030'>be?</span> <span m='1258310'>What's</span> <span m='1258550'>the</span>
  <span m='1258670'>furtherest--</span> <span m='1259310'>left</span> <span m='1259580'>is</span>
  <span m='1259720'>good,</span> <span m='1259960'>right?</span> <span m='1261210'>Left</span>
  <span m='1261480'>is</span> <span m='1261570'>good.</span> <span m='1262180'>Everybody</span>
  <span m='1262440'>knows</span> <span m='1262620'>that,</span> <span m='1262910'>right?</span>
  <span m='1264880'>So</span> <span m='1265150'>right</span> <span m='1265480'>is</span>
  <span m='1265600'>bad.</span> </p><p><span m='1267860'>So</span> <span m='1268310'>small</span>
  <span m='1269630'>distances</span> <span m='1270650'>in</span> <span m='1270860'>the</span>
  <span m='1271100'>s-plane</span> <span m='1271580'>correspond</span> <span m='1272180'>to</span>
  <span m='1274040'>slow</span> <span m='1274580'>responses.</span> <span m='1275750'>Big</span>
  <span m='1276020'>distances</span> <span m='1276650'>correspond</span> <span m='1277100'>to</span>
  <span m='1277250'>fast</span> <span m='1277640'>responses.</span> <span m='1278180'>That's</span>
  <span m='1278330'>what</span> <span m='1278420'>we</span> <span m='1278510'>saw</span>
  <span m='1278720'>in</span> <span m='1278810'>part</span> <span m='1279110'>one.</span>
  </p><p><span m='1280630'>So</span> <span m='1280780'>we're</span> <span m='1280900'>trying</span>
  <span m='1281170'>to</span> <span m='1281230'>push</span> <span m='1281470'>the</span>
  <span m='1281560'>pole</span> <span m='1281860'>that</span> <span m='1282100'>way</span>
  <span m='1282280'>as</span> <span m='1282400'>far</span> <span m='1282580'>as</span>
  <span m='1282700'>we</span> <span m='1282790'>can.</span> <span m='1283220'>How</span>
  <span m='1283240'>far</span> <span m='1283450'>can</span> <span m='1283600'>we</span>
  <span m='1283690'>get</span> <span m='1283840'>it</span> <span m='1283900'>to</span>
  <span m='1283990'>go?</span> <span m='1286960'>OK,</span> <span m='1287200'>everybody</span>
  <span m='1287500'>raise</span> <span m='1287650'>your</span> <span m='1287740'>hands.</span>
  <span m='1288460'>The</span> <span m='1288550'>answer</span> <span m='1288850'>is--</span>
  <span m='1290940'>and</span> <span m='1291090'>again,</span> <span m='1291750'>I</span>
  <span m='1291870'>see</span> <span m='1292080'>lots</span> <span m='1292320'>of</span>
  <span m='1292410'>answers</span> <span m='1292650'>that</span> <span m='1292760'>I
  don't</span> <span m='1292920'>quite</span> <span m='1293310'>like.</span> <span
  m='1295430'>With</span> <span m='1295630'>a</span> <span m='1295720'>minor</span>
  <span m='1296050'>perturbation,</span> <span m='1296860'>all</span> <span m='1297070'>those</span>
  <span m='1297280'>people</span> <span m='1297550'>who</span> <span m='1297670'>I</span>
  <span m='1297760'>don't</span> <span m='1297970'>like</span> <span m='1298210'>can</span>
  <span m='1298360'>become</span> <span m='1298720'>right</span> <span m='1299080'>by</span>
  <span m='1299260'>saying--</span> <span m='1301910'>so</span> <span m='1302060'>a</span>
  <span m='1302090'>lot</span> <span m='1302270'>of</span> <span m='1302330'>people</span>
  <span m='1302600'>have</span> <span m='1302690'>said</span> <span m='1302870'>this,</span>
  <span m='1303080'>which</span> <span m='1303260'>I</span> <span m='1303350'>don't</span>
  <span m='1303530'>quite</span> <span m='1303740'>like.</span> </p><p><span m='1304580'>What's</span>
  <span m='1304820'>the</span> <span m='1304940'>biggest</span> <span m='1305540'>distance</span>
  <span m='1305960'>that</span> <span m='1306080'>I</span> <span m='1306170'>can</span>
  <span m='1306290'>move</span> <span m='1306530'>it?</span> <span m='1310990'>OK,</span>
  <span m='1311890'>new</span> <span m='1312080'>vote--</span> <span m='1313130'>I</span>
  <span m='1313220'>didn't</span> <span m='1313460'>like</span> <span m='1313670'>tw0.</span>
  <span m='1314750'>And</span> <span m='1314870'>so</span> <span m='1314990'>therefore,</span>
  <span m='1315440'>I</span> <span m='1315590'>will</span> <span m='1315710'>change</span>
  <span m='1315950'>my</span> <span m='1316130'>answer</span> <span m='1316370'>to</span>
  <span m='1316550'>four.</span> <span m='1317060'>Wrong,</span> <span m='1318360'>no.</span>
  <span m='1322250'>How</span> <span m='1322550'>big</span> <span m='1322850'>can</span>
  <span m='1323160'>beta be?</span> <span m='1329360'>How</span> <span m='1329510'>big</span>
  <span m='1329750'>can</span> <span m='1330010'>beta be?</span> </p><p><span m='1336660'>What's</span>
  <span m='1336840'>the</span> <span m='1336900'>biggest</span> <span m='1337170'>possible</span>
  <span m='1337530'>value of</span> <span m='1337640'>beta?</span> <span m='1339230'>One.</span>
  <span m='1340560'>So</span> <span m='1340710'>how</span> <span m='1340890'>far</span>
  <span m='1341070'>can</span> <span m='1341220'>I</span> <span m='1341280'>push</span>
  <span m='1341490'>it</span> <span m='1341580'>to</span> <span m='1341670'>the</span>
  <span m='1341790'>left?</span> <span m='1344940'>So</span> <span m='1345150'>I</span>
  <span m='1345240'>can</span> <span m='1345390'>push</span> <span m='1345690'>it</span>
  <span m='1348040'>this</span> <span m='1348190'>far.</span> <span m='1348670'>Right?</span>
  <span m='1349470'>So</span> <span m='1349660'>if</span> <span m='1349850'>I</span>
  <span m='1349990'>make</span> <span m='1350150'>beta</span> <span m='1350530'>1,</span>
  <span m='1350920'>that's</span> <span m='1351130'>as</span> <span m='1351220'>far</span>
  <span m='1351370'>as</span> <span m='1351460'>it</span> <span m='1351520'>goes.</span>
  <span m='1352170'>Beta</span> <span m='1352270'>0</span> <span m='1353080'>is</span>
  <span m='1353230'>kind</span> <span m='1353440'>of</span> <span m='1353530'>the</span>
  <span m='1353620'>rightmost</span> <span m='1354070'>position.</span> <span m='1354550'>Beta</span>
  <span m='1354790'>1</span> <span m='1355150'>is</span> <span m='1355300'>the</span>
  <span m='1355420'>leftmost</span> <span m='1355810'>position.</span> <span m='1356260'>I</span>
  <span m='1356350'>can</span> <span m='1356470'>get</span> <span m='1356650'>it</span>
  <span m='1356740'>that</span> <span m='1356980'>high.</span> </p><p><span m='1357730'>But</span>
  <span m='1357880'>that's</span> <span m='1358120'>very</span> <span m='1358390'>good.</span>
  <span m='1358810'>Right?</span> <span m='1359740'>1</span> <span m='1360040'>plus</span>
  <span m='1360340'>k0--</span> <span m='1360880'>k0</span> <span m='1361240'>is</span>
  <span m='1361360'>a</span> <span m='1361420'>number</span> <span m='1361660'>like</span>
  <span m='1361900'>10</span> <span m='1362110'>to</span> <span m='1362200'>the</span>
  <span m='1362320'>5th.</span> <span m='1364250'>So</span> <span m='1364330'>I</span>
  <span m='1364450'>can</span> <span m='1364600'>get</span> <span m='1364780'>at</span>
  <span m='1364840'>like</span> <span m='1365020'>10</span> <span m='1365230'>to</span>
  <span m='1365320'>the</span> <span m='1365440'>5th</span> <span m='1365680'>bigger</span>
  <span m='1365980'>than</span> <span m='1366130'>it</span> <span m='1366220'>was.</span>
  <span m='1366730'>That's</span> <span m='1367090'>enormous.</span> </p><p><span
  m='1368050'>That</span> <span m='1368260'>means</span> <span m='1368710'>that</span>
  <span m='1368950'>I</span> <span m='1369010'>can</span> <span m='1369190'>stretch</span>
  <span m='1369640'>the</span> <span m='1369730'>frequency</span> <span m='1370210'>response.</span>
  <span m='1372100'>If</span> <span m='1372280'>the</span> <span m='1372400'>pole</span>
  <span m='1372910'>is</span> <span m='1373090'>the</span> <span m='1373210'>thing</span>
  <span m='1373420'>that</span> <span m='1373540'>determines</span> <span m='1374050'>the</span>
  <span m='1374110'>frequency</span> <span m='1374530'>response</span> <span m='1374980'>by</span>
  <span m='1375130'>that</span> <span m='1375310'>construction</span> <span m='1375850'>up</span>
  <span m='1375970'>there,</span> <span m='1376600'>I</span> <span m='1376690'>can</span>
  <span m='1376810'>stretch</span> <span m='1377170'>the</span> <span m='1377290'>frequency</span>
  <span m='1377710'>response</span> <span m='1378070'>by</span> <span m='1378190'>10</span>
  <span m='1378360'>to</span> <span m='1378430'>the</span> <span m='1378520'>5th.</span>
  <span m='1379190'>That's</span> <span m='1379300'>huge.</span> <span m='1381550'>Pure</span>
  <span m='1382330'>win,</span> <span m='1383160'>right?</span> </p><p><span m='1384550'>Well,</span>
  <span m='1384820'>that</span> <span m='1384970'>doesn't</span> <span m='1385180'>sound</span>
  <span m='1385390'>right.</span> <span m='1386990'>So</span> <span m='1387010'>I've</span>
  <span m='1387160'>stretched</span> <span m='1387550'>the</span> <span m='1387640'>region</span>
  <span m='1388000'>where</span> <span m='1388150'>the</span> <span m='1388270'>gain</span>
  <span m='1388540'>is</span> <span m='1388660'>constant.</span> <span m='1389070'>I've</span>
  <span m='1389180'>stretched</span> <span m='1389500'>the</span> <span m='1389620'>region</span>
  <span m='1389950'>where</span> <span m='1390130'>the</span> <span m='1390280'>phase</span>
  <span m='1390730'>is</span> <span m='1390850'>close</span> <span m='1391150'>to</span>
  <span m='1391300'>0.</span> <span m='1391720'>It's</span> <span m='1391830'>a</span>
  <span m='1391860'>100%</span> <span m='1392560'>win</span> <span m='1392950'>except</span>
  <span m='1393550'>that</span> <span m='1395200'>I've</span> <span m='1395320'>cheated</span>
  <span m='1395650'>when</span> <span m='1395800'>I</span> <span m='1395860'>drew</span>
  <span m='1396010'>the</span> <span m='1396130'>plot</span> <span m='1396850'>because</span>
  <span m='1397840'>I</span> <span m='1397960'>normalized</span> <span m='1398680'>it</span>
  <span m='1398890'>by</span> <span m='1399160'>the</span> <span m='1399280'>DC</span>
  <span m='1399760'>gain.</span> </p><p><span m='1400330'>DC,</span> <span m='1400960'>I</span>
  <span m='1401050'>probably</span> <span m='1401410'>didn't</span> <span m='1401590'>define</span>
  <span m='1401950'>that</span> <span m='1402070'>yet.</span> <span m='1402280'>DC</span>
  <span m='1402700'>is</span> <span m='1402820'>direct</span> <span m='1403120'>current.</span>
  <span m='1403855'>It</span> <span m='1404110'>has</span> <span m='1404290'>nothing</span>
  <span m='1404740'>to</span> <span m='1404830'>do</span> <span m='1404980'>with</span>
  <span m='1405100'>current</span> <span m='1405520'>or</span> <span m='1405730'>direct.</span>
  <span m='1406570'>DC</span> <span m='1407080'>means</span> <span m='1407380'>zero</span>
  <span m='1407770'>frequency.</span> <span m='1408760'>I</span> <span m='1408850'>have</span>
  <span m='1409090'>no</span> <span m='1409420'>idea</span> <span m='1409720'>why</span>
  <span m='1409900'>we</span> <span m='1410080'>insist</span> <span m='1410380'>on</span>
  <span m='1410500'>using</span> <span m='1410740'>that</span> <span m='1410890'>word,</span>
  <span m='1411430'>but</span> <span m='1411580'>we</span> <span m='1411700'>do.</span>
  <span m='1412770'>DC</span> <span m='1413440'>means</span> <span m='1414070'>zero</span>
  <span m='1414490'>frequency.</span> <span m='1415740'>OK,</span> <span m='1416320'>so</span>
  <span m='1416470'>you</span> <span m='1416560'>just</span> <span m='1416710'>do</span>
  <span m='1416860'>that</span> <span m='1417040'>automatic</span> <span m='1417550'>mapping</span>
  <span m='1417940'>in</span> <span m='1418030'>your</span> <span m='1418150'>head.</span>
  <span m='1418930'>Every</span> <span m='1419140'>time</span> <span m='1419380'>I</span>
  <span m='1419560'>say</span> <span m='1419740'>DC,</span> <span m='1420250'>I</span>
  <span m='1420400'>mean</span> <span m='1420700'>zero</span> <span m='1421000'>frequency.</span>
  </p><p><span m='1422590'>Everybody</span> <span m='1422920'>else</span> <span m='1423110'>talks</span>
  <span m='1423310'>that way</span> <span m='1423430'>too.</span> <span m='1423880'>So</span>
  <span m='1424060'>the</span> <span m='1424180'>DC</span> <span m='1424570'>gain,</span>
  <span m='1426340'>I've</span> <span m='1426520'>divided</span> <span m='1427240'>the</span>
  <span m='1427360'>magnitude</span> <span m='1427960'>by</span> <span m='1428110'>the</span>
  <span m='1428230'>DC</span> <span m='1428650'>gain,</span> <span m='1429250'>h</span>
  <span m='1429520'>of</span> <span m='1429780'>j0.</span> <span m='1431960'>So</span>
  <span m='1432140'>this</span> <span m='1432350'>is</span> <span m='1432500'>the</span>
  <span m='1432620'>relative</span> <span m='1433100'>frequency</span> <span m='1434090'>magnitude,</span>
  <span m='1434800'>h</span> <span m='1435020'>of</span> <span m='1435110'>j</span>
  <span m='1435440'>omega,</span> <span m='1436190'>divided</span> <span m='1436700'>by</span>
  <span m='1437440'>the</span> <span m='1437960'>magnitude</span> <span m='1438530'>at</span>
  <span m='1439400'>omega</span> <span m='1439850'>equals</span> <span m='1440180'>0.</span>
  <span m='1442160'>Had</span> <span m='1442430'>I</span> <span m='1442550'>not</span>
  <span m='1442850'>done</span> <span m='1443150'>that,</span> <span m='1444230'>the</span>
  <span m='1444320'>picture</span> <span m='1444680'>would</span> <span m='1444830'>have</span>
  <span m='1444950'>looked</span> <span m='1445160'>different.</span> </p><p><span
  m='1447810'>If</span> <span m='1448020'>you</span> <span m='1448110'>think</span>
  <span m='1448350'>about</span> <span m='1448590'>what</span> <span m='1448800'>happens--</span>
  <span m='1449460'>so</span> <span m='1449670'>the</span> <span m='1449760'>top</span>
  <span m='1450150'>curve</span> <span m='1450480'>here</span> <span m='1450690'>shows</span>
  <span m='1451050'>what</span> <span m='1451230'>happens</span> <span m='1451980'>when</span>
  <span m='1452630'>the--</span> <span m='1453500'>shows</span> <span m='1453930'>the</span>
  <span m='1454050'>response</span> <span m='1454530'>curve</span> <span m='1455490'>for</span>
  <span m='1455760'>a</span> <span m='1455820'>741</span> <span m='1456630'>op-amp</span>
  <span m='1457050'>with</span> <span m='1457170'>no</span> <span m='1457320'>feedback.</span>
  <span m='1458970'>It</span> <span m='1459060'>has</span> <span m='1459240'>a</span>
  <span m='1459300'>pole</span> <span m='1459620'>at</span> <span m='1459720'>40.</span>
  <span m='1461591'>It</span> <span m='1462080'>has</span> <span m='1462230'>a</span>
  <span m='1462290'>pole</span> <span m='1462490'>at</span> <span m='1462560'>minus</span>
  <span m='1462900'>40</span> <span m='1463340'>to</span> <span m='1463460'>be</span>
  <span m='1463550'>a</span> <span m='1463610'>little</span> <span m='1463760'>more</span>
  <span m='1464150'>correct.</span> <span m='1465320'>So</span> <span m='1465470'>there's</span>
  <span m='1465650'>a</span> <span m='1465680'>single</span> <span m='1465950'>pole
  at</span> <span m='1466220'>minus</span> <span m='1466550'>40.</span> <span m='1467600'>That</span>
  <span m='1467750'>corresponds</span> <span m='1468240'>to</span> <span m='1468300'>beta</span>
  <span m='1468590'>0.</span> <span m='1468980'>That's</span> <span m='1469190'>open</span>
  <span m='1469430'>loop,</span> <span m='1470240'>no</span> <span m='1470390'>feedback.</span>
  </p><p><span m='1472000'>OK,</span> <span m='1473820'>and</span> <span m='1473970'>what</span>
  <span m='1474120'>you</span> <span m='1474270'>can</span> <span m='1474390'>see</span>
  <span m='1474720'>is</span> <span m='1474930'>the</span> <span m='1475050'>DC</span>
  <span m='1475530'>gain</span> <span m='1475920'>is</span> <span m='1476040'>2</span>
  <span m='1476190'>times</span> <span m='1476470'>10</span> <span m='1476590'>to</span>
  <span m='1476670'>the</span> <span m='1476740'>5th.</span> <span m='1478700'>And</span>
  <span m='1479000'>there's</span> <span m='1479240'>an</span> <span m='1479450'>AC</span>
  <span m='1479890'>gain</span> <span m='1480230'>defined</span> <span m='1480740'>by</span>
  <span m='1480950'>the</span> <span m='1481070'>cutoff</span> <span m='1481400'>frequency.</span>
  <span m='1483160'>If</span> <span m='1483280'>you</span> <span m='1483400'>compare</span>
  <span m='1483880'>this</span> <span m='1484120'>expression</span> <span m='1484630'>and</span>
  <span m='1484720'>that</span> <span m='1484930'>expression,</span> <span m='1485920'>the</span>
  <span m='1486100'>interesting</span> <span m='1486670'>thing</span> <span m='1486910'>that</span>
  <span m='1487030'>happens</span> <span m='1488830'>is</span> <span m='1489070'>that</span>
  <span m='1489250'>the</span> <span m='1489370'>DC</span> <span m='1490540'>response</span>
  <span m='1492890'>depends</span> <span m='1493370'>critically</span> <span m='1494000'>on</span>
  <span m='1494240'>beta.</span> </p><p><span m='1497554'>But</span> <span m='1498010'>the</span>
  <span m='1498130'>high-frequency</span> <span m='1498970'>asymptote</span> <span
  m='1499630'>doesn't</span> <span m='1499960'>depend</span> <span m='1500290'>on</span>
  <span m='1500410'>beta</span> <span m='1500680'>at</span> <span m='1500860'>all.</span>
  <span m='1503020'>The</span> <span m='1503110'>high-frequency</span> <span m='1503740'>asymptote</span>
  <span m='1504190'>of</span> <span m='1504280'>this</span> <span m='1504550'>is</span>
  <span m='1504670'>alpha</span> <span m='1504920'>k0</span> <span m='1505360'>over</span>
  <span m='1505590'>s.</span> <span m='1508190'>The</span> <span m='1508280'>high-frequency</span>
  <span m='1508850'>asymptote</span> <span m='1509120'>of</span> <span m='1509390'>this</span>
  <span m='1509630'>is</span> <span m='1509720'>alpha</span> <span m='1510160'>k0</span>
  <span m='1510280'>over</span> <span m='1510510'>s.</span> <span m='1510850'>They're</span>
  <span m='1510950'>the</span> <span m='1511070'>same</span> <span m='1511400'>high-frequency</span>
  <span m='1511950'>asymptote.</span> </p><p><span m='1514040'>What</span> <span m='1514250'>happened</span>
  <span m='1514670'>was</span> <span m='1515060'>that</span> <span m='1515180'>as</span>
  <span m='1515330'>I</span> <span m='1515450'>increased</span> <span m='1516080'>the</span>
  <span m='1516200'>feedback,</span> <span m='1517430'>I</span> <span m='1517580'>lopped</span>
  <span m='1518060'>off</span> <span m='1519720'>the</span> <span m='1519810'>low-frequency</span>
  <span m='1520440'>gain,</span> <span m='1520800'>which</span> <span m='1520980'>had</span>
  <span m='1521130'>the</span> <span m='1521310'>effect</span> <span m='1521790'>of</span>
  <span m='1521910'>making</span> <span m='1522300'>the</span> <span m='1522420'>frequency</span>
  <span m='1523230'>look</span> <span m='1523500'>like</span> <span m='1523770'>it</span>
  <span m='1523950'>got</span> <span m='1524220'>very</span> <span m='1524490'>big.</span>
  <span m='1527390'>So</span> <span m='1527650'>pure</span> <span m='1528040'>win?</span>
  <span m='1528360'>No.</span> <span m='1529030'>Almost</span> <span m='1529540'>pure</span>
  <span m='1529810'>win?</span> <span m='1530050'>Yes.</span> </p><p><span m='1531030'>OK,</span>
  <span m='1531260'>I've</span> <span m='1531460'>traded--</span> <span m='1532210'>the</span>
  <span m='1532360'>trick</span> <span m='1532630'>is</span> <span m='1533110'>I've</span>
  <span m='1533320'>traded</span> <span m='1534220'>gain</span> <span m='1535030'>for</span>
  <span m='1535750'>bandwidth.</span> <span m='1537130'>That's</span> <span m='1537370'>important</span>
  <span m='1537880'>because</span> <span m='1538630'>the</span> <span m='1538720'>folks</span>
  <span m='1538990'>who</span> <span m='1539080'>know</span> <span m='1539230'>how</span>
  <span m='1539410'>to</span> <span m='1539500'>microfabricate</span> <span m='1540250'>things</span>
  <span m='1540550'>know</span> <span m='1540790'>how</span> <span m='1540940'>to</span>
  <span m='1541060'>make</span> <span m='1541270'>things</span> <span m='1541870'>with</span>
  <span m='1542080'>very</span> <span m='1542620'>high</span> <span m='1543020'>gain.</span>
  <span m='1545060'>Making</span> <span m='1545450'>things</span> <span m='1545810'>that</span>
  <span m='1545990'>are</span> <span m='1546080'>fast</span> <span m='1546520'>is</span>
  <span m='1546800'>harder.</span> <span m='1548910'>This</span> <span m='1549090'>is</span>
  <span m='1549180'>a</span> <span m='1549240'>way</span> <span m='1549480'>that</span>
  <span m='1549600'>we</span> <span m='1549780'>can</span> <span m='1549960'>take</span>
  <span m='1550230'>advantage</span> <span m='1550890'>of</span> <span m='1551100'>the</span>
  <span m='1551250'>relative</span> <span m='1551820'>simplicity</span> <span m='1552600'>of</span>
  <span m='1552720'>making</span> <span m='1553050'>things</span> <span m='1553290'>with</span>
  <span m='1553470'>high</span> <span m='1553710'>gain</span> <span m='1554820'>to</span>
  <span m='1554940'>make</span> <span m='1555180'>them</span> <span m='1555360'>behave</span>
  <span m='1556050'>as</span> <span m='1556350'>though</span> <span m='1556560'>they're</span>
  <span m='1556740'>fast.</span> </p><p><span m='1558870'>OK,</span> <span m='1560300'>you</span>
  <span m='1560420'>can</span> <span m='1560510'>see</span> <span m='1560660'>the</span>
  <span m='1560780'>same</span> <span m='1560960'>thing</span> <span m='1561140'>if</span>
  <span m='1561260'>you</span> <span m='1561410'>think</span> <span m='1561590'>about</span>
  <span m='1561860'>the</span> <span m='1561980'>response</span> <span m='1562470'>in</span>
  <span m='1562600'>time.</span> <span m='1564860'>If</span> <span m='1565010'>you</span>
  <span m='1565070'>think</span> <span m='1565220'>about</span> <span m='1565400'>the</span>
  <span m='1565490'>response in</span> <span m='1565910'>time,</span> <span m='1566540'>we're</span>
  <span m='1567110'>going</span> <span m='1567230'>to</span> <span m='1567320'>go</span>
  <span m='1567500'>from</span> <span m='1568270'>e</span> <span m='1568510'>to</span>
  <span m='1568580'>the</span> <span m='1568640'>minus</span> <span m='1568960'>alpha</span>
  <span m='1569230'>t</span> <span m='1570020'>to--</span> <span m='1570380'>I</span>
  <span m='1570470'>guess</span> <span m='1570620'>I</span> <span m='1570680'>didn't</span>
  <span m='1570830'>write</span> <span m='1570980'>it</span> <span m='1571070'>down.</span>
  <span m='1571640'>It's</span> <span m='1571760'>going</span> <span m='1571910'>to</span>
  <span m='1571970'>be</span> <span m='1572060'>e</span> <span m='1572160'>to</span>
  <span m='1572300'>the</span> <span m='1572420'>minus</span> <span m='1572720'>alpha</span>
  <span m='1573070'>1 plus</span> <span m='1573450'>alpha</span> <span m='1573590'>beta</span>
  <span m='1573850'>k0</span> <span m='1574850'>t,</span> <span m='1576260'>same</span>
  <span m='1576530'>factor.</span> <span m='1578620'>It's</span> <span m='1578770'>going</span>
  <span m='1578920'>to</span> <span m='1579010'>get</span> <span m='1579160'>10</span>
  <span m='1579370'>to</span> <span m='1579460'>the</span> <span m='1579550'>5th</span>
  <span m='1579730'>times</span> <span m='1580060'>faster.</span> </p><p><span m='1582250'>Again,</span>
  <span m='1582550'>it</span> <span m='1582850'>looks</span> <span m='1583120'>like</span>
  <span m='1583300'>pure</span> <span m='1583690'>win.</span> <span m='1585070'>But</span>
  <span m='1585220'>that's</span> <span m='1585430'>because</span> <span m='1585730'>I've</span>
  <span m='1585880'>cheated</span> <span m='1586810'>because</span> <span m='1587170'>I'm</span>
  <span m='1587320'>plotting</span> <span m='1588640'>via</span> <span m='1589090'>this</span>
  <span m='1589330'>normalized</span> <span m='1590440'>final</span> <span m='1590860'>value</span>
  <span m='1592210'>that</span> <span m='1592360'>depends</span> <span m='1592750'>on</span>
  <span m='1592870'>beta.</span> <span m='1595440'>If</span> <span m='1595650'>beta</span>
  <span m='1596010'>were</span> <span m='1596130'>0,</span> <span m='1596650'>the</span>
  <span m='1596670'>final</span> <span m='1596940'>value</span> <span m='1597360'>is</span>
  <span m='1597600'>2</span> <span m='1597780'>times</span> <span m='1598080'>10</span>
  <span m='1598260'>the</span> <span m='1598350'>5th.</span> <span m='1599520'>If</span>
  <span m='1599730'>beta</span> <span m='1599900'>is</span> <span m='1600090'>anything</span>
  <span m='1600450'>else,</span> <span m='1600840'>the</span> <span m='1600990'>final</span>
  <span m='1601230'>value</span> <span m='1601590'>is</span> <span m='1601740'>smaller.</span>
  </p><p><span m='1603240'>If</span> <span m='1603420'>I</span> <span m='1603540'>plot
  it</span> <span m='1603990'>not</span> <span m='1604320'>normalized,</span> <span
  m='1605700'>you</span> <span m='1605820'>get</span> <span m='1605970'>a</span> <span
  m='1606030'>kind</span> <span m='1606270'>of</span> <span m='1606330'>different</span>
  <span m='1606690'>picture.</span> <span m='1607930'>So</span> <span m='1610710'>if</span>
  <span m='1610890'>you</span> <span m='1611010'>were</span> <span m='1611100'>to</span>
  <span m='1611160'>use</span> <span m='1611370'>the</span> <span m='1611460'>op-amp</span>
  <span m='1611820'>open</span> <span m='1612090'>loop,</span> <span m='1613200'>the</span>
  <span m='1613320'>response</span> <span m='1613770'>has</span> <span m='1614100'>a</span>
  <span m='1614160'>time</span> <span m='1614460'>constant</span> <span m='1614820'>of</span>
  <span m='1614880'>1</span> <span m='1615060'>over</span> <span m='1615270'>40,</span>
  <span m='1615600'>as</span> <span m='1615690'>we</span> <span m='1615810'>said</span>
  <span m='1615960'>before.</span> <span m='1618260'>If</span> <span m='1618310'>you</span>
  <span m='1618610'>include</span> <span m='1619090'>feedback,</span> <span m='1619840'>it</span>
  <span m='1620020'>decreases</span> <span m='1620890'>the</span> <span m='1621010'>final</span>
  <span m='1621280'>value,</span> <span m='1624930'>but</span> <span m='1625200'>has</span>
  <span m='1625440'>the</span> <span m='1625560'>property</span> <span m='1626580'>that</span>
  <span m='1626790'>it</span> <span m='1626910'>does</span> <span m='1627120'>not</span>
  <span m='1627420'>change</span> <span m='1627870'>this</span> <span m='1628070'>slope.</span>
  </p><p><span m='1630660'>So</span> <span m='1630770'>if</span> <span m='1630860'>you</span>
  <span m='1630950'>think</span> <span m='1631160'>about</span> <span m='1631490'>this,</span>
  <span m='1633170'>this</span> <span m='1633590'>is</span> <span m='1633650'>an</span>
  <span m='1633770'>analytic</span> <span m='1634190'>expression</span> <span m='1634760'>for</span>
  <span m='1635120'>the</span> <span m='1635960'>closed-loop</span> <span m='1636560'>step</span>
  <span m='1636800'>response.</span> <span m='1638320'>I</span> <span m='1638510'>get</span>
  <span m='1638810'>that</span> <span m='1639080'>by</span> <span m='1639380'>integrating</span>
  <span m='1641930'>one</span> <span m='1642080'>of</span> <span m='1642170'>these</span>
  <span m='1642350'>expressions.</span> <span m='1642830'>I</span> <span m='1642860'>didn't</span>
  <span m='1643010'>write</span> <span m='1643160'>the</span> <span m='1643250'>beta</span>
  <span m='1643460'>one</span> <span m='1643610'>down.</span> <span m='1644150'>I</span>
  <span m='1644240'>need</span> <span m='1644450'>the</span> <span m='1644570'>beta</span>
  <span m='1644930'>equivalent</span> <span m='1645480'>one</span> <span m='1645710'>of</span>
  <span m='1645830'>these.</span> <span m='1647930'>If</span> <span m='1648050'>you</span>
  <span m='1648140'>right</span> <span m='1648320'>the</span> <span m='1648410'>beta</span>
  <span m='1648680'>equivalent</span> <span m='1649160'>one</span> <span m='1649310'>of</span>
  <span m='1649400'>these,</span> <span m='1649640'>which</span> <span m='1649820'>is</span>
  <span m='1649910'>on</span> <span m='1650030'>a</span> <span m='1650090'>previous</span>
  <span m='1650450'>slide,</span> <span m='1651290'>and</span> <span m='1651410'>integrate</span>
  <span m='1651860'>it,</span> <span m='1653580'>you</span> <span m='1654060'>you</span>
  <span m='1654330'>get</span> <span m='1654840'>this</span> <span m='1655320'>expression.</span>
  </p><p><span m='1657720'>And</span> <span m='1657840'>the</span> <span m='1658640'>if</span>
  <span m='1658820'>you</span> <span m='1658940'>differentiate</span> <span m='1659810'>this</span>
  <span m='1659990'>expression</span> <span m='1660560'>with</span> <span m='1660740'>regard</span>
  <span m='1661070'>to</span> <span m='1661160'>time</span> <span m='1661730'>to</span>
  <span m='1661850'>find</span> <span m='1662120'>the</span> <span m='1662210'>slope,</span>
  <span m='1662760'>the</span> <span m='1662780'>slope</span> <span m='1663050'>at</span>
  <span m='1663140'>0</span> <span m='1663920'>is</span> <span m='1664250'>unchanged</span>
  <span m='1664910'>by</span> <span m='1665130'>beta</span> <span m='1666900'>because</span>
  <span m='1667260'>the</span> <span m='1667410'>exponent</span> <span m='1667950'>here,</span>
  <span m='1668840'>1</span> <span m='1669090'>plus</span> <span m='1669300'>beta</span>
  <span m='1669570'>k0,</span> <span m='1670260'>has</span> <span m='1670450'>the</span>
  <span m='1670530'>same</span> <span m='1670800'>form</span> <span m='1671160'>as</span>
  <span m='1671280'>the</span> <span m='1671340'>denominator</span> <span m='1671910'>here.</span>
  <span m='1672550'>So</span> <span m='1672600'>when</span> <span m='1672690'>you</span>
  <span m='1672750'>differentiate</span> <span m='1673125'>it,</span> <span m='1673500'>this</span>
  <span m='1673650'>comes</span> <span m='1673920'>down.</span> <span m='1674540'>The</span>
  <span m='1674640'>two</span> <span m='1674790'>cancel.</span> <span m='1675400'>And</span>
  <span m='1675420'>you</span> <span m='1675510'>end</span> <span m='1675660'>up</span>
  <span m='1675810'>with</span> <span m='1675930'>a</span> <span m='1675990'>slope</span>
  <span m='1676350'>that</span> <span m='1676440'>is</span> <span m='1676500'>independent</span>
  <span m='1676950'>of</span> <span m='1677090'>beta.</span> <span m='1677640'>The</span>
  <span m='1677720'>effect</span> <span m='1678030'>of</span> <span m='1678120'>that</span>
  <span m='1678360'>is</span> <span m='1678630'>that</span> <span m='1679170'>if</span>
  <span m='1679320'>you</span> <span m='1679410'>change</span> <span m='1679860'>the</span>
  <span m='1679950'>final</span> <span m='1680220'>value,</span> <span m='1680550'>it</span>
  <span m='1680610'>appears</span> <span m='1681060'>to</span> <span m='1681150'>go</span>
  <span m='1681300'>much</span> <span m='1681510'>faster.</span> </p><p><span m='1683110'>So</span>
  <span m='1683190'>pure</span> <span m='1683460'>win?</span> <span m='1683750'>No.</span>
  <span m='1685250'>Apparent</span> <span m='1685670'>win?</span> <span m='1685950'>Yes.</span>
  <span m='1687300'>We've</span> <span m='1687540'>traded</span> <span m='1688260'>gain</span>
  <span m='1689220'>for</span> <span m='1689580'>speed.</span> <span m='1691630'>OK,</span>
  <span m='1692310'>so</span> <span m='1692460'>that's</span> <span m='1692730'>ways</span>
  <span m='1693300'>that</span> <span m='1693420'>we</span> <span m='1693600'>can</span>
  <span m='1693810'>use</span> <span m='1694290'>feedback</span> <span m='1695550'>to</span>
  <span m='1695670'>improve</span> <span m='1696240'>the</span> <span m='1696390'>performance</span>
  <span m='1697230'>of</span> <span m='1697380'>an</span> <span m='1697470'>op-amp.</span>
  </p><p><span m='1698930'>OK,</span> <span m='1700180'>the</span> <span m='1700750'>big</span>
  <span m='1701020'>performance</span> <span m='1701530'>parameters</span> <span m='1702010'>that</span>
  <span m='1702130'>I</span> <span m='1702190'>talked</span> <span m='1702430'>about</span>
  <span m='1702670'>today</span> <span m='1703450'>were</span> <span m='1703630'>bandwidth</span>
  <span m='1704140'>and</span> <span m='1704260'>speed.</span> <span m='1705220'>You</span>
  <span m='1705370'>could</span> <span m='1705490'>do</span> <span m='1705640'>the</span>
  <span m='1705730'>same</span> <span m='1706030'>kind</span> <span m='1706270'>of</span>
  <span m='1706360'>analysis</span> <span m='1707170'>with</span> <span m='1707470'>many</span>
  <span m='1707860'>different</span> <span m='1708190'>kinds</span> <span m='1708550'>of</span>
  <span m='1708640'>metrics</span> <span m='1709000'>for</span> <span m='1709150'>op-amps</span>
  <span m='1709570'>like</span> <span m='1709960'>output</span> <span m='1710290'>impedance,</span>
  <span m='1710680'>input</span> <span m='1710980'>impedance,</span> <span m='1711430'>distortion</span>
  <span m='1711880'>reduction.</span> <span m='1712760'>We'll</span> <span m='1712920'>do</span>
  <span m='1713050'>distortion</span> <span m='1713620'>next</span> <span m='1713830'>time.</span>
  </p><p><span m='1715150'>|</span> <span m='1715930'>there's</span> <span m='1716470'>lots</span>
  <span m='1716800'>of</span> <span m='1716980'>other</span> <span m='1717250'>things</span>
  <span m='1717550'>that</span> <span m='1719320'>feedback</span> <span m='1719740'>improves.</span>
  <span m='1720490'>I've</span> <span m='1720690'>illustrated</span> <span m='1721300'>it</span>
  <span m='1721420'>with</span> <span m='1721600'>two.</span> <span m='1723250'>In</span>
  <span m='1723400'>both</span> <span m='1723700'>of</span> <span m='1723760'>those,</span>
  <span m='1724120'>as</span> <span m='1724270'>will</span> <span m='1724390'>be</span>
  <span m='1724510'>the</span> <span m='1724600'>case</span> <span m='1725230'>in</span>
  <span m='1725410'>all</span> <span m='1725740'>of</span> <span m='1725830'>the</span>
  <span m='1725980'>others,</span> <span m='1727000'>the</span> <span m='1727090'>effective</span>
  <span m='1727450'>feedback</span> <span m='1727930'>is</span> <span m='1728080'>to</span>
  <span m='1728380'>trade</span> <span m='1729080'>gain</span> <span m='1731430'>for</span>
  <span m='1731610'>something</span> <span m='1731910'>else</span> <span m='1732090'>of</span>
  <span m='1732210'>interest.</span> </p><p><span m='1735440'>OK,</span> <span m='1736160'>the</span>
  <span m='1736430'>next</span> <span m='1736820'>example</span> <span m='1737240'>I</span>
  <span m='1737330'>want</span> <span m='1737480'>to</span> <span m='1737540'>think</span>
  <span m='1737720'>about</span> <span m='1738440'>is</span> <span m='1738830'>thinking</span>
  <span m='1739070'>about</span> <span m='1739490'>a</span> <span m='1740810'>motor</span>
  <span m='1741080'>controller</span> <span m='1742240'>where</span> <span m='1742530'>what</span>
  <span m='1742790'>I</span> <span m='1742880'>want</span> <span m='1743030'>to</span>
  <span m='1743090'>think</span> <span m='1743240'>about</span> <span m='1743870'>is</span>
  <span m='1745790'>changing</span> <span m='1746180'>the</span> <span m='1746270'>way</span>
  <span m='1746420'>we</span> <span m='1746540'>think</span> <span m='1746720'>about</span>
  <span m='1746870'>the</span> <span m='1746960'>input-output</span> <span m='1747440'>relationship.</span>
  <span m='1750230'>So</span> <span m='1750620'>I</span> <span m='1750740'>take</span>
  <span m='1750920'>a</span> <span m='1751010'>motor.</span> <span m='1751550'>That's</span>
  <span m='1752210'>my</span> <span m='1752330'>motor.</span> <span m='1754290'>And</span>
  <span m='1754310'>what</span> <span m='1754430'>I</span> <span m='1754490'>want</span>
  <span m='1754670'>to</span> <span m='1754760'>do</span> <span m='1755150'>is</span>
  <span m='1755420'>have</span> <span m='1755660'>it</span> <span m='1755780'>control</span>
  <span m='1756410'>position.</span> </p><p><span m='1757880'>So</span> <span m='1758180'>it's</span>
  <span m='1758330'>not</span> <span m='1758480'>too</span> <span m='1758660'>easy</span>
  <span m='1758900'>to</span> <span m='1758990'>see</span> <span m='1759200'>probably</span>
  <span m='1759650'>because</span> <span m='1759920'>it's</span> <span m='1760310'>such</span>
  <span m='1760520'>a</span> <span m='1760580'>tiny</span> <span m='1760850'>little</span>
  <span m='1761030'>motor.</span> <span m='1761720'>Actually,</span> <span m='1761930'>it's</span>
  <span m='1762020'>not</span> <span m='1762140'>a</span> <span m='1762200'>tiny</span>
  <span m='1762440'>little</span> <span m='1762590'>motor.</span> <span m='1762920'>It's</span>
  <span m='1763100'>an</span> <span m='1763190'>enormous</span> <span m='1763580'>motor.</span>
  </p><p><span m='1765980'>So</span> <span m='1766160'>the</span> <span m='1766250'>red</span>
  <span m='1766430'>bar,</span> <span m='1766790'>that's</span> <span m='1767000'>the</span>
  <span m='1767090'>shaft.</span> <span m='1767600'>Right?</span> <span m='1769600'>And</span>
  <span m='1769750'>so</span> <span m='1769930'>the</span> <span m='1770050'>first</span>
  <span m='1770260'>question</span> <span m='1770590'>I</span> <span m='1770650'>want</span>
  <span m='1770810'>to</span> <span m='1770870'>think</span> <span m='1771010'>about</span>
  <span m='1771730'>is</span> <span m='1774560'>what's</span> <span m='1774890'>the</span>
  <span m='1775010'>relationship</span> <span m='1776660'>for</span> <span m='1776960'>the</span>
  <span m='1777080'>motor?</span> <span m='1780480'>What's</span> <span m='1780690'>the</span>
  <span m='1780780'>relationship</span> <span m='1781290'>for</span> <span m='1781410'>the</span>
  <span m='1781500'>motor</span> <span m='1782400'>for</span> <span m='1782610'>the</span>
  <span m='1782940'>transformation</span> <span m='1783720'>from</span> <span m='1783930'>voltage</span>
  <span m='1784530'>to</span> <span m='1785580'>angle</span> <span m='1785870'>of</span>
  <span m='1785940'>the</span> <span m='1786000'>shaft?</span> <span m='1787570'>So</span>
  <span m='1788110'>what's the</span> <span m='1788310'>relation</span> <span m='1788650'>between</span>
  <span m='1788890'>v of t</span> <span m='1789310'>and</span> <span m='1789400'>theta
  of t</span> <span m='1789780'>for</span> <span m='1790060'>DC</span> <span m='1790330'>motor?</span>
  </p><p><span m='1792340'>This</span> <span m='1792640'>is</span> <span m='1793060'>very</span>
  <span m='1793540'>much</span> <span m='1793780'>the</span> <span m='1793900'>same</span>
  <span m='1794080'>problem</span> <span m='1794440'>you</span> <span m='1794530'>worked</span>
  <span m='1794870'>in</span> <span m='1795165'>in</span> <span m='1795460'>the</span>
  <span m='1795580'>head-turning</span> <span m='1796090'>problem</span> <span m='1796630'>in</span>
  <span m='1796870'>6.01.</span> <span m='1798790'>So</span> <span m='1798880'>you</span>
  <span m='1799000'>should</span> <span m='1799090'>be</span> <span m='1799150'>able</span>
  <span m='1799270'>to</span> <span m='1799330'>remember</span> <span m='1799630'>this</span>
  <span m='1799780'>answer</span> <span m='1800020'>from</span> <span m='1800140'>6.01.</span>
  <span m='1801460'>What's</span> <span m='1801660'>the</span> <span m='1801730'>relationship</span>
  <span m='1802300'>between</span> <span m='1802690'>the</span> <span m='1802780'>voltage</span>
  <span m='1803170'>into</span> <span m='1803350'>a</span> <span m='1803410'>DC</span>
  <span m='1803680'>motor</span> <span m='1804040'>and</span> <span m='1804190'>the</span>
  <span m='1804310'>angle</span> <span m='1804790'>out?</span> <span m='1805540'>Is</span>
  <span m='1805750'>it</span> <span m='1806800'>one,</span> <span m='1807080'>two,</span>
  <span m='1807270'>three,</span> <span m='1807590'>four,</span> <span m='1808110'>or</span>
  <span m='1808390'>none</span> <span m='1808570'>of</span> <span m='1808630'>the</span>
  <span m='1808720'>above?</span> <span m='1811020'>Talk</span> <span m='1811200'>to</span>
  <span m='1811260'>your</span> <span m='1811350'>neighbor.</span> <span m='1811680'>Figure</span>
  <span m='1811890'>out</span> <span m='1811950'>the</span> <span m='1812010'>right</span>
  <span m='1812160'>answer.</span> </p><p><span m='1815923'>[SIDE CONVERSATION]</span>
  </p><p></p><p><span m='1878380'>So</span> <span m='1878470'>what's</span> <span
  m='1878600'>the</span> <span m='1878700'>answer--</span> <span m='1878990'>one,</span>
  <span m='1879180'>two,</span> <span m='1879390'>three,</span> <span m='1879660'>four,</span>
  <span m='1880050'>or</span> <span m='1880290'>none</span> <span m='1880440'>of</span>
  <span m='1880500'>the</span> <span m='1880650'>above?</span> <span m='1885210'>Everybody</span>
  <span m='1885570'>votes.</span> <span m='1887080'>You're</span> <span m='1887620'>on</span>
  <span m='1887890'>such</span> <span m='1888190'>a</span> <span m='1888250'>streak.</span>
  <span m='1889120'>More</span> <span m='1889330'>than</span> <span m='1889480'>half</span>
  <span m='1889720'>the</span> <span m='1889840'>answers,</span> <span m='1890170'>I</span>
  <span m='1890350'>really</span> <span m='1890620'>don't</span> <span m='1890800'>like.</span>
  <span m='1892690'>OK,</span> <span m='1893050'>so</span> <span m='1893200'>we'll</span>
  <span m='1893290'>do</span> <span m='1893440'>a</span> <span m='1893500'>demo,</span>
  <span m='1893860'>and</span> <span m='1893950'>we'll</span> <span m='1894040'>figure</span>
  <span m='1894280'>out.</span> </p><p><span m='1894730'>So</span> <span m='1895540'>the</span>
  <span m='1895660'>question</span> <span m='1895960'>is,</span> <span m='1896240'>what</span>
  <span m='1896560'>is</span> <span m='1896800'>the</span> <span m='1896860'>relationship</span>
  <span m='1897370'>between</span> <span m='1897760'>voltage</span> <span m='1898510'>and</span>
  <span m='1898810'>speed?</span> <span m='1899680'>So</span> <span m='1899860'>I've</span>
  <span m='1900010'>got</span> <span m='1900310'>a</span> <span m='1900370'>motor,</span>
  <span m='1900760'>and</span> <span m='1900940'>I've</span> <span m='1901030'>got</span>
  <span m='1901240'>a</span> <span m='1901330'>knob</span> <span m='1901600'>that</span>
  <span m='1901720'>controls</span> <span m='1902260'>the</span> <span m='1902470'>voltage</span>
  <span m='1903100'>that</span> <span m='1903250'>goes</span> <span m='1903550'>to</span>
  <span m='1903640'>the</span> <span m='1903730'>motor.</span> <span m='1904360'>OK,</span>
  <span m='1904600'>so</span> <span m='1904700'>now,</span> <span m='1904810'>I</span>
  <span m='1904900'>turn</span> <span m='1905050'>the</span> <span m='1905110'>motor</span>
  <span m='1905380'>on,</span> <span m='1905740'>and</span> <span m='1905830'>nothing</span>
  <span m='1906070'>happens</span> <span m='1906400'>because</span> <span m='1906940'>I</span>
  <span m='1907090'>preset</span> <span m='1907600'>the</span> <span m='1907690'>voltage</span>
  <span m='1908140'>to</span> <span m='1908260'>be</span> <span m='1908500'>0.</span>
  </p><p><span m='1910390'>Now,</span> <span m='1910720'>I turn</span> <span m='1910930'>the</span>
  <span m='1910990'>voltage</span> <span m='1911410'>to</span> <span m='1911500'>the</span>
  <span m='1911590'>right</span> <span m='1912610'>to</span> <span m='1912760'>make</span>
  <span m='1912910'>the</span> <span m='1913000'>voltage</span> <span m='1913380'>a</span>
  <span m='1913450'>bit</span> <span m='1913560'>positive,</span> <span m='1915800'>more</span>
  <span m='1915910'>positive,</span> <span m='1919560'>back</span> <span m='1919890'>towards</span>
  <span m='1920180'>0,</span> <span m='1922610'>at</span> <span m='1922910'>0,</span>
  <span m='1924710'>negative,</span> <span m='1927410'>more</span> <span m='1927590'>negative.</span>
  <span m='1928930'>OK,</span> <span m='1929390'>so</span> <span m='1929570'>what's</span>
  <span m='1929810'>the</span> <span m='1929930'>relationship</span> <span m='1930530'>between</span>
  <span m='1931580'>voltage</span> <span m='1932420'>and</span> <span m='1934040'>angle?</span>
  </p><p><span m='1935444'>AUDIENCE:</span> <span m='1935560'>Is</span> <span m='1935676'>that</span>
  <span m='1935792'>velocity</span> <span m='1935911'>or</span> <span m='1936378'>voltage?</span>
  </p><p><span m='1938250'>DENNIS FREEMAN:</span> <span m='1938432'>v</span> <span
  m='1938615'>is</span> <span m='1938980'>voltage,</span> <span m='1939550'>sorry.</span>
  <span m='1940350'>v is</span> <span m='1940780'>voltage.</span> <span m='1941360'>Theta</span>
  <span m='1941770'>is</span> <span m='1942070'>angle.</span> <span m='1943660'>So</span>
  <span m='1944080'>here's</span> <span m='1944350'>0.</span> <span m='1945220'>Here's</span>
  <span m='1945460'>90.</span> <span m='1947590'>Here's</span> <span m='1947830'>0,</span>
  <span m='1948160'>pi</span> <span m='1948490'>over</span> <span m='1948820'>2,</span>
  <span m='1949090'>pi.</span> <span m='1950110'>Right?</span> <span m='1950990'>The</span>
  <span m='1951310'>question</span> <span m='1951640'>is,</span> <span m='1951820'>what's</span>
  <span m='1952000'>the</span> <span m='1952060'>relationship</span> <span m='1952570'>between</span>
  <span m='1952900'>the</span> <span m='1952990'>voltage</span> <span m='1953410'>input</span>
  <span m='1953680'>of</span> <span m='1953740'>the</span> <span m='1953830'>motor</span>
  <span m='1954400'>and</span> <span m='1954520'>the</span> <span m='1954640'>angle</span>
  <span m='1954910'>of</span> <span m='1954970'>the</span> <span m='1955030'>shaft</span>
  <span m='1955360'>the</span> <span m='1955480'>output?</span> </p><p><span m='1958720'>And</span>
  <span m='1958870'>now,</span> <span m='1959110'>the</span> <span m='1959230'>answer</span>
  <span m='1959500'>is--</span> <span m='1962910'>OK,</span> <span m='1963690'>the</span>
  <span m='1963900'>number</span> <span m='1964230'>correct</span> <span m='1964500'>has</span>
  <span m='1964710'>not</span> <span m='1965070'>changed.</span> <span m='1969360'>So</span>
  <span m='1969510'>tell</span> <span m='1969690'>me</span> <span m='1969840'>in</span>
  <span m='1969960'>words--</span> <span m='1970410'>forget</span> <span m='1970830'>the</span>
  <span m='1971070'>one,</span> <span m='1971300'>two,</span> <span m='1971460'>three,</span>
  <span m='1971670'>four--</span> <span m='1971970'>what's</span> <span m='1972210'>the</span>
  <span m='1972300'>relationship</span> <span m='1972810'>between</span> <span m='1974430'>voltage</span>
  <span m='1975120'>and</span> <span m='1975360'>angle?</span> <span m='1982410'>What</span>
  <span m='1982560'>is</span> <span m='1982710'>[INAUDIBLE]</span> <span m='1983070'>of</span>
  <span m='1983430'>the</span> <span m='1983590'>voltage?</span> </p><p><span m='1984060'>AUDIENCE:</span>
  <span m='1984295'>[INAUDIBLE]</span> </p><p><span m='1985470'>DENNIS FREEMAN:</span>
  <span m='1985665'>Angular</span> <span m='1985860'>velocity.</span> <span m='1986550'>So</span>
  <span m='1986760'>how</span> <span m='1986880'>do</span> <span m='1986970'>I</span>
  <span m='1987030'>get</span> <span m='1987210'>angular</span> <span m='1987570'>velocity?</span>
  </p><p><span m='1990540'>AUDIENCE:</span> <span m='1990777'>[? Measure ?]</span>
  <span m='1991014'>of the angle.</span> </p><p><span m='1992436'>DENNIS FREEMAN:</span>
  <span m='1992594'>So</span> <span m='1992752'>I'm</span> <span m='1992910'>giving
  you</span> <span m='1993290'>the angle,</span> <span m='1993780'>theta of t.</span>
  <span m='1994270'>How do I get</span> <span m='1994760'>angular</span> <span m='1995250'>velocity?</span>
  </p><p><span m='1995740'>AUDIENCE:</span> <span m='1995985'>Derivative</span> <span
  m='1996230'>of the angle--</span> <span m='1997486'>the</span> <span m='1997972'>derivative.</span>
  </p><p><span m='1998944'>DENNIS FREEMAN:</span> <span m='1999106'>Take</span> <span
  m='1999268'>the</span> <span m='1999430'>derivative,</span> <span m='1999920'>yes.</span>
  <span m='2000640'>So</span> <span m='2000760'>what</span> <span m='2000860'>I</span>
  <span m='2000990'>want</span> <span m='2001360'>is</span> <span m='2001600'>that</span>
  <span m='2002290'>theta</span> <span m='2002580'>dot</span> <span m='2004450'>proportional</span>
  <span m='2005080'>to</span> <span m='2005230'>v.</span> <span m='2006780'>OK?</span>
  <span m='2008370'>Which</span> <span m='2008580'>of</span> <span m='2008670'>those</span>
  <span m='2008910'>relationships</span> <span m='2009460'>say</span> <span m='2009630'>that?</span>
  <span m='2009870'>None</span> <span m='2010050'>of</span> <span m='2010200'>them.</span>
  <span m='2011790'>OK,</span> <span m='2013020'>it</span> <span m='2013140'>was</span>
  <span m='2013230'>a</span> <span m='2013290'>trick</span> <span m='2013470'>question</span>
  <span m='2013950'>of</span> <span m='2014010'>course.</span> </p><p><span m='2016020'>So</span>
  <span m='2016200'>what</span> <span m='2016350'>do</span> <span m='2016440'>I</span>
  <span m='2016560'>want</span> <span m='2016740'>to</span> <span m='2016980'>have</span>
  <span m='2017430'>as</span> <span m='2017610'>my</span> <span m='2017820'>model</span>
  <span m='2018630'>for</span> <span m='2018810'>the</span> <span m='2018900'>DC</span>
  <span m='2019230'>motor?</span> <span m='2020970'>I</span> <span m='2021090'>want</span>
  <span m='2021300'>my</span> <span m='2021480'>model</span> <span m='2022290'>to</span>
  <span m='2022440'>take</span> <span m='2023610'>a</span> <span m='2024090'>voltage</span>
  <span m='2024660'>in</span> <span m='2025770'>and</span> <span m='2025920'>give</span>
  <span m='2026190'>me</span> <span m='2026660'>theta</span> <span m='2027210'>out.</span>
  <span m='2028290'>What</span> <span m='2028530'>should</span> <span m='2028740'>be</span>
  <span m='2029010'>in</span> <span m='2029160'>the</span> <span m='2029250'>model?</span>
  <span m='2037090'>k,</span> <span m='2037820'>it's</span> <span m='2038000'>always</span>
  <span m='2038330'>good</span> <span m='2038480'>to</span> <span m='2038570'>throw</span>
  <span m='2038780'>a</span> <span m='2038810'>k</span> <span m='2039095'>in.</span>
  <span m='2039380'>That</span> <span m='2039530'>always</span> <span m='2039830'>works.</span>
  <span m='2042410'>Excellent</span> <span m='2042800'>answer.</span> <span m='2045070'>k</span>
  <span m='2045260'>always</span> <span m='2045530'>works,</span> <span m='2045770'>sure.</span>
  <span m='2046750'>In</span> <span m='2046910'>any</span> <span m='2047090'>physical</span>
  <span m='2047450'>system,</span> <span m='2047780'>you</span> <span m='2047840'>never</span>
  <span m='2048050'>get</span> <span m='2048170'>one,</span> <span m='2048560'>right?</span>
  <span m='2049460'>Yeah.</span> </p><p><span m='2050135'>AUDIENCE:</span> <span m='2050367'>[INAUDIBLE]</span>
  </p><p><span m='2052460'>DENNIS FREEMAN:</span> <span m='2052565'>You're</span>
  <span m='2052670'>going</span> <span m='2052820'>to</span> <span m='2052880'>need</span>
  <span m='2053060'>an</span> <span m='2053150'>integrator,</span> <span m='2053659'>exactly</span>
  <span m='2054080'>right.</span> <span m='2054989'>So</span> <span m='2055010'>it's</span>
  <span m='2055100'>going</span> <span m='2055250'>to</span> <span m='2055310'>need</span>
  <span m='2055460'>something</span> <span m='2055850'>like</span> <span m='2056060'>I</span>
  <span m='2056120'>think</span> <span m='2056270'>I</span> <span m='2056360'>call
  it</span> <span m='2056510'>a</span> <span m='2056570'>gamma,</span> <span m='2058699'>a</span>
  <span m='2059030'>being</span> <span m='2059389'>the</span> <span m='2059750'>accumulator</span>
  <span m='2060350'>guy.</span> <span m='2060800'>Right?</span> <span m='2061549'>A</span>
  <span m='2061969'>different</span> <span m='2062239'>way</span> <span m='2062389'>of</span>
  <span m='2062480'>saying</span> <span m='2062780'>that</span> <span m='2063020'>would</span>
  <span m='2063199'>be--</span> <span m='2064239'>or</span> <span m='2064370'>I</span>
  <span m='2064460'>write</span> <span m='2064699'>it</span> <span m='2064850'>in</span>
  <span m='2065000'>terms</span> <span m='2065239'>of</span> <span m='2065360'>Laplace</span>
  <span m='2065719'>transforms,</span> <span m='2066350'>I</span> <span m='2066469'>would</span>
  <span m='2066590'>get</span> <span m='2066949'>gamma</span> <span m='2067370'>over</span>
  <span m='2067730'>s.</span> <span m='2069130'>So</span> <span m='2069260'>if</span>
  <span m='2069380'>I</span> <span m='2069440'>put</span> <span m='2070159'>v</span>
  <span m='2070520'>in,</span> <span m='2070670'>and</span> <span m='2070790'>I</span>
  <span m='2070850'>want</span> <span m='2071000'>to</span> <span m='2071060'>get</span>
  <span m='2071219'>theta</span> <span m='2071570'>out,</span> <span m='2077710'>right,</span>
  <span m='2077980'>I</span> <span m='2078070'>need</span> <span m='2078250'>to</span>
  <span m='2078370'>put</span> <span m='2078580'>it</span> <span m='2078639'>through</span>
  <span m='2078820'>an</span> <span m='2078909'>integrator.</span> </p><p><span m='2082540'>So</span>
  <span m='2082690'>the</span> <span m='2082810'>idea</span> <span m='2083230'>is</span>
  <span m='2083590'>that</span> <span m='2084610'>if</span> <span m='2084760'>I</span>
  <span m='2084880'>put</span> <span m='2085270'>a</span> <span m='2085360'>constant</span>
  <span m='2085960'>voltage</span> <span m='2086500'>in--</span> <span m='2086739'>say</span>
  <span m='2086949'>the</span> <span m='2087040'>voltage is</span> <span m='2087520'>0--</span>
  <span m='2088370'>theta</span> <span m='2088690'>was</span> <span m='2088870'>flat.</span>
  <span m='2090000'>But</span> <span m='2090040'>if</span> <span m='2090130'>I</span>
  <span m='2090250'>put</span> <span m='2090520'>a</span> <span m='2090580'>voltage</span>
  <span m='2091090'>at</span> <span m='2091270'>the</span> <span m='2091420'>blue</span>
  <span m='2091659'>line,</span> <span m='2092770'>theta</span> <span m='2093280'>increased</span>
  <span m='2093880'>at</span> <span m='2094000'>some</span> <span m='2094270'>rate.</span>
  <span m='2094820'>And</span> <span m='2094870'>if</span> <span m='2094960'>I</span>
  <span m='2095050'>changed</span> <span m='2095360'>it</span> <span m='2095469'>to</span>
  <span m='2095560'>red,</span> <span m='2095830'>it</span> <span m='2095920'>increased</span>
  <span m='2096340'>faster</span> <span m='2096880'>just</span> <span m='2097150'>like</span>
  <span m='2097570'>an</span> <span m='2097750'>integrator</span> <span m='2098200'>would</span>
  <span m='2098320'>do.</span> <span m='2099010'>So</span> <span m='2099190'>what</span>
  <span m='2099340'>I</span> <span m='2099400'>want</span> <span m='2099580'>to</span>
  <span m='2099640'>do</span> <span m='2100180'>is</span> <span m='2100390'>think</span>
  <span m='2100570'>about</span> <span m='2100840'>the</span> <span m='2100960'>motor</span>
  <span m='2101380'>being</span> <span m='2101680'>an</span> <span m='2101770'>integrator.</span>
  </p><p><span m='2103310'>OK,</span> <span m='2104080'>that</span> <span m='2104320'>lets</span>
  <span m='2104530'>me</span> <span m='2104650'>then</span> <span m='2104860'>cast</span>
  <span m='2105220'>the</span> <span m='2105310'>motor,</span> <span m='2106490'>which</span>
  <span m='2106570'>is</span> <span m='2106660'>a</span> <span m='2106720'>physical</span>
  <span m='2107170'>thing,</span> <span m='2107530'>into</span> <span m='2107680'>6.003</span>
  <span m='2108460'>terms</span> <span m='2108750'>again.</span> <span m='2110660'>So</span>
  <span m='2110780'>now,</span> <span m='2110990'>I</span> <span m='2111080'>can</span>
  <span m='2111230'>think</span> <span m='2111410'>about</span> <span m='2111590'>the</span>
  <span m='2111680'>problem.</span> <span m='2112100'>I'd</span> <span m='2112230'>really</span>
  <span m='2112610'>like</span> <span m='2112820'>it</span> <span m='2112910'>not</span>
  <span m='2113180'>to</span> <span m='2113330'>be</span> <span m='2114260'>a</span>
  <span m='2114320'>speed</span> <span m='2114710'>controller.</span> <span m='2115250'>I'd</span>
  <span m='2115370'>really</span> <span m='2115610'>like</span> <span m='2115820'>it</span>
  <span m='2115900'>to</span> <span m='2116030'>be</span> <span m='2116150'>a</span>
  <span m='2116210'>position</span> <span m='2116690'>controller.</span> </p><p><span
  m='2118740'>So</span> <span m='2120350'>feedback</span> <span m='2120770'>to</span>
  <span m='2120860'>the</span> <span m='2120950'>rescue--</span> <span m='2121760'>what</span>
  <span m='2121940'>I'll</span> <span m='2122030'>do</span> <span m='2122210'>is</span>
  <span m='2122300'>I'll</span> <span m='2122420'>put</span> <span m='2122600'>it</span>
  <span m='2122690'>in</span> <span m='2122810'>a</span> <span m='2122870'>loop.</span>
  <span m='2125450'>So</span> <span m='2125560'>the</span> <span m='2125680'>idea</span>
  <span m='2125950'>is</span> <span m='2126040'>going</span> <span m='2126190'>to</span>
  <span m='2126250'>be</span> <span m='2126370'>that</span> <span m='2126520'>I</span>
  <span m='2126610'>take</span> <span m='2126820'>my</span> <span m='2126970'>motor,</span>
  <span m='2127810'>which</span> <span m='2127990'>looks</span> <span m='2128200'>like</span>
  <span m='2128380'>an</span> <span m='2128470'>integrator,</span> <span m='2129520'>gamma</span>
  <span m='2129890'>a,</span> <span m='2131710'>feedback</span> <span m='2132340'>a</span>
  <span m='2132400'>signal</span> <span m='2132790'>that's</span> <span m='2132970'>proportional</span>
  <span m='2133570'>to</span> <span m='2133780'>the</span> <span m='2134050'>angle,</span>
  <span m='2135550'>which</span> <span m='2135760'>I</span> <span m='2135880'>derive</span>
  <span m='2137740'>by</span> <span m='2137920'>having</span> <span m='2138610'>a</span>
  <span m='2138910'>potentiometer</span> <span m='2139960'>strapped</span> <span m='2140290'>to</span>
  <span m='2140380'>the</span> <span m='2140470'>back</span> <span m='2140650'>of</span>
  <span m='2140710'>the</span> <span m='2140770'>shaft--</span> <span m='2142810'>so</span>
  <span m='2142990'>there's</span> <span m='2143170'>a</span> <span m='2143200'>pot.</span>
  <span m='2143590'>I've</span> <span m='2143880'>taken</span> <span m='2144220'>off</span>
  <span m='2144610'>the</span> <span m='2144680'>little</span> <span m='2144910'>stop</span>
  <span m='2145420'>so</span> <span m='2145660'>that</span> <span m='2145870'>it</span>
  <span m='2146260'>spins</span> <span m='2146590'>around</span> <span m='2146960'>doesn't</span>
  <span m='2147220'>hit</span> <span m='2147340'>the</span> <span m='2147430'>stop.</span>
  <span m='2147760'>Right?</span> <span m='2148090'>Otherwise,</span> <span m='2148430'>it</span>
  <span m='2148470'>would</span> <span m='2148560'>be</span> <span m='2148630'>kind</span>
  <span m='2148780'>of</span> <span m='2148840'>bad</span> <span m='2149020'>for</span>
  <span m='2149110'>the</span> <span m='2149200'>first</span> <span m='2149380'>part</span>
  <span m='2149530'>of</span> <span m='2149590'>the</span> <span m='2149650'>demo.</span>
  </p><p><span m='2151450'>So</span> <span m='2151750'>it's</span> <span m='2151900'>a</span>
  <span m='2152110'>surgically</span> <span m='2152710'>altered</span> <span m='2153190'>potentiometer</span>
  <span m='2153940'>that</span> <span m='2154060'>spins</span> <span m='2154330'>around</span>
  <span m='2154570'>forever.</span> <span m='2155860'>But</span> <span m='2156040'>over</span>
  <span m='2156250'>most</span> <span m='2156550'>of</span> <span m='2156610'>the</span>
  <span m='2156700'>range,</span> <span m='2157000'>it's</span> <span m='2157090'>reporting</span>
  <span m='2157570'>angle.</span> <span m='2159710'>So</span> <span m='2159830'>that's</span>
  <span m='2160070'>the</span> <span m='2160160'>way</span> <span m='2160370'>I</span>
  <span m='2160470'>get</span> <span m='2161030'>this</span> <span m='2161210'>feedback</span>
  <span m='2161660'>loop</span> <span m='2161900'>in.</span> </p><p><span m='2162830'>And</span>
  <span m='2162980'>then</span> <span m='2163160'>I</span> <span m='2163250'>put</span>
  <span m='2163460'>it</span> <span m='2163530'>into</span> <span m='2164270'>this</span>
  <span m='2164540'>thing,</span> <span m='2165200'>which</span> <span m='2165380'>is</span>
  <span m='2165470'>really</span> <span m='2165740'>just</span> <span m='2165920'>a</span>
  <span m='2165990'>741</span> <span m='2167690'>wired</span> <span m='2167990'>up</span>
  <span m='2168110'>like</span> <span m='2168320'>I</span> <span m='2168410'>showed</span>
  <span m='2168770'>in</span> <span m='2168830'>the</span> <span m='2168920'>first</span>
  <span m='2169130'>example,</span> <span m='2170250'>so</span> <span m='2170400'>that</span>
  <span m='2170540'>it</span> <span m='2170630'>would</span> <span m='2170780'>take</span>
  <span m='2170990'>the</span> <span m='2171110'>difference</span> <span m='2171470'>between</span>
  <span m='2171800'>two</span> <span m='2171980'>things,</span> <span m='2173020'>the</span>
  <span m='2173120'>desired</span> <span m='2173690'>input,</span> <span m='2174180'>which</span>
  <span m='2174260'>is</span> <span m='2174470'>a</span> <span m='2175370'>potentiometer</span>
  <span m='2176000'>that</span> <span m='2176150'>I'm</span> <span m='2176240'>turning</span>
  <span m='2176570'>here,</span> <span m='2178710'>and</span> <span m='2179130'>the</span>
  <span m='2180270'>actual</span> <span m='2180720'>position,</span> <span m='2181390'>which</span>
  <span m='2181560'>is</span> <span m='2181680'>the</span> <span m='2181770'>potentiometer</span>
  <span m='2182400'>up here,</span> <span m='2182890'>the same</span> <span m='2183060'>kind</span>
  <span m='2183330'>of</span> <span m='2183420'>potentiometer,</span> <span m='2184050'>just</span>
  <span m='2184230'>one</span> <span m='2184440'>that</span> <span m='2184530'>I</span>
  <span m='2184620'>turn,</span> <span m='2184890'>the</span> <span m='2184980'>other
  that the</span> <span m='2185250'>motor</span> <span m='2185520'>turns.</span> <span
  m='2186930'>And</span> <span m='2187230'>the</span> <span m='2187470'>op-amp</span>
  <span m='2188430'>figures</span> <span m='2188790'>out</span> <span m='2188970'>the</span>
  <span m='2189060'>difference,</span> <span m='2189420'>multiplies</span> <span m='2189950'>it</span>
  <span m='2190050'>by</span> <span m='2190240'>a gain,</span> <span m='2190650'>alpha,</span>
  <span m='2191780'>and</span> <span m='2191910'>presents</span> <span m='2192300'>it</span>
  <span m='2192360'>to</span> <span m='2192480'>the</span> <span m='2192570'>motor.</span>
  <span m='2192870'>That's</span> <span m='2193020'>the</span> <span m='2193140'>idea.</span>
  </p><p><span m='2195300'>And</span> <span m='2195630'>if</span> <span m='2195720'>you</span>
  <span m='2195810'>just</span> <span m='2195960'>think</span> <span m='2196140'>about</span>
  <span m='2196260'>003,</span> <span m='2197460'>it's</span> <span m='2197640'>pretty</span>
  <span m='2197910'>easy</span> <span m='2198270'>to</span> <span m='2198390'>see</span>
  <span m='2198780'>that</span> <span m='2199380'>you</span> <span m='2199740'>can</span>
  <span m='2199860'>represent</span> <span m='2200340'>this</span> <span m='2200670'>relationship</span>
  <span m='2201570'>by</span> <span m='2202080'>a</span> <span m='2202320'>single</span>
  <span m='2202830'>pole.</span> <span m='2203940'>Right,</span> <span m='2204160'>there's</span>
  <span m='2204300'>some</span> <span m='2204450'>annoying</span> <span m='2204870'>constants.</span>
  <span m='2206070'>Right,</span> <span m='2206370'>you</span> <span m='2206430'>have</span>
  <span m='2206520'>to</span> <span m='2206580'>worry</span> <span m='2206730'>about</span>
  <span m='2206910'>the</span> <span m='2207000'>gain</span> <span m='2207180'>of</span>
  <span m='2207240'>the</span> <span m='2207330'>amplifier,</span> <span m='2207830'>the</span>
  <span m='2207930'>gain of the</span> <span m='2208140'>motor,</span> <span m='2208830'>and</span>
  <span m='2209190'>how</span> <span m='2209370'>much</span> <span m='2209610'>feedback.</span>
  <span m='2210160'>That's</span> <span m='2210390'>alpha,</span> <span m='2210730'>beta,</span>
  <span m='2210910'>gamma.</span> <span m='2211950'>But</span> <span m='2212100'>pretty</span>
  <span m='2212370'>much,</span> <span m='2212700'>it's</span> <span m='2212880'>just</span>
  <span m='2213240'>a</span> <span m='2213390'>pole.</span> </p><p><span m='2215960'>So</span>
  <span m='2216730'>what</span> <span m='2216910'>happens</span> <span m='2217330'>then</span>
  <span m='2217660'>as</span> <span m='2217810'>you</span> <span m='2217930'>change</span>
  <span m='2218320'>the</span> <span m='2218500'>gain?</span> <span m='2220890'>Well,</span>
  <span m='2221180'>if</span> <span m='2221510'>the</span> <span m='2221670'>gain</span>
  <span m='2221940'>is</span> <span m='2222090'>0,</span> <span m='2223020'>the</span>
  <span m='2223140'>pole--</span> <span m='2223930'>so</span> <span m='2223980'>if</span>
  <span m='2224130'>the</span> <span m='2224220'>gain,</span> <span m='2224580'>beta,</span>
  <span m='2225320'>is</span> <span m='2225450'>0,</span> <span m='2226650'>the</span>
  <span m='2226740'>pole</span> <span m='2227160'>is</span> <span m='2227400'>at</span>
  <span m='2229630'>0.</span> <span m='2231060'>OK,</span> <span m='2231310'>it</span>
  <span m='2231380'>works</span> <span m='2231710'>just</span> <span m='2231980'>like</span>
  <span m='2232130'>an</span> <span m='2232220'>integrator.</span> <span m='2235380'>That's</span>
  <span m='2235590'>what</span> <span m='2235700'>we</span> <span m='2235800'>said</span>
  <span m='2235950'>before.</span> <span m='2237190'>That's</span> <span m='2237270'>a</span>
  <span m='2237330'>sanity</span> <span m='2237750'>check</span> <span m='2238470'>where</span>
  <span m='2238590'>you</span> <span m='2238710'>check</span> <span m='2238860'>something</span>
  <span m='2239160'>you</span> <span m='2239220'>already</span> <span m='2239460'>know</span>
  <span m='2239580'>the</span> <span m='2239670'>answer</span> <span m='2239880'>to.</span>
  <span m='2240220'>Right?</span> </p><p><span m='2241320'>So</span> <span m='2241770'>if</span>
  <span m='2241920'>you</span> <span m='2242040'>set</span> <span m='2242420'>beta</span>
  <span m='2242590'>to</span> <span m='2242700'>0,</span> <span m='2243150'>you</span>
  <span m='2243330'>get</span> <span m='2243570'>that</span> <span m='2243840'>the</span>
  <span m='2244050'>transformation</span> <span m='2244740'>is</span> <span m='2244830'>an</span>
  <span m='2244950'>integrator,</span> <span m='2245370'>good.</span> <span m='2246630'>If</span>
  <span m='2246750'>you</span> <span m='2246840'>set</span> <span m='2247020'>beta</span>
  <span m='2247350'>and</span> <span m='2247620'>anything</span> <span m='2248160'>else,</span>
  <span m='2248550'>what</span> <span m='2248760'>happens?</span> <span m='2249620'>Well,</span>
  <span m='2249870'>the</span> <span m='2249990'>pole</span> <span m='2250320'>goes</span>
  <span m='2250530'>screaming</span> <span m='2250920'>out</span> <span m='2251040'>that</span>
  <span m='2251190'>way.</span> <span m='2253140'>That's</span> <span m='2253380'>good,</span>
  <span m='2253650'>right?</span> </p><p><span m='2253950'>Remember</span> <span m='2255150'>good</span>
  <span m='2255600'>is</span> <span m='2255840'>that</span> <span m='2256020'>way.</span>
  <span m='2257250'>Right?</span> <span m='2258120'>That's</span> <span m='2258300'>not</span>
  <span m='2258450'>always</span> <span m='2258810'>true.</span> <span m='2259550'>But</span>
  <span m='2259710'>when</span> <span m='2259830'>you're</span> <span m='2259920'>trying</span>
  <span m='2260190'>to</span> <span m='2260250'>make</span> <span m='2260370'>something</span>
  <span m='2260700'>work</span> <span m='2260940'>fast,</span> <span m='2262080'>that's</span>
  <span m='2262410'>the</span> <span m='2262530'>rule.</span> <span m='2262990'>Right?</span>
  <span m='2263620'>Fast</span> <span m='2264210'>is</span> <span m='2264390'>over</span>
  <span m='2264570'>there.</span> </p><p><span m='2266380'>So</span> <span m='2268020'>the</span>
  <span m='2268170'>idea</span> <span m='2268470'>then</span> <span m='2269250'>would</span>
  <span m='2269430'>be</span> <span m='2269610'>that</span> <span m='2269790'>if</span>
  <span m='2269910'>I</span> <span m='2270060'>hook</span> <span m='2270330'>up</span>
  <span m='2270480'>this</span> <span m='2270620'>circuit--</span> <span m='2273070'>right,</span>
  <span m='2273310'>I</span> <span m='2273400'>take</span> <span m='2273580'>the</span>
  <span m='2273700'>feedback,</span> <span m='2274160'>run it</span> <span m='2274360'>into</span>
  <span m='2274570'>an</span> <span m='2274640'>op-amp</span> <span m='2274810'>and</span>
  <span m='2275020'>multiply</span> <span m='2275410'>it,</span> <span m='2275800'>use</span>
  <span m='2276040'>that</span> <span m='2276280'>to</span> <span m='2276370'>control</span>
  <span m='2276670'>the</span> <span m='2276760'>motor</span> <span m='2277030'>instead</span>
  <span m='2277390'>of</span> <span m='2277570'>my</span> <span m='2278110'>turning</span>
  <span m='2278500'>the</span> <span m='2278620'>knob,</span> <span m='2279580'>then</span>
  <span m='2279790'>this</span> <span m='2280000'>thing</span> <span m='2280210'>should</span>
  <span m='2280750'>have</span> <span m='2280990'>the</span> <span m='2281080'>behavior</span>
  <span m='2282400'>that</span> <span m='2283360'>the</span> <span m='2283480'>pole</span>
  <span m='2284710'>goes</span> <span m='2285040'>from</span> <span m='2285160'>the</span>
  <span m='2285250'>origin</span> <span m='2285730'>to</span> <span m='2285820'>the</span>
  <span m='2285910'>right.</span> <span m='2287680'>So</span> <span m='2287850'>the</span>
  <span m='2287940'>question</span> <span m='2288360'>is,</span> <span m='2289650'>if</span>
  <span m='2290010'>that</span> <span m='2290190'>happened,</span> <span m='2291030'>what</span>
  <span m='2291240'>would</span> <span m='2291360'>happen?</span> </p><p><span m='2292230'>OK,</span>
  <span m='2292500'>just</span> <span m='2292770'>doing</span> <span m='2293040'>the</span>
  <span m='2293130'>same</span> <span m='2293610'>kind</span> <span m='2293820'>of</span>
  <span m='2293880'>analysis</span> <span m='2294420'>we</span> <span m='2294570'>did</span>
  <span m='2294780'>for</span> <span m='2294960'>the</span> <span m='2295110'>op-amp,</span>
  <span m='2298040'>the</span> <span m='2298140'>step</span> <span m='2298410'>response</span>
  <span m='2298920'>goes</span> <span m='2299280'>from</span> <span m='2299490'>being</span>
  <span m='2299910'>the</span> <span m='2300090'>response</span> <span m='2300385'>of
  a</span> <span m='2300680'>pole,</span> <span m='2301260'>which</span> <span m='2301470'>is</span>
  <span m='2301560'>an</span> <span m='2301680'>integrator,</span> <span m='2303810'>to</span>
  <span m='2304000'>being</span> <span m='2304510'>this</span> <span m='2304750'>kind</span>
  <span m='2305050'>of</span> <span m='2305140'>a</span> <span m='2305200'>response,</span>
  <span m='2306820'>which</span> <span m='2307030'>has</span> <span m='2307180'>a</span>
  <span m='2307240'>final</span> <span m='2307540'>value.</span> <span m='2309890'>That</span>
  <span m='2310130'>converts</span> <span m='2310700'>it</span> <span m='2310850'>from</span>
  <span m='2311060'>being</span> <span m='2311540'>voltage</span> <span m='2312710'>to</span>
  <span m='2312920'>velocity</span> <span m='2314180'>into</span> <span m='2314480'>voltage</span>
  <span m='2315290'>to</span> <span m='2315520'>angle.</span> <span m='2316790'>Does</span>
  <span m='2317210'>that</span> <span m='2317350'>make</span> <span m='2317500'>sense?</span>
  </p><p><span m='2318940'>It</span> <span m='2319150'>used</span> <span m='2319360'>to</span>
  <span m='2320050'>when</span> <span m='2320950'>the</span> <span m='2321670'>feedback</span>
  <span m='2322180'>was</span> <span m='2322330'>0,</span> <span m='2323950'>the</span>
  <span m='2324070'>pole</span> <span m='2324370'>was</span> <span m='2324610'>at</span>
  <span m='2324880'>0.</span> <span m='2325480'>So</span> <span m='2325690'>the</span>
  <span m='2325840'>output</span> <span m='2326260'>continuously</span> <span m='2326980'>rose.</span>
  <span m='2329070'>There</span> <span m='2329190'>was</span> <span m='2329370'>no</span>
  <span m='2329580'>steady-state</span> <span m='2330570'>position.</span> </p><p><span
  m='2332070'>But</span> <span m='2332220'>now</span> <span m='2332460'>with</span>
  <span m='2332700'>feedback,</span> <span m='2333630'>I</span> <span m='2333720'>get</span>
  <span m='2334080'>a</span> <span m='2334140'>step</span> <span m='2334410'>response</span>
  <span m='2335460'>that</span> <span m='2335580'>has</span> <span m='2335730'>a</span>
  <span m='2335790'>final</span> <span m='2336090'>value.</span> <span m='2338130'>The</span>
  <span m='2338250'>effect</span> <span m='2338550'>of</span> <span m='2338700'>moving</span>
  <span m='2339000'>the</span> <span m='2339090'>pole</span> <span m='2339600'>is</span>
  <span m='2339750'>the</span> <span m='2339870'>same</span> <span m='2340140'>as</span>
  <span m='2340260'>the</span> <span m='2340350'>effect</span> <span m='2340530'>of</span>
  <span m='2340740'>moving</span> <span m='2341040'>the</span> <span m='2341130'>pole.</span>
  <span m='2342590'>In</span> <span m='2342750'>the</span> <span m='2342840'>op-amp</span>
  <span m='2343230'>example,</span> <span m='2344400'>I</span> <span m='2344520'>get</span>
  <span m='2344760'>a</span> <span m='2344820'>step</span> <span m='2345180'>response</span>
  <span m='2345750'>that</span> <span m='2345960'>becomes</span> <span m='2346590'>increasingly</span>
  <span m='2347880'>like</span> <span m='2348360'>a</span> <span m='2348420'>step.</span>
  <span m='2350450'>It</span> <span m='2350570'>goes</span> <span m='2350810'>from</span>
  <span m='2350930'>being</span> <span m='2351140'>a</span> <span m='2351200'>sluggish</span>
  <span m='2351750'>step</span> <span m='2352430'>to</span> <span m='2352580'>a</span>
  <span m='2352610'>fast</span> <span m='2352940'>step.</span> </p><p><span m='2353840'>OK,</span>
  <span m='2354890'>so</span> <span m='2355190'>that's</span> <span m='2355400'>the</span>
  <span m='2355520'>way</span> <span m='2355730'>I</span> <span m='2355850'>use</span>
  <span m='2356260'>003</span> <span m='2356960'>to</span> <span m='2357110'>use</span>
  <span m='2357380'>feedback</span> <span m='2357920'>to</span> <span m='2358220'>fix</span>
  <span m='2358520'>the</span> <span m='2358640'>motor.</span> <span m='2359360'>And</span>
  <span m='2359510'>I've</span> <span m='2359630'>done</span> <span m='2359840'>that.</span>
  <span m='2361280'>So</span> <span m='2361400'>I</span> <span m='2361460'>have</span>
  <span m='2361550'>to</span> <span m='2361670'>move</span> <span m='2362150'>the</span>
  <span m='2363080'>input</span> <span m='2363740'>to</span> <span m='2363890'>the</span>
  <span m='2364100'>amplifier</span> <span m='2364910'>from</span> <span m='2365360'>my</span>
  <span m='2365660'>pot</span> <span m='2366650'>to</span> <span m='2367190'>the</span>
  <span m='2367500'>op-amp,</span> <span m='2370060'>which</span> <span m='2370450'>is</span>
  <span m='2370820'>there</span> <span m='2374420'>hopefully.</span> <span m='2376410'>So</span>
  <span m='2376430'>now</span> <span m='2376880'>when</span> <span m='2377030'>I</span>
  <span m='2377090'>turn</span> <span m='2377260'>it</span> <span m='2377360'>on,</span>
  <span m='2379750'>it</span> <span m='2379870'>becomes</span> <span m='2380410'>a</span>
  <span m='2380590'>position.</span> </p><p><span m='2382120'>OK,</span> <span m='2382750'>and</span>
  <span m='2382900'>I</span> <span m='2382990'>can</span> <span m='2383140'>test</span>
  <span m='2383380'>that</span> <span m='2383860'>by</span> <span m='2384010'>turning</span>
  <span m='2384430'>the</span> <span m='2384520'>pot.</span> <span m='2385390'>And</span>
  <span m='2385660'>in</span> <span m='2385780'>fact,</span> <span m='2386380'>when</span>
  <span m='2386620'>I</span> <span m='2386830'>turn</span> <span m='2387040'>the</span>
  <span m='2387130'>pot,</span> <span m='2387880'>the</span> <span m='2387970'>motor</span>
  <span m='2388450'>moves.</span> <span m='2389200'>Wonderful,</span> <span m='2389600'>voila,</span>
  <span m='2390130'>I</span> <span m='2390250'>won.</span> <span m='2390500'>Right?</span>
  <span m='2390880'>Great.</span> <span m='2391410'>Yes,</span> <span m='2391960'>applause</span>
  <span m='2392530'>please.</span> <span m='2393300'>Come</span> <span m='2393600'>on.</span>
  </p><p><span m='2393900'>[APPLAUSE]</span> </p><p><span m='2394510'>Exactly,</span>
  <span m='2395260'>exactly.</span> <span m='2396850'>OK,</span> <span m='2397190'>well,</span>
  <span m='2397330'>it's</span> <span m='2397420'>pretty</span> <span m='2397630'>wimpy</span>
  <span m='2397900'>actually</span> <span m='2400000'>because</span> <span m='2400360'>I've</span>
  <span m='2400450'>got</span> <span m='2400600'>this</span> <span m='2400750'>motor</span>
  <span m='2401110'>that</span> <span m='2401230'>weighs</span> <span m='2401560'>about,</span>
  <span m='2402130'>I</span> <span m='2402190'>don't</span> <span m='2402280'>know,</span>
  <span m='2402520'>three</span> <span m='2402760'>pounds.</span> <span m='2403600'>And</span>
  <span m='2404470'>it's</span> <span m='2404680'>exerting</span> <span m='2405160'>about</span>
  <span m='2406330'>a</span> <span m='2406390'>quarter</span> <span m='2406720'>of</span>
  <span m='2406810'>an</span> <span m='2406900'>ounce</span> <span m='2407230'>of</span>
  <span m='2407440'>torque.</span> <span m='2408460'>It's</span> <span m='2408610'>not</span>
  <span m='2408820'>really</span> <span m='2409090'>very</span> <span m='2409240'>impressive.</span>
  <span m='2410460'>So</span> <span m='2410500'>how</span> <span m='2410620'>do</span>
  <span m='2410710'>I</span> <span m='2410770'>fix</span> <span m='2410980'>it?</span>
  <span m='2415340'>What</span> <span m='2415460'>do</span> <span m='2415520'>I</span>
  <span m='2415580'>do?</span> <span m='2416090'>How</span> <span m='2416180'>do</span>
  <span m='2416270'>I</span> <span m='2416360'>fix</span> <span m='2416540'>it?</span>
  </p><p><span m='2417990'>I</span> <span m='2418090'>have</span> <span m='2418100'>a</span>
  <span m='2418160'>wimpy</span> <span m='2418610'>controller.</span> <span m='2419500'>Yes.</span>
  </p><p><span m='2420030'>AUDIENCE:</span> <span m='2420160'>More</span> <span m='2420290'>gain.</span>
  </p><p><span m='2420810'>DENNIS FREEMAN:</span> <span m='2420995'>More gain,</span>
  <span m='2421550'>of</span> <span m='2421670'>course.</span> <span m='2422870'>So</span>
  <span m='2424280'>remember</span> <span m='2424580'>that</span> <span m='2424730'>response.</span>
  <span m='2426660'>So</span> <span m='2426760'>now,</span> <span m='2426860'>I</span>
  <span m='2427010'>turn</span> <span m='2427190'>off</span> <span m='2427340'>the</span>
  <span m='2427430'>motor</span> <span m='2427730'>and</span> <span m='2428390'>increase</span>
  <span m='2428750'>the</span> <span m='2428840'>gain</span> <span m='2429020'>by</span>
  <span m='2429170'>a</span> <span m='2429200'>factor</span> <span m='2429440'>of</span>
  <span m='2429520'>three.</span> <span m='2431100'>And</span> <span m='2431190'>the</span>
  <span m='2431250'>answer</span> <span m='2431520'>is</span> <span m='2433290'>much</span>
  <span m='2433680'>better,</span> <span m='2435740'>well,</span> <span m='2436070'>maybe.</span>
  </p><p><span m='2438440'>So</span> <span m='2438620'>what</span> <span m='2438710'>do</span>
  <span m='2438770'>I</span> <span m='2438830'>do?</span> <span m='2441170'>More gain,</span>
  <span m='2441920'>of</span> <span m='2442040'>course.</span> <span m='2442860'>So</span>
  <span m='2443150'>another</span> <span m='2443510'>factor</span> <span m='2443810'>of</span>
  <span m='2443880'>three--</span> <span m='2446060'>much</span> <span m='2446450'>better,</span>
  <span m='2448110'>well,</span> <span m='2448560'>maybe.</span> <span m='2451340'>So</span>
  <span m='2451500'>another</span> <span m='2451950'>factor</span> <span m='2452280'>of</span>
  <span m='2452350'>three.</span> <span m='2456030'>OK,</span> <span m='2456980'>another</span>
  <span m='2457310'>factor</span> <span m='2457570'>of</span> <span m='2457670'>three.</span>
  <span m='2462150'>Hmm,</span> <span m='2462960'>another</span> <span m='2463350'>factor</span>
  <span m='2463660'>of</span> <span m='2463730'>three.</span> </p><p><span m='2468150'>Some</span>
  <span m='2468390'>of</span> <span m='2468510'>you</span> <span m='2468660'>close</span>
  <span m='2469110'>may</span> <span m='2469350'>hear</span> <span m='2469650'>that</span>
  <span m='2469800'>there's</span> <span m='2469950'>a</span> <span m='2469980'>little</span>
  <span m='2470130'>buzzing</span> <span m='2470580'>sound</span> <span m='2470940'>now.</span>
  <span m='2471420'>I</span> <span m='2471540'>can</span> <span m='2471720'>hear</span>
  <span m='2471930'>it.</span> <span m='2472290'>That's</span> <span m='2472500'>the</span>
  <span m='2472650'>op-amp</span> <span m='2473100'>killing</span> <span m='2473500'>itself.</span>
  </p><p><span m='2479460'>OK,</span> <span m='2479850'>it's</span> <span m='2479970'>not</span>
  <span m='2480120'>working.</span> <span m='2480580'>Why</span> <span m='2480690'>is</span>
  <span m='2480810'>it</span> <span m='2480890'>not?</span> <span m='2481420'>Is</span>
  <span m='2481530'>it</span> <span m='2481620'>working?</span> <span m='2483390'>I</span>
  <span m='2483450'>just</span> <span m='2483630'>gave</span> <span m='2483750'>it</span>
  <span m='2483810'>away.</span> <span m='2483990'>It's</span> <span m='2484080'>not</span>
  <span m='2484220'>working.</span> <span m='2484740'>How</span> <span m='2484860'>do</span>
  <span m='2484980'>I</span> <span m='2485040'>know</span> <span m='2485190'>it's</span>
  <span m='2485310'>not</span> <span m='2485460'>working?</span> </p><p><span m='2486480'>Here's</span>
  <span m='2486750'>my</span> <span m='2486930'>theory.</span> <span m='2488740'>Here's</span>
  <span m='2488910'>my</span> <span m='2489150'>answer.</span> <span m='2490020'>How</span>
  <span m='2490170'>do</span> <span m='2490290'>they</span> <span m='2490500'>match</span>
  <span m='2490785'>or</span> <span m='2491070'>mismatch?</span> <span m='2492840'>Is</span>
  <span m='2493020'>it</span> <span m='2493120'>an</span> <span m='2493230'>angle</span>
  <span m='2493590'>controller?</span> <span m='2494250'>Yes</span> <span m='2494490'>or</span>
  <span m='2494580'>no?</span> <span m='2494910'>Yes.</span> </p><p><span m='2497084'>AUDIENCE:</span>
  <span m='2497224'>Didn't</span> <span m='2497364'>we</span> <span m='2497505'>just
  do this?</span> </p><p><span m='2497930'>DENNIS FREEMAN:</span> <span m='2498050'>Yeah,</span>
  <span m='2498170'>it's</span> <span m='2498290'>an</span> <span m='2498380'>angle</span>
  <span m='2498620'>controller.</span> <span m='2500130'>What's</span> <span m='2500450'>different</span>
  <span m='2500960'>about</span> <span m='2501350'>this</span> <span m='2501620'>behavior</span>
  <span m='2502250'>and</span> <span m='2502430'>that</span> <span m='2502730'>behavior?</span>
  </p><p><span m='2507258'>AUDIENCE:</span> <span m='2507503'>There's</span> <span
  m='2507749'>oscillation.</span> </p><p><span m='2508731'>DENNIS FREEMAN:</span>
  <span m='2508980'>There's</span> <span m='2509230'>oscillation.</span> <span m='2510040'>Right,</span>
  <span m='2510280'>this</span> <span m='2510520'>thing,</span> <span m='2511630'>turn</span>
  <span m='2511810'>it</span> <span m='2511870'>back</span> <span m='2512080'>on.</span>
  <span m='2512360'>Let</span> <span m='2512530'>the</span> <span m='2512680'>thing</span>
  <span m='2512890'>kill</span> <span m='2513130'>itself.</span> <span m='2514580'>There's</span>
  <span m='2514720'>an</span> <span m='2514780'>oscillation.</span> <span m='2516280'>Turn</span>
  <span m='2516490'>the</span> <span m='2516580'>gain</span> <span m='2516820'>down</span>
  <span m='2517090'>so</span> <span m='2517180'>it</span> <span m='2517240'>doesn't</span>
  <span m='2517480'>kill</span> <span m='2517630'>itself</span> <span m='2517900'>quite</span>
  <span m='2518170'>as</span> <span m='2518260'>quickly.</span> <span m='2519646'>It's</span>
  <span m='2520090'>oscillating.</span> </p><p><span m='2522570'>Watch</span> <span
  m='2522820'>the</span> <span m='2523010'>oscillation.</span> <span m='2525710'>Think</span>
  <span m='2525920'>about</span> <span m='2526070'>characterizing</span> <span m='2526700'>the</span>
  <span m='2526810'>oscillation.</span> <span m='2529190'>Make</span> <span m='2529340'>the</span>
  <span m='2529430'>gain</span> <span m='2529640'>smaller.</span> <span m='2532090'>That's</span>
  <span m='2532210'>bad.</span> <span m='2536540'>Ignore</span> <span m='2536820'>that.</span>
  <span m='2541210'>Think</span> <span m='2541390'>about</span> <span m='2541570'>the</span>
  <span m='2541690'>oscillation.</span> <span m='2543765'>It's</span> <span m='2544240'>still</span>
  <span m='2544520'>oscillating.</span> <span m='2545770'>Factor of</span> <span m='2546140'>three</span>
  <span m='2546430'>smaller,</span> <span m='2548626'>it's</span> <span m='2549070'>still</span>
  <span m='2549350'>oscillating.</span> </p><p><span m='2551380'>That</span> <span
  m='2551710'>doesn't</span> <span m='2551920'>oscillate.</span> <span m='2552280'>What's</span>
  <span m='2552430'>wrong?</span> <span m='2555980'>OK,</span> <span m='2556370'>so</span>
  <span m='2556520'>the</span> <span m='2556610'>$64,000</span> <span m='2557420'>question,</span>
  <span m='2557660'>what</span> <span m='2557750'>did</span> <span m='2557840'>I</span>
  <span m='2557900'>do</span> <span m='2558020'>wrong?</span> <span m='2559490'>Right,</span>
  <span m='2559760'>the</span> <span m='2559880'>goal</span> <span m='2560190'>is</span>
  <span m='2560330'>to</span> <span m='2560420'>make</span> <span m='2560570'>a</span>
  <span m='2560600'>model</span> <span m='2560860'>of</span> <span m='2560930'>the</span>
  <span m='2560990'>motor,</span> <span m='2561530'>analyze the</span> <span m='2561980'>model,</span>
  <span m='2562520'>figure</span> <span m='2562760'>out</span> <span m='2562820'>how</span>
  <span m='2562910'>to</span> <span m='2563000'>put</span> <span m='2563090'>feedback</span>
  <span m='2563480'>around</span> <span m='2563720'>it,</span> <span m='2563810'>make</span>
  <span m='2563990'>it</span> <span m='2564050'>perfect.</span> <span m='2564470'>Yes.</span>
  </p><p><span m='2565282'>AUDIENCE:</span> <span m='2565372'>The</span> <span m='2565462'>model</span>
  <span m='2565552'>on</span> <span m='2565642'>the</span> <span m='2565734'>board
  was</span> <span m='2566186'>created</span> <span m='2566638'>without any</span>
  <span m='2567090'>inertia.</span> </p><p><span m='2568450'>DENNIS FREEMAN:</span>
  <span m='2568555'>I</span> <span m='2568660'>made</span> <span m='2569020'>too</span>
  <span m='2569260'>simple</span> <span m='2569650'>of</span> <span m='2569770'>a</span>
  <span m='2569800'>model</span> <span m='2570220'>for</span> <span m='2570370'>the</span>
  <span m='2570430'>motor.</span> <span m='2571510'>I</span> <span m='2571690'>ignored</span>
  <span m='2572350'>inertia.</span> <span m='2573280'>I</span> <span m='2573460'>ignored</span>
  <span m='2573820'>all</span> <span m='2574210'>manner</span> <span m='2574720'>of</span>
  <span m='2574840'>things.</span> <span m='2576880'>I</span> <span m='2577060'>ignored</span>
  <span m='2577450'>friction.</span> <span m='2579470'>So</span> <span m='2579700'>how</span>
  <span m='2580240'>can</span> <span m='2580390'>you</span> <span m='2580510'>tell</span>
  <span m='2580810'>that</span> <span m='2580960'>I</span> <span m='2581080'>ignored</span>
  <span m='2581380'>those</span> <span m='2581650'>things?</span> </p><p><span m='2583300'>So</span>
  <span m='2583510'>one</span> <span m='2583750'>way</span> <span m='2583930'>you</span>
  <span m='2584050'>can</span> <span m='2584200'>tell--</span> <span m='2584980'>let's</span>
  <span m='2585280'>see.</span> <span m='2586240'>Is it</span> <span m='2586660'>off
  or</span> <span m='2586990'>on?</span> <span m='2587350'>It's</span> <span m='2587500'>on.</span>
  <span m='2587850'>Or</span> <span m='2587980'>turn it</span> <span m='2588310'>off.</span>
  <span m='2589390'>Go</span> <span m='2589540'>back</span> <span m='2589840'>to</span>
  <span m='2589960'>the</span> <span m='2590110'>original</span> <span m='2590530'>configuration</span>
  <span m='2591310'>where</span> <span m='2591430'>it's</span> <span m='2591550'>a</span>
  <span m='2591610'>speed</span> <span m='2591970'>controller.</span> </p><p><span
  m='2594320'>Turn</span> <span m='2594590'>the</span> <span m='2594650'>speed</span>
  <span m='2595100'>on</span> <span m='2595490'>a</span> <span m='2595550'>little</span>
  <span m='2595850'>bit.</span> <span m='2598030'>Turn</span> <span m='2598280'>it</span>
  <span m='2598420'>off.</span> <span m='2599470'>Grab</span> <span m='2599770'>it</span>
  <span m='2599830'>with</span> <span m='2599980'>my</span> <span m='2600130'>fingers.</span>
  <span m='2602020'>Turn</span> <span m='2602230'>it</span> <span m='2602320'>on.</span>
  <span m='2603190'>Now,</span> <span m='2603400'>release</span> <span m='2603790'>it.</span>
  <span m='2607020'>What</span> <span m='2607110'>did</span> <span m='2607230'>you</span>
  <span m='2607350'>see?</span> <span m='2609338'>Grab</span> <span m='2609760'>it</span>
  <span m='2610010'>with</span> <span m='2610140'>my</span> <span m='2610260'>fingers.</span>
  <span m='2610620'>Turn</span> <span m='2610860'>it</span> <span m='2610920'>on.</span>
  <span m='2612210'>Let</span> <span m='2612360'>go.</span> </p><p><span m='2617080'>We're</span>
  <span m='2617230'>trying</span> <span m='2617620'>to</span> <span m='2617740'>poke</span>
  <span m='2618010'>a</span> <span m='2618070'>hole</span> <span m='2618460'>in</span>
  <span m='2618730'>this.</span> <span m='2620410'>There</span> <span m='2620570'>is</span>
  <span m='2620740'>my</span> <span m='2620890'>model.</span> <span m='2621700'>My</span>
  <span m='2621850'>model</span> <span m='2622180'>is</span> <span m='2622300'>wrong.</span>
  <span m='2624130'>I</span> <span m='2624370'>claim</span> <span m='2624760'>I</span>
  <span m='2624850'>just</span> <span m='2625060'>told</span> <span m='2625300'>you</span>
  <span m='2625420'>the</span> <span m='2625540'>key</span> <span m='2625840'>experiment</span>
  <span m='2626530'>for</span> <span m='2626710'>figuring</span> <span m='2627070'>out</span>
  <span m='2627250'>why</span> <span m='2627460'>my</span> <span m='2627640'>model</span>
  <span m='2627960'>is</span> <span m='2628060'>wrong.</span> <span m='2628360'>Now</span>
  <span m='2628480'>you</span> <span m='2628690'>have</span> <span m='2628780'>to</span>
  <span m='2628870'>figure</span> <span m='2629170'>out</span> <span m='2629560'>how</span>
  <span m='2629710'>to</span> <span m='2629830'>interpret</span> <span m='2630220'>that</span>
  <span m='2630400'>experiment.</span> </p><p><span m='2631030'>So</span> <span m='2633230'>what</span>
  <span m='2633470'>does</span> <span m='2633680'>my</span> <span m='2634010'>theory</span>
  <span m='2634520'>say</span> <span m='2634790'>would</span> <span m='2634940'>happen</span>
  <span m='2638110'>if</span> <span m='2638320'>I</span> <span m='2638440'>turn</span>
  <span m='2638710'>on</span> <span m='2638860'>the</span> <span m='2638950'>power,</span>
  <span m='2639580'>hold</span> <span m='2639850'>the</span> <span m='2639940'>bar,</span>
  <span m='2640390'>and</span> <span m='2640540'>release</span> <span m='2640860'>it?</span>
  </p><p><span m='2644730'>AUDIENCE:</span> <span m='2644965'>[INAUDIBLE].</span>
  </p><p><span m='2648020'>DENNIS FREEMAN:</span> <span m='2648080'>It</span> <span
  m='2648140'>should</span> <span m='2648470'>instantly</span> <span m='2649100'>reach</span>
  <span m='2649550'>the</span> <span m='2649670'>terminal</span> <span m='2650120'>velocity.</span>
  <span m='2651500'>What's</span> <span m='2651770'>it</span> <span m='2651890'>doing?</span>
  </p><p><span m='2652786'>AUDIENCE:</span> <span m='2652905'>I</span> <span m='2653024'>has</span>
  <span m='2653143'>just</span> <span m='2653262'>like a rise</span> <span m='2653738'>time</span>
  <span m='2654214'>[INAUDIBLE].</span> </p><p><span m='2654690'>DENNIS FREEMAN:</span>
  <span m='2654795'>It's</span> <span m='2654900'>ramping</span> <span m='2655470'>up.</span>
  <span m='2656730'>That's</span> <span m='2657060'>what's</span> <span m='2657210'>wrong</span>
  <span m='2657420'>with</span> <span m='2657570'>my</span> <span m='2657720'>model.</span>
  <span m='2659510'>OK,</span> <span m='2660290'>so</span> <span m='2660440'>the</span>
  <span m='2660530'>model</span> <span m='2660890'>is</span> <span m='2661010'>too</span>
  <span m='2661190'>simple.</span> <span m='2661950'>It's</span> <span m='2662060'>not</span>
  <span m='2662420'>just</span> <span m='2662810'>an</span> <span m='2662900'>integrator.</span>
  <span m='2663650'>It's</span> <span m='2663860'>a</span> <span m='2663980'>slow</span>
  <span m='2664700'>integrator.</span> </p><p><span m='2667150'>OK,</span> <span m='2667390'>I</span>
  <span m='2667480'>can</span> <span m='2667660'>model</span> <span m='2667990'>that</span>
  <span m='2668260'>too.</span> <span m='2670210'>If</span> <span m='2670360'>I</span>
  <span m='2670450'>model</span> <span m='2670840'>the</span> <span m='2670960'>slow</span>
  <span m='2671890'>integration,</span> <span m='2674440'>I</span> <span m='2674530'>can</span>
  <span m='2674710'>think</span> <span m='2674920'>about</span> <span m='2675460'>the</span>
  <span m='2675550'>motor</span> <span m='2675910'>doesn't</span> <span m='2676270'>really</span>
  <span m='2676660'>behave</span> <span m='2677020'>like</span> <span m='2677200'>an</span>
  <span m='2677320'>integrator.</span> <span m='2677980'>It</span> <span m='2678160'>works</span>
  <span m='2678430'>like</span> <span m='2678610'>a</span> <span m='2678670'>sluggish</span>
  <span m='2680150'>integrator.</span> <span m='2683330'>That</span> <span m='2683610'>might</span>
  <span m='2683760'>be</span> <span m='2683850'>a</span> <span m='2683880'>lot</span>
  <span m='2684060'>easier</span> <span m='2684360'>to</span> <span m='2684450'>see</span>
  <span m='2684630'>if</span> <span m='2684720'>I</span> <span m='2684780'>write</span>
  <span m='2685050'>that in</span> <span m='2685160'>s.</span> <span m='2686520'>So</span>
  <span m='2688290'>that's</span> <span m='2688560'>the</span> <span m='2688680'>same</span>
  <span m='2689010'>as</span> <span m='2690630'>gamma</span> <span m='2691490'>p</span>
  <span m='2692540'>over</span> <span m='2693140'>s</span> <span m='2693690'>plus</span>
  <span m='2694170'>gamma.</span> <span m='2695140'>No,</span> <span m='2695550'>s</span>
  <span m='2695730'>times--</span> <span m='2697050'>no,</span> <span m='2697890'>close,</span>
  <span m='2698380'>wrong.</span> </p><p><span m='2705200'>So</span> <span m='2705340'>it</span>
  <span m='2705430'>used</span> <span m='2705610'>to</span> <span m='2705700'>be</span>
  <span m='2705820'>gamma</span> <span m='2706150'>over</span> <span m='2706480'>s.</span>
  <span m='2707290'>Now,</span> <span m='2707530'>it's</span> <span m='2707680'>gamma</span>
  <span m='2708130'>over</span> <span m='2708460'>s</span> <span m='2708910'>s plus</span>
  <span m='2709090'>p.</span> <span m='2712150'>OK,</span> <span m='2712590'>so</span>
  <span m='2712880'>I'm</span> <span m='2713060'>replacing</span> <span m='2714140'>what</span>
  <span m='2714350'>had</span> <span m='2714590'>been</span> <span m='2714770'>an</span>
  <span m='2714890'>integrator</span> <span m='2717190'>here</span> <span m='2718960'>with</span>
  <span m='2719230'>a</span> <span m='2719290'>sluggish</span> <span m='2719800'>integrator.</span>
  </p><p><span m='2721540'>Sluggish</span> <span m='2722350'>is</span> <span m='2723280'>another</span>
  <span m='2723640'>pole.</span> <span m='2725640'>So</span> <span m='2725790'>instead</span>
  <span m='2726060'>of</span> <span m='2726150'>representing</span> <span m='2726720'>it</span>
  <span m='2726810'>by</span> <span m='2726990'>a</span> <span m='2727020'>single</span>
  <span m='2727450'>pole</span> <span m='2728910'>at</span> <span m='2729060'>the</span>
  <span m='2729180'>origin,</span> <span m='2730230'>I</span> <span m='2730320'>represent</span>
  <span m='2730575'>it</span> <span m='2730830'>by</span> <span m='2730980'>two</span>
  <span m='2731220'>poles.</span> <span m='2731910'>If</span> <span m='2732060'>you</span>
  <span m='2732120'>calculate</span> <span m='2732780'>the</span> <span m='2733470'>step</span>
  <span m='2733860'>response</span> <span m='2735510'>for</span> <span m='2735740'>the</span>
  <span m='2736170'>single</span> <span m='2736560'>pole</span> <span m='2736950'>at</span>
  <span m='2737040'>the</span> <span m='2737160'>origin,</span> <span m='2738120'>you</span>
  <span m='2738240'>get</span> <span m='2738420'>the</span> <span m='2738510'>straight</span>
  <span m='2738840'>line.</span> <span m='2739140'>That</span> <span m='2739290'>was</span>
  <span m='2739410'>model</span> <span m='2739800'>one.</span> </p><p><span m='2741800'>If</span>
  <span m='2741920'>you</span> <span m='2742010'>calculate</span> <span m='2742550'>the</span>
  <span m='2742670'>step</span> <span m='2742910'>response</span> <span m='2743330'>for</span>
  <span m='2743450'>the</span> <span m='2743570'>modified</span> <span m='2744140'>model,</span>
  <span m='2745790'>that's</span> <span m='2746090'>this</span> <span m='2746330'>one.</span>
  <span m='2748420'>Ultimately,</span> <span m='2749740'>they</span> <span m='2750010'>become</span>
  <span m='2750400'>parallel.</span> <span m='2751280'>So</span> <span m='2751360'>the</span>
  <span m='2751480'>speed</span> <span m='2751780'>becomes</span> <span m='2752230'>the</span>
  <span m='2752350'>same.</span> <span m='2754760'>But</span> <span m='2754940'>there's</span>
  <span m='2755090'>sluggishness</span> <span m='2755870'>because</span> <span m='2756230'>of</span>
  <span m='2756320'>inertia</span> <span m='2756830'>and</span> <span m='2756980'>so</span>
  <span m='2757190'>forth</span> <span m='2758370'>so</span> <span m='2758480'>that</span>
  <span m='2758660'>it</span> <span m='2758720'>takes</span> <span m='2759050'>a</span>
  <span m='2759140'>while</span> <span m='2759650'>for</span> <span m='2759830'>the</span>
  <span m='2759950'>real</span> <span m='2760220'>motor</span> <span m='2760580'>to</span>
  <span m='2760760'>achieve</span> <span m='2761180'>that.</span> </p><p><span m='2761610'>So</span>
  <span m='2761630'>you</span> <span m='2761750'>can</span> <span m='2761900'>see</span>
  <span m='2762080'>that</span> <span m='2762800'>in</span> <span m='2763010'>the</span>
  <span m='2763100'>model</span> <span m='2763390'>two</span> <span m='2763610'>response,</span>
  <span m='2764330'>because</span> <span m='2765020'>the</span> <span m='2766580'>angle</span>
  <span m='2766940'>does</span> <span m='2767150'>not</span> <span m='2767420'>immediately</span>
  <span m='2767990'>change</span> <span m='2768410'>when</span> <span m='2768560'>I</span>
  <span m='2768650'>let</span> <span m='2768800'>go</span> <span m='2769070'>of</span>
  <span m='2769220'>it,</span> <span m='2772030'>it</span> <span m='2772150'>takes</span>
  <span m='2772420'>a</span> <span m='2772510'>while</span> <span m='2772930'>for</span>
  <span m='2773140'>it</span> <span m='2773200'>to</span> <span m='2773320'>start</span>
  <span m='2773560'>to</span> <span m='2773650'>change.</span> <span m='2773950'>That's</span>
  <span m='2774100'>inertia.</span> <span m='2775910'>So</span> <span m='2777550'>if</span>
  <span m='2777730'>I</span> <span m='2777850'>put</span> <span m='2778060'>that</span>
  <span m='2780070'>model,</span> <span m='2780850'>model</span> <span m='2781180'>two,</span>
  <span m='2782260'>into</span> <span m='2782560'>the</span> <span m='2782650'>feedback</span>
  <span m='2783070'>loop,</span> <span m='2785000'>then</span> <span m='2785270'>I</span>
  <span m='2785360'>make</span> <span m='2785570'>a</span> <span m='2785630'>different</span>
  <span m='2786020'>prediction</span> <span m='2786950'>about</span> <span m='2787220'>the</span>
  <span m='2787310'>way</span> <span m='2787490'>things</span> <span m='2787760'>should</span>
  <span m='2787970'>work.</span> </p><p><span m='2790400'>That</span> <span m='2790580'>prediction</span>
  <span m='2791030'>is</span> <span m='2791120'>shown</span> <span m='2791360'>here.</span>
  <span m='2791790'>Right?</span> <span m='2792140'>That's</span> <span m='2792290'>just</span>
  <span m='2792890'>thinking</span> <span m='2793220'>about</span> <span m='2793430'>system</span>
  <span m='2793760'>functions,</span> <span m='2795020'>saying</span> <span m='2795440'>that</span>
  <span m='2795620'>I've</span> <span m='2795710'>got</span> <span m='2795920'>two</span>
  <span m='2796130'>poles,</span> <span m='2797600'>trying</span> <span m='2797750'>to</span>
  <span m='2798000'>figure</span> <span m='2798200'>out</span> <span m='2798320'>where</span>
  <span m='2798470'>the</span> <span m='2798560'>poles</span> <span m='2798890'>are,</span>
  <span m='2799100'>figuring</span> <span m='2799400'>out</span> <span m='2799490'>where</span>
  <span m='2799580'>the</span> <span m='2799670'>time</span> <span m='2799970'>domain</span>
  <span m='2800480'>response</span> <span m='2800870'>is,</span> <span m='2800990'>integrating</span>
  <span m='2801410'>it</span> <span m='2801500'>to</span> <span m='2801590'>turn</span>
  <span m='2801770'>it</span> <span m='2801830'>into</span> <span m='2802010'>a</span>
  <span m='2802040'>step</span> <span m='2802340'>response.</span> <span m='2802910'>Do</span>
  <span m='2803090'>all</span> <span m='2803220'>those</span> <span m='2803450'>things,</span>
  <span m='2804470'>and</span> <span m='2804590'>you</span> <span m='2804680'>get</span>
  <span m='2805040'>a</span> <span m='2806330'>response.</span> </p><p><span m='2807860'>The</span>
  <span m='2807980'>point</span> <span m='2808280'>is</span> <span m='2808550'>that</span>
  <span m='2808760'>the</span> <span m='2808850'>new</span> <span m='2809120'>model</span>
  <span m='2810050'>looks</span> <span m='2810320'>like</span> <span m='2810500'>two</span>
  <span m='2810710'>poles.</span> <span m='2811820'>And</span> <span m='2811940'>when</span>
  <span m='2812030'>you</span> <span m='2812180'>analyze</span> <span m='2812810'>the</span>
  <span m='2813290'>root</span> <span m='2813560'>locus,</span> <span m='2815810'>those</span>
  <span m='2816110'>poles</span> <span m='2816500'>move</span> <span m='2817430'>when</span>
  <span m='2817580'>you</span> <span m='2817730'>change</span> <span m='2818180'>the</span>
  <span m='2818570'>feedback.</span> <span m='2820870'>So</span> <span m='2820920'>as</span>
  <span m='2821040'>I</span> <span m='2821130'>change</span> <span m='2821490'>the</span>
  <span m='2821610'>feedback</span> <span m='2822030'>number,</span> <span m='2822300'>beta,</span>
  <span m='2823780'>as</span> <span m='2824190'>beta</span> <span m='2824490'>goes</span>
  <span m='2824760'>from</span> <span m='2824970'>0</span> <span m='2825570'>to</span>
  <span m='2825810'>big,</span> <span m='2826830'>the</span> <span m='2826920'>poles</span>
  <span m='2827250'>go</span> <span m='2827400'>toward</span> <span m='2827700'>each</span>
  <span m='2827880'>other</span> <span m='2828150'>and</span> <span m='2828300'>then</span>
  <span m='2828450'>split</span> <span m='2828810'>off.</span> </p><p><span m='2830490'>That's</span>
  <span m='2830760'>just</span> <span m='2831060'>math.</span> <span m='2832620'>That's</span>
  <span m='2832860'>the</span> <span m='2832980'>math</span> <span m='2833230'>that</span>
  <span m='2833310'>was</span> <span m='2833460'>showed</span> <span m='2833730'>over</span>
  <span m='2833970'>here.</span> <span m='2834870'>All</span> <span m='2835080'>I</span>
  <span m='2835170'>did</span> <span m='2835380'>was</span> <span m='2835590'>write</span>
  <span m='2837480'>the</span> <span m='2837810'>second</span> <span m='2838140'>model</span>
  <span m='2838710'>up</span> <span m='2838890'>there,</span> <span m='2839640'>figure</span>
  <span m='2840000'>out</span> <span m='2840240'>the</span> <span m='2840870'>system</span>
  <span m='2841230'>function,</span> <span m='2843110'>find</span> <span m='2843580'>the</span>
  <span m='2843700'>poles</span> <span m='2844210'>of</span> <span m='2844270'>the</span>
  <span m='2844390'>system</span> <span m='2844690'>function.</span> <span m='2845440'>They</span>
  <span m='2845620'>depend</span> <span m='2846040'>on</span> <span m='2846190'>beta.</span>
  <span m='2847125'>And</span> <span m='2847540'>that</span> <span m='2847720'>dependence</span>
  <span m='2848170'>is</span> <span m='2848260'>shown</span> <span m='2848560'>here.</span>
  </p><p><span m='2849530'>And</span> <span m='2849580'>so</span> <span m='2849970'>the</span>
  <span m='2850120'>response</span> <span m='2850690'>then,</span> <span m='2851740'>that's</span>
  <span m='2851980'>where</span> <span m='2852070'>the</span> <span m='2852190'>oscillations</span>
  <span m='2852640'>come</span> <span m='2852790'>from.</span> <span m='2853570'>If</span>
  <span m='2853780'>the</span> <span m='2853870'>gain</span> <span m='2854200'>is</span>
  <span m='2854410'>big</span> <span m='2854680'>enough,</span> <span m='2856240'>I</span>
  <span m='2856330'>get</span> <span m='2856540'>a</span> <span m='2856600'>pair</span>
  <span m='2856930'>of</span> <span m='2857080'>poles</span> <span m='2857590'>that</span>
  <span m='2857740'>are</span> <span m='2857860'>off</span> <span m='2858250'>the</span>
  <span m='2858970'>real</span> <span m='2859210'>axis.</span> <span m='2860810'>The</span>
  <span m='2860930'>fact</span> <span m='2861200'>that</span> <span m='2861350'>they</span>
  <span m='2861530'>have</span> <span m='2861710'>an</span> <span m='2861770'>imaginary</span>
  <span m='2862280'>component,</span> <span m='2862790'>the</span> <span m='2862880'>poles,</span>
  <span m='2863900'>means</span> <span m='2864140'>that</span> <span m='2864230'>there's</span>
  <span m='2864410'>an</span> <span m='2864500'>oscillation.</span> <span m='2865880'>And</span>
  <span m='2866570'>what</span> <span m='2866780'>happens</span> <span m='2867200'>is</span>
  <span m='2867350'>I</span> <span m='2867440'>change</span> <span m='2867920'>the</span>
  <span m='2868670'>feedback</span> <span m='2869390'>is</span> <span m='2869630'>not</span>
  <span m='2869870'>that</span> <span m='2869990'>the</span> <span m='2870110'>oscillation</span>
  <span m='2870650'>goes</span> <span m='2870860'>away.</span> <span m='2871890'>In</span>
  <span m='2872000'>fact,</span> <span m='2872970'>the</span> <span m='2873470'>real</span>
  <span m='2873830'>part</span> <span m='2874370'>of</span> <span m='2874490'>the</span>
  <span m='2874640'>envelope</span> <span m='2875120'>doesn't</span> <span m='2875420'>change.</span>
  </p><p><span m='2877160'>That's</span> <span m='2877370'>roughly</span> <span m='2877670'>what</span>
  <span m='2877820'>I</span> <span m='2877910'>was</span> <span m='2878030'>seeing</span>
  <span m='2878390'>here.</span> <span m='2879200'>If</span> <span m='2879380'>you</span>
  <span m='2879860'>watched</span> <span m='2880370'>what</span> <span m='2880520'>was</span>
  <span m='2880640'>going</span> <span m='2880910'>on</span> <span m='2881120'>in</span>
  <span m='2881210'>the</span> <span m='2881300'>closed-loop</span> <span m='2881750'>configuration,</span>
  <span m='2883920'>it</span> <span m='2884070'>always</span> <span m='2884640'>oscillated</span>
  <span m='2885390'>for</span> <span m='2885750'>a</span> <span m='2885870'>couple</span>
  <span m='2886230'>of</span> <span m='2886290'>seconds--</span> <span m='2886890'>like</span>
  <span m='2887070'>a</span> <span m='2887130'>second</span> <span m='2887580'>or</span>
  <span m='2887700'>two</span> <span m='2887880'>seconds</span> <span m='2888270'>or</span>
  <span m='2888360'>three</span> <span m='2888540'>seconds.</span> <span m='2889680'>That</span>
  <span m='2890130'>second</span> <span m='2890490'>or</span> <span m='2890580'>two</span>
  <span m='2890760'>seconds</span> <span m='2891120'>didn't</span> <span m='2891390'>change.</span>
  <span m='2892290'>What</span> <span m='2892470'>did</span> <span m='2892650'>change</span>
  <span m='2892980'>was</span> <span m='2893160'>the</span> <span m='2893280'>bumps--</span>
  <span m='2894540'>how</span> <span m='2894720'>many</span> <span m='2894900'>bumps</span>
  <span m='2895230'>there</span> <span m='2895380'>were</span> <span m='2895620'>in</span>
  <span m='2895800'>the</span> <span m='2895890'>two</span> <span m='2896070'>seconds.</span>
  </p><p><span m='2896910'>And</span> <span m='2897060'>that's</span> <span m='2897210'>what</span>
  <span m='2897360'>the</span> <span m='2897450'>theory</span> <span m='2897750'>says.</span>
  <span m='2900090'>Because</span> <span m='2900750'>the</span> <span m='2901830'>real</span>
  <span m='2902130'>part</span> <span m='2903000'>of</span> <span m='2903240'>the</span>
  <span m='2904140'>imaginary</span> <span m='2904710'>pair</span> <span m='2905010'>of</span>
  <span m='2905130'>poles</span> <span m='2905910'>doesn't</span> <span m='2906240'>change,</span>
  <span m='2907080'>the</span> <span m='2907230'>envelope</span> <span m='2907680'>doesn't</span>
  <span m='2908010'>change.</span> <span m='2909190'>But</span> <span m='2909320'>because</span>
  <span m='2909630'>the</span> <span m='2909720'>imaginary</span> <span m='2910260'>part</span>
  <span m='2910470'>does</span> <span m='2910770'>change,</span> <span m='2911760'>the</span>
  <span m='2911880'>oscillation</span> <span m='2912390'>frequency</span> <span m='2912840'>does</span>
  <span m='2913110'>change.</span> <span m='2914740'>So</span> <span m='2914790'>the</span>
  <span m='2914880'>result</span> <span m='2915270'>then</span> <span m='2915900'>is</span>
  <span m='2916050'>something</span> <span m='2916530'>whose</span> <span m='2916800'>envelope</span>
  <span m='2917610'>doesn't</span> <span m='2917940'>really</span> <span m='2918360'>improve.</span>
  </p><p><span m='2921570'>So</span> <span m='2921750'>that</span> <span m='2922050'>model</span>
  <span m='2922410'>then</span> <span m='2924270'>to</span> <span m='2924420'>a</span>
  <span m='2924480'>large</span> <span m='2924750'>extent</span> <span m='2925110'>does</span>
  <span m='2925410'>predict</span> <span m='2926280'>the</span> <span m='2926690'>behavior</span>
  <span m='2927150'>that</span> <span m='2927460'>I have</span> <span m='2927650'>measured.</span>
  <span m='2928720'>And</span> <span m='2928770'>then</span> <span m='2929160'>what</span>
  <span m='2929340'>that</span> <span m='2929490'>motivates</span> <span m='2930090'>is</span>
  <span m='2930600'>if</span> <span m='2930750'>I</span> <span m='2930810'>want</span>
  <span m='2931020'>to</span> <span m='2931080'>make</span> <span m='2931260'>the</span>
  <span m='2931350'>motor</span> <span m='2931770'>work</span> <span m='2932190'>better,</span>
  <span m='2933120'>I</span> <span m='2933210'>need</span> <span m='2933480'>some</span>
  <span m='2933900'>even</span> <span m='2934230'>better</span> <span m='2934500'>controller</span>
  <span m='2937440'>because</span> <span m='2937800'>my</span> <span m='2937950'>simple</span>
  <span m='2938280'>proportional</span> <span m='2938880'>controller,</span> <span
  m='2939720'>that's</span> <span m='2939960'>as</span> <span m='2940080'>good</span>
  <span m='2940230'>as</span> <span m='2940350'>it's</span> <span m='2940440'>going</span>
  <span m='2940590'>to</span> <span m='2940650'>do.</span> </p><p><span m='2942500'>OK,</span>
  <span m='2944210'>so</span> <span m='2945620'>what</span> <span m='2946220'>I</span>
  <span m='2946310'>tried</span> <span m='2946580'>to</span> <span m='2946640'>illustrate</span>
  <span m='2947090'>today</span> <span m='2947420'>was</span> <span m='2947600'>ways</span>
  <span m='2947960'>of</span> <span m='2948050'>thinking</span> <span m='2948350'>about</span>
  <span m='2948560'>feedback</span> <span m='2949190'>to</span> <span m='2949400'>enhance</span>
  <span m='2950150'>performance.</span> <span m='2951020'>We</span> <span m='2951200'>looked</span>
  <span m='2951410'>at</span> <span m='2951530'>an</span> <span m='2951620'>op-amp</span>
  <span m='2952070'>and</span> <span m='2952160'>saw</span> <span m='2952400'>how</span>
  <span m='2952550'>you</span> <span m='2952700'>could</span> <span m='2952820'>think</span>
  <span m='2953030'>about</span> <span m='2953240'>feedback</span> <span m='2953930'>increasing</span>
  <span m='2954410'>the</span> <span m='2954500'>bandwidth</span> <span m='2955040'>or</span>
  <span m='2955130'>making</span> <span m='2955400'>it</span> <span m='2955490'>faster.</span>
  <span m='2956720'>We</span> <span m='2956810'>looked</span> <span m='2956990'>at</span>
  <span m='2957060'>a</span> <span m='2957140'>motor</span> <span m='2957830'>and</span>
  <span m='2957920'>found</span> <span m='2958150'>out</span> <span m='2958220'>how</span>
  <span m='2958310'>you</span> <span m='2958450'>could</span> <span m='2958550'>think</span>
  <span m='2958700'>about</span> <span m='2958910'>changing</span> <span m='2959390'>the</span>
  <span m='2959510'>motor</span> <span m='2959840'>from</span> <span m='2960050'>being</span>
  <span m='2960410'>a</span> <span m='2960590'>voltage-controlled</span> <span m='2961610'>velocity</span>
  <span m='2962630'>to</span> <span m='2962780'>a</span> <span m='2962810'>voltage-controlled</span>
  <span m='2963740'>position.</span> <span m='2964700'>And</span> <span m='2964810'>we</span>
  <span m='2964880'>saw</span> <span m='2965060'>how</span> <span m='2965240'>the</span>
  <span m='2965450'>feedback</span> <span m='2965850'>could</span> <span m='2965990'>be</span>
  <span m='2966110'>used</span> <span m='2966350'>for</span> <span m='2966470'>both</span>
  <span m='2966680'>of</span> <span m='2966770'>those.</span> <span m='2967400'>Next</span>
  <span m='2967700'>time,</span> <span m='2967940'>we'll</span> <span m='2968060'>look</span>
  <span m='2968240'>at</span> <span m='2968330'>a</span> <span m='2968420'>couple</span>
  <span m='2969230'>other</span> <span m='2969500'>examples.</span> <span m='2971300'>Thanks.</span>
  </p>
type: course
uid: 5277acbc3461158b2e3212b4e39d343c

---
None