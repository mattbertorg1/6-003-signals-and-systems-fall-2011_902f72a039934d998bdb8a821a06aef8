---
about_this_resource_text: <p><strong>Instructor:</strong> Dennis Freeman</p> <p><strong>Description:</strong>
  Building on concepts from the previous lecture, the Laplace transform is introduced
  as the continuous-time analogue of the Z transform. The lecture discusses the Laplace
  transform's definition, properties, applications, and inverse transform.</p>
course_id: 6-003-signals-and-systems-fall-2011
embedded_media:
- id: Video-YouTube-Stream
  media_location: MRy8xxvsZA4
  parent_uid: b07bd25e99c61fa163548ac901a0b605
  title: Video-YouTube-Stream
  type: Video
  uid: 4307ea6e348eadb83ac691da8762be7e
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/MRy8xxvsZA4/default.jpg
  parent_uid: b07bd25e99c61fa163548ac901a0b605
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 4d322725059c86120c38269713a62557
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/lecture-6-laplace-transform/id602305810?i=132453947
  parent_uid: b07bd25e99c61fa163548ac901a0b605
  title: Video-iTunes U-MP4
  type: Video
  uid: ff55c22f02166fb9e6c6d10469de123c
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.003F11/MIT6_003F11_lec06_300k.mp4
  parent_uid: b07bd25e99c61fa163548ac901a0b605
  title: Video-Internet Archive-MP4
  type: Video
  uid: b9c7523cd3cf3978088c6897f704b82c
- id: 3Play-3PlayYouTubeid-MP4
  media_location: MRy8xxvsZA4
  parent_uid: b07bd25e99c61fa163548ac901a0b605
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: dbf0dcebe9d7f1c24b77720b30ae20ff
- id: MRy8xxvsZA4.srt
  parent_uid: b07bd25e99c61fa163548ac901a0b605
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-6-laplace-transform/MRy8xxvsZA4.srt
  title: 3play caption file
  type: null
  uid: 09704df18db6799f5b08d83ddc07cd4b
- id: MRy8xxvsZA4.pdf
  parent_uid: b07bd25e99c61fa163548ac901a0b605
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-6-laplace-transform/MRy8xxvsZA4.pdf
  title: 3play pdf file
  type: null
  uid: adfeeefadde13d524dcd075e65a4be0b
- id: Caption-3Play YouTube id-SRT
  parent_uid: b07bd25e99c61fa163548ac901a0b605
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 254b6fb56d37b5416e0a1d886e6ac5dd
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b07bd25e99c61fa163548ac901a0b605
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f9a1318c711c284c8225eb18250784c9
inline_embed_id: 72030408lecture6:laplacetransform15319008
layout: video
order_index: null
parent_uid: 47b07fedf3a30be25f155f62399cdb59
related_resources_text: ''
short_url: lecture-6-laplace-transform
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/lecture-videos/lecture-6-laplace-transform
template_type: Tabbed
title: 'Lecture 6: Laplace Transform'
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
  <span m='17430'>ocw.mit.edu.</span> </p><p><span m='21970'>DENNIS FREEMAN:</span>
  <span m='22120'>So</span> <span m='22270'>today</span> <span m='23800'>the</span>
  <span m='24040'>idea</span> <span m='24790'>is</span> <span m='25030'>to</span>
  <span m='25150'>think</span> <span m='25360'>about</span> <span m='25720'>CT</span>
  <span m='26140'>systems</span> <span m='26650'>in</span> <span m='26770'>exactly</span>
  <span m='27220'>the</span> <span m='27340'>same</span> <span m='27550'>way</span>
  <span m='27880'>that</span> <span m='28000'>we</span> <span m='28120'>thought</span>
  <span m='28300'>about</span> <span m='28570'>DT</span> <span m='28900'>systems</span>
  <span m='29290'>last</span> <span m='29540'>time.</span> <span m='31960'>For</span>
  <span m='32170'>the</span> <span m='32290'>past</span> <span m='32560'>couple</span>
  <span m='32830'>of</span> <span m='32890'>weeks,</span> <span m='33260'>we've</span>
  <span m='33310'>been</span> <span m='33460'>looking</span> <span m='33790'>at</span>
  <span m='33940'>many</span> <span m='34270'>representations</span> <span m='35290'>of</span>
  <span m='35500'>both</span> <span m='35800'>CT</span> <span m='36320'>and</span>
  <span m='36666'>DT</span> <span m='37012'>systems.</span> <span m='37360'>Last</span>
  <span m='37660'>lecture</span> <span m='39670'>we</span> <span m='39790'>made</span>
  <span m='40000'>a</span> <span m='40060'>picture</span> <span m='41110'>of</span>
  <span m='41260'>a</span> <span m='41320'>bunch</span> <span m='41620'>of</span>
  <span m='41680'>different</span> <span m='41950'>ways</span> <span m='42250'>to</span>
  <span m='42370'>think</span> <span m='42520'>about</span> <span m='42760'>DT</span>
  <span m='43090'>systems</span> <span m='43510'>and</span> <span m='43600'>we</span>
  <span m='43690'>tried</span> <span m='43960'>to</span> <span m='44050'>think</span>
  <span m='44200'>about</span> <span m='44470'>relations</span> <span m='44950'>between</span>
  <span m='45340'>them.</span> <span m='47610'>The</span> <span m='47860'>new</span>
  <span m='48130'>thing</span> <span m='48400'>from</span> <span m='48550'>last</span>
  <span m='48780'>time</span> <span m='49000'>was</span> <span m='49150'>this</span>
  <span m='49300'>idea</span> <span m='49690'>of</span> <span m='49870'>a</span> <span
  m='49890'>z</span> <span m='50110'>transform,</span> <span m='50800'>which</span>
  <span m='50980'>formally</span> <span m='51880'>is</span> <span m='52090'>the</span>
  <span m='52210'>link</span> <span m='52480'>between</span> <span m='52810'>a</span>
  <span m='52870'>system</span> <span m='53200'>function,</span> <span m='54130'>a</span>
  <span m='54190'>function</span> <span m='54580'>of</span> <span m='54640'>z,</span>
  <span m='55630'>and</span> <span m='55720'>a</span> <span m='55780'>unit</span>
  <span m='56020'>sample</span> <span m='56380'>response,</span> <span m='57355'>a</span>
  <span m='57610'>function</span> <span m='58000'>of</span> <span m='58090'>n.</span>
  <span m='60870'>We</span> <span m='60990'>showed</span> <span m='61230'>last</span>
  <span m='61470'>time</span> <span m='61740'>that</span> <span m='61830'>because</span>
  <span m='62190'>we</span> <span m='62310'>already</span> <span m='62640'>understand</span>
  <span m='63060'>a</span> <span m='63090'>whole</span> <span m='63240'>lot</span>
  <span m='63450'>of</span> <span m='63540'>these</span> <span m='63690'>other</span>
  <span m='63900'>connections</span> <span m='64800'>that</span> <span m='65040'>connection</span>
  <span m='65550'>is</span> <span m='65670'>very</span> <span m='65940'>straightforward.</span>
  </p><p><span m='68630'>What</span> <span m='68650'>we're</span> <span m='68740'>going</span>
  <span m='68860'>to</span> <span m='68920'>do</span> <span m='69040'>today</span>
  <span m='69400'>is</span> <span m='69520'>precisely</span> <span m='70000'>the</span>
  <span m='70090'>same</span> <span m='70330'>thing</span> <span m='70540'>for</span>
  <span m='70680'>CT.</span> <span m='73150'>The</span> <span m='73390'>boxes</span>
  <span m='74380'>barely</span> <span m='74860'>changed.</span> <span m='75770'>You</span>
  <span m='75790'>should</span> <span m='75970'>see</span> <span m='76150'>the</span>
  <span m='76270'>relationship</span> <span m='76840'>immediately</span> <span m='77350'>between</span>
  <span m='77680'>the</span> <span m='77740'>former</span> <span m='78040'>set</span>
  <span m='78190'>of</span> <span m='78280'>boxes</span> <span m='78640'>and</span>
  <span m='78760'>this</span> <span m='78880'>set</span> <span m='79060'>of</span>
  <span m='79150'>boxes.</span> <span m='83200'>And</span> <span m='83910'>we'll</span>
  <span m='84040'>do</span> <span m='84220'>a</span> <span m='84280'>very</span> <span
  m='84550'>similar</span> <span m='84940'>thing.</span> <span m='85750'>We'll</span>
  <span m='85930'>look</span> <span m='86110'>at</span> <span m='86200'>a</span> <span
  m='86260'>relationship</span> <span m='86770'>between</span> <span m='87040'>the</span>
  <span m='87460'>system</span> <span m='87790'>function,</span> <span m='88180'>which</span>
  <span m='88360'>is</span> <span m='88450'>a</span> <span m='88510'>function</span>
  <span m='88810'>of</span> <span m='88900'>s,</span> <span m='90280'>and</span> <span
  m='90550'>the</span> <span m='90820'>impulse</span> <span m='91240'>response,</span>
  <span m='91760'>which</span> <span m='91840'>is</span> <span m='91990'>a</span>
  <span m='92050'>function</span> <span m='92380'>of</span> <span m='92470'>t.</span>
  <span m='93820'>We'll</span> <span m='93930'>look</span> <span m='94090'>at</span>
  <span m='94180'>that</span> <span m='94330'>similar</span> <span m='94690'>function</span>
  <span m='95050'>for</span> <span m='95200'>CT,</span> <span m='95980'>the</span>
  <span m='96100'>thing</span> <span m='96340'>that's</span> <span m='96490'>analogous</span>
  <span m='97000'>to</span> <span m='97120'>the</span> <span m='97210'>z</span> <span
  m='97390'>transform</span> <span m='97900'>in</span> <span m='98200'>DT.</span>
  </p><p><span m='99100'>So</span> <span m='99600'>Laplace</span> <span m='99940'>transform,</span>
  <span m='101560'>just</span> <span m='101860'>like</span> <span m='102130'>in</span>
  <span m='102460'>DT</span> <span m='102790'>where it</span> <span m='102850'>maps</span>
  <span m='103440'>a</span> <span m='103520'>function</span> <span m='103840'>of</span>
  <span m='103960'>time</span> <span m='104260'>to</span> <span m='104380'>a</span>
  <span m='104440'>function</span> <span m='104800'>of</span> <span m='104890'>z,</span>
  <span m='105360'>here</span> <span m='105760'>it maps</span> <span m='106070'>a</span>
  <span m='106120'>function</span> <span m='106450'>of</span> <span m='106540'>time,</span>
  <span m='107990'>which</span> <span m='108100'>in</span> <span m='108370'>CT</span>
  <span m='108640'>we'll</span> <span m='108790'>write</span> <span m='109000'>that</span>
  <span m='109240'>way.</span> <span m='109840'>It</span> <span m='109990'>maps</span>
  <span m='110320'>that</span> <span m='110560'>to</span> <span m='110710'>a</span>
  <span m='110800'>function</span> <span m='112810'>of</span> <span m='112990'>s.</span>
  <span m='114100'>So</span> <span m='114340'>s</span> <span m='114580'>is</span>
  <span m='114700'>going</span> <span m='114820'>to</span> <span m='114880'>be</span>
  <span m='114970'>something</span> <span m='115360'>like</span> <span m='117010'>x</span>
  <span m='117250'>of</span> <span m='117370'>t</span> <span m='121564'>e</span> <span
  m='122017'>to the</span> <span m='122470'>minus</span> <span m='122830'>st</span>
  <span m='122970'>dt.</span> </p><p><span m='124750'>So</span> <span m='124900'>the</span>
  <span m='125020'>idea</span> <span m='125230'>is</span> <span m='125320'>going</span>
  <span m='125560'>to</span> <span m='125650'>be</span> <span m='125800'>that</span>
  <span m='125950'>this</span> <span m='126130'>was</span> <span m='126250'>a</span>
  <span m='126280'>function</span> <span m='126640'>of</span> <span m='126700'>time.</span>
  <span m='127000'>This</span> <span m='127120'>is</span> <span m='127210'>only</span>
  <span m='127480'>a</span> <span m='127540'>function</span> <span m='127870'>of</span>
  <span m='127960'>s.</span> <span m='128479'>We</span> <span m='128560'>get</span>
  <span m='128770'>the</span> <span m='128889'>function</span> <span m='129190'>of</span>
  <span m='129280'>s</span> <span m='129430'>by</span> <span m='129580'>integrating</span>
  <span m='130090'>some</span> <span m='130300'>function</span> <span m='130630'>of</span>
  <span m='130750'>time,</span> <span m='131410'>but</span> <span m='131530'>we</span>
  <span m='131680'>integrate</span> <span m='132010'>time</span> <span m='132310'>out</span>
  <span m='132610'>so</span> <span m='132700'>time</span> <span m='132910'>disappears.</span>
  <span m='134390'>So</span> <span m='134440'>the</span> <span m='134560'>idea</span>
  <span m='134890'>then</span> <span m='135100'>is</span> <span m='135250'>that</span>
  <span m='135340'>we</span> <span m='135490'>end</span> <span m='135670'>up</span>
  <span m='135820'>with</span> <span m='135970'>a</span> <span m='136030'>map</span>
  <span m='136780'>linking</span> <span m='137110'>a</span> <span m='137170'>function</span>
  <span m='137500'>of</span> <span m='137590'>time</span> <span m='137920'>to</span>
  <span m='138040'>a</span> <span m='138070'>function</span> <span m='138900'>of</span>
  <span m='139570'>s.</span> </p><p><span m='141940'>Presumably</span> <span m='142510'>you've</span>
  <span m='142660'>seen</span> <span m='142900'>this</span> <span m='143050'>before.</span>
  <span m='144080'>This</span> <span m='144160'>is</span> <span m='144250'>a</span>
  <span m='144310'>topic</span> <span m='144670'>in</span> <span m='144790'>1803.</span>
  <span m='147860'>Smile.</span> <span m='149060'>Nod</span> <span m='149360'>your</span>
  <span m='149450'>head.</span> <span m='149900'>Make</span> <span m='150110'>me</span>
  <span m='150230'>feel</span> <span m='150470'>like</span> <span m='150770'>I'm</span>
  <span m='150950'>connecting</span> <span m='151430'>to</span> <span m='151580'>you,</span>
  <span m='151730'>right.</span> <span m='152090'>Right,</span> <span m='152350'>so</span>
  <span m='152450'>you've</span> <span m='152630'>all</span> <span m='152780'>seen</span>
  <span m='153200'>this</span> <span m='153350'>before.</span> <span m='153960'>Nothing's</span>
  <span m='154250'>new.</span> </p><p><span m='155180'>Actually</span> <span m='155540'>there</span>
  <span m='155690'>is</span> <span m='155810'>one</span> <span m='156140'>tiny</span>
  <span m='156560'>thing</span> <span m='156800'>that's</span> <span m='156980'>new.</span>
  <span m='157640'>In</span> <span m='157790'>1803</span> <span m='158420'>they</span>
  <span m='158570'>use</span> <span m='158750'>a</span> <span m='158810'>variant</span>
  <span m='159290'>of the</span> <span m='159400'>Laplace</span> <span m='159770'>transform</span>
  <span m='160310'>that</span> <span m='160430'>we</span> <span m='160610'>will</span>
  <span m='160760'>call</span> <span m='161030'>the</span> <span m='161150'>unilateral</span>
  <span m='162440'>Laplace</span> <span m='162800'>transform,</span> <span m='163670'>which</span>
  <span m='163850'>means</span> <span m='164090'>they</span> <span m='164240'>started</span>
  <span m='164570'>their</span> <span m='164720'>integrals</span> <span m='165110'>at</span>
  <span m='165170'>0.</span> <span m='167990'>For</span> <span m='168200'>reasons</span>
  <span m='168650'>that</span> <span m='168740'>will</span> <span m='168840'>be</span>
  <span m='169040'>clear</span> <span m='169550'>at</span> <span m='169670'>the</span>
  <span m='169790'>very</span> <span m='170240'>end</span> <span m='170390'>of</span>
  <span m='170450'>the</span> <span m='170570'>course,</span> <span m='170930'>when</span>
  <span m='171080'>we</span> <span m='171200'>do</span> <span m='171470'>Fourier</span>
  <span m='172070'>transforms</span> <span m='174840'>to</span> <span m='174990'>make</span>
  <span m='175200'>the</span> <span m='175290'>transition</span> <span m='175890'>between</span>
  <span m='176250'>this</span> <span m='176430'>kind</span> <span m='176670'>of</span>
  <span m='176760'>a</span> <span m='176790'>transform</span> <span m='177130'>and</span>
  <span m='177360'>a</span> <span m='177480'>Fourier</span> <span m='177840'>transform</span>
  <span m='178380'>easier</span> <span m='180430'>we</span> <span m='180540'>will</span>
  <span m='180690'>do</span> <span m='180870'>something</span> <span m='181200'>called</span>
  <span m='181390'>a</span> <span m='181440'>bilateral</span> <span m='182070'>transform.</span>
  <span m='183930'>The</span> <span m='184020'>only</span> <span m='184290'>difference</span>
  <span m='184650'>being</span> <span m='185010'>that</span> <span m='185400'>we</span>
  <span m='185550'>will</span> <span m='185670'>start</span> <span m='185970'>our</span>
  <span m='186150'>integrals</span> <span m='186540'>at</span> <span m='186630'>minus</span>
  <span m='186930'>infinity.</span> </p><p><span m='189040'>There</span> <span m='189210'>are</span>
  <span m='189540'>subtle</span> <span m='190080'>differences</span> <span m='190620'>between</span>
  <span m='190980'>those</span> <span m='191220'>two</span> <span m='191430'>transforms.</span>
  <span m='193650'>Rest</span> <span m='193950'>assured,</span> <span m='194400'>that</span>
  <span m='194550'>the</span> <span m='194670'>big</span> <span m='194850'>picture</span>
  <span m='195240'>is</span> <span m='195390'>identical.</span> <span m='198360'>And</span>
  <span m='198720'>when</span> <span m='198960'>there</span> <span m='199170'>is</span>
  <span m='199410'>an</span> <span m='199500'>important</span> <span m='199890'>difference</span>
  <span m='200880'>we</span> <span m='201150'>will</span> <span m='201390'>point</span>
  <span m='201630'>that</span> <span m='201810'>out.</span> <span m='203740'>So</span>
  <span m='203970'>for</span> <span m='204270'>the</span> <span m='204480'>rest</span>
  <span m='204870'>of</span> <span m='204990'>today</span> <span m='205500'>and</span>
  <span m='205650'>for</span> <span m='205800'>the</span> <span m='205950'>rest</span>
  <span m='206310'>of</span> <span m='206430'>two</span> <span m='206670'>weeks</span>
  <span m='207030'>I</span> <span m='207140'>will</span> <span m='207300'>only</span>
  <span m='207630'>talk</span> <span m='207880'>about</span> <span m='208110'>bilateral</span>
  <span m='208740'>transforms,</span> <span m='209520'>the</span> <span m='209640'>kind</span>
  <span m='209910'>that</span> <span m='210300'>we</span> <span m='210670'>integrate</span>
  <span m='210840'>over</span> <span m='211110'>all</span> <span m='211290'>of</span>
  <span m='211410'>time.</span> </p><p><span m='214690'>And</span> <span m='214750'>the</span>
  <span m='214810'>easiest</span> <span m='215200'>way</span> <span m='215380'>I</span>
  <span m='215470'>know</span> <span m='215620'>to</span> <span m='215710'>get</span>
  <span m='215860'>started</span> <span m='216310'>is</span> <span m='216430'>to</span>
  <span m='216550'>just</span> <span m='216760'>try</span> <span m='217060'>some,</span>
  <span m='217570'>right.</span> <span m='218050'>You</span> <span m='218200'>could</span>
  <span m='218500'>study</span> <span m='219010'>properties</span> <span m='219670'>of</span>
  <span m='219760'>the</span> <span m='219880'>math.</span> <span m='220570'>That's</span>
  <span m='220780'>probably</span> <span m='221200'>the</span> <span m='221290'>way</span>
  <span m='221440'>it</span> <span m='221500'>was</span> <span m='221650'>studied</span>
  <span m='221980'>in</span> <span m='222070'>1803.</span> <span m='222750'>I</span>
  <span m='222850'>find</span> <span m='223060'>it</span> <span m='223180'>easier</span>
  <span m='225390'>to</span> <span m='225510'>develop</span> <span m='226170'>some</span>
  <span m='226350'>intuition</span> <span m='226920'>for</span> <span m='227070'>what's</span>
  <span m='227250'>going</span> <span m='227490'>on</span> <span m='227700'>here</span>
  <span m='228200'>by</span> <span m='228330'>just</span> <span m='228510'>doing</span>
  <span m='228870'>some.</span> </p><p><span m='230760'>So</span> <span m='230970'>here's</span>
  <span m='231180'>probably</span> <span m='231570'>the</span> <span m='231690'>simplest</span>
  <span m='232170'>Laplace</span> <span m='232500'>transform</span> <span m='232980'>we'll</span>
  <span m='233310'>look</span> <span m='233580'>at.</span> <span m='235140'>What's</span>
  <span m='235410'>the</span> <span m='235530'>Laplace</span> <span m='235920'>transform</span>
  <span m='236490'>of</span> <span m='237480'>a</span> <span m='237570'>function</span>
  <span m='238080'>of</span> <span m='238260'>time</span> <span m='239220'>that</span>
  <span m='239390'>exponentially</span> <span m='240090'>decays</span> <span m='240750'>with</span>
  <span m='240990'>positive</span> <span m='241500'>time</span> <span m='241800'>in</span>
  <span m='241900'>a</span> <span m='241980'>0</span> <span m='242370'>for</span>
  <span m='242550'>time</span> <span m='243000'>less</span> <span m='243210'>than</span>
  <span m='243340'>0?</span> <span m='246000'>As</span> <span m='246180'>you</span>
  <span m='246300'>might</span> <span m='246510'>expect,</span> <span m='247410'>the</span>
  <span m='247500'>first</span> <span m='247740'>transform</span> <span m='248220'>we'll</span>
  <span m='248370'>do</span> <span m='249000'>involve</span> <span m='249390'>simply</span>
  <span m='250020'>plugging</span> <span m='250500'>that</span> <span m='251070'>mathematical</span>
  <span m='251850'>formula</span> <span m='252420'>into</span> <span m='252800'>the</span>
  <span m='253030'>definition.</span> <span m='254890'>So</span> <span m='255210'>the</span>
  <span m='256529'>x of</span> <span m='256919'>s,</span> <span m='257310'>the</span>
  <span m='257430'>Laplace</span> <span m='257790'>transform,</span> <span m='258240'>is</span>
  <span m='258390'>always</span> <span m='258899'>the</span> <span m='259019'>function</span>
  <span m='259350'>of</span> <span m='259440'>time</span> <span m='259860'>integrated</span>
  <span m='260430'>against</span> <span m='260760'>e</span> <span m='260910'>to</span>
  <span m='260970'>the</span> <span m='261060'>minus</span> <span m='261360'>st.</span>
  </p><p><span m='263370'>We're</span> <span m='263610'>only</span> <span m='263910'>doing</span>
  <span m='264220'>bilateral</span> <span m='264990'>but</span> <span m='265230'>notice</span>
  <span m='265680'>that</span> <span m='265950'>the</span> <span m='266070'>0</span>
  <span m='267060'>for</span> <span m='267280'>t</span> <span m='267510'>less</span>
  <span m='267780'>than</span> <span m='267930'>0</span> <span m='268290'>cuts</span>
  <span m='268560'>off</span> <span m='268800'>the</span> <span m='268890'>bottom.</span>
  <span m='269460'>So</span> <span m='269580'>in</span> <span m='269670'>fact,</span>
  <span m='269910'>you</span> <span m='270060'>would get</span> <span m='270210'>the</span>
  <span m='270300'>same</span> <span m='270540'>answer</span> <span m='271230'>if</span>
  <span m='271380'>you</span> <span m='271440'>did</span> <span m='271620'>bilateral</span>
  <span m='272220'>or</span> <span m='272430'>unilateral.</span> <span m='275760'>And</span>
  <span m='275910'>then</span> <span m='276060'>we're</span> <span m='276210'>left</span>
  <span m='276450'>with</span> <span m='279210'>running</span> <span m='279510'>this</span>
  <span m='279750'>integral</span> <span m='280170'>over</span> <span m='280380'>infinite</span>
  <span m='280800'>time</span> <span m='281850'>this</span> <span m='282090'>kind</span>
  <span m='282360'>of</span> <span m='282420'>a</span> <span m='282480'>function,</span>
  <span m='283410'>which</span> <span m='283590'>comes</span> <span m='283800'>out</span>
  <span m='283950'>looking</span> <span m='284250'>like</span> <span m='284490'>this.</span>
  <span m='285880'>The</span> <span m='285960'>only</span> <span m='286200'>tricky</span>
  <span m='286590'>thing</span> <span m='288420'>is</span> <span m='288570'>thinking</span>
  <span m='288840'>about</span> <span m='289050'>the</span> <span m='289140'>implications</span>
  <span m='289650'>of</span> <span m='289710'>that</span> <span m='289860'>infinity</span>
  <span m='290340'>thing.</span> <span m='293080'>There's</span> <span m='293130'>going</span>
  <span m='293250'>to</span> <span m='293310'>be</span> <span m='293400'>certain</span>
  <span m='293910'>values</span> <span m='294540'>of</span> <span m='294660'>s</span>
  <span m='296040'>for</span> <span m='296280'>which</span> <span m='296550'>that</span>
  <span m='296880'>integral</span> <span m='297330'>diverges.</span> </p><p><span
  m='300180'>So</span> <span m='300230'>to</span> <span m='300320'>think</span> <span
  m='300470'>about</span> <span m='300710'>that,</span> <span m='301410'>think</span>
  <span m='301490'>about</span> <span m='302870'>the</span> <span m='302990'>thing</span>
  <span m='303140'>that</span> <span m='303260'>we're</span> <span m='303410'>integrating.</span>
  <span m='304480'>We're</span> <span m='304610'>integrating</span> <span m='305000'>something</span>
  <span m='305330'>that</span> <span m='305420'>looks</span> <span m='305630'>like</span>
  <span m='306230'>e</span> <span m='306694'>to the</span> <span m='307158'>pt.</span>
  <span m='309480'>We're</span> <span m='309980'>integrating</span> <span m='310550'>against</span>
  <span m='311000'>some</span> <span m='311330'>function.</span> <span m='312620'>So</span>
  <span m='313400'>define</span> <span m='313730'>the</span> <span m='313790'>original</span>
  <span m='314060'>function</span> <span m='314360'>of</span> <span m='314420'>time</span>
  <span m='314690'>is</span> <span m='314840'>e</span> <span m='314940'>to</span>
  <span m='315060'>the</span> <span m='315110'>minus</span> <span m='316200'>t,</span>
  <span m='316500'>here we</span> <span m='316830'>have e</span> <span m='317160'>to
  the minus</span> <span m='317320'>st.</span> <span m='317600'>Let's</span> <span
  m='317780'>just</span> <span m='317990'>focus</span> <span m='318380'>on</span>
  <span m='318500'>that</span> <span m='318650'>one</span> <span m='318800'>for</span>
  <span m='318920'>a</span> <span m='318950'>moment,</span> <span m='320132'>the</span>
  <span m='320500'>e to</span> <span m='320740'>the st</span> <span m='321290'>thing.</span>
  </p><p><span m='322970'>We're</span> <span m='323060'>going</span> <span m='323180'>to</span>
  <span m='323270'>generally</span> <span m='323660'>be</span> <span m='323810'>worried</span>
  <span m='324110'>about</span> <span m='324470'>values</span> <span m='324890'>of</span>
  <span m='324980'>s,</span> <span m='325280'>or</span> <span m='325400'>here,</span>
  <span m='325640'>values</span> <span m='326060'>of</span> <span m='326210'>p,</span>
  <span m='327050'>that</span> <span m='327170'>have</span> <span m='327410'>complex</span>
  <span m='327860'>values.</span> <span m='328910'>We're</span> <span m='329060'>going</span>
  <span m='329180'>to</span> <span m='329240'>be</span> <span m='329300'>looking</span>
  <span m='329540'>at</span> <span m='329600'>the</span> <span m='329750'>s</span>
  <span m='329960'>plane</span> <span m='330290'>just</span> <span m='330470'>the</span>
  <span m='330590'>same</span> <span m='330800'>as</span> <span m='330890'>last</span>
  <span m='331100'>time</span> <span m='331250'>we</span> <span m='331340'>looked</span>
  <span m='331550'>at</span> <span m='331610'>the</span> <span m='331730'>z</span>
  <span m='331910'>plane.</span> <span m='333110'>So</span> <span m='333260'>we're</span>
  <span m='333350'>going</span> <span m='333470'>to</span> <span m='333560'>think</span>
  <span m='333770'>about</span> <span m='334070'>this</span> <span m='334250'>thing</span>
  <span m='334430'>might</span> <span m='334640'>have</span> <span m='334790'>a</span>
  <span m='334850'>real</span> <span m='335120'>and</span> <span m='335210'>imaginary</span>
  <span m='335720'>component.</span> </p><p><span m='336290'>So</span> <span m='336440'>we</span>
  <span m='336530'>might</span> <span m='336770'>have</span> <span m='336920'>something</span>
  <span m='337280'>like</span> <span m='337430'>looks</span> <span m='337640'>like</span>
  <span m='337880'>this.</span> <span m='341860'>Sigma</span> <span m='342220'>would</span>
  <span m='342340'>be</span> <span m='342490'>the</span> <span m='342610'>real</span>
  <span m='342820'>part</span> <span m='343270'>of</span> <span m='343525'>p.</span>
  <span m='345280'>Omega</span> <span m='345670'>would</span> <span m='345790'>be</span>
  <span m='345940'>the</span> <span m='346030'>imaginary</span> <span m='346540'>part</span>
  <span m='346750'>of</span> <span m='346970'>p.</span> <span m='348790'>And</span>
  <span m='351360'>somebody</span> <span m='351610'>want</span> <span m='351760'>to</span>
  <span m='351820'>hazard</span> <span m='352090'>a</span> <span m='352150'>guess</span>
  <span m='352420'>at</span> <span m='352510'>what</span> <span m='352690'>that</span>
  <span m='352840'>might</span> <span m='352990'>look</span> <span m='353170'>like</span>
  <span m='354520'>if</span> <span m='354700'>I</span> <span m='354800'>tried</span>
  <span m='355090'>to</span> <span m='355180'>expand</span> <span m='355620'>it</span>
  <span m='355720'>as</span> <span m='355900'>a</span> <span m='355960'>real</span>
  <span m='356170'>and</span> <span m='356250'>imaginary</span> <span m='356740'>part?</span>
  <span m='358880'>Someone</span> <span m='359180'>wanted</span> <span m='359320'>to</span>
  <span m='359380'>hazard</span> <span m='359650'>a</span> <span m='359710'>guess</span>
  <span m='360490'>at</span> <span m='360700'>the</span> <span m='360880'>name</span>
  <span m='361360'>of</span> <span m='361600'>the</span> <span m='361840'>equation</span>
  <span m='362360'>I</span> <span m='362440'>might</span> <span m='362620'>use?</span>
  </p><p><span m='365430'>AUDIENCE:</span> <span m='365651'>Euler.</span> </p><p><span
  m='366760'>DENNIS FREEMAN:</span> <span m='366790'>Euler's</span> <span m='366820'>equation,</span>
  <span m='367620'>sure.</span> <span m='368700'>So</span> <span m='368820'>I</span>
  <span m='368910'>would</span> <span m='369060'>expand</span> <span m='369420'>this</span>
  <span m='369570'>by</span> <span m='369720'>Euler's</span> <span m='370080'>equation</span>
  <span m='370500'>and</span> <span m='370590'>I</span> <span m='370680'>get</span>
  <span m='370860'>something</span> <span m='371190'>of</span> <span m='371260'>the</span>
  <span m='371350'>form</span> <span m='371850'>e to</span> <span m='371940'>the</span>
  <span m='372060'>sigma</span> <span m='372360'>t,</span> <span m='372840'>cos</span>
  <span m='372910'>omega</span> <span m='373140'>t</span> <span m='374730'>plus</span>
  <span m='375060'>j</span> <span m='376700'>sine</span> <span m='376910'>omega</span>
  <span m='377350'>t.</span> <span m='380547'>The</span> <span m='380990'>point</span>
  <span m='381200'>of</span> <span m='381290'>writing</span> <span m='381560'>that</span>
  <span m='381740'>out</span> <span m='382400'>is</span> <span m='382670'>that</span>
  <span m='382790'>I</span> <span m='382880'>hope</span> <span m='383090'>it's</span>
  <span m='383240'>clear</span> <span m='383690'>that</span> <span m='383870'>convergence</span>
  <span m='384530'>of</span> <span m='384620'>the</span> <span m='384950'>integral</span>
  <span m='385220'>is</span> <span m='385310'>going</span> <span m='385460'>to</span>
  <span m='385520'>depend</span> <span m='385880'>critically</span> <span m='386390'>on</span>
  <span m='387020'>the</span> <span m='387110'>real</span> <span m='387350'>or the</span>
  <span m='387590'>imaginary</span> <span m='388010'>part?</span> <span m='389765'>Real,</span>
  <span m='391750'>right?</span> </p><p><span m='392890'>So</span> <span m='393490'>the</span>
  <span m='393610'>convergence</span> <span m='394100'>is</span> <span m='394160'>going</span>
  <span m='394300'>to</span> <span m='394360'>be</span> <span m='394510'>determined</span>
  <span m='394930'>by</span> <span m='395140'>this.</span> <span m='395410'>This</span>
  <span m='395680'>is</span> <span m='395800'>the</span> <span m='395860'>thing</span>
  <span m='396070'>that's</span> <span m='396220'>affecting</span> <span m='396640'>the</span>
  <span m='396730'>magnitude.</span> <span m='397210'>That's</span> <span m='397420'>the</span>
  <span m='397480'>thing</span> <span m='397630'>that's</span> <span m='397780'>getting</span>
  <span m='398020'>smaller</span> <span m='398500'>or</span> <span m='398650'>bigger</span>
  <span m='398980'>as</span> <span m='399100'>I</span> <span m='399160'>go</span>
  <span m='399340'>to</span> <span m='399460'>infinity</span> <span m='399910'>or</span>
  <span m='399970'>minus</span> <span m='400300'>infinity.</span> <span m='402980'>The</span>
  <span m='403220'>cosine</span> <span m='403650'>term,</span> <span m='404390'>the</span>
  <span m='404550'>sine</span> <span m='404880'>term,</span> <span m='405510'>those</span>
  <span m='405660'>are</span> <span m='405780'>oscillating.</span> <span m='408330'>They</span>
  <span m='408450'>don't</span> <span m='408690'>make</span> <span m='409140'>the</span>
  <span m='409350'>function</span> <span m='409890'>be</span> <span m='410070'>more</span>
  <span m='410490'>or</span> <span m='410820'>less</span> <span m='412260'>convergent</span>
  <span m='413460'>than</span> <span m='413610'>it</span> <span m='413730'>was</span>
  <span m='414150'>or</span> <span m='414360'>originally.</span> <span m='416310'>So</span>
  <span m='416440'>when</span> <span m='416550'>I'm</span> <span m='416610'>thinking</span>
  <span m='416770'>about</span> <span m='416970'>convergence</span> <span m='417450'>I'm</span>
  <span m='417480'>going</span> <span m='417560'>to</span> <span m='417660'>be</span>
  <span m='417720'>thinking</span> <span m='417960'>about</span> <span m='418140'>the</span>
  <span m='418230'>real</span> <span m='418470'>part.</span> </p><p><span m='420240'>So</span>
  <span m='420360'>over</span> <span m='420630'>here</span> <span m='420900'>if</span>
  <span m='421020'>I</span> <span m='421110'>want</span> <span m='421270'>to</span>
  <span m='421350'>make</span> <span m='421620'>this</span> <span m='422580'>integral</span>
  <span m='423000'>converge</span> <span m='424320'>I</span> <span m='424410'>want</span>
  <span m='424590'>to</span> <span m='424650'>be</span> <span m='424770'>thinking</span>
  <span m='425130'>about</span> <span m='425490'>t</span> <span m='426030'>going</span>
  <span m='426330'>from</span> <span m='426510'>0</span> <span m='426840'>to</span>
  <span m='426960'>infinity.</span> <span m='427305'>Well,</span> <span m='427650'>0</span>
  <span m='427950'>is</span> <span m='428040'>not</span> <span m='428160'>a</span>
  <span m='428220'>problem.</span> <span m='428730'>e</span> <span m='429000'>to the</span>
  <span m='429320'>0</span> <span m='429720'>is</span> <span m='429840'>1,</span>
  <span m='430230'>that's</span> <span m='430380'>going</span> <span m='430500'>to</span>
  <span m='430560'>work.</span> <span m='431530'>It's</span> <span m='431620'>the</span>
  <span m='431660'>infinity</span> <span m='432060'>part</span> <span m='432270'>that's</span>
  <span m='432420'>a</span> <span m='432480'>problem.</span> </p><p><span m='433420'>So</span>
  <span m='433590'>if</span> <span m='433770'>I</span> <span m='433860'>have</span>
  <span m='435270'>infinity</span> <span m='435780'>plugged</span> <span m='436050'>in</span>
  <span m='436230'>for</span> <span m='436410'>t,</span> <span m='437160'>what's</span>
  <span m='437430'>the</span> <span m='437520'>range</span> <span m='437790'>of</span>
  <span m='437850'>values</span> <span m='438240'>for</span> <span m='438360'>s</span>
  <span m='438570'>for</span> <span m='438690'>plus</span> <span m='438990'>1</span>
  <span m='439680'>that</span> <span m='439830'>makes</span> <span m='440070'>sense?</span>
  <span m='441060'>That's</span> <span m='441870'>the</span> <span m='441990'>important</span>
  <span m='442290'>question,</span> <span m='442650'>right.</span> <span m='444300'>So</span>
  <span m='444390'>I'm</span> <span m='444450'>going</span> <span m='444600'>to</span>
  <span m='444720'>want</span> <span m='444990'>to</span> <span m='445320'>constrain</span>
  <span m='446010'>the</span> <span m='446130'>real</span> <span m='446460'>part</span>
  <span m='447000'>of</span> <span m='447120'>that</span> <span m='447390'>number,</span>
  <span m='447840'>s</span> <span m='448050'>plus</span> <span m='448320'>1,</span>
  <span m='449850'>to</span> <span m='449940'>be</span> <span m='450030'>bigger</span>
  <span m='450270'>than</span> <span m='450390'>0.</span> <span m='451770'>If</span>
  <span m='451920'>the</span> <span m='452010'>real</span> <span m='452160'>part</span>
  <span m='452370'>of</span> <span m='452430'>that</span> <span m='452550'>number</span>
  <span m='452850'>is</span> <span m='452940'>bigger</span> <span m='453150'>than</span>
  <span m='453300'>0,</span> <span m='454320'>then</span> <span m='454620'>this</span>
  <span m='454890'>thing</span> <span m='455070'>will</span> <span m='455220'>converge</span>
  <span m='455670'>to</span> <span m='455820'>0.</span> </p><p><span m='459560'>If</span>
  <span m='459740'>that</span> <span m='459890'>converges</span> <span m='460400'>to</span>
  <span m='460520'>0</span> <span m='460940'>then</span> <span m='461120'>I</span>
  <span m='461210'>have</span> <span m='461360'>a</span> <span m='461390'>simple</span>
  <span m='461780'>answer,</span> <span m='462180'>it's</span> <span m='462200'>just</span>
  <span m='462380'>the</span> <span m='462500'>answer</span> <span m='462860'>in</span>
  <span m='463010'>the</span> <span m='463100'>bottom.</span> <span m='464060'>It's</span>
  <span m='464240'>in</span> <span m='464330'>the</span> <span m='464420'>bottom</span>
  <span m='464810'>so</span> <span m='464950'>I</span> <span m='465050'>have</span>
  <span m='465170'>to</span> <span m='465230'>put</span> <span m='465380'>a</span>
  <span m='465440'>minus</span> <span m='465710'>sign,</span> <span m='466070'>that</span>
  <span m='466190'>kills</span> <span m='466490'>that</span> <span m='466640'>minus</span>
  <span m='466910'>sign.</span> <span m='467340'>So</span> <span m='467390'>my</span>
  <span m='467540'>answer</span> <span m='467750'>is</span> <span m='467840'>1</span>
  <span m='467990'>over</span> <span m='468250'>s plus</span> <span m='468440'>1.</span>
  <span m='470000'>Easy,</span> <span m='470530'>right?</span> </p><p><span m='471230'>And</span>
  <span m='471350'>we</span> <span m='471530'>will</span> <span m='471680'>say</span>
  <span m='472160'>that</span> <span m='472280'>the</span> <span m='472370'>Laplace</span>
  <span m='472790'>transform</span> <span m='473960'>has</span> <span m='474170'>a</span>
  <span m='474230'>functional</span> <span m='474680'>form,</span> <span m='475280'>1
  over</span> <span m='475670'>s</span> <span m='475820'>plus</span> <span m='476070'>1.</span>
  <span m='476710'>And</span> <span m='476810'>it</span> <span m='476870'>has</span>
  <span m='477020'>region of</span> <span m='477380'>convergence,</span> <span m='477730'>the
  real</span> <span m='478080'>part</span> <span m='478280'>of</span> <span m='478370'>s</span>
  <span m='478690'>bigger then</span> <span m='478820'>minus</span> <span m='479220'>1.</span>
  <span m='479485'>Just</span> <span m='479750'>solving</span> <span m='480080'>that</span>
  <span m='480230'>inequality</span> <span m='481130'>for</span> <span m='481250'>the</span>
  <span m='481370'>real</span> <span m='481490'>part</span> <span m='481700'>of</span>
  <span m='481790'>s</span> <span m='481910'>so</span> <span m='482030'>I</span> <span
  m='482090'>can</span> <span m='482210'>draw</span> <span m='482400'>it</span> <span
  m='482480'>on</span> <span m='482570'>an</span> <span m='482660'>s</span> <span
  m='482810'>plane.</span> </p><p><span m='484190'>So</span> <span m='484370'>we'll</span>
  <span m='484550'>associate</span> <span m='485210'>then</span> <span m='486230'>with</span>
  <span m='486440'>this</span> <span m='486590'>s</span> <span m='486740'>transform</span>
  <span m='487610'>a</span> <span m='487830'>picture</span> <span m='489840'>which</span>
  <span m='490020'>we</span> <span m='490140'>will</span> <span m='490290'>commonly</span>
  <span m='490710'>call</span> <span m='490920'>the</span> <span m='490970'>pole</span>
  <span m='491120'>0</span> <span m='491480'>pattern.</span> <span m='492630'>Is</span>
  <span m='493000'>just</span> <span m='493170'>a</span> <span m='493230'>picture</span>
  <span m='494220'>of</span> <span m='494340'>the</span> <span m='494490'>s</span>
  <span m='494730'>plane</span> <span m='496140'>which</span> <span m='496350'>shows</span>
  <span m='496800'>me</span> <span m='497940'>the</span> <span m='498090'>singularities,</span>
  <span m='498930'>the</span> <span m='499050'>poles</span> <span m='499290'>and</span>
  <span m='499380'>zeroes</span> <span m='500010'>of</span> <span m='500340'>the</span>
  <span m='500790'>Laplace</span> <span m='500890'>transform</span> <span m='501600'>and</span>
  <span m='501690'>the</span> <span m='501780'>region</span> <span m='502020'>of</span>
  <span m='502110'>convergence.</span> <span m='503500'>So</span> <span m='503550'>there's</span>
  <span m='503730'>a</span> <span m='503790'>single</span> <span m='504120'>pole.</span>
  <span m='504510'>There's</span> <span m='504690'>a</span> <span m='504750'>pole</span>
  <span m='505520'>at</span> <span m='505940'>s</span> <span m='506220'>equals</span>
  <span m='506460'>a</span> <span m='506520'>minus</span> <span m='506850'>1,</span>
  <span m='507110'>so I</span> <span m='507370'>indicate</span> <span m='507720'>that</span>
  <span m='507930'>by</span> <span m='508050'>the</span> <span m='508200'>x.</span>
  <span m='509940'>And</span> <span m='510170'>I have</span> <span m='510300'>region</span>
  <span m='510660'>of</span> <span m='510780'>convergence</span> <span m='511590'>which</span>
  <span m='511800'>I'll</span> <span m='511900'>illustrate</span> <span m='512559'>here</span>
  <span m='512880'>with</span> <span m='513120'>the</span> <span m='514200'>gray</span>
  <span m='514470'>area.</span> </p><p><span m='515650'>So</span> <span m='515700'>it</span>
  <span m='515760'>converges</span> <span m='516360'>for</span> <span m='516480'>all</span>
  <span m='516659'>values</span> <span m='517049'>of</span> <span m='517169'>s</span>
  <span m='517919'>that</span> <span m='518010'>are</span> <span m='518100'>in</span>
  <span m='518190'>the</span> <span m='518250'>gray</span> <span m='518490'>area.</span>
  <span m='519480'>OK,</span> <span m='519990'>easy</span> <span m='520289'>right?</span>
  <span m='521010'>Trivial.</span> </p><p><span m='523140'>OK,</span> <span m='523710'>so</span>
  <span m='523950'>now</span> <span m='524190'>you</span> <span m='524370'>get</span>
  <span m='524490'>to</span> <span m='524580'>talk</span> <span m='524760'>to</span>
  <span m='524820'>your</span> <span m='524910'>neighbor.</span> <span m='526400'>OK,</span>
  <span m='526770'>turn</span> <span m='526920'>to</span> <span m='526980'>your</span>
  <span m='527070'>neighbor.</span> <span m='527700'>Say,</span> <span m='527880'>hi.</span>
  </p><p><span m='529110'>[INTERPOSING VOICES]</span> </p><p><span m='531030'>And</span>
  <span m='531240'>figure</span> <span m='531720'>out</span> <span m='532170'>the</span>
  <span m='532290'>Laplace</span> <span m='532680'>transform</span> <span m='533190'>of</span>
  <span m='533280'>a</span> <span m='533350'>slightly</span> <span m='533820'>more,</span>
  <span m='534060'>but</span> <span m='534210'>not</span> <span m='534390'>very</span>
  <span m='534660'>complicated,</span> <span m='535710'>function.</span> </p><p><span
  m='541080'>[INTERPOSING VOICES]</span> </p><p></p><p><span m='653060'>DENNIS FREEMAN:</span>
  <span m='653135'>So</span> <span m='653210'>what's</span> <span m='653360'>the</span>
  <span m='653450'>answer?</span> <span m='655190'>Everybody</span> <span m='655400'>raise</span>
  <span m='655640'>your</span> <span m='655760'>hands,</span> <span m='656160'>show</span>
  <span m='656420'>some</span> <span m='656660'>number</span> <span m='656870'>of</span>
  <span m='656930'>fingers</span> <span m='657290'>equal</span> <span m='657590'>to</span>
  <span m='657920'>the</span> <span m='658250'>number</span> <span m='658700'>of</span>
  <span m='659000'>the</span> <span m='659210'>correct</span> <span m='659480'>solution.</span>
  <span m='661700'>Wonderful.</span> <span m='664620'>The</span> <span m='664940'>universal</span>
  <span m='665480'>answer--</span> <span m='665850'>I</span> <span m='665950'>think</span>
  <span m='666050'>it</span> <span m='666150'>was</span> <span m='666250'>universal--</span>
  <span m='667100'>was</span> <span m='667430'>1.</span> <span m='668000'>So</span>
  <span m='668150'>how</span> <span m='668240'>do</span> <span m='668300'>you</span>
  <span m='668360'>get</span> <span m='668480'>1?</span> <span m='669210'>What</span>
  <span m='669350'>do I</span> <span m='669480'>do?</span> <span m='672080'>How</span>
  <span m='672320'>do I</span> <span m='672620'>find</span> <span m='672830'>the</span>
  <span m='673140'>Laplace</span> <span m='673450'>transform</span> <span m='673550'>of
  the</span> <span m='673610'>top</span> <span m='674040'>function?</span> </p><p><span
  m='674390'>[INAUDIBLE]</span> </p><p></p><p><span m='681450'>DENNIS FREEMAN:</span>
  <span m='681590'>Precisely.</span> <span m='682900'>So</span> <span m='683040'>what</span>
  <span m='683310'>I</span> <span m='683400'>do</span> <span m='683670'>is</span>
  <span m='683820'>just</span> <span m='684270'>stick</span> <span m='684660'>it</span>
  <span m='684750'>in</span> <span m='684840'>the</span> <span m='684900'>formula,</span>
  <span m='685410'>do</span> <span m='685620'>it</span> <span m='685710'>twice.</span>
  <span m='687060'>Laplace</span> <span m='687390'>transform,</span> <span m='687810'>like</span>
  <span m='687960'>the z</span> <span m='688230'>transform,</span> <span m='688680'>is</span>
  <span m='688800'>linear.</span> <span m='690030'>It</span> <span m='690120'>will</span>
  <span m='690270'>turn</span> <span m='690510'>out</span> <span m='690780'>that</span>
  <span m='691320'>the</span> <span m='691440'>Laplace</span> <span m='691860'>of</span>
  <span m='691980'>a</span> <span m='692040'>sum</span> <span m='692400'>is</span>
  <span m='692550'>the</span> <span m='692670'>sum</span> <span m='692940'>of</span>
  <span m='693150'>the</span> <span m='693240'>Laplaces.</span> </p><p><span m='699190'>If</span>
  <span m='699480'>I</span> <span m='699570'>simply</span> <span m='700050'>stick</span>
  <span m='700530'>the</span> <span m='700650'>expression</span> <span m='701190'>for</span>
  <span m='701370'>x2</span> <span m='702750'>into</span> <span m='703020'>the</span>
  <span m='703140'>definition,</span> <span m='704160'>you</span> <span m='704280'>can</span>
  <span m='704430'>see</span> <span m='704610'>it</span> <span m='704700'>splits</span>
  <span m='705030'>into</span> <span m='705240'>two</span> <span m='705420'>pieces.</span>
  <span m='708320'>And</span> <span m='708500'>I</span> <span m='708590'>get</span>
  <span m='708860'>two</span> <span m='709670'>parts.</span> <span m='710090'>1</span>
  <span m='710270'>over</span> <span m='710480'>s</span> <span m='710600'>plus</span>
  <span m='710840'>1</span> <span m='711110'>just</span> <span m='711290'>like</span>
  <span m='711440'>I</span> <span m='711540'>got--</span> <span m='712520'>so</span>
  <span m='712730'>the</span> <span m='713000'>first</span> <span m='713240'>part</span>
  <span m='713450'>looks</span> <span m='713660'>just</span> <span m='713840'>like</span>
  <span m='714020'>x1,</span> <span m='715250'>the</span> <span m='715340'>first</span>
  <span m='715580'>example.</span> <span m='716820'>The</span> <span m='716840'>second</span>
  <span m='717110'>one</span> <span m='717260'>looks</span> <span m='717440'>almost</span>
  <span m='717920'>the</span> <span m='718040'>same</span> <span m='718340'>except</span>
  <span m='718610'>there's</span> <span m='718760'>a</span> <span m='718820'>2</span>
  <span m='719060'>where</span> <span m='719210'>there</span> <span m='719330'>used</span>
  <span m='719510'>to</span> <span m='719630'>be</span> <span m='719790'>1.</span>
  <span m='720980'>Shockingly,</span> <span m='721580'>it</span> <span m='721670'>changes</span>
  <span m='722120'>one</span> <span m='722300'>of</span> <span m='722390'>the</span>
  <span m='722450'>ones</span> <span m='722810'>into</span> <span m='723080'>a</span>
  <span m='723170'>2.</span> </p><p><span m='726050'>And</span> <span m='726200'>then</span>
  <span m='726320'>the</span> <span m='726440'>only</span> <span m='726650'>issue</span>
  <span m='726950'>is</span> <span m='727070'>where</span> <span m='727160'>is</span>
  <span m='727310'>the</span> <span m='727400'>region</span> <span m='727670'>of</span>
  <span m='727760'>convergence.</span> <span m='729570'>So</span> <span m='729770'>this</span>
  <span m='730160'>part</span> <span m='730460'>converges</span> <span m='732200'>if</span>
  <span m='732350'>the</span> <span m='732440'>real</span> <span m='732620'>part</span>
  <span m='732860'>of</span> <span m='732980'>s</span> <span m='733160'>is</span>
  <span m='733280'>bigger</span> <span m='733550'>than</span> <span m='733670'>minus</span>
  <span m='734030'>1.</span> <span m='735758'>This</span> <span m='736190'>converges</span>
  <span m='736730'>if</span> <span m='736850'>the</span> <span m='736940'>real</span>
  <span m='737120'>part</span> <span m='737360'>of</span> <span m='737450'>s</span>
  <span m='737630'>is</span> <span m='737720'>bigger</span> <span m='737960'>than</span>
  <span m='738080'>minus</span> <span m='738440'>2.</span> <span m='741030'>So</span>
  <span m='741180'>they</span> <span m='741330'>both</span> <span m='741600'>converge</span>
  <span m='742110'>if</span> <span m='742220'>the</span> <span m='742310'>real</span>
  <span m='742440'>part</span> <span m='742680'>of</span> <span m='742770'>s</span>
  <span m='742950'>is</span> <span m='743040'>bigger</span> <span m='743250'>than</span>
  <span m='743430'>minus?</span> </p><p><span m='744740'>AUDIENCE:</span> <span m='744950'>1.</span>
  </p><p><span m='746000'>DENNIS FREEMAN:</span> <span m='746183'>1,</span> <span
  m='746732'>right.</span> <span m='749110'>If</span> <span m='749200'>I'm</span>
  <span m='749350'>in</span> <span m='749470'>the</span> <span m='749560'>region</span>
  <span m='749920'>of</span> <span m='750040'>s</span> <span m='751150'>where</span>
  <span m='751510'>both</span> <span m='751960'>the</span> <span m='752080'>first</span>
  <span m='752380'>part</span> <span m='752680'>and</span> <span m='752920'>the</span>
  <span m='753010'>second</span> <span m='753310'>part</span> <span m='753520'>converges</span>
  <span m='754570'>then</span> <span m='754780'>I'm</span> <span m='754930'>fine.</span>
  <span m='757570'>So</span> <span m='757720'>that</span> <span m='757870'>was</span>
  <span m='757990'>all</span> <span m='758110'>very</span> <span m='758320'>straightforward.</span>
  <span m='758990'>I</span> <span m='759090'>get</span> <span m='759580'>an</span>
  <span m='759730'>answer</span> <span m='760060'>that</span> <span m='760420'>was</span>
  <span m='760660'>number</span> <span m='760930'>one,</span> <span m='762520'>OK.</span>
  <span m='764020'>So</span> <span m='765040'>the</span> <span m='765770'>transform</span>
  <span m='766240'>is</span> <span m='766480'>just</span> <span m='766660'>the</span>
  <span m='766780'>sum</span> <span m='766990'>of</span> <span m='767050'>those</span>
  <span m='767230'>two</span> <span m='767410'>pieces.</span> <span m='768050'>And</span>
  <span m='768070'>the</span> <span m='768130'>region</span> <span m='768580'>is</span>
  <span m='768850'>the</span> <span m='768940'>region</span> <span m='769240'>of</span>
  <span m='769330'>overlap.</span> </p><p><span m='774450'>A</span> <span m='774690'>more</span>
  <span m='774900'>interesting</span> <span m='775320'>case,</span> <span m='775650'>and</span>
  <span m='775800'>where</span> <span m='775980'>things</span> <span m='776280'>are</span>
  <span m='776520'>a</span> <span m='776550'>little</span> <span m='776790'>bit</span>
  <span m='776910'>different</span> <span m='777240'>when</span> <span m='777390'>we</span>
  <span m='777480'>think</span> <span m='777630'>about</span> <span m='777840'>the</span>
  <span m='777970'>bilateral</span> <span m='778550'>Laplace</span> <span m='778830'>transform</span>
  <span m='779290'>than</span> <span m='779490'>unilateral,</span> <span m='780630'>is</span>
  <span m='780930'>that</span> <span m='781290'>the</span> <span m='781410'>regions</span>
  <span m='781890'>can</span> <span m='782250'>be</span> <span m='782400'>more</span>
  <span m='782580'>complicated.</span> <span m='785850'>So</span> <span m='785990'>here's</span>
  <span m='786380'>an</span> <span m='786470'>example</span> <span m='787400'>where</span>
  <span m='787940'>I've</span> <span m='788150'>got</span> <span m='788530'>a</span>
  <span m='791300'>backwards</span> <span m='791690'>traveling</span> <span m='792020'>function.</span>
  <span m='793710'>So</span> <span m='793760'>now</span> <span m='793970'>the</span>
  <span m='794090'>function</span> <span m='794420'>only</span> <span m='794660'>exists</span>
  <span m='794990'>for</span> <span m='795260'>t less</span> <span m='795500'>than</span>
  <span m='795650'>0.</span> <span m='800330'>As</span> <span m='800480'>you</span>
  <span m='800570'>might</span> <span m='800750'>expect,</span> <span m='801110'>just</span>
  <span m='801280'>stick</span> <span m='801440'>it</span> <span m='801560'>in</span>
  <span m='801650'>the</span> <span m='801710'>formula</span> <span m='802100'>and</span>
  <span m='802190'>see</span> <span m='802370'>what</span> <span m='802520'>happens.</span>
  </p><p><span m='804240'>So</span> <span m='804350'>stick</span> <span m='804680'>this</span>
  <span m='806810'>expression</span> <span m='807290'>into</span> <span m='807530'>here.</span>
  <span m='807800'>Now it</span> <span m='808130'>lips</span> <span m='808400'>off</span>
  <span m='808610'>the</span> <span m='808700'>top</span> <span m='810810'>of</span>
  <span m='810930'>the</span> <span m='811080'>integral.</span> <span m='812610'>But</span>
  <span m='812700'>when</span> <span m='812850'>you're</span> <span m='812970'>grinding</span>
  <span m='813500'>through</span> <span m='813690'>integrals</span> <span m='814330'>it's</span>
  <span m='814350'>hard</span> <span m='814590'>to</span> <span m='814680'>tell</span>
  <span m='814860'>the</span> <span m='814980'>difference.</span> <span m='815880'>You</span>
  <span m='816000'>get</span> <span m='816180'>something</span> <span m='816570'>that</span>
  <span m='816660'>looks</span> <span m='816900'>very</span> <span m='817140'>much</span>
  <span m='817410'>the</span> <span m='817530'>same.</span> </p><p><span m='819090'>The</span>
  <span m='819210'>thing</span> <span m='819480'>that</span> <span m='819690'>is</span>
  <span m='819900'>different,</span> <span m='820800'>notice</span> <span m='821130'>that</span>
  <span m='821250'>the</span> <span m='821340'>function</span> <span m='821730'>was</span>
  <span m='821880'>upside</span> <span m='822210'>down.</span> <span m='822960'>It</span>
  <span m='823080'>was</span> <span m='823260'>minus</span> <span m='823950'>something</span>
  <span m='824460'>rather</span> <span m='824790'>than</span> <span m='824940'>plus</span>
  <span m='825210'>something</span> <span m='825720'>like</span> <span m='825930'>the</span>
  <span m='826050'>first</span> <span m='826290'>example</span> <span m='826710'>was.</span>
  <span m='828600'>So</span> <span m='828750'>the</span> <span m='828840'>first</span>
  <span m='829080'>example</span> <span m='829560'>was</span> <span m='830190'>e</span>
  <span m='830430'>to the</span> <span m='830520'>minus</span> <span m='830770'>t,</span>
  <span m='830900'>t</span> <span m='831330'>bigger</span> <span m='831600'>than</span>
  <span m='831750'>0.</span> </p><p><span m='832110'>This</span> <span m='832320'>example</span>
  <span m='833160'>is</span> <span m='833310'>minus</span> <span m='833680'>e</span>
  <span m='833820'>to</span> <span m='833910'>the</span> <span m='834000'>minus</span>
  <span m='834360'>t,</span> <span m='834700'>t less than</span> <span m='835140'>0.</span>
  <span m='838540'>That</span> <span m='838590'>gave</span> <span m='838830'>me</span>
  <span m='838950'>a</span> <span m='839010'>minus</span> <span m='839370'>sign</span>
  <span m='839700'>here</span> <span m='840510'>but</span> <span m='841200'>the</span>
  <span m='842780'>nontrivial</span> <span m='844260'>limit</span> <span m='845700'>is</span>
  <span m='846090'>at</span> <span m='846240'>the</span> <span m='846360'>top</span>
  <span m='846750'>rather</span> <span m='847010'>than</span> <span m='847130'>at</span>
  <span m='847220'>the</span> <span m='847320'>bottom.</span> <span m='848220'>That's</span>
  <span m='848460'>the</span> <span m='848580'>reason</span> <span m='848820'>I</span>
  <span m='848880'>put</span> <span m='849000'>the</span> <span m='849090'>minus</span>
  <span m='849360'>sign</span> <span m='849600'>in.</span> <span m='849750'>So</span>
  <span m='849870'>it</span> <span m='849930'>would</span> <span m='850020'>kill</span>
  <span m='850230'>the</span> <span m='850350'>other</span> <span m='850530'>minus</span>
  <span m='850770'>sign.</span> </p><p><span m='854180'>Also,</span> <span m='854690'>since</span>
  <span m='854900'>I</span> <span m='854990'>need</span> <span m='855260'>convergence</span>
  <span m='856730'>at</span> <span m='856970'>t</span> <span m='857300'>equals</span>
  <span m='857540'>minus</span> <span m='857960'>infinity,</span> <span m='860530'>the</span>
  <span m='860660'>region</span> <span m='860990'>flips.</span> <span m='863870'>I</span>
  <span m='864020'>still</span> <span m='864290'>need</span> <span m='864530'>to</span>
  <span m='864620'>have</span> <span m='864800'>that</span> <span m='865040'>sort</span>
  <span m='865310'>of</span> <span m='865490'>thing</span> <span m='866030'>decay</span>
  <span m='867830'>so</span> <span m='868040'>that</span> <span m='868190'>the</span>
  <span m='868340'>integral</span> <span m='868760'>exists.</span> <span m='870920'>But</span>
  <span m='871100'>now</span> <span m='871310'>the</span> <span m='871430'>functions</span>
  <span m='871850'>are</span> <span m='871940'>flipped</span> <span m='872240'>in</span>
  <span m='872360'>time.</span> <span m='874620'>So</span> <span m='874800'>the</span>
  <span m='877920'>important</span> <span m='878340'>range</span> <span m='878580'>of</span>
  <span m='878670'>s</span> <span m='879000'>is</span> <span m='879120'>now</span>
  <span m='879300'>flipped.</span> <span m='880920'>So</span> <span m='881070'>now</span>
  <span m='881550'>I</span> <span m='881760'>get</span> <span m='883260'>the</span>
  <span m='883410'>same</span> <span m='883980'>functional</span> <span m='884460'>form</span>
  <span m='884850'>exactly,</span> <span m='886270'>but</span> <span m='886540'>a</span>
  <span m='886620'>region</span> <span m='886980'>that's</span> <span m='887130'>on</span>
  <span m='887250'>the</span> <span m='887340'>other</span> <span m='887550'>side.</span>
  </p><p><span m='890250'>That's</span> <span m='890460'>one</span> <span m='890640'>of</span>
  <span m='890700'>the</span> <span m='890820'>central</span> <span m='891180'>differences</span>
  <span m='891660'>between</span> <span m='891960'>the</span> <span m='892050'>bilateral</span>
  <span m='892540'>and</span> <span m='892640'>the</span> <span m='892770'>unilateral</span>
  <span m='894450'>transform.</span> <span m='897560'>I</span> <span m='897680'>need</span>
  <span m='897920'>to</span> <span m='898040'>tell</span> <span m='898220'>you</span>
  <span m='898400'>the</span> <span m='898520'>region</span> <span m='898850'>of</span>
  <span m='898970'>convergence</span> <span m='899540'>for</span> <span m='899720'>you</span>
  <span m='899900'>to</span> <span m='900020'>know</span> <span m='901430'>which</span>
  <span m='901760'>of</span> <span m='901850'>those</span> <span m='902060'>two</span>
  <span m='902210'>functions</span> <span m='902660'>that</span> <span m='902780'>I'm</span>
  <span m='902870'>talking</span> <span m='903230'>about.</span> </p><p><span m='907400'>OK,</span>
  <span m='907770'>so</span> <span m='908700'>the</span> <span m='908790'>important</span>
  <span m='909180'>thing</span> <span m='909420'>from</span> <span m='909570'>this</span>
  <span m='909750'>example</span> <span m='910260'>is</span> <span m='910650'>the</span>
  <span m='910770'>functional</span> <span m='911250'>form</span> <span m='911790'>looks</span>
  <span m='912060'>exactly</span> <span m='912540'>the</span> <span m='912660'>same.</span>
  <span m='913920'>I</span> <span m='913980'>had</span> <span m='914100'>a</span>
  <span m='914160'>functional</span> <span m='914580'>form</span> <span m='914850'>in</span>
  <span m='914970'>time,</span> <span m='915330'>e</span> <span m='915470'>to the</span>
  <span m='915570'>minus</span> <span m='915990'>t,</span> <span m='916290'>e to the</span>
  <span m='916560'>minus</span> <span m='916920'>t.</span> <span m='918390'>It</span>
  <span m='918510'>was</span> <span m='918720'>that</span> <span m='918930'>functional</span>
  <span m='919350'>form</span> <span m='919650'>of</span> <span m='919740'>time</span>
  <span m='921000'>that</span> <span m='921240'>I</span> <span m='921450'>crank</span>
  <span m='921900'>through</span> <span m='922110'>the</span> <span m='922230'>integration</span>
  <span m='922800'>for,</span> <span m='924240'>and</span> <span m='924390'>it's</span>
  <span m='924510'>not</span> <span m='924720'>surprising</span> <span m='925200'>then</span>
  <span m='925380'>that</span> <span m='925500'>I</span> <span m='925590'>get</span>
  <span m='926430'>a</span> <span m='926520'>functional</span> <span m='927090'>form</span>
  <span m='927420'>for</span> <span m='927570'>the</span> <span m='927660'>s</span>
  <span m='927970'>transform</span> <span m='928380'>that</span> <span m='928500'>looks</span>
  <span m='928710'>the</span> <span m='928800'>same.</span> <span m='930030'>If</span>
  <span m='930150'>you</span> <span m='930240'>start</span> <span m='930450'>with</span>
  <span m='930600'>functional</span> <span m='930930'>forms</span> <span m='931200'>in</span>
  <span m='931320'>time</span> <span m='931620'>that</span> <span m='931720'>look</span>
  <span m='931890'>the</span> <span m='931980'>same,</span> <span m='932190'>you</span>
  <span m='932250'>get</span> <span m='932370'>functional</span> <span m='932730'>forms</span>
  <span m='933480'>in</span> <span m='933630'>s</span> <span m='934875'>that</span>
  <span m='935290'>look</span> <span m='935470'>the</span> <span m='935590'>same.</span>
  </p><p><span m='937160'>However,</span> <span m='938050'>since</span> <span m='938410'>the</span>
  <span m='938620'>region</span> <span m='939040'>of</span> <span m='939160'>t</span>
  <span m='940180'>was</span> <span m='940420'>different</span> <span m='940900'>for</span>
  <span m='941080'>the</span> <span m='941200'>two</span> <span m='941380'>functions</span>
  <span m='942160'>the</span> <span m='942280'>region</span> <span m='942610'>of</span>
  <span m='942700'>s</span> <span m='943450'>is</span> <span m='943630'>different.</span>
  <span m='945990'>There's</span> <span m='946140'>also</span> <span m='946470'>the</span>
  <span m='946590'>negative</span> <span m='946980'>sign.</span> <span m='947400'>There's</span>
  <span m='947640'>the</span> <span m='947730'>fact</span> <span m='948000'>that</span>
  <span m='948150'>this</span> <span m='948360'>flipped</span> <span m='950100'>this</span>
  <span m='950310'>way,</span> <span m='952190'>and</span> <span m='952340'>that's</span>
  <span m='952580'>related</span> <span m='953000'>to</span> <span m='953120'>the</span>
  <span m='953240'>fact</span> <span m='953570'>that</span> <span m='953720'>my</span>
  <span m='953900'>region</span> <span m='954290'>of</span> <span m='954350'>integration</span>
  <span m='955220'>extends</span> <span m='955670'>from</span> <span m='955820'>minus</span>
  <span m='956150'>infinity</span> <span m='956570'>to</span> <span m='956690'>0</span>
  <span m='957080'>versus</span> <span m='957410'>0</span> <span m='957740'>to</span>
  <span m='957860'>infinity.</span> <span m='959060'>The</span> <span m='959150'>important</span>
  <span m='960950'>limit</span> <span m='962440'>flipped</span> <span m='962720'>from</span>
  <span m='962930'>being</span> <span m='963350'>the</span> <span m='963590'>bottom</span>
  <span m='963920'>limit</span> <span m='964160'>to</span> <span m='964280'>the</span>
  <span m='964400'>top</span> <span m='964610'>limit.</span> <span m='966020'>OK,</span>
  <span m='966420'>that's</span> <span m='966660'>roughly</span> <span m='967010'>it.</span>
  </p><p><span m='970610'>So</span> <span m='971040'>just</span> <span m='971250'>to</span>
  <span m='971310'>make</span> <span m='971430'>sure</span> <span m='971610'>that</span>
  <span m='971730'>everybody</span> <span m='971980'>is</span> <span m='972150'>with</span>
  <span m='972330'>me,</span> <span m='972960'>what's</span> <span m='973320'>the</span>
  <span m='973590'>Laplace</span> <span m='973950'>transform</span> <span m='974490'>of</span>
  <span m='974610'>this</span> <span m='974730'>symmetric</span> <span m='975180'>looking</span>
  <span m='975450'>function?</span> </p><p><span m='1070670'>So</span> <span m='1070750'>which</span>
  <span m='1070900'>of</span> <span m='1070960'>those</span> <span m='1071140'>functions</span>
  <span m='1071710'>is</span> <span m='1072130'>the</span> <span m='1072700'>Laplace</span>
  <span m='1072800'>transform</span> <span m='1073330'>of</span> <span m='1073420'>the</span>
  <span m='1073510'>symmetric</span> <span m='1073870'>function?</span> <span m='1077390'>It's</span>
  <span m='1077690'>about</span> <span m='1077990'>3</span> <span m='1078320'>calories</span>
  <span m='1078540'>to raise</span> <span m='1078820'>your hand,</span> <span m='1079320'>right?</span>
  <span m='1080750'>Good</span> <span m='1080900'>exercise,</span> <span m='1081440'>makes</span>
  <span m='1081650'>you</span> <span m='1081710'>breathe.</span> <span m='1083420'>The</span>
  <span m='1083510'>answer</span> <span m='1083780'>is?</span> <span m='1086130'>Oh,</span>
  <span m='1086620'>come on.</span> </p><p><span m='1090540'>OK,</span> <span m='1090970'>it's</span>
  <span m='1091380'>more</span> <span m='1091540'>like</span> <span m='1092230'>90%</span>
  <span m='1092980'>correct.</span> <span m='1094960'>So</span> <span m='1095620'>not</span>
  <span m='1095890'>everybody</span> <span m='1096250'>has</span> <span m='1096400'>it</span>
  <span m='1096490'>right.</span> <span m='1097540'>What</span> <span m='1097720'>am</span>
  <span m='1097780'>I</span> <span m='1097840'>going</span> <span m='1098020'>to</span>
  <span m='1098110'>do?</span> <span m='1099330'>It's</span> <span m='1099730'>just</span>
  <span m='1099940'>like</span> <span m='1100120'>the</span> <span m='1100180'>last</span>
  <span m='1100420'>one,</span> <span m='1100570'>right?</span> <span m='1101330'>Just</span>
  <span m='1101450'>stick</span> <span m='1102160'>it</span> <span m='1102250'>in.</span>
  </p><p><span m='1105850'>If</span> <span m='1106000'>you</span> <span m='1106120'>think</span>
  <span m='1106360'>about</span> <span m='1108070'>writing</span> <span m='1108460'>the</span>
  <span m='1108670'>integral</span> <span m='1109150'>of</span> <span m='1109270'>this</span>
  <span m='1109810'>the</span> <span m='1110020'>complicated</span> <span m='1110740'>part</span>
  <span m='1111100'>is</span> <span m='1111310'>this</span> <span m='1111460'>absolute</span>
  <span m='1111880'>value</span> <span m='1112300'>sine</span> <span m='1112660'>thing.</span>
  <span m='1113560'>So</span> <span m='1113770'>split</span> <span m='1114010'>it</span>
  <span m='1114130'>into</span> <span m='1114310'>two</span> <span m='1114520'>parts,</span>
  <span m='1114940'>that</span> <span m='1115120'>way</span> <span m='1115390'>the</span>
  <span m='1115510'>absolute</span> <span m='1115840'>value is</span> <span m='1116260'>one</span>
  <span m='1116470'>thing</span> <span m='1116620'>when</span> <span m='1116770'>t</span>
  <span m='1116950'>is</span> <span m='1117100'>bigger</span> <span m='1117340'>than</span>
  <span m='1117460'>0</span> <span m='1117790'>and</span> <span m='1117900'>it's</span>
  <span m='1118030'>a</span> <span m='1118090'>different</span> <span m='1118360'>thing</span>
  <span m='1118510'>when</span> <span m='1118630'>t</span> <span m='1118810'>is</span>
  <span m='1118930'>less</span> <span m='1119140'>than</span> <span m='1119260'>0.</span>
  <span m='1123120'>Now</span> <span m='1123310'>looks</span> <span m='1123490'>like</span>
  <span m='1123620'>just</span> <span m='1123810'>the</span> <span m='1123900'>sum</span>
  <span m='1124140'>of</span> <span m='1124260'>two</span> <span m='1125220'>functions</span>
  <span m='1125730'>that</span> <span m='1125910'>are</span> <span m='1126060'>both</span>
  <span m='1126360'>trivial.</span> <span m='1127080'>One</span> <span m='1127350'>is</span>
  <span m='1127980'>right</span> <span m='1128250'>sided,</span> <span m='1128640'>the</span>
  <span m='1128760'>other</span> <span m='1128940'>is</span> <span m='1129030'>left</span>
  <span m='1129270'>sided,</span> <span m='1129750'>so</span> <span m='1129930'>we</span>
  <span m='1130050'>might</span> <span m='1130170'>be</span> <span m='1130320'>expecting</span>
  <span m='1130710'>something</span> <span m='1131010'>a</span> <span m='1131070'>little</span>
  <span m='1131310'>funky</span> <span m='1131730'>compared</span> <span m='1132090'>to</span>
  <span m='1132150'>the</span> <span m='1132270'>last</span> <span m='1132540'>one.</span>
  <span m='1137230'>So</span> <span m='1137460'>this</span> <span m='1137700'>guy</span>
  <span m='1138070'>that is</span> <span m='1138450'>left</span> <span m='1138660'>sided</span>
  <span m='1138900'>in</span> <span m='1139110'>time</span> <span m='1141640'>ends</span>
  <span m='1141940'>up</span> <span m='1142180'>with</span> <span m='1142450'>a</span>
  <span m='1142510'>left-sided</span> <span m='1143140'>transform,</span> <span m='1146420'>just</span>
  <span m='1146600'>like</span> <span m='1146750'>the</span> <span m='1146810'>previous</span>
  <span m='1147200'>examples.</span> </p><p><span m='1149040'>So</span> <span m='1149090'>we</span>
  <span m='1149240'>see</span> <span m='1149510'>that</span> <span m='1149870'>this</span>
  <span m='1150680'>part,</span> <span m='1151980'>which</span> <span m='1152150'>looks</span>
  <span m='1152390'>like</span> <span m='1152630'>a</span> <span m='1152690'>pole</span>
  <span m='1153320'>at</span> <span m='1153640'>1,</span> <span m='1156980'>so</span>
  <span m='1157130'>we're</span> <span m='1157220'>going</span> <span m='1157330'>to</span>
  <span m='1157430'>get</span> <span m='1157680'>a</span> <span m='1158090'>part</span>
  <span m='1158390'>of</span> <span m='1158450'>the</span> <span m='1158670'>transform</span>
  <span m='1159290'>that</span> <span m='1159440'>has</span> <span m='1159590'>a</span>
  <span m='1159650'>pole</span> <span m='1160010'>at</span> <span m='1160100'>1.</span>
  <span m='1160940'>And</span> <span m='1161060'>it's</span> <span m='1161180'>going</span>
  <span m='1161300'>to</span> <span m='1161390'>be</span> <span m='1162020'>valid</span>
  <span m='1162590'>for</span> <span m='1162860'>regions</span> <span m='1163370'>in</span>
  <span m='1163490'>s</span> <span m='1163690'>space</span> <span m='1164360'>for</span>
  <span m='1164680'>s</span> <span m='1165170'>magnitude</span> <span m='1165860'>less</span>
  <span m='1166100'>than</span> <span m='1166280'>1,</span> <span m='1167300'>OK.</span>
  <span m='1168450'>Then</span> <span m='1168740'>we're</span> <span m='1168800'>going</span>
  <span m='1168920'>to</span> <span m='1168980'>get</span> <span m='1169100'>this</span>
  <span m='1169370'>other</span> <span m='1169640'>piece,</span> <span m='1173200'>that</span>
  <span m='1173510'>corresponds</span> <span m='1173930'>to</span> <span m='1173990'>a</span>
  <span m='1174050'>pole</span> <span m='1174410'>minus</span> <span m='1174790'>1.</span>
  <span m='1177215'>And</span> <span m='1177700'>it's</span> <span m='1177920'>right</span>
  <span m='1178190'>sided,</span> <span m='1178700'>so</span> <span m='1178910'>like</span>
  <span m='1179120'>the</span> <span m='1179210'>right</span> <span m='1179420'>sided</span>
  <span m='1179780'>examples</span> <span m='1180260'>that</span> <span m='1180350'>we</span>
  <span m='1180440'>saw</span> <span m='1180650'>before</span> <span m='1181130'>there's</span>
  <span m='1181310'>a</span> <span m='1181390'>right</span> <span m='1181670'>sided</span>
  <span m='1182060'>region</span> <span m='1182390'>of</span> <span m='1182480'>convergence</span>
  <span m='1182990'>here.</span> <span m='1184500'>So</span> <span m='1184520'>it's</span>
  <span m='1184610'>going</span> <span m='1184730'>to</span> <span m='1184790'>be</span>
  <span m='1184910'>right</span> <span m='1185470'>of</span> <span m='1185660'>its</span>
  <span m='1186040'>pole,</span> <span m='1186500'>but</span> <span m='1186680'>it's</span>
  <span m='1186860'>pole is</span> <span m='1187190'>minus</span> <span m='1187610'>1.</span>
  </p><p><span m='1189240'>So</span> <span m='1189380'>in</span> <span m='1189500'>sum,</span>
  <span m='1189890'>the</span> <span m='1190010'>region</span> <span m='1190400'>is</span>
  <span m='1190520'>going</span> <span m='1190640'>to</span> <span m='1190730'>be</span>
  <span m='1191100'>to</span> <span m='1191240'>the</span> <span m='1192050'>right</span>
  <span m='1192530'>of</span> <span m='1192680'>the</span> <span m='1192800'>pole</span>
  <span m='1193280'>at</span> <span m='1193490'>minus</span> <span m='1193990'>1,</span>
  <span m='1194450'>and</span> <span m='1194630'>to</span> <span m='1194780'>the</span>
  <span m='1194900'>left</span> <span m='1195410'>of</span> <span m='1195560'>the</span>
  <span m='1195680'>pole</span> <span m='1196100'>at</span> <span m='1196310'>1</span>
  <span m='1197940'>because</span> <span m='1198180'>we</span> <span m='1198270'>have</span>
  <span m='1198390'>to</span> <span m='1198480'>be</span> <span m='1198600'>in</span>
  <span m='1198690'>the</span> <span m='1198780'>part</span> <span m='1198990'>of
  s</span> <span m='1199160'>space</span> <span m='1199650'>where</span> <span m='1200220'>both</span>
  <span m='1200550'>of</span> <span m='1200670'>those</span> <span m='1200940'>two</span>
  <span m='1202320'>integrals</span> <span m='1202710'>converged.</span> <span m='1204520'>So</span>
  <span m='1204570'>we</span> <span m='1204720'>end</span> <span m='1204960'>up</span>
  <span m='1205500'>with</span> <span m='1205700'>the</span> <span m='1205830'>ROC</span>
  <span m='1206270'>being</span> <span m='1206580'>the</span> <span m='1206700'>intersection,</span>
  <span m='1208430'>OK.</span> <span m='1209870'>So</span> <span m='1210050'>we</span>
  <span m='1210170'>get</span> <span m='1210790'>a pole</span> <span m='1211250'>0</span>
  <span m='1211560'>pattern</span> <span m='1211880'>that</span> <span m='1211970'>looks</span>
  <span m='1212150'>like</span> <span m='1212300'>this.</span> <span m='1212540'>There</span>
  <span m='1212630'>are</span> <span m='1212660'>two</span> <span m='1212840'>poles</span>
  <span m='1213140'>now.</span> <span m='1214580'>When</span> <span m='1214760'>you</span>
  <span m='1214880'>add</span> <span m='1215060'>together</span> <span m='1215840'>a</span>
  <span m='1215930'>part</span> <span m='1216230'>that</span> <span m='1216350'>looks</span>
  <span m='1216530'>like</span> <span m='1216680'>a</span> <span m='1216740'>pole</span>
  <span m='1216910'>a</span> <span m='1217010'>minus</span> <span m='1217310'>1</span>
  <span m='1217490'>and</span> <span m='1217550'>a</span> <span m='1217640'>part</span>
  <span m='1218030'>that</span> <span m='1218120'>looks</span> <span m='1218300'>like</span>
  <span m='1218420'>a</span> <span m='1218450'>pole at</span> <span m='1218860'>1,</span>
  <span m='1219440'>you</span> <span m='1219530'>get</span> <span m='1219770'>two</span>
  <span m='1220010'>poles.</span> </p><p><span m='1223500'>And</span> <span m='1223680'>the</span>
  <span m='1223800'>region</span> <span m='1224490'>becomes</span> <span m='1225030'>the</span>
  <span m='1225150'>band</span> <span m='1225480'>in</span> <span m='1225640'>between.</span>
  <span m='1227600'>Again,</span> <span m='1227960'>because</span> <span m='1228440'>the</span>
  <span m='1228640'>regions</span> <span m='1229160'>of</span> <span m='1229520'>s</span>
  <span m='1229850'>transforms</span> <span m='1230570'>because</span> <span m='1230870'>of</span>
  <span m='1230940'>Euler's</span> <span m='1231320'>expression</span> <span m='1231830'>is</span>
  <span m='1232280'>determined</span> <span m='1232640'>by</span> <span m='1232790'>the</span>
  <span m='1232880'>real</span> <span m='1233150'>part</span> <span m='1235000'>of</span>
  <span m='1235150'>s.</span> <span m='1235750'>So that</span> <span m='1236010'>we're</span>
  <span m='1236170'>always</span> <span m='1236410'>going</span> <span m='1236530'>to</span>
  <span m='1236590'>get</span> <span m='1236770'>some</span> <span m='1236980'>kind</span>
  <span m='1237160'>of</span> <span m='1237340'>vertical</span> <span m='1237700'>band.</span>
  <span m='1239950'>The</span> <span m='1240040'>band</span> <span m='1240360'>is</span>
  <span m='1240400'>always</span> <span m='1240730'>going</span> <span m='1240840'>to</span>
  <span m='1240910'>be</span> <span m='1241040'>delimited</span> <span m='1241450'>by</span>
  <span m='1241600'>a</span> <span m='1241660'>pole,</span> <span m='1242050'>just</span>
  <span m='1242230'>like</span> <span m='1242380'>it</span> <span m='1242470'>was</span>
  <span m='1242710'>in</span> <span m='1242790'>a</span> <span m='1242870'>z</span>
  <span m='1243040'>transform.</span> </p><p><span m='1245810'>There's</span> <span
  m='1246020'>two</span> <span m='1246200'>poles.</span> <span m='1246830'>So</span>
  <span m='1247070'>all</span> <span m='1247130'>we</span> <span m='1247280'>really</span>
  <span m='1247520'>need</span> <span m='1247670'>to</span> <span m='1247790'>worry</span>
  <span m='1247970'>about</span> <span m='1248240'>is</span> <span m='1248390'>which</span>
  <span m='1248630'>region</span> <span m='1250040'>bounded</span> <span m='1250430'>by</span>
  <span m='1250610'>two</span> <span m='1250850'>poles</span> <span m='1251330'>we're</span>
  <span m='1251510'>going</span> <span m='1251630'>to</span> <span m='1251690'>correspond</span>
  <span m='1252170'>to.</span> <span m='1254110'>OK,</span> <span m='1256030'>so</span>
  <span m='1256150'>the</span> <span m='1256300'>answer</span> <span m='1256520'>was</span>
  <span m='1256670'>two.</span> <span m='1259280'>Written</span> <span m='1259520'>in</span>
  <span m='1259640'>a</span> <span m='1259670'>little</span> <span m='1259880'>bit</span>
  <span m='1260000'>of</span> <span m='1260090'>a</span> <span m='1260150'>funky</span>
  <span m='1260480'>form,</span> <span m='1260910'>but</span> <span m='1261010'>if</span>
  <span m='1261110'>factor</span> <span m='1261470'>this</span> <span m='1261680'>you</span>
  <span m='1261770'>can</span> <span m='1261890'>see</span> <span m='1262070'>that</span>
  <span m='1262190'>there's</span> <span m='1262400'>two</span> <span m='1262580'>poles,</span>
  <span m='1263000'>one</span> <span m='1263150'>at</span> <span m='1263210'>1,</span>
  <span m='1263590'>and</span> <span m='1263900'>one</span> <span m='1264080'>at</span>
  <span m='1264140'>minus</span> <span m='1264440'>1.</span> </p><p><span m='1268570'>So</span>
  <span m='1269500'>hopefully</span> <span m='1269830'>that's</span> <span m='1270010'>all</span>
  <span m='1270130'>trivial,</span> <span m='1271360'>that's</span> <span m='1271540'>all</span>
  <span m='1271640'>stuff</span> <span m='1271930'>you</span> <span m='1271990'>can</span>
  <span m='1272080'>do</span> <span m='1272170'>in</span> <span m='1272260'>your</span>
  <span m='1272350'>sleep.</span> <span m='1275050'>What</span> <span m='1275200'>I</span>
  <span m='1275260'>want</span> <span m='1275410'>to</span> <span m='1275470'>do</span>
  <span m='1275590'>is</span> <span m='1275710'>think</span> <span m='1275890'>a</span>
  <span m='1275950'>little</span> <span m='1276160'>bit</span> <span m='1276280'>about</span>
  <span m='1276490'>what</span> <span m='1277150'>the</span> <span m='1277270'>implications</span>
  <span m='1277870'>are.</span> <span m='1278050'>What</span> <span m='1278170'>are</span>
  <span m='1278230'>we</span> <span m='1278350'>doing?</span> <span m='1279520'>What</span>
  <span m='1279880'>is</span> <span m='1282430'>a</span> <span m='1282510'>region</span>
  <span m='1282900'>of</span> <span m='1283020'>convergence?</span> </p><p><span m='1284440'>So</span>
  <span m='1284460'>I</span> <span m='1284550'>want</span> <span m='1284700'>to</span>
  <span m='1284790'>think</span> <span m='1285090'>now</span> <span m='1285750'>about</span>
  <span m='1287310'>four</span> <span m='1287580'>different</span> <span m='1287850'>functions,</span>
  <span m='1288330'>in</span> <span m='1288450'>four</span> <span m='1288630'>different</span>
  <span m='1288870'>poles</span> <span m='1289080'>zero</span> <span m='1289650'>patterns,</span>
  <span m='1290100'>in</span> <span m='1290220'>four</span> <span m='1290430'>different</span>
  <span m='1290700'>regions.</span> <span m='1292920'>And</span> <span m='1293040'>I</span>
  <span m='1293130'>want</span> <span m='1293250'>to</span> <span m='1293340'>think</span>
  <span m='1293550'>about</span> <span m='1293820'>the</span> <span m='1293890'>defining</span>
  <span m='1294520'>integral,</span> <span m='1294720'>that</span> <span m='1294840'>one</span>
  <span m='1294990'>up</span> <span m='1295110'>there.</span> <span m='1296430'>I</span>
  <span m='1296490'>want</span> <span m='1296610'>to</span> <span m='1296670'>think</span>
  <span m='1296820'>about</span> <span m='1297090'>x of</span> <span m='1297480'>s</span>
  <span m='1299910'>is</span> <span m='1300090'>the</span> <span m='1300350'>integral</span>
  <span m='1300630'>over</span> <span m='1301130'>all</span> <span m='1301390'>of</span>
  <span m='1301530'>time</span> <span m='1302530'>of</span> <span m='1302890'>x</span>
  <span m='1303120'>of</span> <span m='1303270'>te</span> <span m='1303750'>to</span>
  <span m='1303860'>the</span> <span m='1303960'>minus</span> <span m='1304350'>st</span>
  <span m='1304850'>dt.</span> </p><p><span m='1306210'>What</span> <span m='1306330'>are</span>
  <span m='1306360'>we</span> <span m='1306510'>doing</span> <span m='1307530'>when</span>
  <span m='1307680'>we</span> <span m='1307740'>take</span> <span m='1307920'>a</span>
  <span m='1308010'>Laplace</span> <span m='1308310'>transform?</span> <span m='1309120'>And</span>
  <span m='1309210'>what</span> <span m='1309330'>are</span> <span m='1309390'>we</span>
  <span m='1309480'>doing</span> <span m='1309840'>when</span> <span m='1309960'>we</span>
  <span m='1310050'>specify</span> <span m='1310500'>a</span> <span m='1310530'>region</span>
  <span m='1310860'>of</span> <span m='1310950'>convergence?</span> <span m='1313260'>Because</span>
  <span m='1313530'>I</span> <span m='1313620'>can</span> <span m='1313770'>help</span>
  <span m='1313980'>you</span> <span m='1314100'>think</span> <span m='1314400'>about</span>
  <span m='1315030'>what</span> <span m='1315270'>should</span> <span m='1315570'>the</span>
  <span m='1315720'>answer</span> <span m='1315990'>be,</span> <span m='1316650'>which</span>
  <span m='1316830'>is</span> <span m='1316920'>helpful</span> <span m='1317280'>when</span>
  <span m='1317400'>you're</span> <span m='1317490'>trying</span> <span m='1317820'>to</span>
  <span m='1317910'>think</span> <span m='1318090'>about</span> <span m='1318690'>does</span>
  <span m='1318840'>my</span> <span m='1319020'>answer</span> <span m='1319320'>make</span>
  <span m='1319530'>any</span> <span m='1319740'>sense?</span> <span m='1320160'>Or</span>
  <span m='1320280'>what</span> <span m='1320400'>am</span> <span m='1320520'>I</span>
  <span m='1320580'>doing</span> <span m='1320850'>anyway?</span> </p><p><span m='1323520'>So</span>
  <span m='1323760'>x1,</span> <span m='1324510'>this</span> <span m='1324690'>was</span>
  <span m='1325335'>e</span> <span m='1325620'>to</span> <span m='1325860'>the</span>
  <span m='1325920'>minus</span> <span m='1326260'>t.</span> <span m='1327870'>So</span>
  <span m='1328060'>it</span> <span m='1328240'>had</span> <span m='1328380'>a</span>
  <span m='1328440'>pole</span> <span m='1328710'>at</span> <span m='1328800'>minus</span>
  <span m='1329160'>1</span> <span m='1329460'>in the</span> <span m='1329550'>region</span>
  <span m='1329880'>to</span> <span m='1329970'>the</span> <span m='1330060'>right.</span>
  <span m='1330330'>Right-sided</span> <span m='1330810'>function,</span> <span m='1331140'>right-sided</span>
  <span m='1331620'>region.</span> <span m='1334840'>Here</span> <span m='1335740'>we</span>
  <span m='1335860'>have</span> <span m='1335980'>a</span> <span m='1336040'>more</span>
  <span m='1336220'>complicated</span> <span m='1336850'>function,</span> <span m='1337370'>which</span>
  <span m='1337420'>can</span> <span m='1337660'>be</span> <span m='1337960'>the</span>
  <span m='1338080'>sum</span> <span m='1338830'>of</span> <span m='1339070'>two</span>
  <span m='1339310'>poles,</span> <span m='1340390'>one</span> <span m='1340600'>at</span>
  <span m='1340690'>minus</span> <span m='1341050'>1</span> <span m='1341240'>and</span>
  <span m='1341330'>1</span> <span m='1341500'>at</span> <span m='1341590'>minus</span>
  <span m='1341920'>2.</span> <span m='1343990'>And</span> <span m='1344140'>we</span>
  <span m='1344260'>got</span> <span m='1344440'>a</span> <span m='1344500'>region</span>
  <span m='1344950'>that</span> <span m='1345040'>was</span> <span m='1345220'>to</span>
  <span m='1345370'>the</span> <span m='1345460'>right</span> <span m='1345670'>of</span>
  <span m='1345730'>the</span> <span m='1345820'>rightmost</span> <span m='1346250'>pole.</span>
  <span m='1347770'>Right-sided</span> <span m='1348330'>function,</span> <span m='1348700'>right-sided</span>
  <span m='1349180'>region.</span> </p><p><span m='1352620'>Here</span> <span m='1352870'>was</span>
  <span m='1353110'>x3,</span> <span m='1353950'>which</span> <span m='1354190'>was</span>
  <span m='1354370'>the</span> <span m='1354460'>negative</span> <span m='1354850'>part</span>
  <span m='1355090'>of</span> <span m='1355180'>that</span> <span m='1355370'>one.</span>
  <span m='1356080'>We</span> <span m='1356200'>got</span> <span m='1356500'>the</span>
  <span m='1356590'>same</span> <span m='1356860'>pole</span> <span m='1357190'>minus</span>
  <span m='1357520'>1</span> <span m='1357820'>one the</span> <span m='1357910'>left-sided</span>
  <span m='1358530'>region.</span> <span m='1360340'>And</span> <span m='1360490'>here</span>
  <span m='1360670'>was</span> <span m='1360820'>the</span> <span m='1360940'>symmetric</span>
  <span m='1361420'>one</span> <span m='1362170'>where</span> <span m='1362290'>we</span>
  <span m='1362410'>found</span> <span m='1362650'>that</span> <span m='1362770'>the</span>
  <span m='1362860'>region</span> <span m='1363160'>was</span> <span m='1363310'>in</span>
  <span m='1363370'>between.</span> <span m='1363910'>So</span> <span m='1364180'>what</span>
  <span m='1364300'>I</span> <span m='1364360'>want</span> <span m='1364510'>to</span>
  <span m='1364570'>think</span> <span m='1364720'>now</span> <span m='1365440'>is</span>
  <span m='1365710'>what</span> <span m='1365950'>happens</span> <span m='1366430'>when</span>
  <span m='1366610'>we</span> <span m='1366760'>have</span> <span m='1366940'>a</span>
  <span m='1367000'>particular</span> <span m='1367450'>value</span> <span m='1367870'>of</span>
  <span m='1367990'>s</span> <span m='1369250'>that</span> <span m='1369400'>is</span>
  <span m='1369550'>inside</span> <span m='1370030'>or</span> <span m='1370120'>outside</span>
  <span m='1370480'>those</span> <span m='1370720'>regions.</span> <span m='1371110'>What's</span>
  <span m='1371260'>really</span> <span m='1371470'>going</span> <span m='1371710'>on?</span>
  </p><p><span m='1373580'>So</span> <span m='1373660'>let's</span> <span m='1373840'>start</span>
  <span m='1374140'>by</span> <span m='1374290'>thinking</span> <span m='1374590'>about</span>
  <span m='1374800'>what</span> <span m='1374980'>would</span> <span m='1375130'>happen</span>
  <span m='1375460'>if</span> <span m='1375550'>I</span> <span m='1375640'>considered</span>
  <span m='1376150'>an</span> <span m='1376270'>s</span> <span m='1377200'>depicted</span>
  <span m='1377680'>by</span> <span m='1377890'>this</span> <span m='1378520'>red</span>
  <span m='1379240'>x.</span> <span m='1379580'>I</span> <span m='1379660'>probably</span>
  <span m='1380050'>shouldn't</span> <span m='1380260'>have</span> <span m='1380380'>used</span>
  <span m='1380560'>x.</span> <span m='1380830'>I</span> <span m='1380920'>should</span>
  <span m='1381070'>have</span> <span m='1381220'>probably</span> <span m='1381640'>used</span>
  <span m='1381880'>a</span> <span m='1381970'>star.</span> <span m='1382900'>That's</span>
  <span m='1383110'>not</span> <span m='1383350'>a</span> <span m='1383410'>pole.</span>
  <span m='1384550'>That's</span> <span m='1384820'>the</span> <span m='1384940'>value</span>
  <span m='1385360'>of</span> <span m='1385540'>s</span> <span m='1386140'>in</span>
  <span m='1386290'>this</span> <span m='1386470'>integral.</span> </p><p><span m='1389050'>What</span>
  <span m='1389290'>happens</span> <span m='1389770'>if</span> <span m='1389920'>I</span>
  <span m='1390040'>choose</span> <span m='1390730'>to</span> <span m='1390910'>integrate</span>
  <span m='1391420'>against</span> <span m='1391930'>the</span> <span m='1392050'>function</span>
  <span m='1392970'>e</span> <span m='1393370'>to</span> <span m='1393580'>the</span>
  <span m='1393940'>minus</span> <span m='1394360'>st</span> <span m='1394870'>where</span>
  <span m='1395110'>s is</span> <span m='1395430'>0?</span> <span m='1399430'>If</span>
  <span m='1399580'>I</span> <span m='1399670'>choose</span> <span m='1399970'>to</span>
  <span m='1400060'>integrate</span> <span m='1400450'>against</span> <span m='1400720'>that</span>
  <span m='1400870'>function,</span> <span m='1401230'>that</span> <span m='1401350'>function</span>
  <span m='1401670'>as</span> <span m='1401770'>depicted</span> <span m='1402160'>by</span>
  <span m='1402340'>red</span> <span m='1402610'>here.</span> <span m='1405120'>So</span>
  <span m='1405250'>the</span> <span m='1405370'>convergence</span> <span m='1405970'>of</span>
  <span m='1406030'>the</span> <span m='1406210'>integral,</span> <span m='1406660'>the</span>
  <span m='1406750'>convergence</span> <span m='1407230'>of</span> <span m='1407290'>the</span>
  <span m='1407380'>thing</span> <span m='1407560'>that</span> <span m='1407650'>I'm</span>
  <span m='1407740'>calling</span> <span m='1408040'>a Laplace</span> <span m='1408400'>transform</span>
  <span m='1408790'>depends</span> <span m='1409090'>entirely</span> <span m='1409690'>on</span>
  <span m='1409810'>the</span> <span m='1409900'>convergence</span> <span m='1410440'>of</span>
  <span m='1410540'>x.</span> <span m='1412500'>That's</span> <span m='1412770'>what</span>
  <span m='1412950'>s</span> <span m='1413100'>equals</span> <span m='1413310'>0</span>
  <span m='1413610'>means.</span> <span m='1416760'>s</span> <span m='1416980'>equals</span>
  <span m='1417220'>0</span> <span m='1417580'>says,</span> <span m='1419650'>the</span>
  <span m='1419860'>converge</span> <span m='1420290'>of</span> <span m='1420400'>the</span>
  <span m='1420500'>transform</span> <span m='1420820'>depends</span> <span m='1421120'>entirely</span>
  <span m='1421600'>on</span> <span m='1421690'>the</span> <span m='1421750'>convergence</span>
  <span m='1422230'>of</span> <span m='1422290'>the</span> <span m='1422410'>function.</span>
  </p><p><span m='1424810'>So</span> <span m='1424830'>that</span> <span m='1425100'>means</span>
  <span m='1425460'>that</span> <span m='1425580'>this</span> <span m='1425760'>function</span>
  <span m='1426090'>converges,</span> <span m='1426900'>it's</span> <span m='1427720'>in</span>
  <span m='1427860'>the</span> <span m='1427950'>region</span> <span m='1428220'>of</span>
  <span m='1428280'>convergence.</span> <span m='1431070'>This</span> <span m='1431250'>one</span>
  <span m='1431570'>converges,</span> <span m='1432270'>it's</span> <span m='1432480'>in</span>
  <span m='1432570'>the</span> <span m='1432660'>region</span> <span m='1432960'>of</span>
  <span m='1433050'>convergence.</span> <span m='1435310'>This</span> <span m='1435550'>one</span>
  <span m='1435730'>does</span> <span m='1436000'>not</span> <span m='1436330'>converge,</span>
  <span m='1436870'>this</span> <span m='1437020'>one</span> <span m='1437170'>diverges.</span>
  </p><p><span m='1439750'>As</span> <span m='1439870'>you</span> <span m='1439930'>go</span>
  <span m='1440050'>to</span> <span m='1440170'>minus</span> <span m='1440470'>infinity</span>
  <span m='1440950'>the</span> <span m='1441010'>function</span> <span m='1441720'>is</span>
  <span m='1441970'>unbounded.</span> <span m='1443890'>The</span> <span m='1444050'>transform</span>
  <span m='1444400'>doesn't</span> <span m='1444670'>exist.</span> <span m='1446320'>s
  equals</span> <span m='1446710'>0</span> <span m='1447040'>is</span> <span m='1447190'>not</span>
  <span m='1447520'>in</span> <span m='1447610'>the</span> <span m='1447700'>region.</span>
  <span m='1449370'>That's</span> <span m='1449610'>what</span> <span m='1449760'>it</span>
  <span m='1449850'>means.</span> <span m='1452920'>Here,</span> <span m='1453340'>if</span>
  <span m='1453520'>I</span> <span m='1453790'>integrate</span> <span m='1454240'>against</span>
  <span m='1454720'>e to</span> <span m='1455050'>the</span> <span m='1455170'>0</span>
  <span m='1457340'>both</span> <span m='1457610'>sides</span> <span m='1458000'>converge,</span>
  <span m='1458680'>there</span> <span m='1458750'>is</span> <span m='1458900'>no</span>
  <span m='1459020'>problem.</span> <span m='1460640'>I'm</span> <span m='1460820'>in</span>
  <span m='1460940'>the</span> <span m='1461030'>region.</span> </p><p><span m='1465120'>So</span>
  <span m='1465330'>now</span> <span m='1465600'>if</span> <span m='1465750'>I</span>
  <span m='1465840'>think</span> <span m='1466020'>about</span> <span m='1466260'>a</span>
  <span m='1466320'>different</span> <span m='1466710'>s,</span> <span m='1466980'>what</span>
  <span m='1467130'>if</span> <span m='1467190'>I</span> <span m='1467250'>move</span>
  <span m='1467960'>s</span> <span m='1468420'>a</span> <span m='1468510'>little</span>
  <span m='1468750'>bit</span> <span m='1468900'>to</span> <span m='1469020'>the</span>
  <span m='1469140'>left?</span> <span m='1470220'>Say,</span> <span m='1470610'>minus</span>
  <span m='1471000'>1/2.</span> <span m='1474150'>If</span> <span m='1474330'>I'm</span>
  <span m='1474810'>thinking</span> <span m='1475140'>about</span> <span m='1475380'>integrating</span>
  <span m='1476070'>against</span> <span m='1477600'>e</span> <span m='1478000'>to</span>
  <span m='1478110'>the</span> <span m='1478200'>minus</span> <span m='1478550'>st,</span>
  <span m='1479160'>and</span> <span m='1479280'>if</span> <span m='1479400'>s</span>
  <span m='1479610'>is</span> <span m='1479730'>minus</span> <span m='1480070'>1/2,</span>
  <span m='1480410'>that's</span> <span m='1480660'>e to</span> <span m='1480960'>the</span>
  <span m='1481050'>1/2</span> <span m='1481420'>t.</span> <span m='1484120'>e to</span>
  <span m='1484380'>the</span> <span m='1484500'>1/2</span> <span m='1484800'>t</span>
  <span m='1485040'>is</span> <span m='1485160'>a</span> <span m='1485220'>function</span>
  <span m='1485580'>that</span> <span m='1485670'>for</span> <span m='1485850'>all</span>
  <span m='1486090'>time</span> <span m='1488020'>becomes</span> <span m='1488470'>greater</span>
  <span m='1488830'>as</span> <span m='1488950'>I</span> <span m='1489010'>go</span>
  <span m='1489150'>toward</span> <span m='1489330'>positive</span> <span m='1489700'>infinity,</span>
  <span m='1490730'>exponentially</span> <span m='1491340'>greater.</span> <span m='1492850'>So</span>
  <span m='1492970'>if</span> <span m='1493030'>I</span> <span m='1493090'>think</span>
  <span m='1493300'>about</span> <span m='1493510'>what</span> <span m='1493690'>happens</span>
  <span m='1493960'>if</span> <span m='1494050'>I</span> <span m='1494530'>multiplied</span>
  <span m='1495490'>this</span> <span m='1495820'>x</span> <span m='1496150'>of</span>
  <span m='1496270'>t</span> <span m='1497080'>by</span> <span m='1497410'>that</span>
  <span m='1497860'>weighting</span> <span m='1498310'>function,</span> <span m='1500270'>does</span>
  <span m='1500570'>the</span> <span m='1500840'>product</span> <span m='1501500'>converge</span>
  <span m='1501805'>or</span> <span m='1502110'>diverge?</span> </p><p><span m='1505990'>It</span>
  <span m='1506370'>converges</span> <span m='1507500'>because</span> <span m='1508190'>the</span>
  <span m='1508310'>convergence</span> <span m='1509390'>of</span> <span m='1509630'>the</span>
  <span m='1509750'>blue</span> <span m='1510080'>line</span> <span m='1510860'>is</span>
  <span m='1511100'>faster</span> <span m='1511700'>than</span> <span m='1511850'>the</span>
  <span m='1511940'>divergence</span> <span m='1512660'>of</span> <span m='1512720'>the</span>
  <span m='1512810'>red</span> <span m='1513020'>line.</span> <span m='1515250'>Even</span>
  <span m='1515550'>though</span> <span m='1515730'>the</span> <span m='1515880'>red</span>
  <span m='1516150'>line</span> <span m='1516480'>is</span> <span m='1516690'>diverging,</span>
  <span m='1518400'>the</span> <span m='1518550'>product</span> <span m='1519600'>is</span>
  <span m='1519810'>overall</span> <span m='1520470'>convergent.</span> </p><p><span
  m='1522460'>OK</span> <span m='1522830'>that's</span> <span m='1523040'>because</span>
  <span m='1523400'>of</span> <span m='1523490'>the</span> <span m='1523670'>relative</span>
  <span m='1524120'>positions</span> <span m='1524570'>of</span> <span m='1524630'>the</span>
  <span m='1524750'>red</span> <span m='1524930'>x</span> <span m='1525140'>and</span>
  <span m='1525260'>the</span> <span m='1525500'>blue</span> <span m='1525770'>x.</span>
  <span m='1527470'>The</span> <span m='1527560'>blue</span> <span m='1527830'>function</span>
  <span m='1528280'>is</span> <span m='1528670'>converging</span> <span m='1529390'>faster</span>
  <span m='1529900'>than</span> <span m='1530050'>the</span> <span m='1530140'>red</span>
  <span m='1530350'>function</span> <span m='1530740'>is</span> <span m='1530860'>diverging.</span>
  <span m='1531640'>The</span> <span m='1531730'>product</span> <span m='1532240'>converges.</span>
  <span m='1534010'>So</span> <span m='1534520'>this</span> <span m='1534760'>x</span>
  <span m='1534970'>is</span> <span m='1535060'>in</span> <span m='1535150'>the</span>
  <span m='1535210'>region of</span> <span m='1535540'>convergence.</span> <span m='1536050'>That's</span>
  <span m='1536200'>what</span> <span m='1536290'>it</span> <span m='1536350'>means.</span>
  </p><p><span m='1538670'>Similarly</span> <span m='1539300'>here,</span> <span m='1539960'>this</span>
  <span m='1540170'>is</span> <span m='1540290'>diverging.</span> <span m='1541880'>The</span>
  <span m='1542000'>red</span> <span m='1542150'>curve</span> <span m='1542420'>is</span>
  <span m='1542510'>still</span> <span m='1542720'>diverging.</span> <span m='1543680'>It's</span>
  <span m='1543830'>the</span> <span m='1543890'>same</span> <span m='1544070'>red</span>
  <span m='1544220'>curves</span> <span m='1544520'>are</span> <span m='1544580'>all</span>
  <span m='1544790'>these</span> <span m='1545000'>red</span> <span m='1545150'>curves</span>
  <span m='1545420'>are</span> <span m='1545480'>diverging</span> <span m='1546020'>to</span>
  <span m='1546140'>the</span> <span m='1546200'>right.</span> <span m='1547700'>This</span>
  <span m='1547970'>one</span> <span m='1548210'>is</span> <span m='1548390'>converging.</span>
  <span m='1549960'>It's</span> <span m='1550160'>ultimately</span> <span m='1550880'>converging</span>
  <span m='1551630'>as</span> <span m='1551900'>the</span> <span m='1552020'>sum</span>
  <span m='1552260'>of</span> <span m='1552380'>two</span> <span m='1552590'>things,</span>
  <span m='1553100'>e</span> <span m='1553200'>to</span> <span m='1553320'>the</span>
  <span m='1553430'>minus</span> <span m='1553810'>t</span> <span m='1554060'>and</span>
  <span m='1554150'>e to the</span> <span m='1554390'>minus</span> <span m='1554690'>2t,</span>
  <span m='1555110'>both</span> <span m='1555440'>of</span> <span m='1555530'>which</span>
  <span m='1555740'>are</span> <span m='1555830'>fast</span> <span m='1558500'>compared</span>
  <span m='1558890'>to</span> <span m='1558980'>the</span> <span m='1559130'>explosion</span>
  <span m='1559670'>e to</span> <span m='1559890'>the</span> <span m='1560040'>1/2</span>
  <span m='1560340'>t.</span> <span m='1561670'>So</span> <span m='1562120'>I'm</span>
  <span m='1562200'>in</span> <span m='1562330'>the</span> <span m='1562420'>region.</span>
  </p><p><span m='1564880'>Here</span> <span m='1566860'>it's</span> <span m='1567040'>exploding</span>
  <span m='1567640'>in</span> <span m='1567760'>a</span> <span m='1567790'>region</span>
  <span m='1568150'>of</span> <span m='1568240'>time</span> <span m='1568480'>that</span>
  <span m='1568600'>I</span> <span m='1568660'>don't</span> <span m='1568810'>care</span>
  <span m='1569020'>about.</span> <span m='1572230'>And</span> <span m='1572400'>it's</span>
  <span m='1572550'>convergent</span> <span m='1573390'>for</span> <span m='1573570'>this</span>
  <span m='1573720'>region</span> <span m='1574020'>of</span> <span m='1574080'>time</span>
  <span m='1574320'>that</span> <span m='1574440'>I</span> <span m='1574530'>do</span>
  <span m='1574710'>care</span> <span m='1574890'>about,</span> <span m='1575640'>but</span>
  <span m='1575790'>it's</span> <span m='1575910'>not</span> <span m='1576120'>convergent</span>
  <span m='1576750'>enough.</span> <span m='1580620'>So</span> <span m='1581040'>the</span>
  <span m='1581190'>integral</span> <span m='1581610'>still</span> <span m='1581880'>diverges,</span>
  <span m='1582540'>I'm</span> <span m='1582720'>not</span> <span m='1583080'>in</span>
  <span m='1583230'>the</span> <span m='1583320'>region.</span> </p><p><span m='1585720'>And</span>
  <span m='1585840'>finally,</span> <span m='1586390'>this</span> <span m='1586500'>one</span>
  <span m='1587040'>is</span> <span m='1587190'>more</span> <span m='1587340'>complicated.</span>
  <span m='1588540'>The</span> <span m='1590010'>integrand,</span> <span m='1590710'>this</span>
  <span m='1591060'>thing</span> <span m='1591240'>that</span> <span m='1591360'>I'm</span>
  <span m='1591480'>integrating</span> <span m='1591930'>against,</span> <span m='1592950'>it's</span>
  <span m='1593190'>always</span> <span m='1595200'>becoming</span> <span m='1595620'>greater</span>
  <span m='1595890'>as</span> <span m='1595980'>I</span> <span m='1596040'>go</span>
  <span m='1596190'>toward</span> <span m='1596520'>positive</span> <span m='1597030'>infinity.</span>
  <span m='1598380'>That</span> <span m='1598560'>tends</span> <span m='1598860'>to</span>
  <span m='1598950'>be</span> <span m='1599040'>convergent</span> <span m='1599730'>on</span>
  <span m='1599880'>this</span> <span m='1600060'>side</span> <span m='1602460'>and</span>
  <span m='1602640'>divergent</span> <span m='1603330'>on that</span> <span m='1603750'>side,</span>
  <span m='1604010'>but</span> <span m='1604110'>it's</span> <span m='1604200'>not</span>
  <span m='1604410'>divergent</span> <span m='1604980'>enough</span> <span m='1606840'>to</span>
  <span m='1606960'>make</span> <span m='1607110'>the</span> <span m='1607230'>function</span>
  <span m='1607590'>not</span> <span m='1608100'>converge.</span> <span m='1609390'>So</span>
  <span m='1609570'>I'm</span> <span m='1609660'>in</span> <span m='1609750'>the</span>
  <span m='1609840'>region.</span> </p><p><span m='1612430'>If</span> <span m='1612640'>I</span>
  <span m='1612760'>make</span> <span m='1613360'>an</span> <span m='1613510'>even</span>
  <span m='1613870'>bigger</span> <span m='1614790'>pole.</span> <span m='1615220'>So</span>
  <span m='1615400'>say</span> <span m='1615910'>I</span> <span m='1616000'>put</span>
  <span m='1618170'>e to the</span> <span m='1618510'>st,</span> <span m='1618850'>if</span>
  <span m='1618940'>I</span> <span m='1619000'>put</span> <span m='1619210'>that</span>
  <span m='1619480'>at</span> <span m='1619750'>minus</span> <span m='1620500'>1</span>
  <span m='1620770'>1/2,</span> <span m='1623890'>then</span> <span m='1624490'>that</span>
  <span m='1624790'>is</span> <span m='1625120'>fast</span> <span m='1625480'>enough</span>
  <span m='1625930'>that</span> <span m='1626080'>it</span> <span m='1626200'>breaks</span>
  <span m='1626650'>the</span> <span m='1626770'>product.</span> <span m='1628000'>The</span>
  <span m='1628120'>product</span> <span m='1628510'>is</span> <span m='1628630'>no</span>
  <span m='1628780'>longer</span> <span m='1629290'>integrable.</span> <span m='1631520'>So</span>
  <span m='1631730'>this</span> <span m='1632030'>divergent</span> <span m='1632780'>trend</span>
  <span m='1633260'>is</span> <span m='1633380'>enough</span> <span m='1633800'>to</span>
  <span m='1634010'>make</span> <span m='1634190'>that</span> <span m='1634610'>diverge.</span>
  <span m='1635990'>I'm</span> <span m='1636140'>not</span> <span m='1636470'>in</span>
  <span m='1636590'>the</span> <span m='1636680'>region</span> <span m='1636980'>anymore.</span>
  </p><p><span m='1639080'>Similarly</span> <span m='1639620'>here,</span> <span m='1640760'>I'm</span>
  <span m='1640940'>not</span> <span m='1641180'>in</span> <span m='1641330'>the</span>
  <span m='1641390'>region</span> <span m='1642080'>because</span> <span m='1642440'>I've</span>
  <span m='1642620'>made</span> <span m='1642860'>it</span> <span m='1642980'>fast</span>
  <span m='1643400'>enough</span> <span m='1644300'>that</span> <span m='1644510'>one</span>
  <span m='1644900'>of</span> <span m='1644960'>the</span> <span m='1645080'>parts</span>
  <span m='1646310'>diverges.</span> <span m='1650170'>One</span> <span m='1650320'>of</span>
  <span m='1650380'>the</span> <span m='1650440'>parts</span> <span m='1650860'>coverages,</span>
  <span m='1651280'>but</span> <span m='1651400'>they</span> <span m='1651490'>have</span>
  <span m='1651580'>to</span> <span m='1651700'>both</span> <span m='1653050'>converge</span>
  <span m='1653590'>in</span> <span m='1653680'>order</span> <span m='1653890'>for</span>
  <span m='1654010'>the</span> <span m='1654130'>interval</span> <span m='1654550'>to</span>
  <span m='1654730'>converge.</span> <span m='1657190'>Here,</span> <span m='1658000'>I</span>
  <span m='1658120'>have</span> <span m='1658300'>finally</span> <span m='1658780'>made</span>
  <span m='1659080'>the</span> <span m='1659230'>left-hand</span> <span m='1659770'>side</span>
  <span m='1660070'>convergent</span> <span m='1660790'>enough</span> <span m='1661600'>to</span>
  <span m='1661720'>make</span> <span m='1661960'>the</span> <span m='1662080'>product</span>
  <span m='1662560'>converge.</span> <span m='1664750'>So</span> <span m='1664930'>that's</span>
  <span m='1665230'>fine.</span> <span m='1666880'>And</span> <span m='1667060'>here,</span>
  <span m='1667870'>this</span> <span m='1668080'>is</span> <span m='1668200'>accelerating</span>
  <span m='1668830'>so</span> <span m='1669100'>fast</span> <span m='1670030'>that</span>
  <span m='1670300'>although</span> <span m='1670680'>it</span> <span m='1670730'>was</span>
  <span m='1670800'>stabilizing</span> <span m='1671530'>here</span> <span m='1672820'>it</span>
  <span m='1672940'>became</span> <span m='1673940'>non-convergent</span> <span m='1674740'>over</span>
  <span m='1674950'>here.</span> </p><p><span m='1677050'>What</span> <span m='1677200'>I</span>
  <span m='1677260'>want</span> <span m='1677470'>you</span> <span m='1677560'>to</span>
  <span m='1677650'>get</span> <span m='1677890'>from</span> <span m='1678100'>this</span>
  <span m='1678370'>is</span> <span m='1678520'>the</span> <span m='1678640'>idea</span>
  <span m='1679090'>that</span> <span m='1679300'>you</span> <span m='1679450'>can</span>
  <span m='1679600'>think</span> <span m='1679840'>physically</span> <span m='1680350'>about</span>
  <span m='1680560'>what</span> <span m='1680770'>the</span> <span m='1680950'>region</span>
  <span m='1681370'>of</span> <span m='1681460'>convergence</span> <span m='1681845'>is.</span>
  <span m='1682230'>The</span> <span m='1682280'>region</span> <span m='1682600'>of</span>
  <span m='1682720'>convergence</span> <span m='1683290'>is</span> <span m='1683410'>a</span>
  <span m='1683470'>function</span> <span m='1684670'>that</span> <span m='1684850'>I</span>
  <span m='1684940'>stick</span> <span m='1685280'>into</span> <span m='1685450'>the</span>
  <span m='1685600'>integral</span> <span m='1687850'>to</span> <span m='1687940'>make</span>
  <span m='1688090'>the</span> <span m='1688210'>integral</span> <span m='1688540'>converge.</span>
  <span m='1690010'>So</span> <span m='1690160'>the</span> <span m='1690280'>region</span>
  <span m='1690670'>of</span> <span m='1690760'>convergence</span> <span m='1691270'>corresponds</span>
  <span m='1691810'>to</span> <span m='1691930'>those</span> <span m='1692200'>exponents</span>
  <span m='1692770'>that</span> <span m='1692920'>makes</span> <span m='1693130'>sense</span>
  <span m='1695230'>for</span> <span m='1695530'>which</span> <span m='1695770'>the</span>
  <span m='1695950'>integral</span> <span m='1696460'>will</span> <span m='1696760'>converge.</span>
  </p><p><span m='1697990'>OK,</span> <span m='1698260'>with</span> <span m='1698410'>that</span>
  <span m='1698620'>vast</span> <span m='1699040'>new</span> <span m='1699220'>insight</span>
  <span m='1701310'>this</span> <span m='1701560'>problem</span> <span m='1701850'>is</span>
  <span m='1701950'>now</span> <span m='1702110'>trivial.</span> <span m='1705080'>Enumerate</span>
  <span m='1705830'>all</span> <span m='1706130'>possible</span> <span m='1706790'>functions</span>
  <span m='1710870'>x</span> <span m='1711050'>of</span> <span m='1711200'>t</span>
  <span m='1711950'>for</span> <span m='1712130'>which</span> <span m='1712340'>that's</span>
  <span m='1712580'>the</span> <span m='1712770'>transform.</span> </p><p><span m='1812300'>So</span>
  <span m='1812450'>how</span> <span m='1812510'>many</span> <span m='1812690'>functions</span>
  <span m='1813080'>are</span> <span m='1813170'>there?</span> <span m='1819640'>Keep</span>
  <span m='1819790'>going,</span> <span m='1820090'>keep</span> <span m='1820210'>going.</span>
  <span m='1820450'>I'm</span> <span m='1820600'>still</span> <span m='1820840'>looking</span>
  <span m='1821050'>for</span> <span m='1821230'>a</span> <span m='1821260'>right</span>
  <span m='1821470'>answer.</span> <span m='1824140'>That's</span> <span m='1824500'>a</span>
  <span m='1824590'>clue.</span> <span m='1825630'>Right,</span> <span m='1826030'>I</span>
  <span m='1826090'>don't</span> <span m='1826240'>see</span> <span m='1826390'>a</span>
  <span m='1826420'>right</span> <span m='1826600'>answer</span> <span m='1826840'>yet.</span>
  <span m='1827170'>So</span> <span m='1827320'>keep</span> <span m='1827500'>going.</span>
  <span m='1827990'>Keep</span> <span m='1828310'>going.</span> </p><p><span m='1828790'>Actually,</span>
  <span m='1829070'>I</span> <span m='1829130'>do</span> <span m='1829240'>now.</span>
  <span m='1831030'>I</span> <span m='1831120'>see</span> <span m='1831300'>two</span>
  <span m='1831480'>right</span> <span m='1831690'>answers.</span> <span m='1832470'>Can</span>
  <span m='1832590'>we</span> <span m='1832950'>make</span> <span m='1833160'>it</span>
  <span m='1833220'>three?</span> <span m='1834000'>Going</span> <span m='1834180'>once.</span>
  <span m='1834650'>Going</span> <span m='1834810'>twice.</span> <span m='1836390'>Two</span>
  <span m='1836550'>right</span> <span m='1836670'>answers?</span> </p><p><span m='1840790'>OK,</span>
  <span m='1841050'>the</span> <span m='1841140'>right</span> <span m='1841320'>answer</span>
  <span m='1841600'>is</span> <span m='1841800'>three.</span> <span m='1843650'>So</span>
  <span m='1843770'>now</span> <span m='1843920'>that</span> <span m='1844040'>I've</span>
  <span m='1844160'>told</span> <span m='1844340'>you</span> <span m='1844430'>the</span>
  <span m='1844520'>right</span> <span m='1844670'>answer,</span> <span m='1845480'>you</span>
  <span m='1845780'>rationalize</span> <span m='1846410'>for</span> <span m='1846590'>me</span>
  <span m='1846740'>why</span> <span m='1847020'>is</span> <span m='1847190'>the</span>
  <span m='1847250'>right</span> <span m='1847400'>answer</span> <span m='1847640'>three?</span>
  <span m='1853060'>Talk to</span> <span m='1853310'>your</span> <span m='1853410'>neighbor.</span>
  <span m='1854230'>Why is</span> <span m='1854600'>the right</span> <span m='1854980'>answer
  three?</span> </p><p><span m='1856968'>[INTERPOSING VOICES]</span> </p><p></p><p><span
  m='1923640'>OK,</span> <span m='1923920'>who</span> <span m='1924040'>can</span>
  <span m='1924190'>volunteer</span> <span m='1925450'>a</span> <span m='1926860'>concise</span>
  <span m='1927460'>statement</span> <span m='1928060'>for</span> <span m='1928280'>why</span>
  <span m='1928740'>the</span> <span m='1928910'>right</span> <span m='1929210'>answer</span>
  <span m='1929470'>is</span> <span m='1929650'>three</span> <span m='1929920'>and</span>
  <span m='1930010'>not</span> <span m='1930220'>four?</span> <span m='1933570'>Yes?</span>
  </p><p><span m='1934524'>[INAUDIBLE]</span> </p><p></p><p><span m='1939300'>That's</span>
  <span m='1939450'>exactly</span> <span m='1940110'>right.</span> <span m='1940460'>There</span>
  <span m='1940740'>are</span> <span m='1941150'>two poles,</span> <span m='1941560'>and</span>
  <span m='1941710'>there</span> <span m='1941830'>are</span> <span m='1941920'>three</span>
  <span m='1942220'>ways</span> <span m='1942490'>you</span> <span m='1942550'>can</span>
  <span m='1942700'>divide</span> <span m='1943000'>up</span> <span m='1944490'>the</span>
  <span m='1944850'>s</span> <span m='1945135'>plane</span> <span m='1945930'>by</span>
  <span m='1946110'>two</span> <span m='1946290'>poles.</span> <span m='1947920'>So</span>
  <span m='1949030'>there's</span> <span m='1949240'>four</span> <span m='1949840'>functions</span>
  <span m='1950260'>here,</span> <span m='1950440'>let's</span> <span m='1950620'>think</span>
  <span m='1950740'>about</span> <span m='1952210'>four</span> <span m='1953275'>s</span>
  <span m='1953600'>planes.</span> </p><p><span m='1958680'>So</span> <span m='1959580'>each</span>
  <span m='1959790'>of</span> <span m='1959850'>these</span> <span m='1960090'>functions--</span>
  <span m='1960830'>so</span> <span m='1961030'>here's</span> <span m='1961530'>a</span>
  <span m='1961590'>pole</span> <span m='1962100'>at</span> <span m='1962220'>minus</span>
  <span m='1962610'>2.</span> <span m='1962940'>Here's</span> <span m='1963180'>a</span>
  <span m='1963240'>pole at</span> <span m='1963600'>2.</span> <span m='1964740'>Minus</span>
  <span m='1965040'>2,</span> <span m='1965190'>2,</span> <span m='1965430'>minus</span>
  <span m='1965690'>2,</span> <span m='1965830'>2,</span> <span m='1966000'>minus
  2,</span> <span m='1966310'>2.</span> <span m='1966630'>They</span> <span m='1966810'>all</span>
  <span m='1967080'>have</span> <span m='1967500'>the</span> <span m='1967590'>same</span>
  <span m='1967860'>poles.</span> </p><p><span m='1974390'>OK,</span> <span m='1975590'>where's</span>
  <span m='1976080'>the</span> <span m='1976170'>region</span> <span m='1976665'>that</span>
  <span m='1977160'>corresponds</span> <span m='1977655'>to</span> <span m='1978150'>function</span>
  <span m='1978390'>one?</span> <span m='1983660'>So</span> <span m='1983740'>here's</span>
  <span m='1985390'>pole</span> <span m='1985760'>at</span> <span m='1985840'>minus</span>
  <span m='1986260'>2.</span> <span m='1986680'>e to</span> <span m='1986870'>the</span>
  <span m='1986950'>minus</span> <span m='1987280'>2t</span> <span m='1987700'>corresponds</span>
  <span m='1988300'>to</span> <span m='1989230'>a</span> <span m='1989350'>pole</span>
  <span m='1989860'>at</span> <span m='1990010'>minus</span> <span m='1990400'>2.</span>
  <span m='1991510'>u</span> <span m='1991780'>of</span> <span m='1991870'>t</span>
  <span m='1992290'>is</span> <span m='1992440'>right-sided</span> <span m='1993040'>function.</span>
  </p><p><span m='1993490'>Where's</span> <span m='1993790'>the</span> <span m='1994230'>region
  that</span> <span m='1994670'>corresponds</span> <span m='1995110'>to the pole</span>
  <span m='1995350'>minus</span> <span m='1995730'>2?</span> <span m='1997450'>To</span>
  <span m='1997600'>the</span> <span m='1997720'>right</span> <span m='1998110'>of</span>
  <span m='1998290'>minus</span> <span m='1998700'>2.</span> <span m='2001650'>So</span>
  <span m='2002010'>this</span> <span m='2002250'>first</span> <span m='2002520'>function</span>
  <span m='2002910'>converges</span> <span m='2003600'>to</span> <span m='2003750'>the</span>
  <span m='2003840'>right</span> <span m='2004880'>of</span> <span m='2004980'>minus</span>
  <span m='2005400'>2.</span> <span m='2007140'>This</span> <span m='2007470'>function</span>
  <span m='2007920'>is</span> <span m='2008040'>a pole</span> <span m='2008520'>at
  2,</span> <span m='2009120'>e</span> <span m='2009420'>to</span> <span m='2009520'>the</span>
  <span m='2009570'>2t</span> <span m='2010770'>and</span> <span m='2010980'>it's</span>
  <span m='2014290'>right</span> <span m='2014510'>sided.</span> <span m='2016970'>So</span>
  <span m='2017120'>it's</span> <span m='2017240'>right</span> <span m='2017450'>sided</span>
  <span m='2017780'>with</span> <span m='2017930'>regard</span> <span m='2018260'>to</span>
  <span m='2018380'>a</span> <span m='2018440'>pole</span> <span m='2018780'>at</span>
  <span m='2019060'>2.</span> </p><p><span m='2021700'>So</span> <span m='2021880'>what's</span>
  <span m='2022120'>the</span> <span m='2022420'>region that</span> <span m='2022900'>corresponds</span>
  <span m='2023380'>to a</span> <span m='2023860'>right-sided</span> <span m='2024130'>time</span>
  <span m='2024400'>function</span> <span m='2025780'>that</span> <span m='2026140'>corresponds</span>
  <span m='2026590'>to</span> <span m='2026680'>a</span> <span m='2026740'>pole</span>
  <span m='2027060'>at</span> <span m='2027380'>2,</span> <span m='2027700'>or that's</span>
  <span m='2027880'>right</span> <span m='2028060'>sided</span> <span m='2028450'>with</span>
  <span m='2028630'>regard</span> <span m='2028960'>to</span> <span m='2029080'>here.</span>
  <span m='2031870'>So</span> <span m='2032080'>the</span> <span m='2032230'>net</span>
  <span m='2032680'>region</span> <span m='2033070'>of</span> <span m='2033160'>convergence</span>
  <span m='2033820'>is</span> <span m='2033940'>that</span> <span m='2034150'>region.</span>
  <span m='2037160'>Make</span> <span m='2037340'>sense?</span> </p><p><span m='2040700'>So</span>
  <span m='2040880'>then</span> <span m='2041060'>I</span> <span m='2041180'>have</span>
  <span m='2042120'>a</span> <span m='2042200'>pole</span> <span m='2042650'>at</span>
  <span m='2042800'>minus</span> <span m='2043250'>2</span> <span m='2043580'>with</span>
  <span m='2043730'>the</span> <span m='2043820'>right</span> <span m='2044060'>sided.</span>
  <span m='2045520'>OK,</span> <span m='2045880'>so</span> <span m='2046040'>that's</span>
  <span m='2046310'>this.</span> <span m='2049139'>And</span> <span m='2049440'>a</span>
  <span m='2049500'>pole</span> <span m='2050040'>as</span> <span m='2050260'>2,</span>
  <span m='2050670'>which</span> <span m='2050880'>is</span> <span m='2051000'>left</span>
  <span m='2051210'>sided.</span> <span m='2053650'>So</span> <span m='2053830'>that's</span>
  <span m='2054159'>this.</span> <span m='2056820'>So</span> <span m='2057000'>that</span>
  <span m='2057719'>corresponds</span> <span m='2058350'>to</span> <span m='2058469'>a</span>
  <span m='2058500'>region</span> <span m='2058889'>here.</span> </p><p><span m='2063929'>Then</span>
  <span m='2064110'>the</span> <span m='2064199'>third</span> <span m='2064469'>one</span>
  <span m='2064650'>I</span> <span m='2064739'>have</span> <span m='2066270'>a</span>
  <span m='2066330'>pole</span> <span m='2066690'>at</span> <span m='2066810'>minus</span>
  <span m='2067230'>2,</span> <span m='2067570'>which</span> <span m='2067679'>is</span>
  <span m='2067770'>left</span> <span m='2067980'>sided.</span> <span m='2070350'>So</span>
  <span m='2070500'>that</span> <span m='2070710'>means</span> <span m='2071010'>I</span>
  <span m='2071130'>want</span> <span m='2071310'>to</span> <span m='2071400'>have</span>
  <span m='2071969'>convergence</span> <span m='2072600'>here.</span> <span m='2076199'>And</span>
  <span m='2076350'>I</span> <span m='2076409'>have</span> <span m='2076560'>a</span>
  <span m='2076620'>pole</span> <span m='2076989'>at 2</span> <span m='2077400'>which</span>
  <span m='2077580'>is</span> <span m='2077699'>right</span> <span m='2077940'>sided,</span>
  <span m='2078480'>and</span> <span m='2078659'>I</span> <span m='2078750'>need</span>
  <span m='2079020'>convergence</span> <span m='2079590'>here.</span> </p><p><span
  m='2080280'>There's</span> <span m='2080429'>no</span> <span m='2080639'>way</span>
  <span m='2081449'>to</span> <span m='2081570'>make</span> <span m='2081750'>that</span>
  <span m='2081929'>convergent.</span> <span m='2083610'>If</span> <span m='2083760'>I</span>
  <span m='2083850'>choose</span> <span m='2084150'>my</span> <span m='2084330'>s</span>
  <span m='2084540'>to</span> <span m='2084650'>make</span> <span m='2084810'>the</span>
  <span m='2084900'>first</span> <span m='2085110'>part</span> <span m='2085320'>convergent</span>
  <span m='2085830'>then</span> <span m='2086010'>my</span> <span m='2086159'>second</span>
  <span m='2086489'>part</span> <span m='2086670'>is</span> <span m='2086790'>not</span>
  <span m='2086940'>convergent,</span> <span m='2087400'>and</span> <span m='2087480'>vice</span>
  <span m='2087690'>versa.</span> <span m='2089330'>So</span> <span m='2089350'>there's</span>
  <span m='2089530'>no</span> <span m='2089650'>way</span> <span m='2089830'>to</span>
  <span m='2089920'>do</span> <span m='2090070'>that</span> <span m='2090400'>one.</span>
  <span m='2092330'>So</span> <span m='2092409'>this</span> <span m='2092620'>is</span>
  <span m='2092770'>no.</span> <span m='2093130'>This</span> <span m='2093340'>is</span>
  <span m='2093460'>yes.</span> <span m='2093820'>This</span> <span m='2094000'>is</span>
  <span m='2094120'>yes.</span> </p><p><span m='2096460'>And</span> <span m='2096639'>then</span>
  <span m='2096850'>finally,</span> <span m='2097520'>this</span> <span m='2097630'>is</span>
  <span m='2098080'>a</span> <span m='2098320'>pole</span> <span m='2098680'>at</span>
  <span m='2098920'>minus</span> <span m='2099360'>2</span> <span m='2099800'>to</span>
  <span m='2100170'>the</span> <span m='2100540'>left.</span> <span m='2103670'>And</span>
  <span m='2104140'>a</span> <span m='2104230'>pole</span> <span m='2104740'>at</span>
  <span m='2105130'>2</span> <span m='2106200'>to</span> <span m='2106360'>the</span>
  <span m='2106480'>left.</span> <span m='2108920'>So</span> <span m='2108970'>that's</span>
  <span m='2109180'>that</span> <span m='2109390'>one.</span> <span m='2110590'>So</span>
  <span m='2110740'>that's</span> <span m='2110950'>OK.</span> <span m='2111970'>So</span>
  <span m='2112090'>the</span> <span m='2112210'>idea</span> <span m='2112570'>is</span>
  <span m='2112900'>that</span> <span m='2113020'>there's</span> <span m='2113170'>only</span>
  <span m='2113410'>three</span> <span m='2113740'>ways</span> <span m='2114040'>to</span>
  <span m='2114170'>chop</span> <span m='2114550'>up</span> <span m='2115890'>a</span>
  <span m='2115960'>space</span> <span m='2116440'>delimited</span> <span m='2116890'>by</span>
  <span m='2117040'>two</span> <span m='2117220'>poles.</span> <span m='2119000'>OK,</span>
  <span m='2119210'>so it</span> <span m='2119480'>looks</span> <span m='2119720'>like</span>
  <span m='2119900'>you</span> <span m='2120060'>to</span> <span m='2120200'>have</span>
  <span m='2120470'>four</span> <span m='2121430'>because</span> <span m='2121730'>we're</span>
  <span m='2121880'>used</span> <span m='2122090'>to</span> <span m='2122180'>thinking</span>
  <span m='2122510'>about</span> <span m='2122780'>the</span> <span m='2122870'>two</span>
  <span m='2123020'>by</span> <span m='2123170'>two</span> <span m='2123350'>matrix.</span>
  <span m='2123830'>That's</span> <span m='2124040'>not</span> <span m='2124220'>the</span>
  <span m='2124310'>way</span> <span m='2124400'>it</span> <span m='2124460'>works.</span>
  </p><p><span m='2129460'>OK,</span> <span m='2131050'>two</span> <span m='2131440'>last</span>
  <span m='2131740'>things.</span> <span m='2132880'>First</span> <span m='2133120'>last</span>
  <span m='2133380'>thing.</span> <span m='2134230'>Probably</span> <span m='2134710'>the</span>
  <span m='2134830'>most</span> <span m='2135100'>important</span> <span m='2135670'>thing</span>
  <span m='2135850'>about</span> <span m='2136060'>the</span> <span m='2136150'>Laplace</span>
  <span m='2136510'>transform,</span> <span m='2137020'>probably</span> <span m='2137500'>the</span>
  <span m='2137650'>only</span> <span m='2137920'>reason</span> <span m='2138250'>we</span>
  <span m='2138370'>bother</span> <span m='2138700'>with</span> <span m='2138860'>that</span>
  <span m='2138970'>whatever</span> <span m='2139960'>is</span> <span m='2140230'>that</span>
  <span m='2140350'>you</span> <span m='2140470'>can</span> <span m='2140590'>use</span>
  <span m='2140830'>it</span> <span m='2140890'>to</span> <span m='2140980'>solve</span>
  <span m='2141190'>differential</span> <span m='2141640'>equations.</span> <span
  m='2142810'>That's</span> <span m='2143050'>probably</span> <span m='2144160'>the</span>
  <span m='2144280'>most</span> <span m='2144520'>important</span> <span m='2144880'>reason</span>
  <span m='2145420'>for</span> <span m='2145660'>even</span> <span m='2145870'>talking</span>
  <span m='2146140'>about</span> <span m='2146380'>it.</span> </p><p><span m='2147010'>The</span>
  <span m='2147100'>fact</span> <span m='2147310'>that</span> <span m='2147400'>we</span>
  <span m='2147520'>can</span> <span m='2147640'>take</span> <span m='2147880'>it</span>
  <span m='2148210'>is</span> <span m='2148390'>of</span> <span m='2148510'>zero</span>
  <span m='2148870'>consequence.</span> <span m='2149600'>We</span> <span m='2149710'>can</span>
  <span m='2149830'>take</span> <span m='2150160'>lots</span> <span m='2150460'>of</span>
  <span m='2150580'>integrals.</span> <span m='2152080'>The</span> <span m='2152200'>interesting</span>
  <span m='2152650'>thing</span> <span m='2152830'>about</span> <span m='2153040'>this</span>
  <span m='2153220'>integral</span> <span m='2153760'>is</span> <span m='2153970'>that</span>
  <span m='2154060'>it</span> <span m='2154180'>helps</span> <span m='2154420'>us</span>
  <span m='2154600'>to</span> <span m='2154870'>solve</span> <span m='2155320'>differential</span>
  <span m='2155920'>equations.</span> <span m='2157360'>And</span> <span m='2157540'>the</span>
  <span m='2157660'>trick</span> <span m='2158320'>is</span> <span m='2158950'>that</span>
  <span m='2159630'>if</span> <span m='2160060'>we</span> <span m='2160150'>start</span>
  <span m='2160390'>with</span> <span m='2160490'>the</span> <span m='2160570'>differential</span>
  <span m='2161020'>equation</span> <span m='2161500'>we</span> <span m='2161680'>can</span>
  <span m='2161890'>take</span> <span m='2162190'>the</span> <span m='2162790'>Laplace</span>
  <span m='2163090'>transform</span> <span m='2163600'>of</span> <span m='2163680'>the</span>
  <span m='2163780'>whole</span> <span m='2163990'>differential</span> <span m='2164470'>equation</span>
  <span m='2164920'>and</span> <span m='2165100'>that will</span> <span m='2165380'>end</span>
  <span m='2165550'>up</span> <span m='2165670'>making</span> <span m='2166000'>sense.</span>
  </p><p><span m='2167260'>Just</span> <span m='2167470'>like</span> <span m='2167620'>the</span>
  <span m='2167710'>z</span> <span m='2168550'>transform,</span> <span m='2169500'>the</span>
  <span m='2170020'>Laplace</span> <span m='2170120'>transform</span> <span m='2170440'>is</span>
  <span m='2170560'>linear.</span> <span m='2172050'>The</span> <span m='2172240'>Laplace</span>
  <span m='2172520'>transform</span> <span m='2172900'>of a</span> <span m='2173100'>sum</span>
  <span m='2173405'>is</span> <span m='2173710'>sum</span> <span m='2173770'>of the</span>
  <span m='2173840'>Laplace</span> <span m='2174070'>transforms.</span> <span m='2176020'>That's</span>
  <span m='2176230'>pretty</span> <span m='2176470'>simple</span> <span m='2176800'>just</span>
  <span m='2176950'>by</span> <span m='2177070'>looking</span> <span m='2177280'>at</span>
  <span m='2177370'>the</span> <span m='2177460'>definition</span> <span m='2178660'>because</span>
  <span m='2178930'>we</span> <span m='2179050'>can</span> <span m='2179230'>distribute</span>
  <span m='2179830'>the</span> <span m='2180010'>e to</span> <span m='2180240'>the</span>
  <span m='2180340'>minus</span> <span m='2180630'>st</span> <span m='2181090'>over</span>
  <span m='2181405'>a</span> <span m='2181720'>sum,</span> <span m='2182380'>if</span>
  <span m='2182500'>x</span> <span m='2182710'>were</span> <span m='2182860'>a</span>
  <span m='2182920'>sum</span> <span m='2183400'>it</span> <span m='2183520'>distributes.</span>
  <span m='2186280'>So</span> <span m='2186370'>that's</span> <span m='2186670'>easy.</span>
  </p><p><span m='2187790'>The</span> <span m='2187890'>other</span> <span m='2187960'>important</span>
  <span m='2188350'>thing</span> <span m='2189100'>is</span> <span m='2189700'>the</span>
  <span m='2189940'>derivative.</span> <span m='2190750'>What's</span> <span m='2191050'>the</span>
  <span m='2191170'>Laplace</span> <span m='2191590'>transform</span> <span m='2192070'>of</span>
  <span m='2192190'>a</span> <span m='2192250'>derivative?</span> <span m='2193210'>That</span>
  <span m='2193570'>turns</span> <span m='2193870'>out</span> <span m='2194050'>to</span>
  <span m='2194170'>be</span> <span m='2194320'>easy.</span> <span m='2195250'>If</span>
  <span m='2195400'>that</span> <span m='2195580'>weren't</span> <span m='2195910'>easy,</span>
  <span m='2196340'>we</span> <span m='2196360'>wouldn't</span> <span m='2196570'>even</span>
  <span m='2196810'>bother</span> <span m='2197110'>with</span> <span m='2197260'>it.</span>
  <span m='2198160'>But</span> <span m='2198310'>it</span> <span m='2198400'>is</span>
  <span m='2198580'>easy.</span> </p><p><span m='2200390'>You</span> <span m='2200440'>can</span>
  <span m='2200560'>see</span> <span m='2200890'>that</span> <span m='2201070'>if</span>
  <span m='2201190'>we</span> <span m='2201490'>make</span> <span m='2201760'>the</span>
  <span m='2201880'>assumption</span> <span m='2202570'>that</span> <span m='2202780'>x</span>
  <span m='2203020'>is</span> <span m='2203170'>the</span> <span m='2203290'>Laplace</span>
  <span m='2203740'>transform</span> <span m='2204310'>of</span> <span m='2204440'>x,</span>
  <span m='2206780'>and</span> <span m='2207080'>then</span> <span m='2207380'>if</span>
  <span m='2207530'>we</span> <span m='2207650'>define</span> <span m='2208190'>y</span>
  <span m='2208520'>is</span> <span m='2208700'>the</span> <span m='2208760'>derivative</span>
  <span m='2209210'>of</span> <span m='2209330'>x,</span> <span m='2209630'>we</span>
  <span m='2209750'>can</span> <span m='2209900'>ask</span> <span m='2210170'>what's</span>
  <span m='2210410'>the</span> <span m='2210610'>Laplace</span> <span m='2210890'>transform</span>
  <span m='2211370'>of</span> <span m='2211520'>y</span> <span m='2212200'>and</span>
  <span m='2212300'>that</span> <span m='2212390'>will</span> <span m='2212510'>tell</span>
  <span m='2212780'>us</span> <span m='2212900'>what's</span> <span m='2213170'>the</span>
  <span m='2213300'>Laplace</span> <span m='2213610'>transform</span> <span m='2213865'>of</span>
  <span m='2214120'>the</span> <span m='2214210'>derivative.</span> <span m='2217420'>Take</span>
  <span m='2217630'>the</span> <span m='2217720'>definition</span> <span m='2218290'>of</span>
  <span m='2218350'>transform,</span> <span m='2218950'>stick</span> <span m='2219220'>in</span>
  <span m='2219580'>y</span> <span m='2220080'>equals</span> <span m='2220450'>x</span>
  <span m='2220640'>dot</span> <span m='2222390'>and</span> <span m='2222510'>integrate</span>
  <span m='2222870'>by</span> <span m='2222990'>parts.</span> <span m='2224910'>You</span>
  <span m='2225150'>all</span> <span m='2225810'>can</span> <span m='2225990'>integrate</span>
  <span m='2226380'>by</span> <span m='2226500'>parts</span> <span m='2226830'>much</span>
  <span m='2227190'>better</span> <span m='2227400'>than</span> <span m='2227520'>I</span>
  <span m='2227670'>can</span> <span m='2228630'>because</span> <span m='2228930'>I</span>
  <span m='2229050'>took</span> <span m='2229260'>it</span> <span m='2229350'>35</span>
  <span m='2229770'>years</span> <span m='2230010'>ago.</span> <span m='2232650'>But</span>
  <span m='2232950'>it's</span> <span m='2233100'>very</span> <span m='2233430'>easy</span>
  <span m='2233790'>to</span> <span m='2233910'>see</span> <span m='2234570'>that</span>
  <span m='2234930'>if</span> <span m='2235110'>we</span> <span m='2235410'>call</span>
  <span m='2235800'>this</span> <span m='2236760'>u</span> <span m='2237300'>and</span>
  <span m='2237480'>this</span> <span m='2237800'>v</span> <span m='2238195'>dot,</span>
  <span m='2238590'>integral</span> <span m='2239310'>u</span> <span m='2239640'>dv</span>
  <span m='2241050'>is</span> <span m='2241320'>uv</span> <span m='2241860'>minus</span>
  <span m='2242250'>the</span> <span m='2242340'>integral</span> <span m='2242680'>v</span>
  <span m='2242960'>du.</span> </p><p><span m='2246240'>The</span> <span m='2246360'>trick</span>
  <span m='2246690'>is</span> <span m='2247020'>that</span> <span m='2247200'>taking</span>
  <span m='2247680'>integrals</span> <span m='2248280'>and</span> <span m='2248370'>derivatives</span>
  <span m='2249030'>of</span> <span m='2249150'>this</span> <span m='2249450'>part</span>
  <span m='2250290'>is</span> <span m='2250500'>easy,</span> <span m='2252120'>it's</span>
  <span m='2252270'>an</span> <span m='2252390'>exponential.</span> <span m='2254180'>Exponentials</span>
  <span m='2254770'>are</span> <span m='2254910'>the</span> <span m='2255080'>one</span>
  <span m='2255360'>function</span> <span m='2257150'>whose</span> <span m='2257360'>derivative</span>
  <span m='2257990'>has</span> <span m='2258230'>the</span> <span m='2258320'>same</span>
  <span m='2258650'>shape</span> <span m='2259340'>as</span> <span m='2259550'>the</span>
  <span m='2259670'>function.</span> <span m='2260510'>That's</span> <span m='2260840'>the</span>
  <span m='2260960'>reason</span> <span m='2261290'>it's</span> <span m='2261410'>easy.</span>
  </p><p><span m='2263800'>So</span> <span m='2263950'>that</span> <span m='2264160'>means</span>
  <span m='2264550'>that</span> <span m='2267310'>I</span> <span m='2267970'>can</span>
  <span m='2269050'>easily</span> <span m='2269410'>integrate</span> <span m='2269800'>that</span>
  <span m='2270010'>part.</span> <span m='2270300'>I</span> <span m='2270370'>can</span>
  <span m='2270520'>easily</span> <span m='2270790'>differentiate</span> <span m='2271390'>that</span>
  <span m='2271570'>part</span> <span m='2271960'>to</span> <span m='2272080'>get</span>
  <span m='2272230'>something</span> <span m='2272530'>that</span> <span m='2272620'>looks</span>
  <span m='2272890'>just</span> <span m='2273160'>like</span> <span m='2273370'>this,</span>
  <span m='2273680'>except</span> <span m='2273840'>as</span> <span m='2273970'>multiplied</span>
  <span m='2274390'>by</span> <span m='2274540'>minus</span> <span m='2274890'>s.</span>
  <span m='2278250'>And</span> <span m='2278400'>that</span> <span m='2278610'>minus</span>
  <span m='2279030'>s</span> <span m='2279210'>is</span> <span m='2279360'>the</span>
  <span m='2279480'>only</span> <span m='2279660'>thing</span> <span m='2279810'>that</span>
  <span m='2279960'>ends</span> <span m='2280140'>up</span> <span m='2281250'>being</span>
  <span m='2281520'>important.</span> <span m='2282570'>The</span> <span m='2283260'>Laplace</span>
  <span m='2283530'>transform</span> <span m='2284190'>of</span> <span m='2284340'>the</span>
  <span m='2284460'>derivative</span> <span m='2285450'>is</span> <span m='2285660'>s</span>
  <span m='2285950'>times</span> <span m='2286410'>the</span> <span m='2287640'>Laplace</span>
  <span m='2287740'>transform</span> <span m='2288090'>of</span> <span m='2288150'>the</span>
  <span m='2288270'>original</span> <span m='2288600'>function.</span> </p><p><span
  m='2290980'>OK,</span> <span m='2292290'>differentiating</span> <span m='2293130'>time</span>
  <span m='2293610'>is</span> <span m='2293760'>the</span> <span m='2293850'>same</span>
  <span m='2294090'>as</span> <span m='2294180'>multiplying</span> <span m='2294690'>by</span>
  <span m='2294860'>s</span> <span m='2295210'>in</span> <span m='2295350'>a</span>
  <span m='2295500'>Laplace</span> <span m='2295770'>transform.</span> <span m='2298350'>Because</span>
  <span m='2298770'>of</span> <span m='2298920'>that</span> <span m='2299610'>it's</span>
  <span m='2299820'>trivial</span> <span m='2300510'>to</span> <span m='2300660'>think</span>
  <span m='2300900'>about</span> <span m='2301440'>the</span> <span m='2301590'>Laplace</span>
  <span m='2302010'>transform</span> <span m='2303000'>of</span> <span m='2303120'>a</span>
  <span m='2303180'>differential</span> <span m='2303660'>equation.</span> <span m='2306050'>Linearity</span>
  <span m='2306650'>says</span> <span m='2306890'>you</span> <span m='2306950'>can</span>
  <span m='2307040'>do</span> <span m='2307140'>it</span> <span m='2307220'>term</span>
  <span m='2307490'>wise.</span> </p><p><span m='2308720'>And</span> <span m='2308840'>a</span>
  <span m='2308900'>differential</span> <span m='2309320'>equation</span> <span m='2310100'>is</span>
  <span m='2310280'>something</span> <span m='2310610'>that</span> <span m='2310700'>has</span>
  <span m='2310880'>a</span> <span m='2310910'>bunch</span> <span m='2311060'>of</span>
  <span m='2311120'>derivatives</span> <span m='2311570'>in</span> <span m='2311690'>it.</span>
  <span m='2312500'>Those</span> <span m='2312770'>all</span> <span m='2312920'>turn</span>
  <span m='2313160'>into</span> <span m='2313400'>multiply</span> <span m='2313940'>by</span>
  <span m='2314150'>s.</span> <span m='2315170'>So</span> <span m='2315320'>you</span>
  <span m='2315500'>end</span> <span m='2315770'>up</span> <span m='2315980'>then</span>
  <span m='2316580'>with</span> <span m='2316790'>this</span> <span m='2316970'>differential</span>
  <span m='2317510'>equation</span> <span m='2317990'>being</span> <span m='2318290'>replaced</span>
  <span m='2318710'>by</span> <span m='2318920'>this.</span> <span m='2325360'>So
  the</span> <span m='2325860'>Laplace</span> <span m='2326360'>transform</span> <span
  m='2326655'>of</span> <span m='2326950'>the</span> <span m='2327050'>derivative</span>
  <span m='2327560'>is</span> <span m='2327830'>s</span> <span m='2328040'>times</span>
  <span m='2328460'>y.</span> <span m='2329810'>The</span> <span m='2329990'>Laplace</span>
  <span m='2330220'>transform</span> <span m='2330630'>of</span> <span m='2330740'>y</span>
  <span m='2331010'>is</span> <span m='2331190'>y.</span> </p><p><span m='2332240'>Now</span>
  <span m='2332390'>I</span> <span m='2332450'>have</span> <span m='2332540'>to</span>
  <span m='2332630'>figure</span> <span m='2332780'>out</span> <span m='2332900'>the</span>
  <span m='2333010'>Laplace</span> <span m='2333290'>transform</span> <span m='2333750'>of</span>
  <span m='2333890'>delta.</span> <span m='2335530'>OK,</span> <span m='2335790'>turns</span>
  <span m='2336050'>out</span> <span m='2336230'>that's</span> <span m='2336590'>easy.</span>
  <span m='2339160'>What's</span> <span m='2339300'>the</span> <span m='2339360'>Laplace</span>
  <span m='2339750'>transform</span> <span m='2340190'>of</span> <span m='2340290'>delta?</span>
  <span m='2340620'>That's</span> <span m='2340770'>why</span> <span m='2340860'>we</span>
  <span m='2340980'>like</span> <span m='2341130'>delta</span> <span m='2341400'>functions.</span>
  <span m='2342630'>Delta</span> <span m='2342900'>functions</span> <span m='2343230'>seem</span>
  <span m='2343530'>mathematically</span> <span m='2344250'>bizarre</span> <span m='2344580'>but</span>
  <span m='2344670'>they're</span> <span m='2344790'>so</span> <span m='2345030'>easy</span>
  <span m='2345330'>to</span> <span m='2345450'>work</span> <span m='2345630'>with,</span>
  <span m='2346530'>that's</span> <span m='2346710'>the</span> <span m='2346800'>only</span>
  <span m='2346980'>reason</span> <span m='2347220'>we</span> <span m='2347310'>use</span>
  <span m='2347520'>them.</span> <span m='2348990'>If</span> <span m='2349170'>you</span>
  <span m='2349290'>think</span> <span m='2349500'>about</span> <span m='2349830'>the</span>
  <span m='2349950'>Laplace</span> <span m='2350310'>transform</span> <span m='2350730'>of</span>
  <span m='2350820'>delta</span> <span m='2351180'>just</span> <span m='2351390'>stick</span>
  <span m='2351570'>it</span> <span m='2351660'>in</span> <span m='2351780'>the</span>
  <span m='2351870'>formula.</span> </p><p><span m='2353760'>The</span> <span m='2353940'>interesting</span>
  <span m='2354510'>thing</span> <span m='2354720'>about</span> <span m='2355020'>the</span>
  <span m='2355110'>delta</span> <span m='2355440'>function</span> <span m='2355830'>is</span>
  <span m='2355980'>that</span> <span m='2356160'>it's</span> <span m='2356280'>0</span>
  <span m='2356850'>almost</span> <span m='2357360'>everywhere.</span> <span m='2360950'>So</span>
  <span m='2360970'>we</span> <span m='2361060'>don't</span> <span m='2361210'>need</span>
  <span m='2361390'>to</span> <span m='2361480'>worry</span> <span m='2361870'>about</span>
  <span m='2362260'>the</span> <span m='2362380'>product</span> <span m='2363040'>except</span>
  <span m='2363430'>where</span> <span m='2363640'>the</span> <span m='2363790'>delta</span>
  <span m='2364090'>function</span> <span m='2364480'>is</span> <span m='2364600'>not</span>
  <span m='2364780'>0.</span> <span m='2368250'>Because</span> <span m='2368540'>the</span>
  <span m='2368620'>delta</span> <span m='2368830'>function</span> <span m='2369220'>makes</span>
  <span m='2369580'>the</span> <span m='2369700'>time</span> <span m='2369970'>axis</span>
  <span m='2370360'>mostly</span> <span m='2370840'>0.</span> <span m='2372740'>The</span>
  <span m='2372890'>only</span> <span m='2373190'>place</span> <span m='2373490'>that's</span>
  <span m='2373730'>not</span> <span m='2373940'>0</span> <span m='2374360'>is</span>
  <span m='2374450'>0.</span> <span m='2376540'>So</span> <span m='2377500'>the</span>
  <span m='2377890'>only</span> <span m='2378250'>value</span> <span m='2378640'>of</span>
  <span m='2378700'>this</span> <span m='2378880'>function</span> <span m='2379240'>that</span>
  <span m='2379360'>matters</span> <span m='2379690'>in</span> <span m='2379810'>the</span>
  <span m='2379870'>least</span> <span m='2381690'>is</span> <span m='2381870'>its</span>
  <span m='2382020'>value</span> <span m='2382500'>at</span> <span m='2382740'>0.</span>
  </p><p><span m='2384520'>If</span> <span m='2384670'>you</span> <span m='2384730'>think</span>
  <span m='2384910'>about</span> <span m='2385060'>what</span> <span m='2385210'>that</span>
  <span m='2385360'>looks</span> <span m='2385540'>like</span> <span m='2385720'>is</span>
  <span m='2386250'>as</span> <span m='2386440'>a</span> <span m='2386500'>picture.</span>
  <span m='2390340'>So</span> <span m='2390390'>if</span> <span m='2390480'>we</span>
  <span m='2390630'>have</span> <span m='2390900'>something</span> <span m='2391230'>that</span>
  <span m='2391320'>looks</span> <span m='2391530'>like</span> <span m='2392660'>e</span>
  <span m='2393030'>to</span> <span m='2393280'>the</span> <span m='2393360'>minus</span>
  <span m='2393690'>st</span> <span m='2395730'>and</span> <span m='2395850'>if</span>
  <span m='2395940'>we</span> <span m='2396030'>multiply</span> <span m='2396630'>by</span>
  <span m='2396990'>an</span> <span m='2397140'>impulse.</span> <span m='2399480'>The</span>
  <span m='2399600'>impulse</span> <span m='2399990'>is</span> <span m='2400080'>0</span>
  <span m='2400470'>except at</span> <span m='2400820'>0.</span> <span m='2401260'>The</span>
  <span m='2401370'>only</span> <span m='2401500'>thing</span> <span m='2401700'>that</span>
  <span m='2401790'>survives</span> <span m='2402390'>that</span> <span m='2402510'>multiplication</span>
  <span m='2403260'>is</span> <span m='2403410'>the</span> <span m='2403770'>value</span>
  <span m='2404040'>of</span> <span m='2404310'>e to</span> <span m='2404600'>the</span>
  <span m='2404700'>minus</span> <span m='2404970'>st</span> <span m='2405490'>at</span>
  <span m='2405790'>t equals</span> <span m='2406190'>0.</span> <span m='2408360'>We</span>
  <span m='2408510'>can</span> <span m='2408630'>think</span> <span m='2408780'>about</span>
  <span m='2408990'>that</span> <span m='2409170'>as</span> <span m='2409290'>a</span>
  <span m='2409350'>limit.</span> </p><p><span m='2410280'>We</span> <span m='2410430'>thought</span>
  <span m='2410610'>about</span> <span m='2411450'>the</span> <span m='2411570'>delta</span>
  <span m='2411900'>function</span> <span m='2412290'>as</span> <span m='2412470'>a</span>
  <span m='2412530'>limit</span> <span m='2412920'>of</span> <span m='2413040'>a</span>
  <span m='2413100'>function</span> <span m='2413460'>that</span> <span m='2413550'>looks</span>
  <span m='2413760'>like</span> <span m='2413970'>this,</span> <span m='2415200'>minus</span>
  <span m='2415560'>epsilon,</span> <span m='2416010'>epsilon</span> <span m='2416393'>t,</span>
  <span m='2417160'>1</span> <span m='2417450'>over</span> <span m='2417630'>2</span>
  <span m='2417880'>epsilon.</span> <span m='2418770'>So</span> <span m='2418950'>that</span>
  <span m='2419190'>the</span> <span m='2419310'>limit</span> <span m='2419640'>as</span>
  <span m='2420480'>epsilon</span> <span m='2420750'>goes</span> <span m='2420960'>to</span>
  <span m='2421080'>0</span> <span m='2421530'>becomes</span> <span m='2422150'>a</span>
  <span m='2422220'>delta.</span> <span m='2422820'>That's</span> <span m='2422970'>how</span>
  <span m='2423090'>we</span> <span m='2423420'>defined</span> <span m='2424320'>the</span>
  <span m='2424500'>impulse</span> <span m='2424860'>function.</span> <span m='2426060'>If</span>
  <span m='2426180'>we</span> <span m='2426270'>think</span> <span m='2426420'>about</span>
  <span m='2426630'>that</span> <span m='2426810'>definition</span> <span m='2427920'>in</span>
  <span m='2428100'>terms</span> <span m='2428430'>of</span> <span m='2428580'>this</span>
  <span m='2429300'>product</span> <span m='2431550'>you</span> <span m='2431760'>can</span>
  <span m='2431910'>see</span> <span m='2432090'>that</span> <span m='2432210'>you</span>
  <span m='2432300'>get</span> <span m='2432450'>exactly</span> <span m='2432870'>this</span>
  <span m='2433050'>expression.</span> </p><p><span m='2436270'>So</span> <span m='2438480'>if</span>
  <span m='2438560'>you</span> <span m='2438650'>multiply</span> <span m='2439010'>this</span>
  <span m='2439190'>times</span> <span m='2439460'>this</span> <span m='2439730'>all</span>
  <span m='2439930'>you</span> <span m='2440530'>pick</span> <span m='2440730'>out</span>
  <span m='2441510'>is</span> <span m='2441710'>this</span> <span m='2441890'>part.</span>
  <span m='2445800'>As</span> <span m='2445950'>you</span> <span m='2446070'>make</span>
  <span m='2446580'>epsilon</span> <span m='2447090'>smaller,</span> <span m='2447450'>and</span>
  <span m='2447540'>smaller,</span> <span m='2447840'>and</span> <span m='2447930'>smaller,</span>
  <span m='2448410'>you</span> <span m='2448530'>focus</span> <span m='2448920'>just</span>
  <span m='2449190'>on</span> <span m='2449280'>that</span> <span m='2449460'>point</span>
  <span m='2449730'>right</span> <span m='2450030'>at</span> <span m='2450270'>0.</span>
  <span m='2452280'>The</span> <span m='2452430'>area</span> <span m='2452700'>of</span>
  <span m='2452760'>the</span> <span m='2452850'>impulse</span> <span m='2453150'>is</span>
  <span m='2453270'>1.</span> <span m='2453470'>Therefore,</span> <span m='2454320'>the</span>
  <span m='2454800'>integral</span> <span m='2456510'>of this</span> <span m='2456930'>thing
  is</span> <span m='2457130'>everywhere</span> <span m='2457950'>1.</span> </p><p><span
  m='2458880'>So</span> <span m='2459060'>this</span> <span m='2459600'>sifts</span>
  <span m='2460110'>out.</span> <span m='2460530'>That's</span> <span m='2460680'>what</span>
  <span m='2460770'>we'll</span> <span m='2460920'>call</span> <span m='2461190'>it.</span>
  <span m='2461710'>So</span> <span m='2461760'>this</span> <span m='2461910'>is</span>
  <span m='2461970'>called</span> <span m='2462150'>the</span> <span m='2462240'>sifting</span>
  <span m='2462630'>property.</span> <span m='2468130'>It's</span> <span m='2468430'>the</span>
  <span m='2468610'>nice</span> <span m='2468940'>part</span> <span m='2469390'>about</span>
  <span m='2469690'>the</span> <span m='2469780'>delta</span> <span m='2470050'>function.</span>
  <span m='2471370'>If</span> <span m='2471520'>you</span> <span m='2471670'>integrate</span>
  <span m='2471970'>a</span> <span m='2472030'>function</span> <span m='2472390'>with</span>
  <span m='2472570'>regard</span> <span m='2473500'>to</span> <span m='2473650'>time</span>
  <span m='2474970'>where</span> <span m='2475120'>the</span> <span m='2475240'>function</span>
  <span m='2475570'>is</span> <span m='2475660'>multiplied</span> <span m='2476090'>by</span>
  <span m='2476260'>delta,</span> <span m='2478110'>that</span> <span m='2478380'>integral</span>
  <span m='2479070'>is</span> <span m='2479370'>the</span> <span m='2479460'>value</span>
  <span m='2479820'>of</span> <span m='2479880'>the</span> <span m='2479970'>function</span>
  <span m='2480360'>at</span> <span m='2480510'>0.</span> <span m='2480600'>It</span>
  <span m='2480870'>sifts</span> <span m='2481290'>out</span> <span m='2481560'>the</span>
  <span m='2481620'>0</span> <span m='2481920'>value.</span> </p><p><span m='2483840'>That</span>
  <span m='2484080'>means</span> <span m='2484500'>that</span> <span m='2485460'>the</span>
  <span m='2485670'>Laplace</span> <span m='2486060'>transform</span> <span m='2486510'>of
  the</span> <span m='2486600'>delta</span> <span m='2486930'>function</span> <span
  m='2487260'>is</span> <span m='2487350'>1.</span> <span m='2489370'>It's</span>
  <span m='2489480'>the</span> <span m='2489600'>most</span> <span m='2489780'>simple</span>
  <span m='2490080'>function</span> <span m='2490440'>you</span> <span m='2490530'>can</span>
  <span m='2490650'>imagine.</span> <span m='2491830'>So</span> <span m='2492690'>the</span>
  <span m='2493020'>net</span> <span m='2493350'>effect</span> <span m='2493710'>of</span>
  <span m='2493800'>that</span> <span m='2494100'>is</span> <span m='2494340'>that</span>
  <span m='2494460'>this</span> <span m='2494700'>differential</span> <span m='2495330'>equation,</span>
  <span m='2496530'>the</span> <span m='2496620'>Laplace</span> <span m='2496950'>transform</span>
  <span m='2497340'>of</span> <span m='2497400'>the</span> <span m='2497460'>differential</span>
  <span m='2497910'>equation</span> <span m='2498690'>becomes</span> <span m='2499440'>an</span>
  <span m='2499620'>algebraic</span> <span m='2500250'>equation.</span> <span m='2505400'>That</span>
  <span m='2505540'>means</span> <span m='2505810'>that</span> <span m='2505930'>we</span>
  <span m='2506050'>can</span> <span m='2506200'>solve</span> <span m='2506500'>it</span>
  <span m='2506590'>by</span> <span m='2506710'>doing</span> <span m='2506950'>algebra.</span>
  </p><p><span m='2509050'>So</span> <span m='2509370'>in</span> <span m='2509580'>particular,</span>
  <span m='2510030'>we</span> <span m='2510210'>can</span> <span m='2511290'>readily</span>
  <span m='2511650'>solve</span> <span m='2511920'>the</span> <span m='2512040'>equation</span>
  <span m='2512500'>to</span> <span m='2512970'>find</span> <span m='2513270'>an</span>
  <span m='2513390'>expression</span> <span m='2513870'>for</span> <span m='2514090'>y.</span>
  <span m='2514830'>We</span> <span m='2514950'>saw</span> <span m='2515290'>that</span>
  <span m='2515480'>previously.</span> <span m='2517530'>We</span> <span m='2517680'>recognize</span>
  <span m='2518460'>ys.</span> <span m='2519720'>It's</span> <span m='2520460'>a</span>
  <span m='2520560'>recognition</span> <span m='2521100'>thing.</span> </p><p><span
  m='2521580'>It's</span> <span m='2521760'>a</span> <span m='2521820'>table</span>
  <span m='2522090'>look</span> <span m='2522270'>up</span> <span m='2522390'>sort</span>
  <span m='2522600'>of</span> <span m='2522690'>thing.</span> <span m='2523950'>We</span>
  <span m='2524130'>know</span> <span m='2524460'>the</span> <span m='2525130'>form</span>
  <span m='2525400'>1</span> <span m='2525560'>over</span> <span m='2526630'>s</span>
  <span m='2527210'>plus</span> <span m='2527580'>1.</span> <span m='2529110'>So</span>
  <span m='2529290'>we</span> <span m='2529410'>know</span> <span m='2529590'>the</span>
  <span m='2529680'>time</span> <span m='2529950'>function</span> <span m='2530310'>that</span>
  <span m='2530430'>is</span> <span m='2530610'>the</span> <span m='2530760'>answer.</span>
  <span m='2533670'>So</span> <span m='2533880'>notice</span> <span m='2534210'>that</span>
  <span m='2534330'>when</span> <span m='2534480'>we</span> <span m='2534600'>do</span>
  <span m='2534780'>this</span> <span m='2535200'>just</span> <span m='2535440'>the</span>
  <span m='2535590'>way</span> <span m='2536030'>that</span> <span m='2536160'>happened</span>
  <span m='2536460'>with</span> <span m='2536610'>the</span> <span m='2536700'>z</span>
  <span m='2536850'>transform.</span> </p><p><span m='2537390'>When</span> <span m='2537510'>we</span>
  <span m='2537600'>solve</span> <span m='2537960'>a</span> <span m='2537990'>differential</span>
  <span m='2538530'>equation</span> <span m='2538950'>by</span> <span m='2539070'>using</span>
  <span m='2539390'>Laplace</span> <span m='2539760'>transform</span> <span m='2540870'>we</span>
  <span m='2540990'>basically</span> <span m='2541470'>don't</span> <span m='2541650'>use</span>
  <span m='2541860'>calculus.</span> <span m='2544920'>We</span> <span m='2545040'>use</span>
  <span m='2545220'>the</span> <span m='2545330'>Laplace</span> <span m='2545640'>transform</span>
  <span m='2546060'>to</span> <span m='2546150'>turn</span> <span m='2546330'>the</span>
  <span m='2546390'>differential</span> <span m='2546870'>equation</span> <span m='2547740'>which</span>
  <span m='2547920'>is</span> <span m='2548010'>calculus</span> <span m='2548550'>in</span>
  <span m='2548610'>1803</span> <span m='2548955'>and</span> <span m='2549300'>that</span>
  <span m='2549390'>kind</span> <span m='2549570'>of</span> <span m='2549630'>stuff,</span>
  <span m='2550620'>into</span> <span m='2550830'>algebra,</span> <span m='2551410'>which</span>
  <span m='2551520'>is</span> <span m='2551580'>high</span> <span m='2551730'>school.</span>
  <span m='2553200'>We</span> <span m='2553380'>do</span> <span m='2553470'>everything</span>
  <span m='2553800'>with</span> <span m='2554100'>algebra.</span> </p><p><span m='2555060'>The</span>
  <span m='2555210'>only</span> <span m='2555480'>annoying</span> <span m='2556050'>thing</span>
  <span m='2556650'>is</span> <span m='2556830'>this</span> <span m='2557010'>table</span>
  <span m='2557370'>look up</span> <span m='2557760'>thing.</span> <span m='2559020'>It's</span>
  <span m='2559200'>a</span> <span m='2559230'>little</span> <span m='2559530'>annoying</span>
  <span m='2560070'>that</span> <span m='2560190'>we</span> <span m='2560310'>had</span>
  <span m='2560430'>to</span> <span m='2560550'>do</span> <span m='2560700'>the</span>
  <span m='2560880'>inverse</span> <span m='2561360'>Laplace</span> <span m='2561780'>transform</span>
  <span m='2565240'>by</span> <span m='2565460'>table</span> <span m='2565850'>look</span>
  <span m='2566140'>up.</span> <span m='2566975'>It's</span> <span m='2567440'>a little</span>
  <span m='2567830'>dissatisfying.</span> </p><p><span m='2570410'>So</span> <span
  m='2570560'>I'll</span> <span m='2570740'>just</span> <span m='2571070'>mention</span>
  <span m='2571940'>that</span> <span m='2572090'>there</span> <span m='2572300'>is</span>
  <span m='2573110'>a</span> <span m='2573200'>formal</span> <span m='2573650'>way</span>
  <span m='2575030'>of</span> <span m='2575240'>not</span> <span m='2575630'>doing</span>
  <span m='2576320'>table</span> <span m='2576630'>look</span> <span m='2576890'>up.</span>
  <span m='2579770'>For</span> <span m='2579920'>the</span> <span m='2580010'>kinds</span>
  <span m='2580250'>of</span> <span m='2580340'>problems</span> <span m='2580860'>we</span>
  <span m='2580910'>will</span> <span m='2581030'>look</span> <span m='2581240'>at</span>
  <span m='2581870'>using</span> <span m='2582230'>this</span> <span m='2582410'>formula</span>
  <span m='2582890'>is</span> <span m='2583200'>so</span> <span m='2583580'>much</span>
  <span m='2583790'>more</span> <span m='2583910'>difficult</span> <span m='2584360'>than</span>
  <span m='2584480'>table</span> <span m='2584780'>look</span> <span m='2584990'>up</span>
  <span m='2587250'>that</span> <span m='2587370'>we</span> <span m='2587520'>will</span>
  <span m='2587610'>never</span> <span m='2587880'>use</span> <span m='2588450'>that</span>
  <span m='2588630'>formula.</span> <span m='2591240'>It</span> <span m='2591390'>will</span>
  <span m='2591600'>be</span> <span m='2591720'>useful</span> <span m='2592200'>for</span>
  <span m='2592410'>proving</span> <span m='2592860'>things,</span> <span m='2593160'>it</span>
  <span m='2593280'>will</span> <span m='2593430'>not</span> <span m='2593730'>be</span>
  <span m='2593910'>useful</span> <span m='2594360'>for</span> <span m='2594540'>inverting</span>
  <span m='2595050'>things.</span> <span m='2596580'>Because</span> <span m='2596970'>of</span>
  <span m='2597030'>the</span> <span m='2597150'>form</span> <span m='2597450'>of</span>
  <span m='2597510'>the</span> <span m='2597600'>things</span> <span m='2597870'>we</span>
  <span m='2597990'>do,</span> <span m='2598560'>linear</span> <span m='2598800'>differential</span>
  <span m='2599250'>equations</span> <span m='2599640'>with</span> <span m='2599760'>constant</span>
  <span m='2600090'>coefficients,</span> <span m='2601290'>it</span> <span m='2601380'>will</span>
  <span m='2601590'>always</span> <span m='2602010'>be</span> <span m='2602190'>easier</span>
  <span m='2602730'>to</span> <span m='2602880'>do</span> <span m='2603030'>table</span>
  <span m='2603390'>look</span> <span m='2603630'>up</span> <span m='2603810'>then</span>
  <span m='2603960'>it</span> <span m='2604050'>will</span> <span m='2604230'>be</span>
  <span m='2604860'>to</span> <span m='2604980'>run</span> <span m='2605190'>this</span>
  <span m='2605340'>integral.</span> </p><p><span m='2605970'>If</span> <span m='2606090'>you're</span>
  <span m='2606210'>interested</span> <span m='2606630'>in</span> <span m='2606720'>that</span>
  <span m='2606870'>integral,</span> <span m='2607230'>fine,</span> <span m='2607860'>take</span>
  <span m='2608080'>1804.</span> <span m='2609390'>There's</span> <span m='2609540'>a</span>
  <span m='2609600'>bunch</span> <span m='2609810'>of</span> <span m='2609900'>people</span>
  <span m='2610170'>who</span> <span m='2610260'>know</span> <span m='2610530'>all</span>
  <span m='2610830'>about</span> <span m='2611190'>how</span> <span m='2611340'>that</span>
  <span m='2611500'>integral</span> <span m='2611820'>works.</span> <span m='2613000'>It's</span>
  <span m='2613260'>spectacularly</span> <span m='2614130'>interesting</span> <span
  m='2614640'>but</span> <span m='2614760'>we</span> <span m='2614910'>won't</span>
  <span m='2615120'>use</span> <span m='2615360'>it</span> <span m='2615480'>here.</span>
  </p><p><span m='2617320'>So</span> <span m='2617760'>the</span> <span m='2617970'>upshot</span>
  <span m='2618450'>then</span> <span m='2619140'>is</span> <span m='2619440'>that</span>
  <span m='2620430'>the</span> <span m='2620580'>Laplace</span> <span m='2621030'>transform,</span>
  <span m='2622020'>we</span> <span m='2622200'>learn</span> <span m='2622440'>about</span>
  <span m='2622770'>it</span> <span m='2624360'>because</span> <span m='2624720'>it's</span>
  <span m='2624900'>very</span> <span m='2625290'>useful</span> <span m='2627840'>and</span>
  <span m='2628020'>its</span> <span m='2628200'>utility</span> <span m='2629130'>comes</span>
  <span m='2629520'>from</span> <span m='2629940'>a</span> <span m='2630030'>bunch</span>
  <span m='2630330'>of</span> <span m='2630510'>properties.</span> <span m='2633110'>The</span>
  <span m='2633230'>ones</span> <span m='2633560'>we</span> <span m='2633710'>illustrated</span>
  <span m='2634310'>today,</span> <span m='2634760'>we</span> <span m='2634910'>use</span>
  <span m='2635180'>the</span> <span m='2635300'>fact</span> <span m='2635600'>that</span>
  <span m='2635750'>it</span> <span m='2635840'>was</span> <span m='2636950'>linear</span>
  <span m='2638160'>and</span> <span m='2638260'>we</span> <span m='2638270'>use</span>
  <span m='2638480'>the</span> <span m='2638570'>fact</span> <span m='2638990'>that</span>
  <span m='2639290'>there's</span> <span m='2639470'>a</span> <span m='2639530'>simple</span>
  <span m='2639860'>relationship</span> <span m='2640550'>with</span> <span m='2640700'>differentiation.</span>
  <span m='2642590'>Using</span> <span m='2642890'>just</span> <span m='2643190'>those</span>
  <span m='2643460'>facts</span> <span m='2643970'>it</span> <span m='2644060'>turns</span>
  <span m='2644360'>out</span> <span m='2644990'>easy</span> <span m='2645470'>to</span>
  <span m='2645620'>do</span> <span m='2645860'>differential</span> <span m='2646430'>equations</span>
  <span m='2648050'>using the</span> <span m='2648440'>Laplace</span> <span m='2648800'>transform.</span>
  <span m='2649550'>And</span> <span m='2649670'>there's</span> <span m='2649820'>many</span>
  <span m='2650090'>other</span> <span m='2650300'>things</span> <span m='2651110'>I've</span>
  <span m='2651290'>illustrated</span> <span m='2651830'>in</span> <span m='2651920'>the</span>
  <span m='2652010'>last</span> <span m='2652280'>two</span> <span m='2652430'>slides</span>
  <span m='2652850'>but</span> <span m='2652970'>I</span> <span m='2653060'>won't</span>
  <span m='2653210'>go</span> <span m='2653420'>over</span> <span m='2653660'>them</span>
  <span m='2653810'>right</span> <span m='2653990'>now.</span> </p><p><span m='2656360'>The</span>
  <span m='2656510'>idea</span> <span m='2657020'>of</span> <span m='2657230'>taking</span>
  <span m='2657620'>limits</span> <span m='2658070'>using</span> <span m='2658410'>Laplace</span>
  <span m='2658730'>transforms.</span> <span m='2660860'>It</span> <span m='2661010'>turns</span>
  <span m='2661370'>out</span> <span m='2661640'>that</span> <span m='2661790'>the</span>
  <span m='2661880'>Laplace</span> <span m='2662240'>transform</span> <span m='2662750'>is</span>
  <span m='2662870'>what</span> <span m='2662990'>we</span> <span m='2663110'>call</span>
  <span m='2663360'>a</span> <span m='2663380'>reciprocal</span> <span m='2663950'>function.</span>
  <span m='2665880'>Since</span> <span m='2666320'>the</span> <span m='2667460'>integrand</span>
  <span m='2668090'>depends</span> <span m='2668450'>and</span> <span m='2668540'>the</span>
  <span m='2668630'>product</span> <span m='2669020'>of</span> <span m='2669140'>s</span>
  <span m='2669320'>and</span> <span m='2669410'>t,</span> <span m='2669695'>s</span>
  <span m='2669980'>gets</span> <span m='2670220'>large,</span> <span m='2670610'>corresponds</span>
  <span m='2671090'>to</span> <span m='2671180'>t</span> <span m='2671360'>gets</span>
  <span m='2671540'>small.</span> <span m='2673950'>So</span> <span m='2674100'>you</span>
  <span m='2674190'>can</span> <span m='2674310'>take</span> <span m='2674520'>the</span>
  <span m='2674610'>limit</span> <span m='2675420'>for</span> <span m='2675630'>things</span>
  <span m='2677570'>with</span> <span m='2677820'>time</span> <span m='2678120'>getting</span>
  <span m='2678330'>small</span> <span m='2678720'>by</span> <span m='2678870'>looking</span>
  <span m='2679260'>at</span> <span m='2679550'>s</span> <span m='2679770'>getting</span>
  <span m='2680010'>big.</span> </p><p><span m='2681900'>Similarly,</span> <span m='2682470'>you</span>
  <span m='2682590'>can</span> <span m='2682680'>do</span> <span m='2682800'>the</span>
  <span m='2682890'>reverse.</span> <span m='2684530'>You</span> <span m='2684620'>can</span>
  <span m='2684770'>look</span> <span m='2684950'>at</span> <span m='2685040'>time</span>
  <span m='2685370'>gets</span> <span m='2685580'>big</span> <span m='2685830'>by</span>
  <span m='2686000'>looking</span> <span m='2686240'>at</span> <span m='2686330'>s
  gets</span> <span m='2686750'>small.</span> <span m='2688490'>That's</span> <span
  m='2688730'>just</span> <span m='2688940'>properties</span> <span m='2689750'>of</span>
  <span m='2690020'>the</span> <span m='2690140'>Laplace</span> <span m='2690530'>transform.</span>
  <span m='2690980'>And</span> <span m='2691130'>there's</span> <span m='2691310'>lots</span>
  <span m='2691580'>of</span> <span m='2691700'>others.</span> </p><p><span m='2692000'>Besides</span>
  <span m='2692480'>the</span> <span m='2692600'>table</span> <span m='2693650'>there's</span>
  <span m='2693860'>lots</span> <span m='2694130'>of</span> <span m='2694220'>properties</span>
  <span m='2694670'>we</span> <span m='2694790'>won't</span> <span m='2695030'>have</span>
  <span m='2695180'>time</span> <span m='2695420'>to</span> <span m='2695540'>go</span>
  <span m='2695720'>over</span> <span m='2696590'>but</span> <span m='2696830'>I</span>
  <span m='2696920'>will</span> <span m='2697100'>hint</span> <span m='2697380'>at</span>
  <span m='2697520'>some</span> <span m='2697760'>of</span> <span m='2697910'>them.</span>
  <span m='2698060'>And</span> <span m='2698150'>in</span> <span m='2698240'>particular,</span>
  <span m='2699170'>there's</span> <span m='2699320'>a</span> <span m='2699380'>very</span>
  <span m='2699770'>useful</span> <span m='2700070'>transformation</span> <span m='2700880'>where</span>
  <span m='2701000'>you</span> <span m='2701120'>take</span> <span m='2701310'>the</span>
  <span m='2701400'>Laplace</span> <span m='2701760'>transform</span> <span m='2702180'>of</span>
  <span m='2702320'>a</span> <span m='2702380'>circuit.</span> <span m='2702990'>And</span>
  <span m='2703040'>that's</span> <span m='2703240'>in</span> <span m='2703360'>the</span>
  <span m='2703440'>homework.</span> <span m='2705720'>So</span> <span m='2705840'>that's</span>
  <span m='2706080'>extremely</span> <span m='2706890'>useful.</span> </p><p><span
  m='2708540'>The</span> <span m='2708690'>major</span> <span m='2708990'>point</span>
  <span m='2709260'>then</span> <span m='2709800'>is</span> <span m='2710040'>just</span>
  <span m='2710310'>that</span> <span m='2710910'>there's</span> <span m='2711150'>lots</span>
  <span m='2711540'>of</span> <span m='2711630'>relationships,</span> <span m='2712260'>there's</span>
  <span m='2712410'>lots</span> <span m='2712620'>of</span> <span m='2712680'>ways</span>
  <span m='2712890'>we</span> <span m='2713010'>think</span> <span m='2713190'>about</span>
  <span m='2713370'>CT</span> <span m='2713760'>systems.</span> <span m='2714370'>This</span>
  <span m='2714750'>Laplace</span> <span m='2715110'>transform</span> <span m='2715590'>is</span>
  <span m='2715710'>a</span> <span m='2715770'>new</span> <span m='2715980'>one</span>
  <span m='2717480'>and</span> <span m='2717600'>it's</span> <span m='2717750'>very</span>
  <span m='2718080'>useful</span> <span m='2718800'>because</span> <span m='2719280'>of</span>
  <span m='2719370'>the</span> <span m='2719460'>properties</span> <span m='2719940'>in</span>
  <span m='2720060'>that</span> <span m='2720180'>table.</span> <span m='2722360'>OK,</span>
  <span m='2722710'>thanks</span> <span m='2722890'>a</span> <span m='2722920'>lot.</span>
  </p>
type: course
uid: b07bd25e99c61fa163548ac901a0b605

---
None