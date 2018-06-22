# jwplayer-snippets README

A collection of JW Player-related snippets for Visual Studio Code

| Snippet | Expanded Code |
|---------|---------------|
|`jwdeclare`|`const ${1:playerInstance} = jwplayer('${2:myElement}');`
|`jwsetup`|`${1:playerInstance}.setup({`<br>`  $2`<br>`});`|
|`jwevent`|`${1:playerInstance}.on('$2', (evt) => {`<br>`  console.log(evt);`<br>`});`|