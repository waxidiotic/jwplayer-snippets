# jwplayer-snippets README

A collection of JW Player-related snippets for Visual Studio Code

| Snippet | Expanded Code |
|---------|---------------|
|`jwdeclare`|`const ${1:playerInstance} = jwplayer('${2:myElement}');`
|`jwsetup`|`${1:playerInstance}.setup({`<br>&nbsp;&nbsp;&nbsp;&nbsp;`$2`<br>`});`|
|`jwevent`|`${1:playerInstance}.on('$2', (evt) => {`<br>&nbsp;&nbsp;&nbsp;&nbsp;`console.log(evt);`<br>`});`|