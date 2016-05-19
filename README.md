# intellij-live-templates
My intelliJ live templates.

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
