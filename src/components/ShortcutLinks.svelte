<script lang="ts">
</script>

<style>
  ul {
    position: absolute;
    padding: 0;
    left: 50%;
    top: -100%;
  }
  ul > li {
    background-color: white;
    margin-left: -50%;
    padding: 0;
    text-align: center;
    list-style: none;
  }
  li > a {
    width: 100%;
    height: 100%;
    padding: 0.5rem;
    text-decoration: none;
    display: block;
    box-sizing: border-box;
  }
  ul:focus-within {
    top: 0;
  }
</style>

<ul id="shotcuts">
  <li><a href="#navigation">Go to navigation</a></li>
  <li><a href="#main-content">Go to main content</a></li>
</ul>
