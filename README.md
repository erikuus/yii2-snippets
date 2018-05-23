# Sublime Text Yii2 Snippets

Useful Yii2 snippets for [Sublime text](https://sublimetext.com)


## Navigation
- [Index](#index)
- [Behaviors](#behaviors)
- [Events](#events)
- [Validation rules](#validation-rules)
- [RBAC](#rbac)

- [Installation](#installation)
- [Yii](#yii)
- [Html](#html)
- [ActiveField](#activefield)
- [ArrayHelper](#arrayhelper)
- [FileHelper](#filehelper)
- [Url](#url)
- [Json](#json)
- [StringHelper](#stringhelper)
- [Request](#request)
- [User](#user)
- [Session](#session)
- [Cache](#cache)
- [Active Record](#active-record)
- [Displaying Data](#displaying-data)
- [Register](#register)
- [Render](#render)
- [Validation scenarios](#validation-scenarios)
- [Database Migration](#database-migration)
- [Database Schema](#database-schema)
- [Other](#other)
- [License](#license)
- [PS](#ps)


### Installation

There are several methods to install package.

1. Search for Yii2 Snippets on Package Control.

2. Clone the repository into your Sublime Text 2/3 packages directory.
**Note:** You can find your packages directory by going to Preferences -> Browse Packages.

### Index

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| Behaviors                        | IB           |
| Events                           | IE           |
| Validation                       | IV           |
| RBAC                             | IRB          |

### Behaviors

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| behaviors                        | B            |
| SluggableBehavior                | Bslug        |
| BlameableBehavior                | Bblame       |
| TimestampBehavior                | Btime        |
| TimestampBehavior advanced       | Btime2       |
| TimestampBehavior touch          | Btouch       |

### Events

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| beforeValidate                   | Ebv          |
| beforeSave                       | Ebs          |
| beforeDelete                     | Ebd          |
| afterValidate                    | Eav          |
| afterSave                        | Eas          |
| afterDelete                      | Ead          |
| afterFind                        | Eaf          |

### Validation

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| boolean                          | Vboolean     |
| captcha                          | Vcaptcha     |
| compare                          | Vcompare     |
| default                          | Vdefault     |
| double                           | Vdouble      |
| each                             | Veach        |
| email                            | Vemail       |
| required                         | Vrequired    |
| trim                             | Vtrim        |
| date                             | Vdate        |
| exist                            | Vexist       |
| file                             | Vfile        |
| in                               | Vin          |
| integer                          | Vinteger     |
| number                           | Vnumber      |
| match                            | Vmatch       |
| safe                             | Vsafe        |
| string                           | Vstring      |
| unique                           | Vunique      |
| url                              | Vurl         |
| filter                           | Vfilter      |
| custom                           | Vcustom      |
| custom function                  | VcustomFunc  |
| when conditon                    | Vwhen        |
| ad hoc validator                 | Vadhoc       |
| ad hoc dynamic model             | Vadhoc2      |
| scenarios                        | Vscenarios   |
| scenarios advanced               | Vscenarios2  |
| scenario construct               | VscenarioSet |

### RBAC

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| createPermission                 | RBpermission |
| define rule                      | RBdr         |
| define rule isOwner              | RBdro        |
| define rule isSelf               | RBdrs        |
| add rules                        | RBar         |
| createPermission with rule       | RBcpwr       |
| createRole                       | RBcr         |
| assign role/permission to user   | RBa          |
| assign to user after save        | RBaas        |
| enforce authorization            | RBea         |

### Json

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| encode                           | Je           |
| htmlEncode                       | Jhe          |
| decode                           | Jd           |

### Yii

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| translate                        | Yt           |
| echo translate                   | Yte          |
| setAlias                         | Ysa          |
| getAlias                         | Yga          |
| user                             | Yu           |
| controller                       | Yc           |
| action                           | Ya           |


### Html

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| encode                           | He           |
| a                                | Ha           |
| mailto                           | Hmail        |
| img                              | Himg         |
| label                            | Hl           |
| button                           | Hb           |
| submitButton                     | Hsb          |
| resetButton                      | Hrb          |
| input                            | Hi           |
| submitInput                      | Hsi          |
| resetInput                       | Hri          |
| textInput                        | Hti          |
| hiddenInput                      | Hhi          |
| passwordInput                    | Hpi          |
| fileInput                        | Hfi          |
| textarea                         | Hta          |
| radio                            | Hrd          |
| checkbox                         | Hcb          |
| dropDownList                     | Hdl          |
| listBox                          | Hlb          |
| checkboxList                     | Hcbl         |
| radioList                        | Hrdl         |
| activeLabel                      | Hal          |
| activeHint                       | Hah          |
| errorSummary                     | Hes          |
| error                            | Herr         |
| activeInput                      | Hai          |
| activeTextInput                  | Hati         |
| activeHiddenInput                | Hahi         |
| activePasswordInput              | Hapi         |
| activeFileInput                  | Hafi         |
| activeTextarea                   | Hata         |
| activeRadio                      | Hard         |
| activeCheckbox                   | Hacb         |
| activeDropDownList               | Hadl         |
| activeListBox                    | Halb         |
| activeCheckboxList               | Hacbl        |
| activeRadioList                  | Hardl        |


### ActiveField

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| textInput                        | AFti         |
| hiddenInput                      | AFhi         |
| passwordInput                    | AFpi         |
| fileInput                        | AFfi         |
| textarea                         | AFta         |
| radio                            | AFrd         |
| checkbox                         | AFcb         |
| dropDownList                     | AFdl         |
| listBox                          | AFlb         |
| checkboxList                     | AFcbl        |
| radioList                        | AFrdl        |
| widget                           | AFw          |


### ArrayHelper

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| toArray                          | AHta         |
| merge                            | AHm          |
| getValue                         | AHgv         |
| remove                           | AHr          |
| index                            | AHi          |
| getColumn                        | AHgc         |
| map                              | AHmap        |
| keyExists                        | AHke         |
| multisort                        | AHsort       |
| htmlEncode                       | AHe          |


### FileHelper

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| normalizePath                    | FHnp         |
| localize                         | FHl          |
| getMimeType                      | FHgmt        |
| getMimeTypeByExtension           | FHgmtbe      |
| getExtensionsByMimeType          | FHgebmt      |
| copyDirectory                    | FHcpd        |
| removeDirectory                  | FHrd         |
| findFiles                        | FHff         |
| filterPath                       | FHfp         |
| createDirectory                  | FHcd         |


### Url

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| toRoute                          | Utr          |
| to                               | Ut           |
| base                             | Ub           |
| remember                         | Ur           |
| previous                         | Up           |
| current                          | Uc           |
| home                             | Uh           |
| isRelative                       | Uir          |


### StringHelper

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| byteLength                       | SHbl         |
| byteSubstr                       | SHbs         |
| basename                         | SHbn         |
| dirname                          | SHdn         |
| truncate                         | SHtr         |
| truncateWords                    | SHtrw        |
| startsWith                       | SHsw         |
| endsWith                         | SHew         |
| explode                          | SHexp        |


### Request

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| resolve                          | Rres         |
| headers                          | Rh           |
| method                           | Rm           |
| isGet                            | Rig          |
| isOptions                        | Rio          |
| isHead                           | Rih          |
| isPost                           | Rip          |
| isDelete                         | Rid          |
| isPut                            | Riput        |
| isPatch                          | Ripatch      |
| isAjax                           | Ria          |
| isPjax                           | Ripj         |
| isFlash                          | Rif          |
| rawBody                          | Rrb          |
| setRawBody                       | Rsrb         |
| bodyParams                       | Rbps         |
| setBodyParams                    | Rsbps        |
| getBodyParam                     | Rbp          |
| post                             | Rp           |
| queryParams                      | Rqps         |
| setQueryParams                   | Rsqps        |
| get                              | Rg           |
| getQueryParam                    | Rqp          |
| hostInfo                         | Rhi          |
| setHostInfo                      | Rshi         |
| baseUrl                          | Rbu          |
| setBaseUrl                       | Rsbu         |
| absoluteUrl                      | Rau          |
| url                              | Ru           |
| setUrl                           | Rsu          |
| queryString                      | Rqs          |
| isSecureConnection               | Risc         |
| serverName                       | Rsm          |
| serverPort                       | Rsp          |
| referrer                         | Rref         |
| userAgent                        | Rua          |
| userIP                           | Ruip         |
| userHost                         | Ruh          |
| cookies                          | Rcook        |
| getCsrfToken                     | Rcsrf        |
| csrfTokenFromHeader              | Rcsrfh       |
| validateCsrfToken                | Rcsrfv       |


### User

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| identity                         | Ui           |
| switchIdentity                   | Usi          |
| login                            | Ul           |
| loginByAccessToken               | Ulbat        |
| logout                           | Ulogout      |
| isGuest                          | Uig          |
| id                               | Uid          |
| getReturnUrl                     | Ugru         |
| setReturnUrl                     | Usru         |
| loginRequired                    | Ulr          |
| can                              | Ucan         |


### Session

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| open                             | Sop          |
| close                            | Scl          |
| destroy                          | Sdesr        |
| isActive                         | Sia          |
| hasSessionId                     | Shsi         |
| setHasSessionId                  | Sshsi        |
| id                               | Sid          |
| setId                            | Ssid         |
| regenerateID                     | Srgid        |
| name                             | Sname        |
| setName                          | Ssname       |
| savePath                         | Ssp          |
| setSavePath                      | Sssp         |
| cookieParams                     | Scp          |
| setCookieParams                  | Sscp         |
| useCookies                       | Suc          |
| setUseCookies                    | Ssuc         |
| openSession                      | Sos          |
| closeSession                     | Scs          |
| readSession                      | Sread        |
| writeSession                     | Swrite       |
| destroySession                   | Sdestroy     |
| count                            | Scount       |
| get                              | Sget         |
| set                              | Sset         |
| remove                           | Sremove      |
| removeAll                        | SremoveAll   |
| has                              | Shas         |
| getFlash                         | Sfl          |
| addFlash                         | Safl         |
| setFlash                         | Ssfl         |
| removeFlash                      | Srfl         |
| removeAllFlashes                 | Srafl        |
| hasFlash                         | Shfl         |


### Cache

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| buildKey                         | Cbk          |
| get                              | Cg           |
| exists                           | Ce           |
| mget                             | Cmg          |
| set                              | Cs           |
| mset                             | Cms          |
| madd                             | Cma          |
| add                              | Ca           |
| delete                           | Cd           |
| flush                            | Cf           |
| offsetExists                     | Coe          |
| offsetGet                        | Cog          |
| offsetSet                        | Cos          |
| offsetUnset                      | Cou          |


### Active Record

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| find                             | Mf           |
| find-all                         | Ma           |
| find-one                         | Mo           |
| find-count                       | Mc           |
| find-exists                      | Me           |
| find-max                         | Mmax         |
| find-min                         | Mmin         |
| model-findOne                    | Mfo          |
| model-findAll                    | Mfa          |
| model-findBySql                  | Mbs          |
| model-updateAll                  | Mua          |
| model-updateAllCounters          | Muac         |
| model-deleteAll                  | Mda          |
| model-newScenario                | Mns          |


### Displaying Data

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| ListView                         | Lw           |
| GridView                         | Gw           |
| LinkPager                        | Lp           |
| HtmlPurifier                     | HPp          |


### Register

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| registerJs                       | Yrj          |
| registerJsFile                   | Yrjf         |
| registerCss                      | Yrc          |
| registerCssFile                  | Yrcf         |
| registerMetaTag                  | Yrmt         |


### Render

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| render                           | RD           |
| renderHtml                       | RDh          |
| renderPartial                    | RDp          |
| renderAjax                       | RDa          |


### Database Migration

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| execute                          | DMe          |
| createTable                      | DMct         |
| dropTable                        | DMdt         |
| truncateTable                    | DMtt         |
| renameTable                      | DMrt         |
| addColumn                        | DMac         |
| dropColumn                       | DMdc         |
| renameColumn                     | DMrc         |
| alterColumn                      | DMalc        |
| addPrimaryKey                    | DMapk        |
| dropPrimaryKey                   | DMdpk        |
| addForeignKey                    | DMafk        |
| dropForeignKey                   | DMdfk        |
| createIndex                      | DMci         |
| dropIndex                        | DMdi         |
| insert                           | DMi          |
| batchInsert                      | DMbi         |
| update                           | DMu          |
| delete                           | DMd          |


### Database Schema

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| primaryKey                       | DSpk         |
| bigPrimaryKey                    | DSbpk        |
| string                           | DSs          |
| text                             | DSt          |
| smallInteger                     | DSsi         |
| integer                          | DSi          |
| bigInteger                       | DSbi         |
| float                            | DSf          |
| double                           | DSd          |
| decimal                          | DSdc         |
| money                            | DSm          |
| dateTime                         | DSdt         |
| timestamp                        | DSts         |
| time                             | DStime       |
| date                             | DSdt         |
| boolean                          | DSbool       |
| binary                           | DSbin        |


### Other

| Method                           | Snippet code |
|--------------------------------- | :----------: |
| ActiveDataProvider               | Adp          |
| transaction                      | Tra          |



### License

Yii2 Snippets is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).


### PS

If you have any ideas to improve this package or you found any errors, please contact me via Github.
