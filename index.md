---
layout: default
title: Welcome
---

{{ site.description }}

Classes are **Mondays** from **4:45pm&ndash;6:20pm** in LS G12, and are often open to non-enrolled students. See the [Schedule](schedule.html) and [Syllabus](syllabus.html) for more information.

<div class="notification is-usf-green">
  <button class="delete"></button>
  <p>This course is funded by under <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1833718">NSF Grant No. 1833718</a>. As part of grant expectations, an external evaluation of project usefulness and impact will be conducted by <a href="http://smartstart-er.com/">SmartStart Evaluation and Research</a>. They will contact you to participate in one or more surveys.</p>

  <p><strong>All participants are requested to participate in the project evaluation.</strong> These surveys are to evaluate our program (the course) and not you (the student), and will not impact your grades in any way. See the <a href="syllabus.html#evaluation">Syllabus</a> for details.</p>
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
