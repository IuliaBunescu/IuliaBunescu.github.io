---
layout: page
title: Control Engineering Papers
permalink: /control-engineering-papers/
subtitle: Fractional-order control research highlights
wide-content: True
---

<p class="publication-intro">
	Fractional-order control has been the core of my undergraduate thesis and early research. Below are the two pieces that capture the journey from prototype algorithms to an industry-ready toolbox.
</p>

<div class="pub-grid">
	<article class="pub-card">
		<div class="pub-media" style="background-image: linear-gradient(135deg, rgba(100, 182, 255, 0.35), rgba(9, 11, 18, 0.75));"></div>
		<header class="publication-card__header">
			<span class="publication-card__label">Journal Article · 2023</span>
			<h2 class="publication-card__title">
				<a href="https://doi.org/10.3390/math11051097" target="_blank" rel="noopener noreferrer">
					A Novel Toolbox for Automatic Design of Fractional Order PI Controllers Based on Automatic System Identification from Step Response Data
				</a>
			</h2>
			<p class="publication-card__meta">Mathematics (MDPI) · Volume 11, Issue 5 · Open access DOI</p>
		</header>
		<div class="pub-body">
		<p class="pub-desc">
			Presents the AFOPI toolbox: an end-to-end workflow that identifies process models from raw step-response data, tunes fractional-order PI controllers, and delivers hardware-ready discrete implementations.
		</p>
		<ul class="publication-card__highlights">
			<li>Automates SOPDT model estimation from noisy experimental measurements.</li>
			<li>Maximizes robustness by scanning the fractional order that yields the highest gain margin.</li>
			<li>Validates the discrete controller on a vertical take-off and landing platform with repeatable tracking performance.</li>
		</ul>
		<p class="publication-card__links">
			<a class="pub-link" href="https://www.mdpi.com/2227-7390/11/5/1097/pdf" target="_blank" rel="noopener noreferrer">Download the PDF</a>
			<a class="pub-link" href="https://www.mdpi.com/2227-7390/11/5/1097" target="_blank" rel="noopener noreferrer">Read on MDPI</a>
		</p>
		</div>
	</article>

	<article class="pub-card">
		<div class="pub-media" style="background-image: linear-gradient(135deg, rgba(255, 118, 195, 0.35), rgba(9, 11, 18, 0.75));"></div>
		<header class="publication-card__header">
			<span class="publication-card__label publication-card__label--conference">Conference Short Paper · 2022</span>
			<h2 class="publication-card__title">
				<a href="http://hdl.handle.net/11652/4116">
					Automatic System Identification and Fractional Order Controller Design from Step Response Data
				</a>
			</h2>
			<p class="publication-card__meta">Conference short paper introducing the AFOPI concept and early validation</p>
		</header>
		<div class="pub-body">
		<p class="pub-desc">
			Distills the foundational ideas behind AFOPI into a concise, conference-ready format—bridging undergraduate research with applied industrial control problems.
		</p>
		<ul class="publication-card__highlights">
			<li>Summarizes the automatic identification routine that removes manual tuning heuristics.</li>
			<li>Shares preliminary fractional-order controller experiments that informed the journal manuscript.</li>
			<li>Clarifies implementation trade-offs for practitioners with limited fractional calculus background.</li>
		</ul>
		<p class="publication-card__links">
			<a class="pub-link" href="http://hdl.handle.net/11652/4116" target="_blank" rel="noopener noreferrer">View the abstract</a>
		</p>
		</div>
	</article>
</div>
