## CProxy

npm:

```diff
import { Configuration } from "openai";

const configuration = new Configuration({
  apiKey: OPENAI_API_KEY,
+ basePath: "https://closeai.deno.dev/v1",
});
```

python:

```diff
  import openai

  openai.api_key = os.getenv("OPENAI_API_KEY")
+ openai.api_base = "https://closeai.deno.dev/v1"
```
### by Ethan 2023-04-13
