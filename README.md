# what is this?

 To beautify images with border radius, box shadows and margins.

# installation

`npm i beautifyImages --save`


Then...

```
import beautifyImages from './node_modules/beautifyImages/index.js';
beautifyImages({
      shadow_type:'soft',
      padding:false
});
```

## options

beautifyImages supports two options :

* *shadow_type* - _hard | soft_ (Defaults to 'soft')
* *padding* - _boolean_ (Defaults to false)
