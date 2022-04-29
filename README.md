# problem_solutions
Crowdsourced solutions to in-class Problems

Please follow the formatting conventions to make the solutions as uniform and navigable as possible:

Solutions for L## problems are in a folder called P##.

One file, called `P##.md` contains the solutions in [markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) format. This is mostly just plaintext, but with some nice text formatting features. Examples (see also this file for examples of how markdown syntax works):

* \`backticks\` around text make it render `like this`, which is handy for code snippets

* You can create a code block as follows:

  \```

  your code here

  \```

  which will render like this:

  ```
  your code here
  ```

* If it's java, you can say so and get syntax highlighting by specifying the language after the opening set of backticks:

  \```java

  public class Foo {}

  \```

  renders like this:

  ```java
  public class Foo {}
  ```

* Bullets (`*`) and numbers (`1.`) get rendered as nicely bulleted/numbered lists.

* Math in LaTeX synax is rendered nicely. For our purposes, this is mostly useful for things like `$O(n \log n)$, $O(1)$, and $O(n^2)$`; the preceding snippet renders as $O(n \log n)$, $O(1)$, and $O(n^2)$.

* Images (e.g., for diagrams and such) can be embedded. Name your image `PXX_YY.png` where XX is the lecture number and YY is the problem number (zero padded if necessary). Make sure the image is in the correct `P##` folder and include it in the markdown file using the following syntax:

```
![](image_name.png)
```
