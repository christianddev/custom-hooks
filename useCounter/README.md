# useCounter

use Exmeple

`useCounter()` have default value 

```JS
    const {state, increment, decrement, reset} = useCounter();
    ...
    <div>
        <h1>CounterWithCustomHook {state}</h1>
        <button onClick={() => increment(1)}> +1</button>
        <button onClick={() => reset(2)} >reset</button>
        <button onClick={() => decrement(2)}> -1</button>
    </div>
   
```