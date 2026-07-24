Remove the temp html files for berita, event, and pengumunan when it is needed

Add this to the index.html when the Berita Page is needed:

  <!-- ══════════════════════════════════════
       BERITA SECTION
  ══════════════════════════════════════ -->
  <section class="berita">

    <!-- Header row -->
    <div class="berita__header">
      <h2 class="berita__heading">BERITA</h2>
      <a class="berita__btn" href="berita.html">BACA BERITA LAINNYA <span>&rarr;</span></a>
    </div>

    <!-- Grid: featured left + 3 small right -->
    <div class="berita__grid" id="beritaGrid">

      <!-- FEATURED ARTICLE (large, left column) -->
      <article class="berita__featured">
        <div class="berita__featured-image">
          <img src="images/berita_1.jpg" alt="Berita 1" />
        </div>
        <div class="berita__featured-body">
          <div class="berita__tags">
            <span class="berita__tag">Kategori</span>
          </div>
          <h3 class="berita__featured-title">Judul Berita Adalah Sebagai Berikut, Ini Adalah Isi Berita Nya Yaitu Sebagai</h3>
          <a class="berita__arrow-btn" href="#">&rarr;</a>
        </div>
      </article>

      <!-- SMALL ARTICLES (right column, stacked) -->
      <div class="berita__list">

        <!-- Small article 1 -->
        <article class="berita__item">
          <div class="berita__item-image">
            <img src="images/berita_2.jpg" alt="Berita 2" />
          </div>
          <div class="berita__item-body">
            <h4 class="berita__item-title">Judul Berita Adalah Sebagai Berikut, Ini Adalah Isi Berita Nya Yaitu Sebagai</h4>
            <div class="berita__tags">
              <span class="berita__tag">Kategori</span>
            </div>
            <a class="berita__arrow-btn" href="#">&rarr;</a>
          </div>
        </article>

        <hr class="berita__divider" />

        <!-- Small article 2 -->
        <article class="berita__item">
          <div class="berita__item-image">
            <img src="images/berita_3.jpg" alt="Berita 3" />
          </div>
          <div class="berita__item-body">
            <h4 class="berita__item-title">Judul Berita Adalah Sebagai Berikut, Ini Adalah Isi Berita Nya Yaitu Sebagai</h4>
            <div class="berita__tags">
              <span class="berita__tag">Kategori</span>
              <span class="berita__tag">Kategori</span>
            </div>
            <a class="berita__arrow-btn" href="#">&rarr;</a>
          </div>
        </article>

        <hr class="berita__divider" />

        <!-- Small article 3 -->
        <article class="berita__item">
          <div class="berita__item-image">
            <img src="images/berita_4.jpg" alt="Berita 4" />
          </div>
          <div class="berita__item-body">
            <h4 class="berita__item-title">Judul Berita Adalah Sebagai Berikut, Ini Adalah Isi Berita Nya Yaitu Sebagai</h4>
            <div class="berita__tags">
              <span class="berita__tag">Kategori</span>
            </div>
            <a class="berita__arrow-btn" href="#">&rarr;</a>
          </div>
        </article>

      </div><!-- /.berita__list -->

    </div><!-- /.berita__grid -->

  </section>