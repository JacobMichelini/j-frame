# j-frame
A light and flexible custom site framework built using flexbox/scss variables to speed up the layout process on new sites 

- A Section is a single row

- Sections may be subdivided into Sub-Sections

- Sub-Section width begins responsively equal, can be manipulated by adding .x2-width, .x3-width, etc type utility classes (making the Sub-Section 2x and 3x wider than the other Sub-Sections respectively).

- The entire structure can be nested, but Sub-Sections must always be contained directly by a Section.

```
<div class="section">

	<div class="sub-section x2-width">
		<div class="section">

			<div class="sub-section">
			content
			</div>

			<div class="sub-section">
			content
			</div>	

		</div>
	</div>

	<div class="sub-section">
	content
	</div>

	<div class="sub-section">
	content
	</div>
</div>
```

- All layout moves to single column at a customizable breakpoint