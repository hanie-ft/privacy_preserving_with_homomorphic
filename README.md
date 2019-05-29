# privacy_preserving_with_homomorphic

Paper here: https://www.overleaf.com/project/5ceba28f48dfde5746a3ecf3

# Sample runs

I have added tests:

* ZKP voting. https://asecuritysite.com/encryption/go_priv
* ElGamal Multiply. https://asecuritysite.com/encryption/go_el_homo
* ElGamal Divide. https://asecuritysite.com/encryption/go_el_homo2 
* ElGamal Additive. https://asecuritysite.com/encryption/go_el_homo3

To run your tests:

go build go_priv.go

Then run:

go_priv [v1] [v2] [v3] [v4] [v5]

where [v1] is the vote for Voter 1, eg:

<pre>
Vote1: 1, Vote2: 2, Vote3: 5, Vote4: 4, Vote5: 7

Result: 9499059345615389969840435808419125566245033357929304072344622690626502412542421684367703931302105397849390388675957378812140288740537857002835713186278293

Total votes: 19

Voter 1 (Vote Registration): 9717449441774596863932107182522723015293019558573861235057183453449918138887484006291371511239749270767730899934430122393332033312936519989621006232074095

Voter 2 (Vote Registration): 9979211979303271906561128573865484289840376149275844120064408657002526626214797587891497218571132555435308773667814984558530219287171718477448831292894276

Voter 3 (Vote Registration): 10260226055060144909495657309307620665975071716357821511668071773900528485759688558486229480267259436593234659383692953025154725723321456089371862729851636

Voter 4 (Vote Registration): 9374282770821534675247529713877083124189697278016496283445307756495925999913081637387484809415414806767669261226720017163156578480783405351792775885639485

Voter 5 (Vote Registration): 4715963672204178893519744645692315549756487065582594365925661689297962812692255475841524311321805156191081950992986134375414091134136796396861607730531987

Voter 1 (Vote Value): 32401232193006155720196638992531749412084427625631678775764791290303067299038470925303292706484585376785616471016503624166807297868000818159189905703742127006021153078333400603184740396745033006868636123575476150574731231178751789899302048597281566920155032719238246134742893881885934332176587099252458401520

Voter 2 (Vote Value): 22406638132804436992749249332952255862162414944274300242628892974896078442234146704784479269219657506758579636670217945256674939338444271409977122656492124652882892514131096981560147734302688011165533810813487451674675199550957033283366017521668531453196706310725822481137764122042248446613834059798769842615

Voter 3 (Vote Value): 11834926401421874979308640231507451884942087416483011363111684342351525054363986593712103415883169303927633242165502268430163354878431359401053897301322619263682111064193604401114412618063533264047238753072165283347737047811644373914381304774348253452543539995578870900232732281890514453274058217545113710666

Voter 4 (Vote Value): 9010114599879211200405233875413417299014138956847221705372417222243449960878258128009741739156673077210332638713398209172206282380236417865418977282905859379831673974563957671842162376097005309032662153452734661963752442476145490385627496849733054419140843839444313342637419185836216665660748272509770080480

Voter 5 (Vote Value): 21219110896547932984699096012205897827178091285359326237468919338515016060660237484642042927251805611756927000698809651784889873791932282484359734714554873875258800569641390232193260619426197901273988198800139619942591866665242425682016857024332330895501275000000583742729422468884919102219079592569480126060
</pre>


