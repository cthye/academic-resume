---
# An instance of the Blank widget with a Gallery page element.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: markdown

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Gallery
subtitle: I also learn sketching in my spare time

design:
  columns: '3'
---

<!-- {{< gallery album="demo" >}} -->

<table>
  <tr>
    <!-- First row, first column -->
    <td>
      <img src="../post/getting-started/featured.jpg">
    </td>
    <!-- First row, second column -->
    <td>
      <img src="../post/getting-started/featured.jpg">
    </td>
  </tr>
  <tr>
    <!-- Second row, first column -->
    <td>
      <img src="../post/getting-started/featured.jpg">
    </td>
    <!-- Second row, second column -->
    <td>
      <img src="../post/getting-started/featured.jpg">
    </td>
  </tr>
</table>
<!-- End of the table -->
