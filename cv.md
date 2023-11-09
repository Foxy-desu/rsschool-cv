# Alexandra Orliuk 

### Contact information:
- :sparkle: **Telegram:** \@Pinkalsthedeer;
- :sparkle: **Phone:** +7 989 989 898 96;
- :sparkle: **Discord:**  \@Foxy-desu;
- :sparkle: [**GitHub**](https://github.com/Foxy-desu)
- :sparkle: [**LinkedIn**](https://ru.linkedin.com/in/alexandra-orliuk)

### About me
Having graduated the university I started my carreer as a teacher of foreign languages at a local foreign language school in Blagoveshchensk. Being a teacher was fun, it also helped a lot in ganing different skills. After 4 years of teaching I found out that this was not my kind of thing.

Some circumstances made me leave my hometown for another city where I started working as a client support agent for an IT company. This position gave me much experience in communication, problem solving; let me take a closer look at technical side of our service, and business processes in our company. Working with high skilled developers I realized that frontend developing is an interesting IT field. I've started learning and have already obtaines some hard skills.

I believe my strong will, background and passion for frontend will surely lead me to this brand-new profession.

-------------------------------------------------------------------------------------------------------------------

### Skills 
- _HTML5_, _CSS3 (SCSS)_;
- _JS_;
- _Git_;
- _React (Redux)_;
- _Figma_;
- _Perfect pixel_;
- _Basic Bash commands_;

### Languages
- :ru: __Russian:__ native;
- :us: __English:__ advanced;
- :cn: __Chinese:__ basic;

---------------------------------------------------------------------------------------------------------------------

### Code example:
> The following code is my solution for **Credit Card Mask** Kata represented on [CodeWars](https://www.codewars.com/kata/5412509bd436bd33920011bc)

```javascript
function maskify(inputed) {
    const maskingChar = "#";
    const shownChars = 4;

    if (inputed.length > shownChars) {
        let shown = inputed.slice(-4);
        let hidden = maskingChar.repeat(inputed.length - shown.length);
        let output = hidden + shown;

        return output;
    }
    else return inputed;
};
```
