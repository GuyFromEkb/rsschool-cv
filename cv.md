# Perepelkin Sergey

# Contacts

- **Phone:** +79021889882
- **Discord:** Joyful#0100
- **Telegram:** [@GuyFromEkb](https://t.me/GuyFromEkb)
- **E-mail:** [graygmai1@gmail.com](graygmai1@gmail.com)
- **GitHub:** [GuyFromEkb](https://github.com/GuyFromEkb)

# About Myself:

I work in the company as a junior front-end, and really like what I do. My target to become a professional in my field. I love sport and coding and hope that my ability to learn and acquire new skills will help me go this way and become an experienced Front end developer.

# Skills

- HTML
- CSS
- JavaScript
- TypeScript
- C# (basic level)
- React (state: Redux,mobX)
- Git (GitHub/GitLab).
- Gulp, Webpack.
- Figma


```js
//In this little assignment you are given a string of space separated numbers, and have to return the highest and lowest number.
//Example:
//highAndLow("1 2 3 4 5");  // return "5 1"
//highAndLow("1 2 -3 4 5"); // return "5 -3"
//highAndLow("1 9 3 4 -5"); // return "9 -5"

function highAndLow(numb) {
    const arr = numb.split(" ").map(item => parseInt(item))
    return `${Math.max(...arr)} ${Math.min(...arr)}`
}
```
