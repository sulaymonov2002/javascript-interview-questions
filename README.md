# JavaScript Interview Questions & Answers

> Agar sizga loyiha yoqsa :star: bosing. Texnik yangilanishlar uchun meni [@ssamir_20 Twitter](https://twitter.com/ssamir_20) <= || => [@ssamir_20 Instagram](https://www.instagram.com/ssamir_20/) kuzatib boring.

Maxsus savollarni kodlash uchun [Kodlash mashqlariga](#coding-exercise) o'ting.

## PDF/Epub formatlarini yuklab oling

Siz ushbu reponing PDF va Epub versiyasini [amallar yorlig'idagi](https://github.com/sulaymonov2002/javascript-interview-questions) so'nggi ishga tushirishdan yuklab olishingiz mumkin.

---

### Mundarija

| No. | Savollar                                                                                                                    |
| --- | --------------------------------------------------------------------------------------------------------------------------- |
| 1   | [JavaScript-da ob'ektlarni yaratishning qanday usullari bor ?](#what-are-the-possible-ways-to-create-objects-in-javascript)                 |
| 2   | [Prototip zanjiri nima ?](#what-is-a-prototype-chain)                                                                             |
| 3   | [Call, Apply va Bind orasidagi farq nima ?](#what-is-the-difference-between-call-apply-and-bind)                        |
| 4   | [JSON nima va uning umumiy operatsiyalari](#what-is-json-and-its-common-operations)                                          |
| 5   | [Massiv slice usulidan maqsad nima ?](#what-is-the-purpose-of-the-array-slice-method)                                                                   | 
| 6   | [Massivni splice usulining maqsadi nima ?](#what-is-the-purpose-of-the-array-splice-method)                                                                 |
| 7   | [Slice va splice o'rtasidagi farq nima ?](#what-is-the-difference-between-slice-and-splice)                                                               |
| 8   | [Ob'ekt va Map qanday taqqoslaysiz](#how-do-you-compare-object-and-map)                                                                                           |
| 9   | [== va === operatorlarning farqi nimada ?](#what-is-the-difference-between--and--operators)                                                            |
| 10   | [lambda yoki arrow function nima ?](#what-are-lambda-or-arrow-functions)                                                                                         |
| 11   | [Birinchi class function nima ?](#what-is-a-first-class-function)                                                                                                 |
| 12   | [Birinchi order function nima ?](#what-is-a-first-order-function)                                                                                                 |
| 13   | [Yuqori tartibli funksiya nima ?](#what-is-a-higher-order-function)                                                                                               |
| 14   | [unary function nima ?](#what-is-a-unary-function)                                                                                                             |
| 15   | [currying function nima ?](#what-is-the-currying-function)                                                                                                   |
| 16   | [pure function nima ?](#what-is-a-pure-function)                                                                                                               |
| 17   | [let kalit so'zining maqsadi nima ?](#what-is-the-purpose-of-the-let-keyword)                                                                                 |
| 18   | [let va var o'rtasidagi farq nima ?](#what-is-the-difference-between-let-and-var)                                                                         |
| 19   | [kalit so'zi sifatida let nomini tanlashning sababi nimada ?](#what-is-the-reason-to-choose-the-name-let-as-a-keyword)                                                 |
| 20   | [swtich blockdagi o'zgarishlarni qanday qilib xatosiz qayta e'lon qilish mumkin ?](#how-do-you-redeclare-variables-in-switch-block-without-an-error)                               |
| 21   | [Temporal Dead Zone nima ?](#what-is-the-temporal-dead-zone)                                                                                                 |
| 22   | [IIFE(darhol chaqiriladigan funksiya ifodasi)nima ?](#what-is-iifeimmediately-invoked-function-expression)                                                     |
| 23   | [JavaScript-da URL-manzilini decode yoki code lash mumkin ?](#how-do-you-decode-or-encode-a-url-in-javascript)                                                              |
| 24   | [Memoization nima ?](#what-is-memoization)                                                                                                                       |
| 25   | [Hoisting nima ?](#what-is-hoisting)                                                                                                                             |
| 26   | [ES6 da qanday sinflar mavjud ?](#what-are-classes-in-es6)                                                                                                               |
| 27   | [Closures nima ?](#what-are-closures)                                                                                                                           |
| 28   | [Modullar nima ?](#what-are-modules)                                                                                                                             |
| 29   | [Nima uchun sizga modullar kerak ?](#why-do-you-need-modules)                                                                                                               |
| 30   | [JavaScriptda scope nima ?](#what-is-scope-in-javascript)                                                                                                       |
| 31   | [Service worker nima ?](#what-is-a-service-worker)                                                                                                             |
| 32   | [Service worker yordamida DOMni qanday boshqarish mumkin ?](#how-do-you-manipulate-dom-using-a-service-worker)                                                             |
| 33   | [Service worker ni qayta ishga tushirishda ma'lumotdan qanday foydalanasiz ?](#how-do-you-reuse-information-across-service-worker-restarts)                                       |
| 34   | [IndexedDB nima ?](#what-is-indexeddb)                                                                                                                           |
| 35   | [Web storage nima ?](#what-is-web-storage)                                                                                                                       |
| 36   | [Post xabari nima ?](#what-is-a-post-message)                                                                                                                 |
| 37   | [cookie nima ?](#what-is-a-cookie)                                                                                                                             |
| 38   | [Cookie nima uchun kerak ?](#why-do-you-need-a-cookie)                                                                                                             |
| 39   | [Cookie-da qanday variantlar mavjud ?](#what-are-the-options-in-a-cookie)                                                                                             |
| 40   | [Cookie faylini qanday o'chirish mumkin ?](#how-do-you-delete-a-cookie)                                                                                                         |
