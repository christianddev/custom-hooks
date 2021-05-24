# useFetch

use example
```JS
    const {data} = useFetch(`https://breakingbadapi.com/api/quotes/1`);

    
    const {quote}= !!data && data[0];
    ...
    
    <blockquote>
        <p>{quote}</p>
    </blockquote>
```