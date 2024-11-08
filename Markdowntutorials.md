# Code in Visual Studio  
  
Here, we will write the Markdown code in visual studio.   
  
## What is Markdown?  
  
Markdown is a simple and easy plaintext language. It uses simple commands as compared to other fancy text documents. It is similar to the Latex. It is used by scientists, writers, etc. to write **documents, research papers, websites, books,** and **presentations**.   


### Common Markdown Commands  
  
> The common Markdown commands are as follows:  
- Bold  
- Italics  
- Text Highlight  
- Blockquotes  
- Images  
- Links  
- Lists  
- Headers  
  
## Online editors  
  
Markdown is also accessible through various online editors, such as **Dillinger**, and **Stack Edit**. It offers quick documentation without the need of any installation. It can be accessed anywhere through the internet.  

_So, what's up tomorrow._ #**TT**## **#Text**
# Heading 1 of the paper is the first of the paper. The paper is 
## Heading 2 of the paper is the second of the paper.
### Heading 3 of the paper represents the third of the paper.

_Gone were the days, I used to learn mermaid code_. So, I got the link to the mermaid code as [mermaid code](https://mermaid.js.org/). 

# Let's Learn How To Insert Images in Markdown #
_This is a computer from Amazon_
![ComputerfromAMazon](https://m.media-amazon.com/images/I/81JjCDg3dcL.__AC_SY300_SX300_QL70_FMwebp_.jpg) 

_This is how to insert markdown image not from the path_
![alt text](overleaf.png)

_I am trying to insert my brand logo_ 
<!---
![alt text](![alt text](Designer.jpeg))  -Useful for writing comments
--->
     
<img src="Designer.jpeg" alt="alt text" title="image Title" width="150"/>


# Writing Blockquotes
> "Hard work and smart work together helps people to achieve their goals."
>> "Markdown is a simple and easy plaintext language with limited number of commands." 
 

#  </u> Code Blocks in Markdown</U>
 <mark> Note: The text should be inserted between the three backtick symbols, but not in the same line. Markdown ignore the text specified on the same line as that of symbols.</mark> 

 ```  
Markdown is one of the easiest plaintext language.  
```  

> `code element`- This represents writing a code in markdown
> HelloWorld.java:
>
> ```java
> class HelloWorld {
>    public static void main(String[] args) {
>       System.out.println("Simple hello world program");
>   }
>}
>

# Writing Links in Markdown
<a href="about.html">About<a>

<a href= "Gallery.html">Gallery section<a>

Links title example [example link](URL "https://mermaid.js.org/")

> Lists in Markdown
1. List A 
2. List B  
       a. List a  
       b. List b 

3. List C
4. List D
    - List c
    - List d
    * List e


<!---
comments syntax-Useful for writing comments
The shortcut key to make any word, line, or paragraph as comments is: Ctrl + / or Ctrl + ?
--->


 # Underlining a *Text* in Markdown


<u>**NB:**</u> The underline tag in Markdown using  <u>HTML</u>  can be only implemented in  <u>visual studio</u> . 

>It does not work in ==online Markdown editors==. If underline is used in any online editor (for example, Dillinger), it will considered it as a normal text, which will be the same syntax as the input.


 # Highlighting *Texts* in Markdown

<mark> This is how to highlight text in a document </mark>

<mark>The purpose of living is to have a healthy, happy, and a cheerful life. </mark>

===page title===
this is page title of an document
== Section
    This is main section
=== Sub section
    This is sub section

# TABLES IN MARKDOWN
|Header1 |Header2  | Header3|       
--- | --- | ---|                     
|data1|data2|data3|
|data11|data12|data13|

# Left side alignment -> 
<!-- : - - - - - -   -->
|Alphabets|Numbers|Symbols|
|:----|:------|:------|
|a        |1   | @|
|b       | 2  |  # |  
|c       | 3  |  % |  
|d       | 4  |  * |

# Center alignment -> 
<!-- : - - - - - - :   -->
|Alphabets|Numbers|Symbols|
|:----:|:------:|:------:|
|a        |1   | @|
|b       | 2  |  # |  
|c       | 3  |  % |  
|d       | 4  |  * |


# Right-side alignment -> 
<!-- : - - - - - - :   -->

|Header1 |Header2  | Header3|
|---: | ---: | ---:|
|**bold style**| `code block`|data3|
|\|escape pipe|\`backtick|data13|

# FOOTNOTES
Here's a sentence with a footnote. [^1]


[^1]: This is the footnote.

<div> test content</div>

# Strikethrough in Markdown
What is the purpose of joining a training session at the beginning of a ~~old~~ new job.

# Superscript in Markdown
<!-- > Try writing a quadratic equation -->
Not workingin Vs code

 Definition  
   
   : Definition is a statement that describes the meaning of the listed word in the heading.  

First Definition  
        : It is the first definition list.   

- [ ] Option A

- [x] Option B

- [ ] Option C

- [ ] Option D

- [x] Option E

... Inline math $r = \sqrt{x^2 + y^2}$ and display math expressions $$e^{ix}=\cos x + i\sin x$$ are supported ... Commutative diagrams can be used since *mdmath* version 2.6

$$\begin{CD} A @>a>> B \\ @VbVV @AAcA \\ C @= D \end{CD}$$