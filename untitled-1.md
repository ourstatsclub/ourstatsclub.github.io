---
description: The following table shows the logical operators supported by R language.
---

# Logical Operators

The following table shows the logical operators supported by the R language. It is applicable only to vectors of type logical, numeric, or complex. All numbers greater than 1 are considered as logical value TRUE.

Each element of the first vector is compared with the corresponding element of the second vector. The result of the comparison is a Boolean value.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Operator</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">&amp;</td>
      <td style="text-align:left">It is called the element-wise Logical AND operator. It combines each element
        of the first vector with the corresponding element of the second vector
        and gives an output TRUE if both the elements are TRUE.</td>
      <td style="text-align:left">
        <p>
          <br />
        </p>
        <p><code>v &lt;- c(3,1,TRUE,2+3i)<br /></code>
        </p>
        <p><code>t &lt;- c(4,1,FALSE,2+3i)<br /></code>
        </p>
        <p><code>print(v&amp;t)<br /></code>
        </p>
        <p>it produces the following result &#x2212;
          <br />
        </p>
        <p><code>[1]  TRUE  TRUE FALSE  TRUE<br /></code>
        </p>
        <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">|</td>
      <td style="text-align:left">It is called the element-wise Logical OR operator. It combines each element
        of the first vector with the corresponding element of the second vector
        and gives an output TRUE if one of the elements is TRUE.</td>
      <td style="text-align:left">
        <p><code>v &lt;- c(3,0,TRUE,2+2i)<br /></code>
        </p>
        <p><code>t &lt;- c(4,0,FALSE,2+3i)<br /></code>
        </p>
        <p><code>print(v|t)<br /></code>
        </p>
        <p>it produces the following result &#x2212;
          <br />
        </p>
        <p><code>[1]  TRUE FALSE  TRUE  TRUE<br /></code>
        </p>
        <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">!</td>
      <td style="text-align:left">It is called Logical NOT operator. Takes each element of the vector and
        gives the opposite logical value.</td>
      <td style="text-align:left">
        <p><code>v &lt;- c(3,0,TRUE,2+2i)<br /></code>
        </p>
        <p><code>print(!v)<br /></code>
        </p>
        <p>it produces the following result &#x2212;
          <br />
        </p>
        <p><code>[1] FALSE  TRUE FALSE FALSE<br /></code>
        </p>
      </td>
    </tr>
  </tbody>
</table>

The logical operator && and \|\| considers only the first element of the vectors and gives a vector of a single element as output.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Operator</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">&amp;&amp;</td>
      <td style="text-align:left">Called Logical AND operator. Takes the first element of both the vectors
        and gives the TRUE only if both are TRUE.</td>
      <td style="text-align:left">
        <p><code>v &lt;- c(3,0,TRUE,2+2i)<br /></code>
        </p>
        <p><code>t &lt;- c(1,3,TRUE,2+3i)<br /></code>
        </p>
        <p><code>print(v&amp;&amp;t)<br /></code>
        </p>
        <p>it produces the following result &#x2212;
          <br />
        </p>
        <p><code>[1] TRUE<br /></code>
        </p>
        <p>&lt;code&gt;&lt;/code&gt;</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">||</td>
      <td style="text-align:left">Called Logical OR operator. Takes the first element of both the vectors
        and gives the TRUE if one of them is TRUE.</td>
      <td style="text-align:left">
        <p><code>v &lt;- c(0,0,TRUE,2+2i)<br /></code>
        </p>
        <p><code>t &lt;- c(0,3,TRUE,2+3i)<br /></code>
        </p>
        <p><code>print(v||t)<br /></code>
        </p>
        <p>it produces the following result &#x2212;
          <br />
        </p>
        <p><code>[1] FALSE<br /></code>
        </p>
        <p></p>
      </td>
    </tr>
  </tbody>
</table>

