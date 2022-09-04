# backdrop-cfx-svelte
Using backdrop filter on fivem with svelte

There is a problem when using backdrop filter on fivem, the background will have weird black background color when using it.

From this:
![image](https://user-images.githubusercontent.com/64617706/188298599-9f016d2a-f910-4f2e-95b0-b48be0fbe7c2.png)

To This:
![image](https://user-images.githubusercontent.com/64617706/188298600-9ba615e1-516e-4c76-a7f7-3353f145224f.png)


Solution:
https://github.com/citizenfx/fivem/blob/538f9cc8310391417fd025febae6d1efb9558bc5/ext/cfx-ui/src/app/app.component.ts#L16-L169

React:
https://gist.github.com/liquiad/f4952575cbff31f923d19b342b4d25f8
