---
about_this_resource_text: <p><strong>Instructor:</strong> Dennis Freeman</p> <p><strong>Description:</strong>
  Continuing the comparison of continuous- and discrete-time signals, today's lecture
  discusses the DT Fourier transform, computation of Fourier series via the Fast Fourier
  Transform (FFT), and examples from digital image processing.</p>
course_id: 6-003-signals-and-systems-fall-2011
embedded_media:
- id: Video-YouTube-Stream
  media_location: 3D51nqZ-97Q
  parent_uid: 6cf031b75b40b8da42b06246a2633eed
  title: Video-YouTube-Stream
  type: Video
  uid: d62405ac188c64727c2789d60a2f3684
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/3D51nqZ-97Q/default.jpg
  parent_uid: 6cf031b75b40b8da42b06246a2633eed
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: de802eafa92ee1c25eab60df76a60102
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/lecture-18-discrete-time-dt/id602305810?i=132455953
  parent_uid: 6cf031b75b40b8da42b06246a2633eed
  title: Video-iTunes U-MP4
  type: Video
  uid: 0760f7082306246b6ebfe51bd0e038d4
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.003F11/MIT6_003F11_lec18_300k.mp4
  parent_uid: 6cf031b75b40b8da42b06246a2633eed
  title: Video-Internet Archive-MP4
  type: Video
  uid: 54b872ee2932840b4e427b223a681e0c
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 3D51nqZ-97Q
  parent_uid: 6cf031b75b40b8da42b06246a2633eed
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 3f370159d15d86ba3517c42b6464cc3b
- id: 3D51nqZ-97Q.srt
  parent_uid: 6cf031b75b40b8da42b06246a2633eed
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-18-discrete-time-dt-fourier-representations/3D51nqZ-97Q.srt
  title: 3play caption file
  type: null
  uid: ea2578212bfd87a3fd31a594d6e38f1f
- id: 3D51nqZ-97Q.pdf
  parent_uid: 6cf031b75b40b8da42b06246a2633eed
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-18-discrete-time-dt-fourier-representations/3D51nqZ-97Q.pdf
  title: 3play pdf file
  type: null
  uid: 77ac2160d71360f9b7169ff32cb1645b
- id: Caption-3Play YouTube id-SRT
  parent_uid: 6cf031b75b40b8da42b06246a2633eed
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ff9ec9ae0136ad2729891daf2e5963bc
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 6cf031b75b40b8da42b06246a2633eed
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 67a2651c894a2c257b3e2aa2ace85d64
inline_embed_id: 195301lecture18:discrete-time(dt)fourierrepresentations74747753
layout: video
order_index: null
parent_uid: 47b07fedf3a30be25f155f62399cdb59
related_resources_text: ''
short_url: lecture-18-discrete-time-dt-fourier-representations
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-18-discrete-time-dt-fourier-representations
template_type: Tabbed
title: 'Lecture 18: Discrete-Time (DT) Fourier Representations'
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
  <span m='17430'>ocw.mit.edu.</span> </p><p><span m='26534'>DENNIS FREEMAN:</span>
  <span m='27040'>Hello,</span> <span m='27370'>welcome.</span> <span m='31080'>As</span>
  <span m='31260'>you</span> <span m='31350'>expect,</span> <span m='31820'>the</span>
  <span m='31890'>big</span> <span m='32070'>news</span> <span m='32490'>is</span>
  <span m='32850'>that</span> <span m='32940'>there's</span> <span m='33120'>a</span>
  <span m='33150'>quiz</span> <span m='33420'>next</span> <span m='33660'>week.</span>
  <span m='34500'>So</span> <span m='34710'>hopefully,</span> <span m='35100'>that's</span>
  <span m='35310'>all</span> <span m='35510'>square,</span> <span m='35970'>everybody</span>
  <span m='36300'>knows</span> <span m='36540'>everything.</span> </p><p><span m='38010'>Questions,</span>
  <span m='38580'>comments?</span> <span m='39640'>Everybody's</span> <span m='40080'>pretty</span>
  <span m='40860'>comfortable</span> <span m='41430'>with</span> <span m='41610'>what's</span>
  <span m='41790'>going</span> <span m='42030'>on</span> <span m='42180'>with</span>
  <span m='42300'>the</span> <span m='42420'>quiz?</span> <span m='44950'>If</span>
  <span m='45130'>you</span> <span m='45220'>have</span> <span m='45370'>a</span>
  <span m='45400'>conflict,</span> <span m='46000'>please</span> <span m='46360'>contact</span>
  <span m='46810'>me</span> <span m='46960'>shortly,</span> <span m='47410'>because</span>
  <span m='47740'>I</span> <span m='47800'>have</span> <span m='47920'>to</span> <span
  m='48040'>arrange</span> <span m='48400'>rooms</span> <span m='48850'>and</span>
  <span m='49270'>proctors.</span> <span m='52000'>No</span> <span m='52120'>questions?</span>
  <span m='53740'>Good.</span> </p><p><span m='55090'>So</span> <span m='55240'>last</span>
  <span m='55480'>time</span> <span m='55660'>we</span> <span m='55810'>looked</span>
  <span m='56200'>at</span> <span m='56890'>discrete</span> <span m='57700'>time</span>
  <span m='58870'>frequency</span> <span m='59470'>responses.</span> <span m='61180'>Lots</span>
  <span m='61540'>of</span> <span m='61630'>things</span> <span m='61900'>were</span>
  <span m='62050'>similar.</span> <span m='62530'>A</span> <span m='62590'>few</span>
  <span m='62860'>things</span> <span m='63160'>were</span> <span m='63280'>different.</span>
  <span m='65140'>The</span> <span m='65500'>first</span> <span m='65740'>difference</span>
  <span m='66070'>we</span> <span m='66190'>saw</span> <span m='66880'>was</span>
  <span m='67240'>that</span> <span m='67510'>in</span> <span m='67690'>discrete</span>
  <span m='68050'>time,</span> <span m='68420'>we</span> <span m='68520'>like</span>
  <span m='68620'>to</span> <span m='68710'>think</span> <span m='68890'>about</span>
  <span m='69130'>complex</span> <span m='70270'>geometric</span> <span m='70900'>sequences</span>
  <span m='71560'>rather</span> <span m='71860'>than</span> <span m='72040'>complex</span>
  <span m='73090'>exponential</span> <span m='73750'>sequences.</span> <span m='74410'>And</span>
  <span m='74500'>the</span> <span m='74620'>effect</span> <span m='74920'>of</span>
  <span m='75040'>that</span> <span m='76570'>is</span> <span m='76900'>that</span>
  <span m='77680'>the</span> <span m='78040'>frequency</span> <span m='78490'>response</span>
  <span m='78940'>lives</span> <span m='79210'>on</span> <span m='79300'>the</span>
  <span m='79360'>unit</span> <span m='79570'>circle.</span> </p><p><span m='80660'>So</span>
  <span m='80800'>if</span> <span m='80890'>you</span> <span m='81010'>try</span>
  <span m='81280'>to</span> <span m='81400'>think</span> <span m='81580'>about</span>
  <span m='82280'>a</span> <span m='82390'>discrete</span> <span m='82870'>time</span>
  <span m='83140'>system,</span> <span m='83530'>say,</span> <span m='83740'>characterized</span>
  <span m='84370'>by</span> <span m='85330'>a</span> <span m='85570'>z-transform</span>
  <span m='87040'>and</span> <span m='87220'>think</span> <span m='87370'>about</span>
  <span m='87610'>what</span> <span m='87820'>would</span> <span m='87970'>be</span>
  <span m='88210'>its</span> <span m='88390'>output</span> <span m='88840'>when</span>
  <span m='89060'>there</span> <span m='89130'>is</span> <span m='89260'>a</span>
  <span m='89500'>sinusoidal</span> <span m='90190'>input,</span> <span m='90940'>just</span>
  <span m='91210'>like</span> <span m='91390'>CT,</span> <span m='92500'>if</span>
  <span m='92650'>you</span> <span m='92740'>have</span> <span m='92890'>a</span>
  <span m='93010'>sinusoidal</span> <span m='93670'>input,</span> <span m='94090'>there's</span>
  <span m='94270'>going</span> <span m='94420'>to</span> <span m='94480'>be</span>
  <span m='94570'>a</span> <span m='94600'>sinusoidal</span> <span m='95260'>output</span>
  <span m='95680'>at</span> <span m='95920'>the</span> <span m='96040'>same</span>
  <span m='96280'>frequency.</span> <span m='98750'>But</span> <span m='99100'>the</span>
  <span m='99220'>amplitude</span> <span m='99580'>and</span> <span m='99670'>phase</span>
  <span m='99940'>can</span> <span m='100060'>be</span> <span m='100180'>shifted.</span>
  <span m='100465'>But</span> <span m='100750'>to</span> <span m='100840'>compute</span>
  <span m='101170'>the</span> <span m='101290'>amplitude</span> <span m='101740'>and
  the</span> <span m='101860'>phase</span> <span m='103390'>for</span> <span m='103580'>a</span>
  <span m='103630'>DT</span> <span m='104050'>system,</span> <span m='104950'>you</span>
  <span m='105070'>look</span> <span m='105250'>at</span> <span m='105350'>the</span>
  <span m='105430'>unit</span> <span m='105730'>circle</span> <span m='106585'>of</span>
  <span m='106870'>the</span> <span m='107020'>z-transform.</span> </p><p><span m='108510'>That's</span>
  <span m='109090'>as</span> <span m='109330'>distinct</span> <span m='109750'>from</span>
  <span m='109990'>the</span> <span m='110730'>Laplace</span> <span m='111070'>transform</span>
  <span m='111670'>in</span> <span m='111790'>CT,</span> <span m='112690'>we</span>
  <span m='112810'>looked</span> <span m='112990'>at</span> <span m='113080'>the</span>
  <span m='113170'>j omega-axis.</span> <span m='114320'>So</span> <span m='114340'>now,</span>
  <span m='114910'>everything</span> <span m='115240'>we</span> <span m='115300'>used</span>
  <span m='115480'>to</span> <span m='115540'>say</span> <span m='115690'>about</span>
  <span m='115870'>the</span> <span m='115980'>j omega-axis,</span> <span m='116710'>we</span>
  <span m='116830'>say</span> <span m='117010'>about</span> <span m='117250'>the</span>
  <span m='117340'>unit</span> <span m='117550'>circle.</span> <span m='118930'>Other</span>
  <span m='119170'>than</span> <span m='119320'>that,</span> <span m='119980'>things</span>
  <span m='120220'>are</span> <span m='120340'>extremely</span> <span m='120850'>similar.</span>
  </p><p><span m='123100'>And</span> <span m='123250'>just</span> <span m='123460'>to</span>
  <span m='123550'>boost</span> <span m='123880'>your</span> <span m='124000'>confidence</span>
  <span m='124550'>so</span> <span m='124630'>you</span> <span m='124720'>know</span>
  <span m='124840'>exactly</span> <span m='125530'>what's</span> <span m='125710'>going</span>
  <span m='125980'>on,</span> <span m='127500'>here's</span> <span m='127630'>a</span>
  <span m='127660'>question.</span> <span m='129220'>What</span> <span m='129400'>if</span>
  <span m='129490'>I</span> <span m='129580'>gave</span> <span m='129820'>you</span>
  <span m='129940'>a</span> <span m='130000'>system</span> <span m='130449'>that</span>
  <span m='130600'>had</span> <span m='130900'>a</span> <span m='130990'>single</span>
  <span m='131290'>pole</span> <span m='131530'>and</span> <span m='131620'>a</span>
  <span m='131650'>single</span> <span m='131930'>zero,</span> <span m='133120'>and</span>
  <span m='133270'>say</span> <span m='133510'>the</span> <span m='133600'>pole</span>
  <span m='133840'>and</span> <span m='133930'>zero</span> <span m='134380'>are</span>
  <span m='134560'>related</span> <span m='135040'>that</span> <span m='135250'>way?</span>
  <span m='138140'>How</span> <span m='138320'>would</span> <span m='138470'>you</span>
  <span m='138560'>think</span> <span m='138770'>about</span> <span m='139010'>that</span>
  <span m='139190'>system--</span> <span m='140000'>Low</span> <span m='140150'>pass,</span>
  <span m='140450'>high</span> <span m='140600'>pass,</span> <span m='140990'>all</span>
  <span m='141130'>pass,</span> <span m='141440'>band</span> <span m='141795'>pass,</span>
  <span m='142150'>band</span> <span m='142570'>stop,</span> <span m='143300'>high</span>
  <span m='143760'>stop,</span> <span m='144180'>low</span> <span m='144480'>stop,</span>
  <span m='145850'>all</span> <span m='146250'>stop?</span> </p><p><span m='157478'>AUDIENCE:</span>
  <span m='157967'>I say</span> <span m='158456'>low pass.</span> </p><p><span m='158945'>AUDIENCE:</span>
  <span m='159189'>Low</span> <span m='159434'>pass.</span> </p><p><span m='159923'>AUDIENCE:</span>
  <span m='160086'>Band</span> <span m='160249'>pass.</span> </p><p><span m='161390'>DENNIS
  FREEMAN:</span> <span m='161900'>So</span> <span m='162110'>some</span> <span m='162260'>very</span>
  <span m='162560'>early</span> <span m='162920'>votes</span> <span m='163310'>that</span>
  <span m='163460'>are</span> <span m='163520'>completely</span> <span m='164150'>correct.</span>
  <span m='170490'>You</span> <span m='170640'>had</span> <span m='170860'>the</span>
  <span m='170980'>recitation,</span> <span m='171850'>so</span> <span m='172000'>then</span>
  <span m='172180'>there</span> <span m='172240'>is</span> <span m='172360'>no</span>
  <span m='172510'>excuse.</span> <span m='173200'>So</span> <span m='173350'>if</span>
  <span m='173440'>I</span> <span m='173500'>see</span> <span m='173740'>any</span>
  <span m='174040'>wrong</span> <span m='174340'>answers--</span> <span m='176440'>and</span>
  <span m='176650'>I</span> <span m='176770'>see</span> <span m='176980'>wrong</span>
  <span m='177280'>answers.</span> </p><p><span m='178320'>[LAUGHTER]</span> </p><p><span
  m='179820'>Ah!</span> <span m='186820'>So</span> <span m='187090'>maybe</span> <span
  m='187330'>I</span> <span m='187420'>should</span> <span m='187600'>have</span>
  <span m='188080'>the</span> <span m='188140'>recitation</span> <span m='188740'>instructor--</span>
  <span m='189260'>well,</span> <span m='189370'>no,</span> <span m='189660'>no,</span>
  <span m='192660'>OK,</span> <span m='192940'>everybody</span> <span m='193330'>votes.</span>
  <span m='193900'>So</span> <span m='194800'>high</span> <span m='195190'>pass,</span>
  <span m='195470'>low</span> <span m='195610'>pass,</span> <span m='195850'>band</span>
  <span m='196260'>pass,</span> <span m='196780'>all</span> <span m='197020'>pass,</span>
  <span m='197390'>band</span> <span m='197740'>stop,</span> <span m='198400'>none</span>
  <span m='198580'>of</span> <span m='198640'>the</span> <span m='198700'>above,</span>
  <span m='199180'>vote.</span> <span m='201960'>The</span> <span m='202080'>vast</span>
  <span m='202500'>majority</span> <span m='202980'>is</span> <span m='203160'>100%</span>
  <span m='203730'>correct.</span> <span m='204300'>The</span> <span m='204390'>vast</span>
  <span m='204630'>majority</span> <span m='204970'>is</span> <span m='205060'>correct,</span>
  <span m='205350'>but</span> <span m='205730'>it's</span> <span m='206020'>not</span>
  <span m='206190'>quite</span> <span m='206430'>100%.</span> </p><p><span m='207660'>So</span>
  <span m='207990'>the</span> <span m='208140'>answer</span> <span m='208560'>is</span>
  <span m='209520'>4,</span> <span m='210840'>all</span> <span m='211060'>pass.</span>
  <span m='212120'>Why?</span> <span m='213730'>Can</span> <span m='213880'>somebody</span>
  <span m='214180'>make</span> <span m='214330'>an</span> <span m='214420'>argument</span>
  <span m='214720'>why</span> <span m='214990'>that</span> <span m='215140'>should</span>
  <span m='215290'>be</span> <span m='215410'>all</span> <span m='215500'>pass,</span>
  <span m='215830'>other</span> <span m='216070'>than</span> <span m='216550'>you</span>
  <span m='216670'>saw it</span> <span m='216850'>yesterday</span> <span m='217180'>in</span>
  <span m='217270'>recitation?</span> </p><p><span m='218800'>[LAUGHTER]</span> </p><p><span
  m='219730'>I</span> <span m='219820'>mean</span> <span m='219940'>that's</span>
  <span m='220120'>a</span> <span m='220180'>good</span> <span m='220330'>reason.</span>
  <span m='223500'>Yeah.</span> </p><p><span m='224650'>AUDIENCE:</span> <span m='225105'>It</span>
  <span m='225560'>can no longer</span> <span m='226015'>go through</span> <span m='226470'>the
  axis</span> <span m='227380'>below</span> <span m='227835'>omega.</span> <span m='229612'>The</span>
  <span m='230110'>magnitude of the</span> <span m='230410'>zero</span> <span m='230893'>divided</span>
  <span m='231376'>by the magnitude</span> <span m='231859'>of the pole</span> <span
  m='232342'>is</span> <span m='232825'>pretty large.</span> <span m='233308'>And</span>
  <span m='233791'>then</span> <span m='234274'>as you go</span> <span m='234757'>to
  infinite</span> <span m='235240'>omega,</span> <span m='235723'>it</span> <span
  m='236206'>goes to</span> <span m='236689'>1.</span> <span m='237172'>So</span>
  <span m='237655'>I think it's</span> <span m='238138'>going to pass.</span> </p><p><span
  m='238621'>DENNIS FREEMAN:</span> <span m='239120'>So</span> <span m='239290'>I'm</span>
  <span m='239350'>a</span> <span m='239380'>little</span> <span m='239530'>bothered</span>
  <span m='239830'>by</span> <span m='239980'>infinite</span> <span m='240460'>omega.</span>
  <span m='241300'>Where</span> <span m='241900'>should</span> <span m='242080'>we</span>
  <span m='242230'>be--</span> <span m='243640'>when</span> <span m='243790'>we</span>
  <span m='243880'>think</span> <span m='244030'>about</span> <span m='244240'>things</span>
  <span m='244450'>as</span> <span m='244570'>low</span> <span m='244720'>pass,</span>
  <span m='244960'>high</span> <span m='245070'>pass,</span> <span m='245440'>whatever,</span>
  <span m='246310'>what</span> <span m='246520'>are</span> <span m='246580'>we</span>
  <span m='246700'>thinking</span> <span m='247030'>about</span> <span m='247420'>when</span>
  <span m='247600'>we</span> <span m='247690'>say</span> <span m='247870'>something
  is</span> <span m='248230'>a</span> <span m='248290'>low</span> <span m='248440'>pass</span>
  <span m='248650'>filter?</span> <span m='251830'>So</span> <span m='252030'>somebody</span>
  <span m='252480'>says</span> <span m='252960'>this.</span> <span m='253310'>So</span>
  <span m='253470'>what's</span> <span m='253650'>that</span> <span m='253770'>mean?</span>
  <span m='254100'>That's</span> <span m='254250'>correct.</span> </p><p><span m='256140'>So</span>
  <span m='256740'>a</span> <span m='256800'>large</span> <span m='257160'>fraction</span>
  <span m='257560'>of</span> <span m='257620'>this</span> <span m='257750'>class</span>
  <span m='258040'>is</span> <span m='258149'>learning</span> <span m='258390'>to</span>
  <span m='258480'>interpret</span> <span m='258899'>sign</span> <span m='259170'>language</span>
  <span m='259500'>in</span> <span m='259589'>the</span> <span m='259709'>air.</span>
  <span m='260370'>And</span> <span m='260640'>so</span> <span m='261570'>what's</span>
  <span m='261839'>it</span> <span m='261930'>mean</span> <span m='262260'>if</span>
  <span m='262440'>a</span> <span m='262530'>system</span> <span m='263040'>is</span>
  <span m='263400'>low</span> <span m='263700'>pass?</span> <span m='265610'>What</span>
  <span m='265980'>do</span> <span m='266100'>I</span> <span m='266190'>look</span>
  <span m='266370'>for</span> <span m='266610'>when</span> <span m='266730'>I</span>
  <span m='266820'>look</span> <span m='266940'>at</span> <span m='267030'>this</span>
  <span m='267180'>diagram</span> <span m='268350'>to</span> <span m='268440'>see</span>
  <span m='268620'>that</span> <span m='268740'>something's</span> <span m='269130'>low</span>
  <span m='269280'>pass?</span> </p><p><span m='272366'>AUDIENCE:</span> <span m='272822'>Look</span>
  <span m='273278'>for lower</span> <span m='273734'>frequencies.</span> </p><p><span
  m='274190'>DENNIS FREEMAN:</span> <span m='274650'>Where is</span> <span m='274890'>low</span>
  <span m='275080'>frequencies</span> <span m='275670'>on</span> <span m='275760'>this</span>
  <span m='275880'>diagram?</span> </p><p><span m='277302'>AUDIENCE:</span> <span
  m='277773'>If you</span> <span m='278244'>cut in half--</span> </p><p><span m='279186'>DENNIS
  FREEMAN:</span> <span m='279660'>Cut it</span> <span m='279910'>in</span> <span
  m='280090'>half,</span> <span m='282400'>top</span> <span m='282640'>and</span>
  <span m='282730'>bottom,</span> <span m='284746'>take</span> <span m='285230'>that</span>
  <span m='285520'>side.</span> </p><p><span m='286397'>[LAUGHTER]</span> </p><p><span
  m='287830'>So</span> <span m='288700'>low</span> <span m='288970'>frequencies</span>
  <span m='289510'>are</span> <span m='289630'>there.</span> <span m='291610'>So</span>
  <span m='291790'>we're</span> <span m='291940'>thinking</span> <span m='292330'>about</span>
  <span m='293560'>frequencies</span> <span m='294100'>being</span> <span m='296020'>e</span>
  <span m='296280'>to</span> <span m='296590'>the</span> <span m='296710'>j</span>
  <span m='297070'>omega,</span> <span m='298510'>because</span> <span m='298870'>what</span>
  <span m='298950'>we're</span> <span m='299140'>thinking</span> <span m='299395'>of</span>
  <span m='299650'>or</span> <span m='299740'>thinking</span> <span m='300010'>about,</span>
  <span m='300490'>we'd</span> <span m='300640'>like</span> <span m='300820'>to</span>
  <span m='300910'>think</span> <span m='301090'>about</span> <span m='301370'>cosine</span>
  <span m='302050'>of</span> <span m='302200'>omega</span> <span m='302590'>n.</span>
  <span m='303460'>But</span> <span m='303550'>we</span> <span m='303640'>want</span>
  <span m='303790'>to</span> <span m='303850'>make</span> <span m='304010'>that</span>
  <span m='304120'>look</span> <span m='304300'>like</span> <span m='304450'>an</span>
  <span m='304570'>eigenfunction.</span> <span m='305650'>So</span> <span m='305830'>we</span>
  <span m='305890'>want</span> <span m='306010'>to</span> <span m='306070'>make</span>
  <span m='306220'>that</span> <span m='306370'>look</span> <span m='306520'>like</span>
  <span m='306780'>e to</span> <span m='307070'>the</span> <span m='307210'>j</span>
  <span m='307540'>omega</span> <span m='307930'>n</span> <span m='309280'>plus</span>
  <span m='309930'>e to</span> <span m='310150'>the</span> <span m='310240'>minus</span>
  <span m='310540'>j omega</span> <span m='310990'>n,</span> <span m='311260'>that</span>
  <span m='311350'>kind</span> <span m='311530'>of</span> <span m='311620'>thing--</span>
  <span m='316464'>then</span> <span m='316930'>divide</span> <span m='317170'>by</span>
  <span m='317350'>1/2</span> <span m='317590'>probably.</span> <span m='323590'>So</span>
  <span m='323860'>the</span> <span m='324070'>question</span> <span m='324490'>is--</span>
  <span m='324600'>so</span> <span m='324750'>this</span> <span m='324970'>is</span>
  <span m='325120'>all</span> <span m='325300'>pass.</span> <span m='325820'>And</span>
  <span m='325920'>that's</span> <span m='325990'>actually</span> <span m='326260'>kind</span>
  <span m='326470'>of</span> <span m='326560'>tricky,</span> <span m='327220'>if</span>
  <span m='327370'>you</span> <span m='327490'>think</span> <span m='327640'>about</span>
  <span m='327970'>how</span> <span m='328210'>it</span> <span m='328270'>would</span>
  <span m='328420'>become</span> <span m='328750'>that</span> <span m='328870'>way.</span>
  <span m='329020'>Yes.</span> </p><p><span m='329838'>AUDIENCE:</span> <span m='330316'>[INAUDIBLE]</span>
  <span m='330794'>at</span> <span m='331272'>any</span> <span m='331750'>point on
  the</span> <span m='332228'>unit circle--</span> </p><p><span m='332710'>DENNIS
  FREEMAN:</span> <span m='332835'>Yes.</span> </p><p><span m='332960'>AUDIENCE:</span>
  <span m='333206'>It</span> <span m='333452'>stems from the</span> <span m='333944'>[INAUDIBLE].</span>
  </p><p><span m='336896'>DENNIS FREEMAN:</span> <span m='337390'>That's</span> <span
  m='337660'>precisely</span> <span m='338200'>right.</span> <span m='338800'>So</span>
  <span m='338960'>somehow,</span> <span m='340870'>if</span> <span m='341050'>you</span>
  <span m='341140'>took</span> <span m='341440'>this</span> <span m='341770'>distance</span>
  <span m='342610'>and</span> <span m='342760'>that</span> <span m='343030'>distance,</span>
  <span m='344290'>which</span> <span m='344500'>is</span> <span m='344590'>intended</span>
  <span m='345040'>in</span> <span m='345160'>this</span> <span m='345310'>figure</span>
  <span m='345550'>not</span> <span m='345700'>to</span> <span m='345790'>look</span>
  <span m='345970'>the</span> <span m='346060'>same,</span> <span m='348010'>but</span>
  <span m='348160'>if</span> <span m='348280'>you</span> <span m='348340'>took</span>
  <span m='348550'>the</span> <span m='348670'>ratio--</span> <span m='349120'>because</span>
  <span m='349420'>this</span> <span m='349570'>one</span> <span m='349710'>is</span>
  <span m='349790'>a</span> <span m='349840'>zero,</span> <span m='350200'>so</span>
  <span m='350290'>it's</span> <span m='350410'>in</span> <span m='350500'>the</span>
  <span m='350590'>top,</span> <span m='350830'>and</span> <span m='350920'>this</span>
  <span m='351030'>one</span> <span m='351120'>is</span> <span m='351280'>a</span>
  <span m='351520'>pole, so</span> <span m='351840'>it's</span> <span m='351970'>in</span>
  <span m='352060'>the</span> <span m='352150'>bottom--</span> <span m='352550'>and</span>
  <span m='352650'>if</span> <span m='352750'>you</span> <span m='352850'>took</span>
  <span m='352950'>that</span> <span m='352960'>ratio,</span> <span m='353650'>somehow</span>
  <span m='354550'>if</span> <span m='354670'>you</span> <span m='354760'>took</span>
  <span m='354940'>that</span> <span m='355240'>ratio</span> <span m='355960'>divided</span>
  <span m='356320'>by</span> <span m='356410'>that</span> <span m='356620'>ratio</span>
  <span m='357190'>and</span> <span m='357340'>compared</span> <span m='357730'>it</span>
  <span m='357820'>to</span> <span m='357970'>this</span> <span m='358270'>one</span>
  <span m='358450'>divided</span> <span m='358750'>by</span> <span m='358870'>that</span>
  <span m='359050'>one,</span> <span m='360400'>those</span> <span m='360640'>numbers</span>
  <span m='360970'>would</span> <span m='361090'>be</span> <span m='361210'>the</span>
  <span m='361330'>same</span> <span m='361570'>thing.</span> <span m='363590'>That's</span>
  <span m='363730'>what</span> <span m='363880'>would</span> <span m='364435'>have</span>
  <span m='364840'>to</span> <span m='364960'>happen.</span> </p><p><span m='366280'>You</span>
  <span m='366430'>would</span> <span m='366580'>compute</span> <span m='368110'>the</span>
  <span m='368200'>magnitude</span> <span m='368650'>of</span> <span m='368710'>the</span>
  <span m='368770'>frequency</span> <span m='369130'>response</span> <span m='369550'>by</span>
  <span m='369790'>taking</span> <span m='370330'>the</span> <span m='370510'>ratio</span>
  <span m='371230'>of</span> <span m='373360'>the</span> <span m='373510'>magnitudes</span>
  <span m='373980'>of the</span> <span m='374080'>vectors</span> <span m='375460'>that</span>
  <span m='375550'>connect</span> <span m='376030'>the</span> <span m='376180'>zero</span>
  <span m='376600'>to</span> <span m='376720'>the</span> <span m='376840'>point</span>
  <span m='377020'>of</span> <span m='377110'>interest</span> <span m='377690'>and</span>
  <span m='377700'>the</span> <span m='377800'>pole</span> <span m='378100'>to</span>
  <span m='378220'>the</span> <span m='378310'>point</span> <span m='378520'>of</span>
  <span m='378610'>interest--</span> <span m='378970'>the</span> <span m='379090'>point</span>
  <span m='379270'>of</span> <span m='379360'>interest</span> <span m='379720'>being</span>
  <span m='379990'>on</span> <span m='380110'>the</span> <span m='380200'>unit</span>
  <span m='380410'>circle.</span> <span m='383520'>It's</span> <span m='383670'>not</span>
  <span m='383850'>at</span> <span m='383940'>all</span> <span m='384120'>obvious</span>
  <span m='384540'>to</span> <span m='384660'>me</span> <span m='386220'>that</span>
  <span m='386430'>that</span> <span m='386610'>ratio</span> <span m='387060'>is</span>
  <span m='387150'>a</span> <span m='387210'>constant,</span> <span m='387720'>if</span>
  <span m='387840'>you</span> <span m='387900'>move</span> <span m='388340'>along</span>
  <span m='388650'>a</span> <span m='388710'>circle.</span> <span m='389040'>That's</span>
  <span m='389220'>another</span> <span m='389460'>one</span> <span m='389580'>of</span>
  <span m='389640'>those</span> <span m='389820'>things</span> <span m='390090'>that</span>
  <span m='390210'>I</span> <span m='390300'>think</span> <span m='390480'>I</span>
  <span m='390570'>need</span> <span m='390800'>Greek</span> <span m='391800'>to</span>
  <span m='391980'>convince</span> <span m='392310'>me.</span> </p><p><span m='392580'>AUDIENCE:</span>
  <span m='392812'>[INAUDIBLE]</span> <span m='393045'>because he</span> <span m='393510'>figured</span>
  <span m='393975'>it out.</span> </p><p><span m='394540'>DENNIS FREEMAN:</span> <span
  m='394780'>Oh,</span> <span m='395180'>somebody</span> <span m='395460'>knows.</span>
  </p><p><span m='395880'>AUDIENCE:</span> <span m='396090'>Yeah,</span> <span m='396300'>the
  guy</span> <span m='396720'>[INAUDIBLE].</span> </p><p><span m='397980'>DENNIS FREEMAN:</span>
  <span m='398400'>Wonderful.</span> <span m='399180'>So</span> <span m='399330'>you</span>
  <span m='399480'>should</span> <span m='399600'>explain</span> <span m='399990'>it</span>
  <span m='400080'>to</span> <span m='400170'>me.</span> <span m='400560'>[LAUGHS]</span>
  </p><p><span m='401022'>AUDIENCE:</span> <span m='401484'>He</span> <span m='401946'>explained
  it</span> <span m='402408'>to me.</span> </p><p><span m='402870'>DENNIS FREEMAN:</span>
  <span m='403332'>[LAUGHS]</span> <span m='404720'>Putting</span> <span m='404940'>you</span>
  <span m='405060'>on</span> <span m='405180'>the</span> <span m='405300'>spot.</span>
  </p><p><span m='405585'>AUDIENCE:</span> <span m='405870'>Like</span> <span m='406326'>right</span>
  <span m='406782'>now?</span> </p><p><span m='407240'>DENNIS FREEMAN:</span> <span
  m='407330'>Oh,</span> <span m='407420'>that's</span> <span m='407850'>OK.</span>
  <span m='409140'>If</span> <span m='409290'>you</span> <span m='409380'>want</span>
  <span m='409590'>to,</span> <span m='409860'>that's</span> <span m='410070'>fine.</span>
  </p><p><span m='412820'>AUDIENCE:</span> <span m='413310'>[INAUDIBLE]</span> <span
  m='415270'>So if</span> <span m='415760'>you</span> <span m='416260'>have any</span>
  <span m='416390'>point on</span> <span m='416843'>the unit</span> <span m='417296'>circle?</span>
  </p><p><span m='417750'>DENNIS FREEMAN:</span> <span m='417835'>Yeah.</span> </p><p><span
  m='417920'>AUDIENCE:</span> <span m='418165'>You</span> <span m='418411'>draw like</span>
  <span m='418902'>a line</span> <span m='419393'>from that</span> <span m='419884'>point</span>
  <span m='420375'>to the</span> <span m='420870'>origin.</span> </p><p><span m='421936'>DENNIS
  FREEMAN:</span> <span m='422374'>So</span> <span m='422812'>if you</span> <span
  m='423250'>have any</span> <span m='423430'>point</span> <span m='423858'>on the
  unit</span> <span m='424286'>circle,</span> <span m='426720'>say</span> <span m='427060'>that
  one--</span> </p><p><span m='427555'>AUDIENCE:</span> <span m='428050'>So you</span>
  <span m='428545'>draw</span> <span m='429040'>a line</span> <span m='429300'>halfway--</span>
  <span m='430232'>could you do it</span> <span m='430698'>on the other side,</span>
  <span m='431164'>on</span> <span m='431630'>that side</span> <span m='432100'>[INAUDIBLE].</span>
  </p><p><span m='432320'>DENNIS FREEMAN:</span> <span m='432483'>So</span> <span
  m='432646'>you</span> <span m='432810'>like this side</span> <span m='433300'>better,</span>
  <span m='433790'>OK.</span> </p><p><span m='434180'>AUDIENCE:</span> <span m='434343'>So</span>
  <span m='434506'>you</span> <span m='434671'>draw a line</span> <span m='435162'>from
  that point</span> <span m='435653'>to the</span> <span m='436144'>origin.</span>
  <span m='437930'>[INAUDIBLE]</span> <span m='438390'>1 over</span> <span m='438850'>a</span>
  <span m='439310'>and</span> <span m='439770'>a</span> <span m='440230'>on the</span>
  <span m='440690'>x-axis.</span> </p><p><span m='441120'>DENNIS FREEMAN:</span> <span
  m='441260'>So</span> <span m='441400'>1 over</span> <span m='441680'>a</span> <span
  m='441970'>and</span> <span m='443520'>a.</span> </p><p><span m='443950'>AUDIENCE:</span>
  <span m='444103'>And</span> <span m='444256'>draw</span> <span m='444410'>set of</span>
  <span m='444870'>lines</span> <span m='445330'>from those</span> <span m='445790'>to
  the</span> <span m='446250'>point</span> <span m='446710'>of</span> <span m='447170'>[INAUDIBLE].</span>
  </p><p><span m='447320'>DENNIS FREEMAN:</span> <span m='447495'>Up</span> <span
  m='447670'>here?</span> </p><p><span m='447990'>AUDIENCE:</span> <span m='448190'>Yeah.</span>
  <span m='449590'>So</span> <span m='449740'>now</span> <span m='450025'>like you
  have</span> <span m='450310'>two</span> <span m='450550'>triangles</span> <span
  m='450860'>that</span> <span m='451170'>have</span> <span m='451480'>the</span>
  <span m='451780'>same</span> <span m='452360'>side</span> <span m='452855'>and</span>
  <span m='453140'>the</span> <span m='453390'>same</span> <span m='453530'>angle.</span>
  <span m='454883'>And</span> <span m='455785'>if you just</span> <span m='456236'>use
  the</span> <span m='456687'>law of</span> <span m='457140'>cosines--</span> </p><p><span
  m='457753'>DENNIS FREEMAN:</span> <span m='458166'>You have</span> <span m='458580'>two--</span>
  </p><p><span m='459510'>AUDIENCE:</span> <span m='459902'>So</span> <span m='460294'>you
  have</span> <span m='460686'>a</span> <span m='461080'>big</span> <span m='461345'>triangle</span>
  <span m='461610'>and</span> <span m='461980'>a</span> <span m='462350'>small triangle.</span>
  </p><p><span m='462720'>DENNIS FREEMAN:</span> <span m='462763'>So</span> <span
  m='462806'>we</span> <span m='462850'>have</span> <span m='463010'>this</span> <span
  m='463190'>triangle</span> <span m='463570'>and</span> <span m='463680'>we</span>
  <span m='463760'>have</span> <span m='463940'>this</span> <span m='464160'>triangle.</span>
  <span m='465220'>Those are</span> <span m='465660'>the two</span> <span m='465920'>you</span>
  <span m='466030'>want?</span> </p><p><span m='466415'>AUDIENCE:</span> <span m='466607'>And</span>
  <span m='466800'>yeah.</span> <span m='467020'>So</span> <span m='467474'>like</span>
  <span m='467928'>they have--</span> <span m='469290'>the</span> <span m='469744'>line</span>
  <span m='470350'>of</span> <span m='470836'>the leftmost</span> <span m='471322'>is</span>
  <span m='471808'>like the</span> <span m='472294'>same</span> <span m='472780'>for
  both.</span> <span m='473266'>And the</span> <span m='473752'>angle</span> <span
  m='474238'>at</span> <span m='474724'>the</span> <span m='475210'>center is the</span>
  <span m='475696'>same</span> <span m='476182'>for both.</span> </p><p><span m='477154'>DENNIS
  FREEMAN:</span> <span m='477640'>So</span> <span m='478130'>this angle</span> <span
  m='478310'>is equal</span> <span m='478740'>to this</span> <span m='478880'>angle?</span>
  </p><p><span m='479376'>AUDIENCE:</span> <span m='479624'>No.</span> </p><p><span
  m='479872'>AUDIENCE:</span> <span m='480368'>The central</span> <span m='480864'>angle.</span>
  <span m='481360'>The central</span> <span m='481510'>angle</span> <span m='481920'>with
  the--</span> </p><p><span m='483150'>AUDIENCE:</span> <span m='483560'>You take</span>
  <span m='483770'>the</span> <span m='484230'>whole be</span> <span m='484420'>triangle</span>
  <span m='484841'>and--</span> </p><p><span m='486104'>DENNIS FREEMAN:</span> <span
  m='486525'>Take</span> <span m='486950'>the</span> <span m='487240'>big</span> <span
  m='487480'>triangle--</span> </p><p><span m='487900'>AUDIENCE:</span> <span m='488114'>And</span>
  <span m='488328'>the origin.</span> </p><p><span m='488756'>AUDIENCE:</span> <span
  m='488970'>And</span> <span m='489184'>then</span> <span m='489612'>the one</span>
  <span m='490040'>you</span> <span m='490250'>just--</span> </p><p><span m='490580'>AUDIENCE:</span>
  <span m='490651'>The</span> <span m='490722'>angle</span> <span m='490793'>at</span>
  <span m='490864'>the</span> <span m='490935'>origin.</span> </p><p><span m='491434'>DENNIS
  FREEMAN:</span> <span m='491861'>And the</span> <span m='492290'>angle at the</span>
  <span m='492730'>origin.</span> </p><p><span m='495083'>AUDIENCE:</span> <span m='495574'>Yes,</span>
  <span m='496065'>that one.</span> </p><p><span m='496556'>AUDIENCE:</span> <span
  m='497047'>So</span> <span m='497540'>that angle</span> <span m='497880'>is in</span>
  <span m='498135'>both the</span> <span m='498390'>big</span> <span m='498710'>triangle
  and</span> <span m='499205'>the little one.</span> </p><p><span m='499700'>DENNIS
  FREEMAN:</span> <span m='499770'>That</span> <span m='499840'>angle</span> <span
  m='499910'>is in the</span> <span m='500100'>big</span> <span m='500290'>triangle</span>
  <span m='500750'>and</span> <span m='500960'>the little one?</span> <span m='501250'>Yes!</span>
  </p><p><span m='502080'>[LAUGHTER]</span> </p><p><span m='503040'>Got</span> <span
  m='503460'>it!</span> </p><p><span m='504470'>AUDIENCE:</span> <span m='504870'>And</span>
  <span m='505160'>the</span> <span m='505450'>size</span> <span m='505930'>of the</span>
  <span m='506412'>bottom are</span> <span m='506894'>like</span> <span m='507376'>1/a
  and a</span> <span m='507858'>for the</span> <span m='508340'>two</span> <span m='508822'>triangles.</span>
  </p><p><span m='509304'>DENNIS FREEMAN:</span> <span m='509790'>Yeah.</span> </p><p><span
  m='510070'>AUDIENCE:</span> <span m='510285'>So</span> <span m='510500'>you</span>
  <span m='510930'>just</span> <span m='511360'>use the</span> <span m='511790'>law
  of</span> <span m='512220'>cosines</span> <span m='512650'>and--</span> </p><p><span
  m='513080'>DENNIS FREEMAN:</span> <span m='513230'>That's</span> <span m='513380'>very</span>
  <span m='513620'>good.</span> </p><p><span m='513860'>AUDIENCE:</span> <span m='514092'>Isn't</span>
  <span m='514325'>that pretty?</span> </p><p><span m='514790'>DENNIS FREEMAN:</span>
  <span m='515255'>What was</span> <span m='515720'>that?</span> </p><p><span m='516185'>AUDIENCE:</span>
  <span m='516340'>Isn't</span> <span m='516495'>that</span> <span m='516650'>pretty?</span>
  </p><p><span m='517120'>DENNIS FREEMAN:</span> <span m='517317'>That's</span> <span
  m='517909'>amazing.</span> <span m='520730'>So</span> <span m='521270'>wonderful.</span>
  <span m='522049'>Congratulations.</span> </p><p><span m='522514'>[APPLAUSE]</span>
  </p><p><span m='526740'>So</span> <span m='527150'>you're</span> <span m='527330'>also</span>
  <span m='527600'>working</span> <span m='527870'>on</span> <span m='527960'>the</span>
  <span m='528050'>triangle</span> <span m='528440'>thing?</span> <span m='529940'>Don't</span>
  <span m='530120'>have</span> <span m='530240'>that</span> <span m='530360'>yet.</span>
  <span m='530580'>OK.</span> <span m='532100'>I'll</span> <span m='532220'>keep</span>
  <span m='532430'>checking</span> <span m='532930'>in.</span> <span m='533810'>So</span>
  <span m='534200'>the</span> <span m='534320'>way</span> <span m='535250'>people</span>
  <span m='535610'>who</span> <span m='535730'>don't</span> <span m='535940'>do</span>
  <span m='536120'>quite</span> <span m='536360'>so</span> <span m='536510'>well</span>
  <span m='536690'>in trig</span> <span m='537080'>do</span> <span m='537290'>it,</span>
  <span m='539030'>so</span> <span m='539180'>you</span> <span m='539360'>can</span>
  <span m='539480'>also</span> <span m='540230'>just</span> <span m='541400'>empty-headedly</span>
  <span m='542240'>substitute</span> <span m='542850'>z</span> <span m='543620'>equals</span>
  <span m='543950'>e to</span> <span m='544160'>the</span> <span m='544310'>j</span>
  <span m='544650'>omega.</span> <span m='547180'>And</span> <span m='547330'>then</span>
  <span m='547480'>if</span> <span m='547600'>you</span> <span m='547660'>want</span>
  <span m='547780'>to</span> <span m='547840'>make</span> <span m='548020'>the</span>
  <span m='548110'>top</span> <span m='548440'>look</span> <span m='548590'>a</span>
  <span m='548650'>little</span> <span m='548860'>bit</span> <span m='548980'>more</span>
  <span m='549160'>like</span> <span m='549370'>the</span> <span m='549460'>bottom,</span>
  <span m='550420'>you</span> <span m='550570'>could</span> <span m='550690'>take</span>
  <span m='551050'>out</span> <span m='551800'>the</span> <span m='552010'>e to</span>
  <span m='552270'>the</span> <span m='552370'>j</span> <span m='552560'>omega</span>
  <span m='552850'>part.</span> <span m='555980'>And</span> <span m='556130'>then</span>
  <span m='556310'>you</span> <span m='556400'>see</span> <span m='556640'>that</span>
  <span m='556790'>these</span> <span m='557030'>look</span> <span m='557180'>like</span>
  <span m='557300'>complex</span> <span m='557720'>conjugates.</span> </p><p><span
  m='561520'>So</span> <span m='561640'>this</span> <span m='561820'>is</span> <span
  m='561910'>kind</span> <span m='562090'>of</span> <span m='562180'>the</span> <span
  m='562270'>math</span> <span m='562525'>way.</span> <span m='562780'>And</span>
  <span m='563110'>what</span> <span m='563230'>you</span> <span m='563380'>said</span>
  <span m='563560'>was</span> <span m='563770'>the trig</span> <span m='564040'>way.</span>
  <span m='564220'>I</span> <span m='564310'>like</span> <span m='564460'>the</span>
  <span m='564550'>trig</span> <span m='564730'>way</span> <span m='564850'>much</span>
  <span m='565060'>better,</span> <span m='565825'>the</span> <span m='566320'>[INAUDIBLE]</span>
  <span m='566710'>way,</span> <span m='567160'>yes.</span> <span m='568480'>So</span>
  <span m='569220'>complex</span> <span m='569640'>conjugates,</span> <span m='570060'>same</span>
  <span m='570280'>magnitude</span> <span m='570760'>done.</span> </p><p><span m='572320'>So</span>
  <span m='572500'>the</span> <span m='572560'>whole</span> <span m='572740'>point</span>
  <span m='573060'>was</span> <span m='573250'>just</span> <span m='573430'>to</span>
  <span m='573520'>motivate</span> <span m='573880'>the</span> <span m='574030'>idea</span>
  <span m='574790'>of</span> <span m='574990'>thinking</span> <span m='575380'>about</span>
  <span m='575580'>an</span> <span m='575680'>all</span> <span m='575800'>pass.</span>
  <span m='576170'>Why</span> <span m='576220'>would</span> <span m='576340'>you</span>
  <span m='576460'>build</span> <span m='576680'>an</span> <span m='576790'>all</span>
  <span m='576970'>pass?</span> <span m='579260'>What's</span> <span m='579430'>an</span>
  <span m='579500'>all</span> <span m='579610'>pass</span> <span m='579890'>good</span>
  <span m='580040'>for?</span> <span m='583669'>It's</span> <span m='584160'>6.003</span>
  <span m='584960'>exercises,</span> <span m='585560'>of</span> <span m='585650'>course.</span>
  <span m='588260'>So</span> <span m='588530'>an</span> <span m='588650'>all</span>
  <span m='588770'>pass</span> <span m='589040'>doesn't</span> <span m='589250'>change</span>
  <span m='589550'>the</span> <span m='589880'>magnitudes.</span> <span m='590185'>So</span>
  <span m='590490'>what's</span> <span m='590600'>it</span> <span m='590700'>good</span>
  <span m='590840'>for?</span> </p><p><span m='591517'>AUDIENCE:</span> <span m='591894'>Changes
  the</span> <span m='592271'>phase.</span> </p><p><span m='592650'>DENNIS FREEMAN:</span>
  <span m='592855'>Changes</span> <span m='593060'>the</span> <span m='593150'>phase.</span>
  <span m='593840'>So</span> <span m='594560'>if</span> <span m='594740'>you</span>
  <span m='594860'>were</span> <span m='594980'>to</span> <span m='595070'>think</span>
  <span m='595280'>about</span> <span m='595550'>what's</span> <span m='595820'>the</span>
  <span m='595970'>phase</span> <span m='596410'>of</span> <span m='596480'>the</span>
  <span m='596630'>all</span> <span m='596810'>pass,</span> <span m='598730'>you</span>
  <span m='598910'>get</span> <span m='599600'>a</span> <span m='599660'>function</span>
  <span m='600530'>that</span> <span m='600710'>depends</span> <span m='601280'>differently.</span>
  <span m='603770'>So</span> <span m='603950'>you</span> <span m='604040'>have</span>
  <span m='604160'>to</span> <span m='604250'>compute</span> <span m='604610'>the</span>
  <span m='604820'>angles</span> <span m='605420'>of</span> <span m='605570'>these</span>
  <span m='605780'>vectors.</span> <span m='606500'>So</span> <span m='606650'>this</span>
  <span m='606860'>one--</span> <span m='607310'>the</span> <span m='607490'>angle</span>
  <span m='607890'>at</span> <span m='608030'>the</span> <span m='608120'>zero</span>
  <span m='608450'>starts</span> <span m='608720'>out</span> <span m='608880'>at</span>
  <span m='608990'>pi.</span> <span m='610550'>The</span> <span m='610730'>angle</span>
  <span m='611030'>associated</span> <span m='611510'>with</span> <span m='611620'>the</span>
  <span m='611670'>pole</span> <span m='611960'>starts</span> <span m='612230'>out</span>
  <span m='612380'>at</span> <span m='612440'>zero.</span> </p><p><span m='614690'>There's</span>
  <span m='614870'>actually</span> <span m='615200'>a</span> <span m='615260'>minus</span>
  <span m='615650'>sign in</span> <span m='616040'>here,</span> <span m='616820'>because</span>
  <span m='617150'>I</span> <span m='617300'>took</span> <span m='617840'>1</span>
  <span m='618110'>minus</span> <span m='618470'>z</span> <span m='618710'>compared
  to</span> <span m='619100'>z</span> <span m='619370'>minus</span> <span m='619710'>a.</span>
  <span m='620840'>So</span> <span m='620930'>I</span> <span m='620960'>put</span>
  <span m='621140'>the</span> <span m='621230'>z</span> <span m='621420'>at</span>
  <span m='621470'>the</span> <span m='621590'>two</span> <span m='621740'>places.</span>
  <span m='622160'>So</span> <span m='622370'>there's</span> <span m='622820'>a</span>
  <span m='622910'>net</span> <span m='623210'>minus</span> <span m='623570'>sign</span>
  <span m='623840'>in</span> <span m='623930'>the</span> <span m='624020'>whole</span>
  <span m='624200'>transfer</span> <span m='624590'>function.</span> <span m='625560'>So</span>
  <span m='625640'>the</span> <span m='625730'>pi</span> <span m='626090'>cancels</span>
  <span m='626380'>out</span> <span m='626630'>the</span> <span m='626720'>pi.</span>
  <span m='627050'>So</span> <span m='627200'>we</span> <span m='627320'>start</span>
  <span m='627560'>at</span> <span m='627680'>zero</span> <span m='628100'>at</span>
  <span m='628250'>zero.</span> </p><p><span m='629840'>Everybody</span> <span m='630180'>know</span>
  <span m='630350'>what</span> <span m='630470'>I</span> <span m='630530'>just</span>
  <span m='630680'>said?</span> <span m='633860'>So</span> <span m='634560'>the</span>
  <span m='635030'>angle</span> <span m='635420'>associated</span> <span m='635990'>with</span>
  <span m='636170'>the</span> <span m='636240'>zero</span> <span m='636680'>is</span>
  <span m='636800'>pi.</span> <span m='638420'>But</span> <span m='638630'>there's</span>
  <span m='638840'>also</span> <span m='639850'>a</span> <span m='639950'>negative</span>
  <span m='640400'>sign</span> <span m='640730'>associated</span> <span m='641300'>with</span>
  <span m='641510'>the</span> <span m='643970'>transfer</span> <span m='644390'>function,</span>
  <span m='645050'>because</span> <span m='645320'>we</span> <span m='645440'>would</span>
  <span m='645560'>normally</span> <span m='645920'>like</span> <span m='646100'>to</span>
  <span m='646240'>write</span> <span m='647780'>z</span> <span m='648470'>minus</span>
  <span m='648875'>a</span> <span m='649280'>0</span> <span m='651260'>divided</span>
  <span m='651590'>by</span> <span m='651740'>z</span> <span m='651980'>minus a</span>
  <span m='652330'>pole.</span> <span m='655280'>And</span> <span m='655430'>I</span>
  <span m='655520'>didn't</span> <span m='655700'>write</span> <span m='655880'>it</span>
  <span m='655970'>that</span> <span m='656090'>way.</span> <span m='658070'>The</span>
  <span m='658190'>top</span> <span m='658460'>one,</span> <span m='658610'>I</span>
  <span m='658700'>wrote</span> <span m='658910'>backwards.</span> </p><p><span m='661730'>So</span>
  <span m='661880'>there's</span> <span m='662060'>a</span> <span m='662150'>net</span>
  <span m='662420'>minus</span> <span m='662780'>sign.</span> <span m='663790'>Because</span>
  <span m='664150'>of</span> <span m='664310'>the</span> <span m='664490'>minus</span>
  <span m='664820'>sign,</span> <span m='665500'>the</span> <span m='665600'>phase</span>
  <span m='665870'>starts</span> <span m='666170'>out</span> <span m='666350'>at</span>
  <span m='666410'>zero</span> <span m='668090'>instead</span> <span m='668480'>of</span>
  <span m='668630'>pi.</span> <span m='669230'>That's</span> <span m='669410'>how</span>
  <span m='669530'>that</span> <span m='669680'>got</span> <span m='669860'>to</span>
  <span m='669940'>be</span> <span m='670040'>zero.</span> </p><p><span m='670910'>So</span>
  <span m='671060'>this</span> <span m='671300'>starts</span> <span m='671660'>out</span>
  <span m='671810'>at</span> <span m='671870'>pi--</span> <span m='673520'>the</span>
  <span m='673610'>angle</span> <span m='673880'>starts</span> <span m='674150'>out</span>
  <span m='674300'>at</span> <span m='674360'>pi.</span> <span m='674810'>It becomes</span>
  <span m='675250'>less,</span> <span m='676490'>and</span> <span m='676610'>then</span>
  <span m='676760'>it</span> <span m='676850'>goes</span> <span m='677150'>back</span>
  <span m='678020'>to</span> <span m='678140'>being</span> <span m='678380'>pi.</span>
  <span m='679820'>But</span> <span m='679970'>the</span> <span m='680090'>angle</span>
  <span m='680390'>associated</span> <span m='680960'>with</span> <span m='681230'>the</span>
  <span m='681800'>pole</span> <span m='682700'>starts</span> <span m='683030'>at</span>
  <span m='683090'>zero</span> <span m='683510'>and</span> <span m='683600'>goes</span>
  <span m='683780'>around</span> <span m='683990'>the</span> <span m='684080'>pi.</span>
  </p><p><span m='685580'>So</span> <span m='685760'>the</span> <span m='685910'>net</span>
  <span m='686165'>from</span> <span m='686420'>the</span> <span m='686510'>pole</span>
  <span m='687470'>is</span> <span m='687740'>a</span> <span m='687800'>pi</span>
  <span m='688070'>shift,</span> <span m='688850'>which</span> <span m='689090'>accounts</span>
  <span m='689450'>for</span> <span m='689600'>why</span> <span m='689810'>this</span>
  <span m='689990'>goes</span> <span m='690230'>from</span> <span m='690380'>0</span>
  <span m='690740'>to</span> <span m='690890'>minus</span> <span m='691220'>pi.</span>
  <span m='693530'>You</span> <span m='693670'>can all</span> <span m='693890'>do</span>
  <span m='694040'>that,</span> <span m='694190'>right?</span> <span m='696530'>So</span>
  <span m='697070'>the</span> <span m='697280'>idea</span> <span m='697700'>is</span>
  <span m='698030'>that</span> <span m='698210'>the</span> <span m='698390'>all</span>
  <span m='698540'>pass</span> <span m='698900'>would</span> <span m='699140'>alter</span>
  <span m='699470'>the</span> <span m='699590'>phase.</span> <span m='700220'>And</span>
  <span m='700400'>that's</span> <span m='700640'>one</span> <span m='700820'>of</span>
  <span m='700910'>the</span> <span m='700970'>things</span> <span m='701210'>I</span>
  <span m='701250'>wanted</span> <span m='701390'>to</span> <span m='701510'>talk</span>
  <span m='701720'>about.</span> </p><p><span m='703100'>What's</span> <span m='703460'>the</span>
  <span m='703640'>effect</span> <span m='704030'>of</span> <span m='704150'>changing</span>
  <span m='704570'>the</span> <span m='704690'>phase?</span> <span m='705440'>And</span>
  <span m='705620'>I'll</span> <span m='705710'>do</span> <span m='705860'>a</span>
  <span m='705920'>demo</span> <span m='706220'>now,</span> <span m='706760'>thinking</span>
  <span m='707030'>about</span> <span m='707270'>how</span> <span m='707420'>it</span>
  <span m='707510'>affects</span> <span m='707840'>audio.</span> <span m='708380'>And</span>
  <span m='708470'>at</span> <span m='708560'>the</span> <span m='708650'>end</span>
  <span m='708800'>of</span> <span m='708860'>the</span> <span m='708950'>hour,</span>
  <span m='709190'>thinking</span> <span m='709400'>about</span> <span m='709610'>how</span>
  <span m='709730'>it</span> <span m='709820'>affects</span> <span m='710120'>video.</span>
  </p><p><span m='712040'>So</span> <span m='713470'>to</span> <span m='714250'>think</span>
  <span m='714440'>about</span> <span m='714680'>this,</span> <span m='714860'>I</span>
  <span m='714980'>took</span> <span m='715430'>this</span> <span m='715810'>fraction.</span>
  <span m='716240'>And</span> <span m='716360'>I</span> <span m='716450'>used</span>
  <span m='716810'>a</span> <span m='717260'>equals</span> <span m='718460'>0.95.</span>
  <span m='724490'>And</span> <span m='725540'>I</span> <span m='725720'>took</span>
  <span m='726230'>a</span> <span m='727070'>waveform</span> <span m='727680'>that</span>
  <span m='727820'>I</span> <span m='727910'>generated</span> <span m='728540'>with</span>
  <span m='728720'>Python.</span> <span m='729860'>I</span> <span m='729950'>just</span>
  <span m='730160'>added</span> <span m='730490'>together</span> <span m='730910'>three</span>
  <span m='731240'>tones</span> <span m='731690'>in</span> <span m='731780'>the</span>
  <span m='731840'>ratio</span> <span m='732290'>1,</span> <span m='732630'>3,</span>
  <span m='732900'>5</span> <span m='733310'>in</span> <span m='733430'>frequencies,</span>
  <span m='734030'>so</span> <span m='734090'>it</span> <span m='734200'>sounds</span>
  <span m='734480'>like</span> <span m='734570'>more</span> <span m='734730'>harmonic.</span>
  <span m='736370'>And</span> <span m='736940'>when</span> <span m='737180'>you</span>
  <span m='737300'>add</span> <span m='737480'>those</span> <span m='737750'>together,</span>
  <span m='738240'>you</span> <span m='738260'>get</span> <span m='738380'>a</span>
  <span m='738440'>sound</span> <span m='738830'>like</span> <span m='739010'>this.</span>
  </p><p><span m='739520'>[TONES PLAYING]</span> </p><p><span m='742160'>What</span>
  <span m='742430'>you</span> <span m='742550'>hear</span> <span m='743060'>is</span>
  <span m='743210'>a</span> <span m='743270'>very</span> <span m='743690'>dominant</span>
  <span m='744350'>tone--</span> <span m='744780'>a</span> <span m='745160'>very</span>
  <span m='745400'>dominant</span> <span m='745910'>pitch,</span> <span m='747200'>because</span>
  <span m='747560'>I</span> <span m='747650'>made</span> <span m='747890'>the</span>
  <span m='748010'>harmonics</span> <span m='748610'>be</span> <span m='750440'>integer</span>
  <span m='750830'>multiples.</span> <span m='751730'>So</span> <span m='751850'>I</span>
  <span m='752150'>made</span> <span m='752360'>the</span> <span m='752510'>overtones</span>
  <span m='752990'>be</span> <span m='753170'>integer</span> <span m='753560'>multiples</span>
  <span m='754070'>of</span> <span m='754190'>the</span> <span m='754280'>fundamental.</span>
  <span m='755750'>So</span> <span m='755930'>the</span> <span m='756050'>fundamental</span>
  <span m='756530'>was</span> <span m='756740'>at</span> <span m='756890'>8,440.</span>
  <span m='758420'>And</span> <span m='758540'>I</span> <span m='758630'>put</span>
  <span m='758820'>in</span> <span m='759290'>some</span> <span m='759620'>third</span>
  <span m='759860'>harmonic</span> <span m='760280'>and</span> <span m='760370'>some</span>
  <span m='760550'>fifth</span> <span m='760760'>harmonic.</span> <span m='761880'>So</span>
  <span m='762310'>you</span> <span m='762400'>get</span> <span m='762530'>something</span>
  <span m='762820'>that</span> <span m='762890'>sounds</span> <span m='763190'>very</span>
  <span m='765620'>constant</span> <span m='766160'>pitch.</span> </p><p><span m='767450'>Then</span>
  <span m='767930'>I</span> <span m='768050'>took</span> <span m='768290'>that</span>
  <span m='768500'>waveform</span> <span m='769070'>and</span> <span m='769160'>put</span>
  <span m='769310'>it</span> <span m='769400'>through</span> <span m='769550'>this</span>
  <span m='769730'>filter.</span> <span m='771670'>And</span> <span m='771880'>that</span>
  <span m='772090'>changes</span> <span m='772660'>this</span> <span m='773020'>looking</span>
  <span m='773410'>wave</span> <span m='773620'>form</span> <span m='773980'>into</span>
  <span m='774220'>that</span> <span m='774430'>looking</span> <span m='774690'>waveform.</span>
  <span m='776000'>Those</span> <span m='776200'>are</span> <span m='776260'>real</span>
  <span m='776460'>waveforms.</span> <span m='779550'>And</span> <span m='779750'>then</span>
  <span m='779880'>it</span> <span m='779940'>changes</span> <span m='780480'>the</span>
  <span m='780600'>sound,</span> <span m='781820'>so</span> <span m='782010'>that</span>
  <span m='782160'>instead</span> <span m='782520'>of</span> <span m='782610'>sounding</span>
  <span m='782970'>like</span> <span m='783150'>this</span> <span m='785181'>[TONES
  PLAYING],</span> <span m='787620'>it sounds</span> <span m='787880'>like</span>
  <span m='789368'>[TONES PLAYING].</span> </p><p><span m='792332'>[LAUGHTER]</span>
  </p><p><span m='794810'>You</span> <span m='794960'>can</span> <span m='795070'>all</span>
  <span m='795230'>hear</span> <span m='795410'>the</span> <span m='795590'>enormous</span>
  <span m='795980'>difference,</span> <span m='796380'>right?</span> <span m='798440'>So</span>
  <span m='798650'>even</span> <span m='798980'>with</span> <span m='799130'>headphones,</span>
  <span m='799580'>I</span> <span m='799700'>can't</span> <span m='799970'>hear</span>
  <span m='800720'>any</span> <span m='801050'>difference</span> <span m='801650'>at</span>
  <span m='801860'>all.</span> <span m='802640'>And</span> <span m='802790'>that's</span>
  <span m='803030'>kind</span> <span m='803360'>of</span> <span m='803450'>a</span>
  <span m='803510'>property</span> <span m='803900'>of</span> <span m='803960'>the</span>
  <span m='804050'>way</span> <span m='804170'>you</span> <span m='804320'>hear.</span>
  <span m='805190'>You</span> <span m='805340'>kind</span> <span m='805850'>of</span>
  <span m='806030'>hear--</span> <span m='807080'>I'll</span> <span m='807230'>say</span>
  <span m='807470'>some</span> <span m='807650'>caveats</span> <span m='808160'>about</span>
  <span m='808430'>this.</span> <span m='808820'>This is</span> <span m='808940'>not</span>
  <span m='809150'>exactly</span> <span m='809660'>true.</span> </p><p><span m='811290'>So</span>
  <span m='812230'>Ohm's</span> <span m='812720'>law</span> <span m='813170'>of</span>
  <span m='813410'>hearing--</span> <span m='814100'>the</span> <span m='814580'>same</span>
  <span m='814940'>Ohm--</span> <span m='816560'>says</span> <span m='816890'>that</span>
  <span m='817010'>you</span> <span m='817220'>hear</span> <span m='818030'>sounds</span>
  <span m='818960'>by</span> <span m='819500'>the</span> <span m='819590'>frequencies</span>
  <span m='820100'>that</span> <span m='820250'>they</span> <span m='820640'>contain.</span>
  <span m='822260'>Roughly</span> <span m='822830'>speaking,</span> <span m='823340'>you</span>
  <span m='823520'>hear</span> <span m='823880'>sounds</span> <span m='824390'>according</span>
  <span m='824810'>to</span> <span m='824930'>the</span> <span m='825050'>magnitude</span>
  <span m='825770'>of</span> <span m='825830'>the</span> <span m='825920'>frequencies</span>
  <span m='826490'>that</span> <span m='826610'>you</span> <span m='826730'>hear.</span>
  <span m='826880'>Now,</span> <span m='826960'>that's</span> <span m='827180'>not</span>
  <span m='827330'>quite</span> <span m='827570'>true,</span> <span m='828140'>but</span>
  <span m='828240'>it's</span> <span m='828340'>sort</span> <span m='828530'>of</span>
  <span m='828650'>true.</span> </p><p><span m='830120'>So</span> <span m='830240'>let</span>
  <span m='830330'>me</span> <span m='830420'>do</span> <span m='830780'>a</span>
  <span m='830810'>more</span> <span m='831020'>complicated</span> <span m='831530'>example.</span>
  <span m='833000'>So</span> <span m='833180'>the</span> <span m='833300'>first</span>
  <span m='833570'>sound</span> <span m='834050'>is</span> <span m='834610'>a</span>
  <span m='835010'>consonant</span> <span m='835490'>vowel</span> <span m='835790'>consonant.</span>
  </p><p><span m='837326'>[AUDIO PLAYBACK]</span> </p><p><span m='837784'>-</span>
  <span m='838013'>Bat.</span> </p><p><span m='838242'>[END PLAYBACK]</span> </p><p><span
  m='839616'>DENNIS FREEMAN:</span> <span m='840080'>And then</span> <span m='840230'>I</span>
  <span m='840440'>put</span> <span m='840590'>it</span> <span m='840650'>through</span>
  <span m='840830'>the</span> <span m='840950'>same</span> <span m='841220'>all</span>
  <span m='841400'>pass.</span> <span m='841870'>So I</span> <span m='842000'>screw</span>
  <span m='842300'>up</span> <span m='842450'>the</span> <span m='843020'>phases.</span>
  <span m='843800'>So</span> <span m='844100'>it</span> <span m='844220'>goes</span>
  <span m='844490'>from</span> <span m='844640'>looking</span> <span m='844910'>like</span>
  <span m='845090'>this</span> <span m='845330'>to</span> <span m='845450'>looking</span>
  <span m='845720'>like</span> <span m='845870'>this</span> <span m='846170'>and</span>
  <span m='846260'>sounding</span> <span m='846650'>like--</span> </p><p><span m='847621'>[AUDIO
  PLAYBACK]</span> </p><p><span m='848112'>-</span> <span m='848357'>Bat.</span> </p><p><span
  m='848603'>[END PLAYBACK]</span> </p><p><span m='851210'>DENNIS FREEMAN:</span>
  <span m='851470'>Hard</span> <span m='851980'>to</span> <span m='852070'>hear</span>
  <span m='852280'>the</span> <span m='852400'>difference.</span> <span m='853710'>Here's</span>
  <span m='853810'>an</span> <span m='853900'>even</span> <span m='854170'>more</span>
  <span m='854320'>complicated</span> <span m='854890'>sound.</span> <span m='855270'>This</span>
  <span m='855400'>is</span> <span m='855490'>Bob</span> <span m='855670'>Donovan's</span>
  <span m='856180'>thesis.</span> </p><p><span m='856750'>[AUDIO PLAYBACK]</span>
  </p><p><span m='857216'>-</span> <span m='857449'>[INAUDIBLE]</span> <span m='860012'>but</span>
  <span m='860478'>you see</span> <span m='860944'>I have</span> <span m='861410'>no</span>
  <span m='861570'>brain.</span> </p><p><span m='862002'>[END PLAYBACK]</span> </p><p><span
  m='864162'>DENNIS FREEMAN:</span> <span m='864600'>Put</span> <span m='864750'>that</span>
  <span m='865030'>through</span> <span m='865150'>the</span> <span m='865410'>all
  pass,</span> <span m='865770'>and</span> <span m='865860'>you</span> <span m='865950'>get--</span>
  </p><p><span m='866460'>[AUDIO PLAYBACK]</span> </p><p><span m='866945'>-</span>
  <span m='867430'>[INAUDIBLE]</span> <span m='868885'>for</span> <span m='869370'>seeking</span>
  <span m='869855'>[INAUDIBLE]</span> <span m='870340'>but</span> <span m='870825'>you
  see</span> <span m='871310'>I have</span> <span m='871795'>no brain.</span> </p><p><span
  m='872280'>[END PLAYBACK]</span> </p><p><span m='873735'>DENNIS FREEMAN:</span>
  <span m='874230'>If</span> <span m='874350'>I</span> <span m='874440'>listen</span>
  <span m='874740'>to</span> <span m='874800'>that</span> <span m='875010'>on</span>
  <span m='875130'>headphones,</span> <span m='875550'>I</span> <span m='875640'>can</span>
  <span m='875790'>actually</span> <span m='876090'>hear</span> <span m='876240'>a</span>
  <span m='876270'>difference.</span> <span m='877140'>But</span> <span m='877350'>I</span>
  <span m='877410'>study</span> <span m='877710'>hearing,</span> <span m='878070'>and</span>
  <span m='878160'>I</span> <span m='878220'>know</span> <span m='878370'>what</span>
  <span m='878490'>to</span> <span m='878580'>listen</span> <span m='878820'>for.</span>
  <span m='880380'>It's</span> <span m='880920'>still</span> <span m='881280'>difficult</span>
  <span m='881730'>to</span> <span m='881850'>tell</span> <span m='882030'>the</span>
  <span m='882120'>difference.</span> <span m='882450'>Now,</span> <span m='882990'>that's</span>
  <span m='883260'>because</span> <span m='883830'>I</span> <span m='883920'>kind</span>
  <span m='884310'>of</span> <span m='884430'>cheated.</span> </p><p><span m='886400'>To</span>
  <span m='886540'>let</span> <span m='886690'>you</span> <span m='886830'>know</span>
  <span m='887010'>how</span> <span m='887190'>I</span> <span m='887280'>cheated,</span>
  <span m='888060'>let</span> <span m='888180'>me</span> <span m='888300'>do</span>
  <span m='888450'>something</span> <span m='888780'>more</span> <span m='888990'>drastic</span>
  <span m='889560'>to</span> <span m='889710'>the</span> <span m='889860'>phase.</span>
  <span m='892010'>Let</span> <span m='892310'>me</span> <span m='892550'>play</span>
  <span m='893050'>the</span> <span m='893170'>waveform</span> <span m='893830'>backwards.</span>
  </p><p><span m='896564'>[AUDIO PLAYBACK]</span> </p><p><span m='897060'>-</span>
  <span m='897308'>[INAUDIBLE]</span> </p><p><span m='902020'>[END PLAYBACK]</span>
  </p><p><span m='902530'>DENNIS FREEMAN:</span> <span m='902650'>Now,</span> <span
  m='903130'>you</span> <span m='903280'>could</span> <span m='903370'>probably</span>
  <span m='903610'>hear</span> <span m='903760'>the</span> <span m='903850'>difference.</span>
  </p><p><span m='905140'>[LAUGHTER]</span> </p><p><span m='906670'>So</span> <span
  m='906880'>now,</span> <span m='907120'>check</span> <span m='907360'>yourself.</span>
  <span m='910130'>How</span> <span m='910390'>does</span> <span m='910630'>the</span>
  <span m='910780'>phase</span> <span m='911470'>of</span> <span m='911650'>the</span>
  <span m='911770'>second</span> <span m='912130'>signal</span> <span m='912520'>compare</span>
  <span m='912940'>to</span> <span m='913060'>the</span> <span m='913180'>phase</span>
  <span m='913570'>of</span> <span m='913630'>the</span> <span m='913720'>first</span>
  <span m='913930'>signal?</span> <span m='929620'>So</span> <span m='929770'>look</span>
  <span m='929950'>at</span> <span m='930040'>each</span> <span m='930220'>other</span>
  <span m='930430'>so</span> <span m='930580'>you</span> <span m='930670'>can</span>
  <span m='930790'>blame</span> <span m='931060'>each</span> <span m='931210'>other.</span>
  <span m='932155'>If</span> <span m='932440'>you</span> <span m='932530'>work</span>
  <span m='932710'>on</span> <span m='932830'>this</span> <span m='933010'>in</span>
  <span m='933080'>solitary,</span> <span m='933550'>then</span> <span m='933700'>I'll</span>
  <span m='933800'>have to</span> <span m='934210'>blame</span> <span m='934330'>you.</span>
  </p><p><span m='939052'>[INTERPOSING VOICES]</span> </p><p></p><p><span m='1009270'>DENNIS
  FREEMAN:</span> <span m='1009830'>So</span> <span m='1010010'>it's</span> <span
  m='1010160'>a</span> <span m='1010220'>phase</span> <span m='1010490'>relationship</span>
  <span m='1011060'>between</span> <span m='1011420'>the x</span> <span m='1011690'>signal</span>
  <span m='1012110'>and</span> <span m='1012260'>the</span> <span m='1012350'>y</span>
  <span m='1012570'>signal.</span> <span m='1015850'>If</span> <span m='1015870'>I</span>
  <span m='1015960'>showed</span> <span m='1016260'>you</span> <span m='1016530'>the</span>
  <span m='1017220'>Fourier</span> <span m='1017550'>transform</span> <span m='1019860'>for</span>
  <span m='1020130'>the x</span> <span m='1020410'>signal</span> <span m='1020940'>and</span>
  <span m='1021210'>looked</span> <span m='1021450'>at</span> <span m='1021720'>the</span>
  <span m='1021930'>y</span> <span m='1022170'>signal,</span> <span m='1022500'>which</span>
  <span m='1022680'>is</span> <span m='1022800'>x</span> <span m='1022950'>of</span>
  <span m='1023080'>minus</span> <span m='1023400'>n,</span> <span m='1023640'>how</span>
  <span m='1023760'>would</span> <span m='1023910'>the</span> <span m='1024000'>two</span>
  <span m='1024720'>look--</span> <span m='1024990'>the</span> <span m='1025079'>same</span>
  <span m='1025319'>or</span> <span m='1025380'>different?</span> <span m='1028150'>I</span>
  <span m='1028210'>sort</span> <span m='1028390'>of</span> <span m='1028450'>gave</span>
  <span m='1028630'>it</span> <span m='1028690'>away.</span> <span m='1029710'>Flipping</span>
  <span m='1030579'>in</span> <span m='1031119'>time</span> <span m='1031839'>does</span>
  <span m='1032079'>what</span> <span m='1032270'>to</span> <span m='1032380'>the</span>
  <span m='1032470'>magnitude</span> <span m='1032920'>of the</span> <span m='1033010'>Fourier</span>
  <span m='1033369'>transform?</span> <span m='1035530'>Flipping</span> <span m='1036040'>time--</span>
  </p><p><span m='1038522'>AUDIENCE:</span> <span m='1039015'>Change</span> <span
  m='1039508'>the</span> <span m='1040001'>magnitude?</span> </p><p><span m='1040500'>DENNIS
  FREEMAN:</span> <span m='1040679'>Doesn't</span> <span m='1040859'>change</span>
  <span m='1041190'>the</span> <span m='1041310'>magnitude</span> <span m='1041849'>at</span>
  <span m='1041940'>all.</span> <span m='1042310'>What</span> <span m='1042329'>does</span>
  <span m='1042480'>it</span> <span m='1042540'>do?</span> </p><p><span m='1044662'>AUDIENCE:</span>
  <span m='1045125'>The</span> <span m='1045588'>phase.</span> </p><p><span m='1046051'>DENNIS
  FREEMAN:</span> <span m='1046520'>Flips</span> <span m='1046910'>the</span> <span
  m='1047030'>sign</span> <span m='1047510'>of</span> <span m='1047599'>the</span>
  <span m='1047720'>phase.</span> <span m='1048349'>That's</span> <span m='1048500'>exactly</span>
  <span m='1048920'>right.</span> <span m='1050020'>So</span> <span m='1051260'>if</span>
  <span m='1051380'>you're</span> <span m='1051590'>into</span> <span m='1051830'>math-y</span>
  <span m='1052040'>these</span> <span m='1052160'>sort</span> <span m='1052370'>of</span>
  <span m='1052460'>things,</span> <span m='1053560'>you</span> <span m='1053780'>can</span>
  <span m='1053900'>think</span> <span m='1054080'>of</span> <span m='1054260'>representing</span>
  <span m='1054860'>the</span> <span m='1054980'>two</span> <span m='1055280'>as</span>
  <span m='1055460'>Fourier</span> <span m='1055800'>series--</span> <span m='1056510'>the</span>
  <span m='1056690'>ak's</span> <span m='1057140'>and</span> <span m='1057260'>the</span>
  <span m='1057350'>bk's.</span> </p><p><span m='1058460'>And</span> <span m='1058790'>if</span>
  <span m='1059000'>you</span> <span m='1059540'>think</span> <span m='1059750'>about</span>
  <span m='1060020'>what</span> <span m='1060230'>happens</span> <span m='1060590'>if</span>
  <span m='1060680'>you</span> <span m='1060800'>have</span> <span m='1060920'>x of</span>
  <span m='1061190'>minus</span> <span m='1061550'>n,</span> <span m='1061760'>you</span>
  <span m='1061820'>can</span> <span m='1061940'>do a</span> <span m='1062060'>change</span>
  <span m='1062280'>of</span> <span m='1062360'>variable,</span> <span m='1063740'>make</span>
  <span m='1064020'>that</span> <span m='1064100'>look</span> <span m='1064250'>like</span>
  <span m='1064460'>x</span> <span m='1064670'>of</span> <span m='1065000'>n.</span>
  <span m='1066050'>Then</span> <span m='1066200'>it</span> <span m='1066260'>looks</span>
  <span m='1066440'>more</span> <span m='1066620'>like</span> <span m='1066890'>the</span>
  <span m='1067010'>Fourier</span> <span m='1067340'>series</span> <span m='1067730'>equation,</span>
  <span m='1068790'>except</span> <span m='1069080'>that</span> <span m='1069410'>now</span>
  <span m='1069770'>I</span> <span m='1069920'>lost</span> <span m='1070250'>my</span>
  <span m='1070400'>minus</span> <span m='1070670'>sign.</span> <span m='1072260'>So</span>
  <span m='1072500'>a</span> <span m='1072740'>sub</span> <span m='1072830'>k</span>
  <span m='1073130'>is</span> <span m='1073280'>the</span> <span m='1073370'>same</span>
  <span m='1073580'>as</span> <span m='1073700'>b sub</span> <span m='1074000'>minus</span>
  <span m='1074300'>k.</span> </p><p><span m='1077080'>The</span> <span m='1077200'>effect</span>
  <span m='1077530'>is</span> <span m='1077680'>to</span> <span m='1077800'>flip</span>
  <span m='1078010'>the</span> <span m='1078130'>sign</span> <span m='1078760'>of</span>
  <span m='1079000'>the</span> <span m='1079120'>phase.</span> <span m='1079450'>Why</span>
  <span m='1079600'>would</span> <span m='1079750'>that</span> <span m='1079900'>be</span>
  <span m='1080020'>so</span> <span m='1080170'>much</span> <span m='1080500'>more</span>
  <span m='1080800'>audible</span> <span m='1082180'>than</span> <span m='1082300'>the</span>
  <span m='1082420'>other</span> <span m='1082660'>things</span> <span m='1082900'>that</span>
  <span m='1083020'>I</span> <span m='1083080'>showed</span> <span m='1083320'>you?</span>
  <span m='1086740'>Flipping</span> <span m='1087280'>the</span> <span m='1087400'>sign</span>
  <span m='1087730'>of</span> <span m='1087810'>a</span> <span m='1087880'>phase,</span>
  <span m='1088210'>why</span> <span m='1088330'>would</span> <span m='1088450'>that</span>
  <span m='1088570'>be</span> <span m='1088690'>audible?</span> <span m='1093890'>What</span>
  <span m='1094090'>would</span> <span m='1094230'>it</span> <span m='1094320'>mean</span>
  <span m='1094560'>if</span> <span m='1094650'>I</span> <span m='1094770'>flipped</span>
  <span m='1095040'>the</span> <span m='1095160'>sign</span> <span m='1096390'>from</span>
  <span m='1097020'>68</span> <span m='1097920'>degrees</span> <span m='1098520'>to</span>
  <span m='1098670'>minus</span> <span m='1098970'>68</span> <span m='1099510'>degrees?</span>
  <span m='1105560'>Not</span> <span m='1106010'>a</span> <span m='1106070'>clue.</span>
  <span m='1106640'>Yes.</span> </p><p><span m='1107030'>AUDIENCE:</span> <span m='1107505'>For
  a</span> <span m='1107980'>total</span> <span m='1108455'>time, it</span> <span
  m='1108930'>wouldn't</span> <span m='1109405'>change a thing.</span> <span m='1109880'>But
  for any</span> <span m='1110355'>sign</span> <span m='1110830'>terms,</span> <span
  m='1111305'>it would</span> <span m='1111780'>invert</span> <span m='1112255'>that</span>
  <span m='1112730'>over</span> <span m='1113205'>that.</span> </p><p><span m='1113680'>DENNIS
  FREEMAN:</span> <span m='1113770'>So</span> <span m='1113860'>it'd</span> <span
  m='1114090'>invert--</span> <span m='1115950'>Let's</span> <span m='1116100'>see,</span>
  <span m='1116260'>if</span> <span m='1116350'>you</span> <span m='1116450'>went</span>
  <span m='1116560'>from</span> <span m='1118270'>plus</span> <span m='1118540'>68</span>
  <span m='1119020'>to</span> <span m='1119110'>minus</span> <span m='1119410'>68--</span>
  <span m='1120700'>so</span> <span m='1120880'>say</span> <span m='1121060'>I</span>
  <span m='1121180'>had</span> <span m='1122250'>cosine</span> <span m='1123650'>of</span>
  <span m='1124180'>omega</span> <span m='1124660'>n</span> <span m='1125080'>plus</span>
  <span m='1125350'>68</span> <span m='1125860'>degrees</span> <span m='1126940'>and</span>
  <span m='1127090'>cosine</span> <span m='1127780'>omega</span> <span m='1128170'>n</span>
  <span m='1129250'>minus</span> <span m='1129610'>68</span> <span m='1130090'>degrees.</span>
  <span m='1132470'>So</span> <span m='1132570'>I</span> <span m='1132670'>change</span>
  <span m='1132850'>the</span> <span m='1132970'>phase</span> <span m='1133910'>by</span>
  <span m='1134110'>flipping</span> <span m='1134440'>the</span> <span m='1134530'>sign</span>
  <span m='1134860'>of</span> <span m='1134980'>it.</span> <span m='1136360'>How</span>
  <span m='1136510'>would</span> <span m='1136630'>that</span> <span m='1136810'>change</span>
  <span m='1137380'>the</span> <span m='1138340'>relationship</span> <span m='1139360'>between</span>
  <span m='1139750'>the</span> <span m='1139840'>two</span> <span m='1139990'>signals?</span>
  </p><p><span m='1145750'>What's</span> <span m='1145970'>phase?</span> <span m='1148600'>Intuitively,</span>
  <span m='1149200'>what's</span> <span m='1149380'>phase?</span> <span m='1150780'>Yeah,</span>
  <span m='1151250'>it's this</span> <span m='1151390'>way.</span> <span m='1151690'>It's
  a</span> <span m='1152100'>time</span> <span m='1152390'>shift.</span> <span m='1154060'>So</span>
  <span m='1154210'>the</span> <span m='1154330'>problem</span> <span m='1154750'>with</span>
  <span m='1154960'>this</span> <span m='1155260'>phase</span> <span m='1155560'>shift</span>
  <span m='1156250'>is</span> <span m='1156400'>that</span> <span m='1156490'>you're</span>
  <span m='1156910'>shifting</span> <span m='1157360'>all</span> <span m='1157510'>the</span>
  <span m='1157630'>different</span> <span m='1157870'>components</span> <span m='1158410'>by</span>
  <span m='1158530'>different</span> <span m='1158800'>amounts</span> <span m='1159100'>of</span>
  <span m='1159160'>phase.</span> <span m='1161180'>So</span> <span m='1161200'>you</span>
  <span m='1161290'>might</span> <span m='1161470'>have</span> <span m='1161620'>a</span>
  <span m='1161650'>little</span> <span m='1161860'>bit</span> <span m='1162040'>of</span>
  <span m='1162610'>68</span> <span m='1163180'>hertz</span> <span m='1163480'>and</span>
  <span m='1163600'>72</span> <span m='1164140'>hertz</span> <span m='1164470'>and</span>
  <span m='1164950'>3</span> <span m='1165250'>kilohertz</span> <span m='1165800'>and</span>
  <span m='1165970'>512</span> <span m='1167230'>hertz.</span> <span m='1167680'>And</span>
  <span m='1168250'>all</span> <span m='1168490'>of</span> <span m='1168580'>those</span>
  <span m='1169300'>are</span> <span m='1169420'>getting</span> <span m='1169660'>their</span>
  <span m='1169810'>phase</span> <span m='1170140'>flipped.</span> <span m='1170500'>So</span>
  <span m='1170580'>whatever</span> <span m='1170880'>it</span> <span m='1170980'>came</span>
  <span m='1171250'>out--</span> <span m='1172410'>13,</span> <span m='1173440'>128,</span>
  <span m='1174250'>whatever--</span> <span m='1174730'>it</span> <span m='1174820'>becomes</span>
  <span m='1175180'>minus</span> <span m='1175570'>that.</span> </p><p><span m='1177380'>All</span>
  <span m='1177690'>of</span> <span m='1177760'>those</span> <span m='1177970'>phase</span>
  <span m='1178150'>shifts</span> <span m='1178570'>represent</span> <span m='1179550'>a</span>
  <span m='1179860'>time</span> <span m='1180310'>shift.</span> <span m='1182170'>All</span>
  <span m='1182330'>the</span> <span m='1182410'>components</span> <span m='1182860'>are</span>
  <span m='1182950'>being</span> <span m='1183220'>shifted</span> <span m='1183580'>in</span>
  <span m='1183700'>time.</span> <span m='1185000'>So</span> <span m='1185200'>you're</span>
  <span m='1185650'>shifting</span> <span m='1186130'>around</span> <span m='1186520'>things,</span>
  <span m='1187180'>all</span> <span m='1187390'>the</span> <span m='1187510'>different</span>
  <span m='1187750'>components,</span> <span m='1188260'>by</span> <span m='1188410'>some</span>
  <span m='1189310'>amount.</span> <span m='1191140'>And</span> <span m='1191260'>what</span>
  <span m='1191380'>your</span> <span m='1191590'>ear</span> <span m='1191730'>is</span>
  <span m='1191830'>actually</span> <span m='1192100'>very</span> <span m='1192280'>sensitive</span>
  <span m='1192700'>to</span> <span m='1193240'>is</span> <span m='1193450'>the</span>
  <span m='1193540'>low</span> <span m='1193750'>frequencies.</span> <span m='1194380'>When</span>
  <span m='1194500'>you</span> <span m='1194620'>shift</span> <span m='1194950'>the</span>
  <span m='1195070'>low</span> <span m='1195280'>frequencies</span> <span m='1196330'>by</span>
  <span m='1196540'>an</span> <span m='1196600'>amount</span> <span m='1196930'>of</span>
  <span m='1197020'>phase,</span> <span m='1197380'>that's</span> <span m='1197530'>a</span>
  <span m='1197620'>big</span> <span m='1197920'>time.</span> </p><p><span m='1199930'>So</span>
  <span m='1200110'>if</span> <span m='1200200'>you</span> <span m='1200290'>think</span>
  <span m='1200440'>about</span> <span m='1200740'>the</span> <span m='1200830'>fundamental</span>
  <span m='1201310'>frequency</span> <span m='1202300'>that</span> <span m='1202510'>started</span>
  <span m='1202930'>when</span> <span m='1203080'>the</span> <span m='1203230'>utterance</span>
  <span m='1203620'>began</span> <span m='1204220'>and</span> <span m='1204310'>went</span>
  <span m='1204520'>to</span> <span m='1204670'>the</span> <span m='1204820'>end</span>
  <span m='1205000'>of</span> <span m='1205060'>the</span> <span m='1205210'>utterance,</span>
  <span m='1205930'>that</span> <span m='1206050'>was</span> <span m='1206140'>like</span>
  <span m='1206290'>two</span> <span m='1206500'>seconds.</span> <span m='1208800'>So</span>
  <span m='1208950'>whatever</span> <span m='1209280'>that</span> <span m='1209490'>phase</span>
  <span m='1209860'>is,</span> <span m='1210000'>it</span> <span m='1210090'>got</span>
  <span m='1210300'>inverted,</span> <span m='1210780'>which</span> <span m='1210990'>is</span>
  <span m='1211140'>a</span> <span m='1211200'>large</span> <span m='1211590'>fraction</span>
  <span m='1212190'>of</span> <span m='1212430'>two</span> <span m='1212610'>seconds</span>
  <span m='1213060'>probably.</span> <span m='1214530'>You</span> <span m='1214620'>can</span>
  <span m='1214770'>easily</span> <span m='1215310'>hear</span> <span m='1215460'>a</span>
  <span m='1215520'>time-shift</span> <span m='1216060'>of</span> <span m='1216180'>two</span>
  <span m='1216330'>seconds.</span> <span m='1216820'>Yeah.</span> </p><p><span m='1216980'>AUDIENCE:</span>
  <span m='1217209'>Could</span> <span m='1217438'>you notice</span> <span m='1217896'>it,</span>
  <span m='1218354'>if</span> <span m='1218812'>it was</span> <span m='1219270'>just
  a</span> <span m='1219728'>pure tone?</span> </p><p><span m='1220644'>DENNIS FREEMAN:</span>
  <span m='1221110'>If</span> <span m='1221230'>it</span> <span m='1221290'>were</span>
  <span m='1221410'>just</span> <span m='1221650'>a</span> <span m='1221710'>pure</span>
  <span m='1221890'>tone,</span> <span m='1222160'>you</span> <span m='1222380'>would</span>
  <span m='1222520'>have</span> <span m='1222730'>no</span> <span m='1222940'>clue.</span>
  </p><p><span m='1223796'>AUDIENCE:</span> <span m='1224292'>Or you can</span> <span
  m='1225284'>[INAUDIBLE]</span> <span m='1226276'>overtones</span> <span m='1227268'>very
  simple.</span> </p><p><span m='1227764'>DENNIS FREEMAN:</span> <span m='1228260'>So</span>
  <span m='1228850'>to</span> <span m='1229000'>make</span> <span m='1230050'>Ohm's</span>
  <span m='1230320'>law</span> <span m='1230620'>a</span> <span m='1230710'>little</span>
  <span m='1231010'>more</span> <span m='1231190'>precise,</span> <span m='1232630'>what</span>
  <span m='1232840'>your</span> <span m='1232960'>ear</span> <span m='1233140'>really</span>
  <span m='1233500'>does</span> <span m='1233950'>is</span> <span m='1235120'>it</span>
  <span m='1235240'>does</span> <span m='1235420'>band pass</span> <span m='1235870'>filters.</span>
  <span m='1237640'>If</span> <span m='1237820'>the</span> <span m='1237940'>components</span>
  <span m='1238510'>fall</span> <span m='1238810'>very</span> <span m='1239080'>close</span>
  <span m='1239380'>to</span> <span m='1239500'>each</span> <span m='1239680'>other,</span>
  <span m='1239890'>you</span> <span m='1240040'>can</span> <span m='1240190'>hear</span>
  <span m='1240460'>the</span> <span m='1240580'>phase</span> <span m='1240820'>shift.</span>
  <span m='1242380'>If</span> <span m='1242530'>the</span> <span m='1242650'>components</span>
  <span m='1243070'>are</span> <span m='1243190'>far</span> <span m='1243490'>from</span>
  <span m='1243730'>each</span> <span m='1243880'>other,</span> <span m='1244850'>you</span>
  <span m='1244870'>can't.</span> </p><p><span m='1247730'>Even</span> <span m='1248650'>the</span>
  <span m='1248810'>second</span> <span m='1249310'>overtone</span> <span m='1251440'>of</span>
  <span m='1251590'>a</span> <span m='1251620'>fundamental</span> <span m='1252220'>is</span>
  <span m='1252400'>far</span> <span m='1252640'>enough</span> <span m='1252910'>away</span>
  <span m='1253360'>that</span> <span m='1253480'>you</span> <span m='1253570'>can't</span>
  <span m='1253840'>hear</span> <span m='1253990'>the</span> <span m='1254110'>relative</span>
  <span m='1254470'>phase</span> <span m='1254800'>of</span> <span m='1254920'>it.</span>
  <span m='1255640'>The</span> <span m='1255730'>frequency</span> <span m='1256150'>components</span>
  <span m='1256570'>have</span> <span m='1256690'>to</span> <span m='1256780'>be</span>
  <span m='1256900'>very</span> <span m='1257140'>close</span> <span m='1257410'>together.</span>
  <span m='1258650'>So</span> <span m='1259060'>you</span> <span m='1259240'>can</span>
  <span m='1259660'>hear</span> <span m='1260050'>phase</span> <span m='1260740'>only</span>
  <span m='1261190'>in</span> <span m='1261310'>a</span> <span m='1261370'>very</span>
  <span m='1261670'>particular</span> <span m='1262180'>case</span> <span m='1262540'>when</span>
  <span m='1262720'>there's</span> <span m='1262930'>frequency</span> <span m='1263350'>components</span>
  <span m='1263800'>that</span> <span m='1263890'>are</span> <span m='1263980'>very</span>
  <span m='1264280'>close</span> <span m='1264580'>to</span> <span m='1264670'>each</span>
  <span m='1264850'>other</span> <span m='1265790'>and</span> <span m='1265930'>there's</span>
  <span m='1266110'>a</span> <span m='1266170'>relatively</span> <span m='1266710'>big</span>
  <span m='1266920'>shift</span> <span m='1267220'>in</span> <span m='1267340'>the</span>
  <span m='1267430'>phase</span> <span m='1267760'>of</span> <span m='1267940'>those</span>
  <span m='1268150'>two</span> <span m='1268270'>signals.</span> <span m='1268690'>Except</span>
  <span m='1269020'>for</span> <span m='1269170'>that,</span> <span m='1269650'>Ohm's</span>
  <span m='1269950'>law is</span> <span m='1270200'>true.</span> </p><p><span m='1272780'>The</span>
  <span m='1272800'>point</span> <span m='1273080'>is</span> <span m='1273220'>just</span>
  <span m='1273490'>that</span> <span m='1274000'>the</span> <span m='1275490'>Fourier</span>
  <span m='1275800'>series</span> <span m='1276510'>gives</span> <span m='1276740'>us</span>
  <span m='1276820'>a</span> <span m='1276880'>way</span> <span m='1277000'>of</span>
  <span m='1277090'>thinking</span> <span m='1277450'>about</span> <span m='1278230'>a</span>
  <span m='1278290'>very</span> <span m='1278620'>interesting</span> <span m='1279160'>dimension</span>
  <span m='1279790'>of</span> <span m='1279940'>a</span> <span m='1280000'>signal--</span>
  <span m='1281530'>one</span> <span m='1281890'>that</span> <span m='1282100'>separates</span>
  <span m='1282760'>things</span> <span m='1283090'>that</span> <span m='1283240'>are</span>
  <span m='1283360'>audible</span> <span m='1283870'>from</span> <span m='1284050'>things</span>
  <span m='1284320'>that</span> <span m='1284440'>are</span> <span m='1284530'>not</span>
  <span m='1284800'>audible.</span> <span m='1285250'>So</span> <span m='1285400'>when</span>
  <span m='1285490'>you're</span> <span m='1285580'>doing</span> <span m='1285760'>signal</span>
  <span m='1286000'>processing,</span> <span m='1286960'>you</span> <span m='1287080'>can</span>
  <span m='1287200'>pay</span> <span m='1287440'>less</span> <span m='1287680'>attention</span>
  <span m='1288100'>to</span> <span m='1288190'>the</span> <span m='1288310'>thing</span>
  <span m='1288490'>that's</span> <span m='1288670'>not</span> <span m='1288850'>audible.</span>
  <span m='1290050'>You</span> <span m='1290170'>can</span> <span m='1290290'>go</span>
  <span m='1290380'>ahead</span> <span m='1290560'>and</span> <span m='1290650'>distort</span>
  <span m='1291040'>that, and</span> <span m='1291280'>nobody</span> <span m='1291580'>will</span>
  <span m='1291670'>know.</span> <span m='1293500'>But</span> <span m='1293710'>you</span>
  <span m='1293860'>have</span> <span m='1294100'>to</span> <span m='1294220'>pay</span>
  <span m='1294580'>close</span> <span m='1294940'>attention</span> <span m='1295510'>to</span>
  <span m='1295630'>the</span> <span m='1295750'>things</span> <span m='1296050'>that's</span>
  <span m='1296200'>very</span> <span m='1296470'>audible,</span> <span m='1296830'>which</span>
  <span m='1296980'>is</span> <span m='1297100'>the</span> <span m='1297160'>magnitude.</span>
  <span m='1299050'>We'll</span> <span m='1299200'>see</span> <span m='1299410'>at</span>
  <span m='1299500'>the</span> <span m='1299620'>end</span> <span m='1299740'>of</span>
  <span m='1299800'>the</span> <span m='1299950'>hour</span> <span m='1300220'>that</span>
  <span m='1300760'>that</span> <span m='1300970'>situation</span> <span m='1301510'>is</span>
  <span m='1301600'>completely</span> <span m='1302020'>flipped</span> <span m='1302410'>for</span>
  <span m='1302590'>video.</span> </p><p><span m='1305860'>But</span> <span m='1306340'>before</span>
  <span m='1306610'>we</span> <span m='1306700'>get</span> <span m='1306850'>there--</span>
  <span m='1308420'>so</span> <span m='1308500'>the</span> <span m='1308590'>first</span>
  <span m='1308770'>thing</span> <span m='1308920'>to</span> <span m='1309010'>think</span>
  <span m='1309190'>about</span> <span m='1309460'>was</span> <span m='1309700'>the</span>
  <span m='1309820'>idea</span> <span m='1310870'>of</span> <span m='1312040'>circular</span>
  <span m='1312430'>frequency--</span> <span m='1313540'>the</span> <span m='1313630'>fact</span>
  <span m='1313840'>that</span> <span m='1313930'>we're</span> <span m='1314080'>looking</span>
  <span m='1314500'>at</span> <span m='1314980'>frequency</span> <span m='1315400'>responses</span>
  <span m='1315850'>living</span> <span m='1316090'>on</span> <span m='1316210'>the</span>
  <span m='1316690'>unit</span> <span m='1317050'>circle,</span> <span m='1317410'>rather</span>
  <span m='1317710'>than</span> <span m='1317860'>on</span> <span m='1317980'>the</span>
  <span m='1318080'>j omega-axis.</span> <span m='1318950'>The</span> <span m='1319050'>second</span>
  <span m='1319180'>big</span> <span m='1319330'>difference</span> <span m='1319960'>with</span>
  <span m='1320140'>the</span> <span m='1320290'>DT</span> <span m='1321100'>is</span>
  <span m='1321280'>the</span> <span m='1321370'>frequencies</span> <span m='1321910'>are</span>
  <span m='1322030'>cyclic.</span> <span m='1324310'>So</span> <span m='1324490'>rather</span>
  <span m='1324910'>than</span> <span m='1325090'>having</span> <span m='1325360'>harmonics</span>
  <span m='1325900'>go</span> <span m='1326050'>the</span> <span m='1326170'>whole</span>
  <span m='1326320'>way</span> <span m='1326500'>up</span> <span m='1326620'>to</span>
  <span m='1326740'>infinity,</span> <span m='1327280'>as</span> <span m='1327400'>we</span>
  <span m='1327490'>did</span> <span m='1327700'>in</span> <span m='1328490'>CT--</span>
  <span m='1330000'>In</span> <span m='1330180'>CT,</span> <span m='1330670'>we</span>
  <span m='1330820'>would</span> <span m='1330910'>have</span> <span m='1331060'>a</span>
  <span m='1331120'>Fourier</span> <span m='1331340'>series</span> <span m='1331780'>constructed</span>
  <span m='1332230'>of the</span> <span m='1332350'>fundamental,</span> <span m='1332830'>the</span>
  <span m='1332920'>second</span> <span m='1333160'>harmonic,</span> <span m='1333520'>the</span>
  <span m='1333640'>third</span> <span m='1333750'>harmonic,</span> <span m='1334120'>the</span>
  <span m='1334240'>fourth</span> <span m='1334450'>harmonic,</span> <span m='1334780'>the
  fifth</span> <span m='1335050'>harmonic,</span> <span m='1335410'>the</span> <span
  m='1335500'>whole</span> <span m='1335650'>way</span> <span m='1335860'>out</span>
  <span m='1335980'>to</span> <span m='1336070'>infinity,</span> <span m='1336670'>in</span>
  <span m='1336820'>principle</span> <span m='1337150'>at</span> <span m='1337210'>least.</span>
  </p><p><span m='1338710'>In</span> <span m='1338950'>DT,</span> <span m='1339580'>they</span>
  <span m='1339790'>rap,</span> <span m='1340630'>so</span> <span m='1340810'>that</span>
  <span m='1340930'>you</span> <span m='1341050'>get</span> <span m='1341170'>a</span>
  <span m='1341230'>finite</span> <span m='1341560'>number</span> <span m='1341830'>of</span>
  <span m='1341930'>them.</span> <span m='1343480'>In</span> <span m='1343630'>fact,</span>
  <span m='1345070'>if</span> <span m='1345680'>you're</span> <span m='1345820'>taking</span>
  <span m='1346330'>a</span> <span m='1346510'>sequence</span> <span m='1346930'>of</span>
  <span m='1347050'>length</span> <span m='1347320'>N,</span> <span m='1348430'>here</span>
  <span m='1348760'>illustrated</span> <span m='1349270'>for</span> <span m='1349420'>8,</span>
  <span m='1350230'>you</span> <span m='1350380'>get</span> <span m='1350770'>eight</span>
  <span m='1351460'>possible</span> <span m='1351940'>frequencies,</span> <span m='1352540'>half</span>
  <span m='1352870'>of</span> <span m='1352960'>which</span> <span m='1353170'>are</span>
  <span m='1353230'>negative.</span> <span m='1354400'>And</span> <span m='1354550'>you</span>
  <span m='1354610'>don't</span> <span m='1354760'>care</span> <span m='1354910'>about</span>
  <span m='1355060'>those</span> <span m='1355240'>anyway.</span> </p><p><span m='1356890'>So</span>
  <span m='1357640'>the</span> <span m='1358180'>number</span> <span m='1358750'>of</span>
  <span m='1359050'>frequency</span> <span m='1359590'>components</span> <span m='1360190'>for</span>
  <span m='1360590'>a</span> <span m='1360700'>DT</span> <span m='1361150'>signal</span>
  <span m='1362140'>is</span> <span m='1362380'>finite--</span> <span m='1363760'>for</span>
  <span m='1363980'>DT</span> <span m='1364760'>Fourier</span> <span m='1365050'>series.</span>
  <span m='1366250'>That</span> <span m='1366460'>has</span> <span m='1366640'>enormous</span>
  <span m='1367330'>implications.</span> <span m='1368990'>It</span> <span m='1369070'>means</span>
  <span m='1369550'>that</span> <span m='1369880'>when</span> <span m='1370000'>you</span>
  <span m='1370150'>do</span> <span m='1370300'>a</span> <span m='1370360'>Fourier</span>
  <span m='1370690'>series</span> <span m='1371100'>decomposition,</span> <span m='1372100'>there's</span>
  <span m='1372250'>a</span> <span m='1372310'>finite</span> <span m='1372640'>number</span>
  <span m='1372850'>of</span> <span m='1372940'>terms.</span> <span m='1373570'>That's</span>
  <span m='1374050'>enormous,</span> <span m='1375280'>because</span> <span m='1375730'>that</span>
  <span m='1376030'>means</span> <span m='1376480'>that,</span> <span m='1376870'>if</span>
  <span m='1377020'>you</span> <span m='1377140'>started</span> <span m='1377590'>out</span>
  <span m='1377830'>with</span> <span m='1377980'>a</span> <span m='1378040'>sequence</span>
  <span m='1378430'>of</span> <span m='1378520'>length cap</span> <span m='1378790'>N,</span>
  <span m='1380770'>say</span> <span m='1381400'>1,024,</span> <span m='1383260'>and</span>
  <span m='1383440'>you</span> <span m='1383560'>take</span> <span m='1384040'>the</span>
  <span m='1384250'>Fourier</span> <span m='1384610'>series</span> <span m='1385030'>of</span>
  <span m='1385180'>it</span> <span m='1385330'>in</span> <span m='1385450'>order</span>
  <span m='1385690'>to</span> <span m='1385780'>think</span> <span m='1385960'>about</span>
  <span m='1386590'>the</span> <span m='1386710'>frequency</span> <span m='1387100'>content,</span>
  <span m='1388450'>you</span> <span m='1388660'>can</span> <span m='1388810'>replace</span>
  <span m='1389380'>the</span> <span m='1389630'>1,024</span> <span m='1391120'>numbers</span>
  <span m='1391510'>in</span> <span m='1391630'>time</span> <span m='1392710'>with</span>
  <span m='1392950'>1,024</span> <span m='1393670'>numbers</span> <span m='1394000'>in</span>
  <span m='1394090'>frequency.</span> </p><p><span m='1395340'>There's</span> <span
  m='1395470'>no--</span> <span m='1396490'>well,</span> <span m='1397420'>no is</span>
  <span m='1397810'>exaggeration.</span> <span m='1398740'>There</span> <span m='1399030'>is</span>
  <span m='1399160'>a</span> <span m='1399220'>factor</span> <span m='1399640'>of</span>
  <span m='1399760'>two</span> <span m='1400120'>kind</span> <span m='1400480'>of</span>
  <span m='1401410'>explosion</span> <span m='1402070'>of</span> <span m='1402160'>data,</span>
  <span m='1403270'>because</span> <span m='1403690'>I</span> <span m='1403780'>went</span>
  <span m='1403990'>from</span> <span m='1404890'>N</span> <span m='1406180'>real-valued</span>
  <span m='1407800'>signals,</span> <span m='1409030'>samples,</span> <span m='1410230'>to</span>
  <span m='1410470'>N</span> <span m='1411400'>complex-valued</span> <span m='1413510'>signals.</span>
  <span m='1414920'>That's</span> <span m='1415250'>not</span> <span m='1415460'>quite</span>
  <span m='1415670'>true</span> <span m='1415970'>either,</span> <span m='1416960'>because</span>
  <span m='1417350'>of</span> <span m='1417500'>the</span> <span m='1417560'>reasons</span>
  <span m='1417950'>about</span> <span m='1418160'>how</span> <span m='1418370'>information</span>
  <span m='1418910'>works.</span> <span m='1419630'>The--</span> <span m='1422210'>how</span>
  <span m='1422330'>do</span> <span m='1422420'>I</span> <span m='1422450'>want</span>
  <span m='1422570'>to</span> <span m='1422660'>say it?</span> <span m='1423260'>The</span>
  <span m='1423470'>resolution</span> <span m='1424190'>that</span> <span m='1424340'>you</span>
  <span m='1424730'>need</span> <span m='1425150'>for</span> <span m='1425360'>the</span>
  <span m='1425510'>frequency</span> <span m='1426020'>domain</span> <span m='1427130'>representation</span>
  <span m='1427970'>is</span> <span m='1428060'>actually</span> <span m='1428360'>slightly</span>
  <span m='1428660'>smaller.</span> <span m='1429730'>To</span> <span m='1429920'>a</span>
  <span m='1429970'>first</span> <span m='1430340'>order,</span> <span m='1430850'>you're</span>
  <span m='1431020'>replacing</span> <span m='1431480'>[? N ?]</span> <span m='1431690'>with</span>
  <span m='1431870'>[? n ?]</span> </p><p><span m='1434110'>That's</span> <span m='1434320'>really</span>
  <span m='1434560'>good,</span> <span m='1434830'>because</span> <span m='1435100'>if</span>
  <span m='1435190'>you</span> <span m='1435280'>think</span> <span m='1435430'>about</span>
  <span m='1435640'>the</span> <span m='1435790'>alternative</span> <span m='1436410'>in</span>
  <span m='1436775'>CT,</span> <span m='1437530'>you</span> <span m='1437680'>would</span>
  <span m='1437800'>be</span> <span m='1437920'>replacing</span> <span m='1438880'>a</span>
  <span m='1438940'>signal</span> <span m='1439420'>with</span> <span m='1439600'>an</span>
  <span m='1439690'>infinite</span> <span m='1440080'>number.</span> <span m='1441010'>And</span>
  <span m='1441130'>that's</span> <span m='1441280'>just</span> <span m='1441460'>not</span>
  <span m='1441700'>reasonable,</span> <span m='1442360'>if</span> <span m='1442480'>you</span>
  <span m='1442570'>want</span> <span m='1442720'>to</span> <span m='1442780'>think</span>
  <span m='1442900'>about</span> <span m='1443230'>processing</span> <span m='1443740'>signals</span>
  <span m='1444520'>with</span> <span m='1444730'>digital</span> <span m='1445060'>electronics.</span>
  <span m='1445720'>There's</span> <span m='1445870'>no</span> <span m='1445990'>way</span>
  <span m='1446230'>that</span> <span m='1446350'>you</span> <span m='1446470'>could</span>
  <span m='1446590'>process</span> <span m='1446980'>an</span> <span m='1447070'>infinite</span>
  <span m='1447340'>number</span> <span m='1447640'>of</span> <span m='1447700'>signals</span>
  <span m='1448090'>in</span> <span m='1448150'>a</span> <span m='1448210'>finite</span>
  <span m='1448480'>amount</span> <span m='1448660'>of</span> <span m='1448720'>time.</span>
  <span m='1450230'>So</span> <span m='1450340'>the</span> <span m='1450460'>fact</span>
  <span m='1450730'>that</span> <span m='1450880'>you're</span> <span m='1451120'>replacing</span>
  <span m='1452140'>n</span> <span m='1452950'>samples</span> <span m='1453490'>in</span>
  <span m='1453640'>time</span> <span m='1454180'>with</span> <span m='1454480'>n</span>
  <span m='1455190'>samples</span> <span m='1455560'>in</span> <span m='1455680'>frequency</span>
  <span m='1456670'>really</span> <span m='1457030'>lends</span> <span m='1457300'>itself</span>
  <span m='1457630'>to</span> <span m='1457750'>doing</span> <span m='1458020'>signal</span>
  <span m='1458320'>processing</span> <span m='1458980'>using</span> <span m='1459790'>digital</span>
  <span m='1460210'>techniques.</span> </p><p><span m='1462410'>Now,</span> <span
  m='1463060'>the</span> <span m='1463150'>problem</span> <span m='1463660'>is--</span>
  <span m='1464410'>and</span> <span m='1465400'>just</span> <span m='1466210'>one</span>
  <span m='1466450'>way</span> <span m='1466600'>of</span> <span m='1466660'>thinking</span>
  <span m='1466930'>about</span> <span m='1467200'>the</span> <span m='1467290'>finite</span>
  <span m='1467650'>length</span> <span m='1468010'>is</span> <span m='1468280'>that</span>
  <span m='1468370'>you</span> <span m='1468430'>can</span> <span m='1468520'>think</span>
  <span m='1468640'>about</span> <span m='1468790'>it</span> <span m='1468840'>by</span>
  <span m='1468980'>matrix.</span> <span m='1469330'>That's just</span> <span m='1469720'>a</span>
  <span m='1470140'>mnemonic</span> <span m='1470590'>that</span> <span m='1470710'>helps</span>
  <span m='1470980'>me</span> <span m='1471130'>a</span> <span m='1471170'>lot,</span>
  <span m='1471770'>to</span> <span m='1471870'>think</span> <span m='1472060'>about</span>
  <span m='1472300'>how,</span> <span m='1472490'>if</span> <span m='1472630'>I</span>
  <span m='1472720'>have</span> <span m='1472840'>a</span> <span m='1472900'>four-length</span>
  <span m='1473350'>sequence,</span> <span m='1474040'>you</span> <span m='1474130'>go</span>
  <span m='1474310'>through</span> <span m='1474490'>some</span> <span m='1474700'>matrix.</span>
  <span m='1475660'>And</span> <span m='1475780'>what</span> <span m='1475870'>comes</span>
  <span m='1476080'>out</span> <span m='1476290'>is</span> <span m='1476410'>a</span>
  <span m='1476470'>four-length</span> <span m='1476890'>frequency</span> <span m='1477310'>response.</span>
  <span m='1478570'>You</span> <span m='1478690'>have</span> <span m='1478810'>some</span>
  <span m='1479080'>eight-length</span> <span m='1479500'>sequence,</span> <span m='1480340'>you</span>
  <span m='1480460'>go</span> <span m='1480640'>through</span> <span m='1480820'>some</span>
  <span m='1481030'>matrix.</span> <span m='1481540'>And then</span> <span m='1481630'>comes</span>
  <span m='1481840'>out</span> <span m='1481960'>some</span> <span m='1482230'>eight-length</span>
  <span m='1484720'>frequency</span> <span m='1485560'>representation.</span> </p><p><span
  m='1487540'>And</span> <span m='1487680'>there's</span> <span m='1487840'>actually</span>
  <span m='1488110'>a</span> <span m='1488170'>lot</span> <span m='1488350'>of</span>
  <span m='1488440'>intuition</span> <span m='1488860'>that</span> <span m='1488950'>you</span>
  <span m='1489040'>can</span> <span m='1489160'>draw</span> <span m='1489550'>in</span>
  <span m='1489760'>making</span> <span m='1490030'>the</span> <span m='1490120'>parallels</span>
  <span m='1490570'>between</span> <span m='1491320'>matrix</span> <span m='1491950'>representations</span>
  <span m='1493510'>and</span> <span m='1494140'>the</span> <span m='1494260'>Fourier</span>
  <span m='1494890'>representation,</span> <span m='1495730'>because</span> <span
  m='1496030'>it</span> <span m='1496150'>is</span> <span m='1496330'>a</span> <span
  m='1496390'>transformation,</span> <span m='1497070'>a</span> <span m='1497110'>linear</span>
  <span m='1497380'>transformation,</span> <span m='1498010'>just</span> <span m='1498250'>like</span>
  <span m='1498430'>the</span> <span m='1498520'>matrix</span> <span m='1499300'>implies.</span>
  <span m='1500800'>There</span> <span m='1500980'>is</span> <span m='1501540'>one</span>
  <span m='1501850'>problem</span> <span m='1503560'>with</span> <span m='1503770'>that</span>
  <span m='1503920'>finite</span> <span m='1504970'>representation</span> <span m='1505810'>idea.</span>
  <span m='1506710'>And</span> <span m='1506830'>that</span> <span m='1507010'>is</span>
  <span m='1507190'>that</span> <span m='1507310'>it</span> <span m='1507400'>scales</span>
  <span m='1508030'>poorly.</span> </p><p><span m='1510790'>If</span> <span m='1510940'>you</span>
  <span m='1511060'>think</span> <span m='1511330'>about</span> <span m='1512440'>having</span>
  <span m='1512740'>a</span> <span m='1512830'>two-length</span> <span m='1513400'>sequence,</span>
  <span m='1516340'>the</span> <span m='1516490'>two-length</span> <span m='1516880'>sequence</span>
  <span m='1517270'>has</span> <span m='1517420'>a</span> <span m='1517480'>two-length</span>
  <span m='1517990'>representation</span> <span m='1518710'>in</span> <span m='1518830'>frequency</span>
  <span m='1519640'>via</span> <span m='1520000'>the</span> <span m='1520120'>Fourier</span>
  <span m='1520430'>series.</span> <span m='1522990'>And</span> <span m='1523170'>that</span>
  <span m='1523410'>representation</span> <span m='1524190'>has</span> <span m='1524400'>how</span>
  <span m='1524520'>many</span> <span m='1524970'>coefficients?</span> <span m='1526970'>Four--</span>
  <span m='1527400'>two</span> <span m='1527570'>and</span> <span m='1527660'>two.</span>
  <span m='1529190'>Now,</span> <span m='1529400'>if</span> <span m='1529490'>I</span>
  <span m='1529550'>do</span> <span m='1529910'>of</span> <span m='1530030'>four,</span>
  <span m='1530900'>I</span> <span m='1530990'>get</span> <span m='1531200'>four,</span>
  <span m='1531740'>how</span> <span m='1531890'>many</span> <span m='1532760'>coefficients?</span>
  <span m='1535770'>4</span> <span m='1535950'>by</span> <span m='1536100'>4</span>
  <span m='1536310'>is</span> <span m='1536400'>16.</span> </p><p><span m='1537810'>Now,</span>
  <span m='1538020'>some</span> <span m='1538230'>of</span> <span m='1538290'>these</span>
  <span m='1538470'>are</span> <span m='1538590'>1's.</span> <span m='1539340'>Right</span>
  <span m='1539680'>So</span> <span m='1539880'>all</span> <span m='1540150'>of</span>
  <span m='1540240'>these</span> <span m='1540450'>are</span> <span m='1540540'>1's.</span>
  <span m='1542490'>As</span> <span m='1542670'>you</span> <span m='1542820'>make</span>
  <span m='1543090'>the</span> <span m='1543210'>sequence</span> <span m='1543660'>bigger</span>
  <span m='1544020'>and</span> <span m='1544110'>bigger</span> <span m='1544380'>and</span>
  <span m='1544470'>bigger,</span> <span m='1544800'>however,</span> <span m='1545550'>the</span>
  <span m='1545700'>number</span> <span m='1546150'>of</span> <span m='1546330'>trivial</span>
  <span m='1547010'>entries</span> <span m='1547380'>gets</span> <span m='1547590'>smaller</span>
  <span m='1548070'>and</span> <span m='1548190'>smaller</span> <span m='1548580'>and</span>
  <span m='1548670'>smaller</span> <span m='1549060'>relative.</span> </p><p><span
  m='1551040'>So</span> <span m='1551340'>as</span> <span m='1551520'>you</span> <span
  m='1551610'>go</span> <span m='1551850'>from</span> <span m='1553200'>a</span> <span
  m='1554700'>two-length</span> <span m='1555210'>sequence</span> <span m='1555870'>to</span>
  <span m='1556050'>a</span> <span m='1556140'>four-length</span> <span m='1556710'>sequence</span>
  <span m='1557220'>to</span> <span m='1557370'>an</span> <span m='1557520'>eight-length</span>
  <span m='1558030'>sequence,</span> <span m='1559290'>now</span> <span m='1559500'>we're</span>
  <span m='1559590'>up</span> <span m='1559710'>to</span> <span m='1559820'>64</span>
  <span m='1562110'>multiplies</span> <span m='1563460'>in</span> <span m='1563580'>order</span>
  <span m='1563820'>to</span> <span m='1563940'>convert</span> <span m='1564330'>a</span>
  <span m='1564390'>time-domain</span> <span m='1564930'>representation</span> <span
  m='1565710'>into</span> <span m='1565980'>a</span> <span m='1566040'>frequency-domain</span>
  <span m='1566820'>representation.</span> <span m='1568000'>Well,</span> <span m='1568110'>that's</span>
  <span m='1568410'>bad,</span> <span m='1568770'>because</span> <span m='1569100'>the</span>
  <span m='1569220'>kinds</span> <span m='1569490'>of</span> <span m='1569580'>things</span>
  <span m='1569790'>we</span> <span m='1569910'>want</span> <span m='1570090'>to</span>
  <span m='1570210'>do</span> <span m='1570390'>are</span> <span m='1570510'>not</span>
  <span m='1571020'>two</span> <span m='1571350'>and</span> <span m='1571470'>four</span>
  <span m='1571980'>and</span> <span m='1572190'>eight.</span> <span m='1572720'>The</span>
  <span m='1572820'>kinds</span> <span m='1573060'>of</span> <span m='1573120'>things</span>
  <span m='1573360'>we</span> <span m='1573450'>want</span> <span m='1573630'>to</span>
  <span m='1573690'>do</span> <span m='1574620'>are</span> <span m='1574800'>manipulations</span>
  <span m='1575580'>on</span> <span m='1575700'>signals</span> <span m='1576110'>of</span>
  <span m='1576170'>10</span> <span m='1576350'>to</span> <span m='1576730'>the sixth,</span>
  <span m='1577110'>10</span> <span m='1577350'>to</span> <span m='1577440'>the</span>
  <span m='1577680'>eighth,</span> <span m='1577980'>10</span> <span m='1578250'>to</span>
  <span m='1578340'>the</span> <span m='1578760'>12th.</span> </p><p><span m='1580500'>For</span>
  <span m='1580680'>my</span> <span m='1581490'>doctoral</span> <span m='1581850'>thesis,</span>
  <span m='1582180'>I</span> <span m='1582270'>did</span> <span m='1582450'>some</span>
  <span m='1582660'>fluid</span> <span m='1582900'>dynamic</span> <span m='1583230'>problems,</span>
  <span m='1584250'>where</span> <span m='1584610'>the</span> <span m='1584730'>calculations</span>
  <span m='1585510'>had</span> <span m='1587240'>10</span> <span m='1587470'>to</span>
  <span m='1587550'>the</span> <span m='1587640'>sixth</span> <span m='1587910'>unknowns.</span>
  <span m='1589290'>And</span> <span m='1589440'>I</span> <span m='1589530'>used</span>
  <span m='1589770'>frequency</span> <span m='1590160'>domain</span> <span m='1590490'>techniques,</span>
  <span m='1592320'>which</span> <span m='1592710'>I</span> <span m='1592800'>was</span>
  <span m='1592950'>able</span> <span m='1593250'>to</span> <span m='1593370'>implement</span>
  <span m='1593850'>with</span> <span m='1594600'>things</span> <span m='1594870'>that</span>
  <span m='1594940'>I'll</span> <span m='1595040'>talk</span> <span m='1595250'>about</span>
  <span m='1595440'>in</span> <span m='1595530'>a</span> <span m='1595590'>minute.</span>
  <span m='1596460'>If</span> <span m='1596640'>we</span> <span m='1596790'>had</span>
  <span m='1597270'>used</span> <span m='1597690'>this</span> <span m='1598000'>scaling</span>
  <span m='1598590'>by</span> <span m='1598920'>the</span> <span m='1599040'>square,</span>
  <span m='1600260'>it</span> <span m='1600420'>just</span> <span m='1600570'>wouldn't</span>
  <span m='1600780'>have</span> <span m='1600870'>worked.</span> <span m='1601710'>If</span>
  <span m='1601860'>you</span> <span m='1602010'>have</span> <span m='1602160'>10</span>
  <span m='1602340'>to</span> <span m='1602400'>the</span> <span m='1602490'>sixth</span>
  <span m='1602730'>unknowns</span> <span m='1603180'>and</span> <span m='1603270'>if</span>
  <span m='1603390'>you're</span> <span m='1603480'>using</span> <span m='1603810'>a</span>
  <span m='1603870'>method</span> <span m='1604200'>that</span> <span m='1604320'>converts</span>
  <span m='1604740'>from</span> <span m='1604890'>one</span> <span m='1605070'>representation</span>
  <span m='1605730'>to</span> <span m='1605790'>another</span> <span m='1606390'>that</span>
  <span m='1606510'>involves</span> <span m='1606810'>10</span> <span m='1606960'>to
  the</span> <span m='1607110'>12th</span> <span m='1607470'>operations,</span> <span
  m='1609150'>that's</span> <span m='1609390'>just</span> <span m='1609660'>not</span>
  <span m='1609840'>a</span> <span m='1609870'>good</span> <span m='1610020'>idea.</span>
  <span m='1611950'>So</span> <span m='1612210'>that's</span> <span m='1612750'>bad.</span>
  </p><p><span m='1614580'>So</span> <span m='1615560'>by</span> <span m='1615750'>the</span>
  <span m='1615870'>theory</span> <span m='1616170'>of</span> <span m='1616260'>lectures,</span>
  <span m='1616770'>what</span> <span m='1616920'>I'm</span> <span m='1617010'>about</span>
  <span m='1617280'>to</span> <span m='1617370'>tell</span> <span m='1617520'>you</span>
  <span m='1617730'>is--</span> </p><p><span m='1619605'>AUDIENCE:</span> <span m='1620040'>[INAUDIBLE].</span>
  </p><p><span m='1621430'>DENNIS FREEMAN:</span> <span m='1621720'>There's</span>
  <span m='1622010'>is</span> <span m='1622200'>a</span> <span m='1622290'>great</span>
  <span m='1622830'>way</span> <span m='1623190'>to</span> <span m='1623370'>fix</span>
  <span m='1623700'>this.</span> <span m='1625440'>If</span> <span m='1625650'>there</span>
  <span m='1625770'>weren't,</span> <span m='1626130'>I</span> <span m='1626220'>wouldn't</span>
  <span m='1626460'>tell</span> <span m='1626730'>you.</span> <span m='1626910'>I</span>
  <span m='1627000'>wouldn't</span> <span m='1627250'>pose</span> <span m='1627720'>the</span>
  <span m='1627810'>problem.</span> <span m='1628840'>So</span> <span m='1628860'>the</span>
  <span m='1628980'>question</span> <span m='1629340'>is</span> <span m='1629820'>how</span>
  <span m='1629970'>to</span> <span m='1630060'>think</span> <span m='1630270'>about</span>
  <span m='1630660'>this</span> <span m='1631000'>scaling</span> <span m='1632520'>in</span>
  <span m='1632670'>order</span> <span m='1632910'>to</span> <span m='1633390'>not</span>
  <span m='1633750'>have</span> <span m='1634110'>the</span> <span m='1634200'>number</span>
  <span m='1634440'>of</span> <span m='1634530'>calculations</span> <span m='1635250'>that</span>
  <span m='1635340'>you</span> <span m='1635460'>need</span> <span m='1635640'>to</span>
  <span m='1635790'>do</span> <span m='1636360'>blow</span> <span m='1636630'>up</span>
  <span m='1636810'>with</span> <span m='1637030'>N</span> <span m='1637080'>square.</span>
  </p><p><span m='1639030'>So</span> <span m='1639750'>in</span> <span m='1639990'>order</span>
  <span m='1640540'>to</span> <span m='1641100'>motivate</span> <span m='1641550'>this,</span>
  <span m='1642330'>I've</span> <span m='1642510'>used</span> <span m='1642810'>a</span>
  <span m='1642870'>funny</span> <span m='1643200'>notation,</span> <span m='1645030'>where</span>
  <span m='1645990'>the</span> <span m='1646170'>W</span> <span m='1647100'>represents</span>
  <span m='1647850'>the</span> <span m='1648030'>N-th</span> <span m='1648360'>primary</span>
  <span m='1648900'>root</span> <span m='1650400'>of</span> <span m='1650610'>1.</span>
  <span m='1652100'>That</span> <span m='1652290'>just</span> <span m='1652470'>saves</span>
  <span m='1652800'>me</span> <span m='1652950'>from</span> <span m='1653160'>writing</span>
  <span m='1653550'>out</span> <span m='1653760'>e to</span> <span m='1654060'>the</span>
  <span m='1654180'>j</span> <span m='1654420'>2</span> <span m='1654660'>pi</span>
  <span m='1654960'>over</span> <span m='1655230'>N</span> <span m='1656190'>64</span>
  <span m='1656790'>times,</span> <span m='1657660'>which</span> <span m='1657930'>when</span>
  <span m='1658110'>I</span> <span m='1658200'>did</span> <span m='1658440'>it,</span>
  <span m='1658660'>it</span> <span m='1658770'>didn't</span> <span m='1659010'>fit</span>
  <span m='1659190'>on</span> <span m='1659340'>one</span> <span m='1659490'>slide.</span>
  <span m='1661080'>I</span> <span m='1661170'>had</span> <span m='1661320'>to</span>
  <span m='1661410'>compress</span> <span m='1661740'>it</span> <span m='1661830'>too</span>
  <span m='1662010'>much,</span> <span m='1662190'>and</span> <span m='1662280'>you</span>
  <span m='1662370'>couldn't</span> <span m='1662580'>see</span> <span m='1662820'>it.</span>
  </p><p><span m='1663960'>So</span> <span m='1664200'>just</span> <span m='1664480'>to</span>
  <span m='1664620'>save</span> <span m='1664920'>space,</span> <span m='1665850'>every</span>
  <span m='1666090'>time</span> <span m='1666330'>I</span> <span m='1666420'>say</span>
  <span m='1667050'>W8,0,</span> <span m='1668820'>all</span> <span m='1669030'>I</span>
  <span m='1669180'>mean</span> <span m='1669510'>is</span> <span m='1670170'>compute</span>
  <span m='1670620'>the</span> <span m='1670890'>eighth</span> <span m='1671290'>root</span>
  <span m='1673130'>of</span> <span m='1673400'>1</span> <span m='1674930'>and</span>
  <span m='1675110'>then</span> <span m='1675530'>raise</span> <span m='1675860'>it</span>
  <span m='1675920'>to</span> <span m='1676070'>the</span> <span m='1676160'>0-th</span>
  <span m='1676490'>power.</span> <span m='1677960'>Compute</span> <span m='1678320'>the</span>
  <span m='1678500'>eighth</span> <span m='1678860'>root</span> <span m='1679250'>of</span>
  <span m='1679460'>1</span> <span m='1680360'>and</span> <span m='1680480'>then</span>
  <span m='1680660'>raise</span> <span m='1680870'>it</span> <span m='1680960'>to</span>
  <span m='1681080'>the</span> <span m='1681200'>seventh</span> <span m='1681530'>power.</span>
  <span m='1681950'>That's</span> <span m='1682100'>all</span> <span m='1682220'>that</span>
  <span m='1682340'>means.</span> </p><p><span m='1684530'>So</span> <span m='1684620'>the</span>
  <span m='1684770'>idea</span> <span m='1685025'>is,</span> <span m='1685280'>is</span>
  <span m='1685670'>there</span> <span m='1685790'>a</span> <span m='1685850'>way</span>
  <span m='1686120'>that</span> <span m='1686240'>we</span> <span m='1686360'>can</span>
  <span m='1686510'>think</span> <span m='1686690'>about</span> <span m='1686840'>the</span>
  <span m='1686930'>structure</span> <span m='1687380'>of</span> <span m='1687470'>this</span>
  <span m='1687710'>matrix</span> <span m='1688700'>more</span> <span m='1688910'>simply?</span>
  <span m='1689840'>And</span> <span m='1689960'>in</span> <span m='1690050'>particular,</span>
  <span m='1690690'>is</span> <span m='1690890'>there</span> <span m='1691040'>a</span>
  <span m='1691100'>way</span> <span m='1692000'>to</span> <span m='1692330'>use</span>
  <span m='1692690'>divide</span> <span m='1692990'>and</span> <span m='1693080'>conquer?</span>
  <span m='1693610'>That's</span> <span m='1693770'>our</span> <span m='1693890'>best</span>
  <span m='1694160'>algorithm.</span> <span m='1695990'>It</span> <span m='1696110'>would</span>
  <span m='1696230'>be</span> <span m='1696380'>great</span> <span m='1696740'>if</span>
  <span m='1696860'>we</span> <span m='1696980'>could</span> <span m='1697100'>take</span>
  <span m='1697370'>the</span> <span m='1697630'>eight-point</span> <span m='1698210'>sequence</span>
  <span m='1701540'>and</span> <span m='1701750'>substitute</span> <span m='1702320'>in</span>
  <span m='1702470'>its</span> <span m='1702650'>place</span> <span m='1704080'>finding</span>
  <span m='1705030'>the</span> <span m='1705380'>frequency</span> <span m='1705740'>representations</span>
  <span m='1706490'>for</span> <span m='1706670'>two</span> <span m='1709580'>four-point</span>
  <span m='1710600'>sequences.</span> <span m='1712700'>And</span> <span m='1712910'>by</span>
  <span m='1713030'>the</span> <span m='1713130'>theory</span> <span m='1713360'>of</span>
  <span m='1713490'>lecture's,</span> <span m='1713750'>that's</span> <span m='1713900'>what</span>
  <span m='1714050'>I'm</span> <span m='1714200'>about</span> <span m='1714440'>to</span>
  <span m='1714560'>do.</span> </p><p><span m='1715590'>So</span> <span m='1715640'>the</span>
  <span m='1715790'>idea</span> <span m='1716210'>is,</span> <span m='1716870'>what</span>
  <span m='1717110'>if</span> <span m='1717260'>I</span> <span m='1717350'>just</span>
  <span m='1717590'>simply</span> <span m='1717950'>took</span> <span m='1718220'>the</span>
  <span m='1718340'>even</span> <span m='1718730'>entries</span> <span m='1719840'>in</span>
  <span m='1720020'>this</span> <span m='1720200'>more</span> <span m='1720350'>complicated</span>
  <span m='1720980'>problem--</span> <span m='1721970'>so</span> <span m='1722120'>I</span>
  <span m='1722210'>have</span> <span m='1722390'>eight</span> <span m='1722630'>entries,</span>
  <span m='1723260'>none</span> <span m='1723440'>of</span> <span m='1723530'>which</span>
  <span m='1723710'>are</span> <span m='1723800'>necessarily</span> <span m='1724430'>0.</span>
  <span m='1725300'>So</span> <span m='1725390'>I</span> <span m='1725480'>have</span>
  <span m='1725660'>x0</span> <span m='1726200'>through</span> <span m='1726560'>x7.</span>
  <span m='1727160'>And</span> <span m='1727250'>I</span> <span m='1727340'>want</span>
  <span m='1727490'>to</span> <span m='1727580'>find</span> <span m='1727820'>the</span>
  <span m='1727910'>frequency</span> <span m='1728360'>representation</span> <span
  m='1729180'>c0</span> <span m='1729890'>through</span> <span m='1730010'>c7.</span>
  </p><p><span m='1732710'>What</span> <span m='1732920'>if</span> <span m='1733040'>I</span>
  <span m='1733130'>just</span> <span m='1733340'>did</span> <span m='1733520'>the</span>
  <span m='1733640'>evens</span> <span m='1734030'>and</span> <span m='1734120'>the</span>
  <span m='1734240'>odds</span> <span m='1734720'>separately?</span> <span m='1736430'>That'd</span>
  <span m='1736580'>be</span> <span m='1736700'>great.</span> <span m='1737870'>In</span>
  <span m='1738020'>order</span> <span m='1738260'>to</span> <span m='1738410'>do</span>
  <span m='1738980'>eight</span> <span m='1739370'>in one</span> <span m='1739550'>fell</span>
  <span m='1739760'>swoop,</span> <span m='1740120'>I</span> <span m='1740210'>need</span>
  <span m='1740420'>64</span> <span m='1740930'>multiplications.</span> <span m='1741890'>In</span>
  <span m='1742040'>order</span> <span m='1742250'>to</span> <span m='1742370'>do</span>
  <span m='1742550'>each</span> <span m='1742820'>of</span> <span m='1742940'>these</span>
  <span m='1743180'>problems,</span> <span m='1743990'>I</span> <span m='1744110'>have</span>
  <span m='1744350'>16</span> <span m='1744890'>for</span> <span m='1745070'>each.</span>
  <span m='1745370'>That's</span> <span m='1745550'>only</span> <span m='1745760'>32,</span>
  <span m='1746250'>I</span> <span m='1746330'>have</span> <span m='1746480'>a</span>
  <span m='1746540'>big</span> <span m='1746690'>win.</span> <span m='1748830'>But</span>
  <span m='1749000'>now,</span> <span m='1749180'>I'm</span> <span m='1749390'>left</span>
  <span m='1749690'>with,</span> <span m='1750230'>is</span> <span m='1750440'>there</span>
  <span m='1750590'>a</span> <span m='1750680'>way</span> <span m='1750890'>to</span>
  <span m='1751010'>relate</span> <span m='1751790'>these</span> <span m='1752180'>things--</span>
  <span m='1752570'>these</span> <span m='1752870'>ak's</span> <span m='1753980'>and</span>
  <span m='1754100'>bk's</span> <span m='1754670'>back</span> <span m='1754910'>to</span>
  <span m='1755030'>the</span> <span m='1755150'>original</span> <span m='1755960'>ck?</span>
  </p><p><span m='1758750'>So</span> <span m='1759080'>the</span> <span m='1759230'>idea</span>
  <span m='1759560'>then</span> <span m='1759890'>is,</span> <span m='1760910'>how</span>
  <span m='1761180'>would</span> <span m='1761360'>you</span> <span m='1761510'>think</span>
  <span m='1761780'>about</span> <span m='1762080'>the</span> <span m='1762170'>contribution</span>
  <span m='1763010'>of</span> <span m='1763100'>the</span> <span m='1763250'>evens,</span>
  <span m='1765560'>as</span> <span m='1765770'>opposed</span> <span m='1766190'>to</span>
  <span m='1766310'>the</span> <span m='1766460'>odds</span> <span m='1768140'>in</span>
  <span m='1768290'>the</span> <span m='1768410'>overall</span> <span m='1768890'>calculation?</span>
  <span m='1770660'>So</span> <span m='1772280'>think</span> <span m='1772520'>about</span>
  <span m='1776250'>the</span> <span m='1776570'>even-numbered</span> <span m='1777710'>entries</span>
  <span m='1778490'>in</span> <span m='1778700'>the</span> <span m='1779150'>signal,</span>
  <span m='1780470'>think</span> <span m='1780650'>about</span> <span m='1780890'>the</span>
  <span m='1780980'>transformation</span> <span m='1781760'>if</span> <span m='1781850'>you</span>
  <span m='1781970'>were</span> <span m='1782090'>to</span> <span m='1782210'>do</span>
  <span m='1782360'>a</span> <span m='1782450'>frequency</span> <span m='1783140'>representation</span>
  <span m='1783890'>for</span> <span m='1784040'>that</span> <span m='1784280'>via</span>
  <span m='1784580'>the</span> <span m='1784690'>Fourier</span> <span m='1784910'>series,</span>
  <span m='1785510'>so</span> <span m='1785690'>that</span> <span m='1785810'>you</span>
  <span m='1785970'>get</span> <span m='1786630'>a0</span> <span m='1787250'>through</span>
  <span m='1787520'>a3.</span> <span m='1789230'>The</span> <span m='1789320'>first</span>
  <span m='1789530'>thing</span> <span m='1789680'>you</span> <span m='1789770'>see</span>
  <span m='1790070'>is</span> <span m='1790250'>that</span> <span m='1790520'>these</span>
  <span m='1790820'>numbers</span> <span m='1791180'>have</span> <span m='1791640'>W</span>
  <span m='1791900'>sub</span> <span m='1792160'>4,</span> <span m='1792870'>the</span>
  <span m='1793040'>fourth</span> <span m='1793390'>root.</span> <span m='1793910'>I</span>
  <span m='1794060'>need</span> <span m='1794420'>W</span> <span m='1794750'>sub</span>
  <span m='1795020'>8,</span> <span m='1795320'>the</span> <span m='1795470'>eighth</span>
  <span m='1795790'>root.</span> </p><p><span m='1797720'>But</span> <span m='1797980'>there's</span>
  <span m='1798380'>a</span> <span m='1798440'>simple</span> <span m='1798770'>identity.</span>
  <span m='1799430'>If</span> <span m='1799550'>I</span> <span m='1799640'>know</span>
  <span m='1799940'>the</span> <span m='1800830'>eighth</span> <span m='1801200'>root,</span>
  <span m='1801620'>I</span> <span m='1801710'>can</span> <span m='1801860'>just</span>
  <span m='1802040'>square</span> <span m='1802430'>it</span> <span m='1802520'>to</span>
  <span m='1802640'>get</span> <span m='1802760'>the</span> <span m='1802850'>fourth</span>
  <span m='1803090'>root.</span> <span m='1804680'>So</span> <span m='1804800'>I</span>
  <span m='1804890'>can</span> <span m='1805040'>rewrite</span> <span m='1805520'>the</span>
  <span m='1805640'>fourth</span> <span m='1805920'>root</span> <span m='1806120'>guys</span>
  <span m='1806480'>in</span> <span m='1806600'>terms</span> <span m='1806900'>of</span>
  <span m='1806990'>equivalent</span> <span m='1807500'>eighth</span> <span m='1807770'>root</span>
  <span m='1808370'>guys.</span> <span m='1810710'>That</span> <span m='1810830'>was</span>
  <span m='1810950'>trivial.</span> <span m='1811700'>Nod</span> <span m='1811910'>your</span>
  <span m='1812000'>head,</span> <span m='1813230'>completely</span> <span m='1813590'>trivial.</span>
  </p><p><span m='1815690'>And</span> <span m='1815840'>then</span> <span m='1816020'>I</span>
  <span m='1816110'>can</span> <span m='1816320'>say,</span> <span m='1816680'>well,</span>
  <span m='1817070'>OK</span> <span m='1817370'>here's</span> <span m='1817640'>my</span>
  <span m='1817760'>problem</span> <span m='1818240'>that</span> <span m='1818360'>I</span>
  <span m='1818450'>would</span> <span m='1818600'>like</span> <span m='1818810'>to</span>
  <span m='1818960'>solve.</span> <span m='1820040'>What</span> <span m='1820250'>if</span>
  <span m='1820370'>I</span> <span m='1820460'>was</span> <span m='1820610'>only</span>
  <span m='1820850'>thinking</span> <span m='1821120'>about</span> <span m='1821330'>the</span>
  <span m='1821450'>contribution</span> <span m='1822050'>of</span> <span m='1822140'>the</span>
  <span m='1822230'>evens?</span> <span m='1824960'>If</span> <span m='1825110'>I'm</span>
  <span m='1825230'>only</span> <span m='1825470'>worried</span> <span m='1825710'>about</span>
  <span m='1825920'>the</span> <span m='1826010'>contributions</span> <span m='1826640'>of</span>
  <span m='1826730'>the</span> <span m='1826850'>evens,</span> <span m='1828020'>then</span>
  <span m='1828200'>I</span> <span m='1828260'>don't</span> <span m='1828440'>need</span>
  <span m='1828590'>to</span> <span m='1828680'>worry</span> <span m='1828920'>about</span>
  <span m='1829220'>some</span> <span m='1829430'>of</span> <span m='1829490'>the</span>
  <span m='1829550'>columns,</span> <span m='1830240'>because</span> <span m='1830510'>they</span>
  <span m='1830630'>don't</span> <span m='1830810'>contribute</span> <span m='1831860'>to</span>
  <span m='1831950'>the</span> <span m='1832100'>evens.</span> <span m='1833360'>That's</span>
  <span m='1833570'>worth</span> <span m='1833750'>thinking</span> <span m='1834050'>about</span>
  <span m='1834290'>things</span> <span m='1834560'>in</span> <span m='1834680'>terms</span>
  <span m='1835010'>of</span> <span m='1835220'>the</span> <span m='1835340'>matrix</span>
  <span m='1836090'>helps</span> <span m='1836420'>us.</span> <span m='1837000'>We</span>
  <span m='1837110'>can</span> <span m='1837260'>visualize</span> <span m='1838160'>operations</span>
  <span m='1839210'>as</span> <span m='1839390'>operations</span> <span m='1839930'>on</span>
  <span m='1840020'>a</span> <span m='1840080'>matrix.</span> </p><p><span m='1841140'>So</span>
  <span m='1841190'>now,</span> <span m='1841430'>if</span> <span m='1841610'>I'm</span>
  <span m='1841730'>only</span> <span m='1841910'>worried</span> <span m='1842150'>about</span>
  <span m='1842330'>the</span> <span m='1842450'>evens,</span> <span m='1842870'>I</span>
  <span m='1842930'>only</span> <span m='1843040'>need</span> <span m='1843260'>to</span>
  <span m='1843320'>worry</span> <span m='1843500'>about</span> <span m='1843710'>four</span>
  <span m='1843890'>of</span> <span m='1843980'>these</span> <span m='1844190'>columns.</span>
  <span m='1846110'>And</span> <span m='1846710'>if</span> <span m='1846860'>I</span>
  <span m='1846950'>squint</span> <span m='1847360'>at</span> <span m='1847490'>this,</span>
  <span m='1848580'>I</span> <span m='1848680'>can</span> <span m='1848780'>see</span>
  <span m='1849080'>that</span> <span m='1849740'>W8,0</span> <span m='1850650'>0,</span>
  <span m='1851105'>0</span> <span m='1851560'>0,</span> <span m='1851960'>that's</span>
  <span m='1852200'>the</span> <span m='1852320'>same</span> <span m='1852560'>row</span>
  <span m='1852790'>as</span> <span m='1852890'>up</span> <span m='1853040'>here.</span>
  <span m='1855440'>So</span> <span m='1855850'>this</span> <span m='1857110'>is</span>
  <span m='1857320'>the</span> <span m='1857440'>same</span> <span m='1857740'>as</span>
  <span m='1857860'>that.</span> <span m='1861490'>And</span> <span m='1861670'>this</span>
  <span m='1861880'>one,</span> <span m='1862810'>W8--</span> <span m='1863330'>so</span>
  <span m='1863620'>those</span> <span m='1863820'>are</span> <span m='1863940'>all</span>
  <span m='1864310'>W8's,</span> <span m='1864760'>I</span> <span m='1864820'>don't</span>
  <span m='1865030'>even</span> <span m='1865140'>to</span> <span m='1865240'>say</span>
  <span m='1865480'>that--</span> <span m='1865690'>0,</span> <span m='1865990'>2,</span>
  <span m='1866290'>4, 6;</span> <span m='1866785'>0,</span> <span m='1867280'>2,</span>
  <span m='1867738'>4,</span> <span m='1868196'>6;</span> <span m='1868654'>0,</span>
  <span m='1869112'>4,</span> <span m='1869570'>0, 4;</span> <span m='1870028'>0,</span>
  <span m='1870490'>4,</span> <span m='1870775'>0,</span> <span m='1871060'>4.</span>
  <span m='1871960'>These</span> <span m='1872260'>numbers</span> <span m='1872620'>are</span>
  <span m='1872710'>just</span> <span m='1872920'>the</span> <span m='1873325'>eight</span>
  <span m='1873730'>coefficients.</span> </p><p><span m='1875440'>Furthermore,</span>
  <span m='1875920'>it</span> <span m='1875980'>repeats.</span> <span m='1877222'>0,</span>
  <span m='1877560'>0,</span> <span m='1878013'>0,</span> <span m='1878466'>0</span>
  <span m='1878920'>is the same as</span> <span m='1879130'>0, 0,</span> <span m='1879506'>0,</span>
  <span m='1879882'>0.</span> <span m='1880260'>So</span> <span m='1880360'>that's</span>
  <span m='1880690'>8,0,</span> <span m='1881050'>and</span> <span m='1881140'>that's</span>
  <span m='1881370'>8,0.</span> <span m='1883210'>What</span> <span m='1883390'>I</span>
  <span m='1883450'>just</span> <span m='1883690'>found</span> <span m='1884000'>was</span>
  <span m='1884140'>that</span> <span m='1884260'>the</span> <span m='1884380'>way</span>
  <span m='1884530'>the</span> <span m='1884710'>evens</span> <span m='1885160'>effect</span>
  <span m='1885500'>the</span> <span m='1885550'>answer</span> <span m='1887500'>is</span>
  <span m='1887680'>precisely</span> <span m='1889120'>by</span> <span m='1889270'>taking</span>
  <span m='1890020'>their</span> <span m='1890500'>Fourier</span> <span m='1891700'>representation</span>
  <span m='1892510'>and</span> <span m='1892690'>repeating</span> <span m='1893140'>it</span>
  <span m='1893200'>twice</span> <span m='1893560'>in</span> <span m='1893650'>time.</span>
  </p><p><span m='1895110'>Well,</span> <span m='1895310'>that's</span> <span m='1895420'>pretty</span>
  <span m='1895600'>cute.</span> <span m='1898840'>So</span> <span m='1899050'>therefore,</span>
  <span m='1899920'>the</span> <span m='1900040'>contribution</span> <span m='1902050'>of</span>
  <span m='1902200'>the</span> <span m='1902320'>four-length</span> <span m='1902890'>sequences</span>
  <span m='1903550'>to</span> <span m='1903670'>the</span> <span m='1903850'>eight-length</span>
  <span m='1904430'>sequences</span> <span m='1904770'>is</span> <span m='1905110'>showed</span>
  <span m='1905440'>this</span> <span m='1905590'>way.</span> <span m='1906910'>Stack</span>
  <span m='1907360'>up</span> <span m='1907510'>the</span> <span m='1907600'>frequency</span>
  <span m='1908020'>representations</span> <span m='1908890'>for</span> <span m='1909100'>the</span>
  <span m='1909720'>four,</span> <span m='1910390'>and</span> <span m='1910540'>that</span>
  <span m='1910750'>is</span> <span m='1910900'>their</span> <span m='1911080'>contribution</span>
  <span m='1911710'>to</span> <span m='1911770'>the</span> <span m='1911970'>eight.</span>
  </p><p><span m='1913720'>The</span> <span m='1913870'>same</span> <span m='1914080'>sort</span>
  <span m='1914290'>of</span> <span m='1914350'>thing</span> <span m='1914530'>happens</span>
  <span m='1914860'>when</span> <span m='1915010'>I</span> <span m='1915100'>do</span>
  <span m='1915220'>the</span> <span m='1915400'>odds.</span> <span m='1917200'>Now,</span>
  <span m='1917440'>if</span> <span m='1917560'>I</span> <span m='1917680'>only</span>
  <span m='1917920'>look</span> <span m='1918070'>at</span> <span m='1918190'>the</span>
  <span m='1918370'>odds,</span> <span m='1920340'>I</span> <span m='1920470'>throw</span>
  <span m='1920740'>away</span> <span m='1920950'>a</span> <span m='1921010'>different</span>
  <span m='1921340'>set</span> <span m='1921550'>of</span> <span m='1921610'>four</span>
  <span m='1921820'>columns.</span> <span m='1924010'>And</span> <span m='1924190'>now,</span>
  <span m='1924430'>if</span> <span m='1924550'>I</span> <span m='1924610'>try</span>
  <span m='1924850'>to</span> <span m='1924910'>compare</span> <span m='1925390'>that</span>
  <span m='1926110'>to</span> <span m='1926290'>what</span> <span m='1927520'>I</span>
  <span m='1927610'>have</span> <span m='1927790'>up</span> <span m='1927940'>here</span>
  <span m='1928120'>for</span> <span m='1928300'>the</span> <span m='1928450'>odds,</span>
  <span m='1930380'>I</span> <span m='1930470'>don't</span> <span m='1930590'>quite</span>
  <span m='1930770'>get</span> <span m='1930950'>something</span> <span m='1931370'>as</span>
  <span m='1931520'>easy.</span> </p><p><span m='1932300'>So</span> <span m='1932420'>if</span>
  <span m='1932510'>I</span> <span m='1932590'>look</span> <span m='1932780'>down</span>
  <span m='1933050'>this</span> <span m='1933920'>column,</span> <span m='1934820'>they</span>
  <span m='1934940'>should</span> <span m='1935120'>have</span> <span m='1935210'>all</span>
  <span m='1935300'>been</span> <span m='1935510'>0.</span> <span m='1936020'>But</span>
  <span m='1936140'>if</span> <span m='1936200'>I</span> <span m='1936290'>look</span>
  <span m='1936440'>down</span> <span m='1936680'>this</span> <span m='1936860'>column,</span>
  <span m='1937370'>it's</span> <span m='1937610'>0,</span> <span m='1937820'>1,</span>
  <span m='1938266'>2,</span> <span m='1938712'>3,</span> <span m='1939158'>4, 5,</span>
  <span m='1939604'>6,</span> <span m='1940050'>7.</span> <span m='1942500'>If</span>
  <span m='1942650'>I</span> <span m='1942710'>look</span> <span m='1942880'>down</span>
  <span m='1943100'>this</span> <span m='1943280'>column--</span> <span m='1943640'>0,</span>
  <span m='1944042'>2,</span> <span m='1944444'>4;</span> <span m='1944846'>0,</span>
  <span m='1945248'>3,</span> <span m='1945650'>6--</span> <span m='1946460'>I'm</span>
  <span m='1946550'>not</span> <span m='1946670'>quite</span> <span m='1946820'>getting</span>
  <span m='1947060'>the</span> <span m='1947150'>right</span> <span m='1947330'>answers.</span>
  <span m='1949910'>But</span> <span m='1949940'>it</span> <span m='1950000'>turns</span>
  <span m='1950300'>out</span> <span m='1950930'>that,</span> <span m='1951080'>if</span>
  <span m='1951170'>I</span> <span m='1951260'>simply</span> <span m='1951650'>factor</span>
  <span m='1952580'>this</span> <span m='1952940'>number</span> <span m='1953810'>out,</span>
  <span m='1956960'>so</span> <span m='1957040'>that</span> <span m='1957190'>I</span>
  <span m='1957280'>make</span> <span m='1957460'>the</span> <span m='1957550'>first</span>
  <span m='1957790'>coefficient</span> <span m='1958330'>right,</span> <span m='1959130'>all</span>
  <span m='1959300'>of</span> <span m='1959410'>the</span> <span m='1959500'>other</span>
  <span m='1959680'>coefficients</span> <span m='1960190'>are</span> <span m='1960250'>right</span>
  <span m='1960460'>too.</span> </p><p><span m='1964070'>So</span> <span m='1964630'>I</span>
  <span m='1964760'>got</span> <span m='1964960'>an</span> <span m='1965080'>easy</span>
  <span m='1965410'>rule</span> <span m='1965680'>now</span> <span m='1966100'>for</span>
  <span m='1966370'>how</span> <span m='1967180'>the</span> <span m='1968290'>Fourier</span>
  <span m='1968590'>coefficients</span> <span m='1969220'>for</span> <span m='1969400'>the</span>
  <span m='1969550'>odds</span> <span m='1971900'>contribute</span> <span m='1972470'>to</span>
  <span m='1972650'>the</span> <span m='1972830'>answer</span> <span m='1973460'>for</span>
  <span m='1973700'>the</span> <span m='1973820'>eight-length</span> <span m='1974210'>sequence.</span>
  <span m='1975800'>And</span> <span m='1975920'>now,</span> <span m='1976250'>all
  I</span> <span m='1976340'>need</span> <span m='1976520'>to</span> <span m='1976610'>do</span>
  <span m='1976760'>is</span> <span m='1976850'>glue</span> <span m='1977060'>those</span>
  <span m='1977300'>two</span> <span m='1977450'>together.</span> <span m='1980200'>So</span>
  <span m='1980310'>the</span> <span m='1980430'>way</span> <span m='1980640'>I</span>
  <span m='1980760'>can</span> <span m='1980940'>calculate</span> <span m='1981510'>the</span>
  <span m='1981860'>eight-length</span> <span m='1982410'>sequence</span> <span m='1984450'>is</span>
  <span m='1984660'>to</span> <span m='1984810'>calculate</span> <span m='1986400'>the</span>
  <span m='1987450'>a's</span> <span m='1987780'>and</span> <span m='1987900'>b's</span>
  <span m='1989540'>from</span> <span m='1989970'>four-length</span> <span m='1990490'>sequences</span>
  <span m='1992890'>and</span> <span m='1993070'>then</span> <span m='1993280'>paste</span>
  <span m='1993670'>them</span> <span m='1993880'>together</span> <span m='1994330'>this</span>
  <span m='1994540'>way.</span> <span m='1996190'>And</span> <span m='1996340'>I'll</span>
  <span m='1996460'>get</span> <span m='1996790'>the</span> <span m='1997050'>eight-length</span>
  <span m='1997660'>answer.</span> </p><p><span m='1999230'>Now,</span> <span m='2000090'>pasting</span>
  <span m='2000510'>them</span> <span m='2000630'>together</span> <span m='2001050'>takes</span>
  <span m='2001290'>some</span> <span m='2001410'>multiplies.</span> <span m='2003570'>So</span>
  <span m='2003730'>it</span> <span m='2003840'>took</span> <span m='2004050'>me</span>
  <span m='2004200'>16</span> <span m='2004770'>to</span> <span m='2004860'>compute</span>
  <span m='2005340'>the</span> <span m='2007260'>a0</span> <span m='2007770'>to</span>
  <span m='2007870'>a3.</span> <span m='2008400'>It</span> <span m='2008460'>took</span>
  <span m='2008610'>me</span> <span m='2008730'>16</span> <span m='2009150'>multiplies</span>
  <span m='2009720'>to</span> <span m='2009840'>figure</span> <span m='2010140'>out</span>
  <span m='2011252'>b0</span> <span m='2012020'>to</span> <span m='2012110'>b3.</span>
  <span m='2014540'>So I'm</span> <span m='2014900'>up</span> <span m='2015020'>to</span>
  <span m='2015130'>32.</span> <span m='2016660'>Then</span> <span m='2016840'>I</span>
  <span m='2016900'>have</span> <span m='2017080'>to</span> <span m='2017170'>do</span>
  <span m='2017440'>eight</span> <span m='2017710'>more</span> <span m='2020580'>to</span>
  <span m='2020770'>make</span> <span m='2020980'>the</span> <span m='2021100'>b's</span>
  <span m='2021430'>look</span> <span m='2021640'>right.</span> <span m='2023740'>So</span>
  <span m='2023890'>if</span> <span m='2023950'>I</span> <span m='2024040'>just</span>
  <span m='2024220'>count</span> <span m='2024460'>multiplies,</span> <span m='2025350'>I'm</span>
  <span m='2025450'>now</span> <span m='2025660'>doing</span> <span m='2025930'>40.</span>
  </p><p><span m='2027940'>But</span> <span m='2028090'>that's</span> <span m='2028270'>a</span>
  <span m='2028330'>win,</span> <span m='2028600'>because</span> <span m='2028930'>that's</span>
  <span m='2029170'>compared</span> <span m='2029530'>to</span> <span m='2029800'>64.</span>
  <span m='2031750'>And</span> <span m='2031870'>I</span> <span m='2031930'>get</span>
  <span m='2032110'>precisely</span> <span m='2032680'>the</span> <span m='2032800'>same</span>
  <span m='2033040'>answer.</span> <span m='2034000'>That</span> <span m='2034240'>algorithm--</span>
  <span m='2035710'>that's</span> <span m='2035890'>an</span> <span m='2035980'>algorithm;</span>
  <span m='2036850'>that's</span> <span m='2037350'>a</span> <span m='2037480'>rule-based</span>
  <span m='2038050'>system</span> <span m='2038470'>for</span> <span m='2038620'>how</span>
  <span m='2038770'>you</span> <span m='2038950'>take</span> <span m='2039610'>one</span>
  <span m='2039880'>set</span> <span m='2040060'>of</span> <span m='2040150'>eight</span>
  <span m='2040270'>numbers</span> <span m='2040600'>and</span> <span m='2040690'>turn</span>
  <span m='2040870'>it</span> <span m='2040930'>into</span> <span m='2041140'>a</span>
  <span m='2041200'>different</span> <span m='2041500'>set</span> <span m='2041680'>of</span>
  <span m='2041770'>eight</span> <span m='2041890'>numbers--</span> <span m='2042250'>that</span>
  <span m='2042430'>algorithm</span> <span m='2043120'>is</span> <span m='2043240'>called</span>
  <span m='2043420'>the</span> <span m='2043570'>FFT,</span> <span m='2045250'>the</span>
  <span m='2045400'>Fast</span> <span m='2045760'>Fourier</span> <span m='2046120'>Transform.</span>
  <span m='2047050'>That's</span> <span m='2047320'>mostly</span> <span m='2047800'>to</span>
  <span m='2047890'>confuse</span> <span m='2048340'>you,</span> <span m='2049600'>because</span>
  <span m='2049900'>it's</span> <span m='2050020'>not</span> <span m='2050170'>a</span>
  <span m='2050239'>transform,</span> <span m='2051500'>but</span> <span m='2051520'>it</span>
  <span m='2051610'>is</span> <span m='2051760'>fast.</span> </p><p><span m='2053482'>So
  it's</span> <span m='2053889'>really a</span> <span m='2054280'>fast</span> <span
  m='2054639'>Fourier</span> <span m='2055030'>series.</span> <span m='2056620'>And</span>
  <span m='2056739'>in</span> <span m='2056830'>fact,</span> <span m='2057040'>the</span>
  <span m='2057100'>guys</span> <span m='2057370'>who</span> <span m='2057460'>figured</span>
  <span m='2057760'>it</span> <span m='2057820'>out</span> <span m='2058030'>knew</span>
  <span m='2058270'>that.</span> <span m='2058610'>And I</span> <span m='2058690'>don't</span>
  <span m='2058810'>know</span> <span m='2058960'>why</span> <span m='2059199'>we</span>
  <span m='2059590'>insist</span> <span m='2059980'>on</span> <span m='2060100'>trying</span>
  <span m='2060310'>to</span> <span m='2060400'>confuse</span> <span m='2060760'>you.</span>
  <span m='2061290'>That's</span> <span m='2061540'>perhaps</span> <span m='2061989'>our</span>
  <span m='2062110'>job.</span> <span m='2063090'>But</span> <span m='2063400'>the</span>
  <span m='2063699'>FFT,</span> <span m='2064540'>fast</span> <span m='2064889'>Fourier</span>
  <span m='2065170'>transform,</span> <span m='2065650'>is</span> <span m='2065739'>really</span>
  <span m='2066010'>the</span> <span m='2066130'>fast</span> <span m='2066429'>Fourier</span>
  <span m='2066909'>series.</span> </p><p><span m='2068350'>And</span> <span m='2068469'>the</span>
  <span m='2068590'>idea</span> <span m='2069070'>is</span> <span m='2069460'>that</span>
  <span m='2070420'>it's</span> <span m='2070600'>a</span> <span m='2070659'>divide</span>
  <span m='2070960'>and</span> <span m='2071050'>conquer</span> <span m='2071380'>thing.</span>
  <span m='2072580'>So</span> <span m='2073060'>if</span> <span m='2073239'>you</span>
  <span m='2073330'>think</span> <span m='2073510'>about</span> <span m='2073750'>extending</span>
  <span m='2074199'>it--</span> <span m='2074440'>So I motivated</span> <span m='2074725'>it</span>
  <span m='2075010'>by</span> <span m='2075219'>thinking</span> <span m='2075520'>about</span>
  <span m='2075760'>how</span> <span m='2075909'>to</span> <span m='2076000'>calculate</span>
  <span m='2076520'>the</span> <span m='2076650'>8</span> <span m='2076840'>by</span>
  <span m='2077320'>8</span> <span m='2078250'>from</span> <span m='2078760'>two</span>
  <span m='2078969'>4</span> <span m='2079179'>by</span> <span m='2079330'>4's.</span>
  <span m='2080190'>But</span> <span m='2080380'>let's</span> <span m='2080530'>start</span>
  <span m='2080830'>from</span> <span m='2081070'>0</span> <span m='2081550'>and</span>
  <span m='2081670'>say,</span> <span m='2082300'>let's</span> <span m='2082480'>like</span>
  <span m='2082659'>capital</span> <span m='2083110'>M</span> <span m='2083350'>represent</span>
  <span m='2083800'>however</span> <span m='2084150'>multiplies</span> <span m='2084639'>it</span>
  <span m='2084699'>took</span> <span m='2084880'>to</span> <span m='2085000'>get</span>
  <span m='2085120'>an</span> <span m='2085320'>endpoint</span> <span m='2086350'>FFT.</span>
  </p><p><span m='2088989'>How</span> <span m='2089139'>many</span> <span m='2089350'>multiplies</span>
  <span m='2089980'>does</span> <span m='2090130'>it</span> <span m='2090190'>take</span>
  <span m='2090460'>to</span> <span m='2090610'>do</span> <span m='2090730'>a</span>
  <span m='2090860'>1-point</span> <span m='2091190'>FFT?</span> <span m='2093639'>If</span>
  <span m='2093820'>my</span> <span m='2093969'>signal</span> <span m='2094420'>is</span>
  <span m='2094570'>periodic</span> <span m='2095320'>in</span> <span m='2095650'>1--</span>
  <span m='2100340'>so</span> <span m='2100580'>what's</span> <span m='2100940'>the</span>
  <span m='2101540'>relationship</span> <span m='2102260'>between</span> <span m='2102710'>the</span>
  <span m='2103160'>series</span> <span m='2103760'>representation</span> <span m='2104690'>and</span>
  <span m='2105050'>the</span> <span m='2105170'>time</span> <span m='2105620'>representation</span>
  <span m='2106490'>if</span> <span m='2106760'>the</span> <span m='2106910'>length</span>
  <span m='2107330'>is</span> <span m='2108230'>capital</span> <span m='2108640'>N</span>
  <span m='2108830'>equals</span> <span m='2109190'>1?</span> </p><p><span m='2112650'>The</span>
  <span m='2112850'>relationship</span> <span m='2113430'>is</span> <span m='2113550'>identity.</span>
  <span m='2115710'>If</span> <span m='2115920'>my</span> <span m='2116040'>sequence</span>
  <span m='2116460'>was</span> <span m='2116700'>17,</span> <span m='2117150'>17,</span>
  <span m='2117570'>17,</span> <span m='2117990'>17,</span> <span m='2118410'>17,</span>
  <span m='2118800'>17,</span> <span m='2119220'>17,</span> <span m='2119640'>17,</span>
  <span m='2120060'>17,</span> <span m='2120480'>17,</span> <span m='2121500'>which</span>
  <span m='2121770'>is</span> <span m='2122040'>a</span> <span m='2122190'>sequence</span>
  <span m='2122730'>that</span> <span m='2122910'>has</span> <span m='2124210'>a</span>
  <span m='2124260'>period</span> <span m='2124800'>of</span> <span m='2125040'>1,</span>
  <span m='2126570'>then</span> <span m='2126840'>the</span> <span m='2127590'>series</span>
  <span m='2128280'>representation</span> <span m='2128940'>is</span> <span m='2129620'>17,</span>
  <span m='2130030'>17,</span> <span m='2130510'>17,</span> <span m='2130915'>17--</span>
  <span m='2131320'>not</span> <span m='2131520'>all</span> <span m='2131670'>that</span>
  <span m='2131780'>surprising.</span> <span m='2132660'>So</span> <span m='2132830'>it</span>
  <span m='2132900'>takes</span> <span m='2133110'>exactly</span> <span m='2133470'>0</span>
  <span m='2133770'>multiplies</span> <span m='2134670'>to</span> <span m='2134760'>calculate</span>
  <span m='2135270'>that</span> <span m='2135480'>one.</span> </p><p><span m='2137280'>How</span>
  <span m='2137370'>many</span> <span m='2137580'>multiplies</span> <span m='2138150'>does</span>
  <span m='2138300'>it</span> <span m='2138360'>take</span> <span m='2138570'>to</span>
  <span m='2138750'>calculate</span> <span m='2139370'>a</span> <span m='2139440'>length</span>
  <span m='2139800'>2?</span> <span m='2141810'>Well,</span> <span m='2141990'>you</span>
  <span m='2142140'>do</span> <span m='2142320'>two</span> <span m='2142560'>length</span>
  <span m='2142860'>1</span> <span m='2143100'>problems.</span> <span m='2145210'>And</span>
  <span m='2145390'>then</span> <span m='2145630'>because</span> <span m='2145960'>it's</span>
  <span m='2146110'>length</span> <span m='2146380'>2,</span> <span m='2146650'>you</span>
  <span m='2146770'>have</span> <span m='2146890'>to</span> <span m='2147010'>do</span>
  <span m='2147160'>those</span> <span m='2147370'>two</span> <span m='2147580'>extra</span>
  <span m='2147910'>multiplies.</span> <span m='2150690'>Then</span> <span m='2151230'>take</span>
  <span m='2151590'>a</span> <span m='2151650'>length</span> <span m='2151950'>2</span>
  <span m='2152190'>and</span> <span m='2152280'>turn</span> <span m='2152460'>it</span>
  <span m='2152550'>into</span> <span m='2152790'>a</span> <span m='2152850'>4,</span>
  <span m='2153300'>how</span> <span m='2153390'>many</span> <span m='2153570'>multiplies</span>
  <span m='2154050'>for</span> <span m='2154100'>4?</span> <span m='2154230'>Well,</span>
  <span m='2154460'>you</span> <span m='2154530'>have</span> <span m='2154620'>to</span>
  <span m='2154710'>do</span> <span m='2154860'>two</span> <span m='2155100'>length</span>
  <span m='2155430'>2,</span> <span m='2156510'>but</span> <span m='2156720'>now</span>
  <span m='2156930'>it's</span> <span m='2157080'>length</span> <span m='2157270'>4,</span>
  <span m='2158310'>so</span> <span m='2158460'>there's</span> <span m='2158640'>4</span>
  <span m='2159000'>gluing</span> <span m='2159870'>multiplies.</span> </p><p><span
  m='2162560'>To</span> <span m='2162740'>do</span> <span m='2163350'>32,</span> <span
  m='2163980'>you</span> <span m='2164130'>have</span> <span m='2164280'>to</span>
  <span m='2164370'>do</span> <span m='2164550'>two</span> <span m='2164760'>length</span>
  <span m='2165030'>16.</span> <span m='2165630'>And</span> <span m='2165720'>then</span>
  <span m='2165870'>there's</span> <span m='2166020'>32</span> <span m='2166560'>gluing.</span>
  <span m='2167850'>When</span> <span m='2168000'>you're</span> <span m='2168150'>all</span>
  <span m='2168420'>done,</span> <span m='2169510'>it</span> <span m='2169530'>takes</span>
  <span m='2170320'>eight</span> <span m='2171220'>N</span> <span m='2171750'>times</span>
  <span m='2172110'>log</span> <span m='2172460'>N.</span> <span m='2174510'>And</span>
  <span m='2174690'>the</span> <span m='2174780'>point</span> <span m='2175050'>is</span>
  <span m='2175260'>that</span> <span m='2175350'>N</span> <span m='2175500'>times</span>
  <span m='2175790'>log</span> <span m='2176080'>N</span> <span m='2176580'>can</span>
  <span m='2176730'>be</span> <span m='2176880'>a</span> <span m='2176940'>lot</span>
  <span m='2177210'>smaller</span> <span m='2178230'>than</span> <span m='2178920'>N</span>
  <span m='2179370'>squared.</span> </p><p><span m='2182680'>So</span> <span m='2182840'>let's</span>
  <span m='2182990'>go</span> <span m='2183080'>back</span> <span m='2183260'>to</span>
  <span m='2183350'>the</span> <span m='2183410'>motivational</span> <span m='2184040'>example.</span>
  <span m='2184460'>The</span> <span m='2184580'>idea</span> <span m='2184850'>was,</span>
  <span m='2185090'>what</span> <span m='2185270'>if</span> <span m='2185390'>I</span>
  <span m='2185510'>had</span> <span m='2186740'>about</span> <span m='2188450'>10</span>
  <span m='2188690'>to</span> <span m='2188750'>the</span> <span m='2188870'>sixth</span>
  <span m='2190040'>unknowns?</span> <span m='2192110'>So</span> <span m='2192260'>that's</span>
  <span m='2192500'>about</span> <span m='2193760'>2</span> <span m='2194000'>to</span>
  <span m='2194090'>the</span> <span m='2194690'>20th?</span> </p><p><span m='2196670'>Yeah,</span>
  <span m='2196820'>that's</span> <span m='2196970'>right.</span> <span m='2197150'>So</span>
  <span m='2197270'>2</span> <span m='2197410'>to</span> <span m='2197500'>the</span>
  <span m='2197590'>10th</span> <span m='2197720'>is</span> <span m='2198140'>10</span>
  <span m='2198380'>cubed</span> <span m='2199160'>roughly.</span> <span m='2200120'>1,024</span>
  <span m='2200620'>is</span> <span m='2200820'>1,000</span> <span m='2202310'>in</span>
  <span m='2202460'>CS</span> <span m='2202720'>terms.</span> <span m='2203880'>So</span>
  <span m='2203930'>I</span> <span m='2203990'>have</span> <span m='2204110'>about</span>
  <span m='2204350'>2</span> <span m='2204520'>to</span> <span m='2204620'>the</span>
  <span m='2204710'>20th.</span> <span m='2206190'>So</span> <span m='2206300'>what</span>
  <span m='2206510'>would</span> <span m='2206690'>be</span> <span m='2207020'>the</span>
  <span m='2207380'>savings</span> <span m='2208130'>if</span> <span m='2208370'>I</span>
  <span m='2208490'>did</span> <span m='2208940'>the</span> <span m='2209360'>FFT</span>
  <span m='2210020'>rather</span> <span m='2210470'>than</span> <span m='2210710'>the</span>
  <span m='2210800'>direct</span> <span m='2211110'>form</span> <span m='2211970'>N</span>
  <span m='2212150'>squared?</span> </p><p><span m='2215968'>AUDIENCE:</span> <span
  m='2216462'>That</span> <span m='2216956'>would</span> <span m='2217450'>be</span>
  <span m='2219426'>2 to the 20th</span> <span m='2219920'>divided</span> <span m='2220414'>by</span>
  <span m='2220908'>[INAUDIBLE].</span> </p><p><span m='2222610'>DENNIS FREEMAN:</span>
  <span m='2223090'>So</span> <span m='2223570'>I</span> <span m='2223900'>need</span>
  <span m='2224110'>to</span> <span m='2224200'>take</span> <span m='2224860'>2</span>
  <span m='2225050'>to</span> <span m='2225220'>20th</span> <span m='2225640'>times</span>
  <span m='2226030'>2 to the</span> <span m='2226270'>20th</span> <span m='2227560'>would</span>
  <span m='2227710'>be</span> <span m='2227830'>the</span> <span m='2228010'>N</span>
  <span m='2228180'>squared</span> <span m='2228630'>algorithm.</span> <span m='2229560'>And</span>
  <span m='2229780'>the</span> <span m='2229900'>other</span> <span m='2230110'>algorithm</span>
  <span m='2230560'>would</span> <span m='2230730'>be</span> <span m='2230980'>2</span>
  <span m='2231190'>to the</span> <span m='2231360'>20th--</span> </p><p><span m='2232316'>AUDIENCE:</span>
  <span m='2232722'>By</span> <span m='2233128'>20.</span> </p><p><span m='2233534'>DENNIS
  FREEMAN:</span> <span m='2233940'>--divided</span> <span m='2234250'>by</span> <span
  m='2234400'>20.</span> <span m='2235750'>It's</span> <span m='2235910'>enormous</span>
  <span m='2236440'>difference,</span> <span m='2236860'>that's</span> <span m='2237040'>the</span>
  <span m='2237130'>point.</span> <span m='2240040'>So</span> <span m='2241420'>just</span>
  <span m='2241750'>a</span> <span m='2241840'>little</span> <span m='2242140'>bit</span>
  <span m='2242350'>of</span> <span m='2242500'>historic</span> <span m='2242890'>context.</span>
  <span m='2243540'>That</span> <span m='2243760'>algorithm</span> <span m='2244240'>has</span>
  <span m='2244420'>been</span> <span m='2245500'>repeatedly</span> <span m='2246070'>invented</span>
  <span m='2246490'>in</span> <span m='2247510'>time.</span> <span m='2249160'>So</span>
  <span m='2249310'>we</span> <span m='2249520'>usually</span> <span m='2250000'>cite</span>
  <span m='2250270'>Cooley</span> <span m='2250600'>and</span> <span m='2250780'>Tukey.</span>
  <span m='2251410'>They</span> <span m='2251560'>wrote</span> <span m='2251730'>a</span>
  <span m='2251770'>classic</span> <span m='2252160'>paper</span> <span m='2252430'>in</span>
  <span m='2252490'>1965.</span> </p><p><span m='2253540'>The</span> <span m='2253630'>title</span>
  <span m='2253870'>of</span> <span m='2253930'>their</span> <span m='2254050'>paper</span>
  <span m='2254440'>was</span> <span m='2256900'>"An</span> <span m='2257410'>Algorithm</span>
  <span m='2258100'>for</span> <span m='2258250'>the</span> <span m='2258340'>Machine</span>
  <span m='2258700'>Calculation</span> <span m='2259270'>of</span> <span m='2259360'>Complex</span>
  <span m='2259780'>Fourier</span> <span m='2260110'>Series."</span> <span m='2260990'>They</span>
  <span m='2261050'>knew</span> <span m='2261270'>it</span> <span m='2261360'>was</span>
  <span m='2261530'>series.</span> <span m='2263060'>That</span> <span m='2263230'>was</span>
  <span m='2263350'>1965.</span> <span m='2264290'>That</span> <span m='2264310'>was</span>
  <span m='2264490'>when</span> <span m='2264640'>computers</span> <span m='2265090'>were</span>
  <span m='2265210'>starting</span> <span m='2265600'>to</span> <span m='2265720'>get</span>
  <span m='2265870'>big.</span> </p><p><span m='2267640'>They</span> <span m='2267820'>actually</span>
  <span m='2268120'>went</span> <span m='2268300'>on</span> <span m='2268540'>and</span>
  <span m='2268750'>solved</span> <span m='2269080'>some</span> <span m='2269230'>very</span>
  <span m='2269980'>interesting</span> <span m='2270460'>problems,</span> <span m='2271060'>including</span>
  <span m='2271420'>neuroscience.</span> <span m='2272080'>They</span> <span m='2272290'>were</span>
  <span m='2272470'>the</span> <span m='2272590'>first</span> <span m='2272770'>people</span>
  <span m='2273190'>who</span> <span m='2273880'>solved</span> <span m='2274240'>Hodgkin-Huxley's</span>
  <span m='2274930'>model</span> <span m='2275230'>for</span> <span m='2275440'>a</span>
  <span m='2275530'>propagated</span> <span m='2276040'>action</span> <span m='2276280'>potential</span>
  <span m='2276700'>and</span> <span m='2276790'>showed</span> <span m='2277000'>that</span>
  <span m='2277750'>the</span> <span m='2277840'>equations</span> <span m='2278095'>that</span>
  <span m='2278350'>Hodgkin</span> <span m='2278450'>and</span> <span m='2278800'>Huxley</span>
  <span m='2279080'>had</span> <span m='2279160'>found</span> <span m='2279370'>for</span>
  <span m='2279490'>biology</span> <span m='2280030'>actually</span> <span m='2280330'>work.</span>
  <span m='2281690'>So</span> <span m='2281710'>that</span> <span m='2281830'>was</span>
  <span m='2281950'>1965.</span> </p><p><span m='2283350'>However,</span> <span m='2284740'>before</span>
  <span m='2285190'>them</span> <span m='2285400'>in</span> <span m='2285490'>1942,</span>
  <span m='2286920'>Danielson</span> <span m='2287430'>and</span> <span m='2288040'>Lanczos</span>
  <span m='2288730'>had</span> <span m='2289540'>independently</span> <span m='2290140'>discovered</span>
  <span m='2290590'>it.</span> <span m='2291040'>In</span> <span m='2291420'>1903,</span>
  <span m='2292380'>Runge</span> <span m='2292870'>had</span> <span m='2293050'>discovered</span>
  <span m='2293530'>it.</span> <span m='2294040'>And,</span> <span m='2295030'>in</span>
  <span m='2295540'>1805,</span> <span m='2297940'>Gauss</span> <span m='2299770'>described</span>
  <span m='2300310'>it.</span> </p><p><span m='2301600'>Now,</span> <span m='2301870'>there's</span>
  <span m='2302080'>a</span> <span m='2302140'>good</span> <span m='2302380'>reason</span>
  <span m='2302800'>why</span> <span m='2303010'>all</span> <span m='2303160'>these</span>
  <span m='2304630'>brilliant</span> <span m='2305020'>scientists--</span> <span m='2306330'>so</span>
  <span m='2306610'>Gauss</span> <span m='2307630'>noted</span> <span m='2308050'>it</span>
  <span m='2309010'>and</span> <span m='2309130'>even</span> <span m='2309430'>used</span>
  <span m='2309800'>it,</span> <span m='2310210'>but</span> <span m='2310330'>he</span>
  <span m='2310420'>commented</span> <span m='2310960'>on</span> <span m='2311110'>how</span>
  <span m='2311350'>useless</span> <span m='2311890'>it</span> <span m='2312010'>was.</span>
  <span m='2315060'>Why</span> <span m='2315310'>would</span> <span m='2315460'>Gauss</span>
  <span m='2315850'>think</span> <span m='2316060'>it</span> <span m='2316150'>was</span>
  <span m='2316300'>useless?</span> <span m='2316690'>He</span> <span m='2316780'>was</span>
  <span m='2316900'>kind</span> <span m='2317050'>of</span> <span m='2317140'>smart.</span>
  </p><p><span m='2317953'>AUDIENCE:</span> <span m='2318436'>Was</span> <span m='2318919'>Fourier</span>
  <span m='2319402'>alive</span> <span m='2319885'>then?</span> </p><p><span m='2320780'>DENNIS
  FREEMAN:</span> <span m='2321160'>So</span> <span m='2321640'>Gauss</span> <span
  m='2322030'>actually</span> <span m='2322420'>died</span> <span m='2322840'>before</span>
  <span m='2323110'>he</span> <span m='2323230'>published</span> <span m='2323620'>this.</span>
  <span m='2324780'>But</span> <span m='2325090'>it</span> <span m='2325180'>got</span>
  <span m='2325390'>published</span> <span m='2325960'>posthumously</span> <span m='2327670'>before</span>
  <span m='2328180'>Fourier</span> <span m='2328630'>started to</span> <span m='2328970'>work.</span>
  <span m='2330130'>So</span> <span m='2330280'>this</span> <span m='2330430'>came</span>
  <span m='2330640'>before</span> <span m='2330870'>Fourier.</span> </p><p><span m='2332966'>AUDIENCE:</span>
  <span m='2333458'>[INAUDIBLE].</span> </p><p><span m='2334442'>DENNIS FREEMAN:</span>
  <span m='2334940'>So</span> <span m='2335090'>why</span> <span m='2335270'>did</span>
  <span m='2335450'>Gauss</span> <span m='2335780'>think</span> <span m='2335960'>this</span>
  <span m='2336110'>was</span> <span m='2336260'>useless?</span> <span m='2337890'>And</span>
  <span m='2337990'>that's</span> <span m='2338150'>1805.</span> <span m='2340070'>And</span>
  <span m='2340190'>now,</span> <span m='2340310'>we</span> <span m='2340430'>come</span>
  <span m='2340590'>around to</span> <span m='2340880'>1965,</span> <span m='2341900'>and</span>
  <span m='2341990'>Cooley</span> <span m='2342260'>and</span> <span m='2342350'>Tukey</span>
  <span m='2342650'>make</span> <span m='2342800'>this</span> <span m='2342980'>huge</span>
  <span m='2343520'>deal.</span> <span m='2343940'>And</span> <span m='2344390'>they're</span>
  <span m='2344540'>world-famous</span> <span m='2345350'>because</span> <span m='2345710'>of</span>
  <span m='2345890'>their</span> <span m='2346070'>rediscovery</span> <span m='2346720'>of</span>
  <span m='2346790'>something</span> <span m='2347090'>that</span> <span m='2347180'>Gauss</span>
  <span m='2347480'>knew</span> <span m='2347600'>in</span> <span m='2348120'>1905.</span>
  </p><p><span m='2349103'>AUDIENCE:</span> <span m='2349586'>I mean,</span> <span
  m='2350552'>you're</span> <span m='2351035'>not going</span> <span m='2351518'>to
  be doing</span> <span m='2352001'>anything</span> <span m='2352484'>that's</span>
  <span m='2352967'>like</span> <span m='2353450'>128</span> <span m='2353933'>by</span>
  <span m='2354416'>128</span> <span m='2354899'>by hand</span> <span m='2355382'>anyway.</span>
  </p><p><span m='2356348'>DENNIS FREEMAN:</span> <span m='2356840'>That's</span>
  <span m='2357080'>exactly</span> <span m='2357470'>right.</span> <span m='2358650'>So</span>
  <span m='2359390'>when</span> <span m='2359750'>Gauss</span> <span m='2360110'>was</span>
  <span m='2360290'>thinking</span> <span m='2360620'>about</span> <span m='2360860'>it,</span>
  <span m='2360920'>he</span> <span m='2361070'>was</span> <span m='2361220'>thinking</span>
  <span m='2361550'>about</span> <span m='2361880'>16</span> <span m='2362300'>by</span>
  <span m='2362450'>16.</span> <span m='2364550'>And</span> <span m='2364700'>so,</span>
  <span m='2365210'>yeah,</span> <span m='2365480'>you</span> <span m='2365630'>save</span>
  <span m='2365870'>two,</span> <span m='2366670'>big</span> <span m='2366890'>deal.</span>
  </p><p><span m='2368360'>He</span> <span m='2368510'>was</span> <span m='2368660'>much</span>
  <span m='2368930'>more</span> <span m='2369170'>actually</span> <span m='2369680'>impressed</span>
  <span m='2370280'>with</span> <span m='2370430'>logarithms,</span> <span m='2372620'>because</span>
  <span m='2372950'>he</span> <span m='2373070'>was</span> <span m='2373220'>doing</span>
  <span m='2373460'>the</span> <span m='2373550'>multiplies</span> <span m='2374060'>by</span>
  <span m='2374180'>hand.</span> <span m='2376490'>And</span> <span m='2376940'>the</span>
  <span m='2377180'>log</span> <span m='2377450'>made</span> <span m='2377660'>it</span>
  <span m='2377720'>much</span> <span m='2377900'>easier</span> <span m='2378200'>to</span>
  <span m='2378290'>do</span> <span m='2378410'>multiplies,</span> <span m='2379020'>because</span>
  <span m='2379190'>you</span> <span m='2379250'>could</span> <span m='2379370'>substitute</span>
  <span m='2379820'>addition.</span> <span m='2381260'>So</span> <span m='2381440'>he</span>
  <span m='2381590'>actually</span> <span m='2381920'>commented</span> <span m='2382460'>on</span>
  <span m='2382610'>how</span> <span m='2382760'>useful</span> <span m='2383360'>logarithms</span>
  <span m='2383930'>are.</span> <span m='2385280'>And</span> <span m='2385460'>he</span>
  <span m='2385610'>didn't</span> <span m='2385940'>comment</span> <span m='2386360'>on</span>
  <span m='2386510'>how</span> <span m='2386660'>useful</span> <span m='2387080'>this</span>
  <span m='2387350'>is.</span> </p><p><span m='2387590'>But</span> <span m='2387710'>now,</span>
  <span m='2387980'>we</span> <span m='2388100'>make</span> <span m='2388310'>a</span>
  <span m='2388370'>big</span> <span m='2388520'>deal</span> <span m='2388810'>in</span>
  <span m='2388950'>the</span> <span m='2389240'>other</span> <span m='2389540'>order.</span>
  <span m='2390800'>And</span> <span m='2390950'>it's</span> <span m='2391130'>entirely</span>
  <span m='2391850'>digital</span> <span m='2392210'>computation.</span> <span m='2393110'>So</span>
  <span m='2393710'>when</span> <span m='2393980'>we</span> <span m='2394280'>solve</span>
  <span m='2394700'>systems</span> <span m='2395240'>of</span> <span m='2395360'>10</span>
  <span m='2395570'>to</span> <span m='2395660'>the</span> <span m='2395780'>sixth</span>
  <span m='2396160'>or</span> <span m='2396450'>10 to the</span> <span m='2396580'>10th</span>
  <span m='2396860'>unknowns,</span> <span m='2397910'>this</span> <span m='2398150'>is</span>
  <span m='2398300'>an</span> <span m='2398450'>enormous</span> <span m='2399050'>deal.</span>
  <span m='2399860'>And</span> <span m='2399920'>logarithms</span> <span m='2400490'>are</span>
  <span m='2400550'>good</span> <span m='2400730'>too.</span> </p><p><span m='2401390'>[LAUGHTER]</span>
  </p><p><span m='2401800'>But</span> <span m='2402770'>this</span> <span m='2402980'>is</span>
  <span m='2403160'>an</span> <span m='2403280'>enormous</span> <span m='2403730'>deal.</span>
  <span m='2406640'>So</span> <span m='2407330'>one</span> <span m='2407570'>more</span>
  <span m='2408200'>piece</span> <span m='2408470'>of</span> <span m='2408560'>theory</span>
  <span m='2408990'>and</span> <span m='2409110'>then</span> <span m='2409220'>one</span>
  <span m='2409400'>more</span> <span m='2409640'>ending</span> <span m='2409960'>thing.</span>
  <span m='2410750'>The</span> <span m='2410870'>piece</span> <span m='2411050'>of</span>
  <span m='2411140'>theory</span> <span m='2411590'>is</span> <span m='2411950'>going</span>
  <span m='2412340'>from</span> <span m='2412940'>periodic</span> <span m='2413480'>signals</span>
  <span m='2413960'>to</span> <span m='2414110'>aperiodic.</span> <span m='2415670'>And</span>
  <span m='2415850'>not</span> <span m='2416090'>surprisingly,</span> <span m='2416820'>that</span>
  <span m='2416900'>works</span> <span m='2417170'>just</span> <span m='2417470'>the</span>
  <span m='2417560'>way</span> <span m='2417680'>it</span> <span m='2417770'>did</span>
  <span m='2417950'>in</span> <span m='2418090'>CT.</span> <span m='2418530'>In</span>
  <span m='2418670'>fact,</span> <span m='2418850'>there's</span> <span m='2419030'>nothing</span>
  <span m='2419360'>new</span> <span m='2419570'>here.</span> </p><p><span m='2420920'>We</span>
  <span m='2421070'>can</span> <span m='2421280'>think</span> <span m='2421490'>about</span>
  <span m='2424970'>how</span> <span m='2425180'>would</span> <span m='2425420'>you</span>
  <span m='2425570'>make</span> <span m='2425780'>a</span> <span m='2425870'>Fourier</span>
  <span m='2426260'>transform</span> <span m='2426830'>compared</span> <span m='2427160'>to</span>
  <span m='2427280'>a</span> <span m='2427310'>Fourier</span> <span m='2427670'>series.</span>
  <span m='2428150'>With</span> <span m='2428340'>the</span> <span m='2428440'>CT,</span>
  <span m='2430250'>we</span> <span m='2430370'>developed</span> <span m='2430810'>the</span>
  <span m='2430910'>theory</span> <span m='2431240'>for</span> <span m='2431390'>series</span>
  <span m='2431810'>first,</span> <span m='2432080'>because</span> <span m='2432350'>it</span>
  <span m='2432410'>was</span> <span m='2432560'>easier.</span> <span m='2433460'>And
  then</span> <span m='2433670'>we</span> <span m='2433790'>derived</span> <span m='2434270'>the</span>
  <span m='2434360'>theory</span> <span m='2434750'>for</span> <span m='2435135'>aperiodic</span>
  <span m='2436250'>signals.</span> <span m='2436700'>By</span> <span m='2437060'>something</span>
  <span m='2437390'>called</span> <span m='2437990'>periodic</span> <span m='2438560'>extension,</span>
  <span m='2439160'>we</span> <span m='2439280'>took</span> <span m='2439480'>an</span>
  <span m='2439790'>aperiodic</span> <span m='2440360'>signal,</span> <span m='2440720'>like</span>
  <span m='2440930'>this</span> <span m='2441100'>CT</span> <span m='2441500'>signal,</span>
  <span m='2442370'>made</span> <span m='2442670'>it</span> <span m='2442790'>periodic,</span>
  <span m='2443420'>like</span> <span m='2443660'>that</span> <span m='2443960'>DT</span>
  <span m='2445100'>signal,</span> <span m='2446690'>and</span> <span m='2446900'>then</span>
  <span m='2447110'>took</span> <span m='2447320'>the</span> <span m='2447440'>limit</span>
  <span m='2448340'>as</span> <span m='2448580'>the</span> <span m='2448670'>period</span>
  <span m='2449000'>goes</span> <span m='2449240'>to</span> <span m='2449330'>infinity.</span>
  </p><p><span m='2450680'>Had</span> <span m='2450890'>we</span> <span m='2451040'>stayed</span>
  <span m='2451340'>in</span> <span m='2451490'>time</span> <span m='2451730'>domain</span>
  <span m='2452090'>the</span> <span m='2452150'>whole</span> <span m='2452300'>time,</span>
  <span m='2452930'>that</span> <span m='2453080'>would</span> <span m='2453200'>be</span>
  <span m='2453380'>a</span> <span m='2453500'>trivial</span> <span m='2453890'>no-op.</span>
  <span m='2455450'>But</span> <span m='2455600'>the</span> <span m='2455720'>trick</span>
  <span m='2456020'>was</span> <span m='2456710'>that</span> <span m='2456980'>after</span>
  <span m='2457490'>we</span> <span m='2457880'>did</span> <span m='2458090'>the</span>
  <span m='2458180'>periodic</span> <span m='2458690'>extension,</span> <span m='2459290'>we</span>
  <span m='2459470'>then</span> <span m='2459680'>took</span> <span m='2459890'>the</span>
  <span m='2460010'>series</span> <span m='2460580'>of</span> <span m='2460730'>this</span>
  <span m='2462830'>and</span> <span m='2462980'>then</span> <span m='2463190'>passed</span>
  <span m='2463580'>the</span> <span m='2463700'>limit</span> <span m='2464300'>onto</span>
  <span m='2464480'>the</span> <span m='2464600'>series.</span> <span m='2466550'>So</span>
  <span m='2466700'>that's</span> <span m='2466940'>the</span> <span m='2467060'>trick.</span>
  </p><p><span m='2467420'>So</span> <span m='2468050'>we</span> <span m='2468800'>think</span>
  <span m='2469010'>about</span> <span m='2469220'>generalizing</span> <span m='2469940'>the</span>
  <span m='2470220'>aperiodic</span> <span m='2470800'>into</span> <span m='2470990'>periodic.</span>
  <span m='2472130'>Then</span> <span m='2472340'>we</span> <span m='2472460'>take</span>
  <span m='2472670'>the</span> <span m='2472760'>series.</span> <span m='2473300'>Then</span>
  <span m='2473510'>we</span> <span m='2473630'>pass</span> <span m='2473940'>the</span>
  <span m='2474050'>limit.</span> <span m='2474680'>And</span> <span m='2474800'>we</span>
  <span m='2474950'>ask</span> <span m='2475160'>whether</span> <span m='2475430'>the</span>
  <span m='2475550'>series</span> <span m='2475910'>converges.</span> <span m='2476480'>And</span>
  <span m='2476630'>just</span> <span m='2476840'>like</span> <span m='2477200'>CT,</span>
  <span m='2478100'>the</span> <span m='2478220'>answer</span> <span m='2478490'>for</span>
  <span m='2478650'>DT</span> <span m='2479000'>will</span> <span m='2479150'>converge.</span>
  </p><p><span m='2480200'>So</span> <span m='2480770'>you</span> <span m='2480890'>start</span>
  <span m='2481160'>with</span> <span m='2481310'>a</span> <span m='2481370'>periodic</span>
  <span m='2482240'>signal.</span> <span m='2483110'>You</span> <span m='2483230'>write</span>
  <span m='2483500'>out</span> <span m='2483830'>the</span> <span m='2484220'>DT</span>
  <span m='2485270'>Fourier</span> <span m='2486020'>series</span> <span m='2486800'>just</span>
  <span m='2487100'>as</span> <span m='2487220'>we've</span> <span m='2487460'>been</span>
  <span m='2487730'>doing.</span> <span m='2489680'>And</span> <span m='2491090'>you</span>
  <span m='2491270'>get</span> <span m='2491390'>an</span> <span m='2491510'>answer</span>
  <span m='2491840'>that</span> <span m='2491960'>for</span> <span m='2492140'>this</span>
  <span m='2492260'>square</span> <span m='2492530'>pulse</span> <span m='2492860'>looks</span>
  <span m='2493010'>very</span> <span m='2493220'>much</span> <span m='2493430'>like</span>
  <span m='2493580'>the</span> <span m='2493640'>answer</span> <span m='2493910'>we</span>
  <span m='2494000'>got</span> <span m='2494180'>before.</span> </p><p><span m='2495440'>The</span>
  <span m='2495590'>tricky</span> <span m='2495980'>thing</span> <span m='2496280'>that</span>
  <span m='2496430'>I've</span> <span m='2496610'>done</span> <span m='2496910'>here</span>
  <span m='2497780'>is</span> <span m='2498050'>I've</span> <span m='2498350'>written</span>
  <span m='2499280'>this</span> <span m='2499450'>series</span> <span m='2500120'>on</span>
  <span m='2500330'>two</span> <span m='2500600'>axes,</span> <span m='2501110'>just</span>
  <span m='2501320'>like</span> <span m='2501540'>CT--</span> <span m='2502220'>a</span>
  <span m='2502680'>k-axis,</span> <span m='2503540'>which</span> <span m='2503720'>is</span>
  <span m='2503870'>the</span> <span m='2503990'>harmonic</span> <span m='2504470'>number,</span>
  <span m='2505280'>and</span> <span m='2505460'>an</span> <span m='2505550'>omega-axis,</span>
  <span m='2506520'>which</span> <span m='2506630'>is</span> <span m='2506870'>the</span>
  <span m='2507710'>frequency.</span> <span m='2508730'>The</span> <span m='2508850'>frequency</span>
  <span m='2509930'>represents</span> <span m='2510440'>the</span> <span m='2510560'>position</span>
  <span m='2511010'>around</span> <span m='2511250'>the</span> <span m='2511340'>unit</span>
  <span m='2511550'>circle.</span> <span m='2512580'>So</span> <span m='2512690'>capital</span>
  <span m='2514010'>omega</span> <span m='2515120'>is</span> <span m='2515360'>the</span>
  <span m='2515510'>angle</span> <span m='2516320'>of</span> <span m='2516470'>the</span>
  <span m='2516530'>unit</span> <span m='2516770'>circle.</span> </p><p><span m='2518550'>Then</span>
  <span m='2519320'>if</span> <span m='2519500'>I</span> <span m='2519590'>change</span>
  <span m='2519980'>the</span> <span m='2520100'>period,</span> <span m='2522170'>the</span>
  <span m='2522260'>effect</span> <span m='2522590'>of</span> <span m='2522710'>making</span>
  <span m='2522980'>the</span> <span m='2523070'>period</span> <span m='2523400'>bigger</span>
  <span m='2523760'>is</span> <span m='2523880'>to</span> <span m='2523970'>put</span>
  <span m='2525560'>the</span> <span m='2525980'>harmonics</span> <span m='2526490'>closer.</span>
  <span m='2528440'>But</span> <span m='2528680'>in</span> <span m='2528830'>a</span>
  <span m='2528890'>magical</span> <span m='2529400'>way,</span> <span m='2530510'>because</span>
  <span m='2530870'>the</span> <span m='2531050'>envelope--</span> <span m='2531590'>the</span>
  <span m='2531680'>thing</span> <span m='2531890'>showed</span> <span m='2532130'>by</span>
  <span m='2532280'>the</span> <span m='2532400'>thin</span> <span m='2532610'>black</span>
  <span m='2532910'>line--</span> <span m='2533600'>doesn't</span> <span m='2533990'>change</span>
  <span m='2534440'>as</span> <span m='2534560'>I</span> <span m='2534650'>take</span>
  <span m='2534910'>the</span> <span m='2535030'>limit,</span> <span m='2537410'>that's</span>
  <span m='2537710'>what</span> <span m='2537860'>enables</span> <span m='2538280'>me</span>
  <span m='2538430'>to</span> <span m='2538520'>think</span> <span m='2538730'>about</span>
  <span m='2539210'>there</span> <span m='2539390'>being</span> <span m='2539720'>a</span>
  <span m='2539780'>limit.</span> <span m='2543380'>As</span> <span m='2543530'>you</span>
  <span m='2543620'>make</span> <span m='2543770'>the</span> <span m='2543890'>period</span>
  <span m='2544280'>bigger</span> <span m='2544550'>and</span> <span m='2544670'>bigger,</span>
  <span m='2546080'>you</span> <span m='2546230'>get</span> <span m='2546380'>more</span>
  <span m='2546710'>and</span> <span m='2546800'>more</span> <span m='2547040'>lines</span>
  <span m='2548300'>in</span> <span m='2548570'>an</span> <span m='2548750'>envelope</span>
  <span m='2549440'>that</span> <span m='2549590'>doesn't</span> <span m='2549890'>change.</span>
  </p><p><span m='2551360'>And</span> <span m='2551510'>then</span> <span m='2551690'>you</span>
  <span m='2551810'>can</span> <span m='2551960'>think</span> <span m='2552200'>about</span>
  <span m='2553040'>the</span> <span m='2553250'>envelope</span> <span m='2554330'>as</span>
  <span m='2554540'>being</span> <span m='2554930'>a</span> <span m='2555020'>function</span>
  <span m='2555650'>of</span> <span m='2555950'>the</span> <span m='2556070'>continuous</span>
  <span m='2556700'>variable</span> <span m='2557180'>omega,</span> <span m='2557930'>rather</span>
  <span m='2558380'>than</span> <span m='2558560'>the</span> <span m='2558650'>discrete</span>
  <span m='2559040'>variable</span> <span m='2559520'>k.</span> <span m='2561650'>And</span>
  <span m='2561800'>then</span> <span m='2561980'>you</span> <span m='2562100'>can</span>
  <span m='2562250'>think</span> <span m='2562400'>about,</span> <span m='2562610'>what</span>
  <span m='2562760'>would</span> <span m='2562880'>happen</span> <span m='2563150'>if</span>
  <span m='2563270'>you</span> <span m='2563360'>pass</span> <span m='2563720'>the</span>
  <span m='2563840'>limit?</span> <span m='2565130'>And</span> <span m='2565250'>the</span>
  <span m='2565370'>idea</span> <span m='2565880'>is</span> <span m='2566270'>that,</span>
  <span m='2568220'>if</span> <span m='2568430'>you</span> <span m='2568610'>do</span>
  <span m='2568820'>the</span> <span m='2568940'>synthesis</span> <span m='2569450'>equation,</span>
  <span m='2570410'>there's</span> <span m='2570590'>an</span> <span m='2570740'>ak</span>
  <span m='2572420'>that</span> <span m='2572570'>depends</span> <span m='2572990'>on</span>
  <span m='2573170'>1/n,</span> <span m='2573980'>which</span> <span m='2574190'>you</span>
  <span m='2574280'>can</span> <span m='2574480'>write</span> <span m='2575090'>in</span>
  <span m='2575270'>terms</span> <span m='2575750'>of</span> <span m='2576140'>the</span>
  <span m='2576290'>fundamental</span> <span m='2576860'>frequency</span> <span m='2577440'>omega</span>
  <span m='2577830'>0.</span> <span m='2580280'>And</span> <span m='2580430'>then</span>
  <span m='2580640'>as</span> <span m='2580760'>you</span> <span m='2580880'>pass</span>
  <span m='2581240'>the</span> <span m='2581360'>limit,</span> <span m='2582100'>omega</span>
  <span m='2582560'>0</span> <span m='2582770'>is</span> <span m='2582950'>the</span>
  <span m='2583070'>spacing</span> <span m='2583580'>between</span> <span m='2583970'>these</span>
  <span m='2584510'>harmonics.</span> </p><p><span m='2586260'>So</span> <span m='2586340'>if</span>
  <span m='2586430'>you</span> <span m='2586520'>multiply</span> <span m='2587090'>by</span>
  <span m='2587210'>the</span> <span m='2587330'>spacing,</span> <span m='2587780'>you</span>
  <span m='2587900'>get</span> <span m='2588080'>the</span> <span m='2588290'>area</span>
  <span m='2589100'>of</span> <span m='2589220'>that</span> <span m='2589460'>block.</span>
  <span m='2590910'>So</span> <span m='2590960'>the</span> <span m='2591140'>area</span>
  <span m='2591590'>associated</span> <span m='2592190'>with</span> <span m='2592340'>N
  equals</span> <span m='2592700'>0</span> <span m='2593120'>is</span> <span m='2593270'>this</span>
  <span m='2593510'>area.</span> <span m='2594440'>The</span> <span m='2594560'>area</span>
  <span m='2594860'>associated</span> <span m='2595280'>with</span> <span m='2595430'>N
  equals</span> <span m='2595820'>1</span> <span m='2596090'>is</span> <span m='2596180'>that</span>
  <span m='2596390'>one,</span> <span m='2596630'>N</span> <span m='2596730'>equals</span>
  <span m='2597080'>2,</span> <span m='2597440'>N</span> <span m='2597530'>equals</span>
  <span m='2597770'>3,</span> <span m='2598040'>et</span> <span m='2598400'>cetera.</span>
  <span m='2599510'>And</span> <span m='2599690'>so</span> <span m='2599900'>by</span>
  <span m='2600140'>doing</span> <span m='2600590'>the</span> <span m='2601210'>sum,</span>
  <span m='2602650'>the</span> <span m='2602960'>sum</span> <span m='2603710'>increasingly</span>
  <span m='2604370'>converges</span> <span m='2604970'>to</span> <span m='2605270'>the</span>
  <span m='2605480'>integral.</span> </p><p><span m='2607190'>So</span> <span m='2607310'>you</span>
  <span m='2607460'>get</span> <span m='2607820'>precisely</span> <span m='2608390'>the</span>
  <span m='2608540'>same</span> <span m='2608810'>kinds</span> <span m='2609200'>of</span>
  <span m='2609260'>formulas</span> <span m='2609830'>we've</span> <span m='2610010'>been</span>
  <span m='2610160'>using</span> <span m='2610490'>before.</span> <span m='2611630'>The</span>
  <span m='2611750'>one</span> <span m='2612020'>thing</span> <span m='2612230'>that's</span>
  <span m='2612410'>a</span> <span m='2612440'>little</span> <span m='2612680'>bit</span>
  <span m='2612850'>weird,</span> <span m='2613700'>in</span> <span m='2613940'>the</span>
  <span m='2614090'>DT</span> <span m='2614840'>Fourier</span> <span m='2615320'>series,</span>
  <span m='2616790'>we</span> <span m='2616970'>had</span> <span m='2617210'>a</span>
  <span m='2617420'>sum</span> <span m='2618050'>in</span> <span m='2618200'>the</span>
  <span m='2618290'>synthesis</span> <span m='2618920'>equation</span> <span m='2619490'>as</span>
  <span m='2619610'>a</span> <span m='2619760'>sum</span> <span m='2620180'>in</span>
  <span m='2620330'>the</span> <span m='2620420'>analysis</span> <span m='2620960'>equation.</span>
  <span m='2621800'>Here,</span> <span m='2622140'>we</span> <span m='2622240'>get</span>
  <span m='2622250'>one</span> <span m='2622490'>of</span> <span m='2622610'>both.</span>
  </p><p><span m='2624710'>The</span> <span m='2625060'>DT</span> <span m='2625760'>Fourier</span>
  <span m='2627560'>transform--</span> <span m='2628400'>that's</span> <span m='2628640'>this</span>
  <span m='2628880'>thing--</span> <span m='2630050'>is</span> <span m='2630200'>a</span>
  <span m='2630260'>function</span> <span m='2630740'>of</span> <span m='2630890'>the</span>
  <span m='2631010'>continuous</span> <span m='2631760'>variable--</span> <span m='2632540'>uh--</span>
  <span m='2634430'>discrete-time</span> <span m='2635570'>Fourier</span> <span m='2636050'>transform</span>
  <span m='2636800'>has</span> <span m='2637010'>a</span> <span m='2637070'>continuous</span>
  <span m='2637820'>frequency</span> <span m='2638360'>variable</span> <span m='2638840'>capital</span>
  <span m='2639270'>omega.</span> <span m='2640940'>Because</span> <span m='2641690'>it</span>
  <span m='2641780'>has</span> <span m='2641990'>a</span> <span m='2642100'>continuous--</span>
  <span m='2642830'>even</span> <span m='2643040'>though</span> <span m='2643190'>it's</span>
  <span m='2643280'>a</span> <span m='2643400'>discrete-time</span> <span m='2644110'>Fourier</span>
  <span m='2644340'>transform--</span> <span m='2645370'>discrete-time</span> <span
  m='2645980'>Fourier</span> <span m='2646400'>transform</span> <span m='2646880'>has</span>
  <span m='2646970'>a</span> <span m='2647030'>continuous</span> <span m='2647750'>frequency</span>
  <span m='2648260'>variable</span> <span m='2648680'>cap</span> <span m='2648980'>omega.</span>
  <span m='2649800'>So</span> <span m='2650090'>when</span> <span m='2650300'>we</span>
  <span m='2650420'>do</span> <span m='2650570'>the</span> <span m='2651690'>synthesis,</span>
  <span m='2653050'>we</span> <span m='2653170'>have</span> <span m='2653320'>to</span>
  <span m='2653440'>integrate.</span> <span m='2655030'>So</span> <span m='2655210'>one</span>
  <span m='2655450'>direction</span> <span m='2655890'>is</span> <span m='2656000'>a</span>
  <span m='2656080'>sum,</span> <span m='2656410'>the</span> <span m='2656560'>other</span>
  <span m='2656740'>direction</span> <span m='2657110'>it's</span> <span m='2657220'>an</span>
  <span m='2657340'>integral.</span> <span m='2657740'>Other</span> <span m='2657970'>than</span>
  <span m='2658120'>that,</span> <span m='2658400'>it's</span> <span m='2658420'>just</span>
  <span m='2658630'>the</span> <span m='2658750'>same.</span> </p><p><span m='2660490'>So</span>
  <span m='2660640'>there's</span> <span m='2660850'>a</span> <span m='2661210'>striking</span>
  <span m='2661750'>parallel.</span> <span m='2662560'>All</span> <span m='2662740'>of</span>
  <span m='2662800'>these</span> <span m='2663010'>things</span> <span m='2663250'>are</span>
  <span m='2663340'>highly</span> <span m='2663640'>related.</span> <span m='2664870'>The</span>
  <span m='2664990'>CT</span> <span m='2665320'>Fourier</span> <span m='2665650'>transforms</span>
  <span m='2666280'>are</span> <span m='2666340'>highly</span> <span m='2666640'>related</span>
  <span m='2667120'>to</span> <span m='2667360'>the</span> <span m='2667580'>CT</span>
  <span m='2667980'>Fourier</span> <span m='2668550'>series,</span> <span m='2669370'>as</span>
  <span m='2669610'>is</span> <span m='2669760'>the</span> <span m='2669850'>CT</span>
  <span m='2670240'>transform</span> <span m='2670750'>to</span> <span m='2670870'>the</span>
  <span m='2670990'>CT</span> <span m='2671350'>series.</span> <span m='2671710'>And</span>
  <span m='2671800'>there's</span> <span m='2671950'>lots</span> <span m='2672190'>of</span>
  <span m='2672310'>connections.</span> <span m='2672760'>And</span> <span m='2672850'>we'll</span>
  <span m='2672940'>talk</span> <span m='2673120'>about</span> <span m='2673390'>that</span>
  <span m='2673570'>more</span> <span m='2673840'>next</span> <span m='2674170'>week--</span>
  <span m='2674920'>how</span> <span m='2675040'>you</span> <span m='2675160'>can</span>
  <span m='2675310'>infer</span> <span m='2676240'>how</span> <span m='2676450'>one</span>
  <span m='2676720'>of</span> <span m='2676780'>these</span> <span m='2677290'>transform</span>
  <span m='2677750'>relationships</span> <span m='2678340'>would</span> <span m='2678520'>have</span>
  <span m='2678640'>worked</span> <span m='2679150'>from</span> <span m='2679360'>all</span>
  <span m='2679540'>of</span> <span m='2679630'>the</span> <span m='2679780'>others.</span>
  </p><p><span m='2682450'>For</span> <span m='2682630'>the</span> <span m='2682720'>time</span>
  <span m='2682990'>being,</span> <span m='2683260'>the</span> <span m='2683380'>important</span>
  <span m='2683770'>thing</span> <span m='2684100'>is</span> <span m='2684370'>just</span>
  <span m='2684610'>that,</span> <span m='2686650'>when</span> <span m='2686860'>you</span>
  <span m='2686920'>do</span> <span m='2687070'>the</span> <span m='2687190'>DT</span>
  <span m='2687560'>Fourier</span> <span m='2687940'>transform,</span> <span m='2689890'>you</span>
  <span m='2690010'>can</span> <span m='2690160'>think</span> <span m='2690370'>about</span>
  <span m='2690670'>that</span> <span m='2690880'>just</span> <span m='2691150'>like</span>
  <span m='2691300'>the</span> <span m='2691420'>CT</span> <span m='2691870'>Fourier</span>
  <span m='2692200'>transform.</span> <span m='2693400'>The</span> <span m='2693520'>CT</span>
  <span m='2693820'>Fourier</span> <span m='2694420'>transform</span> <span m='2694725'>was</span>
  <span m='2695770'>evaluate</span> <span m='2696370'>the</span> <span m='2696490'>Laplace</span>
  <span m='2696910'>transform</span> <span m='2697330'>on</span> <span m='2697450'>the</span>
  <span m='2697510'>j omega-axis.</span> <span m='2698810'>Now,</span> <span m='2699310'>you</span>
  <span m='2699670'>evaluate</span> <span m='2700270'>the</span> <span m='2700360'>z-transform</span>
  <span m='2701620'>on</span> <span m='2701770'>the</span> <span m='2701860'>unit</span>
  <span m='2702070'>circle.</span> <span m='2702400'>The</span> <span m='2702850'>unit</span>
  <span m='2703090'>circle is</span> <span m='2703420'>no</span> <span m='2703570'>surprise.</span>
  <span m='2703990'>That's</span> <span m='2704110'>what</span> <span m='2704230'>we've</span>
  <span m='2704350'>been</span> <span m='2704500'>doing.</span> </p><p><span m='2706690'>Because</span>
  <span m='2707620'>of</span> <span m='2707860'>the</span> <span m='2708850'>relationship</span>
  <span m='2709540'>between</span> <span m='2709990'>the</span> <span m='2710500'>DT</span>
  <span m='2710830'>Fourier</span> <span m='2711250'>transform</span> <span m='2712660'>and</span>
  <span m='2713050'>the</span> <span m='2713380'>z-transform,</span> <span m='2716950'>the</span>
  <span m='2717130'>DT</span> <span m='2717730'>Fourier</span> <span m='2718060'>transform</span>
  <span m='2718900'>inherits</span> <span m='2719560'>all</span> <span m='2719800'>the</span>
  <span m='2719920'>nice</span> <span m='2720160'>properties</span> <span m='2720820'>of</span>
  <span m='2721090'>the</span> <span m='2721435'>z-transform.</span> <span m='2723460'>We'll</span>
  <span m='2723610'>make</span> <span m='2723790'>a</span> <span m='2723850'>bigger</span>
  <span m='2724060'>deal</span> <span m='2724250'>of</span> <span m='2724600'>that</span>
  <span m='2725470'>in</span> <span m='2725620'>the</span> <span m='2725770'>upcoming</span>
  <span m='2726220'>two</span> <span m='2726430'>weeks.</span> <span m='2727030'>In</span>
  <span m='2727150'>fact,</span> <span m='2727360'>that's</span> <span m='2727840'>the</span>
  <span m='2727990'>next</span> <span m='2728260'>two</span> <span m='2728440'>weeks</span>
  <span m='2729270'>of</span> <span m='2729520'>this</span> <span m='2729700'>course,</span>
  <span m='2730120'>is</span> <span m='2730270'>to</span> <span m='2730390'>figure</span>
  <span m='2730660'>out</span> <span m='2730810'>the</span> <span m='2730930'>implications</span>
  <span m='2731530'>of</span> <span m='2731650'>all</span> <span m='2731860'>of</span>
  <span m='2731920'>those</span> <span m='2732880'>properties.</span> </p><p><span
  m='2735170'>But</span> <span m='2735190'>for</span> <span m='2735340'>today,</span>
  <span m='2735640'>what</span> <span m='2735820'>I</span> <span m='2735910'>want</span>
  <span m='2736110'>to</span> <span m='2736350'>just</span> <span m='2736570'>close</span>
  <span m='2736900'>with</span> <span m='2737140'>is</span> <span m='2737650'>one</span>
  <span m='2737800'>more</span> <span m='2738010'>example</span> <span m='2739210'>of</span>
  <span m='2739720'>how</span> <span m='2739990'>you</span> <span m='2740200'>can</span>
  <span m='2740380'>think</span> <span m='2740590'>about</span> <span m='2740890'>these</span>
  <span m='2741160'>frequency</span> <span m='2741880'>representations</span> <span
  m='2742660'>helping</span> <span m='2742990'>you</span> <span m='2743230'>to</span>
  <span m='2743890'>imagine</span> <span m='2744370'>the</span> <span m='2744460'>kinds</span>
  <span m='2744730'>of</span> <span m='2744790'>signal</span> <span m='2745060'>processing</span>
  <span m='2745540'>that</span> <span m='2745660'>you</span> <span m='2746110'>do</span>
  <span m='2746590'>or</span> <span m='2746770'>would</span> <span m='2746920'>like</span>
  <span m='2747160'>to</span> <span m='2747310'>do.</span> <span m='2748270'>And</span>
  <span m='2748420'>so</span> <span m='2749760'>the</span> <span m='2750130'>last</span>
  <span m='2750460'>example</span> <span m='2750760'>now</span> <span m='2750970'>is</span>
  <span m='2751150'>one</span> <span m='2751450'>from</span> <span m='2751660'>image</span>
  <span m='2751960'>processing,</span> <span m='2752470'>instead</span> <span m='2752740'>of</span>
  <span m='2752830'>audio</span> <span m='2753190'>processing.</span> <span m='2753660'>I</span>
  <span m='2753730'>started</span> <span m='2754000'>with</span> <span m='2754150'>audio</span>
  <span m='2754450'>processing.</span> <span m='2756010'>Now,</span> <span m='2756160'>I</span>
  <span m='2756220'>want</span> <span m='2756370'>to</span> <span m='2756430'>think</span>
  <span m='2756550'>about</span> <span m='2756730'>image</span> <span m='2756970'>processing.</span>
  </p><p><span m='2757450'>Image</span> <span m='2757720'>has</span> <span m='2757930'>the</span>
  <span m='2758020'>property</span> <span m='2758890'>that</span> <span m='2759040'>I'm</span>
  <span m='2759160'>going</span> <span m='2759280'>to</span> <span m='2759340'>have</span>
  <span m='2759460'>to</span> <span m='2759550'>do</span> <span m='2759670'>something</span>
  <span m='2759970'>with</span> <span m='2760090'>2D.</span> <span m='2762040'>And</span>
  <span m='2762340'>in</span> <span m='2762460'>this</span> <span m='2762610'>class,</span>
  <span m='2762940'>we</span> <span m='2763090'>primarily</span> <span m='2763630'>think</span>
  <span m='2763810'>about</span> <span m='2764020'>1D.</span> <span m='2764560'>But</span>
  <span m='2764710'>you</span> <span m='2764830'>saw</span> <span m='2765070'>in</span>
  <span m='2765160'>the</span> <span m='2765250'>zebra</span> <span m='2765550'>problem</span>
  <span m='2766180'>that</span> <span m='2766600'>sometimes</span> <span m='2767230'>extending</span>
  <span m='2767740'>to</span> <span m='2767830'>2D</span> <span m='2768160'>is</span>
  <span m='2768310'>not</span> <span m='2768490'>hard.</span> <span m='2769600'>And</span>
  <span m='2769810'>it</span> <span m='2769900'>certainly</span> <span m='2770320'>is</span>
  <span m='2770440'>the</span> <span m='2770560'>case</span> <span m='2771910'>that</span>
  <span m='2772240'>the</span> <span m='2772630'>Fourier</span> <span m='2772960'>method</span>
  <span m='2773830'>extending</span> <span m='2774340'>to</span> <span m='2774460'>2D</span>
  <span m='2774940'>is</span> <span m='2775180'>really</span> <span m='2775690'>easy,</span>
  <span m='2777010'>or</span> <span m='2777130'>at</span> <span m='2777190'>least</span>
  <span m='2777700'>I'm</span> <span m='2777820'>going</span> <span m='2777970'>to</span>
  <span m='2778030'>say</span> <span m='2778150'>that.</span> </p><p><span m='2779680'>So</span>
  <span m='2780510'>the</span> <span m='2780700'>way</span> <span m='2780930'>you</span>
  <span m='2781430'>can</span> <span m='2781570'>think</span> <span m='2781750'>about</span>
  <span m='2781960'>a</span> <span m='2782020'>Fourier</span> <span m='2783670'>series</span>
  <span m='2784990'>in</span> <span m='2785170'>two</span> <span m='2785350'>dimensions</span>
  <span m='2785950'>is</span> <span m='2786070'>illustrated</span> <span m='2786520'>by</span>
  <span m='2786640'>this</span> <span m='2786820'>picture.</span> <span m='2787660'>I</span>
  <span m='2787750'>took</span> <span m='2787930'>a</span> <span m='2787990'>picture</span>
  <span m='2788320'>that</span> <span m='2788410'>512</span> <span m='2789040'>by</span>
  <span m='2789530'>512.</span> <span m='2790240'>That's</span> <span m='2790450'>the</span>
  <span m='2790540'>boat.</span> <span m='2792130'>And</span> <span m='2792280'>I</span>
  <span m='2792370'>made</span> <span m='2792610'>a</span> <span m='2792670'>new</span>
  <span m='2792880'>picture</span> <span m='2795070'>by</span> <span m='2795220'>taking</span>
  <span m='2795670'>this</span> <span m='2795970'>row,</span> <span m='2797100'>calculating</span>
  <span m='2797700'>the</span> <span m='2797800'>Fourier</span> <span m='2798220'>series</span>
  <span m='2798790'>for</span> <span m='2798910'>that</span> <span m='2799120'>row--</span>
  <span m='2799780'>that</span> <span m='2799960'>had</span> <span m='2800110'>512;</span>
  <span m='2801350'>so</span> <span m='2801390'>it's</span> <span m='2801550'>512</span>
  <span m='2802020'>by</span> <span m='2802150'>512.</span> <span m='2803420'>So</span>
  <span m='2803520'>I</span> <span m='2803620'>took</span> <span m='2803710'>these</span>
  <span m='2803980'>512</span> <span m='2804730'>numbers,</span> <span m='2805600'>took</span>
  <span m='2805900'>the</span> <span m='2806040'>Fourier</span> <span m='2806350'>series,</span>
  <span m='2806860'>and</span> <span m='2807040'>wrote</span> <span m='2807250'>them</span>
  <span m='2807400'>here.</span> </p><p><span m='2810450'>Then</span> <span m='2810630'>I</span>
  <span m='2810720'>took</span> <span m='2810990'>these</span> <span m='2811410'>512</span>
  <span m='2812190'>numbers</span> <span m='2812610'>and</span> <span m='2812790'>put</span>
  <span m='2812940'>the</span> <span m='2813000'>Fourier</span> <span m='2813330'>series</span>
  <span m='2813690'>here</span> <span m='2815700'>and</span> <span m='2816350'>repeat--</span>
  <span m='2817980'>so</span> <span m='2818160'>fill</span> <span m='2818340'>the</span>
  <span m='2818430'>whole</span> <span m='2818580'>thing</span> <span m='2818820'>up.</span>
  <span m='2821850'>So</span> <span m='2821970'>I</span> <span m='2822090'>took</span>
  <span m='2822520'>512,</span> <span m='2823770'>512-length</span> <span m='2824570'>sequences.</span>
  <span m='2826200'>Then</span> <span m='2827430'>I</span> <span m='2827550'>took</span>
  <span m='2830400'>that</span> <span m='2831030'>string</span> <span m='2831360'>of</span>
  <span m='2831420'>numbers,</span> <span m='2833862'>took the</span> <span m='2834330'>Fourier</span>
  <span m='2835120'>series,</span> <span m='2836500'>and</span> <span m='2836650'>put</span>
  <span m='2836890'>it</span> <span m='2837310'>there.</span> <span m='2840310'>And</span>
  <span m='2840490'>then</span> <span m='2840910'>that</span> <span m='2841210'>one,</span>
  <span m='2841600'>take</span> <span m='2841780'>the</span> <span m='2841870'>Fourier</span>
  <span m='2842080'>series,</span> <span m='2842590'>put</span> <span m='2842800'>it</span>
  <span m='2842980'>there.</span> <span m='2844060'>Take</span> <span m='2844330'>that</span>
  <span m='2844660'>one,</span> <span m='2845020'>take</span> <span m='2845200'>the</span>
  <span m='2845290'>Fourier</span> <span m='2845500'>series,</span> <span m='2845980'>put</span>
  <span m='2846160'>it</span> <span m='2846250'>there,</span> <span m='2846880'>and</span>
  <span m='2847060'>build</span> <span m='2847270'>up</span> <span m='2847390'>an</span>
  <span m='2847480'>image</span> <span m='2847750'>that</span> <span m='2847900'>way.</span>
  </p><p><span m='2850000'>So</span> <span m='2850180'>I,</span> <span m='2850600'>row</span>
  <span m='2850810'>by</span> <span m='2850990'>row,</span> <span m='2851230'>took</span>
  <span m='2851440'>all</span> <span m='2851560'>the</span> <span m='2851680'>Fourier</span>
  <span m='2851830'>series,</span> <span m='2852520'>pasted</span> <span m='2852910'>them</span>
  <span m='2853030'>together.</span> <span m='2853870'>Column</span> <span m='2854170'>by</span>
  <span m='2854320'>column,</span> <span m='2854710'>took</span> <span m='2854890'>all</span>
  <span m='2855010'>the</span> <span m='2855100'>Fourier</span> <span m='2855300'>series,</span>
  <span m='2855760'>pasted</span> <span m='2856090'>them</span> <span m='2856180'>together.</span>
  <span m='2856840'>When</span> <span m='2856990'>you're</span> <span m='2857080'>done</span>
  <span m='2857290'>with</span> <span m='2857450'>that,</span> <span m='2857590'>you</span>
  <span m='2857710'>get</span> <span m='2857890'>what</span> <span m='2858010'>we</span>
  <span m='2858160'>call</span> <span m='2858520'>a</span> <span m='2858730'>two</span>
  <span m='2858940'>dimensional</span> <span m='2859390'>Fourier</span> <span m='2859660'>series.</span>
  </p><p><span m='2861580'>And</span> <span m='2861730'>what</span> <span m='2861910'>you</span>
  <span m='2862090'>see</span> <span m='2862300'>on</span> <span m='2862420'>the</span>
  <span m='2862510'>right</span> <span m='2862750'>then--</span> <span m='2863470'>so</span>
  <span m='2863650'>here's</span> <span m='2863920'>my</span> <span m='2864040'>original</span>
  <span m='2864400'>picture</span> <span m='2864700'>512</span> <span m='2865090'>by</span>
  <span m='2865210'>512.</span> <span m='2865720'>Here's</span> <span m='2865930'>the</span>
  <span m='2866020'>picture</span> <span m='2866260'>of</span> <span m='2866320'>the</span>
  <span m='2866380'>magnitude</span> <span m='2866800'>of</span> <span m='2866860'>the</span>
  <span m='2866950'>angle.</span> <span m='2872670'>You</span> <span m='2872790'>can</span>
  <span m='2872940'>clearly</span> <span m='2873360'>see</span> <span m='2874530'>the</span>
  <span m='2874620'>boat.</span> </p><p><span m='2875950'>[LAUGHTER]</span> </p><p><span
  m='2879950'>And</span> <span m='2880230'>it's</span> <span m='2880700'>much</span>
  <span m='2880910'>clearer</span> <span m='2881240'>here.</span> <span m='2883490'>So</span>
  <span m='2883760'>the</span> <span m='2884090'>phase</span> <span m='2884840'>looks</span>
  <span m='2885170'>kind</span> <span m='2885680'>of</span> <span m='2885740'>random.</span>
  <span m='2886610'>So to</span> <span m='2886790'>gain</span> <span m='2887200'>some</span>
  <span m='2887320'>insight</span> <span m='2887660'>into</span> <span m='2887870'>what's</span>
  <span m='2888110'>in</span> <span m='2888230'>the</span> <span m='2888290'>magnitude</span>
  <span m='2888800'>and</span> <span m='2888890'>what's</span> <span m='2889070'>in</span>
  <span m='2889160'>the</span> <span m='2889250'>phase,</span> <span m='2890600'>what</span>
  <span m='2890810'>I</span> <span m='2890900'>can</span> <span m='2891110'>do</span>
  <span m='2891740'>is</span> <span m='2891920'>generate</span> <span m='2892370'>a</span>
  <span m='2892430'>new</span> <span m='2892640'>picture</span> <span m='2893570'>by</span>
  <span m='2893780'>setting</span> <span m='2894260'>the</span> <span m='2894410'>angle</span>
  <span m='2894830'>everywhere</span> <span m='2895220'>to</span> <span m='2895310'>0.</span>
  </p><p><span m='2898760'>So</span> <span m='2899450'>I</span> <span m='2899660'>took</span>
  <span m='2899930'>the</span> <span m='2900110'>picture,</span> <span m='2900500'>the</span>
  <span m='2900890'>magnitude,</span> <span m='2901430'>and</span> <span m='2901520'>I</span>
  <span m='2901640'>did</span> <span m='2901850'>this</span> <span m='2902130'>to
  it.</span> <span m='2902450'>I</span> <span m='2902540'>got</span> <span m='2902720'>the</span>
  <span m='2902780'>magnitude</span> <span m='2903230'>and</span> <span m='2903350'>angle.</span>
  <span m='2903980'>I</span> <span m='2904100'>set</span> <span m='2904370'>the</span>
  <span m='2904490'>angles</span> <span m='2904970'>to</span> <span m='2905090'>0.</span>
  <span m='2906470'>And</span> <span m='2906770'>that's</span> <span m='2907100'>the</span>
  <span m='2907220'>picture</span> <span m='2907460'>I</span> <span m='2907550'>got.</span>
  </p><p><span m='2910600'>So</span> <span m='2911510'>I was</span> <span m='2911860'>able</span>
  <span m='2912070'>to</span> <span m='2912190'>munge</span> <span m='2912670'>the</span>
  <span m='2912850'>angle</span> <span m='2913390'>in</span> <span m='2913570'>the</span>
  <span m='2913690'>auditory</span> <span m='2914290'>thing,</span> <span m='2914800'>and</span>
  <span m='2914920'>you</span> <span m='2915010'>could</span> <span m='2915160'>barely</span>
  <span m='2915520'>tell.</span> <span m='2916150'>Can</span> <span m='2916330'>you</span>
  <span m='2916450'>tell</span> <span m='2916780'>that</span> <span m='2916990'>I've</span>
  <span m='2917260'>munged</span> <span m='2917530'>the</span> <span m='2917650'>angle?</span>
  <span m='2919770'>There's</span> <span m='2920330'>some</span> <span m='2920510'>distortion</span>
  <span m='2921020'>caused</span> <span m='2921260'>by</span> <span m='2921380'>the</span>
  <span m='2921500'>angles.</span> <span m='2922130'>There</span> <span m='2922310'>are</span>
  <span m='2922520'>some</span> <span m='2922910'>things</span> <span m='2923240'>that</span>
  <span m='2923330'>you</span> <span m='2923450'>can</span> <span m='2923600'>still</span>
  <span m='2923840'>see.</span> </p><p><span m='2926330'>So</span> <span m='2926540'>if</span>
  <span m='2926720'>you</span> <span m='2926780'>go</span> <span m='2926930'>back</span>
  <span m='2927220'>to</span> <span m='2928220'>this</span> <span m='2928460'>one,</span>
  <span m='2929780'>there's</span> <span m='2929990'>these</span> <span m='2930230'>things</span>
  <span m='2930530'>here,</span> <span m='2930980'>and</span> <span m='2931100'>there's</span>
  <span m='2931310'>these</span> <span m='2931430'>things</span> <span m='2931730'>here,</span>
  <span m='2932150'>and</span> <span m='2932240'>there's--</span> <span m='2932780'>And</span>
  <span m='2932930'>if</span> <span m='2933050'>you</span> <span m='2933110'>go</span>
  <span m='2933260'>to</span> <span m='2933350'>this</span> <span m='2933560'>one,</span>
  <span m='2934370'>there's</span> <span m='2934520'>some</span> <span m='2934670'>lines</span>
  <span m='2935030'>here,</span> <span m='2935410'>and</span> <span m='2935530'>some
  lines--</span> <span m='2937460'>Maybe</span> <span m='2937790'>there's</span> <span
  m='2937970'>something</span> <span m='2938270'>there.</span> <span m='2940430'>But</span>
  <span m='2940640'>to</span> <span m='2940800'>a</span> <span m='2940850'>first</span>
  <span m='2941150'>order,</span> <span m='2941450'>it</span> <span m='2941570'>kind</span>
  <span m='2941840'>of</span> <span m='2942200'>messed</span> <span m='2942500'>things</span>
  <span m='2942770'>up.</span> </p><p><span m='2943880'>So</span> <span m='2944030'>then</span>
  <span m='2944240'>I</span> <span m='2944300'>did</span> <span m='2944420'>the</span>
  <span m='2944750'>opposite--</span> <span m='2946310'>just</span> <span m='2947360'>throw</span>
  <span m='2947570'>away</span> <span m='2947750'>the</span> <span m='2947840'>magnitude</span>
  <span m='2948290'>and</span> <span m='2948380'>substitute</span> <span m='2948830'>1,</span>
  <span m='2949230'>put</span> <span m='2949400'>1</span> <span m='2949790'>everywhere</span>
  <span m='2950150'>there</span> <span m='2950270'>was</span> <span m='2950390'>a</span>
  <span m='2950450'>magnitude,</span> <span m='2952780'>but</span> <span m='2952940'>put</span>
  <span m='2953120'>the</span> <span m='2953270'>angle</span> <span m='2953540'>back.</span>
  <span m='2954090'>Now,</span> <span m='2954250'>you can</span> <span m='2954350'>almost</span>
  <span m='2954610'>see</span> <span m='2954770'>the</span> <span m='2954860'>ship.</span>
  <span m='2956750'>So</span> <span m='2957350'>throw</span> <span m='2957500'>away</span>
  <span m='2957680'>the</span> <span m='2957800'>magnitude</span> <span m='2958310'>is</span>
  <span m='2958430'>better</span> <span m='2958730'>than</span> <span m='2958940'>throw</span>
  <span m='2959090'>away</span> <span m='2959270'>the</span> <span m='2959360'>phase.</span>
  <span m='2959780'>That's</span> <span m='2959900'>kind</span> <span m='2960080'>of</span>
  <span m='2960170'>cute.</span> <span m='2962480'>Can</span> <span m='2962690'>somebody</span>
  <span m='2963050'>think</span> <span m='2963260'>of</span> <span m='2963380'>why</span>
  <span m='2963650'>throw</span> <span m='2963830'>away</span> <span m='2964010'>the</span>
  <span m='2964100'>magnitude</span> <span m='2965270'>might</span> <span m='2965480'>be</span>
  <span m='2965600'>better</span> <span m='2965840'>than</span> <span m='2965990'>throw</span>
  <span m='2966140'>away</span> <span m='2966290'>the</span> <span m='2966440'>angle</span>
  <span m='2966890'>when</span> <span m='2967040'>you're</span> <span m='2967130'>trying</span>
  <span m='2967560'>to look at a</span> <span m='2967700'>picture?</span> <span m='2971980'>Yeah.</span>
  </p><p><span m='2972960'>AUDIENCE:</span> <span m='2973450'>Angle</span> <span m='2973940'>determines</span>
  <span m='2974430'>resolution.</span> <span m='2975410'>Magnitude</span> <span m='2976390'>determines</span>
  <span m='2976880'>[INAUDIBLE].</span> </p><p><span m='2977890'>DENNIS FREEMAN:</span>
  <span m='2978300'>That's</span> <span m='2978510'>exactly</span> <span m='2978900'>right.</span>
  <span m='2979780'>So</span> <span m='2980130'>if</span> <span m='2980310'>you</span>
  <span m='2980550'>muck</span> <span m='2980820'>around</span> <span m='2981090'>with</span>
  <span m='2981240'>the</span> <span m='2981330'>phase,</span> <span m='2982770'>you're</span>
  <span m='2982950'>changing</span> <span m='2983460'>the</span> <span m='2983550'>position.</span>
  <span m='2985650'>Even</span> <span m='2985890'>in</span> <span m='2986010'>audio,</span>
  <span m='2986550'>when</span> <span m='2986730'>you</span> <span m='2986820'>muck</span>
  <span m='2987000'>around</span> <span m='2987270'>with</span> <span m='2987450'>the</span>
  <span m='2987540'>phase,</span> <span m='2987930'>you're</span> <span m='2988050'>changing</span>
  <span m='2988470'>when</span> <span m='2988650'>the</span> <span m='2988770'>component</span>
  <span m='2989190'>comes</span> <span m='2989430'>out--</span> <span m='2989700'>earlier</span>
  <span m='2990150'>or</span> <span m='2990270'>later.</span> <span m='2991110'>In</span>
  <span m='2991260'>the</span> <span m='2991350'>picture,</span> <span m='2991680'>you're</span>
  <span m='2991800'>changing</span> <span m='2992550'>when</span> <span m='2992730'>the</span>
  <span m='2992820'>brightness</span> <span m='2993240'>comes</span> <span m='2993480'>out--</span>
  <span m='2993690'>earlier</span> <span m='2994110'>or</span> <span m='2994290'>later.</span>
  </p><p><span m='2995200'>If</span> <span m='2995220'>you</span> <span m='2995340'>want</span>
  <span m='2995520'>to</span> <span m='2995580'>have</span> <span m='2995790'>a</span>
  <span m='2995850'>nice</span> <span m='2996060'>straight</span> <span m='2996390'>line,</span>
  <span m='2997200'>you</span> <span m='2997320'>better</span> <span m='2997530'>keep</span>
  <span m='2997770'>all</span> <span m='2997890'>the</span> <span m='2998010'>phases</span>
  <span m='2998370'>lined</span> <span m='2998670'>up.</span> <span m='3000020'>If</span>
  <span m='3000170'>you</span> <span m='3000260'>scramble</span> <span m='3000740'>them,</span>
  <span m='3001460'>they</span> <span m='3001730'>end</span> <span m='3001940'>up</span>
  <span m='3002060'>scrambled,</span> <span m='3002580'>and</span> <span m='3002690'>you</span>
  <span m='3002780'>don't</span> <span m='3002930'>see</span> <span m='3003080'>them</span>
  <span m='3003200'>anymore.</span> <span m='3004890'>And</span> <span m='3005360'>as</span>
  <span m='3005540'>you</span> <span m='3005660'>said,</span> <span m='3006740'>the</span>
  <span m='3006830'>magnitude</span> <span m='3007310'>is</span> <span m='3007400'>controlling</span>
  <span m='3008570'>the</span> <span m='3009250'>intensity.</span> <span m='3010410'>So</span>
  <span m='3010450'>my</span> <span m='3010590'>intensities</span> <span m='3011120'>are</span>
  <span m='3011210'>all</span> <span m='3011300'>screwed</span> <span m='3011570'>up,</span>
  <span m='3013260'>but</span> <span m='3013310'>you</span> <span m='3013370'>can</span>
  <span m='3013550'>kind</span> <span m='3013790'>of</span> <span m='3013850'>still</span>
  <span m='3014060'>see</span> <span m='3014210'>the</span> <span m='3014330'>lines.</span>
  <span m='3014730'>You</span> <span m='3014830'>can</span> <span m='3014930'>almost</span>
  <span m='3015200'>even</span> <span m='3015470'>read--</span> <span m='3016140'>if</span>
  <span m='3016280'>you</span> <span m='3016370'>know</span> <span m='3016490'>Polish--</span>
  <span m='3017300'>you</span> <span m='3017420'>can</span> <span m='3017690'>almost</span>
  <span m='3018140'>read</span> <span m='3018870'>what</span> <span m='3019510'>the</span>
  <span m='3019790'>title</span> <span m='3020120'>says.</span> </p><p><span m='3022340'>So</span>
  <span m='3022490'>one</span> <span m='3022670'>more</span> <span m='3022820'>manipulation--</span>
  <span m='3024380'>I</span> <span m='3024530'>took</span> <span m='3024980'>a</span>
  <span m='3025100'>different</span> <span m='3025580'>picture</span> <span m='3029690'>and</span>
  <span m='3029840'>substituted</span> <span m='3030530'>the</span> <span m='3030650'>magnitude</span>
  <span m='3031340'>of</span> <span m='3031490'>that</span> <span m='3031790'>different</span>
  <span m='3032210'>picture</span> <span m='3033590'>in</span> <span m='3033740'>place</span>
  <span m='3034010'>of</span> <span m='3034070'>the</span> <span m='3034160'>magnitude</span>
  <span m='3034610'>of</span> <span m='3034670'>the</span> <span m='3034730'>boat</span>
  <span m='3034910'>picture.</span> <span m='3036210'>So</span> <span m='3038270'>angle</span>
  <span m='3038540'>with the</span> <span m='3038700'>boat,</span> <span m='3040130'>magnitude</span>
  <span m='3040700'>of</span> <span m='3040760'>the</span> <span m='3040850'>mystery</span>
  <span m='3041120'>picture,</span> <span m='3043890'>and</span> <span m='3044040'>it</span>
  <span m='3044100'>came</span> <span m='3044370'>out</span> <span m='3044760'>pretty</span>
  <span m='3045000'>good.</span> <span m='3048090'>But</span> <span m='3048300'>by</span>
  <span m='3048450'>the</span> <span m='3048570'>theory</span> <span m='3048840'>of</span>
  <span m='3048930'>lectures,</span> <span m='3049230'>of</span> <span m='3049320'>course,</span>
  <span m='3049530'>you</span> <span m='3049620'>know</span> <span m='3049800'>that</span>
  <span m='3050010'>the</span> <span m='3050130'>way</span> <span m='3050280'>I</span>
  <span m='3050370'>did</span> <span m='3050610'>this</span> <span m='3051180'>was</span>
  <span m='3051390'>to</span> <span m='3051510'>get</span> <span m='3051690'>a</span>
  <span m='3051750'>picture</span> <span m='3052410'>of a</span> <span m='3052770'>different</span>
  <span m='3053180'>boat,</span> <span m='3053910'>so</span> <span m='3054090'>that</span>
  <span m='3054210'>it</span> <span m='3054270'>would</span> <span m='3054390'>be</span>
  <span m='3054510'>very</span> <span m='3054750'>similar.</span> <span m='3058500'>And</span>
  <span m='3058830'>so</span> <span m='3059040'>that's</span> <span m='3059310'>what</span>
  <span m='3059550'>the</span> <span m='3059700'>magnitude</span> <span m='3060120'>was.</span>
  </p><p><span m='3061350'>[LAUGHTER]</span> </p><p><span m='3063600'>So</span> <span
  m='3063690'>it</span> <span m='3063750'>doesn't</span> <span m='3063990'>really</span>
  <span m='3064230'>matter</span> <span m='3064620'>much.</span> <span m='3067150'>So</span>
  <span m='3067740'>I</span> <span m='3068070'>started</span> <span m='3068430'>with</span>
  <span m='3068640'>this</span> <span m='3068910'>magnitude</span> <span m='3069450'>and</span>
  <span m='3069560'>angle,</span> <span m='3070410'>substitute</span> <span m='3071130'>the</span>
  <span m='3071790'>mandrill's</span> <span m='3072570'>magnitude,</span> <span m='3074070'>and</span>
  <span m='3074280'>you</span> <span m='3074400'>get</span> <span m='3074610'>that.</span>
  <span m='3075190'>So it</span> <span m='3075490'>comes</span> <span m='3075690'>out</span>
  <span m='3075780'>pretty</span> <span m='3075960'>good.</span> <span m='3076140'>So</span>
  <span m='3076230'>the</span> <span m='3076380'>idea</span> <span m='3076770'>then</span>
  <span m='3077370'>is</span> <span m='3077550'>just</span> <span m='3077730'>that</span>
  <span m='3077850'>we've</span> <span m='3078120'>looked</span> <span m='3078360'>at</span>
  <span m='3078490'>Fourier</span> <span m='3079500'>representations</span> <span
  m='3080940'>as</span> <span m='3081090'>an</span> <span m='3081180'>alternative</span>
  <span m='3081870'>way</span> <span m='3082080'>of</span> <span m='3082170'>thinking</span>
  <span m='3082500'>about</span> <span m='3082740'>the</span> <span m='3082830'>content</span>
  <span m='3083250'>of</span> <span m='3083340'>a</span> <span m='3083400'>signal.</span>
  <span m='3084240'>And</span> <span m='3084420'>for</span> <span m='3084570'>many</span>
  <span m='3084900'>purposes,</span> <span m='3085440'>like</span> <span m='3085650'>audio</span>
  <span m='3085950'>and</span> <span m='3086040'>video,</span> <span m='3086880'>that</span>
  <span m='3087120'>alternative</span> <span m='3087780'>representation</span> <span
  m='3088530'>is</span> <span m='3088680'>easy</span> <span m='3089100'>and</span>
  <span m='3089550'>insightful.</span> </p><p><span m='3092220'>No</span> <span m='3092400'>class</span>
  <span m='3092640'>tomorrow.</span> <span m='3093090'>It's</span> <span m='3093210'>Veterans</span>
  <span m='3093540'>Day.</span> <span m='3095130'>Party</span> <span m='3095490'>next</span>
  <span m='3095760'>Wednesday.</span> </p>
type: course
uid: 6cf031b75b40b8da42b06246a2633eed

---
None