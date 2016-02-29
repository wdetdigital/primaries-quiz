# primaries-quiz
A Q & A quiz created using only HTML5/CSS3, so it's simple to use with your text editor.

HTML5 `<article>` and `<section>` elements form a vertical accordion layout for a series of questions, while CSS3's `:target` selector lets us hide and reveal the answers.

## In action
See the post <a href="http://wdet.org/posts/2016/02/29/82585-presidential-primaries-wdets-quiz/">Presidential Primaries: WDET's Quiz</a>, part of the station's 2016 Elections: Issues & Candidates series.

We used <a href="http://soundcite.knightlab.com/">SoundCiteJS</a> to include audio answers, or you can click the question to expand the transcript.

## Make your own
This repo includes two files: the source code and content to create WDET's primaries quiz in `primaries-quiz.html`; and, the simplified file `quiz-template.html` that you can fill with your own content. 

WDET's regular workflow involves using CKEditor to create and manage posts, so we've kept this quiz simple and compatible by not including any external Javascript or jQuery. 

If you're also working in a text editor, just copy everything between `<style>...</style>` and `<article>...</article>` from `quiz-template` and paste into your source. 

Plan to inherit most styles from your site and make custom adjustments to the height of your question and answer sections as needed to best display your content.


