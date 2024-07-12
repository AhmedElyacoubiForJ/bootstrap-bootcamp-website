[Bootstrap 5 Crash Course | Website Build & Deploy](https://www.youtube.com/watch?v=4sosXZsdy-s)
38:43 / 1:18:47
[Bootstrap Docs](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

[Input group](https://getbootstrap.com/docs/5.3/forms/input-group/)

[Cards](https://getbootstrap.com/docs/5.3/components/card/)

[Bootstrap Icons](https://blog.getbootstrap.com/2021/01/07/bootstrap-icons-1-3-0/)

[Accordion](https://getbootstrap.com/docs/5.3/components/accordion/)

[unDraw](https://undraw.co/illustrations)

> A Bootstrap row can hold a maximum of 12 columns due to  its 12-column grid system.
>
> **In these code snippet**
>
> We have a row with 6 columns (col-md-6) 
> and another with 3 columns (col-lg-3).
>
> To maintain the 12-column limit, we can add another 3 columns to the row with 6 columns.

```html
<div class="row">
  <div class="col-md-6">
    <!-- Content for the first column -->
  </div>
  <div class="col-md-3">
    <!-- Content for the second column -->
  </div>
  <div class="col-md-3">
    <!-- Content for the third column -->
  </div>
</div>
´´´