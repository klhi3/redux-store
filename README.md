# Redux Store

This e-commerce platform uses Redux to manage global state instead of the Context API and this website's state management is out of the React ecosystem.
> React’s Context API, Flux or MobX, e-commerce platform code, Redux Provider

## Features

The app passes reducers to a Redux store, extracts state data from the store, and  dispatches actions using Redux instead of the Context API

```bash

// import { useStoreContext } from '../utils/GlobalState';
import { useDispatch, useSelector } from 'react-redux';

// const [state, dispatch] = useStoreContext();
const dispatch = useDispatch();
const state = useSelector((state) => state);

```

```bash

//import { StoreProvider } from './utils/GlobalState';
import { Provider} from 'react-redux';

```

## Deploy

* [Github Repository](https://github.com/klhi3/redux-store)
* [Heroku](https://redux-store-v.herokuapp.com/)

* Pages
- Sign up 
- Display category, product, destail and add & remove it from the shopping cart
- Checkout


# links

* [Redux](https://redux.js.org/)
* [Redux Fundamentals basic tutorial](https://redux.js.org/basics/basic-tutorial)


© klhi
