---
layout: default
title: Welcome
---

{{ site.description }}

Classes are **Mondays** from **4:45pm&ndash;6:20pm** in LS G12, and are often open to non-enrolled students. See the [Schedule](schedule.html) and [Syllabus](syllabus.html) for more information.

<div class="notification is-usf-gold">
  <button class="delete"></button>
  We are now enrolling students in this course! If you are an incoming first-year CS major and are interested, please email Sophie at <a href="mailto:sjengle@cs.usfca.edu">sjengle@cs.usfca.edu</a>.
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
