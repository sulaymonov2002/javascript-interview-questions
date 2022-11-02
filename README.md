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
| 2   | [Prototype chain nima ?](#what-is-a-prototype-chain)                                                                                                 |
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
