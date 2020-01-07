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

  <pre><code class="language-javascript">
    var editor = CodeMirror(document.body.getElementsByTagName("article")[0], {
      value: value,
      lineNumbers: true,
      mode: "pascal",
      keyMap: "sublime",
      autoCloseBrackets: true,
      matchBrackets: true,
      showCursorWhenSelecting: true,
      theme: "monokai",
      tabSize: 1,
      readOnly: true
    });

  </code></pre>



Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.

<img src="https://firebasestorage.googleapis.com/v0/b/unkriswina-informers.appspot.com/o/assets%2Fimg%2Fjavascript.jpg?alt=media&token=07e53a01-e07e-4d2c-b29f-0d6fcaa09dd3" class="img-fluid" />

Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.

  <pre><code class="language-javascript">
      /**
       * kita setting 4 buah postingan dalam 1 kali render page
       * Create posts pagination pages
       */
      const postsPerPage = 6;
      const numberOfPages = Math.ceil(posts.length / postsPerPage);

      Array.from({ length: numberOfPages }).forEach((_, index) => {
        const isFirstPage = index === 0;
        const currentPage = index + 1;

        // Skip first page because of index.js
        if (isFirstPage) return

        // kita buat halaman untuk template post-list
        createPage({
          path: ,
          component: templates.postList,
          context: {
            limit: postsPerPage,
            skip: index * postsPerPage,
            numberOfPages: numberOfPages,
            currentPage: currentPage,
          },
        });
      });

      // kita membuat halaman untuk untuk template page author-post, dimana page ini akan menampilkan bersadarkan author
      authors.forEach(author => {
        createPage({
          path: ,
          component: templates.authorPosts,
          context: {
            authorName: author.name,
            imageUrl: author.imageUrl 
          }
        });
      });
  </code></pre>


Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.Welcome to Code Blog, I hope you enjoy our content, Welcome to Code Blog, I hope you enjoy our content.
