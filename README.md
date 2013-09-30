Ember App Kit Snippets for Sublime Text 2
====================================
These snippets provide access to common functionality for tab completion of Ember JS code.
The snippets have been optimized and formatted for Ember App Kit syntax and module exports.

## How to Use
Install these snippets in a folder in your packages folder of sublime text 2

Type out the snippet shortcut and press `tab` to expand the snippet.

Continue to tab through the snippet to edit segments within the snippet.

## EAK Ember.js

- eak-acceptance-test ⇥
- eak-app ⇥
- eak-component ⇥
- eak-cp ⇥
- eak-controller ⇥
- eak-grunt-task ⇥
- eak-helper ⇥
- eak-initializer ⇥
- eak-mixin ⇥
- eak-model-ed ⇥
- eak-model-em ⇥
- eak-model-epf ⇥
- eak-model-generic ⇥
- eak-object ⇥
- eak-observer ⇥
- eak-route ⇥
- eak-router ⇥
- eak-store-create ⇥
- eak-store ⇥
- eak-unit-test ⇥
- eak-utility ⇥
- eak-view ⇥

## Handlebars (HBS)

- hbs-script-tag ⇥
- hbs-action ⇥
- hbs-each ⇥
- hbs-eachelse ⇥
- hbs-if ⇥
- hbs-ifelse ⇥
- hbs-link-to ⇥
- hbs-partial ⇥
- hbs-unless ⇥
- hbs-view ⇥

## Handlebars script tag (HTML)

- hbs-script-tag ⇥


## Found a bug or have idea for improvement?
Please submit an issue or pull request with the example snippet or raw code snippet included

Things to consider:
* Try to make snippet syntactically complete but minimalist outline of functionality.
* Be mindful of the tab completion order, think about how a user might construct this snippet.
* Resuse common variable names or elements inside the snippet to reduce typing
* Snippet should both save time and provide user with useful example syntax.
* Try to adhere to latest idomatic standards for Ember App Kit and the Ember JS API.
* Use logical prefix in tab trigger (eak, hbs, coffee) so that common snippets are grouped together.

Below is an example of a complete snippet. This one create a utility function for EAK.

```
<snippet>
    <content><![CDATA[
/*
* @method ${1:utilityName}
* @param {${5:String}} ${2:input} ${4:TODO: Needs documentation...}
*/

function ${1:utilityName}(${2:input}) {
  // Do something with ${2:input} 
  var ${3:transform} = ${2:input} + "foo";
  return ${3:transform};
}

export default ${1:utilityName};


]]></content>
    <description>EAK Utility Method</description>
    <tabTrigger>eak-utility</tabTrigger>
    <scope>source.js</scope>
</snippet>

```

To use this snippet in Sublime Text 2

type `eak-utility` press tab to expand, and then continue to tab through and complete the different segments of the snippet.


