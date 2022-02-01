Here you can find all of the icons provided by <i>icon lab</i>.<br/>
You can upload your own icon here without of any fees.

If you can please add attribution to the following
<a href="/LICENSE">License</a>, It will be great appreciation
for us to work more and it will also help to increase your ranking
of visibility in search engines.

<h2> Search...</h2>
<input type="text" id="myInput" onkeyup="find()" placeholder="Search for icons..">
<ul style="list-style-type:none;" id="listing" >

<li><a>Alarm</a></li>
<li><a>Alien<a></li>
<li><a>Angle</a></li>
<li><a>Double Angle</a></li>
<li><a>Arrow</a></li>
<li><a>Backspace</a></li>
<li><a>Bag</a></li>
<li><a>Battery</a></li>
<li><a>Clock</a></li>
<li><a>Coffee</a></li>
<li><a>Home</a></li>
<li><a>Location</a></li>
<li><a>Save</a></li>
<li></li>

</ul>

<script>
function find() {
  // Declare variables
  var input, filter, ul, li, a, i, txtValue;
  input = document.getElementById('myInput');
  filter = input.value.toUpperCase();
  ul = document.getElementById("listing");
  li = ul.getElementsByTagName('li');

  // Loop through all list items, and hide those who don't match the search query
  for (i = 0; i < li.length; i++) {
    a = li[i].getElementsByTagName("a")[0];
    txtValue = a.textContent || a.innerText;
    if (txtValue.toUpperCase().indexOf(filter) > -1) {
      li[i].style.display = "";
    } else {
      li[i].style.display = "none";
    }
  }
}
</script>
