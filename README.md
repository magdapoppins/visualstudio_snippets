# Custom Code Snippets in VSCode and Visual Studio 2017
How to create and customize code snippets and apply them in practice to enhance your workflow.

## VS Code
Code snippets in VSCode are written in JSON.
How?
```json
samplezz
```
Where?
Usage?

## Visual Studio 2017
Visual Studio contains a separate folder for code snippets. They are written in XML and follow this format: 
```xml
<?xml version="1.0" encoding="utf-8"?>  
<CodeSnippets  
    xmlns="http://schemas.microsoft.com/VisualStudio/2005/CodeSnippet">  
    <CodeSnippet Format="1.0.0">  
        <Header>  
            <Title></Title>  
        </Header>  
        <Snippet>  
            <Code Language="">  
                <![CDATA[]]>  
            </Code>  
        </Snippet>  
    </CodeSnippet>  
</CodeSnippets>  
```

To add your custom code snippet, create a new file with the extension `.snippet` and simply move it to the Visual Studio/VisualC#/Snippets folder. After this you will be able to use it in the editor by the specified `<Shortcut></Shortcut>`, like `ctor` or `enum`.