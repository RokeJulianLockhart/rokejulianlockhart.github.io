---

#<table> <tr>
#    <th> Citations </th>
#    <td> <ol>
#        <li> <a href="https://gohugo.io/content-management/front-matter/#fields:~:text=a%20Page%20object.-,description,-(string)%20Conceptually%20different">                    Hugo Documentation </a> </li>
#        <li> <a href="https://gitlab.com/uramer/vscode-comments-as-markdown/-/issues/5#:~:text=there's%20no%20option%20to%20render%20the%20code%20in%20markdown%20frontmatter."> Visual Studio Code Markdown Comment Extension YAML Preamble Render Request </a> </li>
#    </ol> </td>
#</tr> </table>

title: "Repository Information"

  #<table><tr>
  #    <th> Information </th>
  #    <td> Defines the title of the content, because <code><h1></code>/<code>#</code> in the content doesn't affect the metadata. </td>
  #</tr></table>

subject: "Private documents owned and created by Roke Julian Lockhart."

  #<table><tr>
  #    <th> Information </th>
  #    <td> Defines the subject of the content. </td>
  #</tr></table>

lang: "`eng-GBR-oxendict`"

  #<table> <tr>
  #    <th> Information </th>
  #    <td> Defines the language of the content. </td>
  #</tr><tr>
  #    <th> Citations </th>
  #    <td> <ol>
  #        <li> <a href="https://github.com/mattcg/language-subtag-registry/blob/1e7d67e7f9646f47f0766a04b08522f7df59e932/data/json/registry.json#L334-L336:~:text=%22-,English,-%22">                            IANA Language Subtag Registry entry for English </a> </li>
  #        <li> <a href="https://github.com/mattcg/language-subtag-registry/blob/1e7d67e7f9646f47f0766a04b08522f7df59e932/data/json/registry.json#L76371-L76373:~:text=Oxford%20English%20Dictionary%20spelling"> IANA Language Subtag Registry entry for Oxford English Dictionary spelling </a> </li>
  #    </ol> </td>
  #</tr> </table>

author:

  #<table><tr>
  #    <th> Information </th>
  #    <td> Defines the authors. </td>
  #</tr></table>

  - name:  "[`{3rd: \"Beedell\", 1st: \"Roke\"}`{.JSON5}](https://wim.nl.tab.digital/apps/contacts/All%20contacts/e1f2ec5c-074e-4875-ac62-53ff24770ffa~contacts#:~:text=First-name-,Middle%20names,Surname,-Suffix)" # <table><tr><th> Information </th><td> Defines the name of the author. </td></tr></table>
    email: "[`ef4uf956@rokejulianlockhart.addy.io`](mailTo:ef4uf956@rokejulianlockhart.addy.io)"                                                                                                                     # <table><tr><th> Citation </th><td> <a href="https://app.addy.io/aliases/4c7718c1-0f47-429d-a6e5-235c15c68285/edit#:~:text=to%20your%20alias-,ef4uf956%40rokejulianlockhart.addy.io,-https%3A%2F%2Fgithub.com"> Addy.IO </a> </td></tr></table>
output:

  #<table><tr>
  #    <th> Information </th>
  #    <td> Specifies additional document output formats in Pandoc. </td>
  #</tr></table>

- html_document:

      #<table><tr>
      #    <th> Information </th>
      #    <td> Enables <code>.HTML</code> document output in Pandoc. </td>
      #</tr></table>

      number_sections: true

        #<table><tr>
        #    <th> Information </th>
        #    <td> Numbers sections at each table header. </td>
        #</tr></table>

      toc: true

        # <table><tr>
        #    <th> Information </th>
        #    <td> <code>true</code> enables the table of contents. </td>
        #</tr></table>

      toc_depth: 6

        # <table><tr>
        #    <th> Information </th>
        #    <td> <code>true</code> 6 is the maximum. </td>
        #</tr></table>

---

<!--
	```MD
	<!docType Markdown>
	```
-->

<!--
	<table><tr>
	<th> Citation </th>
	<td> <a href="https://github.com/microsoft/vscode/issues/216834#issue-2366955483"> StackOverflow </a> </td>
	</tr></table>
-->

<head>
	<meta charSet = "UTF-8">
</head>

<!--
	<table><tr>
	<th> Citation </th>
	<td> <a href="https://talk.commonmark.org/t/should-md-containing-html-tags-be-wrapped-in-html/4681?u=rokejulianlockhart"> StackOverflow </a> </td>
	</tr></table>
-->

<style>

	:root {
		--text-margin: 9.5px; /* VSC */
		--block-padding: 5px; /* VSC */
		--border: 1px solid #484848; /* VSC */
		--border-radius: 0px;
	}

	:is(H1) {
		font-size: 19.5px; /* 2em */
		padding-top: 1em;
	}

	:not(H1) {
		font-size: 13px; /* 1em */
	}

		/*
			<table><tr>
			<th> Information </th>
			<td> <a href="https://github.com/microsoft/vscode/issues/219520#issue-2383827208"> <code>github.com/microsoft/vscode/issues/219520</code> </a> </td>
			</tr></table>
		*/

	:is(H2, H3, H4, H5, H6, TH) {

		border-bottom: var(--border);

			/*
				<table><tr>
				<th> Citation </th>
				<td> <a href="https://stackoverflow.com/revisions/16073356/1#:~:text=h1%20%7B%20border%2Dbottom:%201px%20solid%20black%20%7D"> StackOverflow </a> </td>
				</tr></table>
			*/

		font-weight: bold;
	}

	:is(H1, H2, H3, H4, H5, H6, TH) {
		margin-top: 0;
		border-bottom: var(--border);
	}
	:is(div.block-indent) {
		margin-left: 2em;
		margin-bottom: 1em;
	}
	:is(TH) { margin-top: 1em; }
	:is(TH, TD) {
		border: var(--border)!important;
		border-collapse: collapse;
		padding-bottom: var(--block-padding)!important;
		padding-top: var(--block-padding)!important;
	}
	:is(pre, code) {
		border: var(--border)!important;
		border-radius: var(--border-radius)!important;
	}
	:is(blockQuote) {
		border: var(--border)!important;
		border-radius: var(--border-radius)!important;
	}

	:is(blockQuote) P { margin-bottom: 0px!important; }
	:is(blockQuote) {
		margin-bottom: var(--text-margin)!important;
		margin-top: var(--text-margin)!important;
		padding-bottom: var(--block-padding)!important;
		padding-top: var(--block-padding)!important;
	}

	:is(OL, UL) {

		/*
			#<!--
				```CSS
				list-style-position: outside;
				```
			#-->
		*/

		padding-left: 0em;

			/*
				<table><tr>
				<th> Citation </th>
				<td> <a href="https://stackoverflow.com/a/26213863/9731176"> StackOverflow </a> </td>
				</tr></table>
			*/

	}

	.hidden {

		visibility: collapse;
		display: none

			/*
				<table><tr>
				<th> Citation </th>
				<td> <a href="https://stackoverflow.com/revisions/45861734/1#:~:text=If%20you%20want%20to%20hide%20a%20row%20in%20a%20table%20you%20could%20just%20set%20display:%20none%20on%20it."> StackOverflow </a> </td>
				</tr></table>
			*/

	}
	:is(details) > summary:first-of-type { list-style-type: none; }
	:is(TR.child-row) TD { padding-left:20px; }
	:is(TR.child-row) TH { padding-left:20px; }

		/*
			<table><tr>
			<th> Citations </th>
			<td> <ol>
				<li> <a href="https://stackoverflow.com/questions/20687826/indenting-borders-for-table-row-tr#comment138668813_20687949"> Stack Overflow question. </a> </li>
				<li> <a href="https://stackoverflow.com/revisions/20687949/2"> Stack Overflow comment. </a> </li>
			</ol> </td>
			</tr></table>
		*/

</style>

<!--
	<table><tr>
	<th> Information </th>
	<td> <a href="https://gitlab.com/gitlab-org/gitlab/-/issues/462208#:~:text=GitLab%20Duo%20Chat-,Render%20disallowed%20HTML%20tags%20in%20the%20Markdown%20preview%20pane%20as%20code.,-Edit"> <code>https://gitlab.com/gitlab-org/gitlab/-/issues/462208</code> prevents this from being rendered in GitLab. </a> </td>
	</tr></table>
-->

<h1> Repository Information </h1> <div class="block-indent">

This is an experimentation.

</div>