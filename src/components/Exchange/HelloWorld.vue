<template>
  <div class="hello">
    <p>
      For a guide and recipes on how to configure / customize this project,
      <br />check out the
      <a
        href="https://cli.vuejs.org"
        target="_blank"
        rel="noopener"
      >vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>

    <header>
      <div class="container flex">
        <div class="nav-toggle mobile-only">
          <a href="#" class="burger-button" title="Mobile Navigation Menu"></a>
          <div class="submenu" style="display: none;">
            <div class="mobile">
              <ul id="main-menu-mobile" class="menu" style="display: none;">
                <li
                  id="menu-item-32209"
                  class="mobile-only menu-item menu-item-type-custom menu-item-object-custom current-menu-item current_page_item menu-item-32209"
                >
                  <a href="/" aria-current="page">HOME</a>
                </li>
                <li
                  id="menu-item-33465"
                  class="featured menu-item menu-item-type-custom menu-item-object-custom menu-item-33465"
                >
                  <a href="/podcast">Podcasts</a>
                </li>
                <li
                  id="menu-item-30966"
                  class="featured menu-item menu-item-type-custom menu-item-object-custom menu-item-30966"
                >
                  <a href="https://whole30.com/books">Books</a>
                </li>
                <li
                  id="menu-item-32009"
                  class="featured menu-item menu-item-type-custom menu-item-object-custom menu-item-32009"
                >
                  <a href="/whole30-approved">Whole30 Approved</a>
                </li>
                <li
                  id="menu-item-32035"
                  class="featured menu-item menu-item-type-custom menu-item-object-custom menu-item-32035"
                >
                  <a href="https://forum.whole30.com/">Forum</a>
                </li>
                <li
                  id="menu-item-32036"
                  class="featured menu-item menu-item-type-custom menu-item-object-custom menu-item-32036"
                >
                  <a
                    href="https://realplans.com/whole30/?AFFID=255802&amp;utm_source=whole30.com&amp;utm_medium=affiliate&amp;utm_campaign=Whole%2030%20Real%20Plans%20Affiliate%20Marketing&amp;utm_content=Whole30%20nav%20bar%20The%20Whole%2030%20menu%20item%20Meal%20Plans%20sub%20item%20text%20link&amp;_ga=2.128213132.1400853707.1553702547-1895853288.1546796398"
                  >Meal Plans</a>
                </li>
                <li
                  id="menu-item-30964"
                  class="menu-item menu-item-type-custom menu-item-object-custom menu-item-30964"
                >
                  <a
                    target="_blank"
                    rel="noopener noreferrer"
                    href="https://coach.whole30.com/"
                  >Coaches</a>
                </li>
                <li
                  id="menu-item-30965"
                  class="menu-item menu-item-type-custom menu-item-object-custom menu-item-30965"
                >
                  <a
                    target="_blank"
                    rel="noopener noreferrer"
                    href="https://www.wholemamasclub.com/"
                  >Mamas</a>
                </li>
                <li
                  id="menu-item-33069"
                  class="footer-link featured menu-item menu-item-type-custom menu-item-object-custom menu-item-33069"
                >
                  <a href="/pdf-downloads">PDF Resources</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="logo">
          <a href="https://whole30.com" class="mainlogo">
            <img
              src="https://whole30.com/wp-content/themes/whole30/images/logo-whole30.gif"
              alt="Whole30 Logo"
              class="main-logo"
            />
          </a>
        </div>
        <div class="search-toggle mobile-only">
          <a href="#" class="search-button" title="Mobile Search Button"></a>
        </div>
        <div class="nav desktop-only">
          <nav>
            <div class="menu-main-menu-container">
              <ul id="menu-main-menu" class="menu">
                <li
                  class="mobile-only menu-item menu-item-type-custom menu-item-object-custom current-menu-item current_page_item menu-item-32209"
                >
                  <a href="/" aria-current="page">HOME</a>
                </li>
                <li
                  class="featured menu-item menu-item-type-custom menu-item-object-custom menu-item-33465"
                >
                  <a href="/podcast">Podcasts</a>
                </li>
                <li
                  class="featured menu-item menu-item-type-custom menu-item-object-custom menu-item-30966"
                >
                  <a href="https://whole30.com/books">Books</a>
                </li>
                <li
                  class="featured menu-item menu-item-type-custom menu-item-object-custom menu-item-32009"
                >
                  <a href="/whole30-approved">Whole30 Approved</a>
                </li>
                <li
                  class="featured menu-item menu-item-type-custom menu-item-object-custom menu-item-32035"
                >
                  <a href="https://forum.whole30.com/">Forum</a>
                </li>
                <li
                  class="featured menu-item menu-item-type-custom menu-item-object-custom menu-item-32036"
                >
                  <a
                    href="https://realplans.com/whole30/?AFFID=255802&amp;utm_source=whole30.com&amp;utm_medium=affiliate&amp;utm_campaign=Whole%2030%20Real%20Plans%20Affiliate%20Marketing&amp;utm_content=Whole30%20nav%20bar%20The%20Whole%2030%20menu%20item%20Meal%20Plans%20sub%20item%20text%20link&amp;_ga=2.128213132.1400853707.1553702547-1895853288.1546796398"
                  >Meal Plans</a>
                </li>
                <li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-30964">
                  <a
                    target="_blank"
                    rel="noopener noreferrer"
                    href="https://coach.whole30.com/"
                  >Coaches</a>
                </li>
                <li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-30965">
                  <a
                    target="_blank"
                    rel="noopener noreferrer"
                    href="https://www.wholemamasclub.com/"
                  >Mamas</a>
                </li>
                <li
                  class="footer-link featured menu-item menu-item-type-custom menu-item-object-custom menu-item-33069"
                >
                  <a href="/pdf-downloads">PDF Resources</a>
                </li>
              </ul>
            </div>
          </nav>
        </div>
        <div class="social desktop-only">
          <ul class="social spriteset">
            <li>
              <a title="Facebook Link" target="_blank" href="https://facebook.com/whole30"></a>
            </li>
            <li>
              <a title="Twitter Link" target="_blank" href="https://twitter.com/whole30"></a>
            </li>
            <li>
              <a title="Instagram Link" target="_blank" href="https://instagram.com/whole30"></a>
            </li>
            <li>
              <a title="Pinterest Link" target="_blank" href="https://www.pinterest.ph/whole30/"></a>
            </li>
          </ul>
        </div>
        <div class="search desktop-only">
          <form role="search" method="get" class="search-form" action="https://whole30.com/">
            <label>
              <span class="screen-reader-text">Search for:</span>
              <input type="search" class="search-field" placeholder="Search …" value name="s" />
            </label>
            <input type="submit" class="search-submit" value="Search" />
          </form>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
