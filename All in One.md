# _JavaScript DOM Assignments_

<b>

## _1. Website: [Dev.to](https://dev.to/)_

```javascript
> document.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerHTML = "Anupam Kumar Krishnan";
< 'Anupam Kumar Krishnan'
> document.querySelector(".side-bar .color-base-70").innerHTML = "Learning Web Development and Implementing By Building Projects";
< 'Learning Web Development and Implementing By Building Projects'
```

## _2. Website: [Apple](https://support.apple.com/en-in)_

```javascript
> document.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerHTML = "Anupam Kumar Krishnan";
< 'Anupam Kumar Krishnan'
> document.querySelector(".side-bar .color-base-70").innerHTML = "Learning Web Development and Implementing By Building Projects";
< 'Learning Web Development and Implementing By Building Projects'
```

## _3. Website: [Youtube Support](https://support.google.com/youtube/#topic=9257498)_

```javascript
> const faqSection = document.querySelector(".accordion-homepage")
  const topic = document.createElement("section")
  topic.classList.add("parent")
  const h3 = document.createElement ("h3" )
  h3.innerText = "My New FAQ"
  faqSection.appendChild(topic)
  topic.appendChild(h3)

< <h3>My New FAQ</h3>
```

## _4. Website: [Oneplus](https://www.oneplus.in/support)_

```javascript
document.querySelector(".customer-support").firstElementChild.innerText = "+91 6366256689"
'+91 6366256689'
```

## _5. Website: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)_

```javascript
> document.querySelector('.diwali-deals-product-sale-pro a').innerText = "Checkout"
< 'Checkout'
```

## _6. Website: [Addidas](https://www.adidas.co.in/)_

```javascript
  const findProduct = document.querySelector(".searchinput___19uW0")
  findProduct.addEventListener( "mouseover" ,()=> findProduct.style.backgroundColor = "Red")
```

## _7. Website: [MDN Web Docs](https://developer.mozilla.org/en-US/)_

```javascript
let inputvalue = document.querySelector("#hp-search-input");
inputvalue.value = "javascript"

let formsubmit = document.querySelector("#hp-search-form");

formsubmit.submit()  
```

## _8. Website: [Google](https://www.google.com/)_

```javascript
   const languagesOffered = document.querySelectorAll('#SIvCob a')
   languagesOffered.forEach( (a, i)=> i%2==0 && a.remove())
```

## _9. Website: [CodeWars](https://www.codewars.com/)_

```javascript
>   document.querySelector('.display-heading-1').style.fontFamily ="monospace"
    document.querySelector('.display-heading-1').style.color="#B1361E"
<   '#B1361E'
```

## _10. Website: [FreeCodeCamp](https://www.freecodecamp.org/)_

```javascript
const btnStarted = document.querySelector(".btn-cta-big .login-btn-text")
btnStarted.addEventListener("mouseover", () => btnStarted.style.backgroundColor = "red" )
````

## _12. Website: [GitHub](https://github.com/)_

```javascript
> document.querySelector(".my-3 .btn").style.backgroundColor = "blue"
< 'blue'
````

## _13. Website: [HackerRank](https://www.hackerrank.com/)_

```javascript
  document.querySelector('.fl-heading').innerHTML = "JSBOOTCAMP"
  'JSBOOTCAMP'
````

## _14. Website: [Asus](https://www.asus.com/in/)_

```javascript
  document.querySelector('.HotDealsAll__Heading__2fIbe').style.fontSize="80px"
  '80px'
````

## _15. Website: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)_

```javascript
  document.querSelector('.ps-title').style.textAlign = "right"
  'right'
````

## _16. Website: [Vercel](https://vercel.com/)_

```javascript
  document.querySelector('.section-title_title__VEDfK').innerHTML = "Start with Sctrach"
  'Start with Sctrach'
````

## _17. Website: [Sony](https://www.sony.co.in/electronics/televisions/a80k-a83k-a84k-series)_

```javascript
  document.querySelector('.btn-container').innerHTML = new Date()
  Fri Sep 30 2022 11:24:29 GMT+0530 (India Standard Time)
````

## _18. Website: [Philips](https://www.philips.co.in/)_

```javascript
  document.querySelector('.p-footer').style.backgroundColor="Orange"
  'Orange'
```

## _19. Website: [Canon](https://in.canon/en/consumer)_

```javascript
  document.querySelector('.logo').src
  'https://in.canon/assets/brand/logo-300-002e45a4aec98fd92899838da9d5560f.png'
```

## _20. Website: [Oppo](https://www.samsung.com/in/offer/online/samsung-fest/)_

```javascript
  document.querySelector('.product-card-content .desc').style.color = 'Orange'
  'Orange'
```
</b>
