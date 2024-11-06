# Anton Hryshchuk
### Junior Frontend Developer
---
## Contact
Phone: 795 029 892

Email: antonhryschuk@gmail.com

[Github](https://github.com/1ways)

[LinkedIn](https://www.linkedin.com/in/anton-hryshchuk-4a9a01304/)

## Profesional Summary
Passionate and dedicated Computer Science student with a solid foundation experience in front-end development. I am deeply excited about JavaScript, React, Web Development and the collaborative nature of teamwork. I am eager to apply my web development skills to make meaningful contributions to projects and drive innovation forward.

## Skills
- HTML
- CSS
- SCSS
- JavaScript
- React
- Figma
- Git
- TailwindCss
- Gulp

## Code Examples
- "Find the unique number" - JavaScript problem

    ```javascript
    const findUniq = arr => {
    const set = new Set(arr)
    const arr2 = [...set]
    
    let count = 0;
    for (let i = 0; i < arr.length; i++) {
        if (arr[i] === arr2[0]) {
            count += 1
        }
    }
    return count > 1 ? arr2[1] : arr2[0]
    }
    ```
- "Counting Duplicates" - JavaScript problem

    ```javascript
    const duplicateCount = text => {
    const textLowerCase = text.toLowerCase()
        let sameArr = [] 
        for (let i = 0; i < textLowerCase.length; i++) {
        const currentSymbolPos = textLowerCase.indexOf(textLowerCase[i])
        const modifyStr = `${textLowerCase.slice(0, currentSymbolPos)}${textLowerCase.slice(currentSymbolPos + 1, textLowerCase.length)}`
        
        for (let j = 0; j < modifyStr.length; j++) {
            if (textLowerCase[i] === modifyStr[j]) {
                if (!sameArr.includes(textLowerCase[i])) {
                sameArr.push(textLowerCase[i])
                }
            }
            }
            
        }
        return sameArr.length || 0
    }
    ```