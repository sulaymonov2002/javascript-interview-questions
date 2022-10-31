# JavaScript Interview Questions & Answers

> Agar sizga loyiha yoqsa :star: bosing. Texnik yangilanishlar uchun meni [@ssamir_20 Twitter](https://twitter.com/ssamir_20) <= || => [@ssamir_20 Instagram](https://www.instagram.com/ssamir_20/) kuzatib boring.

Maxsus savollarni kodlash uchun [Kodlash mashqlariga](#coding-exercise) o'ting.

## PDF/Epub formatlarini yuklab oling

Siz ushbu reponing PDF va Epub versiyasini [amallar yorlig'idagi](https://github.com/sulaymonov2002/javascript-interview-questions) so'nggi ishga tushirishdan yuklab olishingiz mumkin.

---

### Mundarija

| No. | Savollar                                                                                                                                             |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [JavaScript-da ob'ektlarni yaratishning qanday usullari bor ?](#what-are-the-possible-ways-to-create-objects-in-javascript)                          |
| 2   | [Prototype chain nima ?](#what-is-a-prototype-chain)                                                                                                |
| 3   | [Call, Apply va Bind orasidagi farq nima ?](#what-is-the-difference-between-call-apply-and-bind)                                                     |
| 4   | [JSON nima va uning umumiy operatsiyalari](#what-is-json-and-its-common-operations)                                                                  |
| 5   | [Massiv slice usulidan maqsad nima ?](#what-is-the-purpose-of-the-array-slice-method)                                                                |
| 6   | [Massivni splice usulining maqsadi nima ?](#what-is-the-purpose-of-the-array-splice-method)                                                          |
| 7   | [Slice va splice o'rtasidagi farq nima ?](#what-is-the-difference-between-slice-and-splice)                                                          |
| 8   | [Ob'ekt va Map qanday taqqoslaysiz](#how-do-you-compare-object-and-map)                                                                              |
| 9   | [== va === operatorlarning farqi nimada ?](#what-is-the-difference-between--and--operators)                                                          |
| 10  | [lambda yoki arrow function nima ?](#what-are-lambda-or-arrow-functions)                                                                             |
| 11  | [Birinchi class function nima ?](#what-is-a-first-class-function)                                                                                    |
| 12  | [Birinchi order function nima ?](#what-is-a-first-order-function)                                                                                    |
| 13  | [Yuqori tartibli funksiya nima ?](#what-is-a-higher-order-function)                                                                                  |
| 14  | [unary function nima ?](#what-is-a-unary-function)                                                                                                   |
| 15  | [currying function nima ?](#what-is-the-currying-function)                                                                                           |
| 16  | [pure function nima ?](#what-is-a-pure-function)                                                                                                     |
| 17  | [let kalit so'zining maqsadi nima ?](#what-is-the-purpose-of-the-let-keyword)                                                                        |
| 18  | [let va var o'rtasidagi farq nima ?](#what-is-the-difference-between-let-and-var)                                                                    |
| 19  | [kalit so'zi sifatida let nomini tanlashning sababi nimada ?](#what-is-the-reason-to-choose-the-name-let-as-a-keyword)                               |
| 20  | [swtich blockdagi o'zgarishlarni qanday qilib xatosiz qayta e'lon qilish mumkin ?](#how-do-you-redeclare-variables-in-switch-block-without-an-error) |
| 21  | [Temporal Dead Zone nima ?](#what-is-the-temporal-dead-zone)                                                                                         |
| 22  | [IIFE(darhol chaqiriladigan funksiya ifodasi)nima ?](#what-is-iifeimmediately-invoked-function-expression)                                           |
| 23  | [JavaScript-da URL-manzilini decode yoki code lash mumkin ?](#how-do-you-decode-or-encode-a-url-in-javascript)                                       |
| 24  | [Memoization nima ?](#what-is-memoization)                                                                                                           |
| 25  | [Hoisting nima ?](#what-is-hoisting)                                                                                                                 |
| 26  | [ES6 da qanday sinflar mavjud ?](#what-are-classes-in-es6)                                                                                           |
| 27  | [Closures nima ?](#what-are-closures)                                                                                                                |
| 28  | [Modullar nima ?](#what-are-modules)                                                                                                                 |
| 29  | [Nima uchun sizga modullar kerak ?](#why-do-you-need-modules)                                                                                        |
| 30  | [JavaScriptda scope nima ?](#what-is-scope-in-javascript)                                                                                            |
| 31  | [Service worker nima ?](#what-is-a-service-worker)                                                                                                   |
| 32  | [Service worker yordamida DOMni qanday boshqarish mumkin ?](#how-do-you-manipulate-dom-using-a-service-worker)                                       |
| 33  | [Service worker ni qayta ishga tushirishda ma'lumotdan qanday foydalanasiz ?](#how-do-you-reuse-information-across-service-worker-restarts)          |
| 34  | [IndexedDB nima ?](#what-is-indexeddb)                                                                                                               |
| 35  | [Web storage nima ?](#what-is-web-storage)                                                                                                           |
| 36  | [Post xabari nima ?](#what-is-a-post-message)                                                                                                        |
| 37  | [cookie nima ?](#what-is-a-cookie)                                                                                                                   |
| 38  | [Cookie nima uchun kerak ?](#why-do-you-need-a-cookie)                                                                                               |
| 39  | [Cookie-da qanday variantlar mavjud ?](#what-are-the-options-in-a-cookie)                                                                            |
| 40  | [Cookie faylini qanday o'chirish mumkin ?](#how-do-you-delete-a-cookie)                                                                              |
| 41  | [Cookie, local storage va session storage o'rtasidagi farqlar qanday ?](#What-are-the-differences-between-cookie-local-storage-and-session-storage)  |
| 42  | [localStorage va sessionStorage o'rtasidagi asosiy farq nima ?](#what-is-the-main-difference-between-localstorage-and-sessionstorage)                |
| 43  | [Veb-xotiraga qanday kirish mumkin ?](#how-do-you-access-web-storage)                                                                                |
| 44  | [session storage qanday usullar mavjud ?](#what-are-the-methods-available-on-session-storage)                                                        |
| 45  | [storage event nima va uning event handler ?](#what-is-a-storage-event-and-its-event-handler)                                                        |
| 46  | [Nima uchun sizga web storage kerak ?](#why-do-you-need-web-storage)                                                                                 |
| 47  | [Web storage browser yordamini qanday tekshirish mumkin ?](#how-do-you-check-web-storage-browser-support)                                            |
| 48  | [Web workers browser qo'llab-quvvatlashini qanday tekshirish mumkin ?](#how-do-you-check-web-workers-browser-support)                                |
| 49  | [Web worker ga misol keltiring ?](#give-an-example-of-a-web-worker)                                                                                  |
| 50  | [DOM-da web worker larning cheklovlari qanday ?](#what-are-the-restrictions-of-web-workers-on-dom)                                                   |

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
