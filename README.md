# intellij-live-templates
My intelliJ live templates.
Please refer to the [official JetBrains site](https://www.jetbrains.com/help/idea/2016.1/live-templates.html) to see how to use them.

## How to install?
1. Copy this XML code
2. Go to the "Editor > Live templates" settings
3. Click on a template group where to import them
(or create a new one if needed)
4. Paste the XML

## Jasmine

```xml
<template name="aft" value="afterEach(function(){&#10;    $END$&#10;});" description="Jasmine afterEach" toReformat="true" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
    <option name="TypeScript" value="true" />
  </context>
</template>
<template name="bef" value="beforeEach(function(){&#10;    $END$&#10;});" description="Jasmine beforeEach" toReformat="true" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
    <option name="TypeScript" value="true" />
  </context>
</template>
<template name="desc" value="describe('$SELECTION$', function () {&#10;});" description="Jasmine describe" toReformat="true" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
    <option name="TypeScript" value="true" />
  </context>
</template>
<template name="it" value="it('should $END$', function () {&#10;});" description="Jasmine it" toReformat="true" toShortenFQNames="true">
  <context>
    <option name="JAVA_SCRIPT" value="true" />
    <option name="JS_EXPRESSION" value="true" />
    <option name="JSX_HTML" value="true" />
    <option name="JS_STATEMENT" value="true" />
    <option name="TypeScript" value="true" />
  </context>
</template>
```
