# Getting into HTML 🙌

เราลองมาเริ่มสร้างของบนหน้าเว็บกันดีกว่า

```html
<h1>Welcome to CODECAMP #8</h1>
```

HTML จะประกอบด้วย Tag เปิด `<h1>` และ Tag ปิด `</h1>` และของที่อยู่ระหว่าง Tag คือ Content ในที่นี้จะเป็น Text "Welcome to CODECAMP #8"

<br><hr><br>

## Playing With Tags 🧑‍💻

‣ **Heading Tag** - เป็น Tag ที่แสดงข้อความที่เป็นหัวข้อใหญ่ ๆ บนหน้าเว็บ

```html
<h1>Codecamp is so good !</h1>
<h2>Codecamp is so good !</h2>
<h3>Codecamp is so good !</h3>
<h4>Codecamp is so good !</h4>
<h5>Codecamp is so good !</h5>
<h6>Codecamp is so good !</h6>
```

‣ **Paragraph Tag** - เป็น Tag ที่แสดง paragraph บนหน้าเว็บ

```html
<p>
  แอบมองเธอเรื่อยไปให้ไกลแค่ไหนเพียงใดก็ไม่เป็นไร
  ฉันไม่ได้แล้วล่ะนี่คือสัญญาจากฉัน ไม่ต้องไปอยู่เพลงๆมิ้งมุ้งมิ้งเป็นใครชอบฟัง
  อย่าได้รับรู้เวลาที่พึ่งพิงเขียนลำพังคนนี้ช่างงดงามวิเศษแค่ไหน
  จะสยายผมหรือว่ามัดผม เธอนะเพื่อนเราไม่นานก็โตกันไป
</p>
```

ขอบคุณ [bangkokipsum.app](https://bangkokipsum.app/) สำหรับข้อความ paragraph

‣ **span Tag** - เป็น Tag ที่สร้างกล่องที่อยู่บรรทัดเดียวกันกับ Element ตัวอื่น ๆ

```html
<p>
  แอบมองเธอเรื่อยไปให้ไกลแค่ไหนเพียงใดก็ไม่เป็นไร
  ฉันไม่ได้แล้วล่ะนี่คือสัญญาจากฉัน
  <span>ไม่ต้องไปอยู่เพลงๆมิ้งมุ้งมิ้งเป็นใครชอบฟัง</span>
  อย่าได้รับรู้เวลาที่พึ่งพิงเขียนลำพังคนนี้ช่างงดงามวิเศษแค่ไหน
  จะสยายผมหรือว่ามัดผม เธอนะเพื่อนเราไม่นานก็โตกันไป
</p>
```

‣ **a Tag** - เป็น Tag ที่สร้าง Link ไปยังหน้าเว็บอื่น ๆ

```html
<a href="https://google.com">Link to GOOGLE</a>
```

‣ **ol/ul และ li Tag** - เป็น Tag ที่สร้าง List ของข้อมูล

**ul** (**U**norder **L**ist) เป็น Tag ที่สร้าง List ของข้อมูลแบบไม่กำหนดลำดับ แต่ละ **li** (**L**ist **I**tem) จะมี Bullet อยู่ข้างหน้า

```html
<ul>
  <li>Home</li>
  <li>Products</li>
  <li>Customer Support</li>
  <li>About US</li>
</ul>
```

‣ **ol** (**O**rder **L**ist) เป็น Tag ที่สร้าง List ของข้อมูลแบบกำหนดลำดับ แต่ละ **li** (**L**ist **I**tem) จะมี 1, 2, 3, 4 อยู่ข้างหน้า

```html
<ol>
  <li>Home</li>
  <li>Products</li>
  <li>Customer Support</li>
  <li>About US</li>
</ol>
```

🌟 ‣ **div** เป็น Tag ที่สร้างกล่องเปล่า ๆ ไว้ใช้รวบสิ่งของต่าง ๆ ไว้ข้างในกล่อง

```html
<div>
  <div>Post: Coding is easy 😻</div>
  <div>
    ที่เธอยิ่งไกลห่างไปสู่ดินแดนแสนวิเศษกายและคว้าให้ลืม
    ยังอยู่ตรงนี้และหวังดีที่สุดก็เต้นไปในความฝันให้เธอ
    จังหวะเพลงปลุกเร้าชีวิตข้างหน้าอยู่ในใจ
    จะลองไขว่และอยู่ในใจแล้วสิเออลิ้นเราต้องแก้ไข
    ก็เพื่อต้องสายแน่เลยไปอย่างนั้น
    ถ้าหัวใจบอกในใจให้เธอเสนอก็เร็วไปเลยทำอะไรกัน สู่ความสุขและดูเซ็กซี่ไม่ช้า
  </div>
</div>
```

‣ **button** เป็น Tag ที่สร้างปุ่มกด

```html
<button>Submit</button> <button>Login</button>
```

‣ **img** เป็น Tag ที่แสดงรูปภาพ

- attribute href เป็นตัวบอกว่าเราจะเอารูปมาจากไหน สามารใส่ได้ทั้ง file path บนเครื่องเรา หรือ url รูปภาพบน web

- 🌟 alt attribute เป็น attribute ที่บรรยายเวลารูปภาพโหลดไม่ขึ้น และมีผลดีเกี่ยวกับเรื่องของ **Accessibility** เวลา Screen reader มาอ่านรูปมันจะอ่านตามข้อความที่เราใส่ไว้ใน alt attribute เดี๋ยวส่วนนี้เราจะพูดถึงกันอีกต่อ ๆ ไป

```html
<img href="https://placedog.net/640/480?random" alt="cute dog" />
```

‣ **input** เป็น Tag ที่เอาไว้ใช้รับข้อมูล จากผู้ใช้งาน

```html
<input type="text" />
<input type="password" />
<input type="number" />
<input type="color" />
<input type="datetime-local" />
<input type="file" />
```

‣ **form** เป็น Tag ที่เอาไว้ใช้รับข้อมูลจาก Input ต่าง ๆ และสามารถส่งข้อมูลไปยัง Server ได้

```html
<form>
  <input type="text" />
  <button type="submit">Submit</button>
</form>
```

‣ **table** เป็น Tag ที่เอาไว้ใช้สร้างตาราง

```html
<table border="1">
  <tr>
    <td>1</td>
    <td>2</td>
  </tr>
</table>
```

<br><hr><br>

<div style="display: flex; justify-content: space-between;">
  <a href="https://github.com/napatwongchr/intro-to-html/blob/main/lessons/1-web-development-pillars.md"><< ไปก่อนหน้า</a>
  <a href="https://github.com/napatwongchr/intro-to-html/blob/main/lessons/4-attributes.md">หน้าต่อไป >></a>
</div>
