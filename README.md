# Front-End-Roadmap
Complete roadmap along with notes to become a Front End Developer

Credits - Roadmap framework from the [Propeers Front End Roadmap](https://www.propeers.in/roadmaps/657dafb34f74377fd1ac07b0)

Notes generated using ChatGPT

# Table of Contents
- [Front-End-Roadmap](#front-end-roadmap)
  * [HTML](#html)
    + [1. HTML Basics](#1-html-basics)
    + [2. HTML Top Level Tags](#2-html-top-level-tags)
    + [3. HTML Block & Inline Tags](#3-html-block---inline-tags)
    + [4. HTML Tables](#4-html-tables)
    + [5. HTML Forms](#5-html-forms)
    + [6. HTML Attributes](#6-html-attributes)
  * [CSS](#css)
    + [1. Basics of CSS](#1-basics-of-css)
    + [2. Box Model](#2-box-model)
    + [3. Sizing and Styling Elements](#3-sizing-and-styling-elements)
    + [4. Transitions and Animations](#4-transitions-and-animations)
    + [5. Responsive Design](#5-responsive-design)
    + [Responsive Design in Detail](#responsive-design-in-detail)
    + [1. **Understanding Responsive Design**](#1-understanding-responsive-design)
    + [2. **Fluid Grids**](#2-fluid-grids)
    + [3. **Flexible Images**](#3-flexible-images)
    + [4. **Media Queries**](#4-media-queries)
    + [5. **Responsive Frameworks**](#5-responsive-frameworks)
    + [6. **Viewport Meta Tag**](#6-viewport-meta-tag)
    + [Summary](#summary)
  * [JavaScript](#javascript)
    + [1. Intro to JavaScript](#1-intro-to-javascript)
    + [2. Variables and Data Types](#2-variables-and-data-types)
    + [3. If/Else & Loops](#3-if-else---loops)
    + [4. Functions](#4-functions)
    + [5. OOPS in JS](#5-oops-in-js)
    + [6. Important Concepts in JS](#6-important-concepts-in-js)
    + [7. JavaScript for Web](#7-javascript-for-web)
    + [Summary](#summary-1)
  * [React](#react)
    + [Creating a Simple React Project](#creating-a-simple-react-project)
    + [1. **Set Up Your Environment**](#1-set-up-your-environment)
    + [2. **Create a New React Application**](#2-create-a-new-react-application)
    + [3. **Project Structure**](#3-project-structure)
    + [4. **Modify the Default App**](#4-modify-the-default-app)
    + [5. **Add More Components**](#5-add-more-components)
    + [6. **Styling Your Application**](#6-styling-your-application)
    + [7. **Build and Deploy**](#7-build-and-deploy)
    + [Summary](#summary-2)
    + [1. States](#1-states)
    + [2. Components](#2-components)
    + [3. Hooks](#3-hooks)
    + [4. Router](#4-router)
    + [Summary](#summary-3)
  * [Git/GitHub](#git-github)
    + [1. **Getting Started**](#1-getting-started)
    + [2. **Git First Commands**](#2-git-first-commands)
    + [3. **Git Activity Commands**](#3-git-activity-commands)
    + [4. **Git Change**](#4-git-change)
    + [5. **Git Branch**](#5-git-branch)
    + [6. **Git Local**](#6-git-local)
    + [Summary](#summary-4)
  * [Basic SEO Principles](#basic-seo-principles)
    + [1. **On-Page Optimization**](#1-on-page-optimization)
    + [2. **Meta Keywords**](#2-meta-keywords)
    + [3. **SEO Images**](#3-seo-images)
    + [4. **SEO Internal Link Building**](#4-seo-internal-link-building)
    + [5. **SEO Site Map**](#5-seo-site-map)
    + [Summary](#summary-5)
  * [Intermediate React](#intermediate-react)
    + [1. **useReducer**](#1-usereducer)
    + [2. **Redux States**](#2-redux-states)
    + [3. **Concepts of Redux**](#3-concepts-of-redux)
    + [4. **Async Logic and Data Fetching in Redux**](#4-async-logic-and-data-fetching-in-redux)
    + [Summary](#summary-6)
  * [Testing Tools](#testing-tools)
    + [1. **JEST Testing**](#1-jest-testing)
    + [2. **Cross-Browser Testing**](#2-cross-browser-testing)
    + [3. **Website Testing**](#3-website-testing)
    + [Summary](#summary-7)
  * [Advanced React with Next.js](#advanced-react-with-nextjs)
    + [1. **Intro to Next.js**](#1-intro-to-nextjs)
    + [2. **Next.js vs React**](#2-nextjs-vs-react)
    + [3. **Server-Side Rendering (SSR)**](#3-server-side-rendering--ssr-)
    + [4. **Data Fetching**](#4-data-fetching)
    + [5. **Hot Reloading**](#5-hot-reloading)
    + [6. **Image Optimization**](#6-image-optimization)
    + [Summary](#summary-8)
    + [Integrating Next.js into a React Project](#integrating-nextjs-into-a-react-project)
    + [Additional Integration Tips:](#additional-integration-tips-)
    + [Summary](#summary-9)
  * [CI/CD Tools](#ci-cd-tools)
    + [1. **Basics of DevOps**](#1-basics-of-devops)
    + [2. **Server Management**](#2-server-management)
    + [Summary](#summary-10)
  * [Security Handling](#security-handling)
    + [1. **Security**](#1-security)
    + [2. **XSS (Cross-Site Scripting) Attack**](#2-xss--cross-site-scripting--attack)
    + [3. **CSRF (Cross-Site Request Forgery) Attack**](#3-csrf--cross-site-request-forgery--attack)
    + [4. **DOS (Denial of Service) Attack**](#4-dos--denial-of-service--attack)
    + [Summary](#summary-11)
  * [Basic DSA - 50](#basic-dsa-50)
    + [1. **Second Largest Element**](#1-second-largest-element)
    + [2. **Rotate An Array By K**](#2-rotate-an-array-by-k)
    + [3. **Non Decreasing Array**](#3-non-decreasing-array)
    + [4. **Equilibrium Index**](#4-equilibrium-index)
    + [5. **First Missing Positive**](#5-first-missing-positive)
    + [6. **Reverse String Word Wise**](#6-reverse-string-word-wise)
    + [7. **String Encoding**](#7-string-encoding)
    + [8. **Minimum Parentheses**](#8-minimum-parentheses)
    + [9. **Beautiful Strings**](#9-beautiful-strings)
    + [10. **Next Smallest Palindrome**](#10-next-smallest-palindrome)
    + [11. **Sum of Zeroes**](#11-sum-of-zeroes)
    + [12. **Matrix Symmetric**](#12-matrix-symmetric)
    + [13. **Inplace Rotate Matrix 90 Degrees**](#13-inplace-rotate-matrix-90-degrees)
    + [14. **Set Matrix Zeroes**](#14-set-matrix-zeroes)
    + [15. **Spiral Order**](#15-spiral-order)
    + [16. **Make Unique Array**](#16-make-unique-array)
    + [17. **First Non-Repeating Character in String**](#17-first-non-repeating-character-in-string)
    + [18. **Longest Subarray Zero Sum**](#18-longest-subarray-zero-sum)
    + [19. **Count All Sub-arrays Having Sum Divisible by K**](#19-count-all-sub-arrays-having-sum-divisible-by-k)
    + [20. **Group Anagrams**](#20-group-anagrams)
    + [21. **Pair Sum**](#21-pair-sum)
    + [22. **Move Negative Numbers to Start**](#22-move-negative-numbers-to-start)
    + [23. **Container With Most Water**](#23-container-with-most-water)
    + [24. **Check Subsequence**](#24-check-subsequence)
    + [25. **Insertion Sort**](#25-insertion-sort)
    + [26. **Selection Sort**](#26-selection-sort)
    + [27. **Bubble Sort**](#27-bubble-sort)
    + [28. **Kadane’s Algorithm**](#28-kadane-s-algorithm)
    + [29. **Dutch National Flag Algorithm**](#29-dutch-national-flag-algorithm)
    + [30. **Moore’s Voting Algorithm**](#30-moore-s-voting-algorithm)
    + [31. **Check Permutation**](#31-check-permutation)
    + [32. **Intersection Of Two Arrays**](#32-intersection-of-two-arrays)
    + [33. **N/3 Repeated Number in Array**](#33-n-3-repeated-number-in-array)
    + [34. **Counting Sort**](#34-counting-sort)
    + [35. **Rotate Matrix To Right**](#35-rotate-matrix-to-right)
    + [36. **Find Kth Character of Decrypted String**](#36-find-kth-character-of-decrypted-string)
    + [37. **Move Zeroes To End**](#37-move-zeroes-to-end)
    + [38. **Sum of Two Elements Equals Third**](#38-sum-of-two-elements-equals-third)
    + [39. **Minimum Operations to Make String Equal**](#39-minimum-operations-to-make-string-equal)
    + [40. **Maximum Sum Circular Array**](#40-maximum-sum-circular-array)
    + [41. **Longest Consecutive Sequence**](#41-longest-consecutive-sequence)
    + [42. **Maximum Subarray Sum After K Concat**](#42-maximum-subarray-sum-after-k-concat)
    + [43. **Maximum Product Count**](#43-maximum-product-count)
    + [44. **Multiply Strings**](#44-multiply-strings)
    + [45. **Find All Subsquares of Size K**](#45-find-all-subsquares-of-size-k)
    + [46. **Repeat And Missing Number Array**](#46-repeat-and-missing-number-array)
    + [47. **4 Sum Problem**](#47-4-sum-problem)
    + [48. **Count All Subarrays With Given Sum**](#48-count-all-subarrays-with-given-sum)
    + [49. **Maximum Sum Rectangle**](#49-maximum-sum-rectangle)
    + [50. **Nth Element of Spiral Matrix**](#50-nth-element-of-spiral-matrix)
  * [Intermediate DSA - 75](#intermediate-dsa-75)
    + [1. **Square Root**](#1-square-root)
    + [2. **Search in Rotated Sorted Array**](#2-search-in-rotated-sorted-array)
    + [3. **Find Element that Appears Twice**](#3-find-element-that-appears-twice)
    + [4. **Matrix Median**](#4-matrix-median)
    + [5. **Aggressive Cows**](#5-aggressive-cows)
    + [6. **Merge Sort**](#6-merge-sort)
    + [7. **Quick Sort**](#7-quick-sort)
    + [8. **Find Kth Element**](#8-find-kth-element)
    + [9. **Family Structure**](#9-family-structure)
    + [10. **Binary String With No Consecutive 1s**](#10-binary-string-with-no-consecutive-1s)
    + [11. **Reverse a Linked List**](#11-reverse-a-linked-list)
    + [12. **Mid Point In Linked List**](#12-mid-point-in-linked-list)
    + [13. **Add Two Linked Lists**](#13-add-two-linked-lists)
    + [14. **Insertion Sort on Linked List**](#14-insertion-sort-on-linked-list)
    + [15. **Delete Kth Node from End**](#15-delete-kth-node-from-end)
    + [16. **Detect and Remove Cycle**](#16-detect-and-remove-cycle)
    + [17. **Swap Nodes in Pairs**](#17-swap-nodes-in-pairs)
    + [18. **Append Nodes**](#18-append-nodes)
    + [19. **Segregate Odd Even**](#19-segregate-odd-even)
    + [20. **Implement Stack Using Array**](#20-implement-stack-using-array)
    + [21. **Implement Stack Using Linked List**](#21-implement-stack-using-linked-list)
    + [22. **Implement Queue Using Array**](#22-implement-queue-using-array)
    + [23. **Implement Queue Using Linked List**](#23-implement-queue-using-linked-list)
    + [24. **Implement Queue Using 2 Stacks**](#24-implement-queue-using-2-stacks)
    + [25. **Implement Stack Using 2 Queues**](#25-implement-stack-using-2-queues)
    + [26. **Min Stack**](#26-min-stack)
    + [27. **Next Greater Element**](#27-next-greater-element)
    + [28. **Stock Span Problem**](#28-stock-span-problem)
    + [29. **Reverse Queue**](#29-reverse-queue)
    + [30. **Valid Parentheses**](#30-valid-parentheses)
    + [31. **Diameter Of Binary Tree**](#31-diameter-of-binary-tree)
    + [32. **LCA Of Binary Tree**](#32-lca-of-binary-tree)
    + [33. **Level Order Traversal Binary Tree**](#33-level-order-traversal-binary-tree)
    + [34. **ZigZag Order Traversal Binary Tree**](#34-zigzag-order-traversal-binary-tree)
    + [35. **Left View Of Binary Tree**](#35-left-view-of-binary-tree)
    + [36. **Top View Of Binary Tree**](#36-top-view-of-binary-tree)
    + [37. **Construct Binary Tree From Inorder And Preorder**](#37-construct-binary-tree-from-inorder-and-preorder)
    + [38. **Vertical Order Traversal Of Binary Tree**](#38-vertical-order-traversal-of-binary-tree)
    + [39. **Inorder Traversal Binary Tree Using Stacks**](#39-inorder-traversal-binary-tree-using-stacks)
    + [40. **LCA of Two Nodes in BST**](#40-lca-of-two-nodes-in-bst)
    + [41. **Check if Binary Tree is BST?**](#41-check-if-binary-tree-is-bst-)
    + [42. **Kth Smallest Element in BST**](#42-kth-smallest-element-in-bst)
    + [43. **Predecessor And Successor In BST**](#43-predecessor-and-successor-in-bst)
    + [44. **Pair Sum in BST**](#44-pair-sum-in-bst)
    + [45. **Find Whether Array is Subset of Another Array**](#45-find-whether-array-is-subset-of-another-array)
    + [46. **Median of 2 Sorted Arrays**](#46-median-of-2-sorted-arrays)
    + [47. **LCA of 3 Nodes**](#47-lca-of-3-nodes)
    + [48. **Remove Keys Outside Given Range**](#48-remove-keys-outside-given-range)
    + [49. **Search in a Row Wise and Column Wise Sorted Matrix**](#49-search-in-a-row-wise-and-column-wise-sorted-matrix)
    + [50. **Check Linked List is Palindrome?**](#50-check-linked-list-is-palindrome-)
    + [51. **K Reverse Linked List**](#51-k-reverse-linked-list)
    + [52. **Tower of Hanoi**](#52-tower-of-hanoi)
    + [53. **BST Iterator**](#53-bst-iterator)
    + [54. **Flatten Binary Tree To Linked List**](#54-flatten-binary-tree-to-linked-list)
    + [55. **Rearrange Linked List**](#55-rearrange-linked-list)
    + [56. **Largest Rectangle in Histogram**](#56-largest-rectangle-in-histogram)
    + [57. **Quick Sort on Linked List**](#57-quick-sort-on-linked-list)
    + [58. **Sorted Linked List to Balanced BST**](#58-sorted-linked-list-to-balanced-bst)
    + [59. **Binary Tree to Doubly Linked List**](#59-binary-tree-to-doubly-linked-list)
    + [60. **Bottom Right View of Binary Tree**](#60-bottom-right-view-of-binary-tree)
    + [61. **Merge Two BSTs**](#61-merge-two-bsts)
    + [62. **Merge Two Binary Trees**](#62-merge-two-binary-trees)
    + [63. **Sort a Stack**](#63-sort-a-stack)
    + [64. **Boundary Traversal of Binary Tree**](#64-boundary-traversal-of-binary-tree)
    + [65. **Longest Substring with K Distinct Characters**](#65-longest-substring-with-k-distinct-characters)
    + [66. **HashMap Implementation**](#66-hashmap-implementation)
    + [67. **Closest Distance Pair**](#67-closest-distance-pair)
    + [68. **Time to Burn Tree**](#68-time-to-burn-tree)
    + [69. **Allocate Books**](#69-allocate-books)
    + [70. **Clone a LinkedList with Random and Next Pointer**](#70-clone-a-linkedlist-with-random-and-next-pointer)
    + [71. **Fix BST**](#71-fix-bst)
    + [72. **Nth Root of Integer**](#72-nth-root-of-integer)
    + [73. **Size of the Largest BST**](#73-size-of-the-largest-bst)
    + [74. **LRU Cache**](#74-lru-cache)
    + [75. **Binary Tree to Doubly Linked List**](#75-binary-tree-to-doubly-linked-list)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


## HTML

### 1. HTML Basics

**Notes:**

- HTML (HyperText Markup Language) is the standard markup language for creating web pages.
- It structures content on the web and uses tags to define elements.
- An HTML document starts with `<!DOCTYPE html>`, followed by `<html>`, `<head>`, and `<body>` tags.

**Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First HTML Page</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is a paragraph.</p>
</body>
</html>

```

### 2. HTML Top Level Tags

**Notes:**

- `<html>`: Root element of an HTML page.
- `<head>`: Contains meta-information about the HTML document (e.g., title, meta tags, links to scripts and stylesheets).
- `<body>`: Contains the content of the HTML document (e.g., text, images, links).

**Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <title>Example Page</title>
</head>
<body>
    <h1>Example Content</h1>
    <p>This is an example paragraph.</p>
</body>
</html>

```

### 3. HTML Block & Inline Tags

**Notes:**

- Block-level elements: Always start on a new line and take up the full width available (e.g., `<div>`, `<h1>`, `<p>`, `<table>`).
- Inline elements: Do not start on a new line and only take up as much width as necessary (e.g., `<span>`, `<a>`, `<img>`).

**Example:**

```html
<div>
    <h1>Block Level Element</h1>
    <p>This is a block-level element.</p>
    <span>Inline Element</span>
    <a href="#">This is an inline element</a>
</div>

```

### 4. HTML Tables

**Notes:**

- Tables are used to display data in rows and columns.
- Common tags: `<table>`, `<tr>` (table row), `<td>` (table data), `<th>` (table header).

**Example:**

```html
<table border="1">
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Row 1, Cell 1</td>
        <td>Row 1, Cell 2</td>
    </tr>
    <tr>
        <td>Row 2, Cell 1</td>
        <td>Row 2, Cell 2</td>
    </tr>
</table>

```

### 5. HTML Forms

**Notes:**

- Forms are used to collect user input.
- Common tags: `<form>`, `<input>`, `<textarea>`, `<button>`, `<select>`, `<option>`.

**Example:**

```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">

    <label for="email">Email:</label>
    <input type="email" id="email" name="email">

    <input type="submit" value="Submit">
</form>

```

### 6. HTML Attributes

**Notes:**

- Attributes provide additional information about HTML elements.
- Common attributes: `id`, `class`, `style`, `src`, `href`, `alt`.

**Example:**

```html
<img src="image.jpg" alt="Example Image" width="500" height="600">
<a href="<https://www.example.com>" target="_blank">Visit Example</a>
<p id="paragraph1" class="text">This is a paragraph with an id and class attribute.</p>
```

## CSS

### 1. Basics of CSS

**Notes:**

- **CSS** (Cascading Style Sheets) controls the look and feel of HTML elements.
- CSS can be included in three ways:
    - **Inline Styles:** Directly in HTML elements using the `style` attribute.
    - **Internal Stylesheet:** Within the `<style>` tag in the `<head>` section of an HTML document.
    - **External Stylesheet:** Linked via the `<link>` tag, pointing to a `.css` file.

**Examples:**

- **Inline Styles:**
    
    ```html
    <p style="color: blue; font-size: 20px;">This is a blue colored text.</p>
    
    ```
    
- **Internal Stylesheet:**
    
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <style>
            body {
                background-color: lightgray;
            }
            h1 {
                color: darkblue;
            }
        </style>
    </head>
    <body>
        <h1>Internal CSS Example</h1>
    </body>
    </html>
    
    ```
    
- **External Stylesheet:**
Create a `styles.css` file:
    
    ```css
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
    }
    h1 {
        color: #333;
    }
    
    ```
    
    Link it in your HTML:
    
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <h1>External CSS Example</h1>
    </body>
    </html>
    
    ```
    

### 2. Box Model

**Notes:**

- The **Box Model** describes how elements are structured and spaced on a webpage.
- **Components:**
    - **Content:** The actual content (text, images) inside the box.
    - **Padding:** Space between the content and the border.
    - **Border:** Surrounds the padding (and content) area.
    - **Margin:** Space outside the border, separating elements from each other.

**Examples:**

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .box {
            width: 200px;
            height: 150px;
            padding: 20px;
            border: 5px solid black;
            margin: 15px;
            background-color: lightgreen;
        }
    </style>
</head>
<body>
    <div class="box">Box Model Example</div>
</body>
</html>

```

### 3. Sizing and Styling Elements

**Notes:**

- **Sizing:** Use `width`, `height`, `max-width`, `min-width`, `max-height`, `min-height` to control the size of elements.
- **Styling:** Adjust visual aspects using properties like `color`, `background-color`, `font-size`, `text-align`, `line-height`, `border-radius`, etc.

**Examples:**

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .box {
            width: 300px;
            height: 150px;
            background-color: #f4a261;
            color: white;
            font-size: 20px;
            text-align: center;
            line-height: 150px; /* Vertically center text */
            border-radius: 10px; /* Rounded corners */
        }
    </style>
</head>
<body>
    <div class="box">Styled Box</div>
</body>
</html>

```

### 4. Transitions and Animations

**Notes:**

- **Transitions** allow gradual changes of properties over a specified duration.
- **Animations** enable more complex movements and transformations using `@keyframes`.

**Transition Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .transition-box {
            width: 100px;
            height: 100px;
            background-color: blue;
            transition: background-color 0.5s ease;
        }
        .transition-box:hover {
            background-color: red;
        }
    </style>
</head>
<body>
    <div class="transition-box"></div>
</body>
</html>

```

**Animation Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        @keyframes slide {
            from { transform: translateX(0); }
            to { transform: translateX(100px); }
        }
        .animated-box {
            width: 100px;
            height: 100px;
            background-color: green;
            animation: slide 2s infinite;
        }
    </style>
</head>
<body>
    <div class="animated-box"></div>
</body>
</html>

```

### 5. Responsive Design

**Notes:**

- **Flexbox**: A layout model for aligning items in a flexible container.
- **Grid**: A layout model for creating complex, responsive grid-based designs.
- **Media Queries**: Apply different styles based on device characteristics (e.g., screen width).

**Flexbox Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .flex-container {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 100vh;
            background-color: #e0e0e0;
        }
        .flex-item {
            background-color: lightcoral;
            padding: 20px;
            margin: 10px;
            flex: 1;
        }
    </style>
</head>
<body>
    <div class="flex-container">
        <div class="flex-item">Item 1</div>
        <div class="flex-item">Item 2</div>
        <div class="flex-item">Item 3</div>
    </div>
</body>
</html>

```

**Grid Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .grid-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            background-color: #f0f0f0;
        }
        .grid-item {
            background-color: lightblue;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="grid-container">
        <div class="grid-item">Grid Item 1</div>
        <div class="grid-item">Grid Item 2</div>
        <div class="grid-item">Grid Item 3</div>
    </div>
</body>
</html>

```

**Media Queries Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .responsive-box {
            width: 100%;
            height: 200px;
            background-color: lightcoral;
        }
        @media (max-width: 600px) {
            .responsive-box {
                background-color: lightblue;
                height: 150px;
            }
        }
    </style>
</head>
<body>
    <div class="responsive-box"></div>
</body>
</html>
```

### Responsive Design in Detail

### 1. **Understanding Responsive Design**

**Responsive Design** ensures that a website adapts to different screen sizes, orientations, and resolutions. It improves user experience by providing a layout that adjusts dynamically, whether the user is on a desktop, tablet, or smartphone.

**Key Principles:**

- **Fluid Grids:** Use relative units like percentages rather than fixed units like pixels to create flexible layouts.
- **Flexible Images:** Ensure images resize within their containing elements without breaking the layout.
- **Media Queries:** Apply different styles based on the device’s characteristics (e.g., screen width, resolution).

### 2. **Fluid Grids**

**Concept:**

- A fluid grid uses relative units (like percentages) instead of fixed units (like pixels). This allows elements to resize proportionally based on the viewport width.

**Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .container {
            width: 100%;
            margin: 0 auto;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .column {
            float: left;
            width: 50%;
            padding: 10px;
            box-sizing: border-box;
        }
        @media (max-width: 600px) {
            .column {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="column" style="background-color: lightcoral;">Column 1</div>
        <div class="column" style="background-color: lightblue;">Column 2</div>
    </div>
</body>
</html>

```

### 3. **Flexible Images**

**Concept:**

- Images should scale within their containers. This prevents images from overflowing or distorting the layout on different devices.

**Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .responsive-img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <img src="image.jpg" alt="Responsive Image" class="responsive-img">
</body>
</html>

```

### 4. **Media Queries**

**Concept:**

- Media queries apply CSS styles based on the viewport’s characteristics. They enable different styles for different screen sizes or orientations.

**Syntax:**

```css
@media (condition) {
    /* CSS rules */
}

```

**Examples:**

- **Basic Media Query for Screen Width:**
    
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <style>
            body {
                font-family: Arial, sans-serif;
            }
            .container {
                width: 80%;
                margin: 0 auto;
                background-color: #f4f4f4;
                padding: 20px;
            }
            @media (max-width: 768px) {
                .container {
                    width: 95%;
                }
            }
            @media (max-width: 480px) {
                body {
                    font-size: 14px;
                }
            }
        </style>
    </head>
    <body>
        <div class="container">
            <h1>Responsive Design Example</h1>
            <p>This text will adjust based on the screen size.</p>
        </div>
    </body>
    </html>
    
    ```
    
- **Media Query for Device Orientation:**
    
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <style>
            .landscape {
                background-color: lightgreen;
            }
            .portrait {
                background-color: lightcoral;
            }
            @media (orientation: landscape) {
                body {
                    background-color: lightgreen;
                }
            }
            @media (orientation: portrait) {
                body {
                    background-color: lightcoral;
                }
            }
        </style>
    </head>
    <body>
        <h1>Orientation Based Styling</h1>
    </body>
    </html>
    
    ```
    

### 5. **Responsive Frameworks**

**Concept:**

- Frameworks like **Bootstrap** and **Foundation** offer pre-built responsive grid systems and components, simplifying the process of creating responsive designs.

**Bootstrap Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="<https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css>">
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col-md-6">Column 1</div>
            <div class="col-md-6">Column 2</div>
        </div>
    </div>
</body>
</html>

```

### 6. **Viewport Meta Tag**

**Concept:**

- The viewport meta tag controls the layout on mobile browsers. It ensures that the page scales correctly to fit the screen width.

**Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body {
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
    <h1>Viewport Meta Tag Example</h1>
    <p>This page will scale properly on mobile devices.</p>
</body>
</html>

```

### Summary

To create responsive websites, focus on using:

- **Fluid grids** for flexible layouts.
- **Flexible images** to ensure images scale appropriately.
- **Media queries** to apply different styles based on screen size and device characteristics.
- **Responsive frameworks** for pre-built components and grid systems.
- **Viewport meta tag** to control layout on mobile devices.

These techniques will help ensure your website looks and functions well across a wide range of devices and screen sizes.

## JavaScript

### 1. Intro to JavaScript

**Notes:**

- **JavaScript** is a high-level, interpreted scripting language primarily used to create dynamic content on web pages.
- It can manipulate the DOM (Document Object Model), handle events, and interact with web servers.
- JavaScript is executed on the client side (in the browser) but can also be used on the server side with environments like Node.js.

**Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <title>JavaScript Intro</title>
</head>
<body>
    <h1 id="greeting">Hello!</h1>
    <script>
        // JavaScript code
        document.getElementById('greeting').innerText = 'Hello, World!';
    </script>
</body>
</html>

```

### 2. Variables and Data Types

**Notes:**

- **Variables** store data values. JavaScript uses `let`, `const`, and `var` for variable declarations.
- **Data Types:** JavaScript has several types, including:
    - **Primitive Types:** `string`, `number`, `boolean`, `undefined`, `null`, `symbol` (ES6), and `bigint` (ES11).
    - **Complex Types:** `object`, `array`, `function`.

**Examples:**

- **Declaring Variables:**
    
    ```jsx
    let name = 'Alice'; // String
    const age = 30;     // Number
    var isStudent = true; // Boolean
    
    ```
    
- **Data Types:**
    
    ```jsx
    let undefinedVar; // Undefined
    let nullVar = null; // Null
    let symbolVar = Symbol('description'); // Symbol (ES6)
    let bigIntVar = 1234567890123456789012345678901234567890n; // BigInt (ES11)
    
    ```
    
- **Array:**
    
    ```jsx
    let fruits = ['Apple', 'Banana', 'Cherry'];
    
    ```
    
- **Object:**
    
    ```jsx
    let person = {
        name: 'John',
        age: 25,
        greet: function() { return 'Hello!'; }
    };
    
    ```
    

### 3. If/Else & Loops

**Notes:**

- **If/Else Statements** control the flow of code based on conditions.
- **Loops** are used to repeat code multiple times. Common loops include `for`, `while`, and `do...while`.

**Examples:**

- **If/Else Statement:**
    
    ```jsx
    let score = 85;
    
    if (score >= 90) {
        console.log('A');
    } else if (score >= 80) {
        console.log('B');
    } else {
        console.log('C');
    }
    
    ```
    
- **For Loop:**
    
    ```jsx
    for (let i = 0; i < 5; i++) {
        console.log(i); // Prints numbers 0 to 4
    }
    
    ```
    
- **While Loop:**
    
    ```jsx
    let i = 0;
    while (i < 5) {
        console.log(i); // Prints numbers 0 to 4
        i++;
    }
    
    ```
    
- **Do...While Loop:**
    
    ```jsx
    let i = 0;
    do {
        console.log(i); // Prints numbers 0 to 4
        i++;
    } while (i < 5);
    
    ```
    

### 4. Functions

**Notes:**

- **Functions** are blocks of code designed to perform a particular task. They can take inputs (parameters) and return outputs.
- JavaScript functions can be declared in various ways: function declarations, function expressions, and arrow functions.

**Examples:**

- **Function Declaration:**
    
    ```jsx
    function greet(name) {
        return 'Hello, ' + name;
    }
    console.log(greet('Alice')); // Output: Hello, Alice
    
    ```
    
- **Function Expression:**
    
    ```jsx
    const add = function(a, b) {
        return a + b;
    };
    console.log(add(5, 3)); // Output: 8
    
    ```
    
- **Arrow Function:**
    
    ```jsx
    const multiply = (a, b) => a * b;
    console.log(multiply(4, 6)); // Output: 24
    
    ```
    

### 5. OOPS in JS

**Notes:**

- **Object-Oriented Programming (OOP)** in JavaScript uses prototypes and ES6 classes to create objects and manage inheritance.
- Key concepts include **classes**, **objects**, **inheritance**, and **polymorphism**.

**Examples:**

- **Class Declaration (ES6):**
    
    ```jsx
    class Animal {
        constructor(name) {
            this.name = name;
        }
        speak() {
            return this.name + ' makes a noise.';
        }
    }
    
    class Dog extends Animal {
        speak() {
            return this.name + ' barks.';
        }
    }
    
    const dog = new Dog('Rex');
    console.log(dog.speak()); // Output: Rex barks.
    
    ```
    
- **Prototype-based Inheritance:**
    
    ```jsx
    function Animal(name) {
        this.name = name;
    }
    
    Animal.prototype.speak = function() {
        return this.name + ' makes a noise.';
    };
    
    function Dog(name) {
        Animal.call(this, name);
    }
    
    Dog.prototype = Object.create(Animal.prototype);
    Dog.prototype.speak = function() {
        return this.name + ' barks.';
    };
    
    const dog = new Dog('Rex');
    console.log(dog.speak()); // Output: Rex barks.
    
    ```
    

### 6. Important Concepts in JS

**Notes:**

- **Closures:** Functions that retain access to their lexical scope even after execution.
- **Promises:** Objects representing the eventual completion (or failure) of an asynchronous operation.
- **Async/Await:** Syntactic sugar for working with promises, making asynchronous code easier to write and read.

**Examples:**

- **Closure:**
    
    ```jsx
    function makeCounter() {
        let count = 0;
        return function() {
            count++;
            return count;
        };
    }
    
    const counter = makeCounter();
    console.log(counter()); // Output: 1
    console.log(counter()); // Output: 2
    
    ```
    
- **Promise:**
    
    ```jsx
    const fetchData = new Promise((resolve, reject) => {
        setTimeout(() => {
            resolve('Data received');
        }, 2000);
    });
    
    fetchData.then((data) => {
        console.log(data); // Output: Data received
    }).catch((error) => {
        console.error(error);
    });
    
    ```
    
- **Async/Await:**
    
    ```jsx
    async function fetchData() {
        return 'Data received';
    }
    
    async function showData() {
        const data = await fetchData();
        console.log(data); // Output: Data received
    }
    
    showData();
    
    ```
    

### 7. JavaScript for Web

**Notes:**

- JavaScript can interact with HTML and CSS through the **DOM** (Document Object Model).
- Common tasks include **event handling**, **manipulating DOM elements**, and **making HTTP requests**.

**Examples:**

- **Event Handling:**
    
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <title>Event Handling</title>
    </head>
    <body>
        <button id="clickMe">Click Me</button>
        <script>
            document.getElementById('clickMe').addEventListener('click', () => {
                alert('Button clicked!');
            });
        </script>
    </body>
    </html>
    
    ```
    
- **Manipulating DOM Elements:**
    
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <title>DOM Manipulation</title>
    </head>
    <body>
        <p id="demo">Original Text</p>
        <button id="changeText">Change Text</button>
        <script>
            document.getElementById('changeText').addEventListener('click', () => {
                document.getElementById('demo').innerText = 'Text Changed!';
            });
        </script>
    </body>
    </html>
    
    ```
    
- **Making HTTP Requests:**
    
    ```jsx
    fetch('<https://jsonplaceholder.typicode.com/posts/1>')
        .then(response => response.json())
        .then(data => console.log(data))
        .catch(error => console.error('Error:', error));
    
    ```
    

### Summary

- **Intro to JavaScript:** Basics of JavaScript and its usage in web development.
- **Variables and Data Types:** Declaring variables and understanding data types.
- **If/Else & Loops:** Control flow and iteration with conditional statements and loops.
- **Functions:** Creating and using functions in JavaScript.
- **OOPS in JS:** Object-oriented programming concepts using prototypes and ES6 classes.
- **Important Concepts in JS:** Advanced topics like closures, promises, and async/await.
- **JavaScript for Web:** Interacting with the DOM, handling events, and making HTTP requests.

## React

### Creating a Simple React Project

### 1. **Set Up Your Environment**

To create a React project, you'll need Node.js and npm (Node Package Manager) installed on your computer.

- **Install Node.js and npm:** Visit [nodejs.org](https://nodejs.org/) and download the installer for your operating system. This will also install npm.

### 2. **Create a New React Application**

You can create a new React project using the Create React App tool, which sets up a React project with a modern build setup.

1. **Open your terminal or command prompt.**
2. **Run the following command to create a new React app:**
    
    ```bash
    npx create-react-app my-react-app
    
    ```
    
    - `npx` is a package runner tool that comes with npm.
    - `create-react-app` is a command-line tool to generate a new React project.
    - `my-react-app` is the name of your new project. You can choose any name you like.
3. **Navigate to your project directory:**
    
    ```bash
    cd my-react-app
    
    ```
    
4. **Start the development server:**
    
    ```bash
    npm start
    
    ```
    
    This will open your new React application in the default web browser, typically at `http://localhost:3000`.
    

### 3. **Project Structure**

Here’s a brief overview of the default project structure created by Create React App:

- `public/`: Contains the static files, including `index.html`.
- `src/`: Contains your React components and styles.
    - `index.js`: The entry point for your React application.
    - `App.js`: The main App component.
- `package.json`: Manages project dependencies and scripts.

### 4. **Modify the Default App**

You can start modifying your application by editing `App.js` in the `src/` directory.

**Example: Modifying `App.js`:**

```jsx
import React from 'react';
import './App.css';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <h1>Welcome to My React App</h1>
        <p>This is a simple React application.</p>
      </header>
    </div>
  );
}

export default App;

```

- **`import React from 'react';`**: Imports the React library.
- **`import './App.css';`**: Imports the CSS file for styling.
- **`function App() { ... }`**: Defines a functional component named `App`.
- **`export default App;`**: Exports the `App` component so it can be used in other files.

### 5. **Add More Components**

You can create additional components and use them in your app.

**Example: Creating a New Component**

1. **Create a new file `Greeting.js` in the `src/` directory:**
    
    ```jsx
    // src/Greeting.js
    import React from 'react';
    
    function Greeting(props) {
      return <h2>Hello, {props.name}!</h2>;
    }
    
    export default Greeting;
    
    ```
    
2. **Use the new component in `App.js`:**
    
    ```jsx
    import React from 'react';
    import './App.css';
    import Greeting from './Greeting';
    
    function App() {
      return (
        <div className="App">
          <header className="App-header">
            <h1>Welcome to My React App</h1>
            <Greeting name="Alice" />
          </header>
        </div>
      );
    }
    
    export default App;
    
    ```
    

### 6. **Styling Your Application**

You can add styles to your application using CSS. Create or edit `.css` files in the `src/` directory and import them into your components.

**Example: Styling with `App.css`:**

```css
/* src/App.css */
.App {
  text-align: center;
}

.App-logo {
  height: 40vmin;
}

.App-header {
  background-color: #282c34;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: white;
}

```

### 7. **Build and Deploy**

Once you are ready to deploy your application:

1. **Create a production build:**
    
    ```bash
    npm run build
    
    ```
    
    This creates a `build/` directory with a production-optimized version of your application.
    
2. **Deploy your build folder** to a web server or a static site hosting service like Vercel, Netlify, or GitHub Pages.

### Summary

1. **Set up your environment** by installing Node.js and npm.
2. **Create a new React project** using Create React App.
3. **Understand the project structure** and modify default files.
4. **Create and use new components** in your application.
5. **Style your application** with CSS.
6. **Build and deploy** your application when ready.

This guide covers the basics of creating and modifying a simple React application.

### 1. States

**Notes:**

- **State** in React is an object that holds data that can influence the rendering of components.
- **State** is managed within a component and can be updated using the `setState` method in class components or `useState` hook in functional components.

**Examples:**

- **Class Component:**
    
    ```jsx
    import React, { Component } from 'react';
    
    class Counter extends Component {
        constructor(props) {
            super(props);
            this.state = { count: 0 };
        }
    
        increment = () => {
            this.setState({ count: this.state.count + 1 });
        };
    
        render() {
            return (
                <div>
                    <p>Count: {this.state.count}</p>
                    <button onClick={this.increment}>Increment</button>
                </div>
            );
        }
    }
    
    export default Counter;
    
    ```
    
- **Functional Component with Hooks:**
    
    ```jsx
    import React, { useState } from 'react';
    
    function Counter() {
        const [count, setCount] = useState(0);
    
        const increment = () => {
            setCount(count + 1);
        };
    
        return (
            <div>
                <p>Count: {count}</p>
                <button onClick={increment}>Increment</button>
            </div>
        );
    }
    
    export default Counter;
    
    ```
    

### 2. Components

**Notes:**

- **Components** are the building blocks of a React application. They can be functional or class-based.
- **Functional Components** are simpler and primarily use hooks for state and lifecycle methods.
- **Class Components** are more feature-rich but can be more complex.

**Examples:**

- **Functional Component:**
    
    ```jsx
    import React from 'react';
    
    function Greeting(props) {
        return <h1>Hello, {props.name}!</h1>;
    }
    
    export default Greeting;
    
    ```
    
- **Class Component:**
    
    ```jsx
    import React, { Component } from 'react';
    
    class Greeting extends Component {
        render() {
            return <h1>Hello, {this.props.name}!</h1>;
        }
    }
    
    export default Greeting;
    
    ```
    

### 3. Hooks

**Notes:**

- **Hooks** are functions that let you use state and other React features in functional components.
- **Common Hooks:**
    - `useState` for managing state.
    - `useEffect` for performing side effects.
    - `useContext` for context management.
    - `useReducer` for more complex state logic.

**Examples:**

- **useState:**
    
    ```jsx
    import React, { useState } from 'react';
    
    function Toggle() {
        const [isToggled, setIsToggled] = useState(false);
    
        return (
            <button onClick={() => setIsToggled(!isToggled)}>
                {isToggled ? 'On' : 'Off'}
            </button>
        );
    }
    
    export default Toggle;
    
    ```
    
- **useEffect:**
    
    ```jsx
    import React, { useState, useEffect } from 'react';
    
    function FetchData() {
        const [data, setData] = useState(null);
    
        useEffect(() => {
            fetch('<https://api.example.com/data>')
                .then(response => response.json())
                .then(data => setData(data));
        }, []); // Empty dependency array means this runs once on mount
    
        return (
            <div>
                <h1>Data:</h1>
                <pre>{JSON.stringify(data, null, 2)}</pre>
            </div>
        );
    }
    
    export default FetchData;
    
    ```
    

### 4. Router

**Notes:**

- **React Router** is a library for handling routing in React applications. It allows for navigation between different views or pages.
- Key components include:
    - `<BrowserRouter>`: The router component that uses HTML5 history API.
    - `<Route>`: Defines a route with a path and a component to render.
    - `<Link>`: Provides navigation links.

**Examples:**

- **Basic Routing:**
    
    ```jsx
    import React from 'react';
    import { BrowserRouter as Router, Route, Switch, Link } from 'react-router-dom';
    
    function Home() {
        return <h2>Home Page</h2>;
    }
    
    function About() {
        return <h2>About Page</h2>;
    }
    
    function App() {
        return (
            <Router>
                <nav>
                    <ul>
                        <li><Link to="/">Home</Link></li>
                        <li><Link to="/about">About</Link></li>
                    </ul>
                </nav>
    
                <Switch>
                    <Route path="/" exact component={Home} />
                    <Route path="/about" component={About} />
                </Switch>
            </Router>
        );
    }
    
    export default App;
    
    ```
    

### Summary

- **States:** Manage component data and influence rendering. Use `useState` in functional components or `setState` in class components.
- **Components:** Building blocks of React applications. Can be functional or class-based.
- **Hooks:** Functions for using state and other React features in functional components (`useState`, `useEffect`, etc.).
- **Router:** Handle routing and navigation between different pages or views in a React application with components like `<BrowserRouter>`, `<Route>`, and `<Link>`.

## Git/GitHub

### 1. **Getting Started**

**Notes:**

- **Git** is a version control system for tracking changes in source code during software development.
- **GitHub** is a platform for hosting and collaborating on Git repositories.

**Setup:**

1. **Install Git:**
    - Download from [git-scm.com](https://git-scm.com/) and follow the installation instructions for your operating system.
2. **Configure Git:**
    
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    
    ```
    
3. **Create a GitHub account:**
    - Sign up at [github.com](https://github.com/).
4. **Create a new repository on GitHub:**
    - Go to GitHub, click "New" to create a repository, name it, and initialize it.

### 2. **Git First Commands**

**Notes:**

- **Initialize a Repository:** Start tracking a project with Git.
- **Clone a Repository:** Copy an existing repository to your local machine.
- **Add Changes:** Stage files for committing.
- **Commit Changes:** Save changes to the local repository.

**Examples:**

- **Initialize a Repository:**
    
    ```bash
    mkdir my-project
    cd my-project
    git init
    
    ```
    
- **Clone a Repository:**
    
    ```bash
    git clone <https://github.com/username/repository.git>
    
    ```
    
- **Add Changes:**
    
    ```bash
    git add filename  # Add a specific file
    git add .         # Add all changes in the current directory
    
    ```
    
- **Commit Changes:**
    
    ```bash
    git commit -m "Initial commit"
    
    ```
    

### 3. **Git Activity Commands**

**Notes:**

- **Check Status:** See untracked, staged, and modified files.
- **View History:** Look at the commit history.

**Examples:**

- **Check Status:**
    
    ```bash
    git status
    
    ```
    
- **View History:**
    
    ```bash
    git log
    
    ```
    

### 4. **Git Change**

**Notes:**

- **View Changes:** See what has been modified.
- **Undo Changes:** Revert modifications or unstage files.

**Examples:**

- **View Changes:**
    
    ```bash
    git diff            # Show changes in working directory
    git diff --staged   # Show changes in staged area
    
    ```
    
- **Undo Changes:**
    
    ```bash
    git checkout -- filename   # Discard changes in a specific file
    git reset HEAD filename    # Unstage a file
    
    ```
    

### 5. **Git Branch**

**Notes:**

- **Branching:** Create separate lines of development.
- **Merging:** Integrate changes from different branches.

**Examples:**

- **Create a Branch:**
    
    ```bash
    git branch new-branch
    
    ```
    
- **Switch Branches:**
    
    ```bash
    git checkout new-branch
    
    ```
    
- **Create and Switch Branch:**
    
    ```bash
    git checkout -b new-branch
    
    ```
    
- **Merge Branches:**
    
    ```bash
    git checkout main
    git merge new-branch
    
    ```
    

### 6. **Git Local**

**Notes:**

- **Local Repository:** Refers to the repository on your local machine.
- **Fetch Changes:** Update local repository with remote changes.
- **Push Changes:** Upload local changes to the remote repository.

**Examples:**

- **Fetch Changes:**
    
    ```bash
    git fetch origin
    
    ```
    
- **Pull Changes (Fetch + Merge):**
    
    ```bash
    git pull origin main
    
    ```
    
- **Push Changes:**
    
    ```bash
    git push origin main
    
    ```
    

### Summary

- **Getting Started:** Install and configure Git; set up GitHub.
- **Git First Commands:** Initialize, clone, add, and commit.
- **Git Activity Commands:** Check status and view history.
- **Git Change:** View and undo changes.
- **Git Branch:** Create, switch, and merge branches.
- **Git Local:** Fetch, pull, and push changes.

## Basic SEO Principles

### 1. **On-Page Optimization**

**Notes:**

- **On-Page Optimization** refers to the practices used directly within a website to improve its position in search rankings.
- Key elements include content quality, keyword placement, and user experience.

**Examples:**

- **Title Tags:**
    
    ```html
    <title>Best Practices for SEO | MyWebsite</title>
    
    ```
    
    - Include primary keywords and keep it under 60 characters.
- **Meta Descriptions:**
    
    ```html
    <meta name="description" content="Learn the best practices for on-page SEO to improve your website's search engine ranking.">
    
    ```
    
    - Summarize the page content in 150-160 characters.
- **Headings (H1, H2, H3, etc.):**
    
    ```html
    <h1>On-Page SEO Optimization</h1>
    <h2>Why On-Page SEO Matters</h2>
    <h3>Content Quality and Keywords</h3>
    
    ```
    
- **Content Quality:**
    - Write high-quality, relevant content that addresses users' needs and includes keywords naturally.

### 2. **Meta Keywords**

**Notes:**

- **Meta Keywords** were used to specify keywords relevant to the page content. However, they are largely obsolete as search engines have evolved.
- Focus more on **relevant content** and **user experience**.

**Examples:**

- **Meta Keywords (historical use):**
    
    ```html
    <meta name="keywords" content="SEO, search engine optimization, digital marketing">
    
    ```
    

**Current Best Practices:**

- Use **keyword research** to inform content and headings.
- Prioritize **user intent** and **high-quality content** over meta keywords.

### 3. **SEO Images**

**Notes:**

- **SEO for Images** helps search engines understand the content of images, improving page visibility and load times.

**Examples:**

- **Alt Text:**
    
    ```html
    <img src="seo-tips.jpg" alt="SEO tips for improving website rankings">
    
    ```
    
    - Describe the image content in a few words.
- **File Names:**
    
    ```html
    <img src="seo-best-practices.jpg" alt="SEO best practices">
    
    ```
    
    - Use descriptive, hyphenated filenames.
- **Image Size:**
    - Optimize image size for faster loading times. Use formats like JPEG for photos and PNG for graphics.
- **Image Sitemap:**
    - Include images in your XML sitemap for better indexing.

### 4. **SEO Internal Link Building**

**Notes:**

- **Internal Link Building** helps users and search engines navigate your website and establish a site hierarchy.

**Examples:**

- **Linking Within Content:**
    
    ```html
    <a href="/seo-optimization">Learn more about SEO optimization techniques.</a>
    
    ```
    
    - Link to relevant internal pages.
- **Anchor Text:**
    
    ```html
    <a href="/seo-guide">SEO Guide</a>
    
    ```
    
    - Use descriptive anchor text relevant to the linked page.
- **Sitemap Page:**
    - Create an internal sitemap to help users and search engines find pages.

### 5. **SEO Site Map**

**Notes:**

- **Sitemap** helps search engines discover and index all the pages on your site.

**Examples:**

- **XML Sitemap:**
    - Create an XML file with a list of all your site's pages. Submit this file to search engines through their webmaster tools.
    
    ```xml
    <?xml version="1.0" encoding="UTF-8"?>
    <urlset xmlns="<http://www.sitemaps.org/schemas/sitemap/0.9>">
      <url>
        <loc><https://www.example.com/></loc>
        <lastmod>2024-08-05</lastmod>
        <changefreq>daily</changefreq>
        <priority>1.0</priority>
      </url>
      <url>
        <loc><https://www.example.com/about></loc>
        <lastmod>2024-08-01</lastmod>
        <changefreq>monthly</changefreq>
        <priority>0.8</priority>
      </url>
    </urlset>
    
    ```
    
- **HTML Sitemap:**
    - Create a page listing links to all important pages of your site for users and search engines.
    
    ```html
    <h1>Site Map</h1>
    <ul>
      <li><a href="/">Home</a></li>
      <li><a href="/about">About Us</a></li>
      <li><a href="/services">Services</a></li>
      <li><a href="/contact">Contact</a></li>
    </ul>
    
    ```
    

### Summary

- **On-Page Optimization:** Focus on title tags, meta descriptions, headings, and high-quality content.
- **Meta Keywords:** Largely obsolete; focus on content and user experience.
- **SEO Images:** Use descriptive alt text, optimized file names, and appropriate file sizes.
- **SEO Internal Link Building:** Improve navigation and site hierarchy with relevant internal links.
- **SEO Site Map:** Create and submit XML sitemaps, and provide HTML sitemaps for user navigation.

## Intermediate React

### 1. **useReducer**

**Notes:**

- **`useReducer`** is a React Hook used for managing complex state logic in functional components.
- It is an alternative to `useState`, providing a more predictable way to manage state changes, especially when state logic becomes more complex.

**Examples:**

- **Basic Usage:**
    
    ```jsx
    import React, { useReducer } from 'react';
    
    const initialState = { count: 0 };
    
    function reducer(state, action) {
      switch (action.type) {
        case 'increment':
          return { count: state.count + 1 };
        case 'decrement':
          return { count: state.count - 1 };
        default:
          throw new Error();
      }
    }
    
    function Counter() {
      const [state, dispatch] = useReducer(reducer, initialState);
    
      return (
        <div>
          <p>Count: {state.count}</p>
          <button onClick={() => dispatch({ type: 'increment' })}>Increment</button>
          <button onClick={() => dispatch({ type: 'decrement' })}>Decrement</button>
        </div>
      );
    }
    
    export default Counter;
    
    ```
    
- **How It Works:**
    - **`useReducer`** accepts a reducer function and an initial state.
    - **Reducer Function**: Receives the current state and an action, returns a new state.
    - **`dispatch` Function**: Dispatches actions to the reducer to update the state.

### 2. **Redux States**

**Notes:**

- **Redux** is a state management library for JavaScript applications.
- It provides a single global state (store) and uses actions and reducers to manage state changes.

**Key Concepts:**

- **Store**: Holds the application's state.
- **Actions**: Plain JavaScript objects describing changes.
- **Reducers**: Functions that specify how the state changes in response to actions.

**Examples:**

- **Create a Redux Store:**
    
    ```jsx
    import { createStore } from 'redux';
    
    const initialState = { count: 0 };
    
    function counterReducer(state = initialState, action) {
      switch (action.type) {
        case 'INCREMENT':
          return { count: state.count + 1 };
        case 'DECREMENT':
          return { count: state.count - 1 };
        default:
          return state;
      }
    }
    
    const store = createStore(counterReducer);
    
    ```
    

### 3. **Concepts of Redux**

**Notes:**

- **Actions**: Describe what happened in the application.
- **Reducers**: Handle state changes based on actions.
- **Dispatch**: Sends actions to the store.
- **Selectors**: Functions to retrieve data from the state.

**Examples:**

- **Action Creator:**
    
    ```jsx
    // actions.js
    export const increment = () => ({
      type: 'INCREMENT'
    });
    
    export const decrement = () => ({
      type: 'DECREMENT'
    });
    
    ```
    
- **Reducer Example:**
    
    ```jsx
    // reducer.js
    const initialState = { count: 0 };
    
    function counterReducer(state = initialState, action) {
      switch (action.type) {
        case 'INCREMENT':
          return { count: state.count + 1 };
        case 'DECREMENT':
          return { count: state.count - 1 };
        default:
          return state;
      }
    }
    
    export default counterReducer;
    
    ```
    
- **Dispatching Actions:**
    
    ```jsx
    // Inside a component
    import { useDispatch } from 'react-redux';
    import { increment, decrement } from './actions';
    
    function Counter() {
      const dispatch = useDispatch();
    
      return (
        <div>
          <button onClick={() => dispatch(increment())}>Increment</button>
          <button onClick={() => dispatch(decrement())}>Decrement</button>
        </div>
      );
    }
    
    ```
    

### 4. **Async Logic and Data Fetching in Redux**

**Notes:**

- **Async Logic**: Use middleware like Redux Thunk or Redux Saga for handling asynchronous actions.
- **Redux Thunk** is a common middleware for managing async actions.

**Examples:**

- **Setting Up Redux Thunk:**
    
    ```bash
    npm install redux-thunk
    
    ```
    
    ```jsx
    // store.js
    import { createStore, applyMiddleware } from 'redux';
    import thunk from 'redux-thunk';
    import counterReducer from './reducer';
    
    const store = createStore(counterReducer, applyMiddleware(thunk));
    
    ```
    
- **Async Action with Redux Thunk:**
    
    ```jsx
    // actions.js
    export const fetchData = () => {
      return async (dispatch) => {
        dispatch({ type: 'FETCH_REQUEST' });
        try {
          const response = await fetch('<https://api.example.com/data>');
          const data = await response.json();
          dispatch({ type: 'FETCH_SUCCESS', payload: data });
        } catch (error) {
          dispatch({ type: 'FETCH_FAILURE', payload: error.message });
        }
      };
    };
    
    ```
    
- **Reducer Handling Async Actions:**
    
    ```jsx
    // reducer.js
    const initialState = { data: [], loading: false, error: null };
    
    function dataReducer(state = initialState, action) {
      switch (action.type) {
        case 'FETCH_REQUEST':
          return { ...state, loading: true };
        case 'FETCH_SUCCESS':
          return { ...state, loading: false, data: action.payload };
        case 'FETCH_FAILURE':
          return { ...state, loading: false, error: action.payload };
        default:
          return state;
      }
    }
    
    export default dataReducer;
    
    ```
    

### Summary

- **`useReducer`**: Manages complex state logic in functional components.
- **Redux States**: Manages global state with actions, reducers, and dispatch.
- **Concepts of Redux**: Includes actions, reducers, and selectors.
- **Async Logic and Data Fetching**: Handles async actions with middleware like Redux Thunk.

## Testing Tools

### 1. **JEST Testing**

**Notes:**

- **JEST** is a JavaScript testing framework developed by Facebook, used for testing React applications and other JavaScript code.
- It provides features like zero-config setup, snapshot testing, and mocking.

**Key Features:**

- **Snapshot Testing:** Capture the UI component's rendered output and compare it to previous snapshots.
- **Mocking:** Replace dependencies with mock functions to test components in isolation.
- **Asynchronous Testing:** Handle async code with built-in support for Promises and async/await.

**Examples:**

- **Basic Test:**
    
    ```jsx
    // sum.js
    function sum(a, b) {
      return a + b;
    }
    module.exports = sum;
    
    ```
    
    ```jsx
    // sum.test.js
    const sum = require('./sum');
    
    test('adds 1 + 2 to equal 3', () => {
      expect(sum(1, 2)).toBe(3);
    });
    
    ```
    
- **Snapshot Testing:**
    
    ```jsx
    import React from 'react';
    import renderer from 'react-test-renderer';
    import MyComponent from './MyComponent';
    
    test('renders correctly', () => {
      const tree = renderer.create(<MyComponent />).toJSON();
      expect(tree).toMatchSnapshot();
    });
    
    ```
    
- **Mocking:**
    
    ```jsx
    // fetch.js
    export function fetchData() {
      return fetch('<https://api.example.com/data>').then(response => response.json());
    }
    
    ```
    
    ```jsx
    // fetch.test.js
    import { fetchData } from './fetch';
    
    jest.mock('./fetch', () => ({
      fetchData: jest.fn(() => Promise.resolve({ data: 'mocked data' }))
    }));
    
    test('fetchData returns mocked data', async () => {
      const data = await fetchData();
      expect(data).toEqual({ data: 'mocked data' });
    });
    
    ```
    

### 2. **Cross-Browser Testing**

**Notes:**

- **Cross-Browser Testing** ensures that a website or web application functions correctly across different browsers and devices.
- It helps identify inconsistencies in rendering, functionality, and performance.

**Key Tools:**

- **BrowserStack:** Provides real browsers and devices for testing.
- **Sauce Labs:** Cloud-based testing platform with browser and device support.
- **Selenium:** Open-source tool for automated browser testing.

**Examples:**

- **Manual Testing:**
    - Open your website in different browsers (Chrome, Firefox, Safari, Edge) and test its functionality and appearance.
- **Automated Testing with Selenium:**
    
    ```python
    from selenium import webdriver
    
    driver = webdriver.Chrome()
    driver.get('<https://www.example.com>')
    
    assert 'Example Domain' in driver.title
    
    driver.quit()
    
    ```
    

### 3. **Website Testing**

**Notes:**

- **Website Testing** covers a range of tests to ensure the website functions correctly and meets quality standards.

**Key Types of Testing:**

- **Functional Testing:** Verifies that features work as intended (e.g., forms, buttons).
- **Performance Testing:** Assesses site speed and responsiveness.
- **Security Testing:** Identifies vulnerabilities and ensures data protection.

**Examples:**

- **Functional Testing:**
    
    ```jsx
    // Using JEST with a React Testing Library example
    import { render, screen, fireEvent } from '@testing-library/react';
    import UserForm from './UserForm';
    
    test('submits form data', () => {
      render(<UserForm />);
      fireEvent.change(screen.getByLabelText(/name/i), { target: { value: 'John Doe' } });
      fireEvent.click(screen.getByText(/submit/i));
      expect(screen.getByText(/form submitted/i)).toBeInTheDocument();
    });
    
    ```
    
- **Performance Testing with Lighthouse:**
    - **Lighthouse** is a tool integrated into Chrome DevTools for auditing performance, accessibility, SEO, and more.
    
    ```bash
    # Run Lighthouse from the command line
    npx lighthouse <https://www.example.com> --output html --output-path ./report.html
    
    ```
    
- **Security Testing:**
    - Use tools like **OWASP ZAP** or **Burp Suite** to scan for vulnerabilities.

### Summary

- **JEST Testing:** JavaScript testing framework with snapshot testing, mocking, and async testing.
- **Cross-Browser Testing:** Ensures compatibility across different browsers and devices using tools like BrowserStack, Sauce Labs, and Selenium.
- **Website Testing:** Includes functional, performance, and security testing to ensure a website's quality and performance.

## Advanced React with Next.js

### 1. **Intro to Next.js**

**Notes:**

- **Next.js** is a React framework that enables server-side rendering (SSR), static site generation (SSG), and more, to enhance performance and SEO.
- It provides built-in routing, API routes, and optimized performance out-of-the-box.

**Key Features:**

- **File-based Routing:** Automatic routing based on the file structure in the `pages` directory.
- **Server-Side Rendering (SSR):** Render pages on the server for improved SEO and faster initial load.
- **Static Site Generation (SSG):** Generate static HTML pages at build time for better performance.

**Example:**

- **Creating a Page:**
    
    ```jsx
    // pages/index.js
    import React from 'react';
    
    function HomePage() {
      return <h1>Welcome to Next.js!</h1>;
    }
    
    export default HomePage;
    
    ```
    

### 2. **Next.js vs React**

**Notes:**

- **React** is a library for building user interfaces, while **Next.js** is a framework built on top of React.
- **Next.js** adds features like server-side rendering, static site generation, and file-based routing that are not included with React by default.

**Key Differences:**

- **Routing:** Next.js uses a file-based routing system, while React typically requires a separate routing library like React Router.
- **Rendering:** Next.js supports server-side rendering and static site generation, whereas React only supports client-side rendering.

**Example Comparison:**

- **React (Client-Side Rendering):**
    
    ```jsx
    // App.js
    import React from 'react';
    
    function App() {
      return <div>Hello World</div>;
    }
    
    export default App;
    
    ```
    
- **Next.js (Server-Side Rendering):**
    
    ```jsx
    // pages/index.js
    import React from 'react';
    
    export async function getServerSideProps() {
      return { props: { message: 'Hello World' } };
    }
    
    function HomePage({ message }) {
      return <div>{message}</div>;
    }
    
    export default HomePage;
    
    ```
    

### 3. **Server-Side Rendering (SSR)**

**Notes:**

- **Server-Side Rendering** generates HTML on the server for each request, sending a fully rendered page to the client.
- Improves SEO and initial load time by sending fully rendered content.

**Example:**

- **Using `getServerSideProps`:**
    
    ```jsx
    // pages/index.js
    export async function getServerSideProps() {
      const res = await fetch('<https://api.example.com/data>');
      const data = await res.json();
    
      return {
        props: { data },
      };
    }
    
    function HomePage({ data }) {
      return <div>{data.title}</div>;
    }
    
    export default HomePage;
    
    ```
    

### 4. **Data Fetching**

**Notes:**

- **Data Fetching** in Next.js can be done using server-side rendering (`getServerSideProps`), static site generation (`getStaticProps`), or client-side fetching.

**Methods:**

- **`getStaticProps`**: Fetch data at build time for static generation.
- **`getServerSideProps`**: Fetch data on each request for server-side rendering.
- **Client-Side Fetching**: Use `useEffect` for fetching data after initial render.

**Examples:**

- **Static Site Generation with `getStaticProps`:**
    
    ```jsx
    // pages/index.js
    export async function getStaticProps() {
      const res = await fetch('<https://api.example.com/data>');
      const data = await res.json();
    
      return {
        props: { data },
      };
    }
    
    function HomePage({ data }) {
      return <div>{data.title}</div>;
    }
    
    export default HomePage;
    
    ```
    
- **Client-Side Fetching:**
    
    ```jsx
    import React, { useEffect, useState } from 'react';
    
    function HomePage() {
      const [data, setData] = useState(null);
    
      useEffect(() => {
        async function fetchData() {
          const res = await fetch('<https://api.example.com/data>');
          const result = await res.json();
          setData(result);
        }
        fetchData();
      }, []);
    
      return <div>{data ? data.title : 'Loading...'}</div>;
    }
    
    export default HomePage;
    
    ```
    

### 5. **Hot Reloading**

**Notes:**

- **Hot Reloading** allows developers to see changes in real-time without losing the application state.
- It is enabled by default in Next.js for both server-side and client-side code.

**Example:**

- Simply make changes to your component or page files, and Next.js will automatically refresh the browser with the updated content.

### 6. **Image Optimization**

**Notes:**

- **Image Optimization** in Next.js is handled using the `next/image` component, which provides automatic image optimization, responsive loading, and support for various image formats.

**Key Features:**

- **Automatic Optimization:** Images are automatically optimized and served in modern formats like WebP.
- **Responsive Images:** The `next/image` component adjusts the image size based on the device’s viewport.

**Example:**

- **Using `next/image`:**
    
    ```jsx
    import Image from 'next/image';
    import React from 'react';
    
    function Profile() {
      return (
        <div>
          <h1>My Profile</h1>
          <Image
            src="/profile.jpg"
            alt="Profile Picture"
            width={500}
            height={500}
            layout="responsive"
          />
        </div>
      );
    }
    
    export default Profile;
    
    ```
    

### Summary

- **Intro to Next.js:** React framework with features like server-side rendering and static site generation.
- **Next.js vs React:** Next.js offers built-in routing, SSR, and SSG, while React focuses on client-side rendering.
- **Server-Side Rendering (SSR):** Renders HTML on the server for improved SEO and performance.
- **Data Fetching:** Use `getStaticProps`, `getServerSideProps`, or client-side fetching for data handling.
- **Hot Reloading:** Automatically updates the browser with code changes without losing state.
- **Image Optimization:** Uses `next/image` for automatic image optimization and responsive loading.

### Integrating Next.js into a React Project

- *1. **Starting Fresh with Next.js:**
- **Install Next.js:**
If you're starting from scratch or want to migrate a React project to Next.js, you should set up a new Next.js project.
    
    ```bash
    npx create-next-app@latest my-next-app
    cd my-next-app
    
    ```
    
- **Project Structure:**
The `create-next-app` command sets up a Next.js project with a basic structure:
    - **`pages/`**: Contains your pages (routes) as React components.
    - **`public/`**: Static assets like images.
    - **`styles/`**: CSS files.
    - **`next.config.js`**: Configuration for Next.js.
- **Basic Next.js File Structure Example:**
    
    ```
    my-next-app/
    ├── public/
    │   └── favicon.ico
    ├── src/
    │   └── pages/
    │       ├── index.js
    │       └── about.js
    ├── styles/
    │   └── globals.css
    ├── .gitignore
    ├── package.json
    └── next.config.js
    
    ```
    
- *2. **Migrating a React Project to Next.js:**
- **Move React Components:**
Copy your React components into the `pages` or `components` directory in your Next.js project.
- **Convert Routing:**
Next.js uses file-based routing. Move your existing React routes into the `pages` directory:
    - Create `pages/index.js` for the home page.
    - Create other pages, like `pages/about.js`, for additional routes.
- **Adjust Imports and Code:**
    - Import CSS files or other static assets from the `public` directory.
    - Adjust any client-side routing (e.g., React Router) to Next.js routing (file-based).
- **Example Conversion:**
    
    **React Component (Old):**
    
    ```jsx
    // src/App.js
    import React from 'react';
    import { BrowserRouter as Router, Route, Switch } from 'react-router-dom';
    
    function App() {
      return (
        <Router>
          <Switch>
            <Route path="/" exact component={Home} />
            <Route path="/about" component={About} />
          </Switch>
        </Router>
      );
    }
    
    function Home() {
      return <div>Home Page</div>;
    }
    
    function About() {
      return <div>About Page</div>;
    }
    
    export default App;
    
    ```
    
    **Next.js Component (New):**
    
    ```jsx
    // pages/index.js
    import React from 'react';
    
    function Home() {
      return <div>Home Page</div>;
    }
    
    export default Home;
    
    // pages/about.js
    import React from 'react';
    
    function About() {
      return <div>About Page</div>;
    }
    
    export default About;
    
    ```
    
- *3. **Running and Building the Next.js Project:**
- **Start Development Server:**
    
    ```bash
    npm run dev
    
    ```
    
- **Build for Production:**
    
    ```bash
    npm run build
    npm start
    
    ```
    

### Additional Integration Tips:

- **API Routes:**
Use the `pages/api` directory for backend logic or API routes.
    
    **Example:**
    
    ```jsx
    // pages/api/hello.js
    export default function handler(req, res) {
      res.status(200).json({ message: 'Hello World' });
    }
    
    ```
    
- **Static and Dynamic Routes:**
For dynamic routing, create files with brackets to handle parameters.
    
    **Example:**
    
    ```jsx
    // pages/post/[id].js
    import { useRouter } from 'next/router';
    
    function Post() {
      const router = useRouter();
      const { id } = router.query;
    
      return <div>Post ID: {id}</div>;
    }
    
    export default Post;
    
    ```
    
- **Custom Configuration:**
Modify `next.config.js` for custom configurations or plugins.
    
    **Example:**
    
    ```
    // next.config.js
    module.exports = {
      reactStrictMode: true,
      images: {
        domains: ['example.com'],
      },
    };
    
    ```
    

### Summary

1. **Starting Fresh:**
    - Use `create-next-app` to set up a new Next.js project.
2. **Migrating React Project:**
    - Move React components to the `pages` directory.
    - Convert React Router to Next.js file-based routing.
3. **Run and Build:**
    - Use `npm run dev` for development and `npm run build` for production.
4. **Additional Features:**
    - Implement API routes, dynamic routing, and custom configurations as needed.

## CI/CD Tools

### 1. **Basics of DevOps**

**Notes:**

- **DevOps** is a set of practices that combines software development (Dev) and IT operations (Ops) to improve collaboration, streamline workflows, and accelerate software delivery.
- **CI/CD** (Continuous Integration/Continuous Deployment) is a crucial part of DevOps, focusing on automating the software development lifecycle.

**Key Concepts:**

- **Continuous Integration (CI):**
    - Automates the process of integrating code changes from multiple contributors into a shared repository.
    - Involves automated testing to detect issues early.
- **Continuous Deployment (CD):**
    - Automates the process of deploying code changes to production.
    - Ensures that code changes are deployed frequently and reliably.
- **Infrastructure as Code (IaC):**
    - Managing infrastructure through code, enabling automated provisioning and configuration.
    - Tools: Terraform, Ansible.
- **Monitoring and Logging:**
    - Essential for tracking the performance and health of applications.
    - Tools: Prometheus, Grafana, ELK Stack.

**Example: CI Pipeline:**

- **Setup a CI Pipeline with GitHub Actions:**
    
    ```yaml
    # .github/workflows/ci.yml
    name: CI
    
    on:
      push:
        branches:
          - main
    
    jobs:
      build:
        runs-on: ubuntu-latest
    
        steps:
          - name: Checkout code
            uses: actions/checkout@v2
    
          - name: Set up Node.js
            uses: actions/setup-node@v2
            with:
              node-version: '14'
    
          - name: Install dependencies
            run: npm install
    
          - name: Run tests
            run: npm test
    
    ```
    

**Example: CD Pipeline:**

- **Setup a CD Pipeline with GitHub Actions:**
    
    ```yaml
    # .github/workflows/cd.yml
    name: CD
    
    on:
      push:
        branches:
          - main
    
    jobs:
      deploy:
        runs-on: ubuntu-latest
    
        steps:
          - name: Checkout code
            uses: actions/checkout@v2
    
          - name: Deploy to Server
            run: |
              ssh user@server 'cd /path/to/app && git pull && npm install && pm2 restart all'
    
    ```
    

### 2. **Server Management**

**Notes:**

- **Server Management** involves setting up, maintaining, and monitoring servers to ensure they operate efficiently and securely.

**Key Areas:**

- **Server Provisioning:**
    - Setting up and configuring servers (physical or virtual) for hosting applications.
    - Tools: AWS EC2, DigitalOcean, Azure Virtual Machines.
- **Configuration Management:**
    - Automating server setup and configuration using tools.
    - Tools: Ansible, Chef, Puppet.
- **Monitoring:**
    - Tracking server performance, uptime, and health.
    - Tools: Nagios, Prometheus, Grafana.
- **Security:**
    - Implementing measures to protect servers from unauthorized access and vulnerabilities.
    - Techniques: Firewalls, VPNs, Security patches.
- **Backup and Recovery:**
    - Regularly backing up server data and creating recovery plans.
    - Tools: rsync, Backup software, Cloud storage solutions.

**Example: Provisioning with Terraform:**

- **Terraform Configuration:**
    
    ```
    # main.tf
    provider "aws" {
      region = "us-east-1"
    }
    
    resource "aws_instance" "example" {
      ami           = "ami-0c55b159cbfafe1f0"
      instance_type = "t2.micro"
    
      tags = {
        Name = "example-instance"
      }
    }
    
    ```
    

**Example: Configuration Management with Ansible:**

- **Ansible Playbook:**
    
    ```yaml
    # playbook.yml
    - name: Configure web server
      hosts: webservers
      become: yes
    
      tasks:
        - name: Install Nginx
          apt:
            name: nginx
            state: present
    
        - name: Start Nginx service
          service:
            name: nginx
            state: started
            enabled: yes
    
    ```
    

### Summary

- **Basics of DevOps:**
    - **Continuous Integration/Continuous Deployment (CI/CD):** Automate code integration and deployment processes.
    - **Infrastructure as Code (IaC):** Manage infrastructure through code.
    - **Monitoring and Logging:** Track application performance and health.
- **Server Management:**
    - **Provisioning:** Set up and configure servers.
    - **Configuration Management:** Automate server configuration.
    - **Monitoring:** Track server performance.
    - **Security:** Protect servers from threats.
    - **Backup and Recovery:** Ensure data is backed up and recoverable.

## Security Handling

### 1. **Security**

**Notes:**

- **Web Security** is critical for protecting applications from vulnerabilities and ensuring data integrity.
- It involves various practices and tools to safeguard against potential threats.

**Key Concepts:**

- **Input Validation:** Ensure all user inputs are validated and sanitized.
- **Secure Communication:** Use HTTPS to encrypt data transmitted over the network.
- **Authentication and Authorization:** Implement robust methods to verify user identity and permissions.

**Example: Implementing HTTPS in a React Project**

- **For Development:**
Use `https` flag with development servers like `create-react-app`.
    
    ```bash
    HTTPS=true npm start
    
    ```
    
- **For Production:**
Configure your web server (e.g., Nginx, Apache) to use SSL/TLS certificates.

### 2. **XSS (Cross-Site Scripting) Attack**

**Notes:**

- **XSS** involves injecting malicious scripts into web pages viewed by other users.
- It can steal cookies, session tokens, or manipulate the DOM.

**Protection Strategies:**

- **Sanitize User Input:** Ensure that user input is properly sanitized before rendering it in the DOM.
- **Use Libraries:** Use libraries like DOMPurify to sanitize HTML content.

**Example:**

- **Sanitizing User Input in React:**
    
    ```jsx
    import React, { useState } from 'react';
    import DOMPurify from 'dompurify';
    
    function Comment({ comment }) {
      const sanitizedComment = DOMPurify.sanitize(comment);
    
      return <div dangerouslySetInnerHTML={{ __html: sanitizedComment }} />;
    }
    
    export default Comment;
    
    ```
    
- **Where to Place This Code:**
    - Place the sanitization code in components where user-generated content is displayed.

### 3. **CSRF (Cross-Site Request Forgery) Attack**

**Notes:**

- **CSRF** involves tricking users into performing actions on a web application without their consent.
- It exploits the trust that a site has in the user's browser.

**Protection Strategies:**

- **Use CSRF Tokens:** Include a unique token in forms and verify it on the server side.
- **SameSite Cookies:** Use `SameSite` attribute for cookies to restrict cross-origin requests.

**Example:**

- **Adding CSRF Token in a React Form:**
    
    ```jsx
    import React, { useState, useEffect } from 'react';
    
    function ContactForm() {
      const [csrfToken, setCsrfToken] = useState('');
    
      useEffect(() => {
        // Fetch CSRF token from the server
        fetch('/api/csrf-token')
          .then(response => response.json())
          .then(data => setCsrfToken(data.csrfToken));
      }, []);
    
      const handleSubmit = (e) => {
        e.preventDefault();
    
        fetch('/api/contact', {
          method: 'POST',
          headers: {
            'Content-Type': 'application/json',
            'X-CSRF-Token': csrfToken,
          },
          body: JSON.stringify({ message: 'Hello!' }),
        });
      };
    
      return (
        <form onSubmit={handleSubmit}>
          <input type="text" name="message" />
          <button type="submit">Send</button>
        </form>
      );
    }
    
    export default ContactForm;
    
    ```
    
- **Server-Side Example (Express.js):**
    
    ```
    const express = require('express');
    const csrf = require('csurf');
    const bodyParser = require('body-parser');
    const app = express();
    
    app.use(bodyParser.json());
    app.use(csrf());
    
    app.get('/api/csrf-token', (req, res) => {
      res.json({ csrfToken: req.csrfToken() });
    });
    
    app.post('/api/contact', (req, res) => {
      // Handle form submission
      res.send('Form submitted');
    });
    
    app.listen(3000);
    
    ```
    
- **Where to Place This Code:**
    - React components handling forms that interact with APIs.
    - Server-side code for generating and verifying CSRF tokens.

### 4. **DOS (Denial of Service) Attack**

**Notes:**

- **DOS** attacks aim to make a service unavailable by overwhelming it with traffic or resource requests.

**Protection Strategies:**

- **Rate Limiting:** Limit the number of requests a user can make in a certain period.
- **Throttling:** Slow down requests from a single source if they exceed a threshold.

**Example:**

- **Rate Limiting with Express.js:**
    
    ```
    const express = require('express');
    const rateLimit = require('express-rate-limit');
    const app = express();
    
    const limiter = rateLimit({
      windowMs: 15 * 60 * 1000, // 15 minutes
      max: 100, // Limit each IP to 100 requests per windowMs
    });
    
    app.use(limiter);
    
    app.get('/', (req, res) => {
      res.send('Hello, World!');
    });
    
    app.listen(3000);
    
    ```
    
- **Where to Place This Code:**
    - Server-side code for API endpoints or application routes.

### Summary

- **Security:**
    - Use HTTPS for secure communication.
    - Sanitize user input and use libraries like DOMPurify to prevent XSS.
- **XSS Attack:**
    - Sanitize and escape user inputs to avoid injecting malicious scripts.
- **CSRF Attack:**
    - Use CSRF tokens in forms and SameSite cookies to protect against unauthorized actions.
- **DOS Attack:**
    - Implement rate limiting and throttling on the server to handle excessive requests.

## Basic DSA - 50

### 1. **Second Largest Element**

**Problem:**
Find the second largest element in an array.

**Solution:**

```jsx
function findSecondLargest(arr) {
  let first = -Infinity, second = -Infinity;
  for (let num of arr) {
    if (num > first) {
      second = first;
      first = num;
    } else if (num > second && num < first) {
      second = num;
    }
  }
  return second === -Infinity ? "No second largest element" : second;
}

// Example usage
console.log(findSecondLargest([10, 5, 20, 20, 4])); // Output: 10

```

### 2. **Rotate An Array By K**

**Problem:**
Rotate an array to the right by `k` steps.

**Solution:**

```jsx
function rotateArray(arr, k) {
  k = k % arr.length; // Handle cases where k is greater than array length
  return arr.slice(-k).concat(arr.slice(0, -k));
}

// Example usage
console.log(rotateArray([1, 2, 3, 4, 5], 2)); // Output: [4, 5, 1, 2, 3]

```

### 3. **Non Decreasing Array**

**Problem:**
Check if a given array can be made non-decreasing by modifying at most one element.

**Solution:**

```jsx
function checkPossibility(nums) {
  let count = 0;
  for (let i = 1; i < nums.length; i++) {
    if (nums[i] < nums[i - 1]) {
      count++;
      if (count > 1) return false;
      if (i - 2 < 0 || nums[i - 2] <= nums[i]) {
        nums[i - 1] = nums[i];
      } else {
        nums[i] = nums[i - 1];
      }
    }
  }
  return true;
}

// Example usage
console.log(checkPossibility([4, 2, 3])); // Output: true

```

### 4. **Equilibrium Index**

**Problem:**
Find the index in an array where the sum of elements on the left is equal to the sum of elements on the right.

**Solution:**

```jsx
function findEquilibriumIndex(arr) {
  let totalSum = arr.reduce((a, b) => a + b, 0);
  let leftSum = 0;

  for (let i = 0; i < arr.length; i++) {
    totalSum -= arr[i];
    if (leftSum === totalSum) {
      return i;
    }
    leftSum += arr[i];
  }
  return -1;
}

// Example usage
console.log(findEquilibriumIndex([1, 2, 3, 4, 6])); // Output: 3

```

### 5. **First Missing Positive**

**Problem:**
Find the smallest positive integer missing from an unsorted array.

**Solution:**

```jsx
function firstMissingPositive(nums) {
  let n = nums.length;
  for (let i = 0; i < n; i++) {
    while (nums[i] > 0 && nums[i] <= n && nums[i] !== nums[nums[i] - 1]) {
      [nums[i], nums[nums[i] - 1]] = [nums[nums[i] - 1], nums[i]];
    }
  }
  for (let i = 0; i < n; i++) {
    if (nums[i] !== i + 1) return i + 1;
  }
  return n + 1;
}

// Example usage
console.log(firstMissingPositive([3, 4, -1, 1])); // Output: 2

```

### 6. **Reverse String Word Wise**

**Problem:**
Reverse the words in a given string.

**Solution:**

```jsx
function reverseWords(str) {
  return str.split(' ').reverse().join(' ');
}

// Example usage
console.log(reverseWords("The quick brown fox")); // Output: "fox brown quick The"

```

### 7. **String Encoding**

**Problem:**
Encode a string by counting consecutive characters.

**Solution:**

```jsx
function encodeString(str) {
  let result = '';
  let count = 1;

  for (let i = 1; i < str.length; i++) {
    if (str[i] === str[i - 1]) {
      count++;
    } else {
      result += str[i - 1] + count;
      count = 1;
    }
  }
  result += str[str.length - 1] + count;
  return result;
}

// Example usage
console.log(encodeString("aaabbcc")); // Output: "a3b2c2"

```

### 8. **Minimum Parentheses**

**Problem:**
Find the minimum number of parentheses required to balance a string of parentheses.

**Solution:**

```jsx
function minAddToMakeValid(s) {
  let left = 0, right = 0;

  for (let char of s) {
    if (char === '(') {
      left++;
    } else if (char === ')') {
      if (left === 0) {
        right++;
      } else {
        left--;
      }
    }
  }
  return left + right;
}

// Example usage
console.log(minAddToMakeValid("(()")); // Output: 1

```

### 9. **Beautiful Strings**

**Problem:**
Check if a string is "beautiful" where no two consecutive characters are the same.

**Solution:**

```jsx
function isBeautifulString(s) {
  for (let i = 1; i < s.length; i++) {
    if (s[i] === s[i - 1]) return false;
  }
  return true;
}

// Example usage
console.log(isBeautifulString("abcde")); // Output: true
console.log(isBeautifulString("aabbcc")); // Output: false

```

### 10. **Next Smallest Palindrome**

**Problem:**
Find the next smallest palindrome greater than a given number.

**Solution:**

```jsx
function nextPalindrome(num) {
  let str = num.toString();
  let len = str.length;

  let left = str.slice(0, Math.ceil(len / 2));
  let right = str.slice(Math.floor(len / 2)).split('').reverse().join('');

  let palindrome = left + right;
  if (palindrome > str) return palindrome;

  left = (parseInt(left) + 1).toString();
  right = left.slice(0, Math.floor(len / 2)).split('').reverse().join('');

  return left + right;
}

// Example usage
console.log(nextPalindrome(123)); // Output: "131"
```

### 11. **Sum of Zeroes**

**Problem:**
Find if there are any subarrays with a sum of zero.

**Solution:**

```jsx
function hasZeroSumSubarray(arr) {
  let sumSet = new Set();
  let sum = 0;

  for (let num of arr) {
    sum += num;
    if (sum === 0 || sumSet.has(sum)) {
      return true;
    }
    sumSet.add(sum);
  }
  return false;
}

// Example usage
console.log(hasZeroSumSubarray([1, 2, -3, 4])); // Output: true

```

### 12. **Matrix Symmetric**

**Problem:**
Check if a matrix is symmetric (i.e., it is equal to its transpose).

**Solution:**

```jsx
function isSymmetric(matrix) {
  let n = matrix.length;

  for (let i = 0; i < n; i++) {
    for (let j = 0; j < n; j++) {
      if (matrix[i][j] !== matrix[j][i]) {
        return false;
      }
    }
  }
  return true;
}

// Example usage
console.log(isSymmetric([[1, 2, 3], [2, 4, 5], [3, 5, 6]])); // Output: true

```

### 13. **Inplace Rotate Matrix 90 Degrees**

**Problem:**
Rotate a square matrix by 90 degrees in place.

**Solution:**

```jsx
function rotateMatrix(matrix) {
  let n = matrix.length;

  for (let i = 0; i < Math.floor(n / 2); i++) {
    for (let j = i; j < n - i - 1; j++) {
      let temp = matrix[i][j];
      matrix[i][j] = matrix[n - j - 1][i];
      matrix[n - j - 1][i] = matrix[n - i - 1][n - j - 1];
      matrix[n - i - 1][n - j - 1] = matrix[j][n - i - 1];
      matrix[j][n - i - 1] = temp;
    }
  }
  return matrix;
}

// Example usage
console.log(rotateMatrix([[1, 2, 3], [4, 5, 6], [7, 8, 9]]));
// Output: [[7, 4, 1], [8, 5, 2], [9, 6, 3]]

```

### 14. **Set Matrix Zeroes**

**Problem:**
Set entire row and column to zero if an element in the matrix is zero.

**Solution:**

```jsx
function setMatrixZeroes(matrix) {
  let rows = matrix.length;
  let cols = matrix[0].length;
  let zeroRows = new Set();
  let zeroCols = new Set();

  for (let i = 0; i < rows; i++) {
    for (let j = 0; j < cols; j++) {
      if (matrix[i][j] === 0) {
        zeroRows.add(i);
        zeroCols.add(j);
      }
    }
  }

  for (let row of zeroRows) {
    for (let j = 0; j < cols; j++) {
      matrix[row][j] = 0;
    }
  }

  for (let col of zeroCols) {
    for (let i = 0; i < rows; i++) {
      matrix[i][col] = 0;
    }
  }

  return matrix;
}

// Example usage
console.log(setMatrixZeroes([[1, 2, 3], [4, 0, 6], [7, 8, 9]]));
// Output: [[1, 0, 3], [0, 0, 0], [7, 0, 9]]

```

### 15. **Spiral Order**

**Problem:**
Print a matrix in spiral order.

**Solution:**

```jsx
function spiralOrder(matrix) {
  let result = [];
  let top = 0, bottom = matrix.length - 1;
  let left = 0, right = matrix[0].length - 1;

  while (top <= bottom && left <= right) {
    for (let i = left; i <= right; i++) result.push(matrix[top][i]);
    top++;
    for (let i = top; i <= bottom; i++) result.push(matrix[i][right]);
    right--;
    if (top <= bottom) {
      for (let i = right; i >= left; i--) result.push(matrix[bottom][i]);
      bottom--;
    }
    if (left <= right) {
      for (let i = bottom; i >= top; i--) result.push(matrix[i][left]);
      left++;
    }
  }

  return result;
}

// Example usage
console.log(spiralOrder([[1, 2, 3], [4, 5, 6], [7, 8, 9]]));
// Output: [1, 2, 3, 6, 9, 8, 7, 4, 5]

```

### 16. **Make Unique Array**

**Problem:**
Remove duplicates from an array to make it unique.

**Solution:**

```jsx
function makeUniqueArray(arr) {
  return [...new Set(arr)];
}

// Example usage
console.log(makeUniqueArray([1, 2, 2, 3, 4, 4, 5])); // Output: [1, 2, 3, 4, 5]

```

### 17. **First Non-Repeating Character in String**

**Problem:**
Find the first non-repeating character in a string.

**Solution:**

```jsx
function firstNonRepeatingChar(str) {
  let charCount = new Map();

  for (let char of str) {
    charCount.set(char, (charCount.get(char) || 0) + 1);
  }

  for (let char of str) {
    if (charCount.get(char) === 1) {
      return char;
    }
  }
  return null;
}

// Example usage
console.log(firstNonRepeatingChar("swiss")); // Output: "w"

```

### 18. **Longest Subarray Zero Sum**

**Problem:**
Find the length of the longest subarray with a sum of zero.

**Solution:**

```jsx
function longestZeroSumSubarray(arr) {
  let maxLength = 0;
  let sumMap = new Map();
  let sum = 0;

  for (let i = 0; i < arr.length; i++) {
    sum += arr[i];

    if (sum === 0) {
      maxLength = i + 1;
    } else if (sumMap.has(sum)) {
      maxLength = Math.max(maxLength, i - sumMap.get(sum));
    } else {
      sumMap.set(sum, i);
    }
  }
  return maxLength;
}

// Example usage
console.log(longestZeroSumSubarray([1, 2, -3, 3, 4])); // Output: 3

```

### 19. **Count All Sub-arrays Having Sum Divisible by K**

**Problem:**
Count the number of subarrays whose sum is divisible by `k`.

**Solution:**

```jsx
function countSubarraysDivisibleByK(arr, k) {
  let count = 0;
  let sum = 0;
  let sumMap = new Map();
  sumMap.set(0, 1);

  for (let num of arr) {
    sum += num;
    let mod = ((sum % k) + k) % k; // Handle negative mod
    count += sumMap.get(mod) || 0;
    sumMap.set(mod, (sumMap.get(mod) || 0) + 1);
  }

  return count;
}

// Example usage
console.log(countSubarraysDivisibleByK([4, 5, 0, -2, -3, 1], 5)); // Output: 7

```

### 20. **Group Anagrams**

**Problem:**
Group anagrams together from a list of strings.

**Solution:**

```jsx
function groupAnagrams(strs) {
  let map = new Map();

  for (let str of strs) {
    let sortedStr = str.split('').sort().join('');
    if (!map.has(sortedStr)) {
      map.set(sortedStr, []);
    }
    map.get(sortedStr).push(str);
  }

  return Array.from(map.values());
}

// Example usage
console.log(groupAnagrams(["eat", "tea", "tan", "ate", "nat", "bat"]));
// Output: [["eat", "tea", "ate"], ["tan", "nat"], ["bat"]]
```

### 21. **Pair Sum**

**Problem:**
Find if there is a pair of numbers in an array that sums up to a given target.

**Solution:**

```jsx
function hasPairWithSum(arr, target) {
  let numSet = new Set();

  for (let num of arr) {
    if (numSet.has(target - num)) {
      return true;
    }
    numSet.add(num);
  }
  return false;
}

// Example usage
console.log(hasPairWithSum([1, 2, 3, 4, 5], 9)); // Output: true

```

### 22. **Move Negative Numbers to Start**

**Problem:**
Move all negative numbers to the start of an array, preserving the order of positive numbers.

**Solution:**

```jsx
function moveNegativesToStart(arr) {
  let negative = arr.filter(num => num < 0);
  let positive = arr.filter(num => num >= 0);
  return negative.concat(positive);
}

// Example usage
console.log(moveNegativesToStart([1, -2, 3, -4, 5])); // Output: [-2, -4, 1, 3, 5]

```

### 23. **Container With Most Water**

**Problem:**
Find the maximum amount of water a container can hold between two lines in an array.

**Solution:**

```jsx
function maxArea(height) {
  let left = 0, right = height.length - 1;
  let maxArea = 0;

  while (left < right) {
    let width = right - left;
    let currentHeight = Math.min(height[left], height[right]);
    maxArea = Math.max(maxArea, width * currentHeight);

    if (height[left] < height[right]) {
      left++;
    } else {
      right--;
    }
  }
  return maxArea;
}

// Example usage
console.log(maxArea([1, 8, 6, 2, 5, 4, 8, 3, 7])); // Output: 49

```

### 24. **Check Subsequence**

**Problem:**
Check if one string is a subsequence of another.

**Solution:**

```jsx
function isSubsequence(s, t) {
  let sIndex = 0, tIndex = 0;

  while (sIndex < s.length && tIndex < t.length) {
    if (s[sIndex] === t[tIndex]) {
      sIndex++;
    }
    tIndex++;
  }

  return sIndex === s.length;
}

// Example usage
console.log(isSubsequence("abc", "aebdc")); // Output: true

```

### 25. **Insertion Sort**

**Problem:**
Sort an array using insertion sort algorithm.

**Solution:**

```jsx
function insertionSort(arr) {
  for (let i = 1; i < arr.length; i++) {
    let key = arr[i];
    let j = i - 1;

    while (j >= 0 && arr[j] > key) {
      arr[j + 1] = arr[j];
      j--;
    }
    arr[j + 1] = key;
  }
  return arr;
}

// Example usage
console.log(insertionSort([12, 11, 13, 5, 6])); // Output: [5, 6, 11, 12, 13]

```

### 26. **Selection Sort**

**Problem:**
Sort an array using selection sort algorithm.

**Solution:**

```jsx
function selectionSort(arr) {
  for (let i = 0; i < arr.length - 1; i++) {
    let minIndex = i;
    for (let j = i + 1; j < arr.length; j++) {
      if (arr[j] < arr[minIndex]) {
        minIndex = j;
      }
    }
    if (minIndex !== i) {
      [arr[i], arr[minIndex]] = [arr[minIndex], arr[i]];
    }
  }
  return arr;
}

// Example usage
console.log(selectionSort([64, 25, 12, 22, 11])); // Output: [11, 12, 22, 25, 64]

```

### 27. **Bubble Sort**

**Problem:**
Sort an array using bubble sort algorithm.

**Solution:**

```jsx
function bubbleSort(arr) {
  let n = arr.length;
  for (let i = 0; i < n - 1; i++) {
    for (let j = 0; j < n - i - 1; j++) {
      if (arr[j] > arr[j + 1]) {
        [arr[j], arr[j + 1]] = [arr[j + 1], arr[j]];
      }
    }
  }
  return arr;
}

// Example usage
console.log(bubbleSort([64, 34, 25, 12, 22, 11, 90])); // Output: [11, 12, 22, 25, 34, 64, 90]

```

### 28. **Kadane’s Algorithm**

**Problem:**
Find the maximum sum of a contiguous subarray using Kadane’s Algorithm.

**Solution:**

```jsx
function kadaneAlgorithm(arr) {
  let maxSoFar = arr[0];
  let maxEndingHere = arr[0];

  for (let i = 1; i < arr.length; i++) {
    maxEndingHere = Math.max(arr[i], maxEndingHere + arr[i]);
    maxSoFar = Math.max(maxSoFar, maxEndingHere);
  }
  return maxSoFar;
}

// Example usage
console.log(kadaneAlgorithm([-2, 1, -3, 4, -1, 2, 1, -5, 4])); // Output: 6

```

### 29. **Dutch National Flag Algorithm**

**Problem:**
Sort an array with three distinct values (like 0, 1, 2) using Dutch National Flag Algorithm.

**Solution:**

```jsx
function dutchNationalFlag(arr) {
  let low = 0, mid = 0, high = arr.length - 1;

  while (mid <= high) {
    if (arr[mid] === 0) {
      [arr[low], arr[mid]] = [arr[mid], arr[low]];
      low++;
      mid++;
    } else if (arr[mid] === 1) {
      mid++;
    } else {
      [arr[mid], arr[high]] = [arr[high], arr[mid]];
      high--;
    }
  }
  return arr;
}

// Example usage
console.log(dutchNationalFlag([2, 0, 2, 1, 1, 0])); // Output: [0, 0, 1, 1, 2, 2]

```

### 30. **Moore’s Voting Algorithm**

**Problem:**
Find the majority element in an array using Moore’s Voting Algorithm.

**Solution:**

```jsx
function majorityElement(arr) {
  let candidate = arr[0];
  let count = 1;

  for (let i = 1; i < arr.length; i++) {
    if (arr[i] === candidate) {
      count++;
    } else {
      count--;
      if (count === 0) {
        candidate = arr[i];
        count = 1;
      }
    }
  }

  // Verify the candidate
  count = 0;
  for (let num of arr) {
    if (num === candidate) {
      count++;
    }
  }

  return count > arr.length / 2 ? candidate : null;
}

// Example usage
console.log(majorityElement([3, 3, 4, 2, 4, 4, 2, 4, 4])); // Output: 4		
```

### 31. **Check Permutation**

**Problem:**
Check if one string is a permutation of another.

**Solution:**

```jsx
function isPermutation(s1, s2) {
  if (s1.length !== s2.length) return false;

  let sortedS1 = s1.split('').sort().join('');
  let sortedS2 = s2.split('').sort().join('');

  return sortedS1 === sortedS2;
}

// Example usage
console.log(isPermutation("listen", "silent")); // Output: true

```

### 32. **Intersection Of Two Arrays**

**Problem:**
Find the intersection of two arrays.

**Solution:**

```jsx
function intersection(arr1, arr2) {
  let set1 = new Set(arr1);
  let set2 = new Set(arr2);
  return [...set1].filter(item => set2.has(item));
}

// Example usage
console.log(intersection([1, 2, 2, 1], [2, 2])); // Output: [2]

```

### 33. **N/3 Repeated Number in Array**

**Problem:**
Find the element that appears more than `n/3` times in the array.

**Solution:**

```jsx
function findNBy3Repeated(arr) {
  let count1 = 0, count2 = 0;
  let candidate1 = null, candidate2 = null;

  for (let num of arr) {
    if (num === candidate1) {
      count1++;
    } else if (num === candidate2) {
      count2++;
    } else if (count1 === 0) {
      candidate1 = num;
      count1 = 1;
    } else if (count2 === 0) {
      candidate2 = num;
      count2 = 1;
    } else {
      count1--;
      count2--;
    }
  }

  count1 = 0;
  count2 = 0;
  for (let num of arr) {
    if (num === candidate1) count1++;
    else if (num === candidate2) count2++;
  }

  let result = [];
  if (count1 > arr.length / 3) result.push(candidate1);
  if (count2 > arr.length / 3) result.push(candidate2);

  return result;
}

// Example usage
console.log(findNBy3Repeated([3, 2, 3])); // Output: [3]

```

### 34. **Counting Sort**

**Problem:**
Sort an array using counting sort.

**Solution:**

```jsx
function countingSort(arr) {
  let max = Math.max(...arr);
  let min = Math.min(...arr);
  let count = Array(max - min + 1).fill(0);
  let output = [];

  for (let num of arr) {
    count[num - min]++;
  }

  for (let i = 0; i < count.length; i++) {
    for (let j = 0; j < count[i]; j++) {
      output.push(i + min);
    }
  }

  return output;
}

// Example usage
console.log(countingSort([4, 2, 2, 8, 3, 3, 1])); // Output: [1, 2, 2, 3, 3, 4, 8]

```

### 35. **Rotate Matrix To Right**

**Problem:**
Rotate a matrix 90 degrees to the right.

**Solution:**

```jsx
function rotateMatrix(matrix) {
  let n = matrix.length;
  for (let i = 0; i < n; i++) {
    for (let j = i; j < n; j++) {
      [matrix[i][j], matrix[j][i]] = [matrix[j][i], matrix[i][j]];
    }
  }
  for (let i = 0; i < n; i++) {
    matrix[i].reverse();
  }
  return matrix;
}

// Example usage
console.log(rotateMatrix([
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9]
])); // Output: [[7, 4, 1], [8, 5, 2], [9, 6, 3]]

```

### 36. **Find Kth Character of Decrypted String**

**Problem:**
Find the Kth character of a decrypted string from an encoded string.

**Solution:**

```jsx
function findKthCharacter(encoded, k) {
  let decoded = '';
  let i = 0;

  while (i < encoded.length) {
    if (isNaN(encoded[i])) {
      decoded += encoded[i];
      i++;
    } else {
      let num = 0;
      while (!isNaN(encoded[i])) {
        num = num * 10 + parseInt(encoded[i]);
        i++;
      }
      decoded += decoded.slice(-num);
    }
  }

  return decoded[k - 1];
}

// Example usage
console.log(findKthCharacter("a2b3", 4)); // Output: 'b'

```

### 37. **Move Zeroes To End**

**Problem:**
Move all zeroes in an array to the end, preserving the order of non-zero elements.

**Solution:**

```jsx
function moveZeroes(arr) {
  let nonZeroIndex = 0;

  for (let i = 0; i < arr.length; i++) {
    if (arr[i] !== 0) {
      [arr[i], arr[nonZeroIndex]] = [arr[nonZeroIndex], arr[i]];
      nonZeroIndex++;
    }
  }

  return arr;
}

// Example usage
console.log(moveZeroes([0, 1, 0, 3, 12])); // Output: [1, 3, 12, 0, 0]

```

### 38. **Sum of Two Elements Equals Third**

**Problem:**
Find if there are two elements in an array that sum up to a third element.

**Solution:**

```jsx
function hasSumEqualsThird(arr) {
  let numSet = new Set();

  for (let num of arr) {
    numSet.add(num);
  }

  for (let i = 0; i < arr.length; i++) {
    for (let j = i + 1; j < arr.length; j++) {
      if (numSet.has(arr[i] + arr[j])) {
        return true;
      }
    }
  }
  return false;
}

// Example usage
console.log(hasSumEqualsThird([1, 2, 3, 4, 5])); // Output: true (1 + 4 = 5)

```

### 39. **Minimum Operations to Make String Equal**

**Problem:**
Find the minimum number of operations to make two strings equal.

**Solution:**

```jsx
function minOperationsToMakeEqual(s1, s2) {
  if (s1.length !== s2.length) return -1;

  let count = 0;
  let s1Count = new Map();
  let s2Count = new Map();

  for (let i = 0; i < s1.length; i++) {
    s1Count.set(s1[i], (s1Count.get(s1[i]) || 0) + 1);
    s2Count.set(s2[i], (s2Count.get(s2[i]) || 0) + 1);
  }

  for (let [key, value] of s1Count) {
    if (s2Count.get(key) !== value) return -1;
  }

  return s1.length - Array.from(s1Count.values()).reduce((a, b) => a + b);
}

// Example usage
console.log(minOperationsToMakeEqual("abcd", "dcba")); // Output: 0

```

### 40. **Maximum Sum Circular Array**

**Problem:**
Find the maximum sum of a circular subarray.

**Solution:**

```jsx
function maxSumCircularArray(arr) {
  let maxKadane = kadaneAlgorithm(arr);

  let totalSum = 0;
  let minKadane = 0;
  for (let i = 0; i < arr.length; i++) {
    totalSum += arr[i];
    arr[i] = -arr[i];
  }
  minKadane = kadaneAlgorithm(arr);

  let maxCircular = totalSum + minKadane;

  return maxCircular > maxKadane ? maxCircular : maxKadane;
}

// Kadane's algorithm
function kadaneAlgorithm(arr) {
  let maxSoFar = arr[0];
  let maxEndingHere = arr[0];

  for (let i = 1; i < arr.length; i++) {
    maxEndingHere = Math.max(arr[i], maxEndingHere + arr[i]);
    maxSoFar = Math.max(maxSoFar, maxEndingHere);
  }
  return maxSoFar;
}

// Example usage
console.log(maxSumCircularArray([8, -1, 3, 4])); // Output: 15

```

### 41. **Longest Consecutive Sequence**

**Problem:**
Find the length of the longest consecutive elements sequence in an unsorted array.

**Solution:**

```jsx
function longestConsecutive(nums) {
  if (nums.length === 0) return 0;

  let numSet = new Set(nums);
  let longest = 0;

  for (let num of numSet) {
    if (!numSet.has(num - 1)) {
      let currentNum = num;
      let currentStreak = 1;

      while (numSet.has(currentNum + 1)) {
        currentNum += 1;
        currentStreak += 1;
      }

      longest = Math.max(longest, currentStreak);
    }
  }

  return longest;
}

// Example usage
console.log(longestConsecutive([100, 4, 200, 1, 3, 2])); // Output: 4 (1, 2, 3, 4)

```

### 42. **Maximum Subarray Sum After K Concat**

**Problem:**
Given an array `arr`, you need to find the maximum sum of a subarray after concatenating the array `k` times.

**Solution:**

```jsx
function maxSubarraySumAfterKConcat(arr, k) {
  let maxKadane = kadaneAlgorithm(arr);
  let totalSum = arr.reduce((a, b) => a + b, 0);

  if (k === 1) return maxKadane;

  let maxPrefix = 0;
  let maxSuffix = 0;
  let prefixSum = 0;
  let suffixSum = 0;

  for (let i = 0; i < arr.length; i++) {
    prefixSum += arr[i];
    maxPrefix = Math.max(maxPrefix, prefixSum);
  }

  for (let i = arr.length - 1; i >= 0; i--) {
    suffixSum += arr[i];
    maxSuffix = Math.max(maxSuffix, suffixSum);
  }

  let maxCircular = maxPrefix + maxSuffix;
  if (totalSum > 0) {
    maxCircular += (k - 2) * totalSum;
  }

  return Math.max(maxKadane, maxCircular);
}

// Kadane's algorithm
function kadaneAlgorithm(arr) {
  let maxSoFar = arr[0];
  let maxEndingHere = arr[0];

  for (let i = 1; i < arr.length; i++) {
    maxEndingHere = Math.max(arr[i], maxEndingHere + arr[i]);
    maxSoFar = Math.max(maxSoFar, maxEndingHere);
  }
  return maxSoFar;
}

// Example usage
console.log(maxSubarraySumAfterKConcat([1, -2, 1], 5)); // Output: 2

```

### 43. **Maximum Product Count**

**Problem:**
Find the count of maximum product subarrays in an array.

**Solution:**

```jsx
function maxProductCount(arr) {
  if (arr.length === 0) return 0;

  let maxProduct = arr[0];
  let count = 1;
  let currentProduct = arr[0];

  for (let i = 1; i < arr.length; i++) {
    currentProduct = Math.max(arr[i], currentProduct * arr[i]);
    if (currentProduct > maxProduct) {
      maxProduct = currentProduct;
      count = 1;
    } else if (currentProduct === maxProduct) {
      count++;
    }
  }

  return count;
}

// Example usage
console.log(maxProductCount([2, 3, -2, 4])); // Output: 1

```

### 44. **Multiply Strings**

**Problem:**
Multiply two non-negative integers represented as strings.

**Solution:**

```jsx
function multiplyStrings(num1, num2) {
  let m = num1.length;
  let n = num2.length;
  let result = Array(m + n).fill(0);

  for (let i = m - 1; i >= 0; i--) {
    for (let j = n - 1; j >= 0; j--) {
      let mul = (num1[i] - '0') * (num2[j] - '0');
      let sum = mul + result[i + j + 1];
      result[i + j + 1] = sum % 10;
      result[i + j] += Math.floor(sum / 10);
    }
  }

  let resultStr = result.join('');
  return resultStr[0] === '0' ? resultStr.slice(1) : resultStr;
}

// Example usage
console.log(multiplyStrings("123", "456")); // Output: "56088"

```

### 45. **Find All Subsquares of Size K**

**Problem:**
Find all subsquares of size `K x K` in a matrix.

**Solution:**

```jsx
function findAllSubsquares(matrix, k) {
  let result = [];
  let rows = matrix.length;
  let cols = matrix[0].length;

  for (let i = 0; i <= rows - k; i++) {
    for (let j = 0; j <= cols - k; j++) {
      let subSquare = [];
      for (let x = 0; x < k; x++) {
        subSquare.push(matrix[i + x].slice(j, j + k));
      }
      result.push(subSquare);
    }
  }

  return result;
}

// Example usage
console.log(findAllSubsquares([
  [1, 2, 3, 4],
  [5, 6, 7, 8],
  [9, 10, 11, 12],
  [13, 14, 15, 16]
], 2));

```

### 46. **Repeat And Missing Number Array**

**Problem:**
Given an array with numbers from 1 to `n`, find the missing number and the repeated number.

**Solution:**

```jsx
function findRepeatAndMissing(arr) {
  let n = arr.length;
  let totalSum = (n * (n + 1)) / 2;
  let totalSumSquares = (n * (n + 1) * (2 * n + 1)) / 6;

  let actualSum = 0;
  let actualSumSquares = 0;

  for (let num of arr) {
    actualSum += num;
    actualSumSquares += num * num;
  }

  let sumDiff = totalSum - actualSum;
  let sumSquaresDiff = totalSumSquares - actualSumSquares;

  let missingNumber = (sumDiff + sumSquaresDiff / sumDiff) / 2;
  let repeatedNumber = missingNumber - sumDiff;

  return [repeatedNumber, missingNumber];
}

// Example usage
console.log(findRepeatAndMissing([1, 2, 2, 4])); // Output: [2, 3]

```

### 47. **4 Sum Problem**

**Problem:**
Find all unique quadruplets in an array that sum up to a target value.

**Solution:**

```jsx
function fourSum(nums, target) {
  let result = [];
  nums.sort((a, b) => a - b);

  for (let i = 0; i < nums.length - 3; i++) {
    if (i > 0 && nums[i] === nums[i - 1]) continue;

    for (let j = i + 1; j < nums.length - 2; j++) {
      if (j > i + 1 && nums[j] === nums[j - 1]) continue;

      let left = j + 1;
      let right = nums.length - 1;

      while (left < right) {
        let sum = nums[i] + nums[j] + nums[left] + nums[right];
        if (sum === target) {
          result.push([nums[i], nums[j], nums[left], nums[right]]);
          while (left < right && nums[left] === nums[left + 1]) left++;
          while (left < right && nums[right] === nums[right - 1]) right--;
          left++;
          right--;
        } else if (sum < target) {
          left++;
        } else {
          right--;
        }
      }
    }
  }

  return result;
}

// Example usage
console.log(fourSum([1, 0, -1, 0, -2, 2], 0)); // Output: [[-2, -1, 1, 2], [-2, 0, 0, 2], [-1, 0, 0, 1]]

```

### 48. **Count All Subarrays With Given Sum**

**Problem:**
Count all subarrays in an array that sum up to a given value.

**Solution:**

```jsx
function countSubarraysWithSum(arr, sum) {
  let count = 0;
  let currentSum = 0;
  let sumMap = new Map();
  sumMap.set(0, 1);

  for (let num of arr) {
    currentSum += num;
    if (sumMap.has(currentSum - sum)) {
      count += sumMap.get(currentSum - sum);
    }
    sumMap.set(currentSum, (sumMap.get(currentSum) || 0) + 1);
  }

  return count;
}

// Example usage
console.log(countSubarraysWithSum([1, 1, 1, 1, 1], 2)); //

 Output: 4

```

### 49. **Maximum Sum Rectangle**

**Problem:**
Find the maximum sum rectangle in a 2D matrix.

**Solution:**

```jsx
function maximumSumRectangle(matrix) {
  let rows = matrix.length;
  let cols = matrix[0].length;
  let maxSum = Number.MIN_VALUE;

  for (let left = 0; left < cols; left++) {
    let temp = Array(rows).fill(0);

    for (let right = left; right < cols; right++) {
      for (let i = 0; i < rows; i++) {
        temp[i] += matrix[i][right];
      }

      let currentSum = kadaneAlgorithm(temp);
      maxSum = Math.max(maxSum, currentSum);
    }
  }

  return maxSum;
}

// Kadane's algorithm for 1D array
function kadaneAlgorithm(arr) {
  let maxSoFar = arr[0];
  let maxEndingHere = arr[0];

  for (let i = 1; i < arr.length; i++) {
    maxEndingHere = Math.max(arr[i], maxEndingHere + arr[i]);
    maxSoFar = Math.max(maxSoFar, maxEndingHere);
  }
  return maxSoFar;
}

// Example usage
console.log(maximumSumRectangle([
  [1, 2, -1, -4, -20],
  [8, 10, -2,  1,  3],
  [3,  4,  3,  3,  2],
  [4,  5,  1,  3,  1]
])); // Output: 29

```

### 50. **Nth Element of Spiral Matrix**

**Problem:**
Find the Nth element in a matrix traversed in spiral order.

**Solution:**

```jsx
function nthElementInSpiral(matrix, n) {
  let rows = matrix.length;
  let cols = matrix[0].length;
  let top = 0, bottom = rows - 1;
  let left = 0, right = cols - 1;
  let count = 0;

  while (top <= bottom && left <= right) {
    for (let i = left; i <= right; i++) {
      if (++count === n) return matrix[top][i];
    }
    top++;

    for (let i = top; i <= bottom; i++) {
      if (++count === n) return matrix[i][right];
    }
    right--;

    for (let i = right; i >= left; i--) {
      if (++count === n) return matrix[bottom][i];
    }
    bottom--;

    for (let i = bottom; i >= top; i--) {
      if (++count === n) return matrix[i][left];
    }
    left++;
  }

  return -1; // If N is out of bounds
}

// Example usage
console.log(nthElementInSpiral([
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9]
], 5)); // Output: 5
```

## Intermediate DSA - 75

### 1. **Square Root**

**Problem:**
Find the integer part of the square root of a number `x`.

**Solution:**

```jsx
function sqrt(x) {
  if (x < 2) return x;

  let left = 1, right = x;
  while (left <= right) {
    let mid = Math.floor((left + right) / 2);
    let num = mid * mid;
    if (num === x) return mid;
    if (num < x) left = mid + 1;
    else right = mid - 1;
  }
  return right;
}

// Example usage
console.log(sqrt(16)); // Output: 4

```

### 2. **Search in Rotated Sorted Array**

**Problem:**
Search for a target value in a rotated sorted array.

**Solution:**

```jsx
function searchInRotatedArray(nums, target) {
  let left = 0, right = nums.length - 1;

  while (left <= right) {
    let mid = Math.floor((left + right) / 2);

    if (nums[mid] === target) return mid;

    if (nums[left] <= nums[mid]) {
      if (nums[left] <= target && target < nums[mid]) {
        right = mid - 1;
      } else {
        left = mid + 1;
      }
    } else {
      if (nums[mid] < target && target <= nums[right]) {
        left = mid + 1;
      } else {
        right = mid - 1;
      }
    }
  }

  return -1;
}

// Example usage
console.log(searchInRotatedArray([4, 5, 6, 7, 0, 1, 2], 0)); // Output: 4

```

### 3. **Find Element that Appears Twice**

**Problem:**
Find the element that appears twice in an array.

**Solution:**

```jsx
function findDuplicate(nums) {
  let slow = nums[0];
  let fast = nums[0];

  // Phase 1: Finding intersection point in the cycle
  do {
    slow = nums[slow];
    fast = nums[nums[fast]];
  } while (slow !== fast);

  // Phase 2: Finding the entrance to the cycle
  let ptr1 = nums[0];
  let ptr2 = slow;

  while (ptr1 !== ptr2) {
    ptr1 = nums[ptr1];
    ptr2 = nums[ptr2];
  }

  return ptr1;
}

// Example usage
console.log(findDuplicate([1, 3, 4, 2, 2])); // Output: 2

```

### 4. **Matrix Median**

**Problem:**
Find the median of a matrix where each row is sorted.

**Solution:**

```jsx
function findMatrixMedian(matrix) {
  let rows = matrix.length;
  let cols = matrix[0].length;
  let minVal = matrix[0][0];
  let maxVal = matrix[0][cols - 1];

  for (let i = 0; i < rows; i++) {
    minVal = Math.min(minVal, matrix[i][0]);
    maxVal = Math.max(maxVal, matrix[i][cols - 1]);
  }

  let desired = Math.floor((rows * cols + 1) / 2);

  while (minVal < maxVal) {
    let midVal = Math.floor((minVal + maxVal) / 2);
    let place = 0;

    for (let i = 0; i < rows; i++) {
      place += binarySearch(matrix[i], midVal);
    }

    if (place < desired) minVal = midVal + 1;
    else maxVal = midVal;
  }

  return minVal;
}

function binarySearch(row, x) {
  let low = 0;
  let high = row.length;

  while (low < high) {
    let mid = Math.floor((low + high) / 2);
    if (row[mid] <= x) low = mid + 1;
    else high = mid;
  }

  return low;
}

// Example usage
console.log(findMatrixMedian([
  [1, 3, 5],
  [2, 6, 9],
  [3, 6, 9]
])); // Output: 5

```

### 5. **Aggressive Cows**

**Problem:**
Place cows in stalls such that the minimum distance between any two cows is maximized.

**Solution:**

```jsx
function aggressiveCows(stalls, k) {
  stalls.sort((a, b) => a - b);
  let left = 1, right = stalls[stalls.length - 1] - stalls[0];
  let result = 0;

  while (left <= right) {
    let mid = Math.floor((left + right) / 2);
    if (canPlaceCows(stalls, k, mid)) {
      result = mid;
      left = mid + 1;
    } else {
      right = mid - 1;
    }
  }

  return result;
}

function canPlaceCows(stalls, k, minDist) {
  let count = 1;
  let lastPos = stalls[0];

  for (let i = 1; i < stalls.length; i++) {
    if (stalls[i] - lastPos >= minDist) {
      count++;
      lastPos = stalls[i];
    }
    if (count >= k) return true;
  }

  return false;
}

// Example usage
console.log(aggressiveCows([1, 2, 4, 8, 9], 3)); // Output: 3

```

### 6. **Merge Sort**

**Problem:**
Sort an array using merge sort algorithm.

**Solution:**

```jsx
function mergeSort(arr) {
  if (arr.length < 2) return arr;

  let mid = Math.floor(arr.length / 2);
  let left = mergeSort(arr.slice(0, mid));
  let right = mergeSort(arr.slice(mid));

  return merge(left, right);
}

function merge(left, right) {
  let result = [];
  let i = 0, j = 0;

  while (i < left.length && j < right.length) {
    if (left[i] < right[j]) result.push(left[i++]);
    else result.push(right[j++]);
  }

  return result.concat(left.slice(i)).concat(right.slice(j));
}

// Example usage
console.log(mergeSort([38, 27, 43, 3, 9, 82, 10])); // Output: [3, 9, 10, 27, 38, 43, 82]

```

### 7. **Quick Sort**

**Problem:**
Sort an array using quicksort algorithm.

**Solution:**

```jsx
function quickSort(arr) {
  if (arr.length < 2) return arr;

  let pivot = arr[arr.length - 1];
  let left = [], right = [];

  for (let i = 0; i < arr.length - 1; i++) {
    if (arr[i] < pivot) left.push(arr[i]);
    else right.push(arr[i]);
  }

  return [...quickSort(left), pivot, ...quickSort(right)];
}

// Example usage
console.log(quickSort([3, 6, 8, 10, 1, 2, 1])); // Output: [1, 1, 2, 3, 6, 8, 10]

```

### 8. **Find Kth Element**

**Problem:**
Find the Kth smallest element in an array.

**Solution:**

```jsx
function findKthSmallest(arr, k) {
  arr.sort((a, b) => a - b);
  return arr[k - 1];
}

// Example usage
console.log(findKthSmallest([7, 10, 4, 3, 20, 15], 3)); // Output: 7

```

### 9. **Family Structure**

**Problem:**
Design a family tree structure using classes.

**Solution:**

```jsx
class Person {
  constructor(name) {
    this.name = name;
    this.children = [];
  }

  addChild(child) {
    this.children.push(child);
  }
}

// Example usage
let parent = new Person("Parent");
let child1 = new Person("Child1");
let child2 = new Person("Child2");

parent.addChild(child1);
parent.addChild(child2);

console.log(parent);

```

### 10. **Binary String With No Consecutive 1s**

**Problem:**
Generate binary strings of length `n` that do not contain consecutive 1s.

**Solution:**

```jsx
function generateBinaryStrings(n) {
  let result = [];
  function backtrack(path) {
    if (path.length === n) {
      result.push(path);
      return;
    }
    backtrack(path + '0');
    if (path[path.length - 1] !== '1') {
      backtrack(path + '1');
    }
  }
  backtrack('');
  return result;
}

// Example usage
console.log(generateBinaryStrings(3)); // Output: ["000", "001", "010", "100", "101"]
```

### 11. **Reverse a Linked List**

**Problem:**
Reverse a singly linked list.

**Solution:**

```jsx
class ListNode {
  constructor(value = 0, next = null) {
    this.value = value;
    this.next = next;
  }
}

function reverseLinkedList(head) {
  let prev = null;
  let current = head;

  while (current !== null) {
    let next = current.next;
    current.next = prev;
    prev = current;
    current = next;
  }

  return prev;
}

// Example usage
let head = new ListNode(1, new ListNode(2, new ListNode(3)));
let reversed = reverseLinkedList(head);
let result = [];
while (reversed !== null) {
  result.push(reversed.value);
  reversed = reversed.next;
}
console.log(result); // Output: [3, 2, 1]

```

### 12. **Mid Point In Linked List**

**Problem:**
Find the middle node of a linked list.

**Solution:**

```jsx
function findMiddle(head) {
  let slow = head;
  let fast = head;

  while (fast !== null && fast.next !== null) {
    slow = slow.next;
    fast = fast.next.next;
  }

  return slow;
}

// Example usage
let head = new ListNode(1, new ListNode(2, new ListNode(3, new ListNode(4, new ListNode(5)))));
let middle = findMiddle(head);
console.log(middle.value); // Output: 3

```

### 13. **Add Two Linked Lists**

**Problem:**
Add two numbers represented by linked lists.

**Solution:**

```jsx
function addTwoLists(l1, l2) {
  let dummy = new ListNode(0);
  let p = l1, q = l2, curr = dummy;
  let carry = 0;

  while (p !== null || q !== null || carry !== 0) {
    let x = p !== null ? p.value : 0;
    let y = q !== null ? q.value : 0;
    let sum = carry + x + y;
    carry = Math.floor(sum / 10);
    curr.next = new ListNode(sum % 10);
    curr = curr.next;
    if (p !== null) p = p.next;
    if (q !== null) q = q.next;
  }

  return dummy.next;
}

// Example usage
let l1 = new ListNode(2, new ListNode(4, new ListNode(3)));
let l2 = new ListNode(5, new ListNode(6, new ListNode(4)));
let sum = addTwoLists(l1, l2);
let result = [];
while (sum !== null) {
  result.push(sum.value);
  sum = sum.next;
}
console.log(result); // Output: [7, 0, 8]

```

### 14. **Insertion Sort on Linked List**

**Problem:**
Sort a linked list using insertion sort.

**Solution:**

```jsx
function insertionSortList(head) {
  let dummy = new ListNode(-Infinity);

  while (head !== null) {
    let prev = dummy;
    let curr = dummy.next;

    while (curr !== null && curr.value < head.value) {
      prev = curr;
      curr = curr.next;
    }

    let next = head.next;
    head.next = curr;
    prev.next = head;
    head = next;
  }

  return dummy.next;
}

// Example usage
let head = new ListNode(4, new ListNode(2, new ListNode(1, new ListNode(3))));
let sorted = insertionSortList(head);
let result = [];
while (sorted !== null) {
  result.push(sorted.value);
  sorted = sorted.next;
}
console.log(result); // Output: [1, 2, 3, 4]

```

### 15. **Delete Kth Node from End**

**Problem:**
Delete the Kth node from the end of a linked list.

**Solution:**

```jsx
function deleteKthFromEnd(head, k) {
  let dummy = new ListNode(0, head);
  let fast = dummy;
  let slow = dummy;

  for (let i = 0; i <= k; i++) {
    fast = fast.next;
  }

  while (fast !== null) {
    slow = slow.next;
    fast = fast.next;
  }

  slow.next = slow.next.next;

  return dummy.next;
}

// Example usage
let head = new ListNode(1, new ListNode(2, new ListNode(3, new ListNode(4, new ListNode(5)))));
let modified = deleteKthFromEnd(head, 2);
let result = [];
while (modified !== null) {
  result.push(modified.value);
  modified = modified.next;
}
console.log(result); // Output: [1, 2, 3, 5]

```

### 16. **Detect and Remove Cycle**

**Problem:**
Detect and remove a cycle in a linked list.

**Solution:**

```jsx
function detectAndRemoveCycle(head) {
  let slow = head;
  let fast = head;

  while (fast !== null && fast.next !== null) {
    slow = slow.next;
    fast = fast.next.next;
    if (slow === fast) break;
  }

  if (fast === null || fast.next === null) return head;

  let start = head;
  while (start !== slow) {
    start = start.next;
    slow = slow.next;
  }

  let prev = null;
  while (slow !== start) {
    prev = slow;
    slow = slow.next;
  }

  prev.next = null;

  return head;
}

// Example usage
let head = new ListNode(1);
head.next = new ListNode(2);
head.next.next = new ListNode(3);
head.next.next.next = new ListNode(4);
head.next.next.next.next = head.next; // Creates a cycle

let noCycle = detectAndRemoveCycle(head);
let result = [];
while (noCycle !== null) {
  result.push(noCycle.value);
  noCycle = noCycle.next;
}
console.log(result); // Output: [1, 2, 3, 4]

```

### 17. **Swap Nodes in Pairs**

**Problem:**
Swap nodes in pairs in a linked list.

**Solution:**

```jsx
function swapPairs(head) {
  let dummy = new ListNode(0);
  dummy.next = head;
  let prev = dummy;

  while (head !== null && head.next !== null) {
    let first = head;
    let second = head.next;
    prev.next = second;
    first.next = second.next;
    second.next = first;
    prev = first;
    head = first.next;
  }

  return dummy.next;
}

// Example usage
let head = new ListNode(1, new ListNode(2, new ListNode(3, new ListNode(4))));
let swapped = swapPairs(head);
let result = [];
while (swapped !== null) {
  result.push(swapped.value);
  swapped = swapped.next;
}
console.log(result); // Output: [2, 1, 4, 3]

```

### 18. **Append Nodes**

**Problem:**
Append nodes from one linked list to another.

**Solution:**

```jsx
function appendNodes(head1, head2) {
  if (head1 === null) return head2;

  let current = head1;
  while (current.next !== null) {
    current = current.next;
  }
  current.next = head2;

  return head1;
}

// Example usage
let head1 = new ListNode(1, new ListNode(2));
let head2 = new ListNode(3, new ListNode(4));
let appended = appendNodes(head1, head2);
let result = [];
while (appended !== null) {
  result.push(appended.value);
  appended = appended.next;
}
console.log(result); // Output: [1, 2, 3, 4]

```

### 19. **Segregate Odd Even**

**Problem:**
Segregate odd and even nodes in a linked list.

**Solution:**

```jsx
function segregateOddEven(head) {
  let odd = new ListNode(0);
  let even = new ListNode(0);
  let oddTail = odd, evenTail = even;
  let isOdd = true;

  while (head !== null) {
    if (isOdd) {
      oddTail.next = head;
      oddTail = oddTail.next;
    } else {
      evenTail.next = head;
      evenTail = evenTail.next;
    }
    isOdd = !isOdd;
    head = head.next;
  }

  evenTail.next = null;
  oddTail.next = even.next;

  return odd.next;
}

// Example usage
let head = new ListNode(1, new ListNode(2, new ListNode(3, new ListNode(4, new ListNode(5)))));
let segregated = segregateOddEven(head);
let result = [];
while (segregated !== null) {
  result.push(segregated.value);
  segregated = segregated.next;
}
console.log(result); // Output: [1, 3, 5, 2, 4]

```

### 20. **Implement Stack Using Array**

- **Problem:** Implement a stack data structure using an array.

**Solution:**

```jsx
class Stack {
  constructor() {
    this.items = [];
  }

  push(element) {
    this.items.push(element);
  }

  pop() {
    if (this.isEmpty()) return null;
    return this.items.pop();
  }

  peek() {
    if (this.isEmpty()) return null;
    return this.items[this.items.length - 1];
  }

  isEmpty() {
    return this.items.length === 0;
  }

  size() {
    return this.items.length;
  }
}

// Example usage
let stack = new Stack();
stack.push(1);
stack.push(2);
console.log(stack.peek()); // Output: 2
console.log(stack.pop());  // Output: 2
console.log(stack.size()); // Output: 1
```

### 21. **Implement Stack Using Linked List**

**Problem:**
Implement a stack data structure using a linked list.

**Solution:**

```jsx
class ListNode {
  constructor(value = 0, next = null) {
    this.value = value;
    this.next = next;
  }
}

class Stack {
  constructor() {
    this.top = null;
    this.size = 0;
  }

  push(value) {
    const newNode = new ListNode(value, this.top);
    this.top = newNode;
    this.size++;
  }

  pop() {
    if (this.isEmpty()) return null;
    const value = this.top.value;
    this.top = this.top.next;
    this.size--;
    return value;
  }

  peek() {
    return this.isEmpty() ? null : this.top.value;
  }

  isEmpty() {
    return this.size === 0;
  }

  getSize() {
    return this.size;
  }
}

// Example usage
let stack = new Stack();
stack.push(1);
stack.push(2);
console.log(stack.peek()); // Output: 2
console.log(stack.pop());  // Output: 2
console.log(stack.getSize()); // Output: 1

```

### 22. **Implement Queue Using Array**

**Problem:**
Implement a queue data structure using an array.

**Solution:**

```jsx
class Queue {
  constructor() {
    this.items = [];
  }

  enqueue(element) {
    this.items.push(element);
  }

  dequeue() {
    if (this.isEmpty()) return null;
    return this.items.shift();
  }

  peek() {
    if (this.isEmpty()) return null;
    return this.items[0];
  }

  isEmpty() {
    return this.items.length === 0;
  }

  size() {
    return this.items.length;
  }
}

// Example usage
let queue = new Queue();
queue.enqueue(1);
queue.enqueue(2);
console.log(queue.peek()); // Output: 1
console.log(queue.dequeue()); // Output: 1
console.log(queue.size()); // Output: 1

```

### 23. **Implement Queue Using Linked List**

**Problem:**
Implement a queue data structure using a linked list.

**Solution:**

```jsx
class ListNode {
  constructor(value = 0, next = null) {
    this.value = value;
    this.next = next;
  }
}

class Queue {
  constructor() {
    this.front = null;
    this.rear = null;
    this.size = 0;
  }

  enqueue(value) {
    const newNode = new ListNode(value);
    if (this.isEmpty()) {
      this.front = this.rear = newNode;
    } else {
      this.rear.next = newNode;
      this.rear = newNode;
    }
    this.size++;
  }

  dequeue() {
    if (this.isEmpty()) return null;
    const value = this.front.value;
    this.front = this.front.next;
    if (this.front === null) this.rear = null;
    this.size--;
    return value;
  }

  peek() {
    return this.isEmpty() ? null : this.front.value;
  }

  isEmpty() {
    return this.size === 0;
  }

  getSize() {
    return this.size;
  }
}

// Example usage
let queue = new Queue();
queue.enqueue(1);
queue.enqueue(2);
console.log(queue.peek()); // Output: 1
console.log(queue.dequeue()); // Output: 1
console.log(queue.getSize()); // Output: 1

```

### 24. **Implement Queue Using 2 Stacks**

**Problem:**
Implement a queue using two stacks.

**Solution:**

```jsx
class QueueWithStacks {
  constructor() {
    this.stack1 = [];
    this.stack2 = [];
  }

  enqueue(element) {
    this.stack1.push(element);
  }

  dequeue() {
    if (this.isEmpty()) return null;

    if (this.stack2.length === 0) {
      while (this.stack1.length > 0) {
        this.stack2.push(this.stack1.pop());
      }
    }

    return this.stack2.pop();
  }

  peek() {
    if (this.isEmpty()) return null;

    if (this.stack2.length === 0) {
      while (this.stack1.length > 0) {
        this.stack2.push(this.stack1.pop());
      }
    }

    return this.stack2[this.stack2.length - 1];
  }

  isEmpty() {
    return this.stack1.length === 0 && this.stack2.length === 0;
  }

  size() {
    return this.stack1.length + this.stack2.length;
  }
}

// Example usage
let queue = new QueueWithStacks();
queue.enqueue(1);
queue.enqueue(2);
console.log(queue.peek()); // Output: 1
console.log(queue.dequeue()); // Output: 1
console.log(queue.size()); // Output: 1

```

### 25. **Implement Stack Using 2 Queues**

**Problem:**
Implement a stack using two queues.

**Solution:**

```jsx
class StackWithQueues {
  constructor() {
    this.queue1 = [];
    this.queue2 = [];
  }

  push(value) {
    this.queue1.push(value);
  }

  pop() {
    if (this.isEmpty()) return null;

    while (this.queue1.length > 1) {
      this.queue2.push(this.queue1.shift());
    }

    let popped = this.queue1.shift();

    [this.queue1, this.queue2] = [this.queue2, this.queue1];

    return popped;
  }

  peek() {
    if (this.isEmpty()) return null;

    while (this.queue1.length > 1) {
      this.queue2.push(this.queue1.shift());
    }

    let top = this.queue1[0];

    this.queue2.push(this.queue1.shift());

    [this.queue1, this.queue2] = [this.queue2, this.queue1];

    return top;
  }

  isEmpty() {
    return this.queue1.length === 0;
  }

  size() {
    return this.queue1.length;
  }
}

// Example usage
let stack = new StackWithQueues();
stack.push(1);
stack.push(2);
console.log(stack.peek()); // Output: 2
console.log(stack.pop());  // Output: 2
console.log(stack.size()); // Output: 1

```

### 26. **Min Stack**

**Problem:**
Implement a stack that supports retrieving the minimum element in constant time.

**Solution:**

```jsx
class MinStack {
  constructor() {
    this.stack = [];
    this.minStack = [];
  }

  push(value) {
    this.stack.push(value);
    if (this.minStack.length === 0 || value <= this.minStack[this.minStack.length - 1]) {
      this.minStack.push(value);
    }
  }

  pop() {
    if (this.stack.length === 0) return null;

    let value = this.stack.pop();
    if (value === this.minStack[this.minStack.length - 1]) {
      this.minStack.pop();
    }
    return value;
  }

  getMin() {
    return this.minStack.length === 0 ? null : this.minStack[this.minStack.length - 1];
  }
}

// Example usage
let minStack = new MinStack();
minStack.push(1);
minStack.push(2);
minStack.push(0);
console.log(minStack.getMin()); // Output: 0
console.log(minStack.pop());    // Output: 0
console.log(minStack.getMin()); // Output: 1

```

### 27. **Next Greater Element**

**Problem:**
Find the next greater element for each element in an array.

**Solution:**

```jsx
function nextGreaterElements(nums) {
  let stack = [];
  let result = new Array(nums.length).fill(-1);

  for (let i = 0; i < 2 * nums.length; i++) {
    let num = nums[i % nums.length];

    while (stack.length > 0 && nums[stack[stack.length - 1]] < num) {
      result[stack.pop()] = num;
    }

    stack.push(i % nums.length);
  }

  return result;
}

// Example usage
let nums = [1, 2, 1];
console.log(nextGreaterElements(nums)); // Output: [2, -1, 2]

```

### 28. **Stock Span Problem**

**Problem:**
Find the span of stock’s price for each day.

**Solution:**

```jsx
function calculateSpan(prices) {
  let span = new Array(prices.length).fill(1);
  let stack = [];

  for (let i = 0; i < prices.length; i++) {
    while (stack.length > 0 && prices[stack[stack.length - 1]] <= prices[i]) {
      stack.pop();
    }
    span[i] = stack.length === 0 ? i + 1 : i - stack[stack.length - 1];
    stack.push(i);
  }

  return span;
}

// Example usage
let prices = [100, 80, 60, 70, 60, 75, 85];
console.log(calculateSpan(prices)); // Output: [1, 1, 1, 2, 1, 4, 6]

```

### 29. **Reverse Queue**

**Problem:**
Reverse a queue.

**Solution:**

```jsx
function reverseQueue(queue) {
  let stack = [];

  while (queue.length > 0) {
    stack.push(queue.shift());
  }

  while (stack.length > 0) {
    queue.push(stack.pop());
  }
}

// Example usage
let queue = [1, 2, 3, 4, 5];
reverseQueue(queue);
console.log(queue); // Output: [5, 4, 3, 2, 1]

```

### 30. **Valid Parentheses**

**Problem:**
Check if the parentheses in a string are valid.

**Solution:**

```jsx
function isValid(s) {
  let stack = [];
  let map = { '(': ')', '[': ']', '{': '}' };

  for (let char of s) {
    if (char in map) {
      stack.push(char);
    } else {
      if (stack.length === 0 || map[stack.pop()] !== char) {
        return false;
      }
    }
  }

  return stack.length === 0;
}

// Example usage
let s = "()[]{}";
console.log(isValid(s)); // Output: true

```

### 31. **Diameter Of Binary Tree**

**Problem:**
Find the diameter of a binary tree (the longest path between any two nodes).

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function diameterOfBinaryTree(root) {
  let diameter = 0;

  function depth(node) {
    if (!node) return 0;

    let left = depth(node.left);
    let right = depth(node.right);

    diameter = Math.max(diameter, left + right);
    return Math.max(left, right) + 1;
  }

  depth(root);
  return diameter;
}

// Example usage
let root = new TreeNode(1, new TreeNode(2, new TreeNode(4), new TreeNode(5)), new TreeNode(3));
console.log(diameterOfBinaryTree(root)); // Output: 3

```

### 32. **LCA Of Binary Tree**

**Problem:**
Find the Lowest Common Ancestor (LCA) of two nodes in a binary tree.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function lowestCommonAncestor(root, p, q) {
  if (!root || root === p || root === q) return root;

  let left = lowestCommonAncestor(root.left, p, q);
  let right = lowestCommonAncestor(root.right, p, q);

  if (left && right) return root;
  return left ? left : right;
}

// Example usage
let root = new TreeNode(3, new TreeNode(5, new TreeNode(6), new TreeNode(2, new TreeNode(7), new TreeNode(4))), new TreeNode(1, new TreeNode(0), new TreeNode(8)));
let p = root.left;
let q = root.right;
console.log(lowestCommonAncestor(root, p, q).val); // Output: 3

```

### 33. **Level Order Traversal Binary Tree**

**Problem:**
Perform level order traversal (breadth-first traversal) of a binary tree.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function levelOrder(root) {
  if (!root) return [];

  let result = [];
  let queue = [root];

  while (queue.length > 0) {
    let level = [];
    let size = queue.length;

    for (let i = 0; i < size; i++) {
      let node = queue.shift();
      level.push(node.val);

      if (node.left) queue.push(node.left);
      if (node.right) queue.push(node.right);
    }

    result.push(level);
  }

  return result;
}

// Example usage
let root = new TreeNode(3, new TreeNode(9), new TreeNode(20, new TreeNode(15), new TreeNode(7)));
console.log(levelOrder(root)); // Output: [[3], [9, 20], [15, 7]]

```

### 34. **ZigZag Order Traversal Binary Tree**

**Problem:**
Perform ZigZag (spiral) order traversal of a binary tree.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function zigzagLevelOrder(root) {
  if (!root) return [];

  let result = [];
  let queue = [root];
  let level = 0;

  while (queue.length > 0) {
    let size = queue.length;
    let levelNodes = [];

    for (let i = 0; i < size; i++) {
      let node = queue.shift();
      if (level % 2 === 0) {
        levelNodes.push(node.val);
      } else {
        levelNodes.unshift(node.val);
      }

      if (node.left) queue.push(node.left);
      if (node.right) queue.push(node.right);
    }

    result.push(levelNodes);
    level++;
  }

  return result;
}

// Example usage
let root = new TreeNode(3, new TreeNode(9), new TreeNode(20, new TreeNode(15), new TreeNode(7)));
console.log(zigzagLevelOrder(root)); // Output: [[3], [20, 9], [15, 7]]

```

### 35. **Left View Of Binary Tree**

**Problem:**
Find the left view of a binary tree.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function leftView(root) {
  if (!root) return [];

  let result = [];
  let queue = [root];

  while (queue.length > 0) {
    let size = queue.length;

    for (let i = 0; i < size; i++) {
      let node = queue.shift();

      if (i === 0) result.push(node.val);

      if (node.left) queue.push(node.left);
      if (node.right) queue.push(node.right);
    }
  }

  return result;
}

// Example usage
let root = new TreeNode(1, new TreeNode(2, new TreeNode(4), new TreeNode(5)), new TreeNode(3, null, new TreeNode(6)));
console.log(leftView(root)); // Output: [1, 2, 4]

```

### 36. **Top View Of Binary Tree**

**Problem:**
Find the top view of a binary tree.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function topView(root) {
  if (!root) return [];

  let result = [];
  let map = new Map();
  let queue = [{ node: root, hd: 0 }];

  while (queue.length > 0) {
    let { node, hd } = queue.shift();

    if (!map.has(hd)) map.set(hd, node.val);

    if (node.left) queue.push({ node: node.left, hd: hd - 1 });
    if (node.right) queue.push({ node: node.right, hd: hd + 1 });
  }

  for (let [key, value] of [...map].sort((a, b) => a[0] - b[0])) {
    result.push(value);
  }

  return result;
}

// Example usage
let root = new TreeNode(1, new TreeNode(2, new TreeNode(4), new TreeNode(5)), new TreeNode(3, null, new TreeNode(6)));
console.log(topView(root)); // Output: [4, 2, 1, 3, 6]

```

### 37. **Construct Binary Tree From Inorder And Preorder**

**Problem:**
Construct a binary tree from given inorder and preorder traversals.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function buildTree(preorder, inorder) {
  if (!preorder.length || !inorder.length) return null;

  let rootVal = preorder[0];
  let root = new TreeNode(rootVal);

  let rootIndex = inorder.indexOf(rootVal);

  root.left = buildTree(preorder.slice(1, rootIndex + 1), inorder.slice(0, rootIndex));
  root.right = buildTree(preorder.slice(rootIndex + 1), inorder.slice(rootIndex + 1));

  return root;
}

// Example usage
let preorder = [3, 9, 20, 15, 7];
let inorder = [9, 3, 15, 20, 7];
console.log(buildTree(preorder, inorder)); // Constructed Tree

```

### 38. **Vertical Order Traversal Of Binary Tree**

**Problem:**
Perform vertical order traversal of a binary tree.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function verticalOrder(root) {
  if (!root) return [];

  let result = [];
  let map = new Map();
  let queue = [{ node: root, hd: 0 }];

  while (queue.length > 0) {
    let { node, hd } = queue.shift();

    if (!map.has(hd)) map.set(hd, []);
    map.get(hd).push(node.val);

    if (node.left) queue.push({ node: node.left, hd: hd - 1 });
    if (node.right) queue.push({ node: node.right, hd:

 hd + 1 });
  }

  for (let [key, value] of [...map].sort((a, b) => a[0] - b[0])) {
    result.push(value);
  }

  return result;
}

// Example usage
let root = new TreeNode(1, new TreeNode(2, new TreeNode(4), new TreeNode(5)), new TreeNode(3, new TreeNode(6), new TreeNode(7)));
console.log(verticalOrder(root)); // Output: [[4], [2], [1, 5, 6], [3], [7]]

```

### 39. **Inorder Traversal Binary Tree Using Stacks**

**Problem:**
Perform inorder traversal of a binary tree using stacks.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function inorderTraversal(root) {
  let result = [];
  let stack = [];
  let curr = root;

  while (curr || stack.length) {
    while (curr) {
      stack.push(curr);
      curr = curr.left;
    }

    curr = stack.pop();
    result.push(curr.val);
    curr = curr.right;
  }

  return result;
}

// Example usage
let root = new TreeNode(1, null, new TreeNode(2, new TreeNode(3)));
console.log(inorderTraversal(root)); // Output: [1, 3, 2]

```

### 40. **LCA of Two Nodes in BST**

**Problem:**
Find the Lowest Common Ancestor (LCA) of two nodes in a Binary Search Tree (BST).

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function lowestCommonAncestorBST(root, p, q) {
  if (root.val > p.val && root.val > q.val) {
    return lowestCommonAncestorBST(root.left, p, q);
  }

  if (root.val < p.val && root.val < q.val) {
    return lowestCommonAncestorBST(root.right, p, q);
  }

  return root;
}

// Example usage
let root = new TreeNode(6, new TreeNode(2, new TreeNode(0), new TreeNode(4, new TreeNode(3), new TreeNode(5))), new TreeNode(8, new TreeNode(7), new TreeNode(9)));
let p = root.left; // Node with value 2
let q = root.right; // Node with value 8
console.log(lowestCommonAncestorBST(root, p, q).val); // Output: 6

```

### 41. **Check if Binary Tree is BST?**

**Problem:**
Check if a binary tree is a binary search tree (BST).

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function isValidBST(root, min = -Infinity, max = Infinity) {
  if (!root) return true;
  if (root.val <= min || root.val >= max) return false;

  return isValidBST(root.left, min, root.val) && isValidBST(root.right, root.val, max);
}

// Example usage
let root = new TreeNode(2, new TreeNode(1), new TreeNode(3));
console.log(isValidBST(root)); // Output: true

```

### 42. **Kth Smallest Element in BST**

**Problem:**
Find the Kth smallest element in a Binary Search Tree (BST).

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function kthSmallest(root, k) {
  let stack = [];
  let count = 0;

  while (root || stack.length) {
    while (root) {
      stack.push(root);
      root = root.left;
    }

    root = stack.pop();
    count++;

    if (count === k) return root.val;

    root = root.right;
  }
}

// Example usage
let root = new TreeNode(3, new TreeNode(1, null, new TreeNode(2)), new TreeNode(4));
console.log(kthSmallest(root, 2)); // Output: 2

```

### 43. **Predecessor And Successor In BST**

**Problem:**
Find the predecessor and successor of a given node in a Binary Search Tree (BST).

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function findPredecessorSuccessor(root, key) {
  let predecessor = null;
  let successor = null;

  function inorderTraversal(node) {
    if (!node) return;
    inorderTraversal(node.left);

    if (node.val < key) {
      predecessor = node;
    }
    if (node.val > key && !successor) {
      successor = node;
    }

    inorderTraversal(node.right);
  }

  inorderTraversal(root);
  return { predecessor, successor };
}

// Example usage
let root = new TreeNode(5, new TreeNode(3, new TreeNode(2), new TreeNode(4)), new TreeNode(6));
let key = 4;
console.log(findPredecessorSuccessor(root, key)); // Output: { predecessor: TreeNode { val: 3 }, successor: TreeNode { val: 5 } }

```

### 44. **Pair Sum in BST**

**Problem:**
Find if there is a pair in the BST that sums up to a given value.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function findPair(root, target) {
  let set = new Set();

  function inorderTraversal(node) {
    if (!node) return false;

    if (set.has(target - node.val)) return true;

    set.add(node.val);
    return inorderTraversal(node.left) || inorderTraversal(node.right);
  }

  return inorderTraversal(root);
}

// Example usage
let root = new TreeNode(5, new TreeNode(3, new TreeNode(2), new TreeNode(4)), new TreeNode(6));
let target = 9;
console.log(findPair(root, target)); // Output: true

```

### 45. **Find Whether Array is Subset of Another Array**

**Problem:**
Check if one array is a subset of another array.

**Solution:**

```jsx
function isSubset(arr1, arr2) {
  let set = new Set(arr1);

  for (let num of arr2) {
    if (!set.has(num)) return false;
  }

  return true;
}

// Example usage
let arr1 = [11, 1, 13, 21, 3, 7];
let arr2 = [11, 3, 7, 1];
console.log(isSubset(arr1, arr2)); // Output: true

```

### 46. **Median of 2 Sorted Arrays**

**Problem:**
Find the median of two sorted arrays.

**Solution:**

```jsx
function findMedianSortedArrays(nums1, nums2) {
  let merged = [...nums1, ...nums2].sort((a, b) => a - b);
  let len = merged.length;
  let mid = Math.floor(len / 2);

  if (len % 2 === 0) {
    return (merged[mid - 1] + merged[mid]) / 2;
  } else {
    return merged[mid];
  }
}

// Example usage
let nums1 = [1, 3];
let nums2 = [2];
console.log(findMedianSortedArrays(nums1, nums2)); // Output: 2

```

### 47. **LCA of 3 Nodes**

**Problem:**
Find the Lowest Common Ancestor (LCA) of three nodes in a binary tree.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function lowestCommonAncestorThreeNodes(root, a, b, c) {
  if (!root) return null;

  if (root === a || root === b || root === c) return root;

  let left = lowestCommonAncestorThreeNodes(root.left, a, b, c);
  let right = lowestCommonAncestorThreeNodes(root.right, a, b, c);

  if (left && right) return root;
  return left ? left : right;
}

// Example usage
let root = new TreeNode(1, new TreeNode(2), new TreeNode(3));
let a = root.left;
let b = root.right;
let c = root;
console.log(lowestCommonAncestorThreeNodes(root, a, b, c).val); // Output: 1

```

### 48. **Remove Keys Outside Given Range**

**Problem:**
Remove nodes from a binary search tree that are outside a given range.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function trimBST(root, L, R) {
  if (!root) return null;

  if (root.val < L) return trimBST(root.right, L, R);
  if (root.val > R) return trimBST(root.left, L, R);

  root.left = trimBST(root.left, L, R);
  root.right = trimBST(root.right, L, R);
  return root;
}

// Example usage
let root = new TreeNode(3, new TreeNode(0, null, new TreeNode(2)), new TreeNode(4));
console.log(trimBST(root, 1, 3)); // Output: [3, null, 2]

```

### 49. **Search in a Row Wise and Column Wise Sorted Matrix**

**Problem:**
Search for a value in a matrix where rows and columns are sorted.

**Solution:**

```jsx
function searchMatrix(matrix, target) {
  let row = 0;
  let col = matrix[0].length - 1;

  while (row < matrix.length && col >= 0) {
    if (matrix[row][col] === target) return true;
    if (matrix[row][col] > target) col--;
    else row++;
  }

  return false;
}

// Example usage
let matrix = [
  [1, 4, 7, 11],
  [2, 5, 8, 12],
  [3, 6, 9, 16],
  [10, 13, 14, 17]
];
console.log(searchMatrix(matrix, 5)); // Output: true

```

### 50. **Check Linked List is Palindrome?**

**Problem:**
Check if a linked list is a palindrome.

**Solution:**

```jsx
class ListNode {
  constructor(val = 0, next = null) {
    this.val = val;
    this.next = next;
  }
}

function isPalindrome(head) {
  let values = [];
  let current = head;

  while (current) {
    values.push(current.val);
    current = current.next;
  }

  let left = 0;
  let right = values.length - 1;

  while (left < right) {
    if (values[left] !== values[right]) return false;
    left++;
    right--;
  }

  return true;
}

// Example usage
let head = new ListNode(1, new ListNode(2, new ListNode(2,

 new ListNode(1))));
console.log(isPalindrome(head)); // Output: true

```

### 51. **K Reverse Linked List**

**Problem:**
Reverse nodes in a linked list in groups of size K.

**Solution:**

```jsx
class ListNode {
  constructor(val = 0, next = null) {
    this.val = val;
    this.next = next;
  }
}

function reverseKGroup(head, k) {
  let count = 0;
  let current = head;

  while (current && count !== k) {
    current = current.next;
    count++;
  }

  if (count === k) {
    current = reverseKGroup(current, k);

    while (count--) {
      let tmp = head.next;
      head.next = current;
      current = head;
      head = tmp;
    }

    head = current;
  }

  return head;
}

// Example usage
let head = new ListNode(1, new ListNode(2, new ListNode(3, new ListNode(4, new ListNode(5)))));
console.log(reverseKGroup(head, 3)); // Output: 3 -> 2 -> 1 -> 4 -> 5

```

### 52. **Tower of Hanoi**

**Problem:**
Solve the Tower of Hanoi problem with `n` disks.

**Solution:**

```jsx
function towerOfHanoi(n, from, to, aux) {
  if (n === 1) {
    console.log(`Move disk 1 from ${from} to ${to}`);
    return;
  }

  towerOfHanoi(n - 1, from, aux, to);
  console.log(`Move disk ${n} from ${from} to ${to}`);
  towerOfHanoi(n - 1, aux, to, from);
}

// Example usage
towerOfHanoi(3, 'A', 'C', 'B');
// Output: Sequence of moves to solve the puzzle with 3 disks

```

### 53. **BST Iterator**

**Problem:**
Implement an iterator for a Binary Search Tree (BST).

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

class BSTIterator {
  constructor(root) {
    this.stack = [];
    this._leftmostInorder(root);
  }

  _leftmostInorder(root) {
    while (root) {
      this.stack.push(root);
      root = root.left;
    }
  }

  next() {
    let topNode = this.stack.pop();
    if (topNode.right) {
      this._leftmostInorder(topNode.right);
    }
    return topNode.val;
  }

  hasNext() {
    return this.stack.length > 0;
  }
}

// Example usage
let root = new TreeNode(7, new TreeNode(3), new TreeNode(15, new TreeNode(9), new TreeNode(20)));
let iterator = new BSTIterator(root);
console.log(iterator.next());    // Output: 3
console.log(iterator.hasNext()); // Output: true
console.log(iterator.next());    // Output: 7

```

### 54. **Flatten Binary Tree To Linked List**

**Problem:**
Flatten a binary tree into a linked list in place.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function flatten(root) {
  let prev = null;

  function flattenTree(node) {
    if (!node) return;

    flattenTree(node.right);
    flattenTree(node.left);

    node.right = prev;
    node.left = null;
    prev = node;
  }

  flattenTree(root);
}

// Example usage
let root = new TreeNode(1, new TreeNode(2, new TreeNode(3)), new TreeNode(5, new TreeNode(4), new TreeNode(6)));
flatten(root);
// The tree will be flattened into: 1 -> 2 -> 3 -> 5 -> 4 -> 6

```

### 55. **Rearrange Linked List**

**Problem:**
Rearrange a linked list in a specific order (e.g., alternating small and large values).

**Solution:**

```jsx
class ListNode {
  constructor(val = 0, next = null) {
    this.val = val;
    this.next = next;
  }
}

function rearrangeList(head) {
  if (!head || !head.next) return head;

  let slow = head;
  let fast = head;

  while (fast && fast.next) {
    slow = slow.next;
    fast = fast.next.next;
  }

  let second = slow.next;
  slow.next = null;

  let prev = null;
  let curr = second;

  while (curr) {
    let next = curr.next;
    curr.next = prev;
    prev = curr;
    curr = next;
  }

  second = prev;
  let first = head;

  while (second) {
    let temp1 = first.next;
    let temp2 = second.next;

    first.next = second;
    second.next = temp1;

    first = temp1;
    second = temp2;
  }

  return head;
}

// Example usage
let head = new ListNode(1, new ListNode(2, new ListNode(3, new ListNode(4, new ListNode(5)))));
console.log(rearrangeList(head)); // Output: 1 -> 5 -> 2 -> 4 -> 3

```

### 56. **Largest Rectangle in Histogram**

**Problem:**
Find the largest rectangle area in a histogram.

**Solution:**

```jsx
function largestRectangleArea(heights) {
  let stack = [];
  let maxArea = 0;
  let index = 0;

  while (index < heights.length) {
    if (stack.length === 0 || heights[index] >= heights[stack[stack.length - 1]]) {
      stack.push(index++);
    } else {
      let top = stack.pop();
      let width = stack.length === 0 ? index : index - stack[stack.length - 1] - 1;
      maxArea = Math.max(maxArea, heights[top] * width);
    }
  }

  while (stack.length) {
    let top = stack.pop();
    let width = stack.length === 0 ? index : index - stack[stack.length - 1] - 1;
    maxArea = Math.max(maxArea, heights[top] * width);
  }

  return maxArea;
}

// Example usage
let heights = [2, 1, 5, 6, 2, 3];
console.log(largestRectangleArea(heights)); // Output: 10

```

### 57. **Quick Sort on Linked List**

**Problem:**
Sort a linked list using Quick Sort.

**Solution:**

```jsx
class ListNode {
  constructor(val = 0, next = null) {
    this.val = val;
    this.next = next;
  }
}

function quickSortList(head) {
  if (!head || !head.next) return head;

  function partition(head, end) {
    let pivot = end.val;
    let prev = null;
    let cur = head;
    let tail = end;

    while (cur !== end) {
      if (cur.val < pivot) {
        if (!prev) {
          head = cur;
        } else {
          prev.next = cur;
        }
        prev = cur;
      }
      cur = cur.next;
    }

    if (!prev) {
      head = end;
    } else {
      prev.next = end;
    }
    tail.next = cur;

    return [head, end, tail];
  }

  function quickSort(head, end) {
    if (!head || head === end) return head;

    let [newHead, pivot, tail] = partition(head, end);

    quickSort(newHead, pivot);
    quickSort(tail.next, end);

    return newHead;
  }

  let end = head;
  while (end.next) {
    end = end.next;
  }

  return quickSort(head, end);
}

// Example usage
let head = new ListNode(4, new ListNode(2, new ListNode(1, new ListNode(3))));
console.log(quickSortList(head)); // Output: 1 -> 2 -> 3 -> 4

```

### 58. **Sorted Linked List to Balanced BST**

**Problem:**
Convert a sorted linked list to a balanced binary search tree (BST).

**Solution:**

```jsx
class ListNode {
  constructor(val = 0, next = null) {
    this.val = val;
    this.next = next;
  }
}

class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function sortedListToBST(head) {
  let nums = [];
  while (head) {
    nums.push(head.val);
    head = head.next;
  }

  function buildTree(left, right) {
    if (left > right) return null;

    let mid = Math.floor((left + right) / 2);
    let root = new TreeNode(nums[mid]);
    root.left = buildTree(left, mid - 1);
    root.right

 = buildTree(mid + 1, right);

    return root;
  }

  return buildTree(0, nums.length - 1);
}

// Example usage
let head = new ListNode(-10, new ListNode(-3, new ListNode(0, new ListNode(5, new ListNode(9)))));
console.log(sortedListToBST(head)); // Output: Balanced BST

```

### 59. **Binary Tree to Doubly Linked List**

**Problem:**
Convert a binary tree to a doubly linked list in place.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function binaryTreeToDLL(root) {
  let head = null;
  let prev = null;

  function inOrderTraversal(node) {
    if (!node) return;

    inOrderTraversal(node.left);

    if (prev === null) {
      head = node;
    } else {
      prev.right = node;
      node.left = prev;
    }

    prev = node;

    inOrderTraversal(node.right);
  }

  inOrderTraversal(root);

  return head;
}

// Example usage
let root = new TreeNode(4, new TreeNode(2, new TreeNode(1), new TreeNode(3)), new TreeNode(5));
console.log(binaryTreeToDLL(root)); // Output: Doubly linked list

```

### 60. **Bottom Right View of Binary Tree**

**Problem:**
Find the bottom-right view of a binary tree.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function bottomRightView(root) {
  if (!root) return [];

  let result = [];
  let queue = [[root, 0]];

  while (queue.length) {
    let [node, level] = queue.shift();

    if (result.length <= level) result.push(node.val);
    else result[level] = node.val;

    if (node.left) queue.push([node.left, level + 1]);
    if (node.right) queue.push([node.right, level + 1]);
  }

  return result;
}

// Example usage
let root = new TreeNode(1, new TreeNode(2, new TreeNode(4), new TreeNode(5)), new TreeNode(3, null, new TreeNode(6)));
console.log(bottomRightView(root)); // Output: [1, 3, 6]

```

### 61. **Merge Two BSTs**

**Problem:**
Merge two Binary Search Trees (BSTs) into one BST.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function mergeBSTs(root1, root2) {
  function inOrderTraversal(node, arr) {
    if (!node) return;
    inOrderTraversal(node.left, arr);
    arr.push(node.val);
    inOrderTraversal(node.right, arr);
  }

  function sortedArrayToBST(arr) {
    if (!arr.length) return null;
    let mid = Math.floor(arr.length / 2);
    let root = new TreeNode(arr[mid]);
    root.left = sortedArrayToBST(arr.slice(0, mid));
    root.right = sortedArrayToBST(arr.slice(mid + 1));
    return root;
  }

  let vals1 = [], vals2 = [];
  inOrderTraversal(root1, vals1);
  inOrderTraversal(root2, vals2);
  let merged = [...vals1, ...vals2];
  return sortedArrayToBST(merged);
}

// Example usage
let root1 = new TreeNode(1, new TreeNode(0), new TreeNode(3));
let root2 = new TreeNode(4, new TreeNode(2), new TreeNode(5));
console.log(mergeBSTs(root1, root2)); // Output: Merged BST

```

### 62. **Merge Two Binary Trees**

**Problem:**
Merge two binary trees by summing up overlapping nodes.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function mergeTrees(t1, t2) {
  if (!t1) return t2;
  if (!t2) return t1;

  t1.val += t2.val;
  t1.left = mergeTrees(t1.left, t2.left);
  t1.right = mergeTrees(t1.right, t2.right);

  return t1;
}

// Example usage
let t1 = new TreeNode(1, new TreeNode(3, new TreeNode(5)), new TreeNode(2));
let t2 = new TreeNode(2, new TreeNode(1, null, new TreeNode(4)), new TreeNode(3, null, new TreeNode(7)));
console.log(mergeTrees(t1, t2)); // Output: Merged tree

```

### 63. **Sort a Stack**

**Problem:**
Sort a stack using another stack.

**Solution:**

```jsx
function sortStack(stack) {
  let tempStack = [];

  while (stack.length) {
    let temp = stack.pop();

    while (tempStack.length && tempStack[tempStack.length - 1] > temp) {
      stack.push(tempStack.pop());
    }

    tempStack.push(temp);
  }

  while (tempStack.length) {
    stack.push(tempStack.pop());
  }

  return stack;
}

// Example usage
let stack = [34, 3, 31, 98, 92, 23];
console.log(sortStack(stack)); // Output: [3, 23, 31, 34, 92, 98]

```

### 64. **Boundary Traversal of Binary Tree**

**Problem:**
Print the boundary traversal of a binary tree.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function boundaryTraversal(root) {
  if (!root) return [];

  function leftBoundary(node) {
    if (node) {
      if (node.left) {
        result.push(node.val);
        leftBoundary(node.left);
      } else if (node.right) {
        result.push(node.val);
        leftBoundary(node.right);
      }
    }
  }

  function leaves(node) {
    if (node) {
      leaves(node.left);
      if (!node.left && !node.right) result.push(node.val);
      leaves(node.right);
    }
  }

  function rightBoundary(node) {
    if (node) {
      if (node.right) {
        rightBoundary(node.right);
        result.push(node.val);
      } else if (node.left) {
        rightBoundary(node.left);
        result.push(node.val);
      }
    }
  }

  let result = [root.val];
  leftBoundary(root.left);
  leaves(root);
  rightBoundary(root.right);

  return result;
}

// Example usage
let root = new TreeNode(1, new TreeNode(2, new TreeNode(4), new TreeNode(5)), new TreeNode(3, null, new TreeNode(6)));
console.log(boundaryTraversal(root)); // Output: [1, 2, 4, 5, 6, 3]

```

### 65. **Longest Substring with K Distinct Characters**

**Problem:**
Find the longest substring with exactly K distinct characters.

**Solution:**

```jsx
function longestSubstringKDistinct(s, k) {
  let map = new Map();
  let start = 0, maxLen = 0;

  for (let end = 0; end < s.length; end++) {
    map.set(s[end], (map.get(s[end]) || 0) + 1);

    while (map.size > k) {
      map.set(s[start], map.get(s[start]) - 1);
      if (map.get(s[start]) === 0) map.delete(s[start]);
      start++;
    }

    maxLen = Math.max(maxLen, end - start + 1);
  }

  return maxLen;
}

// Example usage
console.log(longestSubstringKDistinct("eceba", 2)); // Output: 3 ("ece" or "eba")

```

### 66. **HashMap Implementation**

**Problem:**
Implement a basic HashMap.

**Solution:**

```jsx
class HashMap {
  constructor(size = 10) {
    this.size = size;
    this.map = new Array(size).fill(null).map(() => []);
  }

  _hash(key) {
    return key.toString().length % this.size;
  }

  set(key, value) {
    let index = this._hash(key);
    let bucket = this.map[index];
    let found = false;

    for (let i = 0; i < bucket.length; i++) {
      if (bucket[i][0] === key) {
        bucket[i][1] = value;
        found = true;
        break;
      }
    }

    if (!found) bucket.push([key, value]);
  }

  get(key) {
    let index = this._hash(key);
    let bucket = this.map[index];

    for (let [k, v] of bucket) {
      if (k === key) return v;
    }

    return undefined;
  }
}

// Example usage
let hashMap = new HashMap();
hashMap.set(1, 'one');
console.log(hashMap.get(1)); // Output: 'one'

```

### 67. **Closest Distance Pair**

**Problem:**
Find the closest distance pair of points in a 2D plane.

**Solution:**

```jsx
function closestDistancePair(points) {
  points.sort((a, b) => a[0] - b[0]);

  function dist(p1, p2) {
    return Math.hypot(p1[0] - p2[0], p1[1] - p2[1]);
  }

  function closestPair(start, end) {
    if (end - start <= 1) return Infinity;

    let mid = Math.floor((start + end) / 2);
    let midX = points[mid][0];
    let minDist = Math.min(closestPair(start, mid), closestPair(mid, end));

    let strip = [];
    for (let i = start; i < end; i++) {
      if (Math.abs(points[i][0] - midX) < minDist) {
        strip.push(points[i]);
      }
    }

    strip.sort((a, b) => a[1] - b[1]);

    for (let i = 0; i < strip.length; i++) {
      for (let j = i + 1; j < strip.length && strip[j][1] - strip[i][1] < minDist; j++) {
        minDist = Math.min(minDist, dist(strip[i], strip[j]));
      }
    }

    return minDist;
  }

  return closestPair(0, points.length);
}

// Example usage
let points = [[0,0], [1,1], [2,2], [3,3], [4,4]];
console.log(closestDistancePair(points)); // Output: Minimum distance between any two points

```

### 68. **Time to Burn Tree**

**Problem:**
Find the time taken to burn a binary tree from a given node.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function timeToBurnTree(root, target) {
  let time = 0;

  function buildGraph(node, parent, graph) {
    if

 (!node) return;

    if (parent !== null) {
      if (!graph[parent]) graph[parent] = [];
      if (!graph[node.val]) graph[node.val] = [];
      graph[parent].push(node.val);
      graph[node.val].push(parent);
    }

    buildGraph(node.left, node.val, graph);
    buildGraph(node.right, node.val, graph);
  }

  function bfs(start, graph) {
    let visited = new Set();
    let queue = [[start, 0]]; // [node, time]
    let maxTime = 0;

    while (queue.length) {
      let [node, curTime] = queue.shift();
      visited.add(node);
      maxTime = Math.max(maxTime, curTime);

      for (let neighbor of graph[node] || []) {
        if (!visited.has(neighbor)) {
          queue.push([neighbor, curTime + 1]);
        }
      }
    }

    return maxTime;
  }

  let graph = {};
  buildGraph(root, null, graph);

  return bfs(target, graph);
}

// Example usage
let root = new TreeNode(1, new TreeNode(2, new TreeNode(4), new TreeNode(5)), new TreeNode(3, new TreeNode(6), new TreeNode(7)));
console.log(timeToBurnTree(root, 5)); // Output: Time to burn tree starting from node 5

```

### 69. **Allocate Books**

**Problem:**
Allocate books to students in such a way that the maximum number of pages assigned to a student is minimized.

**Solution:**

```jsx
function allocateBooks(pages, students) {
  let start = Math.max(...pages);
  let end = pages.reduce((a, b) => a + b, 0);

  function canAllocate(maxPages) {
    let studentCount = 1, currentPages = 0;
    for (let page of pages) {
      if (currentPages + page > maxPages) {
        studentCount++;
        currentPages = page;
        if (studentCount > students) return false;
      } else {
        currentPages += page;
      }
    }
    return true;
  }

  while (start < end) {
    let mid = Math.floor((start + end) / 2);
    if (canAllocate(mid)) end = mid;
    else start = mid + 1;
  }

  return start;
}

// Example usage
let pages = [12, 34, 67, 90];
let students = 2;
console.log(allocateBooks(pages, students)); // Output: Minimum pages

```

### 70. **Clone a LinkedList with Random and Next Pointer**

**Problem:**
Clone a linked list where each node has an additional random pointer.

**Solution:**

```jsx
class ListNode {
  constructor(val = 0, next = null, random = null) {
    this.val = val;
    this.next = next;
    this.random = random;
  }
}

function cloneLinkedList(head) {
  let map = new Map();
  let node = head;

  while (node) {
    map.set(node, new ListNode(node.val));
    node = node.next;
  }

  node = head;
  while (node) {
    map.get(node).next = map.get(node.next) || null;
    map.get(node).random = map.get(node.random) || null;
    node = node.next;
  }

  return map.get(head);
}

// Example usage
let head = new ListNode(1, new ListNode(2), new ListNode(3));
head.random = head.next.next;
head.next.random = head;

console.log(cloneLinkedList(head)); // Output: Cloned linked list

```

### 71. **Fix BST**

**Problem:**
Fix a binary search tree (BST) where two nodes are swapped by mistake.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function fixBST(root) {
  let first = null, second = null, prev = new TreeNode(-Infinity);

  function inorderTraversal(node) {
    if (!node) return;

    inorderTraversal(node.left);

    if (!first && prev.val >= node.val) {
      first = prev;
    }
    if (first && prev.val >= node.val) {
      second = node;
    }

    prev = node;
    inorderTraversal(node.right);
  }

  inorderTraversal(root);

  if (first && second) {
    let temp = first.val;
    first.val = second.val;
    second.val = temp;
  }

  return root;
}

// Example usage
let root = new TreeNode(1, new TreeNode(3, null, new TreeNode(2)));
console.log(fixBST(root)); // Output: Fixed BST

```

### 72. **Nth Root of Integer**

**Problem:**
Find the Nth root of an integer `x`.

**Solution:**

```jsx
function nthRoot(x, n) {
  if (x < 0 && n % 2 === 0) return NaN; // Even roots of negative numbers are not real

  let low = 0, high = x, eps = 1e-6;

  while (high - low > eps) {
    let mid = (low + high) / 2;
    if (Math.pow(mid, n) < x) low = mid;
    else high = mid;
  }

  return (low + high) / 2;
}

// Example usage
console.log(nthRoot(27, 3)); // Output: 3 (cube root of 27)

```

### 73. **Size of the Largest BST**

**Problem:**
Find the size of the largest Binary Search Tree (BST) in a binary tree.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function largestBSTSize(root) {
  function helper(node) {
    if (!node) return [true, 0, Infinity, -Infinity];

    let [leftIsBST, leftSize, leftMin, leftMax] = helper(node.left);
    let [rightIsBST, rightSize, rightMin, rightMax] = helper(node.right);

    if (leftIsBST && rightIsBST && node.val > leftMax && node.val < rightMin) {
      return [true, leftSize + rightSize + 1, Math.min(node.val, leftMin), Math.max(node.val, rightMax)];
    }

    return [false, Math.max(leftSize, rightSize), 0, 0];
  }

  return helper(root)[1];
}

// Example usage
let root = new TreeNode(10, new TreeNode(5, new TreeNode(1), new TreeNode(8)), new TreeNode(15, null, new TreeNode(7)));
console.log(largestBSTSize(root)); // Output: Size of the largest BST

```

### 74. **LRU Cache**

**Problem:**
Implement an LRU (Least Recently Used) cache.

**Solution:**

```jsx
class LRUCache {
  constructor(capacity) {
    this.capacity = capacity;
    this.cache = new Map();
  }

  get(key) {
    if (!this.cache.has(key)) return -1;
    let value = this.cache.get(key);
    this.cache.delete(key);
    this.cache.set(key, value);
    return value;
  }

  put(key, value) {
    if (this.cache.size >= this.capacity) {
      this.cache.delete(this.cache.keys().next().value);
    }
    this.cache.delete(key);
    this.cache.set(key, value);
  }
}

// Example usage
let cache = new LRUCache(2);
cache.put(1, 1);
cache.put(2, 2);
console.log(cache.get(1)); // Output: 1
cache.put(3, 3); // Evicts key 2
console.log(cache.get(2)); // Output: -1 (not found)
cache.put(4, 4); // Evicts key 1
console.log(cache.get(1)); // Output: -1 (not found)
console.log(cache.get(3)); // Output: 3
console.log(cache.get(4)); // Output: 4

```

### 75. **Binary Tree to Doubly Linked List**

**Problem:**
Convert a binary tree to a doubly linked list (DLL) in-place.

**Solution:**

```jsx
class TreeNode {
  constructor(val = 0, left = null, right = null) {
    this.val = val;
    this.left = left;
    this.right = right;
  }
}

function binaryTreeToDLL(root) {
  let head = null, prev = null;

  function inOrderTraversal(node) {
    if (!node) return;

    inOrderTraversal(node.left);

    if (prev === null) {
      head = node;
    } else {
      prev.right = node;
      node.left = prev;
    }
    prev = node;

    inOrderTraversal(node.right);
  }

  inOrderTraversal(root);
  return head;
}

// Example usage
let root = new TreeNode(4, new TreeNode(2, new TreeNode(1), new TreeNode(3)), new TreeNode(5));
let dllHead = binaryTreeToDLL(root);

// Print DLL
let node = dllHead;
while (node) {
  console.log(node.val);
  node = node.right;
}

```
