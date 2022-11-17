# JavaScript Interview Questions & Answers

> Agar sizga loyiha yoqsa :star: bosing. Texnik yangilanishlar uchun meni [@ssamir_20 Twitter](https://twitter.com/ssamir_20) <= || => [@ssamir_20 Instagram](https://www.instagram.com/ssamir_20/) kuzatib boring.

Maxsus savollarni kodlash uchun [Coding Exercise](#coding-exercise) o'ting.

## PDF/Epub formatlarini yuklab oling

Siz ushbu reponing PDF va Epub versiyasini [amallar yorlig'idagi](https://github.com/sulaymonov2002/javascript-interview-questions) so'nggi ishga tushirishdan yuklab olishingiz mumkin.

---

### Mundarija

| No. | Savollar                                                                                                                                                         |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [JavaScript-da ob'ektlarni yaratishning qanday usullari bor ?](#what-are-the-possible-ways-to-create-objects-in-javascript)                                      |
| 2   | [Prototype chain nima ?](#what-is-a-prototype-chain)                                                                                                             |
| 3   | [Call, Apply va Bind orasidagi farq nima ?](#what-is-the-difference-between-call-apply-and-bind)                                                                 |
| 4   | [JSON nima va uning umumiy operatsiyalari](#what-is-json-and-its-common-operations)                                                                              |
| 5   | [Massiv slice usulidan maqsad nima ?](#what-is-the-purpose-of-the-array-slice-method)                                                                            |
| 6   | [Massivni splice usulining maqsadi nima ?](#what-is-the-purpose-of-the-array-splice-method)                                                                      |
| 7   | [Slice va splice o'rtasidagi farq nima ?](#what-is-the-difference-between-slice-and-splice)                                                                      |
| 8   | [Ob'ekt va Map qanday taqqoslaysiz](#how-do-you-compare-object-and-map)                                                                                          |
| 9   | [== va === operatorlarning farqi nimada ?](#what-is-the-difference-between--and--operators)                                                                      |
| 10  | [lambda yoki arrow function nima ?](#what-are-lambda-or-arrow-functions)                                                                                         |
| 11  | [Birinchi class function nima ?](#what-is-a-first-class-function)                                                                                                |
| 12  | [Birinchi order function nima ?](#what-is-a-first-order-function)                                                                                                |
| 13  | [Yuqori tartibli funksiya nima ?](#what-is-a-higher-order-function)                                                                                              |
| 14  | [unary function nima ?](#what-is-a-unary-function)                                                                                                               |
| 15  | [currying function nima ?](#what-is-the-currying-function)                                                                                                       |
| 16  | [pure function nima ?](#what-is-a-pure-function)                                                                                                                 |
| 17  | [let kalit so'zining maqsadi nima ?](#what-is-the-purpose-of-the-let-keyword)                                                                                    |
| 18  | [let va var o'rtasidagi farq nima ?](#what-is-the-difference-between-let-and-var)                                                                                |
| 19  | [kalit so'zi sifatida let nomini tanlashning sababi nimada ?](#what-is-the-reason-to-choose-the-name-let-as-a-keyword)                                           |
| 20  | [swtich blockdagi o'zgarishlarni qanday qilib xatosiz qayta e'lon qilish mumkin ?](#how-do-you-redeclare-variables-in-switch-block-without-an-error)             |
| 21  | [Temporal Dead Zone nima ?](#what-is-the-temporal-dead-zone)                                                                                                     |
| 22  | [IIFE(darhol chaqiriladigan funksiya ifodasi)nima ?](#what-is-iifeimmediately-invoked-function-expression)                                                       |
| 23  | [JavaScript-da URL-manzilini decode yoki code lash mumkin ?](#how-do-you-decode-or-encode-a-url-in-javascript)                                                   |
| 24  | [Memoization nima ?](#what-is-memoization)                                                                                                                       |
| 25  | [Hoisting nima ?](#what-is-hoisting)                                                                                                                             |
| 26  | [ES6 da qanday sinflar mavjud ?](#what-are-classes-in-es6)                                                                                                       |
| 27  | [Closures nima ?](#what-are-closures)                                                                                                                            |
| 28  | [Modullar nima ?](#what-are-modules)                                                                                                                             |
| 29  | [Nima uchun sizga modullar kerak ?](#why-do-you-need-modules)                                                                                                    |
| 30  | [JavaScriptda scope nima ?](#what-is-scope-in-javascript)                                                                                                        |
| 31  | [Service worker nima ?](#what-is-a-service-worker)                                                                                                               |
| 32  | [Service worker yordamida DOMni qanday boshqarish mumkin ?](#how-do-you-manipulate-dom-using-a-service-worker)                                                   |
| 33  | [Service worker ni qayta ishga tushirishda ma'lumotdan qanday foydalanasiz ?](#how-do-you-reuse-information-across-service-worker-restarts)                      |
| 34  | [IndexedDB nima ?](#what-is-indexeddb)                                                                                                                           |
| 35  | [Web storage nima ?](#what-is-web-storage)                                                                                                                       |
| 36  | [Post xabari nima ?](#what-is-a-post-message)                                                                                                                    |
| 37  | [cookie nima ?](#what-is-a-cookie)                                                                                                                               |
| 38  | [Cookie nima uchun kerak ?](#why-do-you-need-a-cookie)                                                                                                           |
| 39  | [Cookie-da qanday variantlar mavjud ?](#what-are-the-options-in-a-cookie)                                                                                        |
| 40  | [Cookie faylini qanday o'chirish mumkin ?](#how-do-you-delete-a-cookie)                                                                                          |
| 41  | [Cookie, local storage va session storage o'rtasidagi farqlar qanday ?](#What-are-the-differences-between-cookie-local-storage-and-session-storage)              |
| 42  | [localStorage va sessionStorage o'rtasidagi asosiy farq nima ?](#what-is-the-main-difference-between-localstorage-and-sessionstorage)                            |
| 43  | [Veb-xotiraga qanday kirish mumkin ?](#how-do-you-access-web-storage)                                                                                            |
| 44  | [session storage qanday usullar mavjud ?](#what-are-the-methods-available-on-session-storage)                                                                    |
| 45  | [storage event nima va uning event handler ?](#what-is-a-storage-event-and-its-event-handler)                                                                    |
| 46  | [Nima uchun sizga web storage kerak ?](#why-do-you-need-web-storage)                                                                                             |
| 47  | [Web storage browser yordamini qanday tekshirish mumkin ?](#how-do-you-check-web-storage-browser-support)                                                        |
| 48  | [Web workers browser qo'llab-quvvatlashini qanday tekshirish mumkin ?](#how-do-you-check-web-workers-browser-support)                                            |
| 49  | [Web worker ga misol keltiring ?](#give-an-example-of-a-web-worker)                                                                                              |
| 50  | [DOM-da web worker larning cheklovlari qanday ?](#what-are-the-restrictions-of-web-workers-on-dom)                                                               |
| 51  | [Promise nima ?](#what-is-a-promise)                                                                                                                             |
| 52  | [Promise nimaga kerak ?](#why-do-you-need-a-promise)                                                                                                             |
| 53  | [Promise(ning) uchta holati nima?](#what-are-the-three-states-of-promise)                                                                                        |
| 54  | [Callback function nima ?](#what-is-a-callback-function)                                                                                                         |
| 55  | [Callback(lar) nimaga kerak ?](#why-do-we-need-callbacks)                                                                                                        |
| 56  | [Callback hell nima ?](#what-is-a-callback-hell)                                                                                                                 |
| 57  | [Server tomonidan yuborilgan event(lar) nima ?](#what-are-server-sent-events)                                                                                    |
| 58  | [Server tomonidan yuborilgan event bildirishnomalarini qanday qabul qilasiz ?](#how-do-you-receive-server-sent-event-notifications)                              |
| 59  | [Server tomonidan yuborilgan event(lar) uchun brauzer yordamini qanday tekshirish mumkin ?](#how-do-you-check-browser-support-for-server-sent-events)            |
| 60  | [Server yuborilgan event(lar) uchun qanday hodisalar mavjud](#what-are-the-events-available-for-server-sent-events)                                              |
| 61  | [Promise berishning asosiy qoidalari qanday](#what-are-the-main-rules-of-promise)                                                                                |
| 62  | [Callback(da) qayta callback nima ?](#what-is-callback-in-callback)                                                                                              |
| 63  | [Promise chaining nima ?](#what-is-promise-chaining)                                                                                                             |
| 64  | [Promise.all nima ?](#what-is-promiseall)                                                                                                                        |
| 65  | [Promise(da) poyga usulining maqsadi nima ?](#what-is-the-purpose-of-the-race-method-in-promise)                                                                 |
| 66  | [JavaScript(da) qat'iy rejim nima ?](#what-is-a-strict-mode-in-javascript)                                                                                       |
| 67  | [Strict mode nimaga kerak ?](#why-do-you-need-strict-mode)                                                                                                       |
| 68  | [Nima uchun sizga strict mode kerak ?](#how-do-you-declare-strict-mode)                                                                                          |
| 69  | [Qo‘sh undovdan maqsad nima ?](#what-is-the-purpose-of-double-exclamation)                                                                                       |
| 70  | [O'chirish operatorining maqsadi nima ?](#what-is-the-purpose-of-the-delete-operator)                                                                            |
| 71  | [typeof operator nima ?](#what-is-typeof-operator)                                                                                                               |
| 72  | [undefined property nima ?](#what-is-undefined-property)                                                                                                         |
| 73  | [null value nima ?](#what-is-null-value)                                                                                                                         |
| 74  | [Null va undefined o'rtasidagi farq nima ?](#what-is-the-difference-between-null-and-undefined)                                                                  |
| 75  | [eval nima ?](#What-is-eval)                                                                                                                                     |
| 76  | [Window va document o'rtasidagi farq nima ?](#what-is-the-difference-between-window-and-document)                                                                |
| 77  | [JavaScript(da) history(ga) qanday kirish mumkin ?](#how-do-you-access-history-in-javascript)                                                                    |
| 78  | [Caps lock tugmachasi yoqilgan yoki yo'qligini qanday aniqlash mumkin ?](#how-do-you-detect-caps-lock-key-turned-on-or-not)                                      |
| 79  | [isNaN nima ?](#what-is-isnan)                                                                                                                                   |
| 80  | [undeclared va undefined o'zgaruvchilari o'rtasidagi farqlar qanday ?](#what-are-the-differences-between-undeclared-and-undefined-variables)                     |
| 81  | [Global variables nima ?](#what-are-global-variables)                                                                                                            |
| 82  | [Global variabl(lar) bilan qanday muammolar bor ?](#what-are-the-problems-with-global-variables)                                                                 |
| 83  | [NaN property nima ?](#what-is-nan-property)                                                                                                                     |
| 84  | [isFinite funksiyasining maqsadi nima ?](#what-is-the-purpose-of-isfinite-function)                                                                              |
| 85  | [Event flow nima ?](#what-is-an-event-flow)                                                                                                                      |
| 86  | [Event bubbling nima ?](#what-is-event-bubbling)                                                                                                                 |
| 87  | [Event capturing nima ?](#what-is-event-capturing)                                                                                                               |
| 88  | [Qanday qilib JavaScript-dan foydalanib shaklni yuborasiz ?](#how-do-you-submit-a-form-using-javascript)                                                         |
| 89  | [Operating system tafsilotlarini qanday topish mumkin ?](#how-do-you-find-operating-system-details)                                                              |
| 90  | [Document load va DOMContentLoaded hodisalari o'rtasidagi farq nima ?](#what-is-the-difference-between-document-load-and-domcontentloaded-events)                |
| 91  | [Native, host va user objects o'rtasidagi farq nima ?](#what-is-the-difference-between-native-host-and-user-objects)                                             |
| 92  | [JavaScript code(ni) tuzatish uchun qanday vositalar yoki usullar qo'llaniladi ?](#what-are-the-tools-or-techniques-used-for-debugging-javascript-code)          |
| 93  | [Callbacks orqali promise(ning) qanday ijobiy va salbiy tomonlari bor ?](#what-are-the-pros-and-cons-of-promises-over-callbacks)                                 |
| 94  | [Attribute va property o'rtasidagi farq nima ?](#what-is-the-difference-between-an-attribute-and-a-property)                                                     |
| 95  | [Same-origin policy nima ?](#what-is-same-origin-policy)                                                                                                         |
| 96  | [Void 0 ning maqsadi nima ?](#what-is-the-purpose-of-void-0)                                                                                                     |
| 97  | [JavaScript kompilyatsiya qilingan yoki tarjima qilingan tilmi ?](#is-javascript-a-compiled-or-interpreted-language)                                             |
| 98  | [JavaScript case-sensitive harflarga sezgir tilmi ?](#is-javascript-a-case-sensitive-language)                                                                   |
| 99  | [Java va JavaScript o'rtasida bog'liqlik bormi?](#is-there-any-relation-between-java-and-javascript)                                                             |
| 100 | [event(lar) nima ?](#what-are-events)                                                                                                                            |
| 101 | [JavaScriptni kim yaratgan ?](#who-created-javascript)                                                                                                           |
| 102 | [preventDefault usulidan fodalanish nima ?](#what-is-the-use-of-preventdefault-method)                                                                           |
| 103 | [stopPropagation usulidan foydalanish nima ?](#what-is-the-use-of-stoppropagation-method)                                                                        |
| 104 | [Noto'g'ri foydalanishni qaytarish uchun qanday usullar mavjud ?](#what-are-the-steps-involved-in-return-false-usage)                                            |
| 105 | [BOM nima ?](#what-is-bom)                                                                                                                                       |
| 106 | [setTimeout(dan) qanday foydalanish kerak ?](#what-is-the-use-of-settimeout)                                                                                     |
| 107 | [setInterval(dan) qanday foydalanish kerak ?](#what-is-the-use-of-setinterval)                                                                                   |
| 108 | [Nima uchun JavaScript Single threaded deb hisoblanadi ?](#why-is-javascript-treated-as-single-threaded)                                                         |
| 109 | [Event delegation nima ?](#what-is-an-event-delegation)                                                                                                          |
| 110 | [ECMAScript nima ?](#what-is-ecmascript)                                                                                                                         |
| 111 | [JSON nima ?](#what-is-json)                                                                                                                                     |
| 112 | [JSON sintaksisi qoidalari qanday ?](#what-are-the-syntax-rules-of-json)                                                                                         |
| 113 | [JSON stringify nima maqsadda ishlatiladi ?](#what-is-the-purpose-json-stringify)                                                                                |
| 114 | [JSON string(ni) qanday parse qilasiz ?](#how-do-you-parse-json-string)                                                                                          |
| 115 | [JSON nimaga kerak ?](#why-do-you-need-json)                                                                                                                     |
| 116 | [PWAs nima ?](#what-are-pwas)                                                                                                                                    |
| 117 | [clearTimeout usulining maqsadi nima ?](#what-is-the-purpose-of-cleartimeout-method)                                                                             |
| 118 | [clearInterval usulining maqsadi nima ?](#what-is-the-purpose-of-clearinterval-method)                                                                           |
| 119 | [Javascriptda yangi sahifani qanday yo'naltirish mumkin ?](#how-do-you-redirect-new-page-in-javascript)                                                          |
| 120 | [Sring(da) substring mavjudligini qanday tekshirish mumkin ?](#how-do-you-check-whether-a-string-contains-a-substring)                                           |
| 121 | [Javascriptda elektron pochtani qanday tekshirish mumkin ?](#how-do-you-validate-an-email-in-javascript)                                                         |
| 122 | [Current url(ni) javascript bilan qanday olish mumkin ?](#how-do-you-get-the-current-url-with-javascript)                                                        |
| 123 | [Location object(ning) turli url xususiyatlari qanday ?](#what-are-the-various-url-properties-of-location-object)                                                |
| 124 | [JavaScript(da) query string value(sini) qanday olish mumkin ?](#how-do-get-query-string-values-in-javascript)                                                   |
| 125 | [Object(da) key mavjudligini qanday tekshirish mumkin ?](#how-do-you-check-if-a-key-exists-in-an-object)                                                         |
| 126 | [JavaScript(da) object(ni) qanday loop yoki enumerat qilasiz ?](#how-do-you-loop-through-or-enumerate-javascript-object)                                         |
| 127 | [Empty object(ni) qanday sinab ko'rasiz ?](#how-do-you-test-for-an-empty-object)                                                                                 |
| 128 | [Arguments object nima ?](#what-is-an-arguments-object)                                                                                                          |
| 129 | [Qanday qilib string(ning) birinchi harfini katta harf bilan yozish mumkin ?](#how-do-you-make-first-letter-of-the-string-in-an-uppercase)                       |
| 130 | [Loop(ning) qanday ijobiy va salbiy tomonlari bor ?](#what-are-the-pros-and-cons-of-for-loop)                                                                    |
| 131 | [Current date(ni) JavaScript(da) qanday ko'rsatasiz ?](#how-do-you-display-the-current-date-in-javascript)                                                       |
| 132 | [Ikki sana object(ni) qanday solishtirasiz ?](#how-do-you-compare-two-date-objects)                                                                              |
| 133 | [String(ning) boshqa string bilan boshlanishini qanday tekshirish mumkin ?](#how-do-you-check-if-a-string-starts-with-another-string)                            |
| 134 | [JavaScript(da) string(ni) qanday kesish mumkin ?](#how-do-you-trim-a-string-in-javascript)                                                                      |
| 135 | [JavaScript(da) key value qiymat juftligini qanday qo'shasiz ?](#how-do-you-add-a-key-value-pair-in-javascript)                                                  |
| 136 | ['!--' belgisi maxsus operatorni ifodalaydi](#is-the----notation-represents-a-special-operator)                                                                  |
| 137 | [O'zgaruvchilarga standart qiymatlarni qanday belgilash mumkin ?](#how-do-you-assign-default-values-to-variables)                                                |
| 138 | [Ko'p qatorli string(larni) qanday aniqlash mumkin ?](#how-do-you-define-multiline-strings)                                                                      |
| 139 | [App shell model nima ?](#what-is-an-app-shell-model)                                                                                                            |
| 140 | [Funktsiyalar uchun xususiyatlarni aniqlay olamizmi ?](#can-we-define-properties-for-functions)                                                                  |
| 141 | [Funksiya kutayotgan parametrlar sonini qanday topish mumkin ?](#what-is-the-way-to-find-the-number-of-parameters-expected-by-a-function)                        |
| 142 | [Polyfill nima ?](#what-is-a-polyfill)                                                                                                                           |
| 143 | [Break and continue statements nima ?](#what-are-break-and-continue-statements)                                                                                  |
| 144 | [Js labels nima ?](#what-are-js-labels)                                                                                                                          |
| 145 | [Declaration(larni) yuqorida saqlashning qanday afzalliklari bor ?](#what-are-the-benefits-of-keeping-declarations-at-the-top)                                   |
| 146 | [variable(larni) ishga tushirishning qanday afzalliklari bor ?](#what-are-the-benefits-of-initializing-variables)                                                |
| 147 | [New object yaratish uchun qanday tavfsiyalar mavud ?](#what-are-the-recommendations-to-create-new-object)                                                       |
| 148 | [JSON array(larini) qanday aniqlaysiz ?](#how-do-you-define-json-arrays)                                                                                         |
| 149 | [Tasodifiy butun sonlar qanday yaratiladi ?](#how-do-you-generate-random-integers)                                                                               |
| 150 | [Butun sonlarni diapazonda chop etish uchun tasodifiy funksiyasini yoza olasizmi ?](#can-you-write-a-random-integers-function-to-print-integers-with-in-a-range) |
| 151 | [Tree shaking nima ?](#what-is-tree-shaking)                                                                                                                    |
| 152 | [Tree shaking nimaga kerak ?](#what-is-the-need-of-tree-shaking)                                                                                            |
| 153 | [Eval dan foydalanish tavsiya etiladimi ?](#is-it-recommended-to-use-eval)                                                                                                  |
| 154 | [Regular Expression nima ?](#what-is-a-regular-expression)                                                                                                    |
| 155 | [Regular expression(da) qanday qator usullari mavjud ?](#what-are-the-string-methods-available-in-regular-expression)                                      |
| 156 | [Regular Expression(dagi) modifikatorlar nima ?](#what-are-modifiers-in-regular-expression)                                                                            |
| 157 | [Regular Expression patterns nima ?](#what-are-regular-expression-patterns)                                                                                    |
| 158 | [RegExp object nima ?](#what-is-a-regexp-object)                                                                                                              |
| 159 | [pattern uchun string(ni) qanday qidirasiz ?](#how-do-you-search-a-string-for-a-pattern)                                                                            |
| 160 | [Exec method(ning) maqsadi nima ?](#what-is-the-purpose-of-exec-method)                                                                                        |
| 161 | [HTML elementining uslubini qanday o'zgartirish mumkin ?](#how-do-you-change-the-style-of-a-html-element)                                                                  |
| 162 | [1+2+'3' natijasi qanday bo'ladi ?](#what-would-be-the-result-of-123)                                                                                          |
| 163 | [Debugger statement nima ?](#what-is-a-debugger-statement)                                                                                                    |
| 164 | [Nosozliklarni tuzatishda uzilish nuqtalarining maqsadi nima ?](#what-is-the-purpose-of-breakpoints-in-debugging)                                                              |
| 165 | [Identifikator sifatida ajratilgan so'zlardan foydalansam bo'ladimi ?](#can-i-use-reserved-words-as-identifiers)                                                                              |
| 166 | [Mobil brauzerni qanday aniqlash mumkin ?](#how-do-you-detect-a-mobile-browser)                                                                                        |
| 167 | [Regexpsiz mobil brauzerni qanday aniqlash mumkin ?](#how-do-you-detect-a-mobile-browser-without-regexp)                                                          |
| 168 | [JS yordamida tasvir kengligi va balandligini qanday olish mumkin ?](#how-do-you-get-the-image-width-and-height-using-js)                                                        |
| 169 | [Synchronous HTTP request(ni) qanday qilasiz ?](#how-do-you-make-synchronous-http-request)                                                                            |
| 170 | [Asynchronous HTTP request(ni) qanday qilasiz ?](#how-do-you-make-asynchronous-http-request)                                                                          |
| 171 | [Javascriptda sanani boshqa vaqt mintaqasiga qanday o'zgartirasiz ?](#how-do-you-convert-date-to-another-timezone-in-javascript)                                          |
| 172 | [Window hajmini olish uchun qanday xususiyatlardan foydalaniladi ?](#what-are-the-properties-used-to-get-size-of-window)                                                        |
| 173 | [Javascriptda shartli operator nima ?](#what-is-a-conditional-operator-in-javascript)                                                                    |
| 174 | [Conditional operator(da) apply chaining(ni) qo'llay olasizmi ?](#Can-you-apply-chaining-on-conditional-operator)                                                                |
| 175 | [Sahifani yuklagandan so'ng Javascriptni bajarish usullari qanday ?](#what-are-the-ways-to-execute-javascript-after-page-load)                                              |
| 176 | [Proto and prototype o'rtasidagi farq nima ?](#what-is-the-difference-between-proto-and-prototype)                                                        |
| 177 | [Sizga nuqta-vergul kerak bo'lgan misol keltiring ?](#give-an-example-where-do-you-really-need-semicolon)                                                        |
| 178 | [Freeze method nima ?](#what-is-a-freeze-method)                                                                                                              |
| 179 | [Freeze method(dan) maqsad nima ?](#what-is-the-purpose-of-freeze-method)                                                                                    |
| 180 | [Nima uchun Freeze method foydalanishim kerak ?](#why-do-i-need-to-use-freeze-method)                                                                                        |
| 181 | [Brauzer tilini afzal ko'rishni qanday aniqlash mumkin ?](#how-do-you-detect-a-browser-language-preference)                                                              |
| 182 | [Qanday qilib Javascript yordamida string(ni) sarlavha holatiga aylantirish mumkin ?](#how-to-convert-string-to-title-case-with-javascript)                                                      |
| 183 | [Sahifada o'chirilgan Javascriptni qanday aniqlash mumkin ?](#how-do-you-detect-javascript-disabled-in-the-page)                                                          |
| 184 | [Javascript tomonidan qo'llab-quvvatlanadigan turli operatorlar nima ?](#what-are-various-operators-supported-by-javascript)                                                        |
| 185 | [Rest parameter nima ?](#what-is-a-rest-parameter)                                                                                                            |
| 186 | [Agar dam olish parametrini oxirgi argument sifatida ishlatmasangiz nima bo'ladi ?](#what-happens-if-you-do-not-use-rest-parameter-as-a-last-argument)                            |
| 187 | [Javascriptda qanday bitli operatorlar mavjud ?](#what-are-the-bitwise-operators-available-in-javascript)                                                |
| 188 | [Spread operator nima ?](#what-is-a-spread-operator)                                                                                                          |
| 189 | [Ob'ektning frozen yoki muzlatilmaganligini qanday aniqlash mumkin ?](#how-do-you-determine-whether-object-is-frozen-or-not)                                                    |
| 190 | [Bir xil yoki ob'ektdan foydalanmayotgan ikkita qiymatni qanday aniqlash mumkin ?](#how-do-you-determine-two-values-same-or-not-using-object)                                            |
| 191 | [Ob'ektni ishlatishdan maqsad - bu usul](#what-is-the-purpose-of-using-object-is-method)                                                                  |
| 192 | [Xususiyatlarni bir ob'ektdan ikkinchisiga qanday nusxalash mumkin ?](#how-do-you-copy-properties-from-one-object-to-other)                                                      |
| 193 | [Assign method qanday qo'llaniladi ?](#what-are-the-applications-of-assign-method)                                                                        |
| 194 | [Proxy object nima ?](#what-is-a-proxy-object)                                                                                                                |
| 195 | [Seal method(ning) maqsadi nima ?](#what-is-the-purpose-of-seal-method)                                                                                        |
| 196 | [Seal method qanday qo'llaniladi ?](#what-are-the-applications-of-seal-method)                                                                            |
| 197 | [Freeze va seal method(lari) o'rtasidagi farqlar qanday ?](#what-are-the-differences-between-freeze-and-seal-methods)                                            |
| 198 | [Ob'ektning muhrlangan yoki yo'qligini qanday aniqlash mumkin ?](#how-do-you-determine-if-an-object-is-sealed-or-not)                                                        |
| 199 | [Qanday qilib sanab o'tiladigan key va value juftlarini olasiz ?](#how-do-you-get-enumerable-key-and-value-pairs)                                                                  |
| 200 | [Object.values ​​va Object.entries usuli o'rtasidagi asosiy farq nima ?](#what-is-the-main-difference-between-objectvalues-and-objectentries-method)        |

1. ### What are the possible ways to create objects in JavaScript

   Quyidagi kabi JavaScriptda ob'ektlar yaratishning ko'plab usullari mavjud

   1. **Ob'ekt konstruktori:**

      Bo'sh ob'ektni yaratishning eng oddiy usuli Ob'ekt konstruktoridan foydalanishdir. Hozirgi vaqtda bunday yondashuv tavsiya etilmaydi.

      ```javascript
      var object = new Object();
      ```

   2. **Ob'ektni yaratish usuli:**

      Object ning yaratish usuli prototip ob'ektini parametr sifatida o'tkazish orqali yangi ob'ektni yaratadi

      ```javascript
      var object = Object.create(null);
      ```

   3. **Obyekt literal sintaksisi:**

      Ob'ektning so'zma-so'z sintaksisi (yoki ob'ektni ishga tushiruvchisi) jingalak qavslarga o'ralgan nom-qiymat juftlarining vergul bilan ajratilgan to'plamidir.

      ```javascript
      var object = {
           name: "Sudheer",
           age: 34
      };

      Ob'ektning so'zma-so'z xossalari qiymatlari har qanday ma'lumotlar turiga, jumladan massiv, funksiya va ichki o'rnatilgan ob'ektga ega bo'lishi mumkin.
      ```

      **Eslatma:** Bu ob'ektni yaratishning eng oson usuli

   4. **Function constructor:**

      Har qanday funktsiyani yarating va ob'ekt misollarini yaratish uchun yangi operatorni qo'llang,

      ```javascript
      function Person(name) {
        this.name = name;
        this.age = 21;
      }
      var object = new Person("Sudheer");
      ```

   5. **Function constructor with prototype:**

      Bu funktsiya konstruktoriga o'xshaydi, lekin u xususiyatlari va usullari uchun prototipdan foydalanadi,

      ```javascript
      function Person() {}
      Person.prototype.name = "Sudheer";
      var object = new Person();
      ```

      Bu funksiya prototipi bilan ob'ekt yaratish usuli bilan yaratilgan misolga teng va keyin ushbu funktsiyani misol va parametrlar bilan argument sifatida chaqirish.

      ```javascript
      function func() {}

      new func(x, y, z);
      ```

      **(OR)**

      ```javascript
      // Funktsiya prototipidan foydalanib yangi namuna yarating.
      var newInstance = Object.create(func.prototype)

      // Funktsiyani chaqiring
      var result = func.call(newInstance, x, y, z),

      // Agar natija null bo'lmagan ob'ekt bo'lsa, uni ishlating, aks holda faqat yangi misoldan foydalaning.
      console.log(result && typeof result === 'object' ? result : newInstance);
      ```

   6. **ES6 Class syntax:**

      ES6 ob'ektlarni yaratish uchun sinf xususiyatini taqdim etadi

      ```javascript
      class Person {
        constructor(name) {
          this.name = name;
        }
      }

      var object = new Person("Sudheer");
      ```

   7. **Singleton pattern:**

      Singleton - bu faqat bir marta yaratilishi mumkin bo'lgan ob'ekt. Uning konstruktoriga takroriy qo'ng'iroqlar bir xil misolni qaytaradi va shu bilan ular tasodifan bir nechta misollarni yaratmasligiga ishonch hosil qilish mumkin.

      ```javascript
      var object = new (function () {
        this.name = "Sudheer";
      })();
      ```

      **[⬆ Yuqoriga qaytish](#mundarija)**

2. ### What is a prototype chain

   **Prototype chaining** mavjudlari asosida yangi turdagi ob'ektlarni qurish uchun foydalaniladi. Bu sinfga asoslangan tilda merosga o'xshaydi.

   Ob'ekt namunasidagi prototip **Object.getPrototypeOf(object)** yoki \***\*proto\*\*** xususiyati orqali, konstruktorlar funksiyasidagi prototip esa **Object.prototype** orqali mavjud.

   ![Screenshot](images/prototype_chain.png)

   **[⬆ Yuqoriga qaytish](#mundarija)**

3. ### What is the difference between Call, Apply and Bind

   Call qilish, Apply va Bind o'rtasidagi farqni quyidagi misollar bilan tushuntirish mumkin,

   **Call:** Call() usuli berilgan qiymatga ega funktsiyani va birma-bir taqdim etilgan argumentlarni chaqiradi.

   ```javascript
   var employee1 = { firstName: "John", lastName: "Rodson" };
   var employee2 = { firstName: "Jimmy", lastName: "Baily" };

   function invite(greeting1, greeting2) {
     console.log(
       greeting1 + " " + this.firstName + " " + this.lastName + ", " + greeting2
     );
   }

   invite.call(employee1, "Hello", "How are you?"); // Hello John Rodson, How are you?
   invite.call(employee2, "Hello", "How are you?"); // Hello Jimmy Baily, How are you?
   ```

   **Apply:** Berilgan qiymat bilan funktsiyani chaqiradi va argumentlarni massiv sifatida o'tkazishga imkon beradi.

   ```javascript
   var employee1 = { firstName: "John", lastName: "Rodson" };
   var employee2 = { firstName: "Jimmy", lastName: "Baily" };

   function invite(greeting1, greeting2) {
     console.log(
       greeting1 + " " + this.firstName + " " + this.lastName + ", " + greeting2
     );
   }

   invite.apply(employee1, ["Hello", "How are you?"]); // Hello John Rodson, How are you?
   invite.apply(employee2, ["Hello", "How are you?"]); // Hello Jimmy Baily, How are you?
   ```

   **bind:** har qanday miqdordagi argumentlarni o'tkazish imkonini beruvchi yangi funktsiyani qaytaradi

   ```javascript
   var employee1 = { firstName: "John", lastName: "Rodson" };
   var employee2 = { firstName: "Jimmy", lastName: "Baily" };

   function invite(greeting1, greeting2) {
     console.log(
       greeting1 + " " + this.firstName + " " + this.lastName + ", " + greeting2
     );
   }

   var inviteEmployee1 = invite.bind(employee1);
   var inviteEmployee2 = invite.bind(employee2);
   inviteEmployee1("Hello", "How are you?"); // Hello John Rodson, How are you?
   inviteEmployee2("Hello", "How are you?"); // Hello Jimmy Baily, How are you?
   ```

   Call qilish va apply berish bir-birini almashtirib turadi. Ikkalasi ham joriy funksiyani darhol bajaradi. Argumentlarni massiv yoki vergul bilan ajratilgan roʻyxatida yuborish osonroqmi, qaror qabul qilishingiz kerak. Call **vergul** uchun (ajratilgan ro'yxat) va **Massiv** uchun Apply ni davolash orqali eslashingiz mumkin.

   Holbuki, Bind yangi funksiyani yaratadi, unda bu birinchi parametr bind() ga o'tkaziladi.

   **[⬆ Yuqoriga qaytish](#mundarija)**

4. ### What is JSON and its common operations

   **JSON** bu `Douglas Crockford` tomonidan ommalashtirilgan JavaScript ob'ekt sintaksisiga asoslangan matnga asoslangan ma'lumotlar formatidir.

   **Parsing:** Satrni mahalliy ob'ektga aylantirish

   ```javascript
   JSON.parse(text);
   ```

   **Stringification:** mahalliy ob'ektni tarmoq bo'ylab uzatilishi uchun satrga aylantirish

   ```javascript
   JSON.stringify(object);
   ```

   **[⬆ Yuqoriga qaytish](#mundarija)**

5. ### What is the purpose of the array slice method

   **slice()** usuli massivdagi tanlangan elementlarni yangi massiv obyekti sifatida qaytaradi. U berilgan boshlang'ich argumentdan boshlanadigan elementlarni tanlaydi va oxirgi elementni qo'shmasdan berilgan ixtiyoriy yakuniy argumentda tugaydi. Agar siz ikkinchi argumentni o'tkazib yuborsangiz, u oxirigacha tanlaydi.

   Ushbu usulning ba'zi misollari:

   ```javascript
   let arrayIntegers = [1, 2, 3, 4, 5];
   let arrayIntegers1 = arrayIntegers.slice(0, 2); // returns [1,2]
   let arrayIntegers2 = arrayIntegers.slice(2, 3); // returns [3]
   let arrayIntegers3 = arrayIntegers.slice(4); //returns [5]
   ```

   **Eslatma:** Slice usuli asl massivni o'zgartirmaydi, lekin u kichik to'plamni yangi massiv sifatida qaytaradi.

   **[⬆ Yuqoriga qaytish](#mundarija)**

6. ### What is the purpose of the array splice method

   **Splice()** usuli qatorga elementlarni qo'shish/o'chirish uchun ishlatiladi va keyin olib tashlangan elementni qaytaradi. Birinchi argument qo'shish yoki o'chirish uchun massiv o'rnini belgilaydi, ixtiyoriy ikkinchi argument esa o'chirilishi kerak bo'lgan elementlar sonini ko'rsatadi. Har bir qo'shimcha argument massivga qo'shiladi.

   Ushbu usulning ba'zi misollari:

   ```javascript
   let arrayIntegersOriginal1 = [1, 2, 3, 4, 5];
   let arrayIntegersOriginal2 = [1, 2, 3, 4, 5];
   let arrayIntegersOriginal3 = [1, 2, 3, 4, 5];

   let arrayIntegers1 = arrayIntegersOriginal1.splice(0, 2); // returns [1, 2]; original array: [3, 4, 5]
   let arrayIntegers2 = arrayIntegersOriginal2.splice(3); // returns [4, 5]; original array: [1, 2, 3]
   let arrayIntegers3 = arrayIntegersOriginal3.splice(3, 1, "a", "b", "c"); //returns [4]; original array: [1, 2, 3, "a", "b", "c", 5]
   ```

   **Eslatma:** Splice usuli asl massivni o'zgartiradi va o'chirilgan massivni qaytaradi.

   **[⬆ Yuqoriga qaytish](#mundarija)**

7. ### What is the difference between slice and splice

   Jadval shaklidagi asosiy farqlardan ba'zilari

   | Slice                                              | Splice                                                                      |
   | -------------------------------------------------- | --------------------------------------------------------------------------- |
   | Asl massivni o'zgartirmaydi (o'zgarmas)            | Asl massivni o'zgartiradi (o'zgaruvchan)                                    |
   | Asl massivning pastki to'plamini qaytaradi         | O'chirilgan elementlarni massiv sifatida qaytaradi                          |
   | Massivdan elementlarni tanlash uchun foydalaniladi | Massivga/massivdan elementlarni kiritish yoki oʻchirish uchun foydalaniladi |

   **[⬆ Yuqoriga qaytish](#mundarija)**

8. ### How do you compare Object and Map

   **Ob'ektlar** **Map(ga)** o'xshaydi, chunki ikkalasi ham key(larni) qiymatlarga o'rnatish, ushbu qiymatlarni olish, key(larni) o'chirish va key(da) biror narsa saqlanganligini aniqlash imkonini beradi. Shu sababli, ob'ektlar tarixan Map(lar) sifatida ishlatilgan. Lekin muhim farqlar borki, ular ma'lum holatlarda Map(dan) foydalanishni afzal ko'radi.

   1. Ob'ektning key(lari) Strings va Symbols bo'lib, ular Map uchun har qanday qiymat, jumladan funktsiyalar, ob'ekt(lar) va har qanday primitive bo'lishi mumkin.
   2. Map(dagi) key(lar) tartiblangan, Ob'ektga qo'shilgan key(lar) esa yo'q. Shunday qilib, uni takrorlashda Map ob'ekti kalitlarni kiritish tartibida qaytaradi.
   3. Siz Map hajmini siz o'lcham xususiyati bilan osongina olishingiz mumkin, shu bilan birga Ob'ektdagi xususiyatlar soni qo'lda aniqlanishi kerak.
   4. Map takrorlanadigan va shuning uchun to'g'ridan-to'g'ri takrorlanishi mumkin, holbuki Ob'ektni takrorlash uchun uning key(larini) qandaydir tarzda olish va ularni takrorlash kerak.
   5. Ob'ektning prototipi bor, shuning uchun map(da) ehtiyot bo'lmasangiz, key(laringiz) bilan to'qnashishi mumkin bo'lgan standart key(lar) mavjud. ES5 dan boshlab map = Object.create(null) yordamida buni chetlab o'tish mumkin, lekin bu kamdan-kam hollarda amalga oshiriladi.
   6. Map key juftlarini tez-tez qo'shish va olib tashlashni o'z ichiga olgan scenarios yaxshiroq ishlashi mumkin.

   **[⬆ Yuqoriga qaytish](#mundarija)**

9. ### What is the difference between == and === operators

   JavaScript qat'iy (===, !==) va turga aylantiruvchi (==, !=) tenglikni taqqoslashni ta'minlaydi. Qattiq operatorlar o'zgaruvchining turini hisobga oladi, qat'iy bo'lmagan operatorlar esa o'zgaruvchilar qiymatlari asosida turni to'g'irlash/konvertatsiya qilishni amalga oshiradilar. Qattiq operatorlar har xil turlar uchun quyidagi shartlarga amal qiladilar,

   1. Ikki satr bir xil belgilar ketma-ketligi, bir xil uzunlik va tegishli pozitsiyalarda bir xil belgilarga ega bo'lsa, qat'iy tengdir.
   2. Ikki raqam son jihatdan teng bo'lsa, ular qat'iy tengdir. ya'ni bir xil raqam qiymatiga ega. Bunda ikkita alohida holat mavjud,
      1. NaN hech narsaga teng emas, shu jumladan NaN.
      2. Ijobiy va manfiy nollar bir-biriga teng.
   3. Ikki mantiqiy operand, agar ikkalasi ham to'g'ri yoki ikkalasi ham yolg'on bo'lsa, mutlaqo tengdir.
   4. Ikki ob'ekt bir xil ob'ektga tegishli bo'lsa, ular mutlaqo tengdir.
   5. Null va Undefined turlari === bilan teng emas, lekin == bilan teng. ya'ni, null===aniqlanmagan --> noto'g'ri, lekin null==aniqlanmagan --> rost

   Yuqoridagi holatlarni qamrab oluvchi ba'zi misollar,

   ```javascript
   0 == false   // true
   0 === false  // false
   1 == "1"     // true
   1 === "1"    // false
   null == undefined // true
   null === undefined // false
   '0' == false // true
   '0' === false // false
   []==[] or []===[] //false, refer different objects in memory
   {}=={} or {}==={} //false, refer different objects in memory
   ```

   **[⬆ Yuqoriga qaytish](#mundarija)**

10. ### What are lambda or arrow functions

    Arrow funtion funksiya ifodasi uchun qisqaroq sintaksis boʻlib, oʻziga xos **this, arguments, super yoki new.target** funksiyalariga ega emas.

    **[⬆ Yuqoriga qaytish](#mundarija)**

11. ### What is a first class function

    Javascriptda funksiyalar birinchi darajali ob'ektlardir. Birinchi darajali funktsiyalar bu tildagi funktsiyalar boshqa har qanday o'zgaruvchilar kabi ko'rib chiqilishini anglatadi.

    Masalan, bunday tilda funksiya boshqa funksiyalarga argument sifatida berilishi, boshqa funksiya tomonidan qaytarilishi va o‘zgaruvchiga qiymat sifatida berilishi mumkin. Misol uchun, quyidagi misolda tinglovchiga tayinlangan ishlov beruvchi funksiyalari

    ```javascript
    const handler = () => console.log("This is a click handler function");
    document.addEventListener("click", handler);
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

12. ### What is a first order function

    Birinchi darajali funksiya boshqa funksiyani argument sifatida qabul qilmaydigan va funksiyani qaytarish qiymati sifatida qaytarmaydigan funksiyadir.

    ```javascript
    const firstOrder = () => console.log("I am a first order function!");
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

13. ### What is a higher order function

    Yuqori tartibli funksiya boshqa funksiyani argument sifatida qabul qiladigan yoki funksiyani qaytarish qiymati yoki ikkalasini qaytaradigan funksiyadir.

    ```javascript
    const firstOrderFunc = () =>
      console.log("Hello, I am a First order function");
    const higherOrder = (ReturnFirstOrderFunc) => ReturnFirstOrderFunc();
    higherOrder(firstOrderFunc);
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

14. ### What is a unary function

    Unary function (ya'ni, monadic) - aynan bitta argumentni qabul qiladigan funksiya. Bu funksiya tomonidan qabul qilingan bitta argumentni anglatadi.

    Unary function(ga) misol keltiraylik,

    ```javascript
    const unaryFunction = (a) => console.log(a + 10); // Add 10 to the given argument and display the value
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

15. ### What is the currying function

    Currying - bu bir nechta argumentli funksiyani olish va uni har birida faqat bitta argumentga ega bo'lgan funksiyalar ketma-ketligiga aylantirish jarayoni. Currying matematik **Xaskell Karri** sharafiga nomlangan. Karringni qo'llash orqali n-ary funksiya uni birlik funksiyaga aylantiradi.

    Keling, n-ary funksiyasiga misol keltiraylik va u qanday qilib currying function(ga) aylanadi,

    ```javascript
    const multiArgFunction = (a, b, c) => a + b + c;
    console.log(multiArgFunction(1, 2, 3)); // 6

    const curryUnaryFunction = (a) => (b) => (c) => a + b + c;
    curryUnaryFunction(1); // returns a function: b => c =>  1 + b + c
    curryUnaryFunction(1)(2); // returns a function: c => 3 + c
    curryUnaryFunction(1)(2)(3); // returns the number 6
    ```

    Currying funtion(lari) **kodning qayta ishlatilishi** va **funktsional tarkibini** yaxshilash uchun juda yaxshi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

16. ### What is a pure function

    **Pure funtion** - bu qaytariladigan qiymat faqat uning argumentlari bilan hech qanday nojo'ya ta'sirlarsiz aniqlanadigan funksiyadir. Ya'ni, agar siz bir xil argumentlarga ega bo'lgan funksiyani "n" soni va ilovadagi joylar soni "n" bilan chaqirsangiz, u har doim bir xil qiymatni qaytaradi.

    Keling, pure va impure function(lar) o'rtasidagi farqni ko'rish uchun misol keltiraylik,

    ```javascript
    //Impure
    let numberArray = [];
    const impureAddNumber = (number) => numberArray.push(number);
    //Pure
    const pureAddNumber = (number) => (argNumberArray) =>
      argNumberArray.concat([number]);

    //Display the results
    console.log(impureAddNumber(6)); // returns 1
    console.log(numberArray); // returns [6]
    console.log(pureAddNumber(7)(numberArray)); // returns [6, 7]
    console.log(numberArray); // returns [6]
    ```

    Yuqoridagi kod parchalariga ko'ra, **Push** funksiyasi massivni o'zgartirish va parametr qiymatidan mustaqil ravishda surish raqami indeksini qaytarish orqali o'zini impure. Boshqa tomondan, **Concat** massivni oladi va uni boshqa massiv bilan birlashtiradi va nojo'ya ta'sirlarsiz butunlay yangi massiv hosil qiladi. Bundan tashqari, qaytarish qiymati oldingi massivning birlashmasi hisoblanadi.

    Esingizda bo'lsin, Pure funtion(lari) muhim ahamiyatga ega, chunki ular side effects(ni) hech qanday nojo'ya ta'sirlarsiz va dependency injection ehtiyoj sezmasdan soddalashtiradi. Ular, shuningdek, qattiq bog'lanishdan qochishadi va hech qanday nojo'ya ta'sirlarga ega bo'lmasdan, ilovangizni buzishni qiyinlashtiradi. Ushbu tamoyillar ES6 ning **Immutability** kontseptsiyasi bilan birlashtirilib, **let(dan)** ko'ra **const** ga ustunlik beradi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

17. ### What is the purpose of the let keyword

    `let` statement **block scope local variable**(ni) e'lon qiladi. Shunday qilib, let keyword bilan aniqlangan o'zgaruvchilar u ishlatiladigan block scope yoki ifoda bilan cheklangan. Holbuki, `var` keyword bilan e'lon qilingan o'zgaruvchilar o'zgaruvchini global miqyosda yoki blok doirasidan qat'i nazar, butun funktsiyaga lokal ravishda aniqlash uchun ishlatiladi.

    Foydalanishni ko'rsatish uchun misol keltiraylik,

    ```javascript
    let counter = 30;
    if (counter === 30) {
      let counter = 31;
      console.log(counter); // 31
    }
    console.log(counter); // 30 (because the variable in if block won't exist here)
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

18. ### What is the difference between let and var

    Siz farqlarni jadval shaklida ko'rishingiz mumkin

    | var                               | let                                        |
    | --------------------------------- | ------------------------------------------ |
    | U JavaScript boshidan beri mavjud | ES6 ning bir qismi sifatida taqdim etilgan |
    | U function scope                  | U block scope                              |
    | O'zgaruvchilar hoisting bo'ladi   | Hoisted lekin ishga tushirilmagan          |

    Farqni ko'rish uchun misol keltiraylik,

    ```javascript
    function userDetails(username) {
      if (username) {
        console.log(salary); // undefined due to hoisting
        console.log(age); // ReferenceError: Cannot access 'age' before initialization
        let age = 30;
        var salary = 10000;
      }
      console.log(salary); //10000 (accessible to due function scope)
      console.log(age); //error: age is not defined(due to block scope)
    }
    userDetails("John");
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

19. ### What is the reason to choose the name let as a keyword

    `let` - bu **Scheme** va **Basic** kabi dastlabki dasturlash tillari tomonidan qabul qilingan matematik bayonot. U imkon qadar `var` ga yaqin anʼanaviy keyword soʻz sifatida `let` soʻzini ishlatadigan oʻnlab boshqa tillardan olingan.

    **[⬆ Yuqoriga qaytish](#mundarija)**

20. ### How do you redeclare variables in switch block without an error

    Agar siz `switch block` o'zgaruvchilarni qayta e'lon qilishga harakat qilsangiz, u xatolarga olib keladi, chunki faqat bitta block mavjud. Masalan, quyidagi code block quyidagi kabi sintaksis xatosini keltirib chiqaradi,

    ```javascript
    let counter = 1;
    switch (x) {
      case 0:
        let name;
        break;

      case 1:
        let name; // SyntaxError for redeclaration.
        break;
    }
    ```

    Ushbu xatolikka yo'l qo'ymaslik uchun siz case bandi ichida ichki blok yaratishingiz va yangi blokli leksik muhitni yaratishingiz mumkin.

    ```javascript
    let counter = 1;
    switch (x) {
      case 0: {
        let name;
        break;
      }
      case 1: {
        let name; // No SyntaxError for redeclaration.
        break;
      }
    }
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

21. ### What is the Temporal Dead Zone

    Temporal Dead Zone - bu JavaScript-da o'zgaruvchini let va const keyword so'zlari bilan e'lon qilishda yuzaga keladigan xatti-harakatlar, lekin var bilan emas. ECMAScript 6 da `let` yoki `const` o'zgaruvchisiga uning e'lon qilinishidan oldin (uning doirasi doirasida) kirish ReferenceError(ga) sabab bo'ladi. Bu sodir bo'ladigan vaqt oralig'i, o'zgaruvchining bog'lanishi yaratilishi va uning e'lon qilinishi o'rtasidagi vaqt oralig'i vaqtinchalik temporal dead zone deb ataladi.

    Keling, bu xatti-harakatni misol bilan ko'rib chiqaylik,

    ```javascript
    function somemethod() {
      console.log(counter1); // undefined
      console.log(counter2); // ReferenceError
      var counter1 = 1;
      let counter2 = 2;
    }
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

22. ### What is IIFE(Immediately Invoked Function Expression)

    IIFE (Immediately Invoked Function Expression) bu JavaScript funksiyasi boʻlib, u aniqlangan zahoti ishga tushadi. Uning imzosi quyidagicha bo'ladi,

    ```javascript
    (function () {
      // logic here
    })();
    ```

    IFE-dan foydalanishning asosiy sababi ma'lumotlarning maxfiyligini olishdir, chunki IIFE ichida e'lon qilingan har qanday o'zgaruvchilarga tashqi dunyo kirishi mumkin emas. ya'ni, agar siz IIFE bilan o'zgaruvchilarga kirishga harakat qilsangiz, u quyidagi kabi xatoga yo'l qo'yadi,

    ```javascript
    (function () {
      var message = "IIFE";
      console.log(message);
    })();
    console.log(message); //Error: message is not defined
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

23. ### How do you decode or encode a URL in JavaScript?

    `encodeURI()` funksiyasi URL manzilini kodlash uchun ishlatiladi. Bu funksiya parametr sifatida URL satrini talab qiladi va kodlangan qatorni qaytaradi.
    `decodeURI()` funksiyasi URL manzilini decode(lash) uchun ishlatiladi. Bu funksiya parametr sifatida kodlangan URL satrini talab qiladi va bu decode(langan) qatorni qaytaradi.

    **Eslatma:** Agar siz / kabi belgilarni kodlashni xohlasangiz `/ ? : @ & = + $ #` keyin `encodeURIComponent()` dan foydalanishingiz kerak.

    ```javascript
    let uri = "employeeDetails?name=john&occupation=manager";
    let encoded_uri = encodeURI(uri);
    let decoded_uri = decodeURI(encoded_uri);
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

24. ### What is memoization

    Memoization - bu oldindan hisoblangan natijalarni keshlash orqali funksiyaning ishlashini oshirishga harakat qiladigan dasturlash usuli. Har safar xotirada saqlangan funksiya chaqirilganda, uning parametrlari keshni indekslash uchun ishlatiladi. Agar ma'lumotlar mavjud bo'lsa, uni butun funksiyani bajarmasdan qaytarish mumkin.Aks holda funksiya bajariladi va natija keshga qo'shiladi. Keling, xotira bilan funksiya qo'shishga misol keltiraylik,

    ```javascript
    const memoizAddition = () => {
      let cache = {};
      return (value) => {
        if (value in cache) {
          console.log("Fetching from cache");
          return cache[value]; // Here, cache.value cannot be used as property name starts with the number which is not a valid JavaScript  identifier. Hence, can only be accessed using the square bracket notation.
        } else {
          console.log("Calculating result");
          let result = value + 20;
          cache[value] = result;
          return result;
        }
      };
    };
    // returned function from memoizAddition
    const addition = memoizAddition();
    console.log(addition(20)); //output: 40 calculated
    console.log(addition(20)); //output: 40 cached
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

25. ### What is Hoisting

    Hoisting JavaScript mexanizmi bo'lib, unda code bajarilishidan oldin o'zgaruvchilar, funksiya deklaratsiyasi va sinflar o'z doirasining yuqori qismiga ko'chiriladi. Esda tutingki, JavaScript faqat deklaratsiyalarni hoisting, ishga tushirishni emas. Keling, o'zgaruvchan yuk ko'tarishning oddiy misolini olaylik,

    ```javascript
    console.log(message); //output : undefined
    var message = "The variable Has been hoisted";
    ```

    Yuqoridagi code tarjimon uchun quyidagi kabi ko'rinadi,

    ```javascript
    var message;
    console.log(message);
    message = "The variable Has been hoisted";
    ```

    Xuddi shu tarzda, funksiya deklaratsiyasi ham hoisting bo'ladi.

    ```javascript
    message("Good morning"); //Good morning

    function message(name) {
      console.log(name);
    }
    ```

    Ushbu hoisting funksiyalarni e'lon qilinishidan oldin code(da) xavfsiz ishlatishga imkon beradi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

26. ### What are classes in ES6

    ES6-da Javascript clas(lar) asosan JavaScript-ning mavjud prototipiga asoslangan merosiga nisbatan syntactic sugar hisoblanadi.
    Masalan, prototipga asoslangan meros quyidagi funksiya ifodasida yozilgan,

    ```javascript
    function Bike(model, color) {
      this.model = model;
      this.color = color;
    }

    Bike.prototype.getDetails = function () {
      return this.model + " bike has" + this.color + " color";
    };
    ```

    ES6 classes esa muqobil sifatida belgilanishi mumkin

    ```javascript
    class Bike {
      constructor(color, model) {
        this.color = color;
        this.model = model;
      }

      getDetails() {
        return this.model + " bike has" + this.color + " color";
      }
    }
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

27. ### What are closures

    Closure - bu funksiya va ushbu funksiya e'lon qilingan leksik muhitning kombinatsiyasi. ya'ni, bu tashqi yoki qo'shuvchi funksiya o'zgaruvchilariga kirish huquqiga ega bo'lgan ichki funksiya. Yopish uchta ko'lamli zanjirga ega

    1. O'zgaruvchilar uning own scope orasida aniqlangan o'z doirasi
    2. Tashqi funksiya o'zgaruvchilari
    3. Global o'zgaruvchilar

    Keling, yopish kontseptsiyasiga misol keltiraylik,

    ```javascript
    function Welcome(name) {
      var greetingInfo = function (message) {
        console.log(message + " " + name);
      };
      return greetingInfo;
    }
    var myFunction = Welcome("John");
    myFunction("Welcome "); //Output: Welcome John
    myFunction("Hello Mr."); //output: Hello Mr.John
    ```

    Yuqoridagi kodga ko'ra, ichki funksiya (ya'ni, greetingInfo) tashqi funksiya qaytganidan keyin ham tashqi funksiya doirasidagi (ya'ni Welcome) o'zgaruvchilarga kirish huquqiga ega.

    **[⬆ Yuqoriga qaytish](#mundarija)**

28. ### What are modules

    Modullar mustaqil, qayta foydalanish mumkin bo'lgan kodning kichik birliklariga ishora qiladi va ko'plab JavaScript dizayn patterns asosi bo'lib xizmat qiladi. JavaScript modullarining aksariyati ob'ektni, funksiyani yoki konstruktorni eksport qiladi

    **[⬆ Yuqoriga qaytish](#mundarija)**

29. ### Why do you need modules

    Quyida JavaScript ekotizimidagi modullardan foydalanishning afzalliklari ro'yxati keltirilgan

    1. Maintainability
    2. Reusability
    3. Namespacing

    **[⬆ Yuqoriga qaytish](#mundarija)**

30. ### What is scope in javascript

    Qo'llash doirasi - bu ish vaqtida kodingizning ma'lum bir qismidagi o'zgaruvchilar, funksiyalar va ob'ektlarga kirish imkoniyati. Boshqacha qilib aytganda, qamrov sizning kodingiz sohalarida o'zgaruvchilar va boshqa resurslarning ko'rinishini aniqlaydi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

31. ### What is a service worker

    Xizmat xodimi asosan fonda ishlaydigan script (JavaScript fayli), veb-sahifadan ajratilgan va veb-sahifa yoki foydalanuvchining oʻzaro taʼsirini talab qilmaydigan xususiyatlarni taqdim etadi. Xizmat xodimlarining asosiy xususiyatlaridan ba'zilari - bu boy offline tajribalar (offline birinchi veb-ilovalarni ishlab chiqish), davriy fon sinxronizatsiyasi, push-bildirishnomalar, tarmoq so'rovlarini ushlab turish va boshqarish va javoblar keshini dasturiy ravishda boshqarish.

    **[⬆ Yuqoriga qaytish](#mundarija)**

32. ### How do you manipulate DOM using a service worker

    Xizmat xodimi DOMga bevosita kira olmaydi. Lekin u `postMessage` interfeysi orqali yuborilgan xabarlarga javob berish orqali o‘zi boshqaradigan sahifalar bilan bog‘lana oladi va bu sahifalar DOMni boshqarishi mumkin.

    **[⬆ Yuqoriga qaytish](#mundarija)**

33. ### How do you reuse information across service worker restarts

    Service worker bilan bog'liq muammo shundaki, u foydalanilmaganda tugatiladi va keyingi kerak bo'lganda qayta ishga tushadi, shuning uchun siz xizmat ko'rsatuvchi xodimning `onfetch` va `onmessage` ishlov beruvchilarida global holatga tayanolmaysiz. Bunday holda, xizmat ko'rsatuvchi xodimlar qayta ishga tushirishda davom etish va qayta foydalanish uchun IndexedDB API ga kirish huquqiga ega bo'ladi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

34. ### What is IndexedDB

    IndexedDB - bu mijoz tomonidan katta hajmdagi tuzilgan ma'lumotlarni, shu jumladan fayllar/bloblarni saqlash uchun past darajadagi API. Ushbu API ushbu ma'lumotlarning yuqori samarali qidiruvlarini yoqish uchun indekslardan foydalanadi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

35. ### What is web storage

    Web storage - bu brauzerlar key/value juftlarini foydalanuvchi brauzerida locally sifatida cookie-fayllardan foydalanishdan ko'ra ancha intuitiv tarzda saqlashi mumkin bo'lgan mexanizmni ta'minlovchi API. Web storage mijozga ma'lumotlarni saqlash uchun ikkita mexanizmni taqdim etadi.

    1. **Local storage:** U amaldagi ma'lumotlarni amal qilish muddatisiz saqlaydi.
    2. **Session storage:** U bir seans uchun ma'lumotlarni saqlaydi va brauzer yorlig'i yopilganda ma'lumotlar yo'qoladi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

36. ### What is a post message

    Post xabari Oyna ob'ektlari (ya'ni, sahifa va u ochilgan qalqib chiquvchi oyna o'rtasida yoki sahifa va uning ichiga o'rnatilgan iframe o'rtasida) o'zaro bog'lanish imkonini beruvchi usuldir. Odatda, turli sahifalardagi script(larga) bir-biriga kirishga ruxsat beriladi, agar sahifalar bir xil asl siyosatiga amal qilsa (ya'ni, sahifalar bir xil protokol, port raqami va xostga ega bo'lsa).

    **[⬆ Yuqoriga qaytish](#mundarija)**

37. ### What is a Cookie

    Cookie - bu brauzeringiz kirishi uchun kompyuteringizda saqlanadigan ma'lumotlarning bir qismi. Cookie-fayllar key/value juftlari sifatida saqlanadi. Masalan, foydalanuvchi nomi bilan quyidagi cookie faylini yaratishingiz mumkin:

    ```javascript
    document.cookie = "username=John";
    ```

    ![Screenshot](images/cookie.png)

    **[⬆ Yuqoriga qaytish](#mundarija)**

38. ### Why do you need a Cookie

    Cookie-fayllar foydalanuvchi profili (masalan, foydalanuvchi nomi) haqidagi ma'lumotlarni eslab qolish uchun ishlatiladi. Bu asosan ikki bosqichni o'z ichiga oladi,

    1. Foydalanuvchi web page tashrif buyurganida, foydalanuvchi profili cookie faylida saqlanishi mumkin.
    2. Keyingi safar foydalanuvchi sahifaga tashrif buyurganida, cookie foydalanuvchi profilini eslab qoladi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

39. ### What are the options in a cookie

    Cookie uchun quyida bir nechta variant mavjud,

    1. Odatiy bo'lib, brauzer yopilganda cookie o'chiriladi, ammo amal qilish muddatini belgilash orqali bu xatti-harakatni o'zgartirishingiz mumkin (UTC vaqti).

    ```javascript
    document.cookie = "username=John; expires=Sat, 8 Jun 2019 12:00:00 UTC";
    ```

    1. Odatiy bo'lib, cookie joriy sahifaga tegishli. Lekin siz brauzerga cookie fayli qaysi yoʻlga tegishli ekanligini yoʻl parametri yordamida ayta olasiz.

    ```javascript
    document.cookie = "username=John; path=/services";
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

40. ### How do you delete a cookie

    Yaroqlilik muddatini o'tgan sana sifatida belgilash orqali cookie faylini o'chirishingiz mumkin. Bu holda cookie qiymatini belgilashingiz shart emas. Masalan, joriy sahifadagi foydalanuvchi nomi cookie faylini quyidagi tarzda oʻchirishingiz mumkin.

    ```javascript
    document.cookie =
      "username=; expires=Fri, 07 Jun 2019 00:00:00 UTC; path=/;";
    ```

    **Eslatma:** To'g'ri cookie-faylni o'chirib tashlashingizga ishonch hosil qilish uchun cookie-fayl yo'li opsiyasini belgilashingiz kerak. Ba'zi brauzerlar, agar siz yo'l parametrini ko'rsatmasangiz, cookie-fayllarni o'chirishga ruxsat bermaydi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

41. ### What are the differences between cookie, local storage and session storage

    Quyida cookie, local storage va session storage o'rtasidagi farqlar keltirilgan.

    | Feature                                   | Cookie                                           | Local storage       | Session storage    |
    | ----------------------------------------- | ------------------------------------------------ | ------------------- | ------------------ |
    | Mijoz yoki server tomonidan kirish mumkin | Ham server tomoni, ham mijoz tomoni              | faqat mijoz tomoni  | faqat mijoz tomoni |
    | Hayot paytida                             | Muddati tugaydi opsiyasi yordamida sozlanganidek | o'chirilgunga qadar | tab yopilguncha    |
    | SSL qo'llab-quvvatlash                    | Qo'llab-quvvatlanadi                             | Not supported       | Not supported      |
    | Maximum data size                         | 4KB                                              | 5 MB                | 5MB                |

    **[⬆ Yuqoriga qaytish](#mundarija)**

42. ### What is the main difference between localStorage and sessionStorage

    LocalStorage SessionStorage bilan bir xil, lekin u brauzer yopilgan va qayta ochilganda ham maʼlumotlarni saqlab qoladi (yaʼni uning amal qilish muddati yoʻq), seansStorageʼda esa sahifa seansi tugashi bilan maʼlumotlar tozalanadi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

43. ### How do you access web storage

    Window obyekti mos ravishda `localStorage`(window.localStorage) va `sessionStorage`(window.sessionStorage) xossalariga ega `WindowLocalStorage` va `WindowSessionStorage` obyektlarini amalga oshiradi. Ushbu xususiyatlar Saqlash ob'ektining namunasini yaratadi, bu orqali ma'lum domen va saqlash turi (session yoki local) uchun ma'lumotlar elementlarini o'rnatish, olish va o'chirish mumkin.
    Masalan, local storage saqlash ob'ektlarida quyida keltirilgan tarzda o'qishingiz va yozishingiz mumkin

    ```javascript
    localStorage.setItem("logo", document.getElementById("logo").value);
    localStorage.getItem("logo");
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

44. ### What are the methods available on session storage

    session storage session ma'lumotlarini o'qish, yozish va tozalash usullarini taqdim etdi

    ```javascript
    // Save data to sessionStorage
    sessionStorage.setItem("key", "value");

    // Get saved data from sessionStorage
    let data = sessionStorage.getItem("key");

    // Remove saved data from sessionStorage
    sessionStorage.removeItem("key");

    // Remove all saved data from sessionStorage
    sessionStorage.clear();
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

45. ### What is a storage event and its event handler

    StorageEvent - bu boshqa hujjat kontekstida saqlash joyi o'zgartirilganda paydo bo'ladigan hodisa.
    Holbuki, saqlash xususiyati - bu saqlash hodisalarini qayta ishlash uchun EventHandler. Sintaksis quyidagi kabi bo'ladi

    ```javascript
    window.onstorage = functionRef;
    ```

    Keling, saqlash kaliti va uning qiymatlarini qayd qiluvchi xotira hodisasi ishlovchisidan foydalanish misolini olaylik

    ```javascript
    window.onstorage = function (e) {
      console.log(
        "The " +
          e.key +
          " key has been changed from " +
          e.oldValue +
          " to " +
          e.newValue +
          "."
      );
    };
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

46. ### Why do you need web storage

    Web storage yanada xavfsizroq va katta hajmdagi ma'lumotlar website ishlashiga ta'sir qilmasdan locally sifatida saqlanishi mumkin. Bundan tashqari, ma'lumotlar hech qachon serverga o'tkazilmaydi. Shuning uchun bu Cookie-fayllarga qaraganda ko'proq tavsiya etilgan yondashuv.

    **[⬆ Yuqoriga qaytish](#mundarija)**

47. ### How do you check web storage browser support

    Web storage foydalanishdan oldin brauzerning localStorage va sessionStorage uchun yordamini tekshirishingiz kerak,

    ```javascript
    if (typeof Storage !== "undefined") {
      // Code for localStorage/sessionStorage.
    } else {
      // Sorry! No Web Storage support..
    }
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

48. ### How do you check web workers browser support

    Uni ishlatishdan oldin web support uchun brauzer yordamini tekshirishingiz kerak

    ```javascript
    if (typeof Worker !== "undefined") {
      // code for Web worker support.
    } else {
      // Sorry! No Web Worker support..
    }
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

49. ### Give an example of a web worker

    Hisoblash misolida web ishchilaridan foydalanishni boshlash uchun quyidagi bosqichlarni bajarishingiz kerak

    1. Web worker faylini yarating: Hisoblash qiymatini oshirish uchun script yozishingiz kerak. Keling, uni counter.js deb nomlaymiz

    ```javascript
    let i = 0;

    function timedCount() {
      i = i + 1;
      postMessage(i);
      setTimeout("timedCount()", 500);
    }

    timedCount();
    ```

    Bu yerda postMessage() usuli xabarni HTML sahifasiga qaytarish uchun ishlatiladi

    1. Web worker ob'ektini yaratish: Brauzer qo'llab-quvvatlashini tekshirish orqali web worker ob'ektini yaratishingiz mumkin. Keling, bu faylni web_worker_example.js deb nomlaymiz

    ```javascript
    if (typeof w == "undefined") {
      w = new Worker("counter.js");
    }
    ```

    va biz web worker xabarlar olishimiz mumkin

    ```javascript
    w.onmessage = function (event) {
      document.getElementById("message").innerHTML = event.data;
    };
    ```

    1. Web worker tugatish: Web worker(lari) xabarlarni tinglashda davom etadilar (hatto tashqi skript tugagandan keyin ham) u tugatilmaguncha. Siz xabarlarni tinglashni tugatish uchun terminate() usulidan foydalanishingiz mumkin.

    ```javascript
    w.terminate();
    ```

    1. Web worker(ni) qayta ishlatish: Agar worker o'zgaruvchini aniqlanmagan deb o'rnatsangiz, code(ni) qayta ishlatishingiz mumkin

    ```javascript
    w = undefined;
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

50. ### What are the restrictions of web workers on DOM

    WebWorkers quyida joylashgan JavaScript obyektlariga kirish huquqiga ega emas, chunki ular tashqi fayllarda aniqlangan

    1. Window object
    2. Document object
    3. Parent object

    **[⬆ Yuqoriga qaytish](#mundarija)**

51. ### What is a promise

    Promise - bu hal qilingan qiymat yoki hal qilinmagan sabab (masalan, tarmoq xatosi) bilan kelajakda bir muncha vaqt bitta qiymat ishlab chiqarishi mumkin bo'lgan ob'ekt. U 3 ta mumkin bo'lgan holatdan birida bo'ladi: bajarilgan, rad etilgan yoki kutilayotgan.

    Promise yaratish sintaksisi quyidagi kabi ko'rinadi:

    ```javascript
    const promise = new Promise(function (resolve, reject) {
      // promise description
    });
    ```

    Va'dadan foydalanish quyidagicha bo'ladi,

    ```javascript
    const promise = new Promise(
      (resolve) => {
        setTimeout(() => {
          resolve("I'm a Promise!");
        }, 5000);
      },
      (reject) => {}
    );

    promise.then((value) => console.log(value));
    ```

    Promise(ning) harakat oqimi quyidagicha bo'ladi,

    ![Screenshot](images/promises.png)

    **[⬆ Yuqoriga qaytish](#mundarija)**

52. ### Why do you need a promise

    Promise(lar) asinxron operatsiyalarni bajarish uchun ishlatiladi. Ular callbacks uchun muqobil yondashuvni taqdim etadilar, bu esa qayta callback hell kamaytirish va toza kodni yozishdir.

    **[⬆ Yuqoriga qaytish](#mundarija)**

53. ### What are the three states of promise

    Promise(lar) uchta holatga ega:

    1. **Pending:** Bu operatsiya boshlanishidan oldingi promise(ning) dastlabki holati
    2. **Fulfilled:** Bu holat belgilangan operatsiya tugaganligini bildiradi.
    3. **Rejected:** Bu holat operatsiya tugallanmaganligini ko'rsatadi. Bunday holda xato qiymati chiqariladi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

54. ### What is a callback function

    Callback function qilish funksiyasi boshqa funksiyaga argument sifatida o'tkaziladigan funksiyadir. Bu funksiya amalni bajarish uchun tashqi funksiya ichida chaqiriladi. Callback funtion qilish funksiyasidan qanday foydalanishni oddiy misol qilib olaylik

    ```javascript
    function callbackFunction(name) {
      console.log("Hello " + name);
    }

    function outerFunction(callback) {
      let name = prompt("Please enter your name.");
      callback(name);
    }

    outerFunction(callbackFunction);
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

55. ### Why do we need callbacks

    Callback function(lar) kerak, chunki JavaScript voqealarga asoslangan tildir. Bu degani, javobni kutish o'rniga JavaScript boshqa voqealarni tinglashda ishlashda davom etadi.API chaqiruvini chaqiruvchi birinchi funksiya (setTimeout tomonidan taqlid qilingan) va xabarni qayd qiluvchi keyingi funksiyaga misol keltiraylik.

    ```javascript
    function firstFunction() {
      // Simulate a code delay
      setTimeout(function () {
        console.log("First function called");
      }, 1000);
    }
    function secondFunction() {
      console.log("Second function called");
    }
    firstFunction();
    secondFunction();

    Output;
    // Second function called
    // First function called
    ```

    Natijadan ko'rinib turibdiki, JavaScript birinchi funktsiyaning javobini kutmagan va qolgan code block bajarilgan. Shunday qilib, callback funtion(lar) ma'lum code boshqa code bajarilishini tugatmaguncha bajarilmasligiga ishonch hosil qilish uchun ishlatiladi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

56. ### What is a callback hell

    Callback Hell bir nechta ichki callback(larga) ega bo'lgan anti-pattern bo'lib, asynchronous mantiq bilan ishlashda code(ni) o'qish va debug dealing qilishni qiyinlashtiradi. callback hell quyida ko'rinadi,

    ```javascript
    async1(function(){
        async2(function(){
            async3(function(){
                async4(function(){
                    ....
                });
            });
        });
    });
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

57. ### What are server-sent events

    Server tomonidan yuborilgan event(lar) (SSE) - bu serverni push texnologiyasi bo'lib, brauzer so'rovga murojaat qilmasdan HTTP ulanishi orqali serverdan avtomatik yangilanishlarni olish imkonini beradi. Bular bir tomonlama aloqa channel(i) - event(lar) faqat serverdan mijozga o'tadi. Bu Facebook/Twitter yangilanishlarida, aksiyalar narxlari yangilanishlarida, yangiliklar tasmalarida va hokazolarda ishlatilgan.

    **[⬆ Yuqoriga qaytish](#mundarija)**

58. ### How do you receive server-sent event notifications

    EventSource obyekti server tomonidan yuborilgan event bildirishnomalarini olish uchun ishlatiladi. Masalan, siz serverdan quyidagi tarzda xabarlar olishingiz mumkin,

    ```javascript
    if (typeof EventSource !== "undefined") {
      var source = new EventSource("sse_generator.js");
      source.onmessage = function (event) {
        document.getElementById("output").innerHTML += event.data + "<br>";
      };
    }
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

59. ### How do you check browser support for server-sent events

    Quyidagi kabi ishlatishdan oldin server tomonidan yuborilgan voqealar uchun brauzerni qo'llab-quvvatlashingiz mumkin,

    ```javascript
    if (typeof EventSource !== "undefined") {
      // Server-sent events supported. Let's have some code here!
    } else {
      // No server-sent events supported
    }
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

60. ### What are the events available for server sent events

    Quyida server tomonidan yuborilgan voqealar uchun mavjud voqealar ro'yxati keltirilgan
    | Event | Description |
    |---- | ---------
    | onopen | U serverga ulanish ochilganda ishlatiladi |
    | onmessage | Ushbu hodisa xabar qabul qilinganda ishlatiladi |
    | onerror | Xatolik yuzaga kelganda sodir bo'ladi|

    **[⬆ Yuqoriga qaytish](#mundarija)**

61. ### What are the main rules of promise

    Promise muayyan qoidalar to'plamiga amal qilishi kerak,

    1. Promise - bu standartga mos keladigan `.then()` usulini ta'minlovchi ob'ekt
    2. Kutilayotgan promise bajarilgan yoki rad etilgan holatga o'tishi mumkin
    3. Bajarilgan yoki rad etilgan promise hal qilinadi va u boshqa hech qanday holatga o'tmasligi kerak.
    4. Promise bajarilgandan so'ng, qiymat o'zgarmasligi kerak.

    **[⬆ Yuqoriga qaytish](#mundarija)**

62. ### What is callback in callback

    Harakatlarni birma-bir bajarish uchun bitta qayta callback(ni) boshqa qayta callback(ga) joylashtirishingiz mumkin. Bu qayta callback(larda) qayta callback(lar) sifatida tanilgan.

    ```javascript
    loadScript("/script1.js", function (script) {
      console.log("first script is loaded");

      loadScript("/script2.js", function (script) {
        console.log("second script is loaded");

        loadScript("/script3.js", function (script) {
          console.log("third script is loaded");
          // after all scripts are loaded
        });
      });
    });
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

63. ### What is promise chaining

    Promise(lar) yordamida birin-ketin asinxron vazifalarni bajarish jarayoni promise zanjiri deb nomlanadi. Yakuniy natijani hisoblash uchun promise zanjiriga misol keltiraylik,

    ```javascript
    new Promise(function (resolve, reject) {
      setTimeout(() => resolve(1), 1000);
    })
      .then(function (result) {
        console.log(result); // 1
        return result * 2;
      })
      .then(function (result) {
        console.log(result); // 2
        return result * 3;
      })
      .then(function (result) {
        console.log(result); // 6
        return result * 4;
      });
    ```

    Yuqoridagi ishlov beruvchilarda natija quyidagi ish oqimi bilan .then() ishlov beruvchilari zanjiriga uzatiladi,

    1. Dastlabki promise 1 soniyada hal qilinadi,
    2. Shundan so'ng `.then` ishlovchi natijani (1) jurnalga kiritish orqali chaqiriladi va natijada \* 2 qiymati bilan promise qaytariladi.
    3. Shundan so'ng, qiymat keyingi `.then` ishlov beruvchiga natijani (2) yozib, natijani \* 3 bilan qaytaring.
    4. Nihoyat, qiymat oxirgi `.then` ishlov beruvchiga natijani (6) yozib, natijani \* 4 bilan qaytaring.

    **[⬆ Yuqoriga qaytish](#mundarija)**

64. ### What is promise.all

    Promise.all - bu bir qator promise(larni) kiritish (takrorlash) sifatida qabul qiladigan promise va u barcha promise(lar) hal qilinganda yoki ulardan biri rad etilganda hal qilinadi. Masalan, prod.all usulining sintaksisi quyida keltirilgan,

    ```javascript
    Promise.all([Promise1, Promise2, Promise3]) .then(result) => {   console.log(result) }) .catch(error => console.log(`Error in promises ${error}`))
    ```

    **Eslatma:** Esda tutingki, promise(lar) tartibi (natijani chiqarish) kiritish tartibiga muvofiq saqlanadi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

65. ### What is the purpose of the race method in promise

    Promise.race() usuli birinchi navbatda hal qilingan yoki rad etilgan promise namunasini qaytaradi. Keling, race() usulini misol qilib olaylik, bunda birinchi navbatda promise2 hal qilinadi

    ```javascript
    var promise1 = new Promise(function (resolve, reject) {
      setTimeout(resolve, 500, "one");
    });
    var promise2 = new Promise(function (resolve, reject) {
      setTimeout(resolve, 100, "two");
    });

    Promise.race([promise1, promise2]).then(function (value) {
      console.log(value); // "two" // Both promises will resolve, but promise2 is faster
    });
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

66. ### What is a strict mode in javascript

    Strict Mode - bu ECMAScript 5-dagi yangi xususiyat bo'lib, u sizga dastur yoki funksiyani "strict" operatsion kontekstda joylashtirish imkonini beradi. Shunday qilib, u muayyan harakatlarning bajarilishini oldini oladi va ko'proq istisnolarni keltirib chiqaradi. `"use strict"; ` so'zma-so'z ifodasi; brauzerga javascript code(ni) qattiq rejimda ishlatishni buyuradi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

67. ### Why do you need strict mode

    Strict Mode haqiqiy xatolarga "yomon sintaksis" haqida xabar berib, "xavfsiz" JavaScript yozish uchun foydalidir. Misol uchun, u xatoga yo'l qo'yish orqali tasodifiy global o'zgaruvchini yaratishni yo'q qiladi va shuningdek, yozilmaydigan xususiyatga tayinlash uchun xato qiladi, faqat qabul qiluvchi xususiyat, mavjud bo'lmagan xususiyat, mavjud bo'lmagan o'zgaruvchi yoki mavjud bo'lmagan ob'ekt.

    **[⬆ Yuqoriga qaytish](#mundarija)**

68. ### How do you declare strict mode

    Strict Mode "use strict" qo'shilishi bilan e'lon qilinadi; script yoki funksiyaning boshiga. Agar script boshida e'lon qilingan bo'lsa, u global scope ega.

    ```javascript
    "use strict";
    x = 3.14; // This will cause an error because x is not declared
    ```

    va agar siz funksiya ichida e'lon qilsangiz, u mahalliy doiraga ega

    ```javascript
    x = 3.14; // This will not cause an error.
    myFunction();

    function myFunction() {
      "use strict";
      y = 3.14; // This will cause an error
    }
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

69. ### What is the purpose of double exclamation

    Qo'sh undov yoki inkor (!!) natijada turning mantiqiy ekanligini ta'minlaydi. Agar u noto'g'ri bo'lsa (masalan, 0, null, undefined va hokazo), u noto'g'ri, aks holda rost bo'ladi.
    Misol uchun, siz quyidagi ibora yordamida IE versiyasini sinab ko'rishingiz mumkin,

    ```javascript
    let isIE8 = false;
    isIE8 = !!navigator.userAgent.match(/MSIE 8.0/);
    console.log(isIE8); // returns true or false
    ```

    Agar siz ushbu ifodani ishlatmasangiz, u asl qiymatni qaytaradi.

    ```javascript
    console.log(navigator.userAgent.match(/MSIE 8.0/)); // returns either an Array or null
    ```

    **Eslatma:** Ifodasi !! operator emas, lekin u faqat ikki marta ! operator.

    **[⬆ Yuqoriga qaytish](#mundarija)**

70. ### What is the purpose of the delete operator

    Delete keyword so'zi property va uning qiymatini o'chirish uchun ishlatiladi.

    ```javascript
    var user = { name: "John", age: 20 };
    delete user.age;

    console.log(user); // {name: "John"}
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

71. ### What is typeof operator

    JavaScript o'zgaruvchisi turini topish uchun JavaScript typeof operatoridan foydalanishingiz mumkin. U o'zgaruvchi yoki ifoda turini qaytaradi.

    ```javascript
    typeof "John Abraham"; // Returns "string"
    typeof (1 + 2); // Returns "number"
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

72. ### What is undefined property

    Undefined property o'zgaruvchiga qiymat berilmaganligini yoki e'lon qilinmagan, lekin umuman ishga tushirilmaganligini ko'rsatadi. Undefined property turi ham aniqlanmagan.

    ```javascript
    var user; // Value is undefined, type is undefined
    console.log(typeof user); //undefined
    ```

    Qiymatni aniqlanmagan qilib belgilash orqali har qanday o'zgaruvchini bo'shatish mumkin.

    ```javascript
    user = undefined;
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

73. ### What is null value

    Null qiymati har qanday ob'ekt qiymatining ataylab yo'qligini anglatadi. Bu JavaScript-ning primitive value(laridan) biridir. Null qiymat turi ob'ekt hisoblanadi. Qiymatni null ga o'rnatish orqali o'zgaruvchini bo'shatish mumkin.

    ```javascript
    var user = null;
    console.log(typeof user); //object
    ```

    **[⬆ Yuqoriga qaytish](#tmundarija)**

74. ### What is the difference between null and undefined

    Quyida null va undefined o'rtasidagi asosiy farqlar keltirilgan,

    | Null                                                                                         | Undefined                                                                              |
    | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
    | Bu o'zgaruvchining hech qanday ob'ektga ishora qilmasligini ko'rsatadigan tayinlash qiymati. | Bu o'zgaruvchi e'lon qilingan, lekin hali qiymat tayinlanmagan tayinlash qiymati emas. |
    | Type of null is object                                                                       | Type of undefined is undefined                                                         |
    | Null qiymat nol, bo'sh yoki mavjud bo'lmagan havolani ifodalovchi ibtidoiy qiymatdir.        | Undefined qiymat o'zgaruvchiga qiymat berilmaganda ishlatiladigan ibtidoiy qiymatdir.  |
    | O'zgaruvchi uchun qiymat yo'qligini ko'rsatadi                                               | O'zgaruvchining o'zi yo'qligini ko'rsatadi                                             |
    | Primitiv amallarni bajarishda nolga (0) aylantiriladi                                        | Primitiv operatsiyalarni bajarishda NaN ga aylantiriladi                               |

    **[⬆ Yuqoriga qaytish](#mundarija)**

75. ### What is eval

    eval() funksiyasi satr sifatida taqdim etilgan JavaScript code(ni) baholaydi. Satr JavaScript ifodasi, o'zgaruvchi, bayonot yoki bayonotlar ketma-ketligi bo'lishi mumkin.

    ```javascript
    console.log(eval("1 + 2")); //  3
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

76. ### What is the difference between window and document

    Quyida window va document o'rtasidagi asosiy farqlar keltirilgan,

    | Window                                                                             | Document                                                                                       |
    | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
    | Bu har qanday web page ildiz darajasining elementidir                              | Bu window ob'ektining bevosita bolasi. Bu Document Object Model (DOM) sifatida ham tanilgan.   |
    | Odatiy bo'lib window ob'ekti sahifada bevosita mavjud                              | Unga window.document yoki document orqali kirishingiz mumkin.                                  |
    | Unda alert(), confirm() kabi usullar va hujjat, joylashuv kabi xususiyatlar mavjud | U getElementById, getElementsByTagName, createElement va boshqalar kabi usullarni taqdim etadi |

    **[⬆ Yuqoriga qaytish](#mundarija)**

77. ### How do you access history in javascript

    window.history obyekti brauzer tarixini o'z ichiga oladi. Tarixdagi oldingi va keyingi URL-larni back() va next() usullaridan foydalanib yuklashingiz mumkin.

    ```javascript
    function goBack() {
      window.history.back();
    }
    function goForward() {
      window.history.forward();
    }
    ```

    **Eslatma:** Siz history(ga) window prefix ham kirishingiz mumkin.

    **[⬆ Yuqoriga qaytish](#mundarija)**

78. ### How do you detect caps lock key turned on or not

    `MouseEvent getModifierState()` ko'rsatilgan modifier key faollashtirilgan yoki yoqilmaganligini ko'rsatadigan mantiqiy qiymatni qaytarish uchun ishlatiladi. CapsLock, ScrollLock va NumLock kabi modifiers(lar) bosilganda faollashadi va yana bosilganda o'chiriladi.

    Keling, misol bilan CapsLock-ni on/off harakatini aniqlash uchun kirish elementini olaylik,

    ```html
    <input type="password" onmousedown="enterInput(event)" />

    <p id="feedback"></p>

    <script>
      function enterInput(e) {
        var flag = e.getModifierState("CapsLock");
        if (flag) {
          document.getElementById("feedback").innerHTML = "CapsLock activated";
        } else {
          document.getElementById("feedback").innerHTML =
            "CapsLock not activated";
        }
      }
    </script>
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

79. ### What is isNaN

    isNaN() funksiyasi qiymat noqonuniy son (Not-a-Number) yoki yoʻqligini aniqlash uchun ishlatiladi. ya'ni, agar qiymat NaN ga teng bo'lsa, bu funksiya true ni qaytaradi. Aks holda u false qaytaradi.

    ```javascript
    isNaN("Hello"); //true
    isNaN("100"); //false
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

80. ### What are the differences between undeclared and undefined variables

    Quyida e'lon qilinmagan (aniqlanmagan) va aniqlanmagan o'zgaruvchilar o'rtasidagi asosiy farqlar,

    | undeclared                                                                                                      | undefined                                                                                                    |
    | --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
    | Bu o'zgaruvchilar program mavjud emas va e'lon qilinmaydi                                                       | Ushbu o'zgaruvchilar program e'lon qilingan, ammo hech qanday qiymat tayinlanmagan                           |
    | Agar siz e'lon qilinmagan o'zgaruvchining qiymatini o'qishga harakat qilsangiz, ish vaqti xatosi paydo bo'ladi. | Agar siz aniqlanmagan o'zgaruvchining qiymatini o'qishga harakat qilsangiz, aniqlanmagan qiymat qaytariladi. |

    **[⬆ Yuqoriga qaytish](#mundarija)**

81. ### What are global variables

    Global o'zgaruvchilar code(ning) butun uzunligi davomida hech qanday qamrovsiz mavjud bo'lganlardir. var keyword so'zi local o'zgaruvchini e'lon qilish uchun ishlatiladi, lekin agar uni o'tkazib yuborsangiz, u global o'zgaruvchiga aylanadi.

    ```javascript
    msg = "Hello"; // var is missing, it becomes global variable
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

82. ### What are the problems with global variables

    Global o'zgaruvchilar bilan bog'liq muammo local va global miqyosdagi o'zgaruvchilar nomlarining ziddiyatidir. Global o'zgaruvchilarga tayanadigan code(ni) disk raskadrovka qilish va sinab ko'rish ham qiyin.

    **[⬆ Yuqoriga qaytish](#mundarija)**

83. ### What is NaN property

    NaN xususiyati "Raqam emas" qiymatini ifodalovchi global xususiyatdir. ya'ni, bu qiymat qonuniy raqam emasligini bildiradi. Dasturda NaN dan foydalanish juda kam uchraydi, lekin uni bir necha hollarda qaytarish qiymati sifatida ishlatish mumkin

    ```javascript
    Math.sqrt(-1);
    parseInt("Hello");
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

84. ### What is the purpose of isFinite function

    isFinite() funksiyasi sonning cheklangan, qonuniy son ekanligini aniqlash uchun ishlatiladi. Qiymat +infinity, -infinity yoki NaN (Not-a-Number) bo'lsa, u noto'g'ri, aks holda u haqiqatni qaytaradi.

    ```javascript
    isFinite(Infinity); // false
    isFinite(NaN); // false
    isFinite(-Infinity); // false

    isFinite(100); // true
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

85. ### What is an event flow

    Event flow - web page voqea qabul qilish tartibi. Turli boshqa elementlarga joylashtirilgan elementni bosganingizda, sizning click o'z manziliga yoki maqsad elementiga yetib borgunga qadar, u global window obyekti bilan yuqoridan boshlab, birinchi navbatda, har bir asosiy element uchun bosish hodisasini ishga tushirishi kerak.
    Event flow ikki yo'li mavjud

    1. Yuqoridan pastgacha (Event Capturing)
    2. Pastdan tepaga (Event Bubbling)

    **[⬆ Yuqoriga qaytish](#mundarija)**

86. ### What is event bubbling

    Event bubbling - bu hodisa tarqalishning bir turi bo'lib event birinchi navbatda eng ichki maqsad elementida boshlanadi, va keyin eng tashqi DOM elementiga yetguncha bir xil joylashtirish hierarchy maqsadli elementning ajdodlarida (ota-onalarida) ketma-ket ishga tushadi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

87. ### What is event capturing

    Event capturing - bu hodisani tarqatishning bir turi bo'lib, unda hodisa birinchi navbatda eng tashqi element tomonidan capture qilinadi, va keyin bir xil joylashtirish hierarchy maqsadli elementning avlodlarida (bolalarida) eng ichki DOM elementiga yetguncha ketma-ket ishga tushadi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

88. ### How do you submit a form using JavaScript

    Form `document.forms[0].submit()` yordamida yuborishingiz mumkin. Form(GA) kiritilgan barcha ma'lumotlar onsubmit event ishlov beruchisi yordamida yuboriladi.

    ```javascript
    function submit() {
      document.forms[0].submit();
    }
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

89. ### How do you find operating system details

    window.navigator ob'ekti tashrif buyuruvchi brauzerining OS tafsilotlari haqidagi ma'lumotlarni o'z ichiga oladi. Ba'zi OS properties platforma property ostida mavjud.

    ```javascript
    console.log(navigator.platform);
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

90. ### What is the difference between document load and DOMContentLoaded events

    `DOMContentLoaded` hodisasi boshlang'ich HTML hujjati to'liq yuklangan va tahlil qilinganda, aktivlar (uslublar jadvallari, tasvirlar va pastki ramkalar) yuklashni tugatilishini kutmasdan ishga tushiriladi. Holbuki, load hodisasi butun sahifa yuklanganda, shu jumladan barcha bog'liq resurslar (uslublar jadvallari, rasmlar) ishga tushiriladi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

91. ### What is the difference between native, host and user objects

    `Native objects` ECMAScript specification bilan belgilangan JavaScript tilining bir qismi bo'lgan ob'ektlardir. Masalan, ECMAScript spetsifikatsiyasida belgilangan String, Math, RegExp, Object, Function va hokazo asosiy ob'ektlar.
    `Host objects` brauzer yoki ish vaqti muhiti (Node) tomonidan taqdim etilgan ob'ektlardir. Masalan, window, XmlHttpRequest, DOM tugunlari va boshqalar xost ob'ektlari sifatida qabul qilinadi.
    `User objects` JavaScript code(dida) belgilangan ob'ektlardir. Masalan, profil ma'lumotlari uchun yaratilgan Foydalanuvchi ob'ektlari.

    **[⬆ Yuqoriga qaytish](#mundarija)**

92. ### What are the tools or techniques used for debugging JavaScript code

    Javascriptni nosozliklarni tuzatish uchun quyidagi vositalar yoki usullardan foydalanishingiz mumkin

    1. Chrome Devtools
    2. debugger statement
    3. Good old console.log statement

    **[⬆ Yuqoriga qaytish](#mundarija)**

93. ### What are the pros and cons of promises over callbacks

    Quyida callbacks bo'yicha promise(larnig) ijobiy va salbiy tomonlari ro'yxati keltirilgan,

    **Pros:**

    1. Bu o'qib bo'lmaydigan callback qilishning oldini oladi
    2. .then() bilan ketma-ket asynchronous code(ni) yozish oson.
    3. Promise.all() bilan parallel asynchronous code yozish oson.
    4. callback(larning) ba'zi umumiy muammolarini hal qiladi (callback juda kech, juda erta, ko'p marta callback va xatolar/istisnolarni yutib yuboring)

    **Kamchiliklari:**

    1. U ozgina murakkab code yaratadi
    2. ES6 qo'llab-quvvatlanmasa, polifillni yuklashingiz kerak

    **[⬆ Yuqoriga qaytish](#mundarija)**

94. ### What is the difference between an attribute and a property

    Atributlar HTML belgilashda, xususiyatlar esa DOMda aniqlanadi. Masalan, quyidagi HTML elementi 2 ta atribut turi va qiymatiga ega,

    ```javascript
    <input type="text" value="Name:">
    ```

    Atribut qiymatini quyidagi tarzda olishingiz mumkin,

    ```javascript
    const input = document.querySelector("input");
    console.log(input.getAttribute("value")); // Good morning
    console.log(input.value); // Good morning
    ```

    Va matn maydonining qiymatini "Good evening" ga o'zgartirganingizdan so'ng, u shunday bo'ladi

    ```javascript
    console.log(input.getAttribute("value")); // Good evening
    console.log(input.value); // Good evening
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

95. ### What is same-origin policy

    Bir xil kelib chiqish siyosati JavaScript-ni domen chegaralari bo'ylab so'rovlar qilishiga to'sqinlik qiluvchi siyosatdir. Kelib chiqishi URL sxemasi, xost nomi va port raqamining kombinatsiyasi sifatida aniqlanadi. Agar siz ushbu siyosatni yoqsangiz, u Document Object Model (DOM) yordamida bir sahifadagi zararli skript boshqa veb-sahifadagi maxfiy maʼlumotlarga kirishini oldini oladi.

    **[⬆ Yuqoriga qaytish](#mundarija)**

96. ### What is the purpose of void 0

    Void(0) sahifaning yangilanishini oldini olish uchun ishlatiladi. Bu kiruvchi yon ta'sirni bartaraf etishda foydali bo'ladi, chunki u aniqlanmagan ibtidoiy qiymatni qaytaradi. U odatda href="JavaScript:Void(0);" ishlatadigan HTML hujjatlari uchun ishlatiladi. `<a>` elementi ichida. ya'ni havolani bosganingizda, brauzer yangi sahifani yuklaydi yoki bir xil sahifani yangilaydi. Ammo bu ibora yordamida bu xatti-harakatning oldini oladi. Masalan, quyidagi havola sahifani qayta yuklamasdan xabarni bildiradi

    ```javascript
    <a href="JavaScript:void(0);" onclick="alert('Well done!')">
      Click Me!
    </a>
    ```

    **[⬆ Yuqoriga qaytish](#mundarija)**

97. ### Is JavaScript a compiled or interpreted language

    JavaScript kompilyatsiya qilingan til emas, balki talqin qilinadigan tildir. Brauzerdagi tarjimon JavaScript code(ni) o'qiydi, har bir satrni sharhlaydi va uni ishga tushiradi. Hozirgi vaqtda zamonaviy brauzerlar JavaScript-ni ishga tushirish arafasida bajariladigan bytecode(ga) kompilyatsiya qiladigan Just-In-Time (JIT) kompilyatsiyasi deb nomlanuvchi texnologiyadan foydalanadilar.

    **[⬆ Yuqoriga qaytish](#mundarija)**

98. ### Is JavaScript a case-sensitive language

    Ha, JavaScript katta-kichik harflarga sezgir tildir. Til kalit so'zlari, o'zgaruvchilar, funksiya va ob'ekt nomlari va boshqa identifikatorlar har doim harflarning izchil bosh harflari bilan kiritilishi kerak.

    **[⬆ Yuqoriga qaytish](#mundarija)**

99. ### Is there any relation between Java and JavaScript

    Yo'q, ular butunlay ikki xil dasturlash tillari va bir-biriga hech qanday aloqasi yo'q. Ammo ularning ikkalasi ham ob'ektga yo'naltirilgan dasturlash tillari va boshqa ko'plab tillar singari, ular asosiy funktsiyalar uchun o'xshash sintaksisga amal qiladilar (agar, boshqacha, uchun, o'tish, buzish, davom ettirish va hokazo).

    **[⬆ Yuqoriga qaytish](#mundarija)**

100. ### What are events

     Hodisalar HTML elementlari bilan sodir bo'ladigan `react`. HTML sahifalarida JavaScript ishlatilsa, JavaScript bu hodisalarga munosabat bildira oladi. HTML hodisalariga ba'zi misollar:

     1. Web page has finished loading
     2. Input field was changed
     3. Button was clicked

     Keling, tugma elementi uchun bosish hodisasining harakatini tasvirlaylik,

     ```javascript
     <!doctype html>
     <html>
      <head>
        <script>
          function greeting() {
            alert('Hello! Good morning');
          }
        </script>
      </head>
      <body>
        <button type="button" onclick="greeting()">Click me</button>
      </body>
     </html>
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

101. ### Who created javascript

     JavaScript Brendan Eich tomonidan 1995 yilda Netscape Communications kompaniyasida ishlagan vaqtida yaratilgan. Dastlab u `Mocha` nomi bilan ishlab chiqilgan, ammo keyinchalik Netscape-ning beta-versiyalarida birinchi marta yuborilganida bu til rasmiy ravishda `LiveScript` deb nomlangan.

     **[⬆ Yuqoriga qaytish](#mundarija)**

102. ### What is the use of preventDefault method

     preventDefault() usuli, agar u bekor qilinadigan bo'lsa, hodisani bekor qiladi, ya'ni hodisaga tegishli bo'lgan standart harakat yoki xatti-harakatlar sodir bo'lmaydi. Masalan, “Yuborish” tugmasini bosganingizda shaklni yuborishni oldini olish va giperhavolani bosganingizda sahifa URL manzilini ochishning oldini olish keng tarqalgan holatlardir.

     ```javascript
     document
       .getElementById("link")
       .addEventListener("click", function (event) {
         event.preventDefault();
       });
     ```

     **Eslatma:** Esda tutingki, barcha tadbirlar bekor qilinmaydi.

     **[⬆ Yuqoriga qaytish](#mundarija)**

103. ### What is the use of stopPropagation method

     StopPropagation usuli hodisaning hodisalar zanjirida ko'payishini to'xtatish uchun ishlatiladi. Misol uchun, stopPropagation usuli bilan quyida joylashgan divlar ichki o'rnatilgan div (Div1) ni bosganda standart hodisa tarqalishini oldini oladi.

     ```javascript
     <p>Click DIV1 Element</p>
     <div onclick="secondFunc()">DIV 2
       <div onclick="firstFunc(event)">DIV 1</div>
     </div>

     <script>
     function firstFunc(event) {
       alert("DIV 1");
       event.stopPropagation();
     }

     function secondFunc() {
       alert("DIV 2");
     }
     </script>
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

104. ### What are the steps involved in return false usage

     Hodisa event handler performs bayonotni qaytarish quyidagi amallarni bajaradi:

     1. Avval u brauzerning standart harakatini yoki harakatini to'xtatadi.
     2. Bu hodisaning DOMni targ'ib qilishiga to'sqinlik qiladi
     3. Callback(ni) bajarishni to'xtatadi va chaqirilganda darhol qaytadi.

     **[⬆ Yuqoriga qaytish](#mundarija)**

105. ### What is BOM

     Brauzer obyekti modeli (BOM) JavaScript-ga brauzer bilan “suhbatlashish” imkonini beradi. U navigator, history, screen, location va window(ning) bolalari bo'lgan hujjatdan iborat. Brauzer object modeli standartlashtirilmagan va turli brauzerlar asosida o'zgarishi mumkin.

     ![Screenshot](images/bom.png)

     **[⬆ Yuqoriga qaytish](#mundarija)**

106. ### What is the use of setTimeout

     setTimeout() usuli funksiyani chaqirish yoki belgilangan millisekundlardan keyin ifodani baholash uchun ishlatiladi. Masalan, setTimeout usuli yordamida 2 soniyadan so'ng xabarni tizimga kiritamiz,

     ```javascript
     setTimeout(function () {
       console.log("Good morning");
     }, 2000);
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

107. ### What is the use of setInterval

     setInterval() usuli funksiyani chaqirish yoki ifodani belgilangan oraliqlarda (millisekundlarda) baholash uchun ishlatiladi. Masalan, setInterval usuli yordamida 2 soniyadan so'ng xabarni tizimga kiritamiz,

     ```javascript
     setInterval(function () {
       console.log("Good morning");
     }, 2000);
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

108. ### Why is JavaScript treated as Single threaded

     JavaScript - bu bitta oqimli til. Chunki til spetsifikatsiyasi dasturchiga code yozishga imkon bermaydi, shunda tarjimon uning qismlarini bir nechta ip yoki jarayonlarda parallel ravishda ishga tushirishi mumkin. Holbuki java, go, C++ kabi tillar ko'p bosqichli va ko'p jarayonli dasturlarni yaratishi mumkin.

     **[⬆ Yuqoriga qaytish](#mundarija)**

109. ### What is an event delegation

     Event delegation - bu event(larni) tinglash usuli bo'lib, unda siz asosiy elementni uning ichida sodir bo'ladigan barcha event(lar) uchun tinglovchi sifatida topshirasiz.

     Misol uchun, agar siz ma'lum bir shakl ichidagi maydon o'zgarishlarini aniqlamoqchi bo'lsangiz, event delegation texnikasidan foydalanishingiz mumkin,

     ```javascript
     var form = document.querySelector("#registration-form");

     // Listen for changes to fields inside the form
     form.addEventListener(
       "input",
       function (event) {
         // Log the field that was changed
         console.log(event.target);
       },
       false
     );
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

110. ### What is ECMAScript

     ECMAScript JavaScript asosini tashkil etuvchi script tilidir. ECMAScript ECMA xalqaro standartlar tashkiloti tomonidan ECMA-262 va ECMA-402 spetsifikatsiyalarida standartlashtirilgan. ECMAScript ning birinchi nashri 1997 yilda chiqarilgan.

     **[⬆ Yuqoriga qaytish](#mundarija)**

111. ### What is JSON

     JSON (JavaScript Object Notation) is a lightweight format that is used for data interchanging. It is based on a subset of JavaScript language in the way objects are built in JavaScript.

     **[⬆ Yuqoriga qaytish](#mundarija)**

112. ### What are the syntax rules of JSON

     Quyida JSON sintaksisi qoidalari ro'yxati keltirilgan

     1. Ma'lumotlar name/value juftliklarida
     2. Ma'lumotlar vergul bilan ajratiladi
     3. Curly qavslar object(larni) ushlab turadi
     4. Kvadrat qavslar array(larni) ushlab turadi

     **[⬆ Yuqoriga qaytish](#mundarija)**

113. ### What is the purpose JSON stringify

     Veb-serverga ma'lumotlarni yuborishda ma'lumotlar string formatida bo'lishi kerak. Bunga JSON obyektini stringify() usuli yordamida satrga aylantirish orqali erishishingiz mumkin.

     ```javascript
     var userJSON = { name: "John", age: 31 };
     var userString = JSON.stringify(userJSON);
     console.log(userString); //"{"name":"John","age":31}"
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

114. ### How do you parse JSON string

     Veb-serverdan ma'lumotlarni qabul qilishda ma'lumotlar har doim string formatida bo'ladi. Lekin bu satr qiymatini parse() usuli yordamida JavaScript object(ga) aylantirishingiz mumkin.

     ```javascript
     var userString = '{"name":"John","age":31}';
     var userJSON = JSON.parse(userString);
     console.log(userJSON); // {name: "John", age: 31}
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

115. ### Why do you need JSON

     Brauzer va server o'rtasida ma'lumot almashishda ma'lumotlar faqat matn bo'lishi mumkin. JSON faqat matn bo'lgani uchun uni serverga va serverdan osongina yuborish va istalgan dasturlash tili tomonidan ma'lumotlar formati sifatida foydalanish mumkin.

     **[⬆ Yuqoriga qaytish](#mundarija)**

116. ### What are PWAs

     Progressiv veb-ilovalar (PWA) - bu HTML, CSS va JavaScript kabi umumiy veb-texnologiyalar yordamida yaratilgan, internet orqali yetkazib beriladigan mobil ilovaning bir turi. Ushbu PWA'lar serverlarga joylashtiriladi, URL manzillari orqali kirish mumkin va qidiruv tizimlari tomonidan indekslanadi.

     **[⬆ Yuqoriga qaytish](#mundarija)**

117. ### What is the purpose of clearTimeout method

     ClearTimeout() funksiyasi javascriptda setTimeout() funktsiyasi tomonidan o'rnatilgan vaqt tugashini tozalash uchun ishlatiladi.ya'ni setTimeout() funksiyasining qaytish qiymati o'zgaruvchida saqlanadi va taymerni tozalash uchun clearTimeout() funksiyasiga o'tkaziladi.

     Masalan, quyidagi setTimeout usuli xabarni 3 soniyadan keyin ko'rsatish uchun ishlatiladi. Bu vaqt tugashi clearTimeout() usuli bilan tozalanishi mumkin.

     ```javascript
     <script>
     var msg;
     function greeting() {
        alert('Good morning');
     }
     function start() {
       msg =setTimeout(greeting, 3000);

     }

     function stop() {
         clearTimeout(msg);
     }
     </script>
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

118. ### What is the purpose of clearInterval method

     ClearInterval() funksiyasi javascriptda setInterval() funksiyasi tomonidan belgilangan intervalni tozalash uchun ishlatiladi. ya'ni, setInterval() funktsiyasi tomonidan qaytarilgan qiymat o'zgaruvchida saqlanadi va intervalni tozalash uchun clearInterval() funksiyasiga o'tkaziladi.

     Masalan, har 3 soniyada xabarni ko'rsatish uchun quyidagi setInterval usuli qo'llaniladi. Ushbu intervalni clearInterval() usuli bilan tozalash mumkin.

     ```javascript
     <script>
     var msg;
     function greeting() {
        alert('Good morning');
     }
     function start() {
       msg = setInterval(greeting, 3000);

     }

     function stop() {
         clearInterval(msg);
     }
     </script>
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

119. ### How do you redirect new page in javascript

     Vanilla JavaScript-da siz window object(ning) `location` xususiyatidan foydalanib, yangi sahifaga yo'naltirishingiz mumkin. Sintaksis quyidagicha bo'ladi:

     ```javascript
     function redirect() {
       window.location.href = "newPage.html";
     }
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

120. ### How do you check whether a string contains a substring

     String(da) substring mavjud yoki yo'qligini tekshirishning 3 ta mumkin bo'lgan usuli mavjud,

     1. **Foydalanuvchi quyidagilarni o'z ichiga oladi:** ES6 bilan ta'minlangan `String.prototype.includes` satrni sinash usuli pastki qatorni o'z ichiga oladi

     ```javascript
     var mainString = "hello",
       subString = "hell";
     mainString.includes(subString);
     ```

     1. **Using indexOf:** ES5 yoki undan kattaroq muhitda siz pastki qator indeksini qaytaradigan `String.prototype.indexOf` dan foydalanishingiz mumkin. Agar indeks qiymati -1 ga teng bo'lmasa, bu pastki satr asosiy satrda mavjudligini anglatadi.

     ```javascript
     var mainString = "hello",
       subString = "hell";
     mainString.indexOf(subString) !== -1;
     ```

     1. **Using RegEx:** Kengaytirilgan yechim muntazam ifodalarni sinovdan o'tkazish usulidan (`RegExp.test`) foydalanmoqda, bu oddiy iboralarga qarshi test qilish imkonini beradi.

     ```javascript
     var mainString = "hello",
       regex = /hell/;
     regex.test(mainString);
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

121. ### How do you validate an email in javascript

     Oddiy iboralar yordamida JavaScript-da elektron pochta xabarini tasdiqlashingiz mumkin. Tasdiqlashlarni mijoz tomoni o'rniga server tomonida qilish tavsiya etiladi. Chunki javascript mijoz tomonida o'chirib qo'yilishi mumkin.

     ```javascript
     function validateEmail(email) {
       var re =
         /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
       return re.test(String(email).toLowerCase());
     }
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

     Yuqoridagi muntazam ifoda unicode belgilarni qabul qiladi.

122. ### How do you get the current url with javascript

     Joriy url yo'lini olish uchun `window.location.href` ifodasidan foydalanishingiz mumkin va URLni yangilash uchun ham xuddi shu ifodadan foydalanishingiz mumkin. `Document.URL` dan faqat o'qish uchun ham foydalanishingiz mumkin, ammo bu yechim FFda muammolarga ega.

     ```javascript
     console.log("location.href", window.location.href); // Returns full URL
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

123. ### What are the various url properties of location object

     Quyidagi `Location` obyekti xususiyatlaridan sahifaning URL komponentlariga kirish uchun foydalanish mumkin,

     1. href - Butun URL
     2. protocol - URL manzilining xost nomi va porti
     3. host - URL manzilining xost nomi va porti
     4. hostname - URL xost nomi
     5. port - URL manzilidagi port raqami
     6. pathname - URL manzilining yo'l nomi
     7. search - URLning so'rov qismi
     8. hash - The URLning langar qismi

     **[⬆ Yuqoriga qaytish](#mundarija)**

124. ### How do get query string values in javascript

     Javascriptda so'rovlar qatori qiymatlarini olish uchun URLSearchParams dan foydalanishingiz mumkin. Keling, URL so'rovlar qatoridan mijoz code qiymatini olish uchun misolni ko'rib chiqaylik,

     ```javascript
     const urlParams = new URLSearchParams(window.location.search);
     const clientCode = urlParams.get("clientCode");
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

125. ### How do you check if a key exists in an object

     Ob'ektda key mavjudligi yoki yo'qligini uchta yondashuv yordamida tekshirishingiz mumkin,

     1. **Operatordan foydalanish:** Ob'ektda key mavjudmi yoki yo'qmi, in operatoridan foydalanishingiz mumkin

     ```javascript
     "key" in obj;
     ```

     Agar key mavjud emasligini tekshirmoqchi bo'lsangiz, qavsdan foydalanishni unutmang,

     ```javascript
     !("key" in obj);
     ```

     1. **hasOwnProperty usulidan foydalanish:** `HasOwnProperty` dan ob'ekt namunasining xususiyatlarini (va meros qilib olingan xususiyatlarni emas) sinab ko'rish uchun foydalanishingiz mumkin.

     ```javascript
     obj.hasOwnProperty("key"); // true
     ```

     1. **Undefined comparison foydalanish:** Agar ob'ektdan mavjud bo'lmagan xususiyatga kirsangiz, natija aniqlanmagan. Mulkning mavjudligini aniqlash uchun xususiyatlarni aniqlanmagan bilan taqqoslaylik.

     ```javascript
     const user = {
       name: "John",
     };

     console.log(user.name !== undefined); // true
     console.log(user.nickName !== undefined); // false
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

126. ### How do you loop through or enumerate javascript object

     Javascript ob'ekti bo'ylab aylanish uchun `for-in` loop(dan) foydalanishingiz mumkin. Shuningdek, siz olgan key ob'ektning haqiqiy mulki ekanligiga va `hasOwnProperty` usuli yordamida prototipdan kelmasligiga ishonch hosil qilishingiz mumkin.

     ```javascript
     var object = {
       k1: "value1",
       k2: "value2",
       k3: "value3",
     };

     for (var key in object) {
       if (object.hasOwnProperty(key)) {
         console.log(key + " -> " + object[key]); // k1 -> value1 ...
       }
     }
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

127. ### How do you test for an empty object

     ECMAScript versiyalariga asoslangan turli xil yechimlar mavjud

     1. **Using Object entries(ECMA 7+):** Siz konstruktor turi bilan birga ob'ekt yozuvlari uzunligidan foydalanishingiz mumkin.

     ```javascript
     Object.entries(obj).length === 0 && obj.constructor === Object; // Sana ob'ektining uzunligi 0 bo'lgani uchun siz konstruktor tekshiruvini ham tekshirishingiz kerak
     ```

     1. **Using Object keys(ECMA 5+):** You can use object keys length along with constructor type.

     ```javascript
     Object.keys(obj).length === 0 && obj.constructor === Object; // Since date object length is 0, you need to check constructor check as well
     ```

     1. **Using for-in with hasOwnProperty(Pre-ECMA 5):** Konstruktor turi bilan birga ob'ekt tugmachalari uzunligidan ham foydalanishingiz mumkin.

     ```javascript
     function isEmpty(obj) {
       for (var prop in obj) {
         if (obj.hasOwnProperty(prop)) {
           return false;
         }
       }

       return JSON.stringify(obj) === JSON.stringify({});
     }
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

128. ### What is an arguments object

     Argumentlar obyekti funksiyalar ichida mavjud boʻlgan massivga oʻxshash obyekt boʻlib, u funksiyaga uzatilgan argumentlar qiymatlarini oʻz ichiga oladi. Masalan, sum funksiyasi ichida argumentlar obyektidan qanday foydalanishni ko‘rib chiqamiz,

     ```javascript
     function sum() {
       var total = 0;
       for (var i = 0, len = arguments.length; i < len; ++i) {
         total += arguments[i];
       }
       return total;
     }

     sum(1, 2, 3); // returns 6
     ```

     **Eslatma:** Argumentlar obyektida massiv usullarini qo‘llay olmaysiz. Lekin siz quyidagi kabi oddiy massivga aylantira olasiz.

     ```javascript
     var argsArray = Array.prototype.slice.call(arguments);
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

129. ### How do you make first letter of the string in an uppercase

     Siz bosh harf bilan satr yaratish uchun charAt, toUpperCase va slice usullari kabi qator usullardan foydalanadigan funksiya yaratishingiz mumkin.

     ```javascript
     function capitalizeFirstLetter(string) {
       return string.charAt(0).toUpperCase() + string.slice(1);
     }
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

130. ### What are the pros and cons of for loop

     For-loop javascriptda tez-tez ishlatiladigan iteratsiya sintaksisidir. Buning ham ijobiy, ham salbiy tomonlari bor

     #### Pros

     1. Har qanday muhitda ishlaydi
     2. Siz break va continue oqimini boshqarish bayonotlaridan foydalanishingiz mumkin

     #### Cons

     1. Juda batafsil
     2. Imperative
     3. Siz bir martalik xatolarga duch kelishingiz mumkin

     **[⬆ Yuqoriga qaytish](#mundarija)**

131. ### How do you display the current date in javascript

     Joriy sana va vaqtni o'z ichiga olgan yangi Sana ob'ektini yaratish uchun `new Date()` dan foydalanishingiz mumkin. Masalan, joriy sanani mm/dd/yyyy da ko'rsatamiz

     ```javascript
     var today = new Date();
     var dd = String(today.getDate()).padStart(2, "0");
     var mm = String(today.getMonth() + 1).padStart(2, "0"); //January is 0!
     var yyyy = today.getFullYear();

     today = mm + "/" + dd + "/" + yyyy;
     document.write(today);
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

132. ### How do you compare two date objects

     Taqqoslash operatorlari (==, !=, === va !== operatorlari) o‘rniga sana qiymatlarini solishtirish uchun date.getTime() usulidan foydalanishingiz kerak.

     ```javascript
     var d1 = new Date();
     var d2 = new Date(d1);
     console.log(d1.getTime() === d2.getTime()); //True
     console.log(d1 === d2); // False
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

133. ### How do you check if a string starts with another string

     ECMAScript 6 ning `String.prototype.startsWith()` usulidan string boshqa string bilan boshlanishi yoki boshlanmasligini tekshirishingiz mumkin. Ammo u hali barcha brauzerlarda qo'llab-quvvatlanmaydi. Keling, ushbu foydalanishni ko'rish uchun misolni ko'rib chiqaylik,

     ```javascript
     "Good morning".startsWith("Good"); // true
     "Good morning".startsWith("morning"); // false
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

134. ### How do you trim a string in javascript

     JavaScript string(nig) boshida yoki oxirida mavjud bo'lgan bo'shliqlarni kesish uchun string turlari bo'yicha kesish usulini taqdim etdi.

     ```javascript
     "  Hello World   ".trim(); //Hello World
     ```

     Agar brauzeringiz (<IE9) bu usulni qo'llab-quvvatlamasa, quyida polyfill(dan) foydalanishingiz mumkin.

     ```javascript
     if (!String.prototype.trim) {
       (function () {
         // Make sure we trim BOM and NBSP
         var rtrim = /^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g;
         String.prototype.trim = function () {
           return this.replace(rtrim, "");
         };
       })();
     }
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

135. ### How do you add a key value pair in javascript

     Ob'ektga yangi xususiyatlar qo'shishning ikkita mumkin bo'lgan yechimi mavjud. Ushbu yechimlarni tushuntirish uchun oddiy ob'ektni olaylik.

     ```javascript
     var object = {
       key1: value1,
       key2: value2,
     };
     ```

     1. **Dot notation foydalanish:** Ushbu yechim mulk nomini bilsangiz foydali bo'ladi

     ```javascript
     object.key3 = "value3";
     ```

     1. **Square bracket notation foydalanish:** Ushbu yechim xususiyat nomi dinamik tarzda aniqlanganda foydalidir.

     ```javascript
     obj["key3"] = "value3";
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

136. ### Is the !-- notation represents a special operator

     Yo'q, bu maxsus operator emas. Ammo bu birin-ketin ikkita standart operatorning kombinatsiyasi,

     1. A logical not (!)
     2. A prefix decrement (--)

     Avvaliga value bittaga kamaydi va keyin truthy/falsy qiymatni aniqlash uchun nolga teng yoki yo'qligini tekshirish uchun sinovdan o'tkazildi.

     **[⬆ Yuqoriga qaytish](#mundarija)**

137. ### How do you assign default values to variables

     Mantiqiy yoki `||` operatoridan foydalanishingiz mumkin standart qiymatni berish uchun tayinlash ifodasida. Sintaksis quyidagi kabi ko'rinadi,

     ```javascript
     var a = b || c;
     ```

     Yuqoridagi ifodaga ko'ra, "a" o'zgaruvchisi "b" noto'g'ri bo'lsa (agar null, noto'g'ri, aniqlanmagan, 0, bo'sh qator yoki NaN bo'lsa), aks holda "a" o'zgaruvchisi "c" qiymatini oladi. "b" qiymati.

     **[⬆ Yuqoriga qaytish](#mundarija)**

138. ### How do you define multiline strings

     Ko'p qatorli satr harflarini "\\" belgisidan keyin qator terminatori yordamida belgilashingiz mumkin.

     ```javascript
     var str =
       "This is a \
     very lengthy \
     sentence!";
     ```

     Ammo "\\" belgisidan keyin bo'sh joy bo'lsa, code aynan bir xil ko'rinadi, lekin u SyntaxError ko'taradi.

     **[⬆ Yuqoriga qaytish](#mundarija)**

139. ### What is an app shell model

     Application shell (yoki app shell) arxitekturasi mahalliy ilovalarda ko'rganingizga o'xshash foydalanuvchilar ekraniga ishonchli va bir zumda yuklanadigan Progressive Web Ilovani yaratish usullaridan biridir. It is useful for getting some initial HTML to the screen fast without a network.

     **[⬆ Back to Top](#mundarija)**

140. ### Can we define properties for functions

     Bu tarmoqsiz ekranga dastlabki HTML-ni tezda olish uchun foydalidir.

     ```javascript
     fn = function (x) {
       //Function code goes here
     };

     fn.name = "John";

     fn.profile = function (y) {
       //Profile code goes here
     };
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

141. ### What is the way to find the number of parameters expected by a function

     Funksiya kutayotgan parametrlar sonini topish uchun `function.length` sintaksisidan foydalanishingiz mumkin. Raqamlar yig'indisini hisoblash uchun yig'indi funksiyasiga misol keltiraylik,

     ```javascript
     function sum(num1, num2, num3, num4) {
       return num1 + num2 + num3 + num4;
     }
     sum.length; // 4 is the number of parameters expected.
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

142. ### What is a polyfill

     Polyfill - bu uni qo'llab-quvvatlamaydigan eski brauzerlarda zamonaviy funksiyalarni ta'minlash uchun ishlatiladigan JS code(ning) bir qismi. Masalan, Silverlight plaginining polyfill dasturidan Microsoft Internet Explorer 7 da HTML Canvas elementining funksionalligini taqlid qilish uchun foydalanish mumkin.

     **[⬆ Yuqoriga qaytish](#mundarija)**

143. ### What are break and continue statements

     Break iborasi tsikldan "jump out" uchun ishlatiladi. ya'ni, skilni buzadi va skildan keyin code(ni) bajarishda davom etadi.

     ```javascript
     for (i = 0; i < 10; i++) {
       if (i === 5) {
         break;
       }
       text += "Number: " + i + "<br>";
     }
     ```

     Davom etish iborasi tsikldagi bir iteratsiyadan "jump over" uchun ishlatiladi. ya'ni, agar belgilangan shart yuzaga kelsa, u bir iteratsiyani (siklda) buzadi va sikldagi keyingi iteratsiya bilan davom etadi.

     ```javascript
     for (i = 0; i < 10; i++) {
       if (i === 5) {
         continue;
       }
       text += "Number: " + i + "<br>";
     }
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

144. ### What are js labels

     Label statement bizga JavaScript-da sikllar va bloklarni nomlash imkonini beradi. Keyin biz ushbu teglardan code(ga) keyinroq murojaat qilish uchun foydalanishimiz mumkin. Masalan, yorliqli quyidagi code raqamlar bir xil bo'lganda chop etishdan saqlaydi,

     ```javascript
     var i, j;

     loop1: for (i = 0; i < 3; i++) {
       loop2: for (j = 0; j < 3; j++) {
         if (i === j) {
           continue loop1;
         }
         console.log("i = " + i + ", j = " + j);
       }
     }

     // Output is:
     //   "i = 1, j = 0"
     //   "i = 2, j = 0"
     //   "i = 2, j = 1"
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

145. ### What are the benefits of keeping declarations at the top

     Barcha deklaratsiyalarni har bir skript yoki funksiyaning yuqori qismida saqlash tavsiya etiladi. Buni amalga oshirishning afzalliklari,

     1. Tozaroq code beradi
     2. Bu local o'zgaruvchilarni qidirish uchun yagona joyni ta'minlaydi
     3. Keraksiz global o'zgaruvchilardan qochish oson
     4. Bu istalmagan qayta re-declaration(lar) ehtimolini kamaytiradi

     **[⬆ Yuqoriga qaytish](#mundarija)**

146. ### What are the benefits of initializing variables

     Quyidagi imtiyozlar tufayli o'zgaruvchilarni ishga tushirish tavsiya etiladi,

     1. Bu toza code(ni) beradi
     2. U o'zgaruvchilarni ishga tushirish uchun yagona joyni taqdim etadi
     3. Code(da) aniqlanmagan qiymatlardan saqlaning

     **[⬆ Yuqoriga qaytish](#mundarija)**

147. ### What are the recommendations to create new object

     `new Object()` yordamida yangi ob'ektlar yaratishdan qochish tavsiya etiladi. Buning o'rniga ob'ektlarni yaratish uchun uning turiga qarab qiymatlarni ishga tushirishingiz mumkin.

     1. Assign {} instead of new Object()
     2. Assign "" instead of new String()
     3. Assign 0 instead of new Number()
     4. Assign false instead of new Boolean()
     5. Assign [] instead of new Array()
     6. Assign /()/ instead of new RegExp()
     7. Assign function (){} instead of new Function()

     Siz ularni misol sifatida belgilashingiz mumkin,

     ```javascript
     var v1 = {};
     var v2 = "";
     var v3 = 0;
     var v4 = false;
     var v5 = [];
     var v6 = /()/;
     var v7 = function () {};
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

148. ### How do you define JSON arrays

     JSON massivlari kvadrat qavslar ichida yoziladi va massivlar javascript ob'ektlarini o'z ichiga oladi. Masalan, foydalanuvchilarning JSON massivi quyidagi kabi bo'ladi:

     ```javascript
     "users":[
       {"firstName":"John", "lastName":"Abrahm"},
       {"firstName":"Anna", "lastName":"Smith"},
       {"firstName":"Shane", "lastName":"Warn"}
     ]
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

149. ### How do you generate random integers

     Tasodifiy butun sonlarni qaytarish uchun Math.random() dan Math.floor() bilan foydalanishingiz mumkin. Misol uchun, agar siz 1 dan 10 gacha bo'lgan tasodifiy butun sonlarni yaratmoqchi bo'lsangiz, ko'paytirish koeffitsienti 10 bo'lishi kerak,

     ```javascript
     Math.floor(Math.random() * 10) + 1; // returns a random integer from 1 to 10
     Math.floor(Math.random() * 100) + 1; // returns a random integer from 1 to 100
     ```

     **Eslatma:** Math.random() 0 (shu jumladan) va 1 (eksklyuziv) orasidagi tasodifiy sonni qaytaradi

     **[⬆ Yuqoriga qaytish](#mundarija)**

150. ### Can you write a random integers function to print integers with in a range

     Ha, siz min va maksimal o'rtasidagi tasodifiy sonni qaytarish uchun tegishli tasodifiy funksiyani yaratishingiz mumkin (ikkalasi ham kiritilgan)

     ```javascript
     function randomInteger(min, max) {
       return Math.floor(Math.random() * (max - min + 1)) + min;
     }
     randomInteger(1, 100); // returns a random integer from 1 to 100
     randomInteger(1, 1000); // returns a random integer from 1 to 1000
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

151. ### What is tree shaking

     Tree shaking o'lik code(ni) yo'q qilish shaklidir. Bu shuni anglatadiki, foydalanilmagan modullar qurish jarayonida to'plamga kiritilmaydi va buning uchun u ES2015 modul sintaksisining statik tuzilishiga (ya'ni import va eksport) tayanadi. Dastlab bu ES2015 modul `to'plami` tomonidan ommalashgan.

     **[⬆ Yuqoriga qaytish](#mundarija)**

152. ### What is the need of tree shaking

     Tree Shaking har qanday dasturda code hajmini sezilarli darajada kamaytirishi mumkin. ya'ni, biz sim orqali qancha kamroq code yuborsak, dastur shunchalik samarali bo'ladi. Misol uchun, agar biz SPA ramkalaridan foydalangan holda "Hello world" ilovasini yaratmoqchi bo'lsak, u bir necha MB vaqtni oladi, lekin tree shaking, u hajmini atigi bir necha yuz KB ga tushirishi mumkin. Daraxtlarni silkitish Rollup va Webpack bundlerlarida amalga oshiriladi.

     **[⬆ Yuqoriga qaytish](#mundarija)**

153. ### Is it recommended to use eval

     Yo'q, bu xavfsizlik muammosini keltirib chiqaradigan o'zboshimchalik code(ni) ishga tushirishga imkon beradi. Bizga ma'lumki, eval() funksiyasi matnni code sifatida ishlatish uchun ishlatiladi. Ko'pgina hollarda, uni ishlatish shart emas.

     **[⬆ Yuqoriga qaytish](#mundarija)**

154. ### What is a Regular Expression

     Regular expression qidiruv sxemasini tashkil etuvchi belgilar ketma-ketligidir. Matndagi ma'lumotlarni qidirish uchun ushbu qidiruv namunasidan foydalanishingiz mumkin. Bulardan matn qidirish va matnni almashtirish operatsiyalarining barcha turlarini bajarish uchun foydalanish mumkin. Keling, sintaksis formatini ko'rib chiqaylik,

     ```javascript
     /pattern/modifiers;
     ```

     Masalan, katta-kichik harfga sezgir bo'lmagan foydalanuvchi nomi bilan muntazam ifoda yoki qidiruv namunasi:

     ```javascript
     /John/i;
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

155. ### What are the string methods available in Regular expression

     Regular Expression ikkita string usuli mavjud: search() va replace(). Search() usuli moslikni qidirish uchun ifodadan foydalanadi va mos keladigan joyni qaytaradi.

     ```javascript
     var msg = "Hello John";
     var n = msg.search(/John/i); // 6
     ```

     replace() usuli naqsh almashtirilgan o'zgartirilgan string(ni) qaytarish uchun ishlatiladi.

     ```javascript
     var msg = "Hello John";
     var n = msg.replace(/John/i, "Buttler"); // Hello Buttler
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

156. ### What are modifiers in regular expression

     Modifikatorlar katta-kichik harflarni sezmaydigan va global qidiruvlarni amalga oshirish uchun ishlatilishi mumkin. Keling, ba'zi modifikatorlarni sanab o'tamiz,

     | Modifier | Description                                             |
     | -------- | ------------------------------------------------------- |
     | i        | Katta-kichik harflarni sezmaydigan moslikni bajaring                       |
     | g        | Birinchi o'yinda to'xtamasdan, global o'yinni bajaring |
     | m        | Ko'p qatorli moslikni bajaring                              |

     Let's take an example of global modifier,

     ```javascript
     var text = "Learn JS one by one";
     var pattern = /one/g;
     var result = text.match(pattern); // one,one
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

157. ### What are regular expression patterns

     Regular Expressions belgilarni moslashtirish uchun pattern guruhini taqdim etadi. Asosan, ular 3 turga bo'linadi,

     1. **Qavslar:** TBu belgilar qatorini topish uchun ishlatiladi. Misol uchun, quyida ba'zi foydalanish holatlari,
        1. [abc]: Qavslar (a,b,c) orasidagi har qanday belgilarni topish uchun foydalaniladi.
        2. [0-9]: Qavslar orasidagi har qanday raqamni topish uchun ishlatiladi
        3. (a|b): | bilan ajratilgan har qanday muqobillarni topish uchun ishlatiladi
     2. **Meta belgilar:** Bular alohida ma'noga ega bo'lgan belgilar, Masalan, quyida ba'zi foydalanish holatlari,
        1. \\d: Raqamni topish uchun ishlatiladi
        2. \\s: Bo'shliq belgisini topish uchun ishlatiladi
        3. \\b: So'z boshida yoki oxirida moslikni topish uchun ishlatiladi
     3. **Miqdor ko'rsatkichlari:** Bu miqdorlarni aniqlash uchun foydalidir Masalan, quyida ba'zi foydalanish holatlari keltirilgan
        1. n+: Kamida bitta n ni o'z ichiga olgan har qanday satr uchun mosliklarni topish uchun foydalaniladi
        2. n\*: n ning nol yoki undan ortiq takrorlanishini o'z ichiga olgan har qanday string uchun mosliklarni topish uchun foydalaniladi
        3. n?: n ning nol yoki bitta takrorlanishini o'z ichiga olgan har qanday string uchun mosliklarni topish uchun foydalaniladi

     **[⬆ Yuqoriga qaytish](#mundarija)**

158. ### What is a RegExp object

     RegExp ob'ekti oldindan belgilangan xususiyatlar va usullarga ega muntazam ifoda ob'ektidir. Keling, RegExp ob'ektidan oddiy foydalanishni ko'rib chiqaylik,

     ```javascript
     var regexp = new RegExp("\\w+");
     console.log(regexp);
     // expected output: /\w+/
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

159. ### How do you search a string for a pattern

     Naqsh uchun string(ni) qidirish va natijaga qarab rost yoki yolgʻonni qaytarish uchun test() muntazam ifoda usulidan foydalanishingiz mumkin.

     ```javascript
     var pattern = /you/;
     console.log(pattern.test("How are you?")); //true
     ```

     **[⬆ Yuqoriga qaytish](#mundarija)**

160. ### What is the purpose of exec method

     The purpose of exec method is similar to test method but it executes a search for a match in a specified string and returns a result array, or null instead of returning true/false.

     ```javascript
     var pattern = /you/;
     console.log(pattern.exec("How are you?")); //["you", index: 8, input: "How are you?", groups: undefined]
     ```

     **[⬆ Back to Top](#table-of-contents)**

161. ### How do you change the style of a HTML element

     You can change inline style or classname of a HTML element using javascript

     1. **Using style property:** You can modify inline style using style property

     ```javascript
     document.getElementById("title").style.fontSize = "30px";
     ```

     1. **Using ClassName property:** It is easy to modify element class using className property

     ```javascript
     document.getElementById("title").className = "custom-title";
     ```

     **[⬆ Back to Top](#table-of-contents)**

162. ### What would be the result of 1+2+'3'

     The output is going to be `33`. Since `1` and `2` are numeric values, the result of the first two digits is going to be a numeric value `3`. The next digit is a string type value because of that the addition of numeric value `3` and string type value `3` is just going to be a concatenation value `33`.

     **[⬆ Back to Top](#table-of-contents)**

163. ### What is a debugger statement

     The debugger statement invokes any available debugging functionality, such as setting a breakpoint. If no debugging functionality is available, this statement has no effect.
     For example, in the below function a debugger statement has been inserted. So
     execution is paused at the debugger statement just like a breakpoint in the script source.

     ```javascript
     function getProfile() {
       // code goes here
       debugger;
       // code goes here
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

164. ### What is the purpose of breakpoints in debugging

     You can set breakpoints in the javascript code once the debugger statement is executed and the debugger window pops up. At each breakpoint, javascript will stop executing, and let you examine the JavaScript values. After examining values, you can resume the execution of code using the play button.

     **[⬆ Back to Top](#table-of-contents)**

165. ### Can I use reserved words as identifiers

     No, you cannot use the reserved words as variables, labels, object or function names. Let's see one simple example,

     ```javascript
     var else = "hello"; // Uncaught SyntaxError: Unexpected token else
     ```

     **[⬆ Back to Top](#table-of-contents)**

166. ### How do you detect a mobile browser

     You can use regex which returns a true or false value depending on whether or not the user is browsing with a mobile.

     ```javascript
     window.mobilecheck = function () {
       var mobileCheck = false;
       (function (a) {
         if (
           /(android|bb\d+|meego).+mobile|avantgo|bada\/|blackberry|blazer|compal|elaine|fennec|hiptop|iemobile|ip(hone|od)|iris|kindle|lge |maemo|midp|mmp|mobile.+firefox|netfront|opera m(ob|in)i|palm( os)?|phone|p(ixi|re)\/|plucker|pocket|psp|series(4|6)0|symbian|treo|up\.(browser|link)|vodafone|wap|windows ce|xda|xiino/i.test(
             a
           ) ||
           /1207|6310|6590|3gso|4thp|50[1-6]i|770s|802s|a wa|abac|ac(er|oo|s\-)|ai(ko|rn)|al(av|ca|co)|amoi|an(ex|ny|yw)|aptu|ar(ch|go)|as(te|us)|attw|au(di|\-m|r |s )|avan|be(ck|ll|nq)|bi(lb|rd)|bl(ac|az)|br(e|v)w|bumb|bw\-(n|u)|c55\/|capi|ccwa|cdm\-|cell|chtm|cldc|cmd\-|co(mp|nd)|craw|da(it|ll|ng)|dbte|dc\-s|devi|dica|dmob|do(c|p)o|ds(12|\-d)|el(49|ai)|em(l2|ul)|er(ic|k0)|esl8|ez([4-7]0|os|wa|ze)|fetc|fly(\-|_)|g1 u|g560|gene|gf\-5|g\-mo|go(\.w|od)|gr(ad|un)|haie|hcit|hd\-(m|p|t)|hei\-|hi(pt|ta)|hp( i|ip)|hs\-c|ht(c(\-| |_|a|g|p|s|t)|tp)|hu(aw|tc)|i\-(20|go|ma)|i230|iac( |\-|\/)|ibro|idea|ig01|ikom|im1k|inno|ipaq|iris|ja(t|v)a|jbro|jemu|jigs|kddi|keji|kgt( |\/)|klon|kpt |kwc\-|kyo(c|k)|le(no|xi)|lg( g|\/(k|l|u)|50|54|\-[a-w])|libw|lynx|m1\-w|m3ga|m50\/|ma(te|ui|xo)|mc(01|21|ca)|m\-cr|me(rc|ri)|mi(o8|oa|ts)|mmef|mo(01|02|bi|de|do|t(\-| |o|v)|zz)|mt(50|p1|v )|mwbp|mywa|n10[0-2]|n20[2-3]|n30(0|2)|n50(0|2|5)|n7(0(0|1)|10)|ne((c|m)\-|on|tf|wf|wg|wt)|nok(6|i)|nzph|o2im|op(ti|wv)|oran|owg1|p800|pan(a|d|t)|pdxg|pg(13|\-([1-8]|c))|phil|pire|pl(ay|uc)|pn\-2|po(ck|rt|se)|prox|psio|pt\-g|qa\-a|qc(07|12|21|32|60|\-[2-7]|i\-)|qtek|r380|r600|raks|rim9|ro(ve|zo)|s55\/|sa(ge|ma|mm|ms|ny|va)|sc(01|h\-|oo|p\-)|sdk\/|se(c(\-|0|1)|47|mc|nd|ri)|sgh\-|shar|sie(\-|m)|sk\-0|sl(45|id)|sm(al|ar|b3|it|t5)|so(ft|ny)|sp(01|h\-|v\-|v )|sy(01|mb)|t2(18|50)|t6(00|10|18)|ta(gt|lk)|tcl\-|tdg\-|tel(i|m)|tim\-|t\-mo|to(pl|sh)|ts(70|m\-|m3|m5)|tx\-9|up(\.b|g1|si)|utst|v400|v750|veri|vi(rg|te)|vk(40|5[0-3]|\-v)|vm40|voda|vulc|vx(52|53|60|61|70|80|81|83|85|98)|w3c(\-| )|webc|whit|wi(g |nc|nw)|wmlb|wonu|x700|yas\-|your|zeto|zte\-/i.test(
             a.substr(0, 4)
           )
         )
           mobileCheck = true;
       })(navigator.userAgent || navigator.vendor || window.opera);
       return mobileCheck;
     };
     ```

     **[⬆ Back to Top](#table-of-contents)**

167. ### How do you detect a mobile browser without regexp

     You can detect mobile browsers by simply running through a list of devices and checking if the useragent matches anything. This is an alternative solution for RegExp usage,

     ```javascript
     function detectmob() {
       if (
         navigator.userAgent.match(/Android/i) ||
         navigator.userAgent.match(/webOS/i) ||
         navigator.userAgent.match(/iPhone/i) ||
         navigator.userAgent.match(/iPad/i) ||
         navigator.userAgent.match(/iPod/i) ||
         navigator.userAgent.match(/BlackBerry/i) ||
         navigator.userAgent.match(/Windows Phone/i)
       ) {
         return true;
       } else {
         return false;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

168. ### How do you get the image width and height using JS

     You can programmatically get the image and check the dimensions(width and height) using Javascript.

     ```javascript
     var img = new Image();
     img.onload = function () {
       console.log(this.width + "x" + this.height);
     };
     img.src = "http://www.google.com/intl/en_ALL/images/logo.gif";
     ```

     **[⬆ Back to Top](#table-of-contents)**

169. ### How do you make synchronous HTTP request

     Browsers provide an XMLHttpRequest object which can be used to make synchronous HTTP requests from JavaScript

     ```javascript
     function httpGet(theUrl) {
       var xmlHttpReq = new XMLHttpRequest();
       xmlHttpReq.open("GET", theUrl, false); // false for synchronous request
       xmlHttpReq.send(null);
       return xmlHttpReq.responseText;
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

170. ### How do you make asynchronous HTTP request

     Browsers provide an XMLHttpRequest object which can be used to make asynchronous HTTP requests from JavaScript by passing the 3rd parameter as true.

     ```javascript
     function httpGetAsync(theUrl, callback) {
       var xmlHttpReq = new XMLHttpRequest();
       xmlHttpReq.onreadystatechange = function () {
         if (xmlHttpReq.readyState == 4 && xmlHttpReq.status == 200)
           callback(xmlHttpReq.responseText);
       };
       xmlHttp.open("GET", theUrl, true); // true for asynchronous
       xmlHttp.send(null);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

171. ### How do you convert date to another timezone in javascript

     You can use the toLocaleString() method to convert dates in one timezone to another. For example, let's convert current date to British English timezone as below,

     ```javascript
     console.log(event.toLocaleString("en-GB", { timeZone: "UTC" })); //29/06/2019, 09:56:00
     ```

     **[⬆ Back to Top](#table-of-contents)**

172. ### What are the properties used to get size of window

     You can use innerWidth, innerHeight, clientWidth, clientHeight properties of windows, document element and document body objects to find the size of a window. Let's use them combination of these properties to calculate the size of a window or document,

     ```javascript
     var width =
       window.innerWidth ||
       document.documentElement.clientWidth ||
       document.body.clientWidth;

     var height =
       window.innerHeight ||
       document.documentElement.clientHeight ||
       document.body.clientHeight;
     ```

     **[⬆ Back to Top](#table-of-contents)**

173. ### What is a conditional operator in javascript

     The conditional (ternary) operator is the only JavaScript operator that takes three operands which acts as a shortcut for if statements.

     ```javascript
     var isAuthenticated = false;
     console.log(
       isAuthenticated ? "Hello, welcome" : "Sorry, you are not authenticated"
     ); //Sorry, you are not authenticated
     ```

     **[⬆ Back to Top](#table-of-contents)**

174. ### Can you apply chaining on conditional operator

     Yes, you can apply chaining on conditional operators similar to if … else if … else if … else chain. The syntax is going to be as below,

     ```javascript
     function traceValue(someParam) {
       return condition1
         ? value1
         : condition2
         ? value2
         : condition3
         ? value3
         : value4;
     }

     // The above conditional operator is equivalent to:

     function traceValue(someParam) {
       if (condition1) {
         return value1;
       } else if (condition2) {
         return value2;
       } else if (condition3) {
         return value3;
       } else {
         return value4;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

175. ### What are the ways to execute javascript after page load

     You can execute javascript after page load in many different ways,

     1. **window.onload:**

     ```javascript
     window.onload = function ...
     ```

     1. **document.onload:**

     ```javascript
     document.onload = function ...
     ```

     1. **body onload:**

     ```javascript
     <body onload="script();">
     ```

     **[⬆ Back to Top](#table-of-contents)**

176. ### What is the difference between proto and prototype

     The `__proto__` object is the actual object that is used in the lookup chain to resolve methods, etc. Whereas `prototype` is the object that is used to build `__proto__` when you create an object with new

     ```javascript
     new Employee().__proto__ === Employee.prototype;
     new Employee().prototype === undefined;
     ```

     **[⬆ Back to Top](#table-of-contents)**

177. ### Give an example where do you really need semicolon

     It is recommended to use semicolons after every statement in JavaScript. For example, in the below case it throws an error ".. is not a function" at runtime due to missing semicolon.

     ```javascript
     // define a function
     var fn = (function () {
       //...
     })(
       // semicolon missing at this line

       // then execute some code inside a closure
       function () {
         //...
       }
     )();
     ```

     and it will be interpreted as

     ```javascript
     var fn = (function () {
       //...
     })(function () {
       //...
     })();
     ```

     In this case, we are passing the second function as an argument to the first function and then trying to call the result of the first function call as a function. Hence, the second function will fail with a "... is not a function" error at runtime.

     **[⬆ Back to Top](#table-of-contents)**

178. ### What is a freeze method

     The **freeze()** method is used to freeze an object. Freezing an object does not allow adding new properties to an object,prevents from removing and prevents changing the enumerability, configurability, or writability of existing properties. i.e, It returns the passed object and does not create a frozen copy.

     ```javascript
     const obj = {
       prop: 100,
     };

     Object.freeze(obj);
     obj.prop = 200; // Throws an error in strict mode

     console.log(obj.prop); //100
     ```

     Remember freezing is only applied to the top-level properties in objects but not for nested objects.
     For example, let's try to freeze user object which has employment details as nested object and observe that details have been changed.

     ```javascript
     const user = {
       name: "John",
       employment: {
         department: "IT",
       },
     };

     Object.freeze(user);
     user.employment.department = "HR";
     ```

     **Note:** It causes a TypeError if the argument passed is not an object.

     **[⬆ Back to Top](#table-of-contents)**

179. ### What is the purpose of freeze method

     Below are the main benefits of using freeze method,

     1. It is used for freezing objects and arrays.
     2. It is used to make an object immutable.

     **[⬆ Back to Top](#table-of-contents)**

180. ### Why do I need to use freeze method

     In the Object-oriented paradigm, an existing API contains certain elements that are not intended to be extended, modified, or re-used outside of their current context. Hence it works as the `final` keyword which is used in various languages.

     **[⬆ Back to Top](#table-of-contents)**

181. ### How do you detect a browser language preference

     You can use navigator object to detect a browser language preference as below,

     ```javascript
     var language =
       (navigator.languages && navigator.languages[0]) || // Chrome / Firefox
       navigator.language || // All browsers
       navigator.userLanguage; // IE <= 10

     console.log(language);
     ```

     **[⬆ Back to Top](#table-of-contents)**

182. ### How to convert string to title case with javascript

     Title case means that the first letter of each word is capitalized. You can convert a string to title case using the below function,

     ```javascript
     function toTitleCase(str) {
       return str.replace(/\w\S*/g, function (txt) {
         return txt.charAt(0).toUpperCase() + txt.substr(1).toLowerCase();
       });
     }
     toTitleCase("good morning john"); // Good Morning John
     ```

     **[⬆ Back to Top](#table-of-contents)**

183. ### How do you detect javascript disabled in the page

     You can use the `<noscript>` tag to detect javascript disabled or not. The code block inside `<noscript>` gets executed when JavaScript is disabled, and is typically used to display alternative content when the page generated in JavaScript.

     ```javascript
     <script type="javascript">
         // JS related code goes here
     </script>
     <noscript>
         <a href="next_page.html?noJS=true">JavaScript is disabled in the page. Please click Next Page</a>
     </noscript>
     ```

     **[⬆ Back to Top](#table-of-contents)**

184. ### What are various operators supported by javascript

     An operator is capable of manipulating(mathematical and logical computations) a certain value or operand. There are various operators supported by JavaScript as below,

     1. **Arithmetic Operators:** Includes + (Addition),– (Subtraction), \* (Multiplication), / (Division), % (Modulus), + + (Increment) and – – (Decrement)
     2. **Comparison Operators:** Includes = =(Equal),!= (Not Equal), ===(Equal with type), > (Greater than),> = (Greater than or Equal to),< (Less than),<= (Less than or Equal to)
     3. **Logical Operators:** Includes &&(Logical AND),||(Logical OR),!(Logical NOT)
     4. **Assignment Operators:** Includes = (Assignment Operator), += (Add and Assignment Operator), – = (Subtract and Assignment Operator), \*= (Multiply and Assignment), /= (Divide and Assignment), %= (Modules and Assignment)
     5. **Ternary Operators:** It includes conditional(: ?) Operator
     6. **typeof Operator:** It uses to find type of variable. The syntax looks like `typeof variable`

     **[⬆ Back to Top](#table-of-contents)**

185. ### What is a rest parameter

     Rest parameter is an improved way to handle function parameters which allows us to represent an indefinite number of arguments as an array. The syntax would be as below,

     ```javascript
     function f(a, b, ...theArgs) {
       // ...
     }
     ```

     For example, let's take a sum example to calculate on dynamic number of parameters,

     ```javascript
     function total(…args){
     let sum = 0;
     for(let i of args){
     sum+=i;
     }
     return sum;
     }
     console.log(fun(1,2)); //3
     console.log(fun(1,2,3)); //6
     console.log(fun(1,2,3,4)); //13
     console.log(fun(1,2,3,4,5)); //15
     ```

     **Note:** Rest parameter is added in ES2015 or ES6

     **[⬆ Back to Top](#table-of-contents)**

186. ### What happens if you do not use rest parameter as a last argument

     The rest parameter should be the last argument, as its job is to collect all the remaining arguments into an array. For example, if you define a function like below it doesn’t make any sense and will throw an error.

     ```javascript
     function someFunc(a,…b,c){
     //You code goes here
     return;
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

187. ### What are the bitwise operators available in javascript

     Below are the list of bitwise logical operators used in JavaScript

     1. Bitwise AND ( & )
     2. Bitwise OR ( | )
     3. Bitwise XOR ( ^ )
     4. Bitwise NOT ( ~ )
     5. Left Shift ( << )
     6. Sign Propagating Right Shift ( >> )
     7. Zero fill Right Shift ( >>> )

     **[⬆ Back to Top](#table-of-contents)**

188. ### What is a spread operator

     Spread operator allows iterables( arrays / objects / strings ) to be expanded into single arguments/elements. Let's take an example to see this behavior,

     ```javascript
     function calculateSum(x, y, z) {
       return x + y + z;
     }

     const numbers = [1, 2, 3];

     console.log(calculateSum(...numbers)); // 6
     ```

     **[⬆ Back to Top](#table-of-contents)**

189. ### How do you determine whether object is frozen or not

     Object.isFrozen() method is used to determine if an object is frozen or not.An object is frozen if all of the below conditions hold true,

     1. If it is not extensible.
     2. If all of its properties are non-configurable.
     3. If all its data properties are non-writable.
        The usage is going to be as follows,

     ```javascript
     const object = {
       property: "Welcome JS world",
     };
     Object.freeze(object);
     console.log(Object.isFrozen(object));
     ```

     **[⬆ Back to Top](#table-of-contents)**

190. ### How do you determine two values same or not using object

     The Object.is() method determines whether two values are the same value. For example, the usage with different types of values would be,

     ```javascript
     Object.is("hello", "hello"); // true
     Object.is(window, window); // true
     Object.is([], []); // false
     ```

     Two values are the same if one of the following holds:

     1. both undefined
     2. both null
     3. both true or both false
     4. both strings of the same length with the same characters in the same order
     5. both the same object (means both object have same reference)
     6. both numbers and
        both +0
        both -0
        both NaN
        both non-zero and both not NaN and both have the same value.

     **[⬆ Back to Top](#mundarija)**

191. ### What is the purpose of using object is method

     Some of the applications of Object's `is` method are follows,

     1. It is used for comparison of two strings.
     2. It is used for comparison of two numbers.
     3. It is used for comparing the polarity of two numbers.
     4. It is used for comparison of two objects.

     **[⬆ Back to Top](#table-of-contents)**

192. ### How do you copy properties from one object to other

     You can use the Object.assign() method which is used to copy the values and properties from one or more source objects to a target object. It returns the target object which has properties and values copied from the target object. The syntax would be as below,

     ```javascript
     Object.assign(target, ...sources);
     ```

     Let's take example with one source and one target object,

     ```javascript
     const target = { a: 1, b: 2 };
     const source = { b: 3, c: 4 };

     const returnedTarget = Object.assign(target, source);

     console.log(target); // { a: 1, b: 3, c: 4 }

     console.log(returnedTarget); // { a: 1, b: 3, c: 4 }
     ```

     As observed in the above code, there is a common property(`b`) from source to target so it's value has been overwritten.

     **[⬆ Back to Top](#table-of-contents)**

193. ### What are the applications of assign method

     Below are the some of main applications of Object.assign() method,

     1. It is used for cloning an object.
     2. It is used to merge objects with the same properties.

     **[⬆ Back to Top](#table-of-contents)**

194. ### What is a proxy object

     The Proxy object is used to define custom behavior for fundamental operations such as property lookup, assignment, enumeration, function invocation, etc. The syntax would be as follows,

     ```javascript
     var p = new Proxy(target, handler);
     ```

     Let's take an example of proxy object,

     ```javascript
     var handler = {
       get: function (obj, prop) {
         return prop in obj ? obj[prop] : 100;
       },
     };

     var p = new Proxy({}, handler);
     p.a = 10;
     p.b = null;

     console.log(p.a, p.b); // 10, null
     console.log("c" in p, p.c); // false, 100
     ```

     In the above code, it uses `get` handler which define the behavior of the proxy when an operation is performed on it

     **[⬆ Back to Top](#table-of-contents)**

195. ### What is the purpose of seal method

     The **Object.seal()** method is used to seal an object, by preventing new properties from being added to it and marking all existing properties as non-configurable. But values of present properties can still be changed as long as they are writable. Let's see the below example to understand more about seal() method

     ```javascript
     const object = {
       property: "Welcome JS world",
     };
     Object.seal(object);
     object.property = "Welcome to object world";
     console.log(Object.isSealed(object)); // true
     delete object.property; // You cannot delete when sealed
     console.log(object.property); //Welcome to object world
     ```

     **[⬆ Back to Top](#table-of-contents)**

196. ### What are the applications of seal method

     Below are the main applications of Object.seal() method,

     1. It is used for sealing objects and arrays.
     2. It is used to make an object immutable.

     **[⬆ Back to Top](#table-of-contents)**

197. ### What are the differences between freeze and seal methods

     If an object is frozen using the Object.freeze() method then its properties become immutable and no changes can be made in them whereas if an object is sealed using the Object.seal() method then the changes can be made in the existing properties of the object.

     **[⬆ Back to Top](#table-of-contents)**

198. ### How do you determine if an object is sealed or not

     The Object.isSealed() method is used to determine if an object is sealed or not. An object is sealed if all of the below conditions hold true

     1. If it is not extensible.
     2. If all of its properties are non-configurable.
     3. If it is not removable (but not necessarily non-writable).
        Let's see it in the action

     ```javascript
     const object = {
       property: "Hello, Good morning",
     };

     Object.seal(object); // Using seal() method to seal the object

     console.log(Object.isSealed(object)); // checking whether the object is sealed or not
     ```

     **[⬆ Back to Top](#table-of-contents)**

199. ### How do you get enumerable key and value pairs

     The Object.entries() method is used to return an array of a given object's own enumerable string-keyed property [key, value] pairs, in the same order as that provided by a for...in loop. Let's see the functionality of object.entries() method in an example,

     ```javascript
     const object = {
       a: "Good morning",
       b: 100,
     };

     for (let [key, value] of Object.entries(object)) {
       console.log(`${key}: ${value}`); // a: 'Good morning'
       // b: 100
     }
     ```

     **Note:** The order is not guaranteed as object defined.

     **[⬆ Back to Top](#table-of-contents)**

200. ### What is the main difference between Object.values and Object.entries method

     The Object.values() method's behavior is similar to Object.entries() method but it returns an array of values instead [key,value] pairs.

     ```javascript
     const object = {
       a: "Good morning",
       b: 100,
     };

     for (let value of Object.values(object)) {
       console.log(`${value}`); // 'Good morning'
       100;
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

### Coding Exercise

#### 1. Quyidagi code(dan) nima chiqadi

```javascript
var car = new Vehicle("Honda", "white", "2010", "UK");
console.log(car);

function Vehicle(model, color, year, country) {
  this.model = model;
  this.color = color;
  this.year = year;
  this.country = country;
}
```

- 1: Undefined
- 2: ReferenceError
- 3: null
- 4: {model: "Honda", color: "white", year: "2010", country: "UK"}

<details><summary><b>Answer</b></summary>
<p>

##### Javob: 4

Function declarations har qanday o'zgaruvchiga o'xshash tarzda ko'tariladi. Shunday qilib, `Vehicle` function declaration joylashtirish hech qanday farq qilmaydi.

</p>
</details>

---

**[⬆ Yuqoriga qaytish](#mundarija)**

#### 2. What is the output of below code
