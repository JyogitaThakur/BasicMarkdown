# MarkDown CheatSheet

## Headings: 
    Code:
          # Heading 1
          ## Heading 2
          ### Heading 3
          #### Heading 4
          ##### Heading 5
        

Output:
  # Heading 1
  ## Heading 2
  ### Heading 3
  #### Heading 4
  ##### Heading 5

## Paragarphs and Text Styling
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.

### Style Your Texts 
- *Italic Text*:

     *Italic*: `I am *Italic* text`\
    _Italic_: `I am _Italic_ text`

- **Bold Text** :

    **Bold** : `I am **Bold** text`\
    __Bold__ : `I am __Bold__ text`

- StrikeThrough:

     ~~strikethrough~~ : `StrikeThrouh can be done using double ~~ sign` 

## Adding Images:

- You can add image `![](url, 'tooltip')`\
``![Alternate text](https://source.unsplash.com/random, 'Random Image') ``

- Or you can use this \
`image: https://source.unsplash.com/random`\
``![random image][image]``

- Link with an image: \
`[![random image](https://source.unsplash.com/random)](https://source.unsplash.com/random)`

## Ordered, Unordered, Bullets and Nesting:

- Unordered List:
   Unordered list can be written in following ways  
    - Code:
    ```
        `- List 1`
        `+ List 2`
        `* List 3`
    ```
    - Output :
        - List 1
        + List 2
        * List 3

- Ordered List
    It doesn't matter if you write the same number, the output you get is in the order.
    - Code:
    ```
        `1. List 1`
        `1. List 2`
        `1. List 3`
    ```
    - Output :
         1.  List 1  
         2.  List 2 
         1.  List 3 

- Nested List:
    - Code :
        ```
            1. List 1
            1. Nested Inside List 1
                1. Nested Inside Nested List 1
                ```js
                    let x = 10
                ```
            1. List 2
                * Nested Inside List 2  
            1. List 3
                - Image Nested inside List 3

                ![Alternate text](http://unsplash.it/500/300?random, 'Random Image') 
        ```

    - Output :
        1. List 1
            1. Nested Inside List 1
                1. Nested Inside Nested List 1
        1. List 2
            * Nested Inside List 2  
                ```js
                        let x = 10
                ```
        1. List 3
            - Image Nested inside List 3

           ![Alternate text](http://unsplash.it/500/300?random, 'Random Image')

## Line Breaks, Horizontal Rules and BlockQuotes: 
- Line Break:  
    - Code: 
    ```   
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <br>when an unknown printer took a galley of type and scrambled it to make a type specimen book. 
    ```    

    - Output :
    
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <br> when an unknown printer took a galley of type and scrambled it to make a type specimen book.

- Horizontal Rules :   
    Create a Horizontal line as follows    
    - Code:
        ```
            Horizontal Line using '---`   
    
            ---
    
            Horizontal Line using `---` and  for heading '===`   
            ===
            
            Horizontal Line using '***`

            ***

            Horizontal Line using '___`
            
            ____

        ```

    - Output:

        Horizontal Line using '---`  
    
        ---

        Horizontal Line using `---` and  for heading '===`   
        ===
        
        Horizontal Line using '***`

        ***

        Horizontal Line using '___`

        ____

- BlockQuotes :  
    You can write Blockquotes using `>`
    - Code:
        ```
            > Knowledge is power. 
            >
            > *– Francis Bacon*  
        ```
    - Output:

        > Knowledge is power. 
        >
        > *– Francis Bacon*     

## Code Blocks + Syntax Highlighting: 
   - You can write your code in between ``` sign
   - The code contains `[```js]` will let the broswer know which language syntax it is.
   - Code:
      ```
            ```js
                var x = 'Hello Javascript'
            ```
            
            // This shows the line added and deleted.
             ```diff
                var x=100
                - var y = 200
                + var y = 300;
            ```
        ```    
    
   - Output:
        ```js
            var x = 'Hello Javascript'
        ```

        ```diff
        var x=100
        - var y = 200
        + var y = 300;
        ```

## Tables:  
- you can create table using `|` and `-` .

    - Code:
        ```
            |Dog's Name | Dog's Age |
            |:---------:|:---------:|
            |Snickers|2|
            |Prudence|8|
        
            // |:---------:|:---------:| contents in center
            // |---------:|---------:| contents are in right side
            // |:---------|:---------| contents are in left side -- By default

        ```

    - Output:
        |Dog's Name | Dog's Age |
        |:---------:|:---------:|
        |Snickers|2|
        |Prudence|8|

## Checkboxes: 
- Code:
    ```
        [ ] Item 1
        [ ] Item 2
        [ ] Item 3
    ```
- OutPut:

    - [ ] Item 1
    - [ ] Item 2
    - [ ] Item 3

## Collapse Section:    
- Code:
    ```
    <details>
    <summary>TITLE</summary>

        BODY CONTENT

    </details>
    ```

- Output:

    <details>
    <summary>TITLE</summary>

        BODY CONTENT

    </details>

## URLs and Email Addresses:
To quickly turn a URL or email address into a link, enclose it in angle brackets.
- Code:
    ```
        <https://www.google.com>\
        <fake@example.com>
    ```
- Output:

    <https://www.google.com>\
    <fake@example.com>

## Formatting Links:
- Code:
    ```
    This is the *[Google Page](https://www.google.com)*.\
    See the section on [`Headings`](#Headings).

    ```
- Output:

    This is the *[Google Page](https://www.google.com)*.\
    See the section  [`Headings`](#Headings).


