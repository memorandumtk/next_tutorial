This is a starter template for [Learn Next.js](https://nextjs.org/learn).

### getStaticProps
- I was curious `props` value is positioned after function passed the `props`. But it was because 'getStaticProps' is called at build time. So, the component that receives the `props` will receive props at build time.https://nextjs.org/docs/pages/api-reference/functions/get-static-props
> based on above official site (and chatGPT),
> // By returning { props: { posts } }, the Blog component
> // will receive `posts` as a prop at build time  

  
