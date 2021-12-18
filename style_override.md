---
title: megu_style_override
tags: 東雲めぐ
---
<style type="text/css">
	body    {
		background-color: #fffcef !important;
		background-image:
			radial-gradient( farthest-side circle at center top, #f8d74c 8%, transparent 0%),
			radial-gradient(farthest-side circle at center bottom, #f8d74c 8%, transparent 0%);
		background-size: 40px 40px;
		background-position: 0 0, 20px 20px;
	}
	a       { color: #737eae; }
	a:hover { color: #8ebfe7; }
    p       { padding: 0 1em;}
	hr      { background-color: #ef8589 !important; }
	#doc 	{ background-color: #fffcef !important; }
	#doc>ul	{ padding-left: 0; }
	#doc>ul>li {
		background-color: #fcfbf9;
		margin: 0.25em;
		padding: 0.25em 1em;
		list-style: none;
		border-radius: 0.25em;
		border-left: solid 0.25em #f18a5d;
	}
	.markdown-body>h1 {
		text-align: center;
		background-color: #ef8589;
		color: #fff;
		border-color :#f18a5d !important;
		margin: 0;
		padding: 0.5em 0;
		border-radius: 1em 1em 0.25em 0.25em;
	}
	.markdown-body>h2 {
		padding: 0.25em 1em;
		border-color :#f18a5d !important;
		border-left: solid 1em;
		border-radius: 0.25em 0 0 0.25em;
	} 
	.markdown-body>h2,
	.markdown-body>h3 { color: #f18a5d; }
	.ui-toc-label {
		background-color: #ef8589;
		color: #fff;
	}
	.ui-toc-label:hover {
		background-color: #ffa5a9;
		color: #fff;
	}
	.ui-toc-label:focus,
	.ui-toc-label:active:focus {
		background-color: #ffa5a9;
		color: #fff;
	}
	.ui-toc-label::after {
		content: "目次";
	}
</style>