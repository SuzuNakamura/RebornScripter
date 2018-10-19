# Kagami

## What's this?
It's a simple and tiny script language.The name of this project is from Japanese kanji "鏡（かがみ）".

## What does it looks like?

```
def ReadFile()
    stream = instream('SomeWords.txt')
    while(stream.eof() != true)
        print(stream.get())
    end
    stream.close()
end

if(__name__ == '__main__')
    ReadFile()
end
```

There's no any documents for this language and interpreter for now(because of development process and etc.).I pick some of my favorite syntax from Python and Visual Basic .NET, and try to make Kagami easier to read and use. 

## Feature
[√] Dynamic and weak typing language with reflection support

[√] GC based on referenced count

[√] Fully based on C++11 and STL

[√] C Function support(partial and experimental)

[×] Class support/SDL2 support


## How to use these codes?
Strongly recommend to compile them in Visual Studio 2010 or later version.You can also compile by using g++/clang++ with -std=c++11 option.

## Help me?
You can post issues or create pull request.

## License
This application is licensed under BSD - 2 clause, just do anything you like.
