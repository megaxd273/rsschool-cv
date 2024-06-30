# RSSCHOOL-CV

---

1. Full Name:

   - Stanislau Kazlou

2. Contacts:

   - [telegram](https://t.me/megaxd274)
   - [mail](kazemirova.l@gmail.com)
   - [discord](https://discordapp.com/users/466573332196884481/)

3. About me:
   Having completed university a year ago with a degree in Software Engineering, I initially struggled with my studies due to a lack of interest. Despite this, I managed to graduate and secure a job as a system administrator in an office environment.

   Since starting this role, I have come to realize that I am more passionate about programming. The appeal of remote work and the opportunity to tackle interesting challenges in programming are far more engaging to me than the routine tasks of system administration. This newfound understanding is guiding me towards a career shift to become a programmer.

4. Skills:

   > HTML, CSS, JS, REACT, NODE JS, GIT, FIGMA, PHP.

5. Code example:

   RGB to hex conversion 5 kyu:

   ```
    function fixRgb(number) {
     return (number === 0 ? '00' : number < 0 ? '00' : number > 255 ? 255 : number)
         .toString(16)
         .toUpperCase();
     }
     function rgb(r, g, b) {
     let arr = [];
     for (const arg of arguments) {
         arr.push(fixRgb(arg));
     }
     console.log(arr);
     return arr
         .map((el) => {
         if (el.length === 1) {
             el = '0' + el;
         }
         return el;
         })
         .join('');
     }
   ```

6. [Diploma Project](https://github.com/megaxd273/dip)

7. Education:

   - BNTU Faculty of Information Technologies and Robotics,
     Department of Software Engineering and Information Technologies (2019-2023)

   - Participated in rsschool stage 1 and node js course but did't make it till the end.

8. Languages:
   - Russian(native)
   - English(~B1-B2)
