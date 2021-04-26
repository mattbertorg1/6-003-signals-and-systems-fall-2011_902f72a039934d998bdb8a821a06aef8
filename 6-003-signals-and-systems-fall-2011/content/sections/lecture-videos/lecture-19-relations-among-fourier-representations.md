---
about_this_resource_text: <p><strong>Instructor:</strong> Dennis Freeman</p> <p><strong>Description:</strong>
  Today's lecture solidifies the connections between continuous- and discrete-time
  Fourier series and transforms, converting between the time and frequency domains
  with familiar tools such as convolution, periodic extension, and sampling.</p>
course_id: 6-003-signals-and-systems-fall-2011
embedded_media:
- id: Video-YouTube-Stream
  media_location: HDYAbIA-DNY
  parent_uid: b337e541707d5aefb6a1cc3b98184d53
  title: Video-YouTube-Stream
  type: Video
  uid: 417dc291eeb236a1058fa4a154aa56cb
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/HDYAbIA-DNY/default.jpg
  parent_uid: b337e541707d5aefb6a1cc3b98184d53
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 8ed9064fc5cc5dc68ecbbe06dea329b5
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/lecture-19-relations-among/id602305810?i=132455889
  parent_uid: b337e541707d5aefb6a1cc3b98184d53
  title: Video-iTunes U-MP4
  type: Video
  uid: da225bba0451514eba4840d871143bf6
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.003F11/MIT6_003F11_lec19_300k.mp4
  parent_uid: b337e541707d5aefb6a1cc3b98184d53
  title: Video-Internet Archive-MP4
  type: Video
  uid: ef8f6e2d5779e089e3428297a587e04d
- id: 3Play-3PlayYouTubeid-MP4
  media_location: HDYAbIA-DNY
  parent_uid: b337e541707d5aefb6a1cc3b98184d53
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 1e6a4c45d5572c08d23b332d621d206a
- id: HDYAbIA-DNY.srt
  parent_uid: b337e541707d5aefb6a1cc3b98184d53
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-19-relations-among-fourier-representations/HDYAbIA-DNY.srt
  title: 3play caption file
  type: null
  uid: 3c7f80c59522ba1bf7a49291d884ad18
- id: HDYAbIA-DNY.pdf
  parent_uid: b337e541707d5aefb6a1cc3b98184d53
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-19-relations-among-fourier-representations/HDYAbIA-DNY.pdf
  title: 3play pdf file
  type: null
  uid: d581337403d046f57e857c2057264f7c
- id: Caption-3Play YouTube id-SRT
  parent_uid: b337e541707d5aefb6a1cc3b98184d53
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: f36b13b011334c657a65ad751c2e6f54
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b337e541707d5aefb6a1cc3b98184d53
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 690da149105c97614fcb84b4be64bb8c
inline_embed_id: 95718384lecture19:relationsamongfourierrepresentations98977437
layout: video
order_index: null
parent_uid: 47b07fedf3a30be25f155f62399cdb59
related_resources_text: ''
short_url: lecture-19-relations-among-fourier-representations
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-19-relations-among-fourier-representations
template_type: Tabbed
title: 'Lecture 19: Relations Among Fourier Representations'
transcript: <p><span m='120'>The</span> <span m='210'>following</span> <span m='630'>content</span>
  <span m='1200'>is</span> <span m='1350'>provided</span> <span m='1800'>under</span>
  <span m='2040'>a</span> <span m='2100'>Creative</span> <span m='2520'>Commons</span>
  <span m='2910'>license.</span> <span m='4059'>Your</span> <span m='4200'>support</span>
  <span m='4710'>will</span> <span m='4890'>help</span> <span m='5130'>MIT</span>
  <span m='5580'>OpenCourseWare</span> <span m='6360'>continue</span> <span m='6870'>to</span>
  <span m='6990'>offer</span> <span m='7410'>high</span> <span m='7620'>quality</span>
  <span m='8130'>educational</span> <span m='8760'>resources</span> <span m='9360'>for</span>
  <span m='9540'>free.</span> <span m='10750'>To</span> <span m='10770'>make</span>
  <span m='10950'>a</span> <span m='11010'>donation</span> <span m='11760'>or</span>
  <span m='11940'>view</span> <span m='12420'>additional</span> <span m='12810'>materials</span>
  <span m='13350'>from</span> <span m='13530'>hundreds</span> <span m='13950'>of</span>
  <span m='14040'>MIT</span> <span m='14490'>courses,</span> <span m='15580'>visit</span>
  <span m='15780'>MIT</span> <span m='16230'>OpenCourseWare</span> <span m='17310'>at</span>
  <span m='17430'>ocw.mit.edu.</span> </p><p><span m='21780'>DENNIS FREEMAN:</span>
  <span m='21990'>Hello.</span> <span m='24505'>So</span> <span m='24970'>there's</span>
  <span m='26290'>almost</span> <span m='26980'>certainly</span> <span m='27700'>no</span>
  <span m='27910'>need</span> <span m='28150'>to</span> <span m='28240'>show</span>
  <span m='28450'>this,</span> <span m='29890'>but</span> <span m='30160'>the</span>
  <span m='30250'>good</span> <span m='30370'>news</span> <span m='30640'>is</span>
  <span m='31600'>this</span> <span m='31810'>is</span> <span m='31960'>the</span>
  <span m='32080'>last</span> <span m='32470'>time</span> <span m='32780'>I'll</span>
  <span m='32920'>ever</span> <span m='33160'>show</span> <span m='33400'>a</span>
  <span m='33430'>slide</span> <span m='33760'>like</span> <span m='33970'>this.</span>
  <span m='35420'>It'll</span> <span m='35650'>never</span> <span m='36010'>happen</span>
  <span m='36370'>again.</span> <span m='36670'>At</span> <span m='36730'>least</span>
  <span m='36910'>not</span> <span m='37090'>to</span> <span m='37180'>this</span>
  <span m='37360'>crowd.</span> </p><p><span m='37750'>So</span> <span m='38890'>you</span>
  <span m='39040'>can</span> <span m='39160'>all</span> <span m='39340'>rest</span>
  <span m='39610'>assured</span> <span m='40060'>this</span> <span m='40240'>is</span>
  <span m='40330'>the</span> <span m='40420'>last</span> <span m='40720'>time</span>
  <span m='40960'>you'll</span> <span m='41110'>see</span> <span m='41290'>something</span>
  <span m='41620'>like</span> <span m='41800'>this.</span> <span m='43780'>Any</span>
  <span m='44020'>questions</span> <span m='44830'>on</span> <span m='45310'>this,</span>
  <span m='45730'>everybody's</span> <span m='46330'>happy?</span> <span m='49180'>Those</span>
  <span m='49390'>are</span> <span m='49480'>two</span> <span m='49690'>separate</span>
  <span m='50020'>questions,</span> <span m='50560'>I</span> <span m='50620'>guess.</span>
  <span m='52210'>Any</span> <span m='52450'>questions</span> <span m='53050'>on</span>
  <span m='53230'>this?</span> <span m='56120'>OK,</span> <span m='56290'>good.</span>
  </p><p><span m='57940'>So</span> <span m='58540'>today</span> <span m='59170'>I</span>
  <span m='59320'>want</span> <span m='59500'>to</span> <span m='60760'>finish</span>
  <span m='61060'>up</span> <span m='61150'>talking</span> <span m='61390'>about</span>
  <span m='61540'>Fourier</span> <span m='61780'>transforms</span> <span m='62680'>by</span>
  <span m='62890'>comparing</span> <span m='63640'>a</span> <span m='63730'>lot</span>
  <span m='63940'>of</span> <span m='64000'>stuff</span> <span m='64300'>we've</span>
  <span m='64450'>already</span> <span m='64780'>done.</span> <span m='65129'>So</span>
  <span m='65200'>there's</span> <span m='65349'>nothing</span> <span m='65620'>new</span>
  <span m='65800'>today.</span> <span m='67840'>This</span> <span m='68050'>is</span>
  <span m='68170'>intended,</span> <span m='68620'>if</span> <span m='68740'>anything,</span>
  <span m='69160'>to</span> <span m='69250'>be</span> <span m='69370'>a</span> <span
  m='69430'>bit</span> <span m='69580'>of</span> <span m='69670'>a</span> <span m='69730'>review</span>
  <span m='71320'>in</span> <span m='71470'>light</span> <span m='71680'>of</span>
  <span m='71770'>things</span> <span m='72010'>that</span> <span m='72100'>might</span>
  <span m='72220'>happen</span> <span m='72460'>tomorrow.</span> <span m='74740'>And</span>
  <span m='75700'>also</span> <span m='76000'>just</span> <span m='76210'>to</span>
  <span m='76300'>make</span> <span m='76510'>things</span> <span m='76780'>look</span>
  <span m='76960'>simpler.</span> </p><p><span m='78250'>Now,</span> <span m='79120'>the</span>
  <span m='79210'>best</span> <span m='79420'>way</span> <span m='79540'>to</span>
  <span m='79630'>make</span> <span m='79780'>things</span> <span m='80020'>look</span>
  <span m='80170'>simpler</span> <span m='80860'>is</span> <span m='81010'>to</span>
  <span m='81100'>start</span> <span m='81340'>with</span> <span m='81460'>something</span>
  <span m='81760'>that</span> <span m='81880'>looks</span> <span m='82090'>incredibly</span>
  <span m='82840'>complicated.</span> <span m='84220'>OK,</span> <span m='84520'>so</span>
  <span m='84700'>this</span> <span m='84910'>is</span> <span m='85030'>my</span>
  <span m='85180'>thing</span> <span m='85420'>that</span> <span m='85540'>looks</span>
  <span m='85720'>very</span> <span m='85990'>complicated.</span> <span m='87020'>This</span>
  <span m='87100'>is</span> <span m='87190'>simply</span> <span m='87550'>a</span>
  <span m='87610'>summary</span> <span m='90400'>of</span> <span m='90550'>the</span>
  <span m='90910'>transforms</span> <span m='91720'>that</span> <span m='91810'>we've</span>
  <span m='91960'>talked</span> <span m='92260'>about</span> <span m='92470'>today.</span>
  <span m='92830'>We've</span> <span m='92950'>talked</span> <span m='93160'>about</span>
  <span m='93370'>four</span> <span m='93610'>of</span> <span m='93710'>them.</span>
  </p><p><span m='95420'>And</span> <span m='95680'>the</span> <span m='95770'>point</span>
  <span m='96190'>of</span> <span m='96280'>the</span> <span m='96400'>slide</span>
  <span m='97630'>is</span> <span m='97900'>first,</span> <span m='98980'>it</span>
  <span m='99130'>looks</span> <span m='99340'>a</span> <span m='99400'>little</span>
  <span m='99580'>complicated.</span> <span m='101020'>But</span> <span m='101230'>much</span>
  <span m='101590'>more</span> <span m='101740'>importantly,</span> <span m='102790'>by</span>
  <span m='102940'>the</span> <span m='103120'>end</span> <span m='103360'>of</span>
  <span m='103420'>the</span> <span m='103600'>hour,</span> <span m='103930'>it's</span>
  <span m='104050'>supposed</span> <span m='104410'>to</span> <span m='104530'>look</span>
  <span m='104770'>very</span> <span m='105250'>simple.</span> <span m='105640'>Yes?</span>
  </p><p><span m='106000'>AUDIENCE:</span> <span m='106225'>Could</span> <span m='106450'>we</span>
  <span m='106900'>increase</span> <span m='107350'>the volume?</span> </p><p><span
  m='109180'>DENNIS FREEMAN:</span> <span m='109270'>Could</span> <span m='109360'>we</span>
  <span m='109540'>increase</span> <span m='109900'>the</span> <span m='109990'>volume</span>
  <span m='110320'>a</span> <span m='110380'>bit?</span> <span m='110570'>Well,</span>
  <span m='111070'>I</span> <span m='111190'>know</span> <span m='111430'>that</span>
  <span m='111580'>I</span> <span m='111760'>can</span> <span m='111940'>shout</span>
  <span m='112420'>more.</span> <span m='113860'>And</span> <span m='114190'>if</span>
  <span m='114490'>they</span> <span m='114730'>notice</span> <span m='115090'>me,</span>
  <span m='115510'>they'll</span> <span m='115690'>turn</span> <span m='115960'>the</span>
  <span m='116050'>volume</span> <span m='116350'>up,</span> <span m='116500'>too.</span>
  <span m='117580'>So</span> <span m='117790'>I</span> <span m='117910'>will</span>
  <span m='118090'>try</span> <span m='118300'>to</span> <span m='118390'>shout</span>
  <span m='118660'>more.</span> <span m='118870'>So</span> <span m='119050'>if</span>
  <span m='119140'>I</span> <span m='119200'>don't,</span> <span m='119660'>please</span>
  <span m='120400'>tell</span> <span m='120580'>me</span> <span m='120700'>to</span>
  <span m='120790'>do</span> <span m='121560'>so.</span> </p><p><span m='124190'>So</span>
  <span m='125140'>the</span> <span m='125260'>idea,</span> <span m='125560'>then,</span>
  <span m='126050'>is</span> <span m='126220'>to</span> <span m='126340'>try</span>
  <span m='126580'>to</span> <span m='126670'>look</span> <span m='126910'>for</span>
  <span m='127090'>some</span> <span m='127300'>structure.</span> <span m='129639'>Not</span>
  <span m='129880'>only</span> <span m='130150'>within</span> <span m='130509'>one</span>
  <span m='130720'>of</span> <span m='130780'>the</span> <span m='130870'>transforms,</span>
  <span m='131530'>but</span> <span m='131680'>also</span> <span m='132130'>across</span>
  <span m='133900'>all</span> <span m='134130'>of</span> <span m='134210'>the</span>
  <span m='134290'>transforms.</span> <span m='136660'>And</span> <span m='137440'>to</span>
  <span m='138130'>start</span> <span m='138580'>this</span> <span m='138820'>off,</span>
  <span m='139540'>let's</span> <span m='139720'>just</span> <span m='139930'>think</span>
  <span m='140110'>about</span> <span m='140350'>it</span> <span m='140470'>at</span>
  <span m='140560'>the</span> <span m='140680'>most</span> <span m='140980'>basic</span>
  <span m='141460'>level.</span> </p><p><span m='142120'>What</span> <span m='142300'>were</span>
  <span m='142450'>the</span> <span m='142570'>kinds</span> <span m='142870'>of</span>
  <span m='142990'>signals</span> <span m='145220'>that</span> <span m='145340'>we</span>
  <span m='145490'>thought</span> <span m='145730'>about?</span> <span m='146510'>The</span>
  <span m='146600'>kinds</span> <span m='146870'>of</span> <span m='146960'>signals</span>
  <span m='147560'>that</span> <span m='147650'>we</span> <span m='147770'>thought</span>
  <span m='147980'>about</span> <span m='148220'>when</span> <span m='148370'>we</span>
  <span m='148490'>did</span> <span m='148670'>DT</span> <span m='149080'>Fourier</span>
  <span m='149510'>series,</span> <span m='149815'>DT</span> <span m='150410'>Fourier</span>
  <span m='150850'>transforms,</span> <span m='151890'>CT</span> <span m='152310'>Fourier</span>
  <span m='152780'>series,</span> <span m='153060'>and</span> <span m='153340'>CT</span>
  <span m='154100'>Fourier</span> <span m='154460'>transforms?</span> <span m='154940'>The</span>
  <span m='155030'>kinds</span> <span m='155270'>of</span> <span m='155360'>signals</span>
  <span m='157600'>look</span> <span m='157870'>different,</span> <span m='159860'>right?</span>
  </p><p><span m='160570'>So</span> <span m='161040'>in</span> <span m='161230'>the</span>
  <span m='161350'>top</span> <span m='161710'>ones,</span> <span m='162160'>we</span>
  <span m='162310'>had</span> <span m='162430'>discrete</span> <span m='162910'>time.</span>
  <span m='164290'>In</span> <span m='164470'>the</span> <span m='164560'>bottom</span>
  <span m='164890'>ones,</span> <span m='165100'>we</span> <span m='165220'>have</span>
  <span m='165370'>continuous</span> <span m='165880'>time.</span> <span m='167470'>In</span>
  <span m='167650'>the</span> <span m='167770'>left</span> <span m='168230'>we</span>
  <span m='168400'>have</span> <span m='168520'>things</span> <span m='168790'>that</span>
  <span m='168910'>are</span> <span m='169120'>periodic.</span> <span m='171070'>In</span>
  <span m='171220'>the</span> <span m='171340'>right</span> <span m='171700'>we</span>
  <span m='171820'>had</span> <span m='171910'>things</span> <span m='172180'>that</span>
  <span m='172270'>were</span> <span m='172420'>not</span> <span m='172780'>periodic.</span>
  <span m='174190'>Four</span> <span m='174430'>different</span> <span m='174700'>kinds</span>
  <span m='174940'>of</span> <span m='175030'>signals.</span> <span m='175380'>Not</span>
  <span m='175510'>surprising</span> <span m='175990'>there</span> <span m='176140'>would</span>
  <span m='176230'>be</span> <span m='176320'>four</span> <span m='176500'>different</span>
  <span m='176740'>kinds</span> <span m='177010'>of</span> <span m='177220'>transforms.</span>
  </p><p><span m='179590'>An</span> <span m='179740'>interesting</span> <span m='180310'>thing</span>
  <span m='180520'>happens</span> <span m='180970'>if</span> <span m='181090'>you</span>
  <span m='181210'>look</span> <span m='181420'>at</span> <span m='181510'>the</span>
  <span m='181600'>Fourier</span> <span m='182170'>domain.</span> <span m='184210'>I</span>
  <span m='184330'>haven't</span> <span m='184630'>switched</span> <span m='184990'>around</span>
  <span m='185260'>the</span> <span m='185380'>order.</span> <span m='185770'>It</span>
  <span m='185920'>was</span> <span m='186580'>DT</span> <span m='186970'>Fourier,</span>
  <span m='187510'>DT</span> <span m='187990'>Fourier</span> <span m='188250'>transform,</span>
  <span m='188800'>CT</span> <span m='189210'>series,</span> <span m='189720'>CT</span>
  <span m='190090'>transform.</span> <span m='190990'>It's</span> <span m='191170'>still</span>
  <span m='191510'>that.</span> </p><p><span m='194530'>I've</span> <span m='194710'>drawn</span>
  <span m='195040'>a</span> <span m='195100'>sort</span> <span m='195340'>of</span>
  <span m='195430'>iconic</span> <span m='196060'>view</span> <span m='196480'>of</span>
  <span m='196570'>how</span> <span m='196750'>we</span> <span m='196930'>would</span>
  <span m='197080'>draw</span> <span m='197410'>a</span> <span m='197440'>picture</span>
  <span m='199580'>of</span> <span m='199820'>the</span> <span m='199920'>Fourier</span>
  <span m='200270'>transform</span> <span m='200580'>of</span> <span m='200890'>interest.</span>
  <span m='202510'>Where</span> <span m='203440'>is</span> <span m='203800'>discrete?</span>
  <span m='208080'>So</span> <span m='208260'>discrete</span> <span m='208770'>in</span>
  <span m='208890'>the</span> <span m='208980'>previous</span> <span m='209430'>picture--</span>
  <span m='209760'>which</span> <span m='209980'>was</span> <span m='210120'>a</span>
  <span m='210180'>picture</span> <span m='210540'>of</span> <span m='210690'>time--</span>
  <span m='212220'>NNTT.</span> <span m='213860'>Where</span> <span m='214020'>was</span>
  <span m='214200'>discrete</span> <span m='214590'>in</span> <span m='214710'>this</span>
  <span m='214830'>picture?</span> <span m='219070'>Up.</span> </p><p><span m='220300'>Where</span>
  <span m='220600'>is</span> <span m='220750'>discrete</span> <span m='221350'>in</span>
  <span m='221470'>this</span> <span m='221650'>picture?</span> <span m='224290'>Left,</span>
  <span m='225160'>that's</span> <span m='225610'>weird.</span> <span m='228970'>Where</span>
  <span m='229300'>is</span> <span m='229450'>periodic</span> <span m='230170'>in</span>
  <span m='230290'>this</span> <span m='230440'>picture?</span> <span m='233770'>Left.</span>
  <span m='236130'>Where</span> <span m='236300'>is</span> <span m='236420'>periodic</span>
  <span m='236990'>in</span> <span m='237140'>this</span> <span m='237320'>picture?</span>
  <span m='242110'>Is</span> <span m='242260'>there</span> <span m='242380'>a</span>
  <span m='242410'>periodic</span> <span m='242890'>in</span> <span m='242980'>this</span>
  <span m='243100'>picture?</span> <span m='245700'>Top.</span> <span m='246030'>Why</span>
  <span m='246150'>do</span> <span m='246210'>you</span> <span m='246270'>say</span>
  <span m='246490'>top?</span> <span m='248760'>Ah,</span> <span m='249800'>unit</span>
  <span m='250170'>circle!</span> <span m='250950'>Unit circle</span> <span m='251280'>is</span>
  <span m='251580'>periodic.</span> </p><p><span m='253050'>So</span> <span m='253290'>there's</span>
  <span m='253530'>discreteness</span> <span m='254160'>and</span> <span m='254310'>periodicity</span>
  <span m='255150'>in</span> <span m='255360'>both</span> <span m='255810'>pictures,</span>
  <span m='257490'>but</span> <span m='257640'>they're</span> <span m='257760'>not</span>
  <span m='257970'>at</span> <span m='258060'>the</span> <span m='258180'>same</span>
  <span m='258450'>place.</span> <span m='260890'>Well,</span> <span m='261070'>that's</span>
  <span m='261190'>kind</span> <span m='261370'>of</span> <span m='261430'>interesting,</span>
  <span m='261890'>right?</span> <span m='263050'>Somehow,</span> <span m='263950'>discrete</span>
  <span m='264370'>and</span> <span m='264460'>periodic</span> <span m='264970'>map</span>
  <span m='265240'>to</span> <span m='265390'>things</span> <span m='265630'>like</span>
  <span m='265780'>discrete</span> <span m='266050'>and</span> <span m='266140'>periodic,</span>
  <span m='266590'>but</span> <span m='266710'>they</span> <span m='266800'>don't</span>
  <span m='267010'>map</span> <span m='267250'>directly.</span> <span m='269110'>That's</span>
  <span m='269290'>kind</span> <span m='269500'>of</span> <span m='269560'>interesting.</span>
  </p><p><span m='270380'>So</span> <span m='270640'>part</span> <span m='270850'>of</span>
  <span m='270910'>the</span> <span m='271060'>goal</span> <span m='271330'>today</span>
  <span m='271630'>is</span> <span m='271750'>to</span> <span m='271840'>try</span>
  <span m='271960'>to</span> <span m='272050'>get</span> <span m='272170'>to</span>
  <span m='272260'>the</span> <span m='272350'>bottom</span> <span m='272590'>of</span>
  <span m='272650'>that.</span> <span m='272800'>To</span> <span m='272860'>understand</span>
  <span m='273220'>why</span> <span m='273370'>that's</span> <span m='273550'>true.</span>
  <span m='275380'>You</span> <span m='275500'>already</span> <span m='275860'>know</span>
  <span m='276250'>a</span> <span m='276400'>lot</span> <span m='277360'>about</span>
  <span m='277900'>how</span> <span m='278320'>different</span> <span m='278710'>transformations</span>
  <span m='279520'>are</span> <span m='279670'>related.</span> <span m='281210'>So</span>
  <span m='281440'>let's</span> <span m='281650'>think</span> <span m='281800'>of</span>
  <span m='281920'>a</span> <span m='281980'>simple</span> <span m='282460'>example</span>
  <span m='283000'>of</span> <span m='283150'>the</span> <span m='283210'>relation</span>
  <span m='283630'>between</span> <span m='283990'>Fourier</span> <span m='284380'>series</span>
  <span m='284740'>and</span> <span m='284830'>Fourier</span> <span m='285160'>transforms.</span>
  </p><p><span m='285690'>Imagine</span> <span m='286060'>that</span> <span m='286150'>we</span>
  <span m='286270'>have</span> <span m='286420'>one</span> <span m='286540'>of</span>
  <span m='286600'>those</span> <span m='286750'>signals</span> <span m='287140'>that</span>
  <span m='287230'>was</span> <span m='287350'>periodic</span> <span m='287860'>in</span>
  <span m='287950'>time,</span> <span m='288660'>continuous</span> <span m='289720'>in</span>
  <span m='290080'>time.</span> <span m='291400'>Then</span> <span m='291610'>there'd</span>
  <span m='291770'>be</span> <span m='291970'>a</span> <span m='292040'>Fourier</span>
  <span m='292340'>series--</span> <span m='292870'>represented</span> <span m='293410'>this</span>
  <span m='293590'>way.</span> <span m='295360'>So</span> <span m='295480'>I'd</span>
  <span m='295570'>end</span> <span m='295750'>up</span> <span m='295900'>with a</span>
  <span m='296140'>Fourier</span> <span m='296560'>series</span> <span m='296980'>that</span>
  <span m='297070'>has</span> <span m='297220'>a bunch of</span> <span m='297460'>coefficients,</span>
  <span m='298060'>a, k.</span> </p><p><span m='300100'>Can</span> <span m='300280'>somebody</span>
  <span m='300610'>tell</span> <span m='300790'>me,</span> <span m='300910'>what</span>
  <span m='301030'>would the</span> <span m='301180'>Fourier</span> <span m='301450'>transform</span>
  <span m='301870'>look</span> <span m='301990'>like?</span> <span m='305730'>Fourier</span>
  <span m='306100'>transform--</span> <span m='306520'>are you</span> <span m='306610'>allowed
  to</span> <span m='306950'>take</span> <span m='307030'>the</span> <span m='307120'>Fourier</span>
  <span m='307360'>transform</span> <span m='307660'>of a</span> <span m='307960'>periodic</span>
  <span m='308380'>thing?</span> <span m='314057'>Yeah?</span> </p><p><span m='314554'>AUDIENCE:</span>
  <span m='314802'>Could</span> <span m='315051'>we</span> <span m='315548'>take the</span>
  <span m='316045'>same thing</span> <span m='316542'>with</span> <span m='317039'>impulses?</span>
  </p><p><span m='318040'>DENNIS FREEMAN:</span> <span m='318145'>Take</span> <span
  m='318250'>the</span> <span m='318400'>same</span> <span m='318670'>thing</span>
  <span m='318880'>with</span> <span m='319030'>impulses.</span> <span m='319720'>OK,</span>
  <span m='320020'>I</span> <span m='320110'>like</span> <span m='320620'>lots</span>
  <span m='320890'>of</span> <span m='320980'>those</span> <span m='321190'>words.</span>
  <span m='321650'>Could</span> <span m='321700'>you</span> <span m='321760'>put</span>
  <span m='321910'>them</span> <span m='322030'>together</span> <span m='322390'>in</span>
  <span m='322480'>slightly a</span> <span m='322840'>different</span> <span m='323110'>order?</span>
  <span m='325420'>Where</span> <span m='325720'>should</span> <span m='325900'>I</span>
  <span m='325960'>put</span> <span m='326110'>the</span> <span m='326200'>impulses?</span>
  <span m='329776'>Yeah?</span> </p><p><span m='330758'>AUDIENCE:</span> <span m='331003'>At</span>
  <span m='331249'>the</span> <span m='331740'>k</span> <span m='332231'>omega</span>
  <span m='332730'>not.</span> </p><p><span m='333166'>DENNIS FREEMAN:</span> <span
  m='333384'>At</span> <span m='333602'>the</span> <span m='334460'>k</span> <span
  m='334700'>omega</span> <span m='335040'>not.</span> <span m='335270'>How</span>
  <span m='335400'>do</span> <span m='335480'>you</span> <span m='335570'>get</span>
  <span m='335780'>that?</span> <span m='336080'>That's</span> <span m='336260'>exactly</span>
  <span m='336650'>right.</span> <span m='336800'>How'd</span> <span m='336950'>you</span>
  <span m='337010'>get</span> <span m='337160'>that?</span> </p><p><span m='337420'>AUDIENCE:</span>
  <span m='337664'>Because</span> <span m='338884'>the</span> <span m='340348'>[INAUDIBLE].</span>
  </p><p><span m='354510'>DENNIS FREEMAN:</span> <span m='354570'>So</span> <span
  m='354630'>there's</span> <span m='354780'>some</span> <span m='354990'>kind</span>
  <span m='355170'>of</span> <span m='355260'>a</span> <span m='355290'>relationship</span>
  <span m='355890'>between</span> <span m='356400'>the</span> <span m='356520'>k's,</span>
  <span m='357600'>in</span> <span m='358420'>the</span> <span m='358740'>ak's,</span>
  <span m='360480'>and</span> <span m='360690'>frequency</span> <span m='361230'>that</span>
  <span m='361380'>ought</span> <span m='361500'>to</span> <span m='361560'>be</span>
  <span m='361680'>represented</span> <span m='362240'>as</span> <span m='362370'>an</span>
  <span m='362460'>impulse,</span> <span m='362790'>is</span> <span m='363360'>what</span>
  <span m='363480'>you're</span> <span m='363600'>saying?</span> <span m='365250'>One</span>
  <span m='365550'>way</span> <span m='365730'>you</span> <span m='365880'>can</span>
  <span m='366030'>see</span> <span m='366240'>that</span> <span m='366540'>is</span>
  <span m='366690'>to</span> <span m='366780'>take</span> <span m='366960'>the</span>
  <span m='367080'>Fourier</span> <span m='367410'>transform</span> <span m='367920'>of</span>
  <span m='367980'>this</span> <span m='368190'>expression.</span> </p><p><span m='368710'>What</span>
  <span m='368810'>would</span> <span m='368900'>you</span> <span m='368970'>get</span>
  <span m='369150'>if</span> <span m='369240'>you</span> <span m='369470'>took</span>
  <span m='369650'>the</span> <span m='369880'>Fourier</span> <span m='370170'>transform</span>
  <span m='370620'>of</span> <span m='370680'>x</span> <span m='370860'>of</span>
  <span m='370980'>t,</span> <span m='371370'>x</span> <span m='371670'>of</span>
  <span m='371760'>j</span> <span m='372000'>omega?</span> <span m='372420'>That's</span>
  <span m='372600'>pretty</span> <span m='372750'>easy.</span> <span m='373500'>What</span>
  <span m='373710'>would</span> <span m='373830'>you</span> <span m='373890'>get</span>
  <span m='374040'>if</span> <span m='374130'>you</span> <span m='374220'>took</span>
  <span m='374350'>the</span> <span m='374440'>Fourier</span> <span m='374670'>transform</span>
  <span m='375070'>of a</span> <span m='375180'>sum?</span> <span m='379050'>What</span>
  <span m='379360'>do</span> <span m='379460'>you</span> <span m='379580'>always</span>
  <span m='379850'>get when</span> <span m='380050'>you</span> <span m='380110'>take
  the</span> <span m='380240'>Fourier</span> <span m='380470'>transfer</span> <span
  m='380820'>of</span> <span m='380890'>a sum?</span> <span m='382560'>The</span>
  <span m='383030'>sum</span> <span m='383240'>of</span> <span m='383300'>the</span>
  <span m='383360'>Fourier</span> <span m='383510'>transforms,</span> <span m='383960'>right?
  It's</span> <span m='384230'>within</span> <span m='384390'>your</span> <span m='384530'>operator.</span>
  </p><p><span m='385850'>That's</span> <span m='386150'>one</span> <span m='386420'>of</span>
  <span m='386480'>the</span> <span m='386540'>most</span> <span m='386960'>powerful</span>
  <span m='387320'>reasons</span> <span m='387650'>we</span> <span m='387740'>like</span>
  <span m='387950'>it.</span> <span m='388880'>So</span> <span m='389150'>sum</span>
  <span m='390620'>of</span> <span m='390680'>the</span> <span m='390740'>functions,</span>
  <span m='391430'>take</span> <span m='391640'>the</span> <span m='391860'>transform
  of</span> <span m='392270'>each</span> <span m='392450'>one.</span> <span m='392780'>Add</span>
  <span m='392840'>them</span> <span m='392930'>back</span> <span m='393170'>up.</span>
  <span m='394160'>How</span> <span m='394250'>do</span> <span m='394310'>you</span>
  <span m='394370'>take</span> <span m='394520'>the</span> <span m='394610'>Fourier</span>
  <span m='394850'>transform</span> <span m='395900'>of</span> <span m='396340'>e
  to the</span> <span m='396590'>j omega</span> <span m='396980'>not</span> <span
  m='397180'>t?</span> </p><p><span m='398510'>What's</span> <span m='398750'>the</span>
  <span m='398870'>Fourier</span> <span m='399180'>transform?</span> <span m='399790'>e</span>
  <span m='400000'>to</span> <span m='400150'>the</span> <span m='400280'>j</span>
  <span m='400790'>omega</span> <span m='401170'>not</span> <span m='401450'>t</span>
  <span m='402410'>transforms</span> <span m='403040'>to</span> <span m='403190'>what?</span>
  <span m='404570'>Fourier</span> <span m='405230'>transform--</span> <span m='409250'>impulse.</span>
  <span m='410840'>So</span> <span m='411520'>how</span> <span m='411650'>do</span>
  <span m='411740'>I</span> <span m='411830'>know</span> <span m='412010'>that?</span>
  <span m='413000'>So</span> <span m='413270'>impulse--</span> <span m='416360'>what</span>
  <span m='416540'>else,</span> <span m='416780'>anything?</span> <span m='417700'>Am</span>
  <span m='417830'>I</span> <span m='417940'>done?</span> </p><p><span m='420960'>Where</span>
  <span m='421110'>should</span> <span m='421260'>I</span> <span m='421320'>put</span>
  <span m='421470'>the</span> <span m='421590'>impulse?</span> <span m='427140'>What</span>
  <span m='427360'>should</span> <span m='427510'>I</span> <span m='427600'>put--</span>
  <span m='428260'>how</span> <span m='428500'>should I</span> <span m='428730'>indicate</span>
  <span m='429160'>where</span> <span m='429340'>I</span> <span m='429430'>put</span>
  <span m='429610'>it?</span> <span m='431800'>So</span> <span m='431920'>I</span>
  <span m='432010'>need</span> <span m='432190'>to</span> <span m='432310'>say</span>
  <span m='432580'>omega</span> <span m='433270'>minus</span> <span m='433900'>omega</span>
  <span m='434210'>not,</span> <span m='435250'>or</span> <span m='435370'>something</span>
  <span m='435640'>like</span> <span m='435820'>that,</span> <span m='436075'>right?</span>
  </p><p><span m='437510'>So</span> <span m='438610'>how</span> <span m='438700'>do</span>
  <span m='438790'>I</span> <span m='438880'>know</span> <span m='439030'>that?</span>
  <span m='440940'>And</span> <span m='441070'>am</span> <span m='441250'>I</span>
  <span m='441340'>done?</span> <span m='443970'>Yeah?</span> </p><p><span m='444606'>AUDIENCE:</span>
  <span m='444829'>Multiply</span> <span m='445052'>by 2 pi.</span> </p><p><span m='445500'>DENNIS
  FREEMAN:</span> <span m='445680'>Multiply</span> <span m='445860'>by</span> <span
  m='446010'>2</span> <span m='446200'>pi.</span> <span m='446910'>And</span> <span
  m='447030'>a</span> <span m='447090'>good</span> <span m='447240'>way</span> <span
  m='447390'>to</span> <span m='447480'>do</span> <span m='447630'>that</span> <span
  m='447810'>is</span> <span m='447900'>just</span> <span m='448050'>to</span> <span
  m='448140'>memorize an</span> <span m='448540'>absurd</span> <span m='448830'>number</span>
  <span m='449070'>of</span> <span m='449130'>equations,</span> <span m='449580'>right?</span>
  <span m='452100'>Let's</span> <span m='452280'>think</span> <span m='452460'>about</span>
  <span m='452670'>how</span> <span m='452820'>you</span> <span m='452940'>would</span>
  <span m='453060'>remember</span> <span m='453390'>that.</span> </p><p><span m='453600'>So</span>
  <span m='454470'>if</span> <span m='454680'>you</span> <span m='454830'>wanted</span>
  <span m='455070'>to</span> <span m='455130'>take</span> <span m='455310'>the</span>
  <span m='455400'>Fourier</span> <span m='455700'>transform</span> <span m='456150'>of</span>
  <span m='456270'>anything,</span> <span m='456960'>right?</span> <span m='457200'>You</span>
  <span m='457350'>would</span> <span m='457440'>say,</span> <span m='457680'>h</span>
  <span m='457860'>of</span> <span m='457960'>j omega</span> <span m='460440'>is</span>
  <span m='460590'>some</span> <span m='460830'>integral</span> <span m='461310'>of</span>
  <span m='461430'>anything</span> <span m='462952'>e to the</span> <span m='463430'>minus</span>
  <span m='463760'>j</span> <span m='464030'>omega</span> <span m='464520'>t</span>
  <span m='465020'>dt,</span> <span m='465290'>right?</span> </p><p><span m='467550'>What</span>
  <span m='467670'>happens</span> <span m='467970'>if</span> <span m='468060'>I</span>
  <span m='468120'>plug</span> <span m='468510'>x</span> <span m='468750'>of</span>
  <span m='468900'>t</span> <span m='469230'>equals</span> <span m='469560'>e</span>
  <span m='469770'>to</span> <span m='470040'>the</span> <span m='470160'>j</span>
  <span m='470320'>omega</span> <span m='470620'>not</span> <span m='470850'>t</span>
  <span m='471180'>into</span> <span m='471360'>this</span> <span m='471510'>expression?</span>
  <span m='475540'>Can</span> <span m='475720'>you</span> <span m='475840'>close</span>
  <span m='476080'>the</span> <span m='476170'>integral?</span> <span m='479000'>I</span>
  <span m='479060'>mean,</span> <span m='479180'>that's</span> <span m='479360'>the</span>
  <span m='479450'>way</span> <span m='479540'>you</span> <span m='479660'>would</span>
  <span m='479750'>do</span> <span m='479930'>it,</span> <span m='480080'>right?</span>
  <span m='480470'>I</span> <span m='480530'>want</span> <span m='480650'>to</span>
  <span m='480710'>take</span> <span m='480830'>the</span> <span m='480920'>Fourier</span>
  <span m='481220'>transform</span> <span m='481850'>of</span> <span m='482150'>e</span>
  <span m='482280'>to</span> <span m='482360'>the</span> <span m='482420'>j omega</span>
  <span m='482780'>not</span> <span m='482910'>t.</span> <span m='484340'>You</span>
  <span m='484520'>stick</span> <span m='484850'>it</span> <span m='484940'>in</span>
  <span m='485030'>the</span> <span m='485120'>formula,</span> <span m='485660'>and</span>
  <span m='485750'>it</span> <span m='485990'>should</span> <span m='486200'>come</span>
  <span m='486350'>out,</span> <span m='486530'>right?</span> </p><p><span m='490900'>So</span>
  <span m='491170'>how</span> <span m='491350'>many</span> <span m='491590'>of</span>
  <span m='491680'>you</span> <span m='491770'>can</span> <span m='491920'>integrate</span>
  <span m='492220'>this</span> <span m='492370'>function?</span> <span m='498000'>No</span>
  <span m='498180'>one,</span> <span m='498420'>good.</span> <span m='499080'>That's</span>
  <span m='499290'>good,</span> <span m='499470'>because</span> <span m='499680'>I</span>
  <span m='499740'>can't</span> <span m='499980'>either.</span> <span m='502320'>What's</span>
  <span m='502560'>hard</span> <span m='502830'>about</span> <span m='503040'>integrating</span>
  <span m='503430'>that</span> <span m='503550'>function?</span> </p><p><span m='510130'>That</span>
  <span m='510220'>was</span> <span m='510340'>a</span> <span m='510580'>much easier</span>
  <span m='510760'>question,</span> <span m='511060'>right?</span> <span m='511300'>Can</span>
  <span m='511450'>you</span> <span m='511570'>integrate</span> <span m='511980'>was
  a</span> <span m='512120'>hard</span> <span m='512289'>question.</span> <span m='513880'>Well,</span>
  <span m='514480'>maybe</span> <span m='514690'>not.</span> <span m='514870'>It's</span>
  <span m='515020'>binary.</span> <span m='516760'>What's</span> <span m='517000'>difficult</span>
  <span m='517600'>about</span> <span m='517960'>integrating</span> <span m='518409'>that</span>
  <span m='518530'>function</span> <span m='519010'>of</span> <span m='519429'>time?</span>
  <span m='520330'>What</span> <span m='520480'>if</span> <span m='520539'>I</span>
  <span m='520600'>try</span> <span m='520780'>to</span> <span m='520900'>integrate</span>
  <span m='521950'>e</span> <span m='522970'>to</span> <span m='523090'>the</span>
  <span m='523240'>j</span> <span m='523659'>omega</span> <span m='523909'>not</span>
  <span m='524169'>t</span> <span m='525080'>e</span> <span m='525380'>to</span> <span
  m='525600'>the</span> <span m='525680'>minus</span> <span m='526020'>j</span> <span
  m='526290'>omega</span> <span m='526560'>t</span> <span m='526830'>dt?</span> <span
  m='527620'>What's</span> <span m='527860'>difficult</span> <span m='528250'>about</span>
  <span m='528490'>integrating</span> <span m='528910'>that</span> <span m='529040'>function?</span>
  </p><p><span m='535200'>What</span> <span m='535220'>do</span> <span m='535280'>we</span>
  <span m='535370'>do</span> <span m='535610'>when</span> <span m='535760'>we</span>
  <span m='535880'>see</span> <span m='536390'>these</span> <span m='537650'>sorts</span>
  <span m='537920'>of</span> <span m='537980'>things--</span> <span m='538460'>e</span>
  <span m='538755'>to the</span> <span m='539050'>j omega</span> <span m='539510'>not
  t?</span> <span m='539870'>How</span> <span m='540100'>do</span> <span m='540200'>you</span>
  <span m='540260'>think</span> <span m='540410'>about</span> <span m='540610'>e</span>
  <span m='540920'>to</span> <span m='541350'>the--</span> <span m='543050'>complex</span>
  <span m='543590'>exponential.</span> <span m='545680'>You</span> <span m='545740'>can</span>
  <span m='545860'>name</span> <span m='546070'>out</span> <span m='546670'>things</span>
  <span m='546850'>like</span> <span m='547090'>Euler's</span> <span m='547510'>equation,</span>
  <span m='548000'>right?</span> <span m='548710'>So</span> <span m='548830'>e to
  the</span> <span m='549130'>j</span> <span m='549330'>omega</span> <span m='549390'>not</span>
  <span m='549470'>t--</span> <span m='549820'>you</span> <span m='549910'>might</span>
  <span m='550060'>want</span> <span m='550210'>to</span> <span m='550270'>say,</span>
  <span m='550550'>well,</span> <span m='550570'>that's</span> <span m='550810'>the</span>
  <span m='550900'>same</span> <span m='551110'>thing</span> <span m='551320'>as</span>
  <span m='551440'>cosine</span> <span m='551920'>omega</span> <span m='552180'>not</span>
  <span m='552420'>t</span> <span m='553450'>plus</span> <span m='553720'>j</span>
  <span m='554050'>sine</span> <span m='554330'>omega</span> <span m='554560'>not</span>
  <span m='554750'>t.</span> </p><p><span m='560190'>If</span> <span m='560310'>I</span>
  <span m='560380'>took</span> <span m='560580'>just</span> <span m='560810'>the</span>
  <span m='560890'>first</span> <span m='561120'>term--</span> <span m='561380'>cosine</span>
  <span m='561620'>omega</span> <span m='561810'>not</span> <span m='562040'>t,</span>
  <span m='562550'>does</span> <span m='562640'>it have a</span> <span m='562915'>Laplace</span>
  <span m='563190'>transform?</span> <span m='566790'>Doesn't</span> <span m='567090'>have</span>
  <span m='567210'>a</span> <span m='567300'>Laplace</span> <span m='567620'>transform,</span>
  <span m='567950'>hmm.</span> <span m='568790'>How</span> <span m='569080'>about</span>
  <span m='569540'>a</span> <span m='569740'>Fourier</span> <span m='569870'>transform?</span>
  <span m='572810'>Why</span> <span m='573170'>does</span> <span m='573350'>it</span>
  <span m='573410'>have</span> <span m='573530'>a</span> <span m='573590'>Fourier</span>
  <span m='573890'>transform</span> <span m='574310'>and</span> <span m='574400'>not</span>
  <span m='574520'>a</span> <span m='574720'>Laplace</span> <span m='575020'>transform?</span>
  </p><p><span m='581320'>So</span> <span m='581700'>Laplace</span> <span m='581930'>transforms--</span>
  <span m='582920'>there's</span> <span m='583160'>only</span> <span m='583370'>a</span>
  <span m='583430'>Laplace</span> <span m='583760'>transform</span> <span m='584600'>if</span>
  <span m='584750'>there's</span> <span m='584890'>some</span> <span m='585320'>kind</span>
  <span m='585710'>of</span> <span m='585800'>a</span> <span m='585830'>multiplicative</span>
  <span m='587000'>kernel--</span> <span m='587600'>e</span> <span m='587930'>to</span>
  <span m='588200'>the</span> <span m='588500'>minus</span> <span m='589010'>st--</span>
  <span m='590760'>that</span> <span m='590900'>has</span> <span m='591080'>some</span>
  <span m='591260'>values</span> <span m='591890'>that</span> <span m='591980'>make</span>
  <span m='592160'>the</span> <span m='592340'>integral</span> <span m='592670'>converge.</span>
  <span m='594920'>There's</span> <span m='595250'>no</span> <span m='595490'>value</span>
  <span m='595820'>of</span> <span m='595940'>s</span> <span m='596630'>for</span>
  <span m='596810'>which</span> <span m='597220'>e to</span> <span m='597470'>the</span>
  <span m='597560'>j omega</span> <span m='597960'>not t</span> <span m='598340'>will</span>
  <span m='598490'>converge.</span> </p><p><span m='600380'>The</span> <span m='600500'>amplitude</span>
  <span m='601190'>of</span> <span m='601300'>e to the</span> <span m='601600'>j omega
  not</span> <span m='602000'>t--</span> <span m='603470'>the</span> <span m='603590'>real</span>
  <span m='603830'>part</span> <span m='604220'>has</span> <span m='604340'>an</span>
  <span m='604430'>amplitude</span> <span m='604820'>that</span> <span m='604940'>fluctuates</span>
  <span m='605390'>like</span> <span m='605540'>this</span> <span m='605750'>and</span>
  <span m='605870'>never</span> <span m='606200'>decays.</span> <span m='607700'>Goes</span>
  <span m='607910'>on</span> <span m='608060'>forever</span> <span m='608300'>and</span>
  <span m='608390'>ever in</span> <span m='608570'>both</span> <span m='608720'>directions.</span>
  <span m='609980'>There's</span> <span m='610190'>no</span> <span m='611090'>exponential</span>
  <span m='611660'>function</span> <span m='612050'>that</span> <span m='612140'>you</span>
  <span m='612230'>can</span> <span m='612320'>multiply</span> <span m='612980'>times</span>
  <span m='614020'>that</span> <span m='614210'>function</span> <span m='615440'>to</span>
  <span m='615530'>make</span> <span m='615680'>it</span> <span m='615770'>converge.</span>
  <span m='617510'>There</span> <span m='617630'>is</span> <span m='617730'>no</span>
  <span m='617840'>Laplace</span> <span m='618170'>transform.</span> <span m='620635'>Is
  there</span> <span m='621128'>a Fourier</span> <span m='621621'>transform?</span>
  <span m='622120'>Yeah.</span> </p><p><span m='623900'>What's</span> <span m='624200'>different?</span>
  <span m='624590'>What</span> <span m='624740'>makes</span> <span m='624980'>us</span>
  <span m='625430'>be</span> <span m='625700'>able</span> <span m='625880'>to</span>
  <span m='625940'>do</span> <span m='626100'>a</span> <span m='626150'>Fourier</span>
  <span m='626390'>transform</span> <span m='626780'>and</span> <span m='626870'>not</span>
  <span m='626990'>a</span> <span m='627060'>Laplace</span> <span m='627120'>transform?</span>
  <span m='630700'>Delta</span> <span m='631060'>functions.</span> <span m='633660'>We</span>
  <span m='633810'>never</span> <span m='634450'>write</span> <span m='634840'>a</span>
  <span m='635115'>Laplace</span> <span m='635390'>transform</span> <span m='635675'>with</span>
  <span m='635960'>a</span> <span m='636070'>delta</span> <span m='636390'>function,</span>
  <span m='636900'>ever.</span> <span m='637830'>If</span> <span m='637980'>you</span>
  <span m='638570'>write</span> <span m='638800'>on</span> <span m='638940'>your</span>
  <span m='639060'>exam</span> <span m='642390'>h of</span> <span m='642510'>s</span>
  <span m='644620'>is</span> <span m='644970'>some</span> <span m='645060'>function</span>
  <span m='645450'>of</span> <span m='645570'>delta</span> <span m='646000'>of</span>
  <span m='646320'>s,</span> <span m='647450'>that's</span> <span m='647880'>definitely</span>
  <span m='648390'>wrong,</span> <span m='649170'>right?</span> <span m='649390'>We</span>
  <span m='649530'>just</span> <span m='649680'>never</span> <span m='650100'>do</span>
  <span m='650310'>that.</span> </p><p><span m='653130'>We're</span> <span m='653310'>much</span>
  <span m='653580'>more</span> <span m='653970'>liberal</span> <span m='654360'>about</span>
  <span m='654600'>using</span> <span m='654930'>delta</span> <span m='655230'>functions</span>
  <span m='655800'>in</span> <span m='657120'>Fourier</span> <span m='657690'>transforms.</span>
  <span m='658320'>That's</span> <span m='658440'>one</span> <span m='658590'>of</span>
  <span m='658650'>the</span> <span m='658710'>reasons</span> <span m='659050'>they're</span>
  <span m='659730'>powerful.</span> <span m='662130'>And</span> <span m='663430'>one</span>
  <span m='663630'>of</span> <span m='663690'>the</span> <span m='663750'>ways</span>
  <span m='663990'>you</span> <span m='664080'>can</span> <span m='664230'>think</span>
  <span m='664410'>about</span> <span m='664650'>that</span> <span m='665280'>is</span>
  <span m='665550'>that</span> <span m='665970'>delta</span> <span m='666330'>functions</span>
  <span m='666660'>are</span> <span m='666750'>easy</span> <span m='667080'>to</span>
  <span m='667200'>integrate.</span> <span m='667930'>That's</span> <span m='668040'>not</span>
  <span m='668190'>quite</span> <span m='668460'>enough.</span> </p><p><span m='669580'>The</span>
  <span m='669680'>other</span> <span m='669750'>thing</span> <span m='669930'>that's</span>
  <span m='670050'>important</span> <span m='670380'>to</span> <span m='670470'>realize</span>
  <span m='670920'>is</span> <span m='671040'>that</span> <span m='671280'>we've</span>
  <span m='671520'>got</span> <span m='671670'>this</span> <span m='672330'>integral</span>
  <span m='672840'>here--</span> <span m='674580'>it's</span> <span m='674850'>either</span>
  <span m='675150'>going</span> <span m='675300'>to</span> <span m='675360'>be</span>
  <span m='675480'>zero</span> <span m='675825'>or</span> <span m='676170'>infinity.</span>
  <span m='678150'>There's</span> <span m='678300'>going</span> <span m='678420'>to</span>
  <span m='678480'>be</span> <span m='678570'>certain</span> <span m='679200'>values</span>
  <span m='679770'>of</span> <span m='679920'>omega</span> <span m='682270'>that</span>
  <span m='682480'>when</span> <span m='682660'>we</span> <span m='682750'>multiply</span>
  <span m='683290'>this</span> <span m='683470'>together,</span> <span m='683730'>we're
  going</span> <span m='683990'>to</span> <span m='684160'>get</span> <span m='684310'>something</span>
  <span m='684610'>that</span> <span m='684700'>goes</span> <span m='684910'>on</span>
  <span m='685090'>and</span> <span m='685180'>on</span> <span m='685360'>forever</span>
  <span m='685690'>and</span> <span m='685780'>ever</span> <span m='685980'>and</span>
  <span m='686070'>never</span> <span m='686230'>decays.</span> </p><p><span m='688180'>That's</span>
  <span m='688480'>going</span> <span m='688600'>to</span> <span m='688660'>give</span>
  <span m='688780'>us</span> <span m='688870'>infinity.</span> <span m='689530'>And</span>
  <span m='689650'>there's</span> <span m='689770'>going</span> <span m='689890'>to</span>
  <span m='689950'>be</span> <span m='690070'>other</span> <span m='690340'>values</span>
  <span m='692260'>that</span> <span m='692410'>the</span> <span m='692500'>long-term</span>
  <span m='692920'>integral's</span> <span m='693280'>going</span> <span m='693400'>to</span>
  <span m='693460'>go</span> <span m='693550'>to</span> <span m='693610'>zero.</span>
  <span m='695970'>And</span> <span m='696120'>that</span> <span m='696360'>information</span>
  <span m='696930'>is</span> <span m='696990'>summarized</span> <span m='699030'>by</span>
  <span m='699210'>the</span> <span m='699330'>impulses,</span> <span m='700540'>right?</span>
  </p><p><span m='701340'>So</span> <span m='701610'>if</span> <span m='701850'>we</span>
  <span m='701970'>choose</span> <span m='703070'>omega</span> <span m='703490'>not--</span>
  <span m='704310'>if</span> <span m='704460'>we</span> <span m='704550'>choose</span>
  <span m='704790'>omega</span> <span m='704840'>to</span> <span m='705160'>be</span>
  <span m='705380'>omega</span> <span m='705770'>not--</span> <span m='708220'>then</span>
  <span m='708580'>when</span> <span m='708730'>we</span> <span m='708850'>do</span>
  <span m='709000'>the</span> <span m='709150'>integral,</span> <span m='710060'>which</span>
  <span m='710140'>comes</span> <span m='710350'>out</span> <span m='710470'>a</span>
  <span m='710530'>function</span> <span m='710830'>of</span> <span m='710920'>omega,</span>
  <span m='711380'>we're</span> <span m='711940'>going</span> <span m='712060'>to</span>
  <span m='712150'>get</span> <span m='712450'>something that</span> <span m='712840'>goes</span>
  <span m='713050'>to</span> <span m='713140'>infinity.</span> <span m='716780'>OK?</span>
  </p><p><span m='718210'>The</span> <span m='718360'>easy</span> <span m='718690'>way</span>
  <span m='718840'>to</span> <span m='718960'>think</span> <span m='719140'>about</span>
  <span m='719350'>that</span> <span m='719560'>is</span> <span m='719650'>to</span>
  <span m='719770'>do</span> <span m='719860'>the</span> <span m='720040'>inverse</span>
  <span m='720370'>Fourier</span> <span m='720670'>transform,</span> <span m='722260'>right?</span>
  <span m='722950'>The</span> <span m='723100'>inverse</span> <span m='723430'>Fourier</span>
  <span m='723700'>transform</span> <span m='724360'>is</span> <span m='725440'>x</span>
  <span m='725820'>of</span> <span m='726110'>t</span> <span m='728660'>is</span>
  <span m='728820'>1</span> <span m='728990'>over</span> <span m='729170'>2</span>
  <span m='729400'>pi</span> <span m='730030'>in</span> <span m='730120'>the</span>
  <span m='730180'>integral</span> <span m='731020'>x</span> <span m='731350'>of</span>
  <span m='731774'>j</span> <span m='732198'>omega</span> <span m='733046'>e to the</span>
  <span m='733470'>j</span> <span m='733850'>omega</span> <span m='734150'>t</span>
  <span m='734440'>d</span> <span m='735190'>omega.</span> </p><p><span m='737500'>Now,</span>
  <span m='737710'>if</span> <span m='737800'>we</span> <span m='737920'>put</span>
  <span m='738160'>the</span> <span m='738280'>delta</span> <span m='738640'>function</span>
  <span m='739030'>in</span> <span m='739150'>this,</span> <span m='739510'>it's</span>
  <span m='739660'>easy.</span> <span m='742470'>Because</span> <span m='742800'>the</span>
  <span m='742890'>delta</span> <span m='743190'>function</span> <span m='743670'>over</span>
  <span m='743940'>here--</span> <span m='744900'>if</span> <span m='745020'>we</span>
  <span m='745140'>say</span> <span m='745350'>that--</span> <span m='747222'>it's</span>
  <span m='747630'>x</span> <span m='747930'>over</span> <span m='748140'>here</span>
  <span m='748290'>and</span> <span m='748380'>it's</span> <span m='748490'>h</span>
  <span m='748680'>over</span> <span m='748830'>there.</span> <span m='749040'>But</span>
  <span m='749150'>who</span> <span m='749320'>cares?</span> <span m='749580'>That</span>
  <span m='749670'>should</span> <span m='749820'>have</span> <span m='749910'>been</span>
  <span m='750020'>x.</span> </p><p><span m='758790'>If</span> <span m='759570'>we</span>
  <span m='759660'>put</span> <span m='759870'>over</span> <span m='760110'>there</span>
  <span m='760320'>that</span> <span m='760500'>the</span> <span m='760680'>x</span>
  <span m='760860'>of</span> <span m='760950'>j</span> <span m='761160'>omega</span>
  <span m='761550'>is</span> <span m='761760'>2</span> <span m='762120'>pi</span>
  <span m='762540'>delta</span> <span m='763020'>omega</span> <span m='763440'>minus</span>
  <span m='763740'>omega</span> <span m='764080'>not,</span> <span m='764700'>then</span>
  <span m='764850'>we</span> <span m='764940'>can</span> <span m='765090'>see</span>
  <span m='765300'>that</span> <span m='765570'>the</span> <span m='766050'>function</span>
  <span m='766440'>of</span> <span m='766500'>the</span> <span m='766620'>delta</span>
  <span m='766980'>is</span> <span m='767130'>just</span> <span m='767310'>to</span>
  <span m='767430'>sift</span> <span m='767730'>out</span> <span m='767940'>a</span>
  <span m='768000'>particular</span> <span m='768450'>value</span> <span m='768870'>of</span>
  <span m='768990'>e to</span> <span m='769200'>the</span> <span m='769320'>j</span>
  <span m='769530'>omega</span> <span m='769830'>t,</span> <span m='770880'>the</span>
  <span m='770970'>one</span> <span m='771330'>at</span> <span m='771570'>omega</span>
  <span m='771890'>not.</span> <span m='773490'>And</span> <span m='773670'>the</span>
  <span m='773760'>2</span> <span m='773910'>pi's</span> <span m='774210'>obvious,</span>
  <span m='774540'>too.</span> <span m='775860'>The</span> <span m='775950'>2</span>
  <span m='776130'>pi</span> <span m='776370'>came</span> <span m='776640'>from</span>
  <span m='776790'>the</span> <span m='776880'>1</span> <span m='777060'>over</span>
  <span m='777240'>2</span> <span m='777390'>pi,</span> <span m='777660'>right?</span>
  <span m='778110'>We</span> <span m='778230'>had</span> <span m='778350'>to</span>
  <span m='778410'>have</span> <span m='778530'>a</span> <span m='778580'>2</span>
  <span m='778710'>pi</span> <span m='778890'>out</span> <span m='779110'>front</span>
  <span m='779250'>so</span> <span m='779430'>that</span> <span m='779550'>the</span>
  <span m='779640'>1</span> <span m='779790'>over</span> <span m='779970'>2</span>
  <span m='780180'>pi</span> <span m='780330'>killed</span> <span m='780600'>it.</span>
  </p><p><span m='781620'>OK,</span> <span m='781930'>anyway--</span> <span m='782460'>so</span>
  <span m='782610'>the</span> <span m='782730'>idea,</span> <span m='783030'>then,</span>
  <span m='783330'>is</span> <span m='783630'>that</span> <span m='784140'>simply</span>
  <span m='784440'>by</span> <span m='784590'>taking</span> <span m='784920'>the</span>
  <span m='785010'>Fourier</span> <span m='785370'>transform</span> <span m='785880'>of</span>
  <span m='786000'>this,</span> <span m='786390'>we</span> <span m='786570'>can</span>
  <span m='786720'>get</span> <span m='786870'>an</span> <span m='786960'>expression</span>
  <span m='787530'>for</span> <span m='787740'>the</span> <span m='787830'>Fourier</span>
  <span m='788190'>transform.</span> <span m='789300'>And</span> <span m='789810'>that</span>
  <span m='790380'>tells</span> <span m='790770'>us</span> <span m='790860'>something</span>
  <span m='791190'>about</span> <span m='791430'>the</span> <span m='791520'>great</span>
  <span m='791730'>utility</span> <span m='792270'>of</span> <span m='792420'>using</span>
  <span m='792750'>impulses,</span> <span m='793710'>right?</span> </p><p><span m='794730'>Because</span>
  <span m='795180'>we</span> <span m='795300'>use</span> <span m='795540'>impulses</span>
  <span m='796020'>in</span> <span m='796120'>the</span> <span m='796210'>Fourier</span>
  <span m='796500'>transform,</span> <span m='796980'>we</span> <span m='797070'>can</span>
  <span m='797190'>represent</span> <span m='797640'>a</span> <span m='797730'>lot</span>
  <span m='798030'>more</span> <span m='798240'>signals</span> <span m='799080'>than</span>
  <span m='799230'>we</span> <span m='799320'>could</span> <span m='799470'>have</span>
  <span m='799560'>represented</span> <span m='800520'>in</span> <span m='800680'>the</span>
  <span m='800760'>Laplace</span> <span m='801150'>transform.</span> <span m='801810'>That's</span>
  <span m='801990'>one</span> <span m='802170'>of</span> <span m='802230'>the</span>
  <span m='802290'>utilities</span> <span m='802620'>of</span> <span m='802950'>a</span>
  <span m='803130'>Fourier.</span> <span m='805030'>And</span> <span m='805060'>there's</span>
  <span m='805170'>a</span> <span m='805230'>big</span> <span m='805410'>relationship</span>
  <span m='805920'>between</span> <span m='806220'>the</span> <span m='806290'>Fourier</span>
  <span m='806580'>series</span> <span m='806910'>and</span> <span m='807000'>the</span>
  <span m='807060'>Fourier</span> <span m='807660'>transform.</span> </p><p><span
  m='809980'>So</span> <span m='810250'>in</span> <span m='810360'>particular,</span>
  <span m='810940'>if</span> <span m='811040'>we</span> <span m='811140'>have</span>
  <span m='811240'>a</span> <span m='811340'>signal</span> <span m='811560'>that's</span>
  <span m='811740'>periodic</span> <span m='812160'>in</span> <span m='812250'>time,</span>
  <span m='813040'>it'll</span> <span m='813330'>have</span> <span m='813540'>both</span>
  <span m='813840'>a</span> <span m='813900'>series</span> <span m='814350'>and</span>
  <span m='814500'>a</span> <span m='814530'>transform.</span> <span m='816280'>The</span>
  <span m='816430'>transform</span> <span m='816840'>is</span> <span m='816920'>a</span>
  <span m='816950'>bunch</span> <span m='817170'>of</span> <span m='817260'>delta</span>
  <span m='817560'>functions</span> <span m='817950'>weighted</span> <span m='818250'>by</span>
  <span m='818430'>the</span> <span m='818580'>Fourier</span> <span m='819120'>series</span>
  <span m='819660'>coefficients</span> <span m='820940'>and</span> <span m='821130'>2</span>
  <span m='821310'>pi.</span> </p><p><span m='823110'>And</span> <span m='823200'>what</span>
  <span m='823320'>that</span> <span m='823500'>says</span> <span m='823860'>is,</span>
  <span m='825030'>had</span> <span m='825270'>we</span> <span m='825390'>been</span>
  <span m='825600'>willing</span> <span m='825900'>to</span> <span m='826020'>put</span>
  <span m='826210'>in</span> <span m='826380'>impulses</span> <span m='827790'>to</span>
  <span m='827940'>begin</span> <span m='828330'>with,</span> <span m='828600'>we</span>
  <span m='828690'>would</span> <span m='828810'>never</span> <span m='829080'>have</span>
  <span m='829230'>had</span> <span m='829440'>to</span> <span m='829590'>define</span>
  <span m='830160'>the</span> <span m='830250'>series.</span> <span m='831030'>We</span>
  <span m='831120'>did</span> <span m='831240'>the</span> <span m='831360'>series</span>
  <span m='831720'>just</span> <span m='831900'>because</span> <span m='832140'>it</span>
  <span m='832200'>was</span> <span m='832350'>easy.</span> <span m='833940'>Convergence</span>
  <span m='834510'>issues</span> <span m='834870'>were</span> <span m='834990'>more</span>
  <span m='835140'>clear.</span> </p><p><span m='837500'>But</span> <span m='838200'>if</span>
  <span m='838380'>we</span> <span m='838470'>had</span> <span m='838620'>been</span>
  <span m='838740'>willing</span> <span m='839100'>to</span> <span m='839190'>think</span>
  <span m='839370'>about</span> <span m='839820'>delta</span> <span m='840240'>functions</span>
  <span m='840690'>in</span> <span m='840810'>the</span> <span m='840900'>transforms--</span>
  <span m='841770'>which</span> <span m='841950'>would</span> <span m='842070'>have</span>
  <span m='842160'>been an</span> <span m='842460'>extremely</span> <span m='843060'>foreign</span>
  <span m='843600'>concept</span> <span m='845400'>coming</span> <span m='845730'>straight</span>
  <span m='845970'>from</span> <span m='846180'>Laplace,</span> <span m='846660'>where</span>
  <span m='846780'>you</span> <span m='846900'>would</span> <span m='846990'>never</span>
  <span m='847230'>see</span> <span m='847500'>that.</span> <span m='849090'>Had</span>
  <span m='849300'>we</span> <span m='849450'>been</span> <span m='849660'>willing</span>
  <span m='850020'>to</span> <span m='850170'>accept</span> <span m='850520'>delta</span>
  <span m='850770'>functions</span> <span m='851190'>in</span> <span m='851280'>the</span>
  <span m='851370'>transforms</span> <span m='851910'>from</span> <span m='852060'>the</span>
  <span m='852160'>outset,</span> <span m='852780'>we</span> <span m='852870'>never</span>
  <span m='853110'>would</span> <span m='853260'>have</span> <span m='853380'>needed</span>
  <span m='853620'>series.</span> </p><p><span m='854980'>So</span> <span m='855000'>the</span>
  <span m='855090'>relationship</span> <span m='855690'>between</span> <span m='856050'>series</span>
  <span m='856440'>and</span> <span m='856530'>transforms</span> <span m='857010'>has</span>
  <span m='857160'>to</span> <span m='857250'>do</span> <span m='857910'>with</span>
  <span m='858990'>the</span> <span m='859110'>fact</span> <span m='859440'>that</span>
  <span m='859620'>the</span> <span m='860460'>series</span> <span m='860970'>represents</span>
  <span m='861510'>periodic</span> <span m='862080'>signals.</span> <span m='862440'>Periodic</span>
  <span m='862920'>signals</span> <span m='863250'>go</span> <span m='863400'>on</span>
  <span m='863550'>forever.</span> <span m='865500'>There's</span> <span m='865710'>never</span>
  <span m='866220'>a</span> <span m='866280'>Laplace</span> <span m='866640'>transform,</span>
  <span m='869160'>and</span> <span m='869310'>that</span> <span m='869430'>means</span>
  <span m='869730'>that--</span> <span m='870210'>there's</span> <span m='870420'>never</span>
  <span m='870900'>a</span> <span m='870930'>Laplace</span> <span m='871170'>transform.</span>
  <span m='871830'>That</span> <span m='871950'>means</span> <span m='872130'>the</span>
  <span m='872220'>Fourier</span> <span m='872550'>transform</span> <span m='872970'>has</span>
  <span m='873110'>a</span> <span m='873170'>bunch</span> <span m='873300'>of</span>
  <span m='873360'>delta</span> <span m='873600'>functions</span> <span m='874020'>in</span>
  <span m='874140'>it,</span> <span m='875970'>OK?</span> </p><p><span m='878600'>OK,</span>
  <span m='878810'>so</span> <span m='878960'>what</span> <span m='879110'>I</span>
  <span m='879170'>want</span> <span m='879320'>to</span> <span m='879380'>do,</span>
  <span m='879560'>then,</span> <span m='880100'>is</span> <span m='880340'>think</span>
  <span m='880550'>through</span> <span m='880910'>other</span> <span m='881180'>relationships</span>
  <span m='881840'>that</span> <span m='881930'>are</span> <span m='882020'>on</span>
  <span m='882140'>this</span> <span m='882290'>table.</span> <span m='883280'>And</span>
  <span m='883370'>in</span> <span m='883490'>particular,</span> <span m='883880'>I</span>
  <span m='883940'>want</span> <span m='884090'>to</span> <span m='884150'>think</span>
  <span m='884300'>about</span> <span m='884510'>them</span> <span m='885020'>by</span>
  <span m='885140'>thinking</span> <span m='885380'>about</span> <span m='885560'>the</span>
  <span m='885680'>underlying</span> <span m='886070'>structure</span> <span m='886430'>of</span>
  <span m='886490'>the</span> <span m='886580'>signals.</span> </p><p><span m='888780'>So</span>
  <span m='891520'>think</span> <span m='891670'>about</span> <span m='891880'>having</span>
  <span m='894510'>DTFS,</span> <span m='897588'>DTFT,</span> <span m='901080'>CTFS,</span>
  <span m='903520'>and</span> <span m='903790'>CTFT.</span> <span m='905890'>So</span>
  <span m='906010'>what</span> <span m='906130'>I</span> <span m='906190'>want</span>
  <span m='906310'>to</span> <span m='906370'>do</span> <span m='906490'>is</span>
  <span m='906580'>think</span> <span m='906730'>about</span> <span m='906880'>the</span>
  <span m='906940'>relationships</span> <span m='908470'>among</span> <span m='908770'>those</span>
  <span m='908950'>four</span> <span m='909130'>transforms</span> <span m='911500'>by</span>
  <span m='911680'>thinking</span> <span m='912100'>about</span> <span m='912460'>how</span>
  <span m='912640'>they</span> <span m='912820'>differ</span> <span m='913150'>in</span>
  <span m='913270'>time,</span> <span m='914560'>right?</span> <span m='915300'>So</span>
  <span m='917330'>the</span> <span m='917470'>top</span> <span m='917710'>guys</span>
  <span m='917980'>are</span> <span m='918040'>discrete</span> <span m='918430'>in</span>
  <span m='918520'>time.</span> <span m='918790'>The</span> <span m='918850'>bottom</span>
  <span m='919120'>guys</span> <span m='919330'>are</span> <span m='919570'>continuous</span>
  <span m='920080'>in</span> <span m='920170'>time.</span> <span m='920590'>The</span>
  <span m='920740'>left</span> <span m='920980'>guys</span> <span m='921640'>are</span>
  <span m='922840'>periodic</span> <span m='923710'>in</span> <span m='923860'>time.</span>
  <span m='924670'>The</span> <span m='924760'>right</span> <span m='924940'>ones</span>
  <span m='925150'>are aperiodic</span> <span m='926290'>in</span> <span m='926440'>time.</span>
  </p><p><span m='926830'>So</span> <span m='926950'>what</span> <span m='927100'>I</span>
  <span m='927160'>want</span> <span m='927310'>to</span> <span m='927400'>do</span>
  <span m='927790'>to</span> <span m='927910'>think</span> <span m='928090'>about</span>
  <span m='928300'>how</span> <span m='928480'>they</span> <span m='928600'>relate</span>
  <span m='928900'>to</span> <span m='928960'>each</span> <span m='929200'>other,</span>
  <span m='929740'>is</span> <span m='929890'>think</span> <span m='930100'>about</span>
  <span m='930310'>a</span> <span m='930370'>base</span> <span m='930730'>case.</span>
  <span m='932650'>Think</span> <span m='932830'>about</span> <span m='933070'>a</span>
  <span m='933130'>signal</span> <span m='933460'>that's</span> <span m='933640'>down</span>
  <span m='933940'>here--</span> <span m='934300'>aperiodic</span> <span m='935000'>CT.</span>
  <span m='937310'>And</span> <span m='937460'>think</span> <span m='937670'>about</span>
  <span m='937910'>what</span> <span m='938060'>you</span> <span m='938180'>would</span>
  <span m='938270'>have</span> <span m='938390'>to</span> <span m='938480'>do</span>
  <span m='938600'>to</span> <span m='938690'>the</span> <span m='938810'>signal,</span>
  <span m='939260'>and</span> <span m='939440'>therefore</span> <span m='939920'>what</span>
  <span m='940070'>would</span> <span m='940220'>you</span> <span m='940280'>have</span>
  <span m='940430'>to</span> <span m='940520'>do</span> <span m='940610'>to the</span>
  <span m='940760'>transform.</span> </p><p><span m='943540'>If</span> <span m='943690'>you</span>
  <span m='943780'>wanted</span> <span m='943990'>to</span> <span m='944110'>move</span>
  <span m='944620'>this</span> <span m='944890'>way--</span> <span m='945370'>I'll</span>
  <span m='945490'>do</span> <span m='945610'>that</span> <span m='945790'>one</span>
  <span m='945910'>first.</span> <span m='948470'>If</span> <span m='948620'>you</span>
  <span m='948710'>move</span> <span m='949100'>up--</span> <span m='950090'>I'll</span>
  <span m='950210'>do</span> <span m='950360'>that</span> <span m='950510'>one</span>
  <span m='950660'>second.</span> <span m='952430'>Or</span> <span m='952610'>if</span>
  <span m='952730'>you</span> <span m='952820'>move</span> <span m='953060'>that</span>
  <span m='953330'>way--</span> <span m='953810'>I'll</span> <span m='953900'>do</span>
  <span m='954020'>that</span> <span m='954200'>one</span> <span m='954500'>third.</span>
  <span m='955070'>So</span> <span m='955220'>really,</span> <span m='955490'>the</span>
  <span m='955580'>rest</span> <span m='955730'>of</span> <span m='955790'>the</span>
  <span m='955880'>hour</span> <span m='956090'>is</span> <span m='956180'>just</span>
  <span m='956330'>doing</span> <span m='956540'>three</span> <span m='956780'>examples.</span>
  <span m='958150'>Well,</span> <span m='958290'>four</span> <span m='958490'>examples.</span>
  </p><p><span m='960320'>What's</span> <span m='960650'>the</span> <span m='960930'>transform</span>
  <span m='961380'>of</span> <span m='961520'>a</span> <span m='961580'>base</span>
  <span m='961880'>case?</span> <span m='963290'>Then</span> <span m='963590'>what</span>
  <span m='963740'>would</span> <span m='963890'>happen</span> <span m='964250'>as</span>
  <span m='964370'>I</span> <span m='964460'>move</span> <span m='964640'>through</span>
  <span m='964850'>this</span> <span m='965030'>table?</span> <span m='966730'>OK,</span>
  <span m='967100'>everybody's</span> <span m='967490'>with</span> <span m='967620'>the</span>
  <span m='967670'>game</span> <span m='967880'>plan?</span> </p><p><span m='969530'>So</span>
  <span m='969740'>here's</span> <span m='969920'>my</span> <span m='970040'>base</span>
  <span m='970310'>case.</span> <span m='971480'>I</span> <span m='971540'>want</span>
  <span m='971720'>to</span> <span m='971780'>think</span> <span m='971900'>about</span>
  <span m='972050'>the</span> <span m='972110'>Fourier</span> <span m='972380'>transform</span>
  <span m='972830'>of</span> <span m='972920'>a</span> <span m='972950'>signal,</span>
  <span m='973250'>x</span> <span m='973460'>of</span> <span m='973580'>t,</span>
  <span m='973840'>that's a</span> <span m='974030'>triangle.</span> <span m='976760'>We</span>
  <span m='976880'>could</span> <span m='976990'>calculate</span> <span m='977390'>the</span>
  <span m='977450'>Fourier</span> <span m='977810'>transform</span> <span m='978470'>just</span>
  <span m='978710'>from</span> <span m='978860'>the</span> <span m='978950'>definition.</span>
  <span m='979490'>That's</span> <span m='979670'>trivial,</span> <span m='980090'>right?</span>
  </p><p><span m='981730'>Good</span> <span m='981890'>way,</span> <span m='982160'>bad</span>
  <span m='982370'>way.</span> <span m='983360'>Good</span> <span m='983670'>way.</span>
  <span m='987860'>Smile.</span> <span m='989780'>Better.</span> <span m='990320'>OK,</span>
  <span m='991550'>bad</span> <span m='991850'>way--</span> <span m='993140'>I</span>
  <span m='993230'>can</span> <span m='993380'>think</span> <span m='993530'>of</span>
  <span m='993620'>a</span> <span m='993680'>better</span> <span m='993890'>way</span>
  <span m='994010'>to</span> <span m='994100'>do</span> <span m='994250'>it.</span>
  <span m='995880'>What's</span> <span m='995960'>a</span> <span m='995990'>better</span>
  <span m='996170'>way</span> <span m='996290'>to</span> <span m='996350'>do</span>
  <span m='996470'>it?</span> <span m='1000560'>Yeah?</span> </p><p><span m='1001060'>AUDIENCE:</span>
  <span m='1001310'>[INAUDIBLE].</span> </p><p><span m='1020560'>DENNIS FREEMAN:</span>
  <span m='1020600'>So</span> <span m='1020640'>one</span> <span m='1020790'>way</span>
  <span m='1020970'>is</span> <span m='1021090'>to</span> <span m='1021210'>think</span>
  <span m='1021420'>about</span> <span m='1022200'>turning</span> <span m='1022620'>straight</span>
  <span m='1023070'>lines</span> <span m='1024119'>into</span> <span m='1024569'>constants</span>
  <span m='1025680'>via</span> <span m='1026130'>derivatives</span> <span m='1026730'>and</span>
  <span m='1026819'>integrals</span> <span m='1027240'>and</span> <span m='1027329'>stuff</span>
  <span m='1027540'>like</span> <span m='1027690'>that.</span> <span m='1028030'>That's</span>
  <span m='1028079'>a</span> <span m='1028109'>very</span> <span m='1028230'>good</span>
  <span m='1028380'>way.</span> <span m='1028740'>Can</span> <span m='1028890'>somebody</span>
  <span m='1029160'>think</span> <span m='1029280'>of</span> <span m='1029339'>a</span>
  <span m='1029400'>different</span> <span m='1029640'>way?</span> <span m='1031020'>That'll</span>
  <span m='1031240'>work,</span> <span m='1031520'>it'll</span> <span m='1031849'>be
  fine.</span> <span m='1032160'>Yes?</span> </p><p><span m='1032400'>AUDIENCE:</span>
  <span m='1032837'>Is that</span> <span m='1033274'>the convolution</span> <span
  m='1033711'>of two</span> <span m='1034148'>square</span> <span m='1034585'>pulses?</span>
  </p><p><span m='1035460'>DENNIS FREEMAN:</span> <span m='1035632'>Convolution</span>
  <span m='1036150'>of</span> <span m='1036240'>two</span> <span m='1036390'>square</span>
  <span m='1036630'>pulses,</span> <span m='1037069'>that's</span> <span m='1037230'>wonderful.</span>
  <span m='1038880'>So</span> <span m='1039359'>a</span> <span m='1039710'>different</span>
  <span m='1040050'>way</span> <span m='1040230'>we</span> <span m='1040380'>can</span>
  <span m='1040530'>do</span> <span m='1040710'>it</span> <span m='1041609'>is</span>
  <span m='1041940'>to</span> <span m='1042210'>convolve</span> <span m='1042960'>a</span>
  <span m='1043020'>square</span> <span m='1043260'>pulse</span> <span m='1043530'>with</span>
  <span m='1043680'>a</span> <span m='1043859'>square</span> <span m='1044160'>pulse.</span>
  <span m='1044510'>That's</span> <span m='1044760'>particularly</span> <span m='1045329'>good</span>
  <span m='1045480'>for</span> <span m='1045599'>this</span> <span m='1045780'>example,</span>
  <span m='1046560'>because</span> <span m='1046880'>a</span> <span m='1046920'>square</span>
  <span m='1047190'>pulse</span> <span m='1047460'>is</span> <span m='1047550'>one</span>
  <span m='1047700'>of</span> <span m='1047790'>our</span> <span m='1047849'>canonical</span>
  <span m='1048270'>forms.</span> </p><p><span m='1050960'>So</span> <span m='1051310'>if</span>
  <span m='1051460'>we</span> <span m='1051580'>think</span> <span m='1051730'>about</span>
  <span m='1051940'>what's</span> <span m='1052180'>the</span> <span m='1052270'>Fourier</span>
  <span m='1052510'>transform</span> <span m='1052860'>of a</span> <span m='1053020'>square</span>
  <span m='1053260'>pulse?</span> <span m='1053590'>We</span> <span m='1053710'>all</span>
  <span m='1053800'>know</span> <span m='1054040'>that</span> <span m='1054190'>it's</span>
  <span m='1054290'>something</span> <span m='1054670'>that</span> <span m='1054790'>has</span>
  <span m='1055000'>the</span> <span m='1055120'>form</span> <span m='1055940'>sine</span>
  <span m='1056200'>omega</span> <span m='1056470'>over</span> <span m='1056730'>omega.</span>
  <span m='1058030'>So</span> <span m='1058150'>all</span> <span m='1058270'>we</span>
  <span m='1058450'>really</span> <span m='1058720'>need</span> <span m='1058900'>to</span>
  <span m='1059020'>do</span> <span m='1059200'>is</span> <span m='1059350'>fill</span>
  <span m='1059500'>in</span> <span m='1059590'>the</span> <span m='1059680'>constants.</span>
  </p><p><span m='1061660'>Filling</span> <span m='1061930'>in</span> <span m='1062020'>the</span>
  <span m='1062110'>constants</span> <span m='1062360'>is</span> <span m='1062710'>easy,</span>
  <span m='1063040'>because</span> <span m='1063340'>we</span> <span m='1063460'>know</span>
  <span m='1063610'>the</span> <span m='1063700'>moment</span> <span m='1064000'>theorems.</span>
  <span m='1065410'>The</span> <span m='1065500'>moment</span> <span m='1065800'>theorem</span>
  <span m='1066130'>says</span> <span m='1066460'>that</span> <span m='1066730'>whatever</span>
  <span m='1067060'>the</span> <span m='1067240'>area</span> <span m='1067660'>is</span>
  <span m='1067960'>under</span> <span m='1068140'>this</span> <span m='1068350'>curve,</span>
  <span m='1069370'>it</span> <span m='1069490'>has</span> <span m='1069670'>to</span>
  <span m='1069790'>be</span> <span m='1069910'>the</span> <span m='1070030'>height</span>
  <span m='1070270'>of</span> <span m='1070330'>that</span> <span m='1070480'>curve</span>
  <span m='1073300'>at</span> <span m='1073560'>0.</span> <span m='1074810'>Whatever</span>
  <span m='1075170'>is</span> <span m='1075320'>the</span> <span m='1075470'>area</span>
  <span m='1075890'>under</span> <span m='1076130'>this</span> <span m='1076310'>curve,</span>
  <span m='1076640'>it</span> <span m='1076700'>has</span> <span m='1076880'>to</span>
  <span m='1076970'>be</span> <span m='1077090'>the</span> <span m='1077210'>height</span>
  <span m='1077420'>of</span> <span m='1077510'>that</span> <span m='1077690'>one.</span>
  <span m='1077900'>Except</span> <span m='1078200'>that</span> <span m='1078290'>you</span>
  <span m='1078350'>have</span> <span m='1078470'>to</span> <span m='1078560'>divide</span>
  <span m='1078770'>by</span> <span m='1078890'>2</span> <span m='1079040'>pi,</span>
  <span m='1079250'>because</span> <span m='1079520'>the</span> <span m='1079640'>annoying</span>
  <span m='1079910'>2</span> <span m='1080030'>pi</span> <span m='1080210'>factor.</span>
  </p><p><span m='1082260'>The</span> <span m='1082460'>annoying</span> <span m='1082760'>2</span>
  <span m='1083360'>pi</span> <span m='1083600'>factor</span> <span m='1084020'>is</span>
  <span m='1084590'>something</span> <span m='1084950'>that's</span> <span m='1085150'>in</span>
  <span m='1085340'>the</span> <span m='1085520'>inverse</span> <span m='1085910'>transform</span>
  <span m='1086420'>and</span> <span m='1086510'>not</span> <span m='1086690'>in</span>
  <span m='1086780'>the</span> <span m='1086870'>Fourier</span> <span m='1087200'>transform.</span>
  <span m='1087800'>That</span> <span m='1087950'>makes</span> <span m='1088190'>it</span>
  <span m='1088310'>asymmetric.</span> <span m='1090830'>So</span> <span m='1092450'>in</span>
  <span m='1092690'>order</span> <span m='1092930'>to</span> <span m='1093020'>choose</span>
  <span m='1093290'>the</span> <span m='1093380'>constants--</span> <span m='1094070'>the</span>
  <span m='1094220'>area</span> <span m='1094520'>under</span> <span m='1094730'>this</span>
  <span m='1094910'>is</span> <span m='1095030'>1,</span> <span m='1095720'>so</span>
  <span m='1096920'>that</span> <span m='1097100'>height</span> <span m='1097310'>must</span>
  <span m='1097520'>be</span> <span m='1097670'>1.</span> </p><p><span m='1099610'>The</span>
  <span m='1099790'>area</span> <span m='1100150'>under</span> <span m='1100420'>this,</span>
  <span m='1100810'>by</span> <span m='1101020'>magic,</span> <span m='1101440'>turns</span>
  <span m='1101740'>into</span> <span m='1101920'>the</span> <span m='1102100'>area</span>
  <span m='1102400'>of</span> <span m='1102520'>that</span> <span m='1102700'>triangle,</span>
  <span m='1103640'>which</span> <span m='1103750'>is</span> <span m='1103840'>2</span>
  <span m='1104030'>pi.</span> <span m='1104980'>Divide</span> <span m='1105280'>by</span>
  <span m='1105400'>2</span> <span m='1105580'>pi</span> <span m='1105790'>is</span>
  <span m='1105940'>1.</span> <span m='1106750'>So</span> <span m='1106930'>that</span>
  <span m='1107080'>means</span> <span m='1107440'>that</span> <span m='1107830'>this</span>
  <span m='1108130'>frequency</span> <span m='1108670'>must</span> <span m='1108880'>be</span>
  <span m='1109000'>2</span> <span m='1109210'>pi</span> <span m='1109480'>in</span>
  <span m='1109600'>order</span> <span m='1109810'>to</span> <span m='1109930'>make</span>
  <span m='1110110'>that</span> <span m='1110260'>constant</span> <span m='1110680'>be</span>
  <span m='1110830'>1.</span> <span m='1112900'>So</span> <span m='1113020'>we're</span>
  <span m='1113130'>done.</span> </p><p><span m='1114160'>So</span> <span m='1114730'>we</span>
  <span m='1114940'>know,</span> <span m='1115240'>then,</span> <span m='1115570'>that</span>
  <span m='1115750'>the</span> <span m='1115970'>transform</span> <span m='1117080'>of</span>
  <span m='1117450'>this</span> <span m='1117790'>signal,</span> <span m='1118250'>which</span>
  <span m='1118360'>is</span> <span m='1118450'>the</span> <span m='1118490'>convolution</span>
  <span m='1119230'>of</span> <span m='1119410'>this</span> <span m='1119610'>signal</span>
  <span m='1119920'>with</span> <span m='1120110'>itself,</span> <span m='1122400'>is</span>
  <span m='1123120'>just</span> <span m='1123450'>the</span> <span m='1123720'>product</span>
  <span m='1124380'>of</span> <span m='1124560'>this</span> <span m='1124830'>function</span>
  <span m='1125220'>with</span> <span m='1125400'>itself.</span> <span m='1126570'>Convolution</span>
  <span m='1127170'>in</span> <span m='1127290'>time</span> <span m='1127800'>maps</span>
  <span m='1128130'>to</span> <span m='1128280'>multiplication</span> <span m='1129000'>in</span>
  <span m='1129120'>frequency.</span> <span m='1130830'>OK?</span> </p><p><span m='1132560'>So</span>
  <span m='1132680'>that's</span> <span m='1132890'>the</span> <span m='1133010'>base</span>
  <span m='1133250'>case.</span> <span m='1133550'>Now</span> <span m='1133700'>what</span>
  <span m='1133910'>I</span> <span m='1133970'>want</span> <span m='1134120'>to</span>
  <span m='1134180'>think</span> <span m='1134390'>about</span> <span m='1135110'>is</span>
  <span m='1135260'>how</span> <span m='1135500'>I</span> <span m='1135620'>would</span>
  <span m='1136040'>march</span> <span m='1136370'>through</span> <span m='1136520'>the</span>
  <span m='1136640'>table.</span> <span m='1137000'>That's</span> <span m='1137180'>my</span>
  <span m='1137330'>case</span> <span m='1137630'>down</span> <span m='1137900'>here.</span>
  <span m='1138930'>So</span> <span m='1138950'>what</span> <span m='1139040'>I</span>
  <span m='1139100'>want</span> <span m='1139250'>to</span> <span m='1139310'>do</span>
  <span m='1139460'>first</span> <span m='1139880'>is</span> <span m='1140000'>think</span>
  <span m='1140150'>about,</span> <span m='1140330'>how</span> <span m='1140510'>would</span>
  <span m='1140660'>I</span> <span m='1141470'>convert</span> <span m='1141920'>that</span>
  <span m='1142190'>this</span> <span m='1142400'>way?</span> <span m='1143180'>And</span>
  <span m='1143270'>what's</span> <span m='1143450'>the</span> <span m='1143540'>implication</span>
  <span m='1144150'>for</span> <span m='1144710'>that</span> <span m='1144950'>conversion</span>
  <span m='1145430'>in</span> <span m='1145520'>terms</span> <span m='1145730'>of</span>
  <span m='1145820'>time,</span> <span m='1148010'>and</span> <span m='1148160'>in</span>
  <span m='1148250'>terms</span> <span m='1148520'>of</span> <span m='1148610'>frequency?</span>
  </p><p><span m='1151260'>So</span> <span m='1151730'>one</span> <span m='1152030'>way</span>
  <span m='1152180'>to</span> <span m='1152270'>think</span> <span m='1152480'>about</span>
  <span m='1152810'>the</span> <span m='1152930'>transformation</span> <span m='1153590'>from</span>
  <span m='1153770'>a</span> <span m='1153860'>transform</span> <span m='1154520'>to</span>
  <span m='1154640'>a</span> <span m='1154700'>series--</span> <span m='1155690'>you</span>
  <span m='1155780'>can</span> <span m='1155900'>only</span> <span m='1156210'>series</span>
  <span m='1156620'>with</span> <span m='1156710'>things</span> <span m='1156950'>that</span>
  <span m='1157040'>are</span> <span m='1157100'>periodic.</span> <span m='1158090'>The</span>
  <span m='1158180'>transformation</span> <span m='1158840'>that</span> <span m='1158930'>we</span>
  <span m='1159020'>talked</span> <span m='1159260'>about</span> <span m='1159440'>in</span>
  <span m='1159560'>class</span> <span m='1159890'>was</span> <span m='1160250'>periodic</span>
  <span m='1160790'>extension.</span> </p><p><span m='1162170'>So</span> <span m='1162350'>you</span>
  <span m='1162500'>think</span> <span m='1162740'>about</span> <span m='1163040'>taking</span>
  <span m='1163460'>the</span> <span m='1163580'>base</span> <span m='1163820'>case,</span>
  <span m='1164150'>which</span> <span m='1164300'>was</span> <span m='1164450'>a</span>
  <span m='1165020'>single</span> <span m='1165500'>triangle</span> <span m='1165710'>wave,</span>
  <span m='1166820'>and</span> <span m='1166940'>turning it</span> <span m='1167250'>into</span>
  <span m='1167540'>a</span> <span m='1167600'>sequence</span> <span m='1168020'>of</span>
  <span m='1168140'>triangle</span> <span m='1168590'>waves.</span> <span m='1169670'>There's</span>
  <span m='1169850'>lots</span> <span m='1170090'>of</span> <span m='1170150'>ways</span>
  <span m='1170390'>to</span> <span m='1170510'>think</span> <span m='1170690'>about</span>
  <span m='1171020'>that.</span> <span m='1171800'>But</span> <span m='1171950'>the</span>
  <span m='1172040'>way</span> <span m='1172220'>I</span> <span m='1172310'>want</span>
  <span m='1172460'>to</span> <span m='1172550'>motivate</span> <span m='1173060'>is</span>
  <span m='1173240'>to</span> <span m='1173360'>think</span> <span m='1173540'>about</span>
  <span m='1173840'>it--</span> <span m='1174870'>well,</span> <span m='1175250'>no,</span>
  <span m='1175910'>backing</span> <span m='1176270'>up.</span> </p><p><span m='1177260'>So</span>
  <span m='1178010'>if</span> <span m='1178250'>we</span> <span m='1178430'>think</span>
  <span m='1178730'>about</span> <span m='1178970'>the</span> <span m='1179060'>triangle</span>
  <span m='1179480'>wave</span> <span m='1179810'>and</span> <span m='1179930'>transformation</span>
  <span m='1180530'>and</span> <span m='1180620'>make</span> <span m='1180830'>it</span>
  <span m='1180890'>into</span> <span m='1181100'>a</span> <span m='1181160'>periodic</span>
  <span m='1181640'>triangle</span> <span m='1182000'>wave,</span> <span m='1182300'>we</span>
  <span m='1182420'>could</span> <span m='1182630'>just</span> <span m='1182840'>substitute</span>
  <span m='1183470'>this</span> <span m='1183770'>into</span> <span m='1183980'>the</span>
  <span m='1184070'>definition</span> <span m='1184550'>of</span> <span m='1184640'>transform.</span>
  <span m='1185660'>That's</span> <span m='1185990'>ugly,</span> <span m='1186440'>why?</span>
  <span m='1192510'>For</span> <span m='1192690'>the</span> <span m='1192780'>same</span>
  <span m='1193020'>reason</span> <span m='1193530'>that</span> <span m='1193770'>one</span>
  <span m='1193920'>was</span> <span m='1194100'>ugly.</span> <span m='1195270'>What's</span>
  <span m='1195450'>ugly</span> <span m='1195720'>about</span> <span m='1195970'>this?</span>
  <span m='1199630'>The</span> <span m='1199760'>signal</span> <span m='1200060'>goes</span>
  <span m='1200270'>on</span> <span m='1200510'>and</span> <span m='1200600'>on</span>
  <span m='1200870'>and</span> <span m='1200990'>on</span> <span m='1201230'>and</span>
  <span m='1201350'>on</span> <span m='1201560'>and</span> <span m='1201680'>on.</span>
  </p><p><span m='1202980'>There</span> <span m='1203030'>will</span> <span m='1203150'>be</span>
  <span m='1203270'>certain</span> <span m='1203630'>frequencies</span> <span m='1204290'>where</span>
  <span m='1204530'>it'll</span> <span m='1204830'>blow</span> <span m='1205190'>up.</span>
  <span m='1206330'>Those</span> <span m='1206570'>will</span> <span m='1206720'>be</span>
  <span m='1207050'>infinity.</span> <span m='1208160'>There</span> <span m='1208280'>will</span>
  <span m='1208370'>be</span> <span m='1208580'>other</span> <span m='1208820'>frequencies</span>
  <span m='1209360'>where</span> <span m='1209570'>it</span> <span m='1209720'>is</span>
  <span m='1209780'>0.</span> <span m='1211190'>There</span> <span m='1211370'>could</span>
  <span m='1211640'>be</span> <span m='1211760'>frequencies</span> <span m='1212300'>where</span>
  <span m='1212450'>it's</span> <span m='1212600'>minus</span> <span m='1212990'>infinity,</span>
  <span m='1213470'>and</span> <span m='1213560'>those</span> <span m='1213740'>are</span>
  <span m='1213830'>the</span> <span m='1213950'>only</span> <span m='1214130'>three</span>
  <span m='1214310'>options.</span> </p><p><span m='1217130'>Since</span> <span m='1217400'>it</span>
  <span m='1217460'>goes</span> <span m='1217700'>on</span> <span m='1217880'>and</span>
  <span m='1217970'>on</span> <span m='1218120'>and</span> <span m='1218210'>on</span>
  <span m='1218390'>and</span> <span m='1218480'>on,</span> <span m='1218630'>if it's</span>
  <span m='1218810'>anything</span> <span m='1219110'>different</span> <span m='1219380'>from</span>
  <span m='1219530'>0,</span> <span m='1219890'>it</span> <span m='1219980'>has</span>
  <span m='1220130'>to</span> <span m='1220220'>be</span> <span m='1220310'>either</span>
  <span m='1220580'>infinity</span> <span m='1220970'>or</span> <span m='1221060'>minus</span>
  <span m='1221240'>infinity.</span> <span m='1224260'>It's</span> <span m='1224410'>going</span>
  <span m='1224530'>to</span> <span m='1224590'>be</span> <span m='1224680'>a</span>
  <span m='1224740'>train</span> <span m='1225040'>of</span> <span m='1225100'>impulses</span>
  <span m='1225670'>for</span> <span m='1225760'>the</span> <span m='1225850'>same</span>
  <span m='1226090'>reason</span> <span m='1226390'>that</span> <span m='1226510'>thing</span>
  <span m='1227050'>was</span> <span m='1227200'>some</span> <span m='1227350'>kind</span>
  <span m='1227530'>of</span> <span m='1227620'>a</span> <span m='1227650'>train</span>
  <span m='1227890'>of</span> <span m='1227950'>impulses.</span> <span m='1228670'>So</span>
  <span m='1228820'>we</span> <span m='1228880'>want</span> <span m='1229060'>to</span>
  <span m='1229120'>have</span> <span m='1229300'>a</span> <span m='1229360'>good</span>
  <span m='1229540'>way</span> <span m='1229690'>of</span> <span m='1229780'>thinking</span>
  <span m='1230110'>about</span> <span m='1230350'>it.</span> </p><p><span m='1230440'>I</span>
  <span m='1230500'>told</span> <span m='1230740'>you</span> <span m='1230890'>one</span>
  <span m='1231160'>way</span> <span m='1231340'>to</span> <span m='1231430'>think</span>
  <span m='1231640'>about</span> <span m='1232000'>this--</span> <span m='1232900'>by</span>
  <span m='1233110'>taking</span> <span m='1233470'>the</span> <span m='1233650'>inverse</span>
  <span m='1234010'>transform.</span> <span m='1234650'>This</span> <span m='1234700'>is</span>
  <span m='1234820'>a</span> <span m='1234880'>little</span> <span m='1235240'>harder</span>
  <span m='1236200'>to</span> <span m='1236350'>guess</span> <span m='1239930'>the</span>
  <span m='1239990'>transforms,</span> <span m='1240440'>so</span> <span m='1240530'>you</span>
  <span m='1240680'>can</span> <span m='1240800'>verify it</span> <span m='1241170'>with</span>
  <span m='1241430'>the inverse.</span> <span m='1244040'>But</span> <span m='1244250'>you</span>
  <span m='1244340'>can</span> <span m='1244490'>form</span> <span m='1245000'>this</span>
  <span m='1246350'>by</span> <span m='1246530'>thinking</span> <span m='1246950'>about</span>
  <span m='1247840'>convolving</span> <span m='1248810'>the</span> <span m='1248950'>base</span>
  <span m='1249260'>waveform</span> <span m='1251780'>with</span> <span m='1252290'>an</span>
  <span m='1252410'>impulse</span> <span m='1252740'>train.</span> </p><p><span m='1255350'>So</span>
  <span m='1255530'>what</span> <span m='1255740'>if</span> <span m='1255860'>I</span>
  <span m='1255980'>had</span> <span m='1256370'>an</span> <span m='1256490'>impulse</span>
  <span m='1256970'>train?</span> <span m='1260420'>So</span> <span m='1260660'>I'm--</span>
  <span m='1260820'>oh, it's</span> <span m='1261080'>on</span> <span m='1261170'>the</span>
  <span m='1261230'>next</span> <span m='1261340'>slide.</span> <span m='1262130'>What</span>
  <span m='1262310'>if</span> <span m='1262430'>I</span> <span m='1262520'>had</span>
  <span m='1262700'>an</span> <span m='1262820'>impulse</span> <span m='1263240'>train</span>
  <span m='1263570'>like</span> <span m='1263780'>so?</span> <span m='1265910'>If</span>
  <span m='1266060'>I</span> <span m='1266180'>think</span> <span m='1266390'>about</span>
  <span m='1266630'>having</span> <span m='1267020'>an</span> <span m='1267140'>impulse</span>
  <span m='1267530'>train,</span> <span m='1267860'>if</span> <span m='1267920'>I</span>
  <span m='1268010'>had</span> <span m='1268130'>the</span> <span m='1268220'>base</span>
  <span m='1268560'>waveform</span> <span m='1271150'>and</span> <span m='1271310'>an</span>
  <span m='1271400'>appropriate</span> <span m='1271850'>impulse</span> <span m='1272240'>train,</span>
  <span m='1274400'>how</span> <span m='1274580'>could</span> <span m='1274730'>I</span>
  <span m='1274820'>manufacture</span> <span m='1277340'>the</span> <span m='1279470'>signal</span>
  <span m='1279890'>of</span> <span m='1279950'>interest,</span> <span m='1280470'>which</span>
  <span m='1280550'>is</span> <span m='1280670'>this</span> <span m='1280820'>periodic</span>
  <span m='1281330'>extension?</span> </p><p><span m='1282530'>So</span> <span m='1282650'>if</span>
  <span m='1282770'>I</span> <span m='1282860'>have</span> <span m='1283040'>these</span>
  <span m='1283280'>two</span> <span m='1283430'>signals,</span> <span m='1283790'>what</span>
  <span m='1283940'>would</span> <span m='1284060'>I</span> <span m='1284120'>do</span>
  <span m='1284270'>to</span> <span m='1284360'>get</span> <span m='1284480'>that</span>
  <span m='1284630'>signal?</span> <span m='1287520'>Convolve.</span> <span m='1289270'>So</span>
  <span m='1289460'>if</span> <span m='1289700'>I</span> <span m='1289820'>knew</span>
  <span m='1292040'>the</span> <span m='1292130'>transform</span> <span m='1292430'>of</span>
  <span m='1292730'>this,</span> <span m='1293000'>which</span> <span m='1293180'>I</span>
  <span m='1293270'>do</span> <span m='1293540'>because</span> <span m='1293810'>this</span>
  <span m='1293960'>is</span> <span m='1294050'>the</span> <span m='1294140'>base</span>
  <span m='1294350'>case</span> <span m='1295810'>which</span> <span m='1296000'>we</span>
  <span m='1296090'>just</span> <span m='1296300'>did.</span> <span m='1297170'>If</span>
  <span m='1297290'>I</span> <span m='1297350'>knew</span> <span m='1297500'>the</span>
  <span m='1297590'>transform of</span> <span m='1298010'>the</span> <span m='1298070'>base</span>
  <span m='1298280'>case,</span> <span m='1298610'>and</span> <span m='1298700'>if</span>
  <span m='1298790'>I</span> <span m='1298850'>knew</span> <span m='1299000'>the</span>
  <span m='1299060'>transform</span> <span m='1299330'>of</span> <span m='1299600'>the</span>
  <span m='1299690'>impulse</span> <span m='1300230'>train--</span> <span m='1301550'>impulse</span>
  <span m='1301910'>train</span> <span m='1302150'>is</span> <span m='1302240'>something</span>
  <span m='1302570'>that</span> <span m='1302720'>goes</span> <span m='1303030'>to</span>
  <span m='1303110'>function</span> <span m='1303380'>of</span> <span m='1303470'>time.</span>
  </p><p><span m='1304360'>0--</span> <span m='1304850'>let's</span> <span m='1305000'>say</span>
  <span m='1305210'>that</span> <span m='1305330'>they're</span> <span m='1305480'>separated</span>
  <span m='1305900'>by</span> <span m='1306060'>t.</span> <span m='1306390'>Let's
  say</span> <span m='1306720'>each</span> <span m='1306890'>one</span> <span m='1307040'>has</span>
  <span m='1307160'>a</span> <span m='1307220'>height</span> <span m='1307340'>of</span>
  <span m='1307460'>1.</span> <span m='1308450'>What's</span> <span m='1308810'>the</span>
  <span m='1309200'>Fourier</span> <span m='1309770'>transform</span> <span m='1310630'>of</span>
  <span m='1310790'>an</span> <span m='1310880'>impulse</span> <span m='1311360'>train?</span>
  <span m='1320350'>I</span> <span m='1320380'>can</span> <span m='1320560'>see</span>
  <span m='1320740'>you're all</span> <span m='1320930'>on</span> <span m='1321250'>the</span>
  <span m='1321370'>edge</span> <span m='1321550'>of</span> <span m='1321640'>your</span>
  <span m='1321760'>seats.</span> <span m='1326000'>How</span> <span m='1326210'>do</span>
  <span m='1326270'>you</span> <span m='1326420'>find</span> <span m='1327080'>the</span>
  <span m='1327980'>Fourier</span> <span m='1328400'>transform</span> <span m='1328900'>of</span>
  <span m='1328970'>an</span> <span m='1329060'>impulse</span> <span m='1329360'>train?</span>
  <span m='1332540'>OK,</span> <span m='1332730'>ask</span> <span m='1332930'>your</span>
  <span m='1333030'>neighbor.</span> </p><p><span m='1447010'>So</span> <span m='1447200'>how</span>
  <span m='1447440'>do</span> <span m='1447550'>you</span> <span m='1447640'>find</span>
  <span m='1448330'>the</span> <span m='1448630'>Fourier</span> <span m='1448960'>transform</span>
  <span m='1449580'>of</span> <span m='1449670'>an</span> <span m='1449810'>impulse</span>
  <span m='1450040'>train?</span> <span m='1454230'>Look it</span> <span m='1454330'>up</span>
  <span m='1454510'>in</span> <span m='1454640'>the</span> <span m='1454830'>tables!</span>
  <span m='1457430'>Boo,</span> <span m='1457790'>hiss.</span> <span m='1461280'>How
  do</span> <span m='1461430'>you</span> <span m='1461570'>find</span> <span m='1461840'>the</span>
  <span m='1462680'>Fourier</span> <span m='1463130'>transform</span> <span m='1463670'>of</span>
  <span m='1463760'>an</span> <span m='1463820'>impulse</span> <span m='1464120'>train?</span>
  </p><p><span m='1468630'>Is</span> <span m='1468750'>there</span> <span m='1468930'>anything</span>
  <span m='1469500'>easy</span> <span m='1469860'>about an</span> <span m='1470250'>impulse</span>
  <span m='1470580'>train?</span> <span m='1470970'>What</span> <span m='1471120'>a</span>
  <span m='1471150'>horrendous</span> <span m='1471630'>thing,</span> <span m='1471900'>right?</span>
  <span m='1473700'>It</span> <span m='1473820'>has</span> <span m='1473970'>an</span>
  <span m='1474060'>infinite</span> <span m='1474360'>number</span> <span m='1474810'>of</span>
  <span m='1475020'>impulses,</span> <span m='1475620'>yuck.</span> <span m='1476010'>Each</span>
  <span m='1476410'>impulse is</span> <span m='1476880'>horribly</span> <span m='1479990'>misbehaved.</span>
  <span m='1481790'>How</span> <span m='1481940'>would</span> <span m='1482060'>I</span>
  <span m='1482150'>find</span> <span m='1482630'>the</span> <span m='1482840'>Fourier</span>
  <span m='1483180'>transform</span> <span m='1483730'>of</span> <span m='1483860'>a</span>
  <span m='1483920'>train</span> <span m='1484160'>of</span> <span m='1484260'>impulses?</span>
  <span m='1484610'>Yes?</span> </p><p><span m='1484950'>AUDIENCE:</span> <span m='1485200'>So
  if you</span> <span m='1485450'>actually just</span> <span m='1485950'>plug that</span>
  <span m='1486450'>in to the</span> <span m='1486950'>formula, then</span> <span
  m='1487450'>you get</span> <span m='1487950'>different</span> <span m='1488450'>exponents</span>
  <span m='1488950'>and</span> <span m='1489450'>like,</span> <span m='1490450'>[INAUDIBLE],</span>
  <span m='1491100'>and then,</span> <span m='1491450'>since</span> <span m='1491800'>there's</span>
  <span m='1492295'>negative</span> <span m='1492790'>infinity to</span> <span m='1493285'>infinity,</span>
  <span m='1493780'>they add</span> <span m='1494275'>up to</span> <span m='1494770'>the</span>
  <span m='1495265'>[INAUDIBLE].</span> </p><p><span m='1496750'>DENNIS FREEMAN:</span>
  <span m='1496825'>So</span> <span m='1497480'>you're</span> <span m='1498110'>saying</span>
  <span m='1498410'>that</span> <span m='1498530'>somehow</span> <span m='1498890'>I</span>
  <span m='1498980'>should</span> <span m='1499250'>stick</span> <span m='1499610'>it</span>
  <span m='1499710'>into--</span> <span m='1500510'>so</span> <span m='1500910'>I'm</span>
  <span m='1501050'>thinking</span> <span m='1501260'>about</span> <span m='1501500'>finding</span>
  <span m='1502040'>the</span> <span m='1502170'>Fourier</span> <span m='1502550'>transform</span>
  <span m='1505100'>by</span> <span m='1505250'>going</span> <span m='1505520'>back</span>
  <span m='1505760'>to</span> <span m='1505850'>the</span> <span m='1506240'>direct</span>
  <span m='1506630'>formula.</span> <span m='1508860'>So</span> <span m='1508970'>if</span>
  <span m='1509120'>I</span> <span m='1509260'>put</span> <span m='1509530'>an</span>
  <span m='1509970'>infinite</span> <span m='1510620'>train</span> <span m='1510860'>of</span>
  <span m='1510950'>impulses</span> <span m='1511490'>here,</span> <span m='1513030'>what</span>
  <span m='1513110'>would</span> <span m='1513230'>I</span> <span m='1513350'>do?</span>
  <span m='1513910'>So</span> <span m='1514070'>I'd</span> <span m='1514190'>have</span>
  <span m='1514350'>a</span> <span m='1514510'>sum</span> <span m='1515390'>of</span>
  <span m='1517370'>delta</span> <span m='1518080'>of</span> <span m='1518510'>t</span>
  <span m='1518930'>minus,</span> <span m='1519740'>say,</span> <span m='1520040'>n</span>
  <span m='1521360'>times</span> <span m='1522210'>t</span> <span m='1523790'>sum</span>
  <span m='1524150'>over</span> <span m='1524480'>n</span> <span m='1525140'>e</span>
  <span m='1525340'>to</span> <span m='1525470'>the</span> <span m='1525560'>minus</span>
  <span m='1525815'>j</span> <span m='1526070'>omega</span> <span m='1526530'>t</span>
  <span m='1526860'>dt.</span> </p><p><span m='1534780'>That's</span> <span m='1534960'>a</span>
  <span m='1535020'>good</span> <span m='1535170'>step.</span> <span m='1538630'>So</span>
  <span m='1538780'>now,</span> <span m='1539380'>what</span> <span m='1539740'>I</span>
  <span m='1539830'>might</span> <span m='1540040'>do</span> <span m='1540250'>is</span>
  <span m='1540380'>interchange</span> <span m='1540850'>the</span> <span m='1540970'>order,</span>
  <span m='1541210'>because</span> <span m='1541450'>that's</span> <span m='1541600'>what</span>
  <span m='1541690'>everybody</span> <span m='1542020'>does,</span> <span m='1542550'>right?</span>
  <span m='1543780'>And</span> <span m='1543980'>it's</span> <span m='1544150'>a</span>
  <span m='1544210'>little</span> <span m='1544480'>dicey</span> <span m='1544900'>doing</span>
  <span m='1545170'>that,</span> <span m='1545410'>right?</span> <span m='1545990'>You're</span>
  <span m='1546250'>always</span> <span m='1546520'>safe</span> <span m='1546760'>to</span>
  <span m='1546850'>do</span> <span m='1546970'>that</span> <span m='1547220'>if</span>
  <span m='1547360'>the</span> <span m='1547540'>integrand</span> <span m='1548140'>is</span>
  <span m='1548260'>absolutely</span> <span m='1548680'>summable.</span> <span m='1549400'>That's</span>
  <span m='1549580'>not</span> <span m='1549850'>precisely</span> <span m='1550900'>absolutely</span>
  <span m='1551440'>summable.</span> </p><p><span m='1553430'>Everybody</span> <span
  m='1553760'>knows</span> <span m='1554000'>what</span> <span m='1555020'>absolutely</span>
  <span m='1555640'>summable</span> <span m='1555890'>means?</span> <span m='1559260'>So</span>
  <span m='1559500'>it</span> <span m='1559640'>means</span> <span m='1559880'>if</span>
  <span m='1560000'>you</span> <span m='1560060'>took</span> <span m='1560240'>the</span>
  <span m='1560330'>absolute</span> <span m='1560630'>value</span> <span m='1561200'>and</span>
  <span m='1561470'>you</span> <span m='1561560'>summed</span> <span m='1561780'>it</span>
  <span m='1561920'>over</span> <span m='1562130'>all</span> <span m='1562310'>of</span>
  <span m='1562400'>time,</span> <span m='1562730'>you would</span> <span m='1562880'>get</span>
  <span m='1563030'>something</span> <span m='1563300'>less</span> <span m='1563440'>than</span>
  <span m='1563540'>infinity.</span> <span m='1564350'>That's</span> <span m='1564560'>not</span>
  <span m='1564770'>quite</span> <span m='1565010'>the</span> <span m='1565100'>truth</span>
  <span m='1565550'>here,</span> <span m='1565940'>right?</span> </p><p><span m='1566720'>So</span>
  <span m='1566930'>some</span> <span m='1567080'>of</span> <span m='1567170'>the</span>
  <span m='1567230'>sums</span> <span m='1567590'>in</span> <span m='1567740'>Fourier</span>
  <span m='1568040'>series</span> <span m='1568960'>and</span> <span m='1569180'>Fourier</span>
  <span m='1569440'>transforms</span> <span m='1569810'>can</span> <span m='1569900'>be</span>
  <span m='1570020'>hard,</span> <span m='1570940'>OK?</span> <span m='1571210'>But</span>
  <span m='1572210'>throwing</span> <span m='1572660'>caution</span> <span m='1573020'>to</span>
  <span m='1573110'>the</span> <span m='1573200'>wind,</span> <span m='1573830'>we</span>
  <span m='1573980'>would</span> <span m='1574130'>probably</span> <span m='1574550'>get</span>
  <span m='1574730'>something</span> <span m='1575120'>like</span> <span m='1576050'>that.</span>
  </p><p><span m='1581940'>And</span> <span m='1582030'>then</span> <span m='1582180'>we</span>
  <span m='1582300'>could</span> <span m='1582480'>say,</span> <span m='1582850'>well,</span>
  <span m='1582900'>that</span> <span m='1583110'>just</span> <span m='1583290'>samples</span>
  <span m='1583830'>it.</span> <span m='1585270'>We</span> <span m='1585360'>could</span>
  <span m='1585510'>sample</span> <span m='1585990'>this</span> <span m='1586230'>thing</span>
  <span m='1586620'>at</span> <span m='1586860'>t</span> <span m='1587310'>equals</span>
  <span m='1587510'>nt.</span> <span m='1587815'>So</span> <span m='1588120'>that</span>
  <span m='1588300'>would</span> <span m='1588450'>be</span> <span m='1589110'>e</span>
  <span m='1589210'>to</span> <span m='1589430'>the</span> <span m='1589530'>minus</span>
  <span m='1590010'>j</span> <span m='1592230'>omega</span> <span m='1592910'>nt.</span>
  <span m='1595860'>Then</span> <span m='1596040'>I</span> <span m='1596160'>end</span>
  <span m='1596370'>up</span> <span m='1596670'>summing</span> <span m='1597660'>a</span>
  <span m='1597750'>large</span> <span m='1598170'>number</span> <span m='1598650'>of</span>
  <span m='1598890'>complex</span> <span m='1599400'>exponentials--</span> <span m='1601320'>large</span>
  <span m='1601650'>being</span> <span m='1601920'>infinite.</span> <span m='1603948'>It's</span>
  <span m='1604350'>kind</span> <span m='1604650'>of</span> <span m='1604770'>ugly.</span>
  <span m='1606240'>Yes?</span> </p><p><span m='1606735'>AUDIENCE:</span> <span m='1606982'>Could</span>
  <span m='1607230'>you</span> <span m='1607725'>now</span> <span m='1608715'>[INAUDIBLE].</span>
  </p><p><span m='1616150'>So</span> <span m='1616500'>I</span> <span m='1616580'>could</span>
  <span m='1616710'>split</span> <span m='1617000'>this</span> <span m='1617200'>into</span>
  <span m='1617410'>two</span> <span m='1617650'>sums--</span> <span m='1618310'>n</span>
  <span m='1619060'>less</span> <span m='1619360'>than</span> <span m='1619540'>0,</span>
  <span m='1620000'>and</span> <span m='1620110'>a</span> <span m='1620170'>similar</span>
  <span m='1620560'>sum--</span> <span m='1620950'>n</span> <span m='1621220'>bigger</span>
  <span m='1621520'>than</span> <span m='1621670'>0.</span> <span m='1622170'>And</span>
  <span m='1622310'>then</span> <span m='1622510'>throw</span> <span m='1622750'>in
  the</span> <span m='1622960'>0</span> <span m='1623290'>term,</span> <span m='1623560'>just</span>
  <span m='1623740'>for</span> <span m='1623830'>good</span> <span m='1623980'>measure.</span>
  </p><p><span m='1626414'>AUDIENCE:</span> <span m='1626662'>And</span> <span m='1626910'>then</span>
  <span m='1627406'>we</span> <span m='1627902'>can</span> <span m='1628398'>see you
  have a</span> <span m='1628894'>bunch of</span> <span m='1629390'>sines--</span>
  <span m='1629886'>actually,</span> <span m='1630382'>in this case,</span> <span
  m='1630878'>you have a bunch</span> <span m='1631374'>of cosine terms.</span> <span
  m='1631870'>So you</span> <span m='1632366'>know</span> <span m='1632862'>that--</span>
  <span m='1633358'>by</span> <span m='1633854'>having the</span> <span m='1634350'>cosine
  terms,</span> <span m='1634846'>[INAUDIBLE].</span> </p><p><span m='1638830'>DENNIS
  FREEMAN:</span> <span m='1638950'>So</span> <span m='1639070'>you</span> <span m='1639240'>just</span>
  <span m='1639420'>said something</span> <span m='1639865'>that</span> <span m='1640310'>seemed</span>
  <span m='1640600'>to</span> <span m='1640690'>take</span> <span m='1640900'>a</span>
  <span m='1640930'>left</span> <span m='1641110'>turn,</span> <span m='1641320'>there.</span>
  <span m='1641440'>What</span> <span m='1641530'>was</span> <span m='1641660'>the</span>
  <span m='1641700'>thing</span> <span m='1641860'>about</span> <span m='1642040'>series?</span>
  </p><p><span m='1643990'>AUDIENCE:</span> <span m='1644195'>So</span> <span m='1644400'>if
  you</span> <span m='1644620'>take</span> <span m='1644880'>your Fourier series</span>
  <span m='1646670'>of</span> <span m='1646800'>a</span> <span m='1647120'>sum</span>
  <span m='1647410'>of</span> <span m='1647890'>cosines,</span> <span m='1648140'>it's</span>
  <span m='1648626'>just</span> <span m='1649598'>the</span> <span m='1650084'>coefficient</span>
  <span m='1650570'>of</span> <span m='1651056'>the same sign?</span> </p><p><span
  m='1652030'>DENNIS FREEMAN:</span> <span m='1652165'>So,</span> <span m='1653650'>that</span>
  <span m='1653800'>sounds</span> <span m='1654070'>good.</span> <span m='1655300'>Could</span>
  <span m='1655420'>we</span> <span m='1655540'>use</span> <span m='1655810'>that</span>
  <span m='1655960'>idea</span> <span m='1656440'>of</span> <span m='1656560'>taking</span>
  <span m='1656860'>a</span> <span m='1656910'>Fourier</span> <span m='1657220'>series</span>
  <span m='1657610'>a little</span> <span m='1657970'>earlier</span> <span m='1658420'>in</span>
  <span m='1658510'>the</span> <span m='1658570'>proof?</span> <span m='1662200'>How</span>
  <span m='1662350'>would</span> <span m='1662480'>I</span> <span m='1662560'>take
  the</span> <span m='1662800'>Fourier</span> <span m='1663130'>transform</span> <span
  m='1663415'>of</span> <span m='1663700'>that?</span> <span m='1665810'>How</span>
  <span m='1665920'>would</span> <span m='1666040'>I</span> <span m='1666100'>take</span>
  <span m='1666250'>the</span> <span m='1666340'>Fourier</span> <span m='1666610'>series</span>
  <span m='1667090'>of</span> <span m='1667190'>that?</span> <span m='1669900'>Yeah?</span>
  </p><p><span m='1671358'>AUDIENCE:</span> <span m='1671601'>All</span> <span m='1672330'>1's.</span>
  <span m='1674760'>All 1's.</span> </p><p><span m='1676260'>DENNIS FREEMAN:</span>
  <span m='1676280'>All</span> <span m='1676300'>the</span> <span m='1676620'>1's,</span>
  <span m='1677730'>yes,</span> <span m='1678270'>yes.</span> <span m='1679020'>This</span>
  <span m='1679290'>is</span> <span m='1679410'>periodic.</span> <span m='1680010'>It</span>
  <span m='1680100'>has</span> <span m='1680250'>a</span> <span m='1680310'>series.</span>
  <span m='1682170'>Trick?</span> <span m='1683840'>No,</span> <span m='1683990'>no,</span>
  <span m='1684325'>no--</span> <span m='1684660'>clever</span> <span m='1685290'>observation,</span>
  <span m='1686220'>not</span> <span m='1686460'>a</span> <span m='1686520'>trick.</span>
  <span m='1688590'>So</span> <span m='1689070'>it's</span> <span m='1689250'>a</span>
  <span m='1689310'>periodic</span> <span m='1689910'>waveform.</span> <span m='1690450'>It</span>
  <span m='1690570'>has</span> <span m='1690840'>a</span> <span m='1690900'>series.</span>
  </p><p><span m='1692730'>OK,</span> <span m='1693110'>why</span> <span m='1693330'>is</span>
  <span m='1693450'>that</span> <span m='1693720'>good?</span> <span m='1694470'>Periodic</span>
  <span m='1695160'>waveform</span> <span m='1695760'>series,</span> <span m='1696170'>I</span>
  <span m='1696230'>only</span> <span m='1696390'>need</span> <span m='1696540'>to</span>
  <span m='1696630'>look</span> <span m='1696780'>at</span> <span m='1696840'>one</span>
  <span m='1697050'>period.</span> <span m='1697680'>I</span> <span m='1697770'>reduce</span>
  <span m='1698070'>an</span> <span m='1698190'>infinite</span> <span m='1698520'>number</span>
  <span m='1698910'>of</span> <span m='1699090'>impulses</span> <span m='1699870'>to</span>
  <span m='1700560'>one.</span> <span m='1701850'>That's</span> <span m='1702180'>a</span>
  <span m='1702210'>good</span> <span m='1702390'>move.</span> </p><p><span m='1704890'>So</span>
  <span m='1705070'>all</span> <span m='1705310'>I</span> <span m='1705400'>need</span>
  <span m='1705580'>to</span> <span m='1705700'>do</span> <span m='1706090'>is--</span>
  <span m='1706880'>to</span> <span m='1707040'>find</span> <span m='1707260'>the</span>
  <span m='1707350'>series,</span> <span m='1707840'>all</span> <span m='1707920'>I</span>
  <span m='1708040'>need</span> <span m='1708190'>to</span> <span m='1708280'>do</span>
  <span m='1708430'>is</span> <span m='1708550'>think</span> <span m='1708700'>about</span>
  <span m='1709790'>the</span> <span m='1711090'>Fourier</span> <span m='1711580'>series</span>
  <span m='1712210'>sum.</span> <span m='1712600'>Which</span> <span m='1712780'>is</span>
  <span m='1712870'>almost</span> <span m='1713260'>the</span> <span m='1713350'>same</span>
  <span m='1713590'>thing,</span> <span m='1714770'>except</span> <span m='1714970'>that
  now</span> <span m='1715180'>I've</span> <span m='1715420'>got</span> <span m='1715600'>something</span>
  <span m='1715900'>that</span> <span m='1715990'>has</span> <span m='1716140'>k's</span>
  <span m='1716410'>in</span> <span m='1716590'>it,</span> <span m='1718120'>right?</span>
  <span m='1718450'>Because</span> <span m='1719060'>a</span> <span m='1719140'>series</span>
  <span m='1719770'>only</span> <span m='1720160'>has</span> <span m='1720340'>harmonic</span>
  <span m='1720850'>frequencies.</span> </p><p><span m='1723500'>So</span> <span m='1723580'>what</span>
  <span m='1723730'>I</span> <span m='1723790'>can</span> <span m='1723970'>do</span>
  <span m='1724090'>is,</span> <span m='1724310'>instead of</span> <span m='1724510'>thinking</span>
  <span m='1724690'>about</span> <span m='1724840'>a</span> <span m='1724900'>Fourier</span>
  <span m='1725350'>series--</span> <span m='1727630'>so</span> <span m='1727780'>now</span>
  <span m='1727990'>I</span> <span m='1728080'>can</span> <span m='1728230'>say,</span>
  <span m='1728530'>instead</span> <span m='1728800'>of</span> <span m='1728860'>finding</span>
  <span m='1729160'>the</span> <span m='1729250'>Fourier</span> <span m='1729550'>transform,</span>
  <span m='1730620'>let's</span> <span m='1731140'>find</span> <span m='1731550'>the</span>
  <span m='1731740'>Fourier</span> <span m='1732130'>series.</span> <span m='1732610'>That's</span>
  <span m='1732760'>find</span> <span m='1733070'>a</span> <span m='1733300'>sub</span>
  <span m='1733640'>k,</span> <span m='1735010'>which</span> <span m='1735220'>would</span>
  <span m='1735310'>be</span> <span m='1735460'>1</span> <span m='1735670'>over</span>
  <span m='1735910'>t to the</span> <span m='1736330'>integral</span> <span m='1736740'>on</span>
  <span m='1736930'>t</span> <span m='1737350'>of</span> <span m='1737440'>x</span>
  <span m='1737620'>of</span> <span m='1737740'>t</span> <span m='1739030'>e</span>
  <span m='1739500'>to</span> <span m='1739630'>the</span> <span m='1739750'>minus</span>
  <span m='1740110'>j</span> <span m='1740440'>2</span> <span m='1740680'>pi</span>
  <span m='1741630'>kt</span> <span m='1742630'>by</span> <span m='1743020'>t</span>
  <span m='1743590'>on</span> <span m='1744070'>t,</span> <span m='1744880'>OK?</span>
  </p><p><span m='1745210'>So</span> <span m='1746350'>now</span> <span m='1746540'>I</span>
  <span m='1746650'>only</span> <span m='1746770'>need</span> <span m='1746950'>to</span>
  <span m='1747040'>find</span> <span m='1747220'>the</span> <span m='1747280'>series.</span>
  <span m='1748990'>And</span> <span m='1749290'>by</span> <span m='1749470'>integrating</span>
  <span m='1749890'>over</span> <span m='1750120'>t--</span> <span m='1750850'>OK,</span>
  <span m='1751080'>well</span> <span m='1751180'>I'll</span> <span m='1751270'>do</span>
  <span m='1751420'>the</span> <span m='1751570'>easy</span> <span m='1751900'>one,</span>
  <span m='1752110'>right?</span> <span m='1752710'>Never</span> <span m='1752920'>do</span>
  <span m='1753070'>something</span> <span m='1753370'>that's</span> <span m='1753520'>hard.</span>
  <span m='1753760'>I</span> <span m='1753820'>can</span> <span m='1753970'>choose</span>
  <span m='1754210'>any</span> <span m='1754780'>interval</span> <span m='1755110'>of</span>
  <span m='1755200'>t.</span> <span m='1755380'>Let</span> <span m='1755500'>me</span>
  <span m='1755590'>take</span> <span m='1755740'>that</span> <span m='1755950'>one.</span>
  </p><p><span m='1758140'>So</span> <span m='1758290'>the</span> <span m='1758440'>only</span>
  <span m='1758680'>thing</span> <span m='1758920'>that</span> <span m='1759070'>persists,</span>
  <span m='1759680'>then--</span> <span m='1760240'>so</span> <span m='1760480'>if</span>
  <span m='1760660'>I</span> <span m='1760720'>do</span> <span m='1761110'>minus--</span>
  <span m='1761770'>whatever,</span> <span m='1762130'>t</span> <span m='1762290'>by</span>
  <span m='1762430'>2</span> <span m='1762846'>to</span> <span m='1763262'>t</span>
  <span m='1763680'>by</span> <span m='1763870'>2,</span> <span m='1765280'>then</span>
  <span m='1765490'>this</span> <span m='1765670'>becomes</span> <span m='1766030'>delta</span>
  <span m='1766420'>of</span> <span m='1766900'>t.</span> <span m='1769860'>And</span>
  <span m='1770010'>delta</span> <span m='1770280'>of</span> <span m='1770550'>t</span>
  <span m='1771180'>sifts</span> <span m='1771630'>out</span> <span m='1771960'>the</span>
  <span m='1772080'>0</span> <span m='1772440'>value</span> <span m='1773520'>of</span>
  <span m='1773760'>this</span> <span m='1773970'>guy.</span> <span m='1775815'>But</span>
  <span m='1776270'>e</span> <span m='1776660'>to</span> <span m='1776990'>0</span>
  <span m='1777590'>is</span> <span m='1777860'>1.</span> <span m='1778760'>So</span>
  <span m='1778910'>this</span> <span m='1779180'>is</span> <span m='1779480'>1</span>
  <span m='1779730'>over</span> <span m='1779850'>t</span> <span m='1781010'>for</span>
  <span m='1781280'>all</span> <span m='1781750'>k.</span> </p><p><span m='1783800'>We</span>
  <span m='1783890'>knew</span> <span m='1784040'>that,</span> <span m='1784220'>right?</span>
  <span m='1785090'>The</span> <span m='1785480'>Fourier</span> <span m='1786050'>series</span>
  <span m='1786650'>for</span> <span m='1786930'>a</span> <span m='1787350'>unit</span>
  <span m='1787700'>impulse</span> <span m='1788780'>is</span> <span m='1789020'>1</span>
  <span m='1789260'>everywhere.</span> <span m='1789950'>All</span> <span m='1790100'>the</span>
  <span m='1790220'>harmonics</span> <span m='1790640'>have</span> <span m='1790730'>the</span>
  <span m='1790820'>same</span> <span m='1791060'>size--</span> <span m='1792320'>same</span>
  <span m='1792590'>size,</span> <span m='1792860'>same</span> <span m='1793730'>magnitude,</span>
  <span m='1794120'>same</span> <span m='1794660'>phase</span> <span m='1794960'>everywhere.</span>
  </p><p><span m='1796580'>Then,</span> <span m='1797150'>since</span> <span m='1797360'>we</span>
  <span m='1797480'>know</span> <span m='1797730'>the</span> <span m='1797750'>series,</span>
  <span m='1798890'>we</span> <span m='1799010'>can</span> <span m='1799160'>trivially</span>
  <span m='1799610'>convert it</span> <span m='1799970'>into</span> <span m='1800240'>a</span>
  <span m='1800300'>Fourier</span> <span m='1800570'>transform,</span> <span m='1802310'>right?</span>
  <span m='1802490'>Using</span> <span m='1802820'>the</span> <span m='1803690'>deep</span>
  <span m='1804050'>insight</span> <span m='1804590'>from</span> <span m='1805100'>a</span>
  <span m='1805340'>few</span> <span m='1805520'>slides</span> <span m='1805790'>ago,</span>
  <span m='1806300'>right?</span> <span m='1806540'>So</span> <span m='1806660'>how</span>
  <span m='1806780'>do</span> <span m='1806840'>you</span> <span m='1806960'>take
  a</span> <span m='1807260'>series</span> <span m='1807680'>and</span> <span m='1807770'>turn</span>
  <span m='1807920'>it</span> <span m='1808010'>into</span> <span m='1808160'>a</span>
  <span m='1808220'>transform?</span> <span m='1810680'>Substitute</span> <span m='1811310'>for</span>
  <span m='1811490'>every</span> <span m='1811790'>k.</span> </p><p><span m='1814725'>AUDIENCE:</span>
  <span m='1814958'>[INAUDIBLE].</span> </p><p><span m='1818000'>DENNIS FREEMAN:</span>
  <span m='1818100'>Put</span> <span m='1818200'>an</span> <span m='1818330'>impulse</span>
  <span m='1819230'>in</span> <span m='1819410'>place</span> <span m='1819680'>of</span>
  <span m='1819800'>every</span> <span m='1820100'>k</span> <span m='1820970'>at</span>
  <span m='1821300'>the</span> <span m='1821630'>frequency--</span> <span m='1822530'>omega--</span>
  <span m='1823070'>that</span> <span m='1823220'>corresponds</span> <span m='1823910'>to</span>
  <span m='1824000'>that</span> <span m='1824190'>k,</span> <span m='1825960'>OK?</span>
  <span m='1826560'>The</span> <span m='1826710'>k's--</span> <span m='1827550'>0,</span>
  <span m='1827980'>1,</span> <span m='1828190'>2,</span> <span m='1828900'>3, are
  the</span> <span m='1829170'>0, 1,</span> <span m='1829440'>2,</span> <span m='1829720'>3</span>
  <span m='1829860'>harmonics.</span> <span m='1830520'>The</span> <span m='1830610'>harmonics</span>
  <span m='1831090'>are</span> <span m='1831180'>harmonics</span> <span m='1831570'>of</span>
  <span m='1831630'>the</span> <span m='1831720'>fundamental.</span> <span m='1832200'>The</span>
  <span m='1832290'>fundamental</span> <span m='1832770'>is</span> <span m='1832860'>2</span>
  <span m='1833040'>pi</span> <span m='1833370'>over</span> <span m='1833700'>t.</span>
  </p><p><span m='1836460'>So</span> <span m='1836900'>you</span> <span m='1837140'>put</span>
  <span m='1837500'>one</span> <span m='1837780'>impulse</span> <span m='1838310'>at</span>
  <span m='1838490'>every</span> <span m='1838790'>multiple</span> <span m='1839360'>of</span>
  <span m='1839450'>2</span> <span m='1839630'>pi</span> <span m='1839890'>over</span>
  <span m='1840190'>capital</span> <span m='1840550'>T.</span> <span m='1842600'>And</span>
  <span m='1843350'>you</span> <span m='1843440'>multiply</span> <span m='1843920'>them</span>
  <span m='1844040'>all</span> <span m='1844340'>by</span> <span m='1844520'>2</span>
  <span m='1844700'>pi.</span> <span m='1845730'>So</span> <span m='1845810'>here's</span>
  <span m='1846020'>your</span> <span m='1846110'>answer.</span> <span m='1847340'>You</span>
  <span m='1847490'>start</span> <span m='1847700'>with</span> <span m='1847910'>this</span>
  <span m='1848060'>thing</span> <span m='1848270'>you</span> <span m='1848390'>recognize</span>
  <span m='1848850'>as a</span> <span m='1849020'>periodic</span> <span m='1849480'>waveform.</span>
  <span m='1850500'>You</span> <span m='1850580'>turn</span> <span m='1850850'>it</span>
  <span m='1850940'>into</span> <span m='1851180'>a</span> <span m='1851240'>series.</span>
  <span m='1853400'>Then</span> <span m='1853580'>you</span> <span m='1853670'>convert</span>
  <span m='1854090'>every</span> <span m='1854390'>one</span> <span m='1854690'>of</span>
  <span m='1854880'>the</span> <span m='1855140'>harmonics</span> <span m='1856310'>into</span>
  <span m='1857200'>a</span> <span m='1857300'>continuous</span> <span m='1857780'>frequency</span>
  <span m='1858140'>representation</span> <span m='1859340'>so</span> <span m='1859550'>that</span>
  <span m='1859670'>the</span> <span m='1859790'>spacing</span> <span m='1860450'>is</span>
  <span m='1860720'>the</span> <span m='1860840'>base</span> <span m='1861110'>period</span>
  <span m='1861500'>2 pi</span> <span m='1861650'>over</span> <span m='1862010'>cap</span>
  <span m='1862220'>T.</span> </p><p><span m='1865250'>The</span> <span m='1865430'>height</span>
  <span m='1865670'>of</span> <span m='1865790'>these</span> <span m='1866000'>guys</span>
  <span m='1866300'>was</span> <span m='1866390'>1</span> <span m='1866570'>over</span>
  <span m='1866780'>T,</span> <span m='1867020'>because</span> <span m='1867290'>of</span>
  <span m='1867350'>the</span> <span m='1867440'>annoying</span> <span m='1867740'>1</span>
  <span m='1867920'>over</span> <span m='1868100'>T</span> <span m='1868340'>factor</span>
  <span m='1868730'>in</span> <span m='1868820'>front</span> <span m='1869030'>of</span>
  <span m='1869120'>the</span> <span m='1869210'>Fourier</span> <span m='1869360'>series</span>
  <span m='1869840'>formula.</span> <span m='1872590'>And</span> <span m='1872950'>you</span>
  <span m='1873070'>get</span> <span m='1873220'>an</span> <span m='1873310'>extra</span>
  <span m='1873640'>2</span> <span m='1873820'>pi,</span> <span m='1874060'>because</span>
  <span m='1874360'>the</span> <span m='1874480'>annoying</span> <span m='1874810'>1</span>
  <span m='1874980'>over</span> <span m='1875170'>2</span> <span m='1875380'>pi</span>
  <span m='1876220'>in</span> <span m='1876460'>the</span> <span m='1876640'>inverse</span>
  <span m='1877120'>Fourier</span> <span m='1878110'>formula,</span> <span m='1880170'>OK?</span>
  </p><p><span m='1881390'>So</span> <span m='1881540'>what</span> <span m='1881690'>we</span>
  <span m='1881810'>see,</span> <span m='1881990'>then,</span> <span m='1882230'>is</span>
  <span m='1882480'>that</span> <span m='1882800'>the</span> <span m='1883070'>Fourier</span>
  <span m='1883400'>transform of</span> <span m='1883850'>an</span> <span m='1883940'>impulse</span>
  <span m='1884210'>train</span> <span m='1884420'>is</span> <span m='1884510'>an</span>
  <span m='1884590'>impulse</span> <span m='1884810'>train.</span> <span m='1887190'>And</span>
  <span m='1887240'>so</span> <span m='1887420'>we</span> <span m='1887540'>can</span>
  <span m='1887690'>use</span> <span m='1887990'>that,</span> <span m='1888230'>then,</span>
  <span m='1888410'>to</span> <span m='1888520'>find</span> <span m='1888830'>the</span>
  <span m='1888950'>Fourier</span> <span m='1889280'>transform</span> <span m='1889820'>of</span>
  <span m='1889940'>this</span> <span m='1890150'>mass,</span> <span m='1890480'>remember?</span>
  <span m='1891260'>Oh,</span> <span m='1891440'>I've</span> <span m='1891560'>got--</span>
  <span m='1891870'>oh,</span> <span m='1892010'>here</span> <span m='1892140'>it</span>
  <span m='1892270'>is.</span> </p><p><span m='1892760'>I</span> <span m='1892850'>was</span>
  <span m='1893030'>taking</span> <span m='1893300'>my</span> <span m='1893420'>base</span>
  <span m='1893680'>waveform,</span> <span m='1894170'>which</span> <span m='1894320'>was</span>
  <span m='1894440'>a</span> <span m='1894500'>triangle,</span> <span m='1896030'>trying</span>
  <span m='1896300'>to</span> <span m='1896390'>figure</span> <span m='1896690'>out</span>
  <span m='1897290'>what</span> <span m='1897440'>would</span> <span m='1897560'>happen</span>
  <span m='1897800'>if</span> <span m='1897920'>I</span> <span m='1897980'>did</span>
  <span m='1898220'>an</span> <span m='1898310'>infinite</span> <span m='1898700'>extension</span>
  <span m='1899150'>of</span> <span m='1899240'>that--</span> <span m='1899780'>an</span>
  <span m='1899960'>infinite</span> <span m='1900260'>periodic</span> <span m='1900740'>extension.</span>
  <span m='1901970'>I</span> <span m='1902090'>think</span> <span m='1902300'>about</span>
  <span m='1902510'>the</span> <span m='1902630'>extension</span> <span m='1903140'>as</span>
  <span m='1903260'>being</span> <span m='1903590'>convolving</span> <span m='1904970'>the</span>
  <span m='1905090'>base</span> <span m='1905390'>waveform.</span> <span m='1907520'>Cover
  that</span> <span m='1907940'>up.</span> </p><p><span m='1908460'>If</span> <span
  m='1908600'>I</span> <span m='1908690'>think</span> <span m='1908870'>about</span>
  <span m='1909070'>convolving</span> <span m='1909560'>the</span> <span m='1909650'>base</span>
  <span m='1909860'>wave,</span> <span m='1910230'>form--</span> <span m='1912684'>oh,
  no,</span> <span m='1913120'>it's</span> <span m='1913340'>gone.</span> <span m='1914450'>If</span>
  <span m='1914480'>I</span> <span m='1914530'>think</span> <span m='1914720'>about</span>
  <span m='1915020'>convolving</span> <span m='1915500'>the</span> <span m='1915590'>base</span>
  <span m='1915880'>waveform</span> <span m='1916700'>with</span> <span m='1916850'>periodic</span>
  <span m='1917330'>train</span> <span m='1917600'>of</span> <span m='1917690'>impulses,</span>
  <span m='1920360'>that</span> <span m='1920750'>means</span> <span m='1921200'>that--</span>
  <span m='1921410'>so</span> <span m='1921620'>the</span> <span m='1921800'>time</span>
  <span m='1922100'>waveform</span> <span m='1922580'>is</span> <span m='1922700'>the</span>
  <span m='1922760'>convolution</span> <span m='1923480'>of</span> <span m='1923630'>two</span>
  <span m='1923810'>things.</span> <span m='1924390'>That</span> <span m='1924440'>means</span>
  <span m='1924740'>that</span> <span m='1924920'>the</span> <span m='1925860'>Fourier</span>
  <span m='1926390'>transform</span> <span m='1926810'>is</span> <span m='1926900'>the</span>
  <span m='1926990'>multiplying</span> <span m='1928670'>of</span> <span m='1928820'>two</span>
  <span m='1928970'>things.</span> </p><p><span m='1930420'>So</span> <span m='1930470'>I</span>
  <span m='1930530'>write</span> <span m='1930740'>down</span> <span m='1931040'>the</span>
  <span m='1931260'>transform</span> <span m='1931530'>of</span> <span m='1931770'>the</span>
  <span m='1931850'>base</span> <span m='1932030'>waveform--</span> <span m='1934620'>thing</span>
  <span m='1934800'>that</span> <span m='1934890'>we</span> <span m='1934950'>did</span>
  <span m='1935060'>a</span> <span m='1935090'>long</span> <span m='1935280'>time</span>
  <span m='1935490'>ago.</span> <span m='1936690'>I</span> <span m='1936810'>write</span>
  <span m='1936990'>down</span> <span m='1937200'>the</span> <span m='1937290'>Fourier</span>
  <span m='1937570'>transform</span> <span m='1938160'>of</span> <span m='1938310'>the</span>
  <span m='1938400'>impulse</span> <span m='1938730'>train.</span> <span m='1945960'>The</span>
  <span m='1946050'>period</span> <span m='1946350'>of</span> <span m='1946410'>the</span>
  <span m='1946560'>impulse</span> <span m='1946830'>train</span> <span m='1947070'>is</span>
  <span m='1947220'>the</span> <span m='1947280'>same</span> <span m='1947520'>as</span>
  <span m='1947610'>the</span> <span m='1947730'>period</span> <span m='1948060'>of</span>
  <span m='1948150'>the</span> <span m='1948240'>periodic</span> <span m='1948690'>extension,</span>
  <span m='1949420'>which</span> <span m='1949500'>is</span> <span m='1950070'>capital
  T.</span> </p><p><span m='1950560'>It</span> <span m='1950600'>was</span> <span
  m='1950760'>4.</span> <span m='1952350'>So</span> <span m='1952470'>that</span>
  <span m='1952620'>means</span> <span m='1953530'>the</span> <span m='1953970'>impulses</span>
  <span m='1954480'>are</span> <span m='1954540'>separated</span> <span m='1955050'>by</span>
  <span m='1955230'>2</span> <span m='1955440'>pi</span> <span m='1955710'>over</span>
  <span m='1956040'>4</span> <span m='1956790'>pi</span> <span m='1957040'>over</span>
  <span m='1957280'>2.</span> <span m='1959330'>And</span> <span m='1960650'>the</span>
  <span m='1960920'>height of</span> <span m='1961300'>the</span> <span m='1961490'>impulse</span>
  <span m='1961830'>is</span> <span m='1962000'>always</span> <span m='1962480'>equal</span>
  <span m='1962720'>to</span> <span m='1962840'>their</span> <span m='1962990'>separation.</span>
  <span m='1963600'>So</span> <span m='1963710'>they're</span> <span m='1963910'>also
  pi</span> <span m='1964220'>over</span> <span m='1964620'>2.</span> <span m='1967200'>So</span>
  <span m='1967440'>then</span> <span m='1967830'>all</span> <span m='1968040'>I</span>
  <span m='1968130'>do</span> <span m='1968310'>is</span> <span m='1968430'>multiply</span>
  <span m='1968910'>this</span> <span m='1969090'>times</span> <span m='1969390'>this,</span>
  <span m='1969600'>and</span> <span m='1969720'>that gives</span> <span m='1969990'>me</span>
  <span m='1970080'>the</span> <span m='1970170'>transform.</span> <span m='1971400'>Convolving</span>
  <span m='1972120'>time,</span> <span m='1972510'>multiplying</span> <span m='1972900'>frequency.</span>
  </p><p><span m='1974700'>The</span> <span m='1974790'>important</span> <span m='1975150'>thing</span>
  <span m='1975330'>that</span> <span m='1975450'>I</span> <span m='1975540'>found</span>
  <span m='1976350'>is</span> <span m='1976510'>that</span> <span m='1976590'>the</span>
  <span m='1976710'>effect</span> <span m='1976980'>of</span> <span m='1977130'>periodic</span>
  <span m='1977670'>extension--</span> <span m='1981100'>I</span> <span m='1981190'>took</span>
  <span m='1981430'>a</span> <span m='1982090'>base</span> <span m='1982390'>waveform</span>
  <span m='1982840'>and</span> <span m='1982930'>turned</span> <span m='1983140'>it</span>
  <span m='1983230'>into</span> <span m='1983440'>a</span> <span m='1983470'>string</span>
  <span m='1983740'>of</span> <span m='1983800'>waveforms,</span> <span m='1984470'>right?</span>
  <span m='1984820'>So</span> <span m='1985420'>over</span> <span m='1985630'>here,</span>
  <span m='1985870'>I</span> <span m='1985930'>took</span> <span m='1987610'>a</span>
  <span m='1987670'>base</span> <span m='1988010'>waveform</span> <span m='1988930'>and</span>
  <span m='1989110'>turned</span> <span m='1989320'>it</span> <span m='1989440'>into</span>
  <span m='1991300'>a</span> <span m='1991390'>repeated</span> <span m='1992440'>thing,</span>
  <span m='1992930'>like</span> <span m='1993280'>so,</span> <span m='1994030'>in</span>
  <span m='1994210'>time.</span> </p><p><span m='1996940'>The</span> <span m='1997030'>effect</span>
  <span m='1997300'>of</span> <span m='1997360'>the</span> <span m='1997480'>periodic</span>
  <span m='1997900'>extension,</span> <span m='1999610'>which</span> <span m='1999790'>we</span>
  <span m='1999910'>understand</span> <span m='2000420'>trivially</span> <span m='2000900'>in</span>
  <span m='2001020'>time,</span> <span m='2001830'>is</span> <span m='2002050'>to</span>
  <span m='2002220'>sample</span> <span m='2002910'>frequency.</span> <span m='2005720'>What</span>
  <span m='2005930'>I</span> <span m='2006080'>get</span> <span m='2006910'>in</span>
  <span m='2007160'>the</span> <span m='2007280'>frequency</span> <span m='2007880'>representation</span>
  <span m='2009640'>is</span> <span m='2009820'>samples.</span> <span m='2010640'>The</span>
  <span m='2010760'>samples</span> <span m='2011180'>being</span> <span m='2011480'>controlled</span>
  <span m='2012980'>by</span> <span m='2013220'>how</span> <span m='2013400'>long</span>
  <span m='2013720'>is</span> <span m='2013910'>the</span> <span m='2014510'>periodic</span>
  <span m='2014960'>extension.</span> <span m='2017160'>So</span> <span m='2017310'>what</span>
  <span m='2017520'>I</span> <span m='2017640'>get</span> <span m='2017880'>is</span>
  <span m='2018330'>samples.</span> <span m='2019050'>Instead</span> <span m='2019320'>of</span>
  <span m='2019410'>getting</span> <span m='2019650'>all</span> <span m='2019980'>of</span>
  <span m='2020070'>these,</span> <span m='2020370'>I</span> <span m='2020490'>just</span>
  <span m='2020670'>get</span> <span m='2020850'>part.</span> <span m='2021270'>I</span>
  <span m='2021390'>just</span> <span m='2021570'>get</span> <span m='2022800'>a</span>
  <span m='2022890'>uniformly-spaced</span> <span m='2023730'>sample</span> <span
  m='2024120'>set</span> <span m='2024440'>separated</span> <span m='2024840'>by</span>
  <span m='2024960'>pi</span> <span m='2025340'>over</span> <span m='2025630'>2.</span>
  </p><p><span m='2028320'>So</span> <span m='2028540'>then</span> <span m='2028840'>the</span>
  <span m='2029020'>effect</span> <span m='2029470'>of</span> <span m='2029770'>the</span>
  <span m='2030760'>periodic</span> <span m='2031300'>extension</span> <span m='2032260'>was</span>
  <span m='2032620'>to</span> <span m='2034000'>sample</span> <span m='2036220'>the</span>
  <span m='2036320'>Fourier</span> <span m='2036600'>transform of the</span> <span
  m='2037020'>base</span> <span m='2037220'>waveform.</span> <span m='2038940'>And</span>
  <span m='2039120'>that's</span> <span m='2039420'>the</span> <span m='2039540'>reason</span>
  <span m='2040050'>we</span> <span m='2040260'>can</span> <span m='2040440'>think</span>
  <span m='2040650'>about</span> <span m='2041400'>the</span> <span m='2041650'>Fourier</span>
  <span m='2042630'>series</span> <span m='2043380'>as</span> <span m='2043620'>being</span>
  <span m='2043920'>just</span> <span m='2044130'>a</span> <span m='2044190'>sequence</span>
  <span m='2044550'>of</span> <span m='2044640'>numbers.</span> <span m='2045070'>In</span>
  <span m='2045170'>fact,</span> <span m='2045310'>those</span> <span m='2045420'>numbers</span>
  <span m='2045750'>are</span> <span m='2045840'>the</span> <span m='2045930'>same.</span>
  <span m='2047930'>Or,</span> <span m='2048150'>they</span> <span m='2048300'>differ</span>
  <span m='2048540'>by</span> <span m='2048650'>2</span> <span m='2048820'>pi,</span>
  <span m='2050060'>right?</span> </p><p><span m='2050310'>So</span> <span m='2050400'>I</span>
  <span m='2050460'>have</span> <span m='2050580'>to</span> <span m='2050670'>multiply</span>
  <span m='2052230'>these</span> <span m='2052500'>guys</span> <span m='2052739'>by</span>
  <span m='2052889'>2</span> <span m='2053100'>pi</span> <span m='2053370'>to</span>
  <span m='2053520'>get</span> <span m='2053699'>the</span> <span m='2053790'>Fourier</span>
  <span m='2054179'>transform</span> <span m='2054780'>coefficients,</span> <span
  m='2056150'>because</span> <span m='2056550'>the</span> <span m='2056810'>Fourier</span>
  <span m='2057090'>transform</span> <span m='2057400'>of</span> <span m='2057710'>cosine</span>
  <span m='2058210'>of</span> <span m='2058699'>e to the</span> <span m='2058949'>j
  omega</span> <span m='2059310'>not t,</span> <span m='2059429'>I</span> <span m='2059510'>should</span>
  <span m='2059800'>say,</span> <span m='2061900'>is</span> <span m='2062080'>2</span>
  <span m='2062260'>pi</span> <span m='2062469'>delta,</span> <span m='2064960'>OK?</span>
  </p><p><span m='2065290'>So</span> <span m='2065469'>the</span> <span m='2065620'>reason</span>
  <span m='2065915'>the</span> <span m='2066210'>Fourier</span> <span m='2066580'>series</span>
  <span m='2067420'>coefficients</span> <span m='2067989'>are</span> <span m='2068080'>related</span>
  <span m='2068500'>the</span> <span m='2068620'>way</span> <span m='2068770'>they</span>
  <span m='2068980'>are,</span> <span m='2071000'>the</span> <span m='2071020'>reason</span>
  <span m='2071380'>they</span> <span m='2072219'>sample</span> <span m='2073270'>the</span>
  <span m='2073449'>Fourier</span> <span m='2073780'>transform,</span> <span m='2074440'>is</span>
  <span m='2074620'>because</span> <span m='2075159'>we</span> <span m='2075280'>can</span>
  <span m='2075429'>regard</span> <span m='2075790'>the</span> <span m='2075909'>periodic</span>
  <span m='2076540'>extension,</span> <span m='2077739'>which</span> <span m='2077940'>was</span>
  <span m='2078100'>convolved</span> <span m='2078600'>by</span> <span m='2078730'>an</span>
  <span m='2078820'>impulse</span> <span m='2079150'>train</span> <span m='2079420'>as</span>
  <span m='2079540'>being</span> <span m='2079810'>equivalently</span> <span m='2080710'>multiplying</span>
  <span m='2081370'>by</span> <span m='2081489'>an</span> <span m='2081620'>impulse</span>
  <span m='2081840'>train</span> <span m='2082449'>and</span> <span m='2082630'>frequency.</span>
  <span m='2084433'>OK?</span> </p><p><span m='2086239'>That's</span> <span m='2086420'>what</span>
  <span m='2086570'>I</span> <span m='2086659'>wanted</span> <span m='2086900'>you</span>
  <span m='2086989'>to</span> <span m='2087050'>see.</span> <span m='2087239'>I</span>
  <span m='2087290'>wanted</span> <span m='2087460'>you</span> <span m='2087550'>to</span>
  <span m='2087620'>see</span> <span m='2087860'>that</span> <span m='2089480'>if</span>
  <span m='2089659'>you</span> <span m='2089810'>think</span> <span m='2090020'>about</span>
  <span m='2091880'>periodic</span> <span m='2092449'>extension--</span> <span m='2094639'>which</span>
  <span m='2094719'>is</span> <span m='2094840'>moving</span> <span m='2095139'>left</span>
  <span m='2095440'>in</span> <span m='2095530'>this</span> <span m='2095679'>diagram.</span>
  <span m='2096850'>If</span> <span m='2097000'>you think</span> <span m='2097240'>about</span>
  <span m='2097390'>moving</span> <span m='2097720'>left,</span> <span m='2098120'>what</span>
  <span m='2098170'>you're</span> <span m='2098260'>really</span> <span m='2098530'>doing</span>
  <span m='2098770'>is</span> <span m='2098890'>sampling</span> <span m='2099460'>in</span>
  <span m='2099550'>frequency.</span> </p><p><span m='2101750'>So</span> <span m='2101800'>that's</span>
  <span m='2102100'>the</span> <span m='2102250'>reason</span> <span m='2103240'>it</span>
  <span m='2103420'>came</span> <span m='2103720'>out</span> <span m='2104020'>having</span>
  <span m='2104320'>a</span> <span m='2104380'>sampled</span> <span m='2104800'>representation</span>
  <span m='2105490'>on</span> <span m='2105610'>the</span> <span m='2105700'>left.</span>
  <span m='2108750'>The</span> <span m='2108840'>periodic</span> <span m='2109410'>extension</span>
  <span m='2110480'>convolving</span> <span m='2111000'>with</span> <span m='2111160'>an</span>
  <span m='2111210'>impulse</span> <span m='2111630'>train</span> <span m='2111960'>was</span>
  <span m='2112110'>the</span> <span m='2112200'>same</span> <span m='2112410'>as</span>
  <span m='2112530'>multiplying</span> <span m='2113070'>by</span> <span m='2113180'>the</span>
  <span m='2113280'>impulse</span> <span m='2113610'>train</span> <span m='2114230'>and</span>
  <span m='2114690'>frequency,</span> <span m='2115800'>which</span> <span m='2115980'>has</span>
  <span m='2116130'>the</span> <span m='2116220'>effect</span> <span m='2116520'>of</span>
  <span m='2116610'>sampling</span> <span m='2117690'>the</span> <span m='2117870'>frequency</span>
  <span m='2118230'>response.</span> </p><p><span m='2119990'>OK,</span> <span m='2121590'>so</span>
  <span m='2121770'>now</span> <span m='2122940'>the</span> <span m='2123180'>effect</span>
  <span m='2123510'>of</span> <span m='2123600'>moving</span> <span m='2123900'>this</span>
  <span m='2124110'>way</span> <span m='2124440'>was</span> <span m='2124650'>the</span>
  <span m='2124710'>same</span> <span m='2124950'>sampling</span> <span m='2125400'>in</span>
  <span m='2125490'>frequency.</span> <span m='2126090'>Well,</span> <span m='2126290'>what</span>
  <span m='2126390'>happens</span> <span m='2126570'>if</span> <span m='2126660'>you</span>
  <span m='2126780'>actually</span> <span m='2127200'>sample</span> <span m='2127590'>in</span>
  <span m='2127710'>time,</span> <span m='2128160'>which</span> <span m='2128310'>is</span>
  <span m='2128940'>what</span> <span m='2129150'>you</span> <span m='2129240'>do</span>
  <span m='2129360'>when</span> <span m='2129480'>you</span> <span m='2129540'>go</span>
  <span m='2129780'>up?</span> <span m='2133850'>It's</span> <span m='2134030'>got</span>
  <span m='2134210'>to</span> <span m='2134270'>be</span> <span m='2134410'>an</span>
  <span m='2134530'>[INAUDIBLE]</span> <span m='2134670'>like this,</span> <span m='2134870'>right?</span>
  </p><p><span m='2137770'>So,</span> <span m='2138140'>the</span> <span m='2139160'>most</span>
  <span m='2139460'>useful</span> <span m='2139820'>thing</span> <span m='2140030'>about
  the Fourier</span> <span m='2140360'>transform</span> <span m='2141080'>is</span>
  <span m='2141260'>that</span> <span m='2141410'>the</span> <span m='2141560'>Fourier</span>
  <span m='2141890'>transform</span> <span m='2142370'>and the</span> <span m='2142460'>inverse</span>
  <span m='2142760'>transform</span> <span m='2143180'>look</span> <span m='2143330'>almost</span>
  <span m='2143720'>the</span> <span m='2143810'>same.</span> <span m='2145490'>That's</span>
  <span m='2145790'>the</span> <span m='2146210'>most</span> <span m='2146540'>useful</span>
  <span m='2146900'>property</span> <span m='2147230'>of</span> <span m='2147290'>the</span>
  <span m='2147450'>transform.</span> </p><p><span m='2148230'>Now,</span> <span m='2148380'>the</span>
  <span m='2149000'>Fourier</span> <span m='2149240'>transform</span> <span m='2149630'>has</span>
  <span m='2149750'>a</span> <span m='2149810'>simple</span> <span m='2150170'>inverse</span>
  <span m='2150650'>relationship,</span> <span m='2151610'>and</span> <span m='2151730'>is</span>
  <span m='2151880'>almost</span> <span m='2152360'>precisely</span> <span m='2153050'>the</span>
  <span m='2153170'>same</span> <span m='2153470'>except</span> <span m='2153710'>for</span>
  <span m='2153830'>the</span> <span m='2153940'>annoying</span> <span m='2154240'>2</span>
  <span m='2154430'>pi</span> <span m='2156520'>and</span> <span m='2156680'>except</span>
  <span m='2156950'>for</span> <span m='2157070'>a</span> <span m='2157100'>change</span>
  <span m='2157460'>of</span> <span m='2157610'>sign--</span> <span m='2159470'>e</span>
  <span m='2159710'>to</span> <span m='2159810'>the</span> <span m='2159950'>j omega</span>
  <span m='2160380'>t,</span> <span m='2161330'>compared</span> <span m='2161660'>to</span>
  <span m='2161720'>e to</span> <span m='2161960'>the</span> <span m='2162050'>minus</span>
  <span m='2162450'>j</span> <span m='2162610'>omega t.</span> <span m='2163790'>Except</span>
  <span m='2164090'>for</span> <span m='2164210'>those</span> <span m='2164420'>trivial</span>
  <span m='2164900'>differences,</span> <span m='2165420'>they're</span> <span m='2165560'>the</span>
  <span m='2165710'>same</span> <span m='2165980'>thing.</span> </p><p><span m='2166760'>So</span>
  <span m='2166910'>we</span> <span m='2167030'>might</span> <span m='2167240'>expect</span>
  <span m='2167990'>that</span> <span m='2168110'>if</span> <span m='2168200'>we</span>
  <span m='2168350'>understood</span> <span m='2169340'>the</span> <span m='2169520'>effect</span>
  <span m='2169810'>of</span> <span m='2169940'>moving</span> <span m='2170270'>that</span>
  <span m='2170540'>way,</span> <span m='2170900'>which</span> <span m='2171410'>is</span>
  <span m='2173210'>convolve</span> <span m='2173780'>in</span> <span m='2173910'>time,</span>
  <span m='2174550'>multiply in</span> <span m='2174950'>frequency,</span> <span m='2176210'>you</span>
  <span m='2176330'>might</span> <span m='2176540'>expect</span> <span m='2177650'>an</span>
  <span m='2177770'>analogous</span> <span m='2178310'>thing</span> <span m='2178490'>to</span>
  <span m='2178580'>happen</span> <span m='2178910'>this</span> <span m='2179060'>way.</span>
  <span m='2179330'>And</span> <span m='2179420'>of</span> <span m='2179510'>course,</span>
  <span m='2179750'>it</span> <span m='2179810'>does.</span> </p><p><span m='2181730'>So</span>
  <span m='2181940'>here,</span> <span m='2182870'>let's</span> <span m='2183100'>think</span>
  <span m='2183230'>about</span> <span m='2183410'>the</span> <span m='2183500'>base</span>
  <span m='2183840'>waveform--</span> <span m='2184760'>same</span> <span m='2185030'>base</span>
  <span m='2185330'>waveform.</span> <span m='2186780'>But</span> <span m='2186800'>now</span>
  <span m='2186980'>what</span> <span m='2187130'>we're</span> <span m='2187250'>doing</span>
  <span m='2187520'>is</span> <span m='2187580'>sampling</span> <span m='2188000'>in</span>
  <span m='2188090'>time.</span> <span m='2188450'>And</span> <span m='2188540'>I'll</span>
  <span m='2188630'>just</span> <span m='2188840'>arbitrarily,</span> <span m='2189470'>for</span>
  <span m='2189590'>the</span> <span m='2189830'>sake</span> <span m='2190100'>of</span>
  <span m='2190160'>illustration,</span> <span m='2191090'>sample</span> <span m='2191510'>it</span>
  <span m='2191570'>with</span> <span m='2191780'>capital T</span> <span m='2192120'>equals</span>
  <span m='2192650'>a</span> <span m='2192710'>half.</span> </p><p><span m='2194480'>Question</span>
  <span m='2194900'>is--</span> <span m='2195500'>what</span> <span m='2195710'>would</span>
  <span m='2195920'>that</span> <span m='2196310'>sampling</span> <span m='2197090'>in</span>
  <span m='2197330'>time</span> <span m='2198380'>do</span> <span m='2198560'>to</span>
  <span m='2198650'>the</span> <span m='2198740'>Fourier</span> <span m='2199010'>transform?</span>
  <span m='2200180'>OK,</span> <span m='2200420'>sampling</span> <span m='2200810'>is</span>
  <span m='2200930'>time.</span> <span m='2201200'>That's</span> <span m='2201320'>something</span>
  <span m='2201560'>we</span> <span m='2201620'>understand</span> <span m='2201980'>completely</span>
  <span m='2202400'>in</span> <span m='2202490'>the</span> <span m='2202550'>time</span>
  <span m='2202760'>domain.</span> <span m='2203480'>What</span> <span m='2203660'>would</span>
  <span m='2203840'>happen</span> <span m='2204110'>in</span> <span m='2204200'>the</span>
  <span m='2204290'>Fourier</span> <span m='2204710'>domain?</span> </p><p><span m='2207610'>OK,</span>
  <span m='2207980'>well</span> <span m='2208100'>that's</span> <span m='2208310'>a</span>
  <span m='2208370'>little</span> <span m='2208550'>hard</span> <span m='2208700'>to</span>
  <span m='2208790'>compare,</span> <span m='2209730'>because</span> <span m='2210590'>the</span>
  <span m='2210710'>domain</span> <span m='2211490'>of</span> <span m='2211670'>these</span>
  <span m='2212000'>two</span> <span m='2212270'>signals--</span> <span m='2212810'>this</span>
  <span m='2212990'>is</span> <span m='2213530'>continuous</span> <span m='2214010'>domain,</span>
  <span m='2214680'>T.</span> <span m='2215600'>This</span> <span m='2215870'>is</span>
  <span m='2216050'>discrete</span> <span m='2216410'>domain.</span> <span m='2216920'>And</span>
  <span m='2217670'>that's</span> <span m='2217910'>kind</span> <span m='2218120'>of</span>
  <span m='2218180'>annoying.</span> <span m='2219300'>So</span> <span m='2219400'>it's</span>
  <span m='2219500'>kind</span> <span m='2219530'>of</span> <span m='2219590'>hard,</span>
  <span m='2220070'>because</span> <span m='2220310'>they're</span> <span m='2220400'>not</span>
  <span m='2220610'>on</span> <span m='2220730'>equal</span> <span m='2221000'>footing</span>
  <span m='2221360'>to</span> <span m='2221450'>compare</span> <span m='2221840'>them.</span>
  </p><p><span m='2222890'>So</span> <span m='2223010'>what</span> <span m='2223130'>I</span>
  <span m='2223190'>can</span> <span m='2223370'>do</span> <span m='2223550'>is</span>
  <span m='2223670'>map</span> <span m='2223970'>the</span> <span m='2224060'>same</span>
  <span m='2224480'>information</span> <span m='2225170'>that</span> <span m='2225260'>was</span>
  <span m='2225440'>here</span> <span m='2226100'>into</span> <span m='2226460'>a</span>
  <span m='2226610'>representation</span> <span m='2227390'>over</span> <span m='2227630'>here</span>
  <span m='2229490'>that</span> <span m='2229670'>is</span> <span m='2229790'>continuous</span>
  <span m='2230360'>in</span> <span m='2230450'>time.</span> <span m='2232630'>The</span>
  <span m='2232790'>information</span> <span m='2233300'>over</span> <span m='2233480'>here</span>
  <span m='2233990'>was</span> <span m='2234620'>0</span> <span m='2235070'>everywhere,</span>
  <span m='2235970'>except</span> <span m='2236360'>one</span> <span m='2236780'>half-and-half.</span>
  <span m='2238790'>Here</span> <span m='2239150'>it's</span> <span m='2239240'>0</span>
  <span m='2239600'>everywhere</span> <span m='2239990'>except</span> <span m='2240260'>one</span>
  <span m='2240500'>half-and-half.</span> </p><p><span m='2242240'>Anyone</span> <span
  m='2242510'>know</span> <span m='2242750'>why</span> <span m='2243470'>I</span>
  <span m='2243590'>used</span> <span m='2244400'>impulses</span> <span m='2245150'>instead</span>
  <span m='2245540'>of</span> <span m='2245630'>just</span> <span m='2245810'>making</span>
  <span m='2246080'>the</span> <span m='2246170'>function</span> <span m='2246500'>different?</span>
  <span m='2248150'>Why</span> <span m='2248390'>didn't</span> <span m='2248640'>I,</span>
  <span m='2248930'>instead</span> <span m='2249260'>of</span> <span m='2249350'>using</span>
  <span m='2249620'>the</span> <span m='2249740'>complicated--</span> <span m='2250600'>wouldn't</span>
  <span m='2250770'>it</span> <span m='2250850'>be</span> <span m='2250940'>much</span>
  <span m='2251150'>easier</span> <span m='2252740'>if</span> <span m='2252860'>I</span>
  <span m='2252950'>didn't</span> <span m='2253190'>use</span> <span m='2253400'>the</span>
  <span m='2253490'>impulses?</span> <span m='2254760'>And</span> <span m='2254780'>if</span>
  <span m='2254900'>instead,</span> <span m='2257960'>I</span> <span m='2258050'>just</span>
  <span m='2258260'>said,</span> <span m='2258560'>OK,</span> <span m='2259490'>my</span>
  <span m='2260090'>xp</span> <span m='2260510'>of</span> <span m='2260630'>t--</span>
  <span m='2262490'>why</span> <span m='2262670'>didn't</span> <span m='2262910'>I</span>
  <span m='2263030'>say</span> <span m='2263270'>xp</span> <span m='2263660'>of</span>
  <span m='2263780'>t</span> <span m='2265370'>is</span> <span m='2265550'>almost</span>
  <span m='2265940'>everywhere</span> <span m='2266300'>0,</span> <span m='2267560'>except</span>
  <span m='2268160'>at</span> <span m='2268340'>that</span> <span m='2268580'>point,</span>
  <span m='2269270'>at</span> <span m='2269450'>that</span> <span m='2269750'>point,</span>
  <span m='2270560'>and</span> <span m='2270680'>at</span> <span m='2270800'>that</span>
  <span m='2271070'>point?</span> <span m='2273720'>Why</span> <span m='2273840'>didn't</span>
  <span m='2274050'>I</span> <span m='2274140'>do</span> <span m='2274290'>that?</span>
  <span m='2283152'>Yes?</span> </p><p><span m='2283636'>AUDIENCE:</span> <span m='2283878'>[INAUDIBLE].</span>
  </p><p></p><p><span m='2288970'>DENNIS FREEMAN:</span> <span m='2289140'>Right,</span>
  <span m='2289310'>let's</span> <span m='2289520'>assume</span> <span m='2289820'>that</span>
  <span m='2289970'>it</span> <span m='2290090'>is</span> <span m='2290270'>continuous.</span>
  <span m='2291480'>And</span> <span m='2291590'>that</span> <span m='2291740'>there's</span>
  <span m='2297590'>exactly</span> <span m='2298070'>three</span> <span m='2298310'>points</span>
  <span m='2298730'>that</span> <span m='2298880'>differ</span> <span m='2299240'>from</span>
  <span m='2299420'>the</span> <span m='2299510'>straight</span> <span m='2299720'>line</span>
  <span m='2299990'>at</span> <span m='2300080'>0.</span> <span m='2301690'>Yes?</span>
  <span m='2303150'>The</span> <span m='2303270'>integral's</span> <span m='2303580'>0.</span>
  <span m='2305320'>That</span> <span m='2305560'>never</span> <span m='2305800'>works.</span>
  <span m='2308610'>In</span> <span m='2308760'>fact,</span> <span m='2309090'>the</span>
  <span m='2309180'>most</span> <span m='2309390'>trivial</span> <span m='2309780'>representation</span>
  <span m='2310590'>that</span> <span m='2310770'>only</span> <span m='2311040'>has</span>
  <span m='2311220'>energy</span> <span m='2311580'>at</span> <span m='2311670'>three</span>
  <span m='2311880'>places</span> <span m='2312480'>is</span> <span m='2312840'>three</span>
  <span m='2313410'>impulses.</span> <span m='2315830'>That's</span> <span m='2315980'>the</span>
  <span m='2316050'>only</span> <span m='2316220'>way</span> <span m='2316340'>to</span>
  <span m='2316430'>get</span> <span m='2316880'>non-trivial</span> <span m='2317660'>energy.</span>
  </p><p><span m='2319390'>OK,</span> <span m='2319840'>so</span> <span m='2319940'>I</span>
  <span m='2320040'>can't</span> <span m='2320180'>do</span> <span m='2320330'>that.</span>
  <span m='2321230'>I'm</span> <span m='2321350'>forced</span> <span m='2321680'>to</span>
  <span m='2321800'>do</span> <span m='2321920'>something</span> <span m='2322250'>like</span>
  <span m='2322430'>this.</span> <span m='2323190'>So</span> <span m='2323210'>now</span>
  <span m='2323390'>the</span> <span m='2323510'>idea</span> <span m='2323810'>is--</span>
  <span m='2324320'>I</span> <span m='2324480'>switched</span> <span m='2324890'>to</span>
  <span m='2325010'>this</span> <span m='2325160'>kind</span> <span m='2325340'>of</span>
  <span m='2325400'>representation</span> <span m='2326020'>that</span> <span m='2326100'>has
  the</span> <span m='2326270'>same</span> <span m='2326600'>information,</span> <span
  m='2328080'>but</span> <span m='2328280'>has</span> <span m='2328520'>the</span>
  <span m='2328640'>same</span> <span m='2329030'>domain--</span> <span m='2330260'>CT,</span>
  <span m='2331280'>continuous</span> <span m='2331730'>time.</span> <span m='2333490'>So</span>
  <span m='2333560'>that</span> <span m='2333710'>now</span> <span m='2333890'>I</span>
  <span m='2333950'>can</span> <span m='2334100'>think</span> <span m='2334220'>about--</span>
  <span m='2334370'>what's</span> <span m='2334580'>the</span> <span m='2334670'>Fourier</span>
  <span m='2334970'>transform</span> <span m='2335450'>of</span> <span m='2335540'>this</span>
  <span m='2335690'>guy?</span> </p><p><span m='2337140'>Well,</span> <span m='2337340'>it's</span>
  <span m='2337460'>the</span> <span m='2337550'>same</span> <span m='2337790'>idea.</span>
  <span m='2339350'>The</span> <span m='2339470'>way</span> <span m='2339740'>I</span>
  <span m='2339830'>can</span> <span m='2340010'>think</span> <span m='2340220'>about</span>
  <span m='2344030'>computing</span> <span m='2345620'>this</span> <span m='2345830'>thing</span>
  <span m='2346040'>from</span> <span m='2346220'>that</span> <span m='2346430'>thing</span>
  <span m='2347480'>is</span> <span m='2347660'>to</span> <span m='2347840'>multiply</span>
  <span m='2348560'>in</span> <span m='2348770'>time</span> <span m='2349190'>by</span>
  <span m='2349340'>an</span> <span m='2349500'>impulse train.</span> <span m='2353540'>What's</span>
  <span m='2353780'>the</span> <span m='2353870'>effect</span> <span m='2354140'>of</span>
  <span m='2354260'>multiplying</span> <span m='2354800'>time</span> <span m='2355010'>by
  an</span> <span m='2355160'>impulse</span> <span m='2355510'>train?</span> <span
  m='2356300'>What's</span> <span m='2356480'>the</span> <span m='2356570'>effect</span>
  <span m='2357450'>in</span> <span m='2357870'>frequency?</span> </p><p><span m='2359570'>Multiply</span>
  <span m='2360200'>in</span> <span m='2360380'>time</span> <span m='2360830'>by an</span>
  <span m='2361080'>impulse train,</span> <span m='2361670'>what</span> <span m='2361760'>are</span>
  <span m='2361790'>you</span> <span m='2361850'>doing to</span> <span m='2362030'>frequency?</span>
  <span m='2363600'>Convolving</span> <span m='2364440'>frequency.</span> <span m='2366130'>So</span>
  <span m='2366180'>we</span> <span m='2366330'>take</span> <span m='2366750'>the</span>
  <span m='2366870'>original</span> <span m='2367200'>base</span> <span m='2367540'>waveform,</span>
  <span m='2368320'>but</span> <span m='2368370'>now</span> <span m='2368550'>we</span>
  <span m='2368670'>convolve</span> <span m='2369100'>it.</span> <span m='2371890'>And</span>
  <span m='2372070'>lo</span> <span m='2372250'>and</span> <span m='2372340'>behold,</span>
  <span m='2373970'>we</span> <span m='2373990'>convolve</span> <span m='2374500'>this</span>
  <span m='2374740'>signal--</span> <span m='2375070'>which</span> <span m='2375220'>could</span>
  <span m='2375340'>be</span> <span m='2375490'>anything--</span> <span m='2376270'>with</span>
  <span m='2376420'>this</span> <span m='2376540'>signal--</span> <span m='2376900'>which</span>
  <span m='2377080'>is</span> <span m='2377200'>always</span> <span m='2377470'>periodic.</span>
  </p><p><span m='2378310'>If</span> <span m='2378430'>you</span> <span m='2378490'>convolve</span>
  <span m='2378630'>in</span> <span m='2378970'>anything</span> <span m='2379900'>with</span>
  <span m='2380110'>a</span> <span m='2380140'>periodic,</span> <span m='2380770'>what</span>
  <span m='2380860'>do</span> <span m='2380920'>you</span> <span m='2381010'>get?</span>
  <span m='2382630'>Periodic,</span> <span m='2384210'>inevitable.</span> <span m='2386240'>So</span>
  <span m='2386650'>the</span> <span m='2386770'>fact</span> <span m='2387130'>that</span>
  <span m='2387370'>I</span> <span m='2387580'>sampled</span> <span m='2388150'>in</span>
  <span m='2388330'>time</span> <span m='2389380'>leads</span> <span m='2389740'>to</span>
  <span m='2389890'>periodic</span> <span m='2390640'>in</span> <span m='2390760'>frequency.</span>
  <span m='2391630'>That's</span> <span m='2391990'>the</span> <span m='2392110'>point.</span>
  <span m='2393980'>Sampling</span> <span m='2394490'>in</span> <span m='2394610'>time</span>
  <span m='2395030'>leads</span> <span m='2395330'>to</span> <span m='2395420'>periodic</span>
  <span m='2395940'>in</span> <span m='2396100'>frequency.</span> <span m='2397460'>That's</span>
  <span m='2397730'>always</span> <span m='2398180'>going</span> <span m='2398330'>to</span>
  <span m='2398420'>be</span> <span m='2398510'>true.</span> </p><p><span m='2399750'>So</span>
  <span m='2399800'>we</span> <span m='2399950'>end</span> <span m='2400100'>up</span>
  <span m='2400220'>with</span> <span m='2400340'>a</span> <span m='2400400'>relationship</span>
  <span m='2401090'>here.</span> <span m='2401870'>The</span> <span m='2402020'>sampled</span>
  <span m='2402490'>waveform</span> <span m='2403460'>is</span> <span m='2403640'>going</span>
  <span m='2403760'>to</span> <span m='2403850'>be</span> <span m='2403970'>periodic.</span>
  <span m='2404600'>In</span> <span m='2404840'>here</span> <span m='2405110'>it's</span>
  <span m='2405380'>periodic,</span> <span m='2405870'>and</span> <span m='2405980'>4</span>
  <span m='2406280'>pi.</span> <span m='2407300'>That's</span> <span m='2407450'>a</span>
  <span m='2407540'>little</span> <span m='2407810'>different</span> <span m='2408110'>from</span>
  <span m='2408290'>what</span> <span m='2408440'>we've</span> <span m='2408590'>seen</span>
  <span m='2408830'>before.</span> <span m='2409670'>If</span> <span m='2409820'>we</span>
  <span m='2409910'>had</span> <span m='2410090'>looked</span> <span m='2410360'>at</span>
  <span m='2410630'>the</span> <span m='2411260'>x of</span> <span m='2411600'>n,</span>
  <span m='2411980'>we</span> <span m='2412130'>would</span> <span m='2412280'>have</span>
  <span m='2412370'>seen</span> <span m='2412640'>something</span> <span m='2412970'>that</span>
  <span m='2413090'>was</span> <span m='2413210'>periodic</span> <span m='2413750'>in
  2</span> <span m='2414080'>pi,</span> <span m='2414830'>but</span> <span m='2414980'>that's</span>
  <span m='2415250'>because</span> <span m='2415580'>the</span> <span m='2415670'>frequencies</span>
  <span m='2416270'>are</span> <span m='2416330'>different.</span> <span m='2419250'>One</span>
  </p><p><span m='2420320'>The</span> <span m='2420630'>first</span> <span m='2421050'>one</span>
  <span m='2421200'>I</span> <span m='2421290'>showed</span> <span m='2422070'>is</span>
  <span m='2422220'>a</span> <span m='2422280'>function</span> <span m='2422580'>of</span>
  <span m='2422670'>little</span> <span m='2422930'>omega,</span> <span m='2423690'>which</span>
  <span m='2423900'>has</span> <span m='2424110'>the</span> <span m='2424230'>units</span>
  <span m='2424650'>radians</span> <span m='2425160'>per</span> <span m='2425280'>second.</span>
  <span m='2427420'>This</span> <span m='2427650'>one</span> <span m='2428430'>is</span>
  <span m='2428640'>a</span> <span m='2428700'>function</span> <span m='2429030'>of</span>
  <span m='2429120'>cap</span> <span m='2429540'>Omega,</span> <span m='2430020'>which</span>
  <span m='2430290'>has</span> <span m='2430560'>the</span> <span m='2430710'>units</span>
  <span m='2431130'>radians,</span> <span m='2431700'>they're</span> <span m='2431900'>different.</span>
  <span m='2432750'>One's</span> <span m='2433440'>frequency</span> <span m='2433890'>in</span>
  <span m='2433980'>discrete</span> <span m='2434310'>time.</span> <span m='2434610'>One's</span>
  <span m='2434910'>frequency</span> <span m='2435330'>in</span> <span m='2436080'>continuous</span>
  <span m='2436680'>time.</span> </p><p><span m='2439350'>And</span> <span m='2439590'>there's</span>
  <span m='2439800'>a</span> <span m='2439860'>relationship,</span> <span m='2440610'>and</span>
  <span m='2440790'>that</span> <span m='2440970'>relationship</span> <span m='2441660'>is</span>
  <span m='2441900'>always</span> <span m='2442820'>this.</span> <span m='2444510'>That's</span>
  <span m='2444870'>the</span> <span m='2444960'>reason</span> <span m='2445290'>I</span>
  <span m='2445380'>write</span> <span m='2445620'>the</span> <span m='2445740'>two</span>
  <span m='2445920'>frequencies</span> <span m='2446520'>differently.</span> <span
  m='2448420'>One</span> <span m='2448590'>way</span> <span m='2448800'>to</span>
  <span m='2448950'>relate</span> <span m='2449430'>the</span> <span m='2449730'>two</span>
  <span m='2449940'>frequencies</span> <span m='2450600'>is</span> <span m='2450720'>via</span>
  <span m='2450970'>sampling.</span> <span m='2452100'>That's</span> <span m='2452280'>a</span>
  <span m='2452340'>way</span> <span m='2452520'>of</span> <span m='2452640'>taking</span>
  <span m='2453210'>a</span> <span m='2453300'>continuous</span> <span m='2453870'>time</span>
  <span m='2454140'>signal</span> <span m='2454470'>and</span> <span m='2454560'>turning</span>
  <span m='2454730'>it</span> <span m='2454840'>into</span> <span m='2455310'>a</span>
  <span m='2455370'>discrete</span> <span m='2455730'>time</span> <span m='2456000'>signal.</span>
  </p><p><span m='2456300'>When</span> <span m='2456450'>you</span> <span m='2456570'>do</span>
  <span m='2456810'>that,</span> <span m='2457810'>if</span> <span m='2457860'>you</span>
  <span m='2457950'>sample</span> <span m='2458430'>by</span> <span m='2458790'>the</span>
  <span m='2459090'>sampling</span> <span m='2459480'>interval</span> <span m='2459950'>capital</span>
  <span m='2460330'>T,</span> <span m='2461100'>that</span> <span m='2461460'>dictates</span>
  <span m='2462120'>that</span> <span m='2462240'>this</span> <span m='2462420'>relationship's</span>
  <span m='2463140'>going</span> <span m='2463380'>to</span> <span m='2463470'>be</span>
  <span m='2463590'>like</span> <span m='2463770'>that.</span> <span m='2464350'>And</span>
  <span m='2464370'>it's</span> <span m='2464550'>very</span> <span m='2464910'>general.</span>
  <span m='2466400'>All</span> <span m='2466560'>you</span> <span m='2466680'>need</span>
  <span m='2466830'>to</span> <span m='2466920'>do</span> <span m='2467070'>is</span>
  <span m='2467160'>look</span> <span m='2467300'>at</span> <span m='2467360'>the</span>
  <span m='2467400'>definitions.</span> </p><p><span m='2469350'>If</span> <span m='2469500'>you</span>
  <span m='2469590'>look</span> <span m='2469740'>at</span> <span m='2469800'>the</span>
  <span m='2469890'>definition</span> <span m='2470670'>of</span> <span m='2471450'>the</span>
  <span m='2472080'>DT</span> <span m='2473460'>Fourier</span> <span m='2474120'>transform--</span>
  <span m='2476220'>that's</span> <span m='2476550'>this--</span> <span m='2479150'>the</span>
  <span m='2479510'>CT</span> <span m='2480890'>Fourier</span> <span m='2481370'>transform--</span>
  <span m='2481970'>that's</span> <span m='2482210'>this--</span> <span m='2485190'>and</span>
  <span m='2485340'>just</span> <span m='2485550'>remember</span> <span m='2485970'>that</span>
  <span m='2486120'>we</span> <span m='2486480'>form</span> <span m='2486920'>this</span>
  <span m='2487200'>thing</span> <span m='2488370'>by</span> <span m='2488670'>samples</span>
  <span m='2489870'>of</span> <span m='2490020'>that</span> <span m='2490260'>thing.</span>
  </p><p><span m='2494260'>So</span> <span m='2494470'>now,</span> <span m='2494860'>if</span>
  <span m='2495040'>you</span> <span m='2495130'>think</span> <span m='2495310'>about</span>
  <span m='2495550'>flipping</span> <span m='2495940'>the</span> <span m='2496090'>order--</span>
  <span m='2496750'>and</span> <span m='2497050'>again,</span> <span m='2499210'>not</span>
  <span m='2499390'>worrying</span> <span m='2499600'>about</span> <span m='2499750'>whether</span>
  <span m='2500080'>or</span> <span m='2500110'>not</span> <span m='2500290'>it</span>
  <span m='2500330'>will</span> <span m='2500500'>converge.</span> <span m='2500980'>You</span>
  <span m='2501040'>just</span> <span m='2501190'>assume</span> <span m='2501460'>it</span>
  <span m='2501550'>will</span> <span m='2501820'>for</span> <span m='2501940'>the</span>
  <span m='2502000'>time</span> <span m='2502240'>being.</span> <span m='2503380'>Just</span>
  <span m='2503590'>flip</span> <span m='2503770'>the</span> <span m='2503920'>order</span>
  <span m='2504370'>of</span> <span m='2504670'>the</span> <span m='2505300'>summation</span>
  <span m='2505840'>and</span> <span m='2505930'>the</span> <span m='2506050'>integration.</span>
  <span m='2507340'>This</span> <span m='2507730'>then</span> <span m='2509290'>sifts</span>
  <span m='2509680'>out</span> <span m='2510070'>the</span> <span m='2510190'>value</span>
  <span m='2510700'>of</span> <span m='2510910'>little</span> <span m='2511240'>t</span>
  <span m='2511580'>equals</span> <span m='2512170'>n</span> <span m='2512500'>cap</span>
  <span m='2512850'>T,</span> <span m='2515340'>and</span> <span m='2515460'>we</span>
  <span m='2515610'>get</span> <span m='2515820'>a</span> <span m='2515910'>formula</span>
  <span m='2516450'>for</span> <span m='2516660'>the</span> <span m='2516840'>continuous</span>
  <span m='2517620'>time</span> <span m='2518070'>Fourier</span> <span m='2518550'>transform</span>
  <span m='2519570'>that</span> <span m='2519810'>looks</span> <span m='2520320'>just</span>
  <span m='2520740'>like</span> <span m='2521100'>the</span> <span m='2521190'>formula</span>
  <span m='2522000'>for</span> <span m='2522180'>the</span> <span m='2522300'>discrete</span>
  <span m='2522720'>time</span> <span m='2523080'>Fourier</span> <span m='2523440'>transform.</span>
  </p><p><span m='2526720'>The</span> <span m='2526910'>only</span> <span m='2527780'>difference</span>
  <span m='2528470'>in</span> <span m='2528590'>the</span> <span m='2528710'>two</span>
  <span m='2529400'>is</span> <span m='2529610'>that</span> <span m='2529760'>one</span>
  <span m='2530120'>has</span> <span m='2530330'>discrete</span> <span m='2530750'>domain,</span>
  <span m='2531200'>n.</span> <span m='2531800'>The</span> <span m='2531950'>other</span>
  <span m='2532160'>has</span> <span m='2532310'>continuous</span> <span m='2532820'>domain,</span>
  <span m='2533180'>time.</span> <span m='2534200'>And</span> <span m='2534350'>by</span>
  <span m='2534530'>sampling,</span> <span m='2535010'>we</span> <span m='2535130'>convert</span>
  <span m='2535700'>continuous</span> <span m='2536240'>domain,</span> <span m='2536570'>time,</span>
  <span m='2537020'>into</span> <span m='2537260'>discrete</span> <span m='2537620'>domain,</span>
  <span m='2538710'>n.</span> </p><p><span m='2539840'>So</span> <span m='2540020'>we're</span>
  <span m='2540200'>always</span> <span m='2540680'>going</span> <span m='2540920'>to</span>
  <span m='2541040'>end</span> <span m='2541250'>up</span> <span m='2541400'>with</span>
  <span m='2541520'>this</span> <span m='2541670'>relationship</span> <span m='2542810'>that</span>
  <span m='2542930'>the</span> <span m='2543050'>discrete</span> <span m='2543440'>frequency--</span>
  <span m='2544100'>that's</span> <span m='2545120'>generated</span> <span m='2545630'>by</span>
  <span m='2545780'>sampling--</span> <span m='2546770'>the</span> <span m='2546860'>discrete</span>
  <span m='2547190'>frequency</span> <span m='2547680'>is</span> <span m='2547790'>related</span>
  <span m='2548180'>to</span> <span m='2548330'>the</span> <span m='2548480'>continuous</span>
  <span m='2549020'>frequency</span> <span m='2549890'>multiplied</span> <span m='2550410'>by</span>
  <span m='2550610'>capital</span> <span m='2551110'>T.</span> <span m='2551320'>Capital</span>
  <span m='2551590'>T</span> <span m='2551930'>has</span> <span m='2552140'>the</span>
  <span m='2552190'>units</span> <span m='2552530'>of</span> <span m='2552620'>seconds.</span>
  <span m='2553970'>So</span> <span m='2554120'>that</span> <span m='2554300'>takes</span>
  <span m='2554720'>radians</span> <span m='2555170'>per</span> <span m='2555290'>second</span>
  <span m='2555840'>and</span> <span m='2555890'>turns</span> <span m='2556160'>it</span>
  <span m='2556250'>into</span> <span m='2556460'>radians.</span> </p><p><span m='2559080'>OK,</span>
  <span m='2560420'>almost</span> <span m='2560780'>done,</span> <span m='2562250'>one</span>
  <span m='2562550'>more.</span> <span m='2563840'>So</span> <span m='2564050'>I've</span>
  <span m='2564320'>gone</span> <span m='2564710'>from</span> <span m='2564950'>here</span>
  <span m='2565190'>to</span> <span m='2565310'>here.</span> <span m='2567860'>What</span>
  <span m='2568040'>happens</span> <span m='2568460'>if</span> <span m='2568550'>I</span>
  <span m='2568640'>do</span> <span m='2568820'>a</span> <span m='2568880'>periodic</span>
  <span m='2569420'>extension?</span> <span m='2569960'>The</span> <span m='2570080'>answer</span>
  <span m='2570470'>was</span> <span m='2571280'>that</span> <span m='2572090'>you</span>
  <span m='2572270'>convolve</span> <span m='2572690'>in</span> <span m='2572810'>time,</span>
  <span m='2573740'>which</span> <span m='2573920'>is the</span> <span m='2574040'>same</span>
  <span m='2574370'>as</span> <span m='2574460'>multiply</span> <span m='2575090'>in</span>
  <span m='2575270'>frequency</span> <span m='2576380'>by</span> <span m='2576920'>an</span>
  <span m='2577100'>impulse</span> <span m='2577550'>train,</span> <span m='2577880'>which</span>
  <span m='2578060'>is</span> <span m='2578180'>the</span> <span m='2578240'>same</span>
  <span m='2578510'>as</span> <span m='2578570'>sampling</span> <span m='2579230'>in</span>
  <span m='2579410'>frequency.</span> <span m='2581740'>Convolving</span> <span m='2582280'>time,</span>
  <span m='2582550'>sampling</span> <span m='2582940'>frequency.</span> <span m='2584200'>That's</span>
  <span m='2584410'>what</span> <span m='2584530'>happened</span> <span m='2584830'>when</span>
  <span m='2584980'>I</span> <span m='2585070'>did</span> <span m='2585400'>this</span>
  <span m='2585680'>one.</span> <span m='2586450'>I</span> <span m='2586690'>just</span>
  <span m='2586990'>now</span> <span m='2587290'>did</span> <span m='2587500'>this</span>
  <span m='2587740'>one.</span> </p><p><span m='2589270'>What</span> <span m='2589420'>happens</span>
  <span m='2589750'>if</span> <span m='2589840'>you</span> <span m='2589960'>sample</span>
  <span m='2590440'>in</span> <span m='2590560'>time?</span> <span m='2592910'>Sample</span>
  <span m='2593330'>in</span> <span m='2593470'>time</span> <span m='2593740'>is</span>
  <span m='2593860'>multiplied</span> <span m='2594370'>by</span> <span m='2594620'>an</span>
  <span m='2594740'>impulse</span> <span m='2595090'>train.</span> <span m='2597260'>Multiplied</span>
  <span m='2597760'>by</span> <span m='2597890'>an</span> <span m='2597950'>impulse</span>
  <span m='2598250'>train</span> <span m='2598480'>is</span> <span m='2598520'>the</span>
  <span m='2598580'>same</span> <span m='2598790'>as</span> <span m='2598880'>convolve</span>
  <span m='2599225'>in</span> <span m='2599570'>frequency.</span> <span m='2601880'>Convolve</span>
  <span m='2602160'>in</span> <span m='2602440'>frequency</span> <span m='2603400'>makes</span>
  <span m='2603670'>it</span> <span m='2603760'>periodic.</span> <span m='2605640'>Sample</span>
  <span m='2606080'>in</span> <span m='2606170'>time,</span> <span m='2606460'>periodic</span>
  <span m='2606910'>in</span> <span m='2607000'>frequency.</span> </p><p><span m='2608290'>The</span>
  <span m='2608410'>last</span> <span m='2608740'>example</span> <span m='2610300'>is</span>
  <span m='2610510'>just</span> <span m='2610720'>to</span> <span m='2610870'>do</span>
  <span m='2611050'>this</span> <span m='2611380'>direction.</span> <span m='2612620'>What</span>
  <span m='2612700'>happens</span> <span m='2613000'>if</span> <span m='2613090'>I</span>
  <span m='2613180'>take</span> <span m='2613420'>the</span> <span m='2613510'>DTFT</span>
  <span m='2615910'>and</span> <span m='2616030'>try</span> <span m='2616210'>to</span>
  <span m='2616330'>turn</span> <span m='2616600'>that</span> <span m='2616840'>into</span>
  <span m='2617110'>a</span> <span m='2617190'>DTFS?</span> <span m='2619300'>Not</span>
  <span m='2619540'>surprisingly,</span> <span m='2620110'>what</span> <span m='2620260'>I</span>
  <span m='2620320'>have</span> <span m='2620470'>to</span> <span m='2620560'>do</span>
  <span m='2620710'>is</span> <span m='2620830'>the</span> <span m='2620920'>same</span>
  <span m='2621130'>thing</span> <span m='2621310'>I</span> <span m='2621370'>did</span>
  <span m='2621550'>in</span> <span m='2621670'>continuous</span> <span m='2622150'>time.</span>
  <span m='2623110'>If</span> <span m='2623260'>I</span> <span m='2623320'>want</span>
  <span m='2623500'>to</span> <span m='2623560'>change</span> <span m='2623920'>this</span>
  <span m='2624250'>DT</span> <span m='2624700'>signal--</span> <span m='2625190'>which</span>
  <span m='2625270'>is</span> <span m='2625390'>aperiodic--</span> <span m='2626230'>into</span>
  <span m='2626500'>a</span> <span m='2626560'>periodic</span> <span m='2626845'>DT</span>
  <span m='2627430'>signal,</span> <span m='2628210'>I</span> <span m='2628330'>do</span>
  <span m='2628480'>periodic</span> <span m='2629020'>extension.</span> </p><p><span
  m='2631360'>I</span> <span m='2631480'>can</span> <span m='2631660'>think</span>
  <span m='2631840'>about</span> <span m='2632080'>the</span> <span m='2632170'>periodically-extended</span>
  <span m='2633510'>waveform,</span> <span m='2634090'>here</span> <span m='2634270'>extended</span>
  <span m='2634720'>by</span> <span m='2634870'>multiples</span> <span m='2635380'>of</span>
  <span m='2635550'>8,</span> <span m='2638280'>as</span> <span m='2638490'>being</span>
  <span m='2638850'>the</span> <span m='2638970'>original</span> <span m='2639450'>waveform</span>
  <span m='2639960'>convolved</span> <span m='2640530'>with</span> <span m='2640680'>that</span>
  <span m='2641580'>unit</span> <span m='2641970'>sample</span> <span m='2642920'>train.</span>
  <span m='2647120'>And</span> <span m='2647300'>so</span> <span m='2647600'>if</span>
  <span m='2647780'>I</span> <span m='2647930'>convolve</span> <span m='2648380'>by</span>
  <span m='2648530'>the</span> <span m='2648620'>unit</span> <span m='2648840'>sample</span>
  <span m='2649200'>train,</span> <span m='2650270'>what</span> <span m='2650420'>do</span>
  <span m='2650510'>I</span> <span m='2650570'>do</span> <span m='2650720'>in</span>
  <span m='2650810'>frequency?</span> <span m='2655320'>Convolve</span> <span m='2655920'>by</span>
  <span m='2656130'>unit</span> <span m='2656400'>sample</span> <span m='2656730'>train</span>
  <span m='2658110'>in</span> <span m='2658320'>time,</span> <span m='2659520'>gives</span>
  <span m='2659900'>[INAUDIBLE]</span> <span m='2660150'>and</span> <span m='2660310'>frequency.</span>
  </p><p><span m='2662590'>Multiply--</span> <span m='2663340'>so</span> <span m='2663490'>I'm</span>
  <span m='2663610'>expecting</span> <span m='2664180'>that</span> <span m='2664780'>the</span>
  <span m='2664900'>answer</span> <span m='2665230'>will</span> <span m='2665410'>be</span>
  <span m='2665530'>sampled,</span> <span m='2666220'>and</span> <span m='2666340'>that's</span>
  <span m='2666550'>what</span> <span m='2666670'>happens.</span> <span m='2668290'>So</span>
  <span m='2668410'>I</span> <span m='2668500'>take</span> <span m='2668950'>the</span>
  <span m='2670810'>Fourier</span> <span m='2671140'>transform</span> <span m='2672340'>of</span>
  <span m='2672550'>this</span> <span m='2672820'>case.</span> <span m='2674880'>Which,</span>
  <span m='2675090'>like</span> <span m='2675300'>all</span> <span m='2675510'>Fourier</span>
  <span m='2675840'>transforms,</span> <span m='2676800'>is</span> <span m='2678570'>periodic</span>
  <span m='2679050'>in 2</span> <span m='2679280'>pi.</span> </p><p><span m='2681860'>And</span>
  <span m='2682010'>now</span> <span m='2682250'>I</span> <span m='2682370'>think</span>
  <span m='2682610'>about</span> <span m='2683810'>convolving</span> <span m='2684530'>it</span>
  <span m='2684800'>with</span> <span m='2685100'>this</span> <span m='2686060'>unit</span>
  <span m='2686420'>sample</span> <span m='2686990'>train,</span> <span m='2689640'>which</span>
  <span m='2689850'>has</span> <span m='2690030'>the</span> <span m='2690150'>same</span>
  <span m='2690390'>relationship</span> <span m='2691180'>as</span> <span m='2691490'>the</span>
  <span m='2691680'>impulse</span> <span m='2692160'>train. And the</span> <span m='2692580'>impulse</span>
  <span m='2692970'>train--</span> <span m='2693300'>the</span> <span m='2694320'>train</span>
  <span m='2694950'>of</span> <span m='2695130'>impulses</span> <span m='2695610'>separated</span>
  <span m='2696090'>by</span> <span m='2696240'>capital</span> <span m='2696675'>T,</span>
  <span m='2697410'>turned</span> <span m='2697710'>into</span> <span m='2697950'>a</span>
  <span m='2698040'>train</span> <span m='2698370'>of</span> <span m='2698460'>impulses</span>
  <span m='2698880'>separated</span> <span m='2699270'>by</span> <span m='2699390'>2</span>
  <span m='2699540'>pi</span> <span m='2699780'>over</span> <span m='2700050'>t.</span>
  <span m='2701040'>Here</span> <span m='2701730'>separated</span> <span m='2702300'>by</span>
  <span m='2702780'>capital</span> <span m='2703320'>N,</span> <span m='2703980'>turns</span>
  <span m='2704340'>into</span> <span m='2705360'>impulse</span> <span m='2705750'>trains</span>
  <span m='2706080'>separated</span> <span m='2706530'>by</span> <span m='2706680'>2</span>
  <span m='2706860'>pi</span> <span m='2707190'>over</span> <span m='2707580'>n--</span>
  <span m='2708090'>same</span> <span m='2708330'>thing.</span> </p><p><span m='2710230'>So</span>
  <span m='2710490'>if</span> <span m='2710730'>this</span> <span m='2710910'>is</span>
  <span m='2711120'>8</span> <span m='2712080'>over</span> <span m='2712350'>here,</span>
  <span m='2713100'>I</span> <span m='2713220'>do</span> <span m='2713370'>2</span>
  <span m='2713580'>pi</span> <span m='2713820'>over</span> <span m='2714210'>8,</span>
  <span m='2714680'>which</span> <span m='2714830'>is</span> <span m='2714930'>pi</span>
  <span m='2715140'>over</span> <span m='2715320'>4.</span> <span m='2716850'>So</span>
  <span m='2717180'>convolving</span> <span m='2717960'>in</span> <span m='2718530'>discrete</span>
  <span m='2719070'>time</span> <span m='2720030'>is</span> <span m='2720240'>the</span>
  <span m='2720360'>same</span> <span m='2720780'>as</span> <span m='2721020'>multiplying</span>
  <span m='2722160'>by</span> <span m='2722370'>this</span> <span m='2722670'>impulse</span>
  <span m='2723150'>train,</span> <span m='2723840'>which</span> <span m='2724020'>gives</span>
  <span m='2724260'>me, then,</span> <span m='2724410'>a</span> <span m='2724890'>string</span>
  <span m='2725190'>of</span> <span m='2725310'>samples</span> <span m='2728530'>from</span>
  <span m='2728770'>that</span> <span m='2728980'>waveform.</span> <span m='2729410'>So</span>
  <span m='2729550'>the</span> <span m='2729670'>effect</span> <span m='2730000'>of</span>
  <span m='2730090'>going</span> <span m='2730330'>this</span> <span m='2730540'>way,</span>
  <span m='2731300'>which</span> <span m='2731410'>is</span> <span m='2731500'>periodic</span>
  <span m='2732040'>extension,</span> <span m='2732680'>which</span> <span m='2732760'>is</span>
  <span m='2732910'>the</span> <span m='2733000'>same</span> <span m='2733240'>as</span>
  <span m='2733330'>convolving</span> <span m='2733960'>in</span> <span m='2734080'>time,</span>
  <span m='2734860'>is</span> <span m='2735220'>sampling</span> <span m='2735820'>in</span>
  <span m='2735920'>frequency.</span> </p><p><span m='2738410'>OK,</span> <span m='2738720'>so</span>
  <span m='2739530'>the</span> <span m='2739680'>idea,</span> <span m='2740010'>then,</span>
  <span m='2740310'>is</span> <span m='2740540'>that</span> <span m='2740630'>that's</span>
  <span m='2740820'>a</span> <span m='2740940'>way</span> <span m='2741180'>of</span>
  <span m='2741300'>rationalizing</span> <span m='2742530'>how</span> <span m='2742710'>the</span>
  <span m='2742860'>Fourier</span> <span m='2743330'>series</span> <span m='2743820'>would</span>
  <span m='2744000'>have</span> <span m='2744090'>worked.</span> <span m='2746970'>So</span>
  <span m='2747120'>the</span> <span m='2747270'>Fourier</span> <span m='2747580'>series</span>
  <span m='2748020'>was</span> <span m='2748200'>a</span> <span m='2748260'>discrete</span>
  <span m='2748650'>set</span> <span m='2748860'>of</span> <span m='2748980'>numbers</span>
  <span m='2749400'>exactly</span> <span m='2750030'>for</span> <span m='2750210'>that</span>
  <span m='2750390'>reason.</span> <span m='2751720'>I</span> <span m='2751740'>started</span>
  <span m='2752100'>out</span> <span m='2752280'>with</span> <span m='2752400'>something</span>
  <span m='2752730'>that</span> <span m='2752850'>was</span> <span m='2752970'>continuous</span>
  <span m='2753510'>in</span> <span m='2753630'>frequency,</span> <span m='2754140'>but</span>
  <span m='2754320'>I</span> <span m='2754450'>sampled</span> <span m='2755010'>it</span>
  <span m='2756030'>because</span> <span m='2756330'>I</span> <span m='2756420'>was</span>
  <span m='2756570'>multiplying</span> <span m='2758040'>by</span> <span m='2759210'>an</span>
  <span m='2759500'>impulse train.</span> </p><p><span m='2762440'>So</span> <span
  m='2764480'>what</span> <span m='2764690'>I</span> <span m='2764750'>hope</span>
  <span m='2765020'>this</span> <span m='2765230'>did,</span> <span m='2765910'>OK,</span>
  <span m='2766910'>was</span> <span m='2767210'>dragged</span> <span m='2767540'>you</span>
  <span m='2767660'>through</span> <span m='2767810'>a</span> <span m='2767870'>couple</span>
  <span m='2768080'>of</span> <span m='2768200'>examples</span> <span m='2768740'>that</span>
  <span m='2768860'>will</span> <span m='2768950'>make</span> <span m='2769130'>things</span>
  <span m='2769340'>a</span> <span m='2769370'>little</span> <span m='2769520'>bit</span>
  <span m='2769610'>easier</span> <span m='2769910'>tomorrow.</span> <span m='2771770'>But</span>
  <span m='2771920'>I</span> <span m='2771980'>also</span> <span m='2772190'>hope</span>
  <span m='2772370'>that</span> <span m='2772490'>you</span> <span m='2772550'>understand</span>
  <span m='2773000'>how</span> <span m='2773570'>we</span> <span m='2773720'>went</span>
  <span m='2773930'>from</span> <span m='2774140'>a</span> <span m='2774260'>diagram</span>
  <span m='2774920'>that</span> <span m='2775040'>looks</span> <span m='2775280'>kind</span>
  <span m='2775490'>of</span> <span m='2776480'>complicated</span> <span m='2777230'>an</span>
  <span m='2777320'>arbitrary--</span> <span m='2778310'>here</span> <span m='2778520'>we</span>
  <span m='2778620'>had</span> <span m='2778890'>DT</span> <span m='2779660'>on</span>
  <span m='2779780'>the</span> <span m='2779870'>top</span> <span m='2780140'>and</span>
  <span m='2780230'>CT</span> <span m='2780590'>on</span> <span m='2780680'>the</span>
  <span m='2780770'>bottom,</span> <span m='2781490'>periodic</span> <span m='2782030'>on</span>
  <span m='2782150'>the</span> <span m='2782240'>left</span> <span m='2782570'>and</span>
  <span m='2782780'>not</span> <span m='2783050'>periodic</span> <span m='2783560'>on</span>
  <span m='2783650'>the</span> <span m='2783770'>right.</span> </p><p><span m='2785640'>The</span>
  <span m='2785690'>transforms</span> <span m='2786290'>had</span> <span m='2786500'>all</span>
  <span m='2786650'>that</span> <span m='2786770'>things</span> <span m='2787240'>turn</span>
  <span m='2787560'>90</span> <span m='2787910'>degrees.</span> <span m='2788930'>We</span>
  <span m='2789110'>ended</span> <span m='2789350'>up</span> <span m='2789500'>with</span>
  <span m='2789650'>discrete</span> <span m='2790160'>on</span> <span m='2790280'>the</span>
  <span m='2790400'>left</span> <span m='2790760'>instead</span> <span m='2791060'>of</span>
  <span m='2791150'>on</span> <span m='2791270'>the</span> <span m='2791360'>top,</span>
  <span m='2793760'>and</span> <span m='2793880'>we</span> <span m='2794030'>ended</span>
  <span m='2794330'>up</span> <span m='2794570'>with</span> <span m='2794840'>periodic</span>
  <span m='2795770'>in</span> <span m='2795980'>the</span> <span m='2796100'>top</span>
  <span m='2796790'>rather</span> <span m='2797090'>than</span> <span m='2797270'>on</span>
  <span m='2797420'>the</span> <span m='2797510'>left.</span> <span m='2799260'>And</span>
  <span m='2799280'>that's</span> <span m='2799460'>entirely</span> <span m='2800480'>because</span>
  <span m='2800840'>of</span> <span m='2800900'>the</span> <span m='2800990'>relationships</span>
  <span m='2806180'>between</span> <span m='2806540'>the</span> <span m='2806630'>various</span>
  <span m='2806930'>Fourier</span> <span m='2807200'>transforms.</span> </p><p><span
  m='2808460'>So</span> <span m='2808670'>the</span> <span m='2808850'>idea</span>
  <span m='2809390'>is--</span> <span m='2810080'>and</span> <span m='2810200'>you</span>
  <span m='2810290'>can</span> <span m='2810410'>understand</span> <span m='2810770'>all</span>
  <span m='2811070'>of those</span> <span m='2811190'>relationships</span> <span m='2811730'>by</span>
  <span m='2811880'>simply</span> <span m='2812390'>thinking</span> <span m='2812780'>about</span>
  <span m='2812990'>impulse</span> <span m='2813380'>trains.</span> <span m='2814880'>We</span>
  <span m='2815000'>take</span> <span m='2815300'>an</span> <span m='2815660'>aperiodic</span>
  <span m='2816230'>signal,</span> <span m='2816530'>turn it</span> <span m='2816770'>into</span>
  <span m='2816950'>a</span> <span m='2816980'>periodic</span> <span m='2817810'>by</span>
  <span m='2818030'>convolution</span> <span m='2818660'>in</span> <span m='2818750'>time,</span>
  <span m='2819110'>which</span> <span m='2819290'>is the</span> <span m='2819390'>same</span>
  <span m='2819620'>as</span> <span m='2819710'>multiplying</span> <span m='2820190'>frequency,</span>
  <span m='2820610'>which is the</span> <span m='2820760'>same</span> <span m='2820970'>as</span>
  <span m='2821030'>sampling.</span> </p><p><span m='2823570'>We</span> <span m='2823780'>sample</span>
  <span m='2824200'>in</span> <span m='2824320'>time</span> <span m='2824570'>by</span>
  <span m='2824710'>multiplying</span> <span m='2825310'>by</span> <span m='2825450'>an</span>
  <span m='2825560'>impulse</span> <span m='2825860'>train,</span> <span m='2826280'>which</span>
  <span m='2826570'>is</span> <span m='2826690'>the</span> <span m='2826780'>same</span>
  <span m='2827020'>as</span> <span m='2827110'>convolving</span> <span m='2827600'>in</span>
  <span m='2827690'>frequency,</span> <span m='2828340'>which</span> <span m='2828550'>makes</span>
  <span m='2828730'>it</span> <span m='2828790'>periodic.</span> <span m='2830530'>So</span>
  <span m='2830680'>the</span> <span m='2830800'>hope</span> <span m='2831040'>is</span>
  <span m='2831520'>that</span> <span m='2831670'>this</span> <span m='2832390'>looks</span>
  <span m='2832570'>like</span> <span m='2832780'>more</span> <span m='2832960'>than</span>
  <span m='2833110'>just--</span> <span m='2835360'>1, 2,</span> <span m='2835768'>3,
  4,</span> <span m='2836176'>5, 6,</span> <span m='2836584'>7, 8--</span> <span m='2836992'>eight</span>
  <span m='2837400'>independent</span> <span m='2837940'>equations,</span> <span m='2838450'>they're</span>
  <span m='2838570'>not.</span> </p><p><span m='2840000'>It's</span> <span m='2840310'>really</span>
  <span m='2841180'>two</span> <span m='2841630'>equations--</span> <span m='2842590'>the</span>
  <span m='2842840'>transform</span> <span m='2843280'>and</span> <span m='2843370'>the</span>
  <span m='2843460'>inverse</span> <span m='2843730'>transform--</span> <span m='2844130'>and</span>
  <span m='2844210'>they're</span> <span m='2844510'>almost</span> <span m='2844900'>the</span>
  <span m='2844990'>same</span> <span m='2845230'>equation,</span> <span m='2847710'>except</span>
  <span m='2848030'>for</span> <span m='2848570'>taking</span> <span m='2848900'>into</span>
  <span m='2849110'>account</span> <span m='2849440'>the</span> <span m='2849530'>special</span>
  <span m='2849860'>properties</span> <span m='2850250'>of</span> <span m='2850310'>the</span>
  <span m='2850430'>different</span> <span m='2850670'>domains.</span> <span m='2851950'>OK,</span>
  <span m='2852830'>have</span> <span m='2852950'>a</span> <span m='2852980'>good</span>
  <span m='2853130'>time,</span> <span m='2853850'>and</span> <span m='2854150'>see</span>
  <span m='2854420'>you</span> <span m='2854630'>tomorrow.</span> </p>
type: course
uid: b337e541707d5aefb6a1cc3b98184d53

---
None