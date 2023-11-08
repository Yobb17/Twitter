# Twitter
Twitter
<div id="myModal" class="modal fade" tabindex="-1" role="dialog" aria-hidden="true">
    ...
    <select id="mySelect2">
        ...
    </select>
    ...
</div>

...

<script>
    $('#mySelect2').select2({
        dropdownParent: $('#myModal')
    });
</script>
