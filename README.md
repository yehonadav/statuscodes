# StatusCodes

## install

```
npm i statuscodes
```

enum mapping for http status codes: 

## usage

```typescript
import {statusCode} from "statuscodes"

function responseOk(message) {
  return {
    status: statusCode.ok,
    message,
  }
}
```

enjoy =)  
