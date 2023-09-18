# PolyglotColab
Polyglot Jupyter notenook Boilerplate code


[Polyglot Programming](https://en.wikipedia.org/wiki/Polyglot_(computing)) refers to the ability  to use multiple programming languages in one domain app  . 
this would allow great interopability between services , libraries ,SDK tools and frameworks and allow you to use your own  favourite  techstack  in  unified hybird environment

dotnet core is a great modren framework and  runtimeplatform that have great flexibility to extend,
there's often muliple ways to do this , either by  exposing low level code  throught [FFI](https://en.wikipedia.org/wiki/Foreign_function_interface)which call external basecodelibrary in callstack  then [abstract the API](https://en.wikipedia.org/wiki/Wrapper_function)   callbacks using [P/invoke](https://en.wikipedia.org/wiki/Platform_Invocation_Services) or through  [reflection and marshling](https://en.wikipedia.org/wiki/Language_binding) by using [DLR](https://learn.microsoft.com/en-us/dotnet/framework/reflection-and-codedom/dynamic-language-runtime-overview) language binding

others are less likely to use is IPC in process commcunicatition , using trnspiler / crosscompiler ( source to source compiler e.g haxe)   or converting tools e.g e4k and finally boostrap .net in interpeted mode 
aka ad hoc hosting ( .net in c)  for moe informatin :
```https://medium.com/@tombly/net-embedding-in-practice-8eb3df24687f```
and
```https://learn.microsoft.com/en-us/dotnet/core/tutorials/netcore-hosting```

Google colab is a great platform to build and run Jupyter Notebooks for free. 

![image](https://github.com/PrestigeDevop/PolyglotColab/assets/85388342/c682dc96-c0c2-4da8-9ce6-d081c1fb41ff)

- todo;
  make code server consistent between sessions
  add more plugins
  add ikvm , InodeSerice
  multilanguage kernalshell
  
   
