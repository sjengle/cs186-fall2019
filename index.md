---
layout: default
title: Welcome
---

{{ site.description }}

Classes are **Mondays** from **4:45pm&ndash;6:20pm** in LS G12, and are often open to non-enrolled students. See the [Schedule](schedule.html) and [Syllabus](syllabus.html) for more information.

<div class="notification is-usf-green">
  <button class="delete"></button>
  The course is full but there is a waiting list. If you are an incoming first-year CS major and are interested in joining the waiting list, please email Sophie at <a href="mailto:sjengle@cs.usfca.edu">sjengle@cs.usfca.edu</a>.
</div>

<script>
document.addEventListener('DOMContentLoaded', () => {
  (document.querySelectorAll('.notification .delete') || []).forEach(($delete) => {
    $notification = $delete.parentNode;
    $delete.addEventListener('click', () => {
      $notification.parentNode.removeChild($notification);
    });
  });
});
</script>
