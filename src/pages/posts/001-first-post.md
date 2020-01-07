---
title: 'First Post - Introduction'
date: 2019-12-19 13:06:42
author: 'Umbu Rambu'
image: ../../images/javascript.jpg
tags:
  - design
  - tutorials
---

 

<style>
  .CodeMirror {border-top: 1px solid #eee; border-bottom: 1px solid #eee; line-height: 1.3; height: 500px}
  .CodeMirror-linenumbers { padding: 0 8px; }
</style>
 
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.

<div id="code1"></div>
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
<div id="code2"></div>

<img src="https://firebasestorage.googleapis.com/v0/b/unkriswina-informers.appspot.com/o/assets%2Fimg%2Fjavascript.jpg?alt=media&token=07e53a01-e07e-4d2c-b29f-0d6fcaa09dd3" class="img-fluid" />

Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.


Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.

<!-- <script async defer type="text/javascript" src="https://firebasestorage.googleapis.com/v0/b/unkriswina-informers.appspot.com/o/assets%2Fjs%2Ffirst-post.js?alt=media&token=b31c13c0-0790-48fd-855d-ce87cd0a5092"> </script> -->

<script>
  biarkan code1 = `
    / **
     * Kita mengatur 4 buah postingan dalam 1 kali render page
     * Buat halaman halaman pagination
     * /
    const postsPerPage = 6;
    const numberOfPages = Math.ceil (posts.length / postsPerPage);

    Array.from ({length: numberOfPages}). ForEach ((_, index) => {
      const isFirstPage = index === 0;
      const currentPage = indeks +1;

      // Lewati halaman pertama karena index.js
      if (isFirstPage) kembali

      // kita buat halaman untuk template post-list
      membuat halaman({
        jalan:,
        komponen: templates.postList,
        konteks: {
          batas: postsPerPage,
          lewati: index * postsPerPage,
          numberOfPages: numberOfPages,
          currentPage: currentPage,
        },
      });
    });

    // kita membuat halaman untuk untuk halaman template penulis-posting, dimana halaman ini akan menampilkan penulis bersadarkan
    author.forEach (author => {
      membuat halaman({
        jalan:,
        komponen: templates.authorPosts,
        konteks: {
          authorName: author.name,
          imageUrl: author.imageUrl 
        }
      });
    });
   `;
  
  biarkan code2 = `
    var editor = CodeMirror (document.body.getElementsByTagName ("article") [0], {
      nilai: nilai,
      lineNumber: true,
      mode: "pascal",
      keyMap: "luhur",
      autoCloseBrackets: true,
      matchBrackets: true,
      showCursorWhenSelecting: true,
      tema: "monokai",
      tabSize: 1,
      readOnly: true
    });

  `
  biarkan editorCode1 = CodeMirror (document.getElementById ('code1'), {
    nilai: code1,
    lineNumber: true,
    mode: "javascript",
    keyMap: "luhur",
    autoCloseBrackets: true,
    matchBrackets: true,
    showCursorWhenSelecting: true,
    tema: "monokai",
    tabSize: 1,
    readOnly: true
  });

   biarkan editorCode2 = CodeMirror (document.getElementById ('code2'), {
    nilai: code2,
    lineNumber: true,
    mode: "javascript",
    keyMap: "luhur",
    autoCloseBrackets: true,
    matchBrackets: true,
    showCursorWhenSelecting: true,
    tema: "monokai",
    tabSize: 1,
    readOnly: true
  }); 
</script>