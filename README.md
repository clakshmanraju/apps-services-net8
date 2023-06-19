> **IMPORTANT!** [Information for Technical Reviewers](docs/reviewers.md)

[Common Mistakes, Improvements, and Errata aka list of corrections](docs/errata/README.md)

# Apps and Services with .NET 8, Second Edition

Repository for the Packt Publishing book titled "Apps and Services with .NET 8" by Mark J. Price

This book is expected to publish in December 2023.

My author page on Amazon: https://www.amazon.com/Mark-J-Price/e/B071DW3QGN/ 

All of my books on my publisher Packt's website: https://subscription.packtpub.com/search?query=mark+j.+price

## Code solutions for Visual Studio 2022 and Visual Studio Code

Visual Studio Code now has an extension named **C# Dev Kit** that includes a solution explorer so it can better work with Visual Studio 2022 solution files. Visual Studio 2022 for Windows, Visual Studio 2022 for Mac, and Visual Studio Code + C# Dev Kit can now use the same code solution files and projects for each chapter, found here: [/code](/code). 

> **For Visual Studio Code:** To use the chapter solution files with Visual Studio Code, install the **C# Dev Kit** extension. Then in Visual Studio Code, open the `ChapterNN` folder that contains a `ChapterNN.sln` solution file and wait for the **SOLUTION EXPLORER** pane to appear at the bottom of the **EXPLORER**. You can drag and drop to reorder the panes to put **SOLUTION EXPLORER** at the top. Learn more about C# Dev Kit at the following link: https://devblogs.microsoft.com/visualstudio/announcing-csharp-dev-kit-for-visual-studio-code/

> **Warning!** If you use both Visual Studio 2022 and Visual Studio Code to open these solutions, be aware that the build process can conflict. This is because Visual Studio 2022 has its own non-standard build server that is different from the standard build server used by .NET SDK CLI. My recommendation is to only have a solution open in one code editor at any time. You should also clean the solutions between opening in different code editors. For example, after closing the solution in one code editor, I delete the `bin` and `obj` folders before then opening in a different code editor.

## Chapters and code solutions

**Introduction**
- Chapter 1 Introducing Apps and Services with .NET: [code/Chapter01](code/Chapter01)

**Data**
- Chapter 2 Managing Relational Data Using SQL Server: [code/Chapter02](code/Chapter02)
- Chapter 3 Building Entity Models for SQL Server Using EF Core: [code/Chapter03](code/Chapter03)
- Chapter 4 Managing NoSQL Data Using Azure Cosmos DB: [code/Chapter04](code/Chapter04)

**Specialized Libraries**
- Chapter 5 Multitasking and Concurrency: [code/Chapter05](code/Chapter05)
- Chapter 6 Implementing Popular Third-Party Libraries: [code/Chapter06](code/Chapter06)
- Chapter 7 Handling Dates, Times, and Internationalization: [code/Chapter07](code/Chapter07)

**Services**
- Chapter 8 Building and Securing Web Services Using Minimal APIs: [code/Chapter08](code/Chapter08)
- Chapter 9 Caching, Queuing, and Resilient Background Services: [code/Chapter09](code/Chapter09)
- Chapter 10 Building Serverless Nanoservices Using Azure Functions: [code/Chapter10](code/Chapter10)
- Chapter 11 Broadcasting Real-Time Communication Using SignalR: [code/Chapter11](code/Chapter11)
- Chapter 12 Combining Data Sources Using GraphQL: [code/Chapter12](code/Chapter12)
- Chapter 13 Building Efficient Microservices Using gRPC: [code/Chapter13](code/Chapter13)

**Apps**
- Chapter 14 Building Web User Interfaces Using ASP.NET Core: [code/Chapter14](code/Chapter14)
- Chapter 15 Building Web Components Using Blazor: [code/Chapter15](code/Chapter15)
- Chapter 16 Building Mobile and Desktop Apps Using .NET MAUI: [code/Chapter16](code/Chapter16)
- Chapter 17 Implementing Model-View-ViewModel for .NET MAUI: [code/Chapter17](code/Chapter17)
- Chapter 18 Integrating .NET MAUI Apps with Blazor and Native Platforms: [code/Chapter18](code/Chapter18)
- Chapter 19 Introducing the Survey Project Challenge

## Extra content to download

The appendix and color figures are available to download as PDFs:

- Appendix A, Answers to the Test Your Knowledge Questions: coming December 2023.
- Color images of the screenshots/diagrams used in this book: coming December 2023.

## Important
Corrections for typos and other mistakes and improvements like refactoring code. Useful links to other related material. 
- [Online-only sections](https://github.com/markjprice/apps-services-net8/blob/main/docs/README.md)
- [Common Mistakes, Improvements, and Errata aka list of corrections](docs/errata/README.md)
- [Book Links](docs/book-links.md)
- [Command-Lines](docs/command-lines.md) page lists all commands as a single line that can be copied and pasted to make it easier to enter commands at the prompt.
- [Second edition's support for .NET 9](docs/dotnet9.md)

## Microsoft Certifications
Microsoft used to have exams and certifications for developers that covered skills like C# and ASP.NET. Sadly, they have retired them all. These days, the only developer-adjacent exams and certifications are for Azure or Power Platform, as you can see from the certification poster: https://aka.ms/traincertposter

## Microsoft .NET community support
- [.NET Developer Community](https://dotnet.microsoft.com/platform/community)
- [.NET Tech Community Forums for topic discussions](https://techcommunity.microsoft.com/t5/net/ct-p/dotnet)
- [Q&A for .NET to get your questions answered](https://docs.microsoft.com/en-us/answers/products/dotnet)
- [Technical questions about the C# programming language](https://docs.microsoft.com/en-us/answers/topics/dotnet-csharp.html)
- [If you'd like to apply to be a reviewer](https://authors.packtpub.com/reviewers/)

## Interviews with me
Podcast interviews with me:
- [The .NET Core Podcast - March 3, 2023](https://dotnetcore.show/episode-117-our-perspectives-on-the-future-of-net-with-mark-j-price/)
- [Yet Another Podcast with Jesse Liberty - December 2022](https://jesseliberty.com/2022/12/10/mark-price-on-c-11-fixed/)
- [The .NET Core Podcast - February 4, 2022](https://dotnetcore.show/episode-91-c-sharp-10-and-dotnet-6-with-mark-j-price/)
- [Yet Another Podcast with Jesse Liberty - May 2021](http://jesseliberty.com/2021/05/16/mark-price-on-c9-and-net-6/)
- [The .NET Core Podcast - February 7, 2020](https://dotnetcore.show/episode-44-learning-net-core-with-mark-j-price/)
- [Yet Another Podcast with Jesse Liberty - February 2020](http://jesseliberty.com/2020/02/23/mark-price-c-net-core/)
- [Packt Podcasts](https://soundcloud.com/packt-podcasts/csharp-8-dotnet-core-3-the-evolution-of-the-microsoft-ecosystem)

Written interviews with me:
- [C# 9 and .NET 5: Book Review and Q&A](https://www.infoq.com/articles/book-interview-mark-price/?itm_source=infoq&itm_campaign=user_page&itm_medium=link)
- [Q&A with Episerver's Mark J. Price, author of C# 9 and .NET 5 - Modern Cross-Platform Development](https://www.episerver.com/articles/q-and-a-with-mark-price)
