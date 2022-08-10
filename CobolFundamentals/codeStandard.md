---
layout: default
title: Coding Standards
parent: Cobol Fundamentals
nav_order: 7
---

## Comments
<hr class="hr-no-bottom-margin"/>

- Comments must be added to each program and each section when changes are made
- All comments must include:
  - Change order
  - Brief description of the change
  - Date and initials of the programmer who made the change
  
<table>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/20475336/183905021-90f9fc4f-2ccf-4e0d-bb53-28724022afbf.png">
    </td>
  </tr>
</table>

## ID Division

<table>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/20475336/183906049-4a14d445-68cc-45d8-8a83-a7544c478321.png">
    </td>
  </tr>
</table>

## Data Division

- Levels are generally 01, 02, 04, 06, etc …
- Local variables are generally prefixed with W-
- Host variables are generally prefixed with V-
- Array subscripts are defined using X1 through X99 variables

## Procedure Division
