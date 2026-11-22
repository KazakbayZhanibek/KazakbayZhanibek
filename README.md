<p><img src="./assets/banner.png" width="100%" alt="Kazakbay Janibek — full-stack developer from Kazakhstan" /></p>

**Tools I build with** &nbsp; `TypeScript` `React` `Next.js` `Node.js` `Express` `SQL` `Python`

## Inside EduMatch KZ

I’m building a university guide for students in Kazakhstan. A programme may fit a student’s exam results while its application deadline is still unverified. Here’s how the API flags that university for a second look.

```js
let status = 'notSuitable';
if (candidate) {
  const hasUnknownCritical = critical.some(
    key => candidate.checks?.[key] === 'unverified'
  );
  status = hasUnknownCritical
    ? 'needsClarification'
    : 'matched';
}
```

[View the code in context ↗](https://github.com/KazakbayZhanibek/edumatch.kz/blob/10d4d11453ba9c7c35153d1a0df25a523acd4abf/backend/grants-routes.js#L247-L251) &nbsp; · &nbsp; [EduMatch repository](https://github.com/KazakbayZhanibek/edumatch.kz)

### Elsewhere in my code

**[RANO Komfort Service](https://rano-comfort.vercel.app/catalog)** · A Next.js storefront for household supplies. Checkout requires an address for home delivery. [Checkout implementation ↗](https://github.com/KazakbayZhanibek/rano-comfort/blob/d4a81af8ae487a2ac3229de344191c76a8c5b5d8/app/checkout/page.tsx#L89-L92)

**Belle Croissant Lyonnais** · A Django app for bakery operations, with a desktop interface built using PyWebView.

[Telegram](https://t.me/tibio_404) &nbsp; · &nbsp; [Email](mailto:janibekkaz3@gmail.com) &nbsp; · &nbsp; [LinkedIn](https://kz.linkedin.com/in/zhanibek-kazakbay-7a1909359)
