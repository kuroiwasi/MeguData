---
title: megu_style_override
tags: 東雲めぐ
---
<style type="text/css">
	@media all {
		body    {
			background-color: #fffcef !important;
			background-image:
				radial-gradient( farthest-side circle at center top, #f8d74c 8%, transparent 0%),
				radial-gradient(farthest-side circle at center bottom, #f8d74c 8%, transparent 0%);
			background-size: 40px 40px;
			background-position: 0 0, 20px 20px;
		}
		.markdown-body a       { color: #737eae !important; }
		.markdown-body a:hover { color: #8ebfe7 !important; }
		p       { padding: 0 1em;}
		hr      { background-color: #ef8589 !important; }
		strong:not(a>strong)  { color: #f18a5d !important; }
		small:not(a>small) {
			color: #cdcdcd !important;
			padding : 0 1em;
		}
		#doc 	{ background-color: #fffcef !important; }
		.markdown-body ul	{ padding-left: 0 !important; }
		.markdown-body li {
			background-color: #fcfbf9 !important;
			margin: 0.25em;
			padding: 0.25em 1em;
			list-style: none;
			border-radius: 0.25em;
		}
		li::marker {
			content: none !important;
		}
		div:nth-child(1 of .embed-note)>ul>li {
			border-left: solid 0.25em #ffcdc7;
		}
		div:nth-child(2 of .embed-note)>ul>li {
			border-left: solid 0.25em #b1f0d1;
		}
		div:nth-child(3 of .embed-note)>ul>li {
			border-left: solid 0.25em #cfe8ff;
		}
		.markdown-body h1 {
			text-align: center;
			background-color: #ef8589 !important;
			color: #fff !important;
			border-color :#f18a5d !important;
			margin: 0;
			padding: 0.5em 0;
			border-radius: 1em 1em 0.25em 0.25em;
		}
		.markdown-body h2 {
			padding: 0.25em 1em;
			border-color :#f18a5d !important;
			border-left: solid 1em;
			border-radius: 0.25em 0 0 0.25em;
		} 
		.markdown-body h2,
		.markdown-body h3 { color: #f18a5d !important; }
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
		.fa-user:before {
			content: "\f16a";
		}
	}
	@media print {
		#meta-title-tags {
			page-break-inside: none !important;
			display: none !important;
		}
		#doc 	{ padding-top: unset; }
		div:nth-child(1 of .embed-note) {
			page-break-inside: auto !important;
		}
		small:not(a>small) *, .fa-user:before {
			color: #cdcdcd !important;
		}
		h1 span{
			color: #fff !important;
		}
	}
</style>